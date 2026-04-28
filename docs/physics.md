# 🌀 物理海洋学系统

物理海洋学研究海水的运动规律及其物理性质。

## 1. 波浪理论 (Wave Dynamics)
波浪是能量穿越介质的体现。

<div class="sim-container">
  <h4>实时波浪交互模拟</h4>
  <canvas id="waveChart" width="400" height="150"></canvas>
  <div style="display:flex; gap:15px; font-size:0.8em;">
    <label>波高: <input type="range" id="amp" min="1" max="10" value="5"></label>
    <label>周期: <input type="range" id="freq" min="0.5" max="3" step="0.1" value="1"></label>
  </div>
</div>

### 核心知识点
- **艾里波 (Airy Wave)**：描述微幅波的基础方程。
- **波速公式**：$c = \sqrt{\frac{gL}{2\pi} \tanh(\frac{2\pi d}{L})}$

---

## 2. 温盐环流 (Thermohaline Circulation)
由密度梯度驱动的全球“输送带”。当海水结冰时，排出的盐分增加了剩余海水的密度，导致其下沉。

> [!TIP]
> **深入探索**：[点击了解北大西洋深层水的形成](physics-deep-water.md)

---

## 3. 海洋力学基础
- **科氏力 (Coriolis Force)**：由于地球自转产生的偏向力。
- **埃克曼抽吸 (Ekman Suction)**：风应力导致的海水垂直运动。

| [🧪 访问生化中心](biochem.md) | [🌋 访问地质中心](geology.md) | [🏠 返回主页](/) |
