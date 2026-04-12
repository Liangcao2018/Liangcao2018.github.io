---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-area {
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
.collab-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 12px;
  margin-top: 16px;
}
.collab-card {
  background: #f7fafc;
  border-radius: 6px;
  padding: 14px 16px;
  font-size: 0.9em;
  border: 1px solid #e2e8f0;
}
.collab-card strong { color: #2d3748; }
.collab-card .affil { color: #718096; font-size: 0.85em; }
</style>

<h2 class="research-section-title" style="color: #1a365d; font-family: 'Source Serif 4', Georgia, serif; font-size: 1.35em; font-weight: 700; border-bottom: 2px solid #2c5282; padding-bottom: 8px; margin: 28px 0 16px 0;">Overview</h2>

My research focuses on **intelligent monitoring and control of complex industrial processes**, with the goal of improving the safety, reliability, and intelligence of industrial systems. I develop theories and algorithms spanning three interconnected pillars:

<div class="research-area">
<h3>1. Data-Physics Hybrid Modeling for Complex Industrial Processes</h3>
<p>
I develop methods that fuse data-driven machine learning with first-principles knowledge to build high-accuracy, physically consistent models. Key contributions include incorporating mechanistic constraints into neural network architectures, multi-source data fusion with iterative optimization, knowledge transfer using causal reasoning, and constructing reliable transfer learning models grounded in domain knowledge. These methods have been applied to <strong>refinery digital twins</strong>, <strong>biofeedstock co-processing</strong>, and <strong>renewable CO2 tracking</strong>.
</p>
<div class="research-keywords">
<span class="research-kw">Soft Sensors</span>
<span class="research-kw">Hybrid Modeling</span>
<span class="research-kw">Transfer Learning</span>
<span class="research-kw">Physics-informed ML</span>
<span class="research-kw">Digital Twins</span>
</div>
</div>

<div class="research-area">
<h3>2. Trustworthy Intelligent Monitoring and Fault Diagnosis</h3>
<p>
I address the "black-box" bottleneck in industrial AI by developing interpretable and reliable monitoring systems. My work includes causal discovery algorithms (including a novel polynomial chaos framework published at <strong>ICLR, CVPR, AAAI 2026</strong>), virtual sample generation with causal learning, alarm sequence alignment and threshold optimization, and attack detection for cyber-physical systems using causal representations.
</p>
<div class="research-keywords">
<span class="research-kw">Causal Discovery</span>
<span class="research-kw">Process Monitoring</span>
<span class="research-kw">Alarm Management</span>
<span class="research-kw">Polynomial Chaos</span>
<span class="research-kw">Interpretable AI</span>
</div>
</div>

<div class="research-area">
<h3>3. Multi-Channel Fault-Tolerant Control</h3>
<p>
I design control strategies that maintain system stability and performance under multi-type, multi-channel faults common in industrial settings. This includes mathematical modeling of multi-channel faults in 2D systems, observer design for fault estimation, and nonlinear time-varying fault-tolerant control with provable stability guarantees.
</p>
<div class="research-keywords">
<span class="research-kw">Fault-Tolerant Control</span>
<span class="research-kw">2D Systems</span>
<span class="research-kw">Observer Design</span>
<span class="research-kw">Robust Control</span>
</div>
</div>

<h2 class="research-section-title" style="color: #1a365d; font-family: 'Source Serif 4', Georgia, serif; font-size: 1.35em; font-weight: 700; border-bottom: 2px solid #2c5282; padding-bottom: 8px; margin: 28px 0 16px 0;">Application Domains</h2>

My research has been successfully deployed in real-world industrial scenarios:

- **Biopharmaceutical Manufacturing**: Core participant in MIT/US FDA's $82M continuous mRNA manufacturing platform project
- **Refinery Digital Twins**: Developed soft measurement and big data analytics for UBC-Parkland Corporation, deployed in production
- **Smart Energy Systems**: Microgrid digital twin modeling and optimal control (NRC Canada, $15M)
- **Healthcare**: Real-time intelligent monitoring for emergency departments (Vancouver Coastal Health)
- **Lithium-ion Battery Management**: State of health estimation and capacity prediction
- **AI-Accelerated Materials Discovery**: Inverse design using machine learning (Mitacs, $3.6M)

