# 🌀 物理海洋：波浪理论专题

波浪是海洋中最直观的动力现象。本模块通过交互仿真，带你理解从规则波到随机海面的演变。

## 1. 规则波 (Regular Waves)
规则波具有固定的频率、振幅和波长，是研究复杂波浪的基础。

<details>
<summary><b>🛠️ 开启：规则波交互仿真</b></summary>
<br>
<div class="sim-container" style="background: rgba(255,255,255,0.05); padding: 20px; border-radius: 15px; border: 1px solid #00d4ff33;">
  <canvas id="waveChart" width="400" height="180"></canvas>
  <div class="sim-controls" style="display: flex; gap: 15px; margin-top: 15px; justify-content: center; align-items: center; flex-wrap: wrap;">
    <button id="toggleBtn" class="sim-btn">停止/开始</button>
    <label>波高 (H): <input type="range" id="amp" min="1" max="10" value="5"></label>
    <label>周期 (T): <input type="range" id="period" min="1" max="5" step="0.1" value="2"></label>
  </div>
  <p style="font-size:0.8em; color:#888; text-align:center; margin-top:10px;">提示：光标悬停在波浪线上可查看各点的实时高度数据</p>
</div>
</details>

**核心物理量：**
* **波速 (c)**：单位时间内波形传播的距离。公式：c = L / T。
* **深水波特性**：当水深大于半个波长时，波速主要由周期决定。

---

## 2. 不规则波 (Irregular Waves)
实际海面是由无数不同波长、方向和振幅的规则波线性叠加而成的随机场。

### 描述方式
由于其随机性，我们通常使用统计学方法：
* **有效波高 (Hs)**：将波高按从大到小排列，取前 1/3 个波高的平均值。
* **波谱分析**：描述能量在不同频率上的分布，如经典的 P-M 谱。


---
| [🧪 海洋化学](biochem-chem.md) | [🐟 海洋生物](biochem-bio.md) | [🏠 返回首页](/) |
