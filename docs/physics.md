# 🌀 物理海洋：波浪实验室

本实验室专注于海水的动力学机制，通过仿真与理论结合，探索从规则波到随机海面的演化。

## 🔬 核心仿真模块
> 请选择你想进行的实验：

* [**规则波仿真 (Regular Wave)**](#规则波实验台) —— 探索正弦波的振幅、周期与波速关系。
* [**不规则波分析 (Irregular Wave)**](#不规则波理论) —— 理解海面的随机性与谱分析。

---

## 🌊 规则波实验台
<details open>
<summary><b>点击收起/展开仿真器</b></summary>
<div class="sim-container" style="background: rgba(255,255,255,0.05); padding: 20px; border-radius: 15px; border: 1px solid #00d4ff33;">
  <canvas id="waveChart" width="400" height="180"></canvas>
  <div class="sim-controls" style="display: flex; gap: 15px; margin-top: 15px; justify-content: center; align-items: center; flex-wrap: wrap;">
    <button id="toggleBtn" class="sim-btn">停止/开始</button>
    <label>波高: <input type="range" id="amp" min="1" max="10" value="5"></label>
    <label>周期: <input type="range" id="period" min="1" max="5" step="0.1" value="2"></label>
  </div>
</div>
</details>

**基础属性：**
* **波速 (c)**：c = L / T。
* **深水波**：当水深 d > L/2 时，波速不受水深影响。

---

## 🌪️ 不规则波理论
实际海面是由无数不同频率的规则波叠加而成的。
* [cite_start]**有效波高 (Hs)**：统计学中最常用的波高描述值 [cite: 1]。
* **能量谱**：描述能量随频率分布的函数（如 P-M 谱）。



---
| [🧪 前往海洋化学](biochem-chem.md) | [🏠 返回门户](/) |
