# 🌀 物理海洋：波浪理论专题

波浪是海洋中最直观的动力现象，其本质是能量在水介质中的传递。

## 1. 规则波 (Regular Waves)
规则波具有单一的频率、振幅和波长，通常用正弦或余弦函数描述。

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
</div>
</details>

**核心公式：**
* **波速 (c)**：c = L / T
* **深水波波速**：c = gT / 2π (约等于 1.56T)

---

## 2. 不规则波 (Irregular Waves)
实际海面是由无数不同方向、频率和振幅的规则波叠加而成的。

### 统计特征
由于海面的随机性，我们通常使用统计值来描述：
* **有效波高 (Hs)**：将波高按从大到小排列，取前 1/3 个波高的平均值。
* **谱分析**：利用 P-M 谱或 JONSWAP 谱来描述能量在不同频率上的分布。

> **仿真进阶**：不规则波模拟器正在开发中，它将模拟多个正弦波的线性叠加。



| [🧪 海洋化学](biochem-chem.md) | [🐟 海洋生物](biochem-bio.md) | [🏠 返回首页](/) |
