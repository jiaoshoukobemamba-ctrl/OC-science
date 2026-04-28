# 🌀 物理海洋：动力学交互实验室

> **实验室指引**：在左侧调节参数，实时观察物理环境对海浪形态的影响。

#### [physics-tabs:start]

##### **🌊 实时波浪仿真**
通过调整**振幅**和**频率**，观察水质点的运动包络线。

<div style="background: rgba(255,255,255,0.05); padding: 20px; border-radius: 15px; border: 1px solid #00d4ff;">
  <canvas id="waveChart" width="400" height="180"></canvas>
  <div style="margin-top: 15px; display: flex; gap: 20px; justify-content: center; font-size: 0.9em;">
    <label>振幅 (Amplitude): <input type="range" id="amplitude" min="1" max="10" value="5"></label>
    <label>频率 (Frequency): <input type="range" id="frequency" min="0.1" max="2" step="0.1" value="1"></label>
  </div>
</div>

**原理提示**：
- **振幅 ($A$)**：决定波浪的能量。
- **频率 ($f$)**：决定单位时间内波峰通过的数量。

##### **🌍 环流探索**
- [**风驱洋流**：表层系统的动力源](#/physics?id=wind-driven)
- [**温盐环流**：深海的热量输送带](#/physics?id=thermohaline)

#### [physics-tabs:end]

---
### 🔗 实验室导航
| [🧪 前往生化中心](#/biochem) | [🌋 前往地质考察](#/geology) | [🏠 返回主门户](/) |
