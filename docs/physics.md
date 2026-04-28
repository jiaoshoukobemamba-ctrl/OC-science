# 🌀 物理海洋学系统

物理海洋学致力于研究海水的运动规律及其物理性质，从微小的波纹到横跨大洋的环流。

## 1. 波浪理论 (Wave Dynamics)
波浪是能量穿越流体介质的体现，其本质是能量的传递而非水质点的长距离搬运。

<details>
<summary><b>🛠️ 点击展开：实时波浪实验室 (含参数控制)</b></summary>
<br>
<div class="sim-container" style="background: rgba(255,255,255,0.05); padding: 20px; border-radius: 15px; border: 1px solid #00d4ff33;">
  <canvas id="waveChart" width="400" height="180"></canvas>
  
  <div class="sim-controls" style="display: flex; gap: 15px; margin-top: 15px; justify-content: center; align-items: center; flex-wrap: wrap;">
    <button id="toggleBtn" class="sim-btn" style="background: #00d4ff; color: #000; border: none; padding: 6px 15px; border-radius: 4px; cursor: pointer; font-weight: bold;">停止模拟</button>
    <label style="font-size: 0.9em;">波高 (Amplitude): <input type="range" id="amp" min="1" max="10" value="5"></label>
    <label style="font-size: 0.9em;">周期 (Period): <input type="range" id="period" min="1" max="5" step="0.1" value="2"></label>
  </div>
  <p style="font-size:0.8em; color:#888; text-align:center; margin-top:10px;">💡 提示：光标悬停在波浪线上可查看各点的实时高度数据</p>
</div>
</details>

### 核心知识点
* **艾里波 (Airy Wave)**：描述微幅波的基础方程，假设流体无粘性且不可压缩。
* **波速公式**：波长 ($L$)、周期 ($T$) 与水深 ($d$) 决定了波浪的传播速度：
    $$c = \sqrt{\frac{gL}{2\pi} \tanh\left(\frac{2\pi d}{L}\right)}$$



---

## 2. 温盐环流 (Thermohaline Circulation)
被称为全球“大洋输送带”，由海水的温度（Thermo）和盐度（Haline）引起的密度差异驱动。

* **下沉区**：主要发生在北大西洋和南极海域。
* **物理机制**：表层水变冷或因结冰排盐导致密度增大，垂直下沉至深海。

---

## 3. 科氏力与流体平衡
* **科氏力 (Coriolis Force)**：由于地球自转，物体在北半球向右偏，南半球向左偏。
* **地转流 (Geostrophic Current)**：压力梯度力与科氏力达到平衡时形成的稳定洋流。

| [🧪 访问生化中心](biochem.md) | [🌋 访问地质中心](geology.md) | [🏠 返回主页](/) |
