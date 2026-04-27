---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-area {
  display: flex;
  gap: 20px;
  align-items: flex-start;
  background: #fff;
  border: 1px solid #e2e8f0;
  border-radius: 8px;
  padding: 24px;
  margin-bottom: 24px;
  transition: box-shadow 0.2s;
}
.research-area:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.08);
}
.research-thumb {
  flex-shrink: 0;
  width: 160px;
  height: 125px;
  border-radius: 6px;
  overflow: hidden;
  background: #f0f4f8;
  border: 1px solid #e2e8f0;
}
.research-thumb img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.research-content {
  flex: 1;
  min-width: 0;
}
.research-area h3 {
  color: #2c5282;
  margin-top: 0;
  font-size: 1.15em;
  border-left: 4px solid #2c5282;
  padding-left: 12px;
}
.research-area p {
  color: #4a5568;
  font-size: 0.93em;
  line-height: 1.7;
}
.research-keywords {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin-top: 10px;
}
.research-kw {
  background: #ebf4ff;
  color: #2c5282;
  padding: 3px 10px;
  border-radius: 12px;
  font-size: 0.78em;
  font-weight: 600;
}
</style>

<h2 class="research-section-title" style="color: #1a365d; font-family: 'Source Serif 4', Georgia, serif; font-size: 1.35em; font-weight: 700; border-bottom: 2px solid #2c5282; padding-bottom: 8px; margin: 28px 0 16px 0;">Overview</h2>

<p class="lang-en">My research focuses on <b>intelligent monitoring and control of complex industrial processes</b>, with the goal of improving the safety, reliability, and intelligence of industrial systems. I develop theories and algorithms spanning three interconnected pillars:</p>

<p class="lang-zh">我的研究聚焦于<b>复杂工业过程的智能监控与控制</b>，致力于提升工业系统的安全性、可靠性与智能化水平。研究工作围绕以下三个相互关联的方向展开：</p>

<div class="research-area">
<div class="research-thumb"><img src="/images/research/research_1.png" alt=""></div>
<div class="research-content">
<h3 data-i18n-en="1. Data-Physics Hybrid Modeling for Complex Industrial Processes" data-i18n-zh="1. 复杂工业过程的数据-物理混合建模">1. Data-Physics Hybrid Modeling for Complex Industrial Processes</h3>
<p class="lang-en">I develop methods that fuse data-driven machine learning with first-principles knowledge to build high-accuracy, physically consistent models. Key contributions include incorporating mechanistic constraints into neural network architectures, multi-source data fusion with iterative optimization, knowledge transfer using causal reasoning, and constructing reliable transfer learning models grounded in domain knowledge. These methods have been applied to <strong>refinery digital twins</strong>, <strong>biofeedstock co-processing</strong>, and <strong>renewable CO2 tracking</strong>.</p>
<p class="lang-zh">我致力于将数据驱动的机器学习与第一性原理知识相融合，构建高精度、物理一致的模型。主要贡献包括：将机理约束嵌入神经网络结构、基于迭代优化的多源数据融合、利用因果推理的知识迁移，以及基于领域知识的可靠迁移学习模型。这些方法已成功应用于<strong>炼化数字孪生</strong>、<strong>生物质原料共处理</strong>以及<strong>可再生 CO₂ 追踪</strong>等场景。</p>
<div class="research-keywords">
<span class="research-kw" data-i18n-en="Soft Sensors" data-i18n-zh="软测量">Soft Sensors</span>
<span class="research-kw" data-i18n-en="Hybrid Modeling" data-i18n-zh="混合建模">Hybrid Modeling</span>
<span class="research-kw" data-i18n-en="Transfer Learning" data-i18n-zh="迁移学习">Transfer Learning</span>
<span class="research-kw" data-i18n-en="Physics-informed ML" data-i18n-zh="物理信息机器学习">Physics-informed ML</span>
<span class="research-kw" data-i18n-en="Digital Twins" data-i18n-zh="数字孪生">Digital Twins</span>
</div>
</div>
</div>

<div class="research-area">
<div class="research-thumb"><img src="/images/research/research_2.png" alt=""></div>
<div class="research-content">
<h3 data-i18n-en="2. Trustworthy Intelligent Monitoring and Fault Diagnosis" data-i18n-zh="2. 可信智能监控与故障诊断">2. Trustworthy Intelligent Monitoring and Fault Diagnosis</h3>
<p class="lang-en">I address the "black-box" bottleneck in industrial AI by developing interpretable and reliable monitoring systems. My work includes causal discovery algorithms (including a novel polynomial chaos framework published at <strong>ICLR, CVPR, AAAI 2026</strong>), virtual sample generation with causal learning, alarm sequence alignment and threshold optimization, and attack detection for cyber-physical systems using causal representations.</p>
<p class="lang-zh">针对工业人工智能中的"黑箱"瓶颈，我致力于构建可解释、可信赖的监控系统。研究工作包括：因果发现算法（含发表于 <strong>ICLR、CVPR、AAAI 2026</strong> 的新型多项式混沌框架）、基于因果学习的虚拟样本生成、报警序列对齐与阈值优化，以及基于因果表征的信息物理系统攻击检测。</p>
<div class="research-keywords">
<span class="research-kw" data-i18n-en="Causal Discovery" data-i18n-zh="因果发现">Causal Discovery</span>
<span class="research-kw" data-i18n-en="Process Monitoring" data-i18n-zh="过程监控">Process Monitoring</span>
<span class="research-kw" data-i18n-en="Alarm Management" data-i18n-zh="报警管理">Alarm Management</span>
<span class="research-kw" data-i18n-en="Polynomial Chaos" data-i18n-zh="多项式混沌">Polynomial Chaos</span>
<span class="research-kw" data-i18n-en="Interpretable AI" data-i18n-zh="可解释 AI">Interpretable AI</span>
</div>
</div>
</div>

<div class="research-area">
<div class="research-thumb"><img src="/images/research/research_3.png" alt=""></div>
<div class="research-content">
<h3 data-i18n-en="3. Learning-Based Industrial Control" data-i18n-zh="3. 基于学习的工业控制">3. Learning-Based Industrial Control</h3>
<p class="lang-en">I develop intelligent control strategies that integrate machine learning with classical control theory for complex industrial systems. My work spans model predictive control (MPC) enhanced by data-driven models, reinforcement learning (RL) for adaptive optimal control, as well as fault-tolerant and robust control under uncertain and changing operating conditions. These methods aim to achieve safe, efficient, and autonomous operation in real-world industrial environments.</p>
<p class="lang-zh">我致力于将机器学习与经典控制理论相结合，开发面向复杂工业系统的智能控制策略。研究涵盖基于数据驱动模型增强的模型预测控制（MPC）、面向自适应最优控制的强化学习（RL），以及不确定和时变工况下的容错控制与鲁棒控制。这些方法旨在实现真实工业环境中的安全、高效和自主运行。</p>
<div class="research-keywords">
<span class="research-kw" data-i18n-en="Model Predictive Control" data-i18n-zh="模型预测控制">Model Predictive Control</span>
<span class="research-kw" data-i18n-en="Reinforcement Learning" data-i18n-zh="强化学习">Reinforcement Learning</span>
<span class="research-kw" data-i18n-en="Fault-Tolerant Control" data-i18n-zh="容错控制">Fault-Tolerant Control</span>
<span class="research-kw" data-i18n-en="Robust Control" data-i18n-zh="鲁棒控制">Robust Control</span>
<span class="research-kw" data-i18n-en="Optimal Control" data-i18n-zh="最优控制">Optimal Control</span>
</div>
</div>
</div>

<h2 class="research-section-title" style="color: #1a365d; font-family: 'Source Serif 4', Georgia, serif; font-size: 1.35em; font-weight: 700; border-bottom: 2px solid #2c5282; padding-bottom: 8px; margin: 28px 0 16px 0;">Application Domains</h2>

<p class="lang-en">My research has been successfully deployed in real-world industrial scenarios:</p>
<p class="lang-zh">相关研究成果已在多个实际工业场景中成功落地：</p>

<ul class="lang-en">
<li><strong>Biopharmaceutical Manufacturing</strong>: Core participant in MIT/US FDA continuous mRNA manufacturing platform project</li>
<li><strong>Refinery Digital Twins</strong>: Developed soft measurement and big data analytics for UBC–Parkland Corporation, deployed in production</li>
<li><strong>Smart Energy Systems</strong>: Microgrid digital twin modeling and optimal control (NRC Canada)</li>
<li><strong>Healthcare</strong>: Real-time intelligent monitoring for emergency departments (Vancouver Coastal Health)</li>
<li><strong>Lithium-ion Battery Management</strong>: State of health estimation and capacity prediction</li>
<li><strong>AI-Accelerated Materials Discovery</strong>: Inverse design using machine learning (Mitacs)</li>
</ul>

<ul class="lang-zh">
<li><strong>生物制药</strong>：作为核心成员参与 MIT 与美国 FDA 连续化 mRNA 生产平台项目</li>
<li><strong>炼化数字孪生</strong>：为 UBC–Parkland Corporation 开发软测量与大数据分析系统，已在生产线部署</li>
<li><strong>智慧能源</strong>：微电网数字孪生建模与最优控制（加拿大国家研究委员会 NRC）</li>
<li><strong>智慧医疗</strong>：急诊科实时智能监控系统（Vancouver Coastal Health）</li>
<li><strong>锂离子电池管理</strong>：健康状态估计与容量预测</li>
<li><strong>AI 加速材料发现</strong>：基于机器学习的反向设计（Mitacs）</li>
</ul>
