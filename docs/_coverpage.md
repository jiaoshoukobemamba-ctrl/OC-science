# OSDL Cover
## Ocean Science Digital Lab

<style>
  /* 全局封面背景与字体 */
  section.cover {
    background: radial-gradient(circle at center, #02203c 0%, #000c19 100%) !important;
    font-family: 'Segoe UI', Roboto, sans-serif !important;
  }
  
  /* 霓虹发光标题 */
  section.cover .anchor h1 { font-size: 4rem; font-weight: 300; color: #fff; margin: 0; }
  section.cover h1 span.glow-text {
    font-weight: 700;
    color: #00d4ff;
    text-shadow: 0 0 25px rgba(0, 212, 255, 0.6);
  }
  
  /* 嵌套卡片布局 Grid */
  .cover-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    width: 90%;
    max-width: 900px;
    margin-top: 50px;
  }
  
  /* 卡片基础样式 */
  .cover-card {
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(255,255,255,0.08);
    border-radius: 15px;
    padding: 30px;
    text-align: center;
    text-decoration: none !important;
    color: #fff !important;
    transition: all 0.3s ease;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  /* 卡片悬停增强视觉感 */
  .cover-card:hover {
    transform: translateY(-10px) scale(1.02);
    border-color: #00d4ff;
    background: rgba(0, 212, 255, 0.05);
    box-shadow: 0 15px 40px rgba(0, 212, 255, 0.2);
  }
  
  /* 卡片图标与标题 */
  .card-icon { font-size: 2.5rem; margin-bottom: 15px; }
  .cover-card h3 { color: #00d4ff; font-weight: 500; margin: 0 0 10px 0; }
  .cover-card p { font-size: 0.9rem; opacity: 0.7; line-height: 1.5; margin: 0; }

  /* 底部按钮 */
  section.cover a.cover-btn {
    margin-top: 60px;
    background: #00d4ff;
    color: #000;
    border-radius: 30px;
    padding: 12px 30px;
    font-weight: bold;
    text-decoration: none;
  }
</style>

# 海洋科学 <br> <span class="glow-text">数字实验室</span>

<div class="cover-grid">
  
  <a href="#/physics" class="cover-card">
    <div class="card-icon">🌀</div>
    <h3>物理海洋学</h3>
    <p>实时波浪模拟与动力学交互</p>
  </a>
  
  <a href="#/biochem-chem" class="cover-card">
    <div class="card-icon">🧪</div>
    <h3>生化与生命</h3>
    <p>碳循环泵机制与生命多样性</p>
  </a>
  
  <a href="#/geology" class="cover-card">
    <div class="card-icon">🌋</div>
    <h3>海洋地质学</h3>
    <p>板块扩张与海沟俯冲可视化</p>
  </a>

</div>

[进入实验室](#/README)
