<div align="center">
<style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', sans-serif;
  line-height: 1.6;
  color: #0f172a;
}
.container {
  max-width: 900px;
  margin: 0 auto;
  padding: 0 20px;
}
.hero {
  padding: 60px 20px;
  background: linear-gradient(135deg, #f8fafc 0%, #e0f2fe 100%);
  border-radius: 12px;
  margin: 40px 0;
  text-align: center;
}
.hero h1 {
  font-size: 3em;
  margin-bottom: 10px;
  color: #0f172a;
  font-weight: 700;
}
.hero .highlight {
  color: #0ea5e9;
  font-weight: 700;
}
.hero p {
  font-size: 1.1em;
  color: #475569;
  margin-bottom: 30px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}
.cta-buttons {
  display: flex;
  gap: 15px;
  justify-content: center;
  flex-wrap: wrap;
  margin-bottom: 30px;
}
.btn {
  padding: 12px 24px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.95em;
  transition: all 0.3s ease;
  border: 2px solid;
  display: inline-block;
}
.btn-primary {
  background-color: #0ea5e9;
  color: white;
  border-color: #0ea5e9;
}
.btn-primary:hover {
  background-color: #0284c7;
  border-color: #0284c7;
  transform: translateY(-2px);
}
.btn-secondary {
  background-color: transparent;
  color: #0ea5e9;
  border-color: #0ea5e9;
}
.btn-secondary:hover {
  background-color: #f0f9ff;
  transform: translateY(-2px);
}
.metrics {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 20px;
  margin: 40px 0;
}
.metric-card {
  background: white;
  padding: 20px;
  border-radius: 8px;
  border: 1px solid #e2e8f0;
  text-align: center;
  transition: all 0.3s ease;
}
.metric-card:hover {
  border-color: #0ea5e9;
  box-shadow: 0 4px 12px rgba(14, 165, 233, 0.1);
}
.metric-number {
  font-size: 2.5em;
  font-weight: 700;
  color: #0ea5e9;
  margin-bottom: 5px;
}
.metric-label {
  font-size: 0.85em;
  color: #64748b;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}
.section {
  margin: 60px 0;
  padding: 40px 20px;
  background: white;
  border-radius: 12px;
  border: 1px solid #e2e8f0;
}
.section h2 {
  font-size: 2em;
  margin-bottom: 30px;
  color: #0f172a;
  border-bottom: 3px solid #0ea5e9;
  padding-bottom: 15px;
}
.section h3 {
  font-size: 1.3em;
  margin-top: 25px;
  margin-bottom: 15px;
  color: #0f172a;
}
.deliverables {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  margin: 30px 0;
}
.deliverable-card {
  background: #f8fafc;
  padding: 20px;
  border-radius: 8px;
  border-left: 4px solid #0ea5e9;
  transition: all 0.3s ease;
}
.deliverable-card:hover {
  background: #f0f9ff;
  transform: translateX(5px);
}
.deliverable-card h4 {
  color: #0f172a;
  margin-bottom: 10px;
  font-size: 1.05em;
}
.deliverable-card p {
  color: #64748b;
  font-size: 0.95em;
}
.project-card {
  background: #f8fafc;
  padding: 25px;
  border-radius: 8px;
  border: 2px solid #e2e8f0;
  margin: 20px 0;
  transition: all 0.3s ease;
}
.project-card:hover {
  border-color: #0ea5e9;
  box-shadow: 0 8px 16px rgba(14, 165, 233, 0.15);
}
.project-card h3 {
  color: #0f172a;
  margin-bottom: 8px;
}
.project-industry {
  color: #0ea5e9;
  font-size: 0.9em;
  font-weight: 600;
  margin-bottom: 15px;
}
.scope-list {
  list-style: none;
  margin: 15px 0;
}
.scope-list li {
  padding: 8px 0;
  padding-left: 25px;
  position: relative;
  color: #475569;
}
.scope-list li:before {
  content: "→";
  position: absolute;
  left: 0;
  color: #0ea5e9;
  font-weight: bold;
}
.tech-stack {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  margin: 15px 0;
}
.tech-badge {
  background: white;
  color: #0ea5e9;
  padding: 6px 14px;
  border-radius: 20px;
  border: 1px solid #0ea5e9;
  font-size: 0.85em;
  font-weight: 600;
}
.stack-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 15px;
  margin: 30px 0;
}
.stack-item {
  background: white;
  padding: 20px;
  border-radius: 8px;
  border: 1px solid #e2e8f0;
  text-align: center;
  transition: all 0.3s ease;
}
.stack-item:hover {
  border-color: #0ea5e9;
  background: #f0f9ff;
  transform: translateY(-5px);
}
.stack-icon {
  font-size: 2.5em;
  margin-bottom: 10px;
}
.stack-name {
  font-weight: 600;
  color: #0f172a;
  margin-bottom: 5px;
}
.stack-desc {
  font-size: 0.8em;
  color: #64748b;
}
.availability-banner {
  background: linear-gradient(135deg, #0ea5e9 0%, #06b6d4 100%);
  color: white;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  margin: 30px 0;
  font-weight: 500;
}
.cta-section {
  background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
  color: white;
  padding: 50px 20px;
  border-radius: 12px;
  text-align: center;
  margin: 40px 0;
}
.cta-section h2 {
  color: white;
  border-bottom-color: #0ea5e9;
  margin-bottom: 20px;
}
.cta-section p {
  color: #cbd5e1;
  margin-bottom: 30px;
  max-width: 500px;
  margin-left: auto;
  margin-right: auto;
}
.social-links {
  display: flex;
  gap: 15px;
  justify-content: center;
  margin: 30px 0;
}
.social-link {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 10px 16px;
  background: rgba(255, 255, 255, 0.1);
  color: white;
  text-decoration: none;
  border-radius: 6px;
  transition: all 0.3s ease;
  border: 1px solid rgba(255, 255, 255, 0.2);
}
.social-link:hover {
  background: rgba(255, 255, 255, 0.2);
  border-color: rgba(255, 255, 255, 0.4);
}
.divider {
  height: 1px;
  background: linear-gradient(to right, transparent, #e2e8f0, transparent);
  margin: 40px 0;
}
@media (max-width: 600px) {
  .hero h1 {
    font-size: 2em;
  }
  .hero p {
    font-size: 1em;
  }
  .cta-buttons {
    flex-direction: column;
  }
  .btn {
    width: 100%;
    text-align: center;
  }
  .metrics {
    grid-template-columns: 1fr;
  }
  .deliverables {
    grid-template-columns: 1fr;
  }
  .stack-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}



</style>
</div> <div align="center">

<span style="color: #0f172a;">Hi 👋 I'm</span> <span style="color: #0ea5e9;">Claudenilson Junior</span>

<span style="color: #0f172a;">Data Analyst • SQL • Python • Power BI • Business Analytics</span>

</div>




<div class="hero">
<h1>Transform Data Into <span class="highlight">Business Decisions</span></h1>
  <p>I'm a hands-on Data Analyst specializing in end-to-end analytics delivery. From raw data to executive dashboards, I help organizations unlock insights that drive growth.</p>   <div class="cta-buttons">
    <a href="https://github.com/Claudenilsonjunior" class="btn btn-primary">View My Projects</a>
    <a href="mailto:claudenilsonjunior2@gmail.com" class="btn btn-secondary">Get in Touch</a>
  </div>   <div class="metrics">
    <div class="metric-card">
      <div class="metric-number">50+</div>
      <div class="metric-label">Projects Delivered</div>
    </div>
    <div class="metric-card">
      <div class="metric-number">5+</div>
      <div class="metric-label">Years Experience</div>
    </div>
    <div class="metric-card">
      <div class="metric-number">100%</div>
      <div class="metric-label">Client Satisfaction</div>
    </div>
  </div>
</div> <div class="availability-banner">
  🌍 Open to Remote Opportunities • Europe • United States • Global • Full-time • Contract • B2B
</div>




<div class="section">

🧠 What I Deliver

Every project is an opportunity to turn complexity into clarity. I combine technical expertise with business acumen to deliver insights that matter.

<div class="deliverables">
<div class="deliverable-card">
    <h4>📊 End-to-End Analysis</h4>
    <p>From raw, messy data to clear, business-ready insights</p>
  </div>
  <div class="deliverable-card">
    <h4>🔍 Advanced SQL</h4>
    <p>Complex queries, data modeling, and optimization</p>
  </div>
  <div class="deliverable-card">
    <h4>📈 Executive Dashboards</h4>
    <p>Power BI, Looker Studio, Tableau visualizations</p>
  </div>
  <div class="deliverable-card">
    <h4>🎯 KPI Design</h4>
    <p>Performance tracking, reporting automation, business storytelling</p>
  </div>
</div> </div>




<div class="section">

🏢 Selected Work & Case Studies

Real projects, real impact. Each case study demonstrates my approach to solving complex analytics challenges.

<div class="project-card">
<h3>🛒 E-Commerce Sales & Performance Analysis</h3>
  <div class="project-industry">Industry: E-Commerce / Retail Tech</div>   <p>Delivered a full sales performance analysis for a multi-channel e-commerce operation, focusing on revenue drivers, regional performance, and product-level insights.</p>   <h4 style="margin-top: 20px; color: #0f172a;">Scope & Impact</h4>
  <ul class="scope-list">
    <li>Structured raw transactional data (orders, customers, products )</li>
    <li>SQL analysis for revenue, growth, and performance trends</li>
    <li>Identified underperforming regions and high-impact product categories</li>
    <li>Built Power BI dashboards for executive decision-making</li>
  </ul>   <div class="tech-stack">
    <span class="tech-badge">SQL</span>
    <span class="tech-badge">Power BI</span>
    <span class="tech-badge">Data Modeling</span>
  </div>   <p style="margin-top: 20px;">
    <a href="https://github.com/Claudenilsonjunior/E-Commerce_Sales_Analysis" style="color: #0ea5e9; font-weight: 600; text-decoration: none;">👉 View Case Study →</a>
  </p>
</div> <div style="background: #fef3c7; padding: 20px; border-radius: 8px; margin: 30px 0; border-left: 4px solid #f59e0b;">
  <p style="color: #92400e; margin: 0;">
    <strong>🚧 More projects coming soon.</strong> I'm currently working on additional case studies including revenue forecasting, customer segmentation, and Microsoft Fabric implementations.
  </p>
</div> </div>




<div class="section">

🛠️ Core Stack

Tools and technologies I use to deliver world-class analytics solutions.

<div class="stack-grid">
<div class="stack-item">
    <div class="stack-icon">🐍</div>
    <div class="stack-name">Python</div>
    <div class="stack-desc">Data processing & automation</div>
  </div>
  <div class="stack-item">
    <div class="stack-icon">🗄️</div>
    <div class="stack-name">SQL</div>
    <div class="stack-desc">Advanced queries & modeling</div>
  </div>
  <div class="stack-item">
    <div class="stack-icon">🐘</div>
    <div class="stack-name">PostgreSQL</div>
    <div class="stack-desc">Enterprise databases</div>
  </div>
  <div class="stack-item">
    <div class="stack-icon">🔧</div>
    <div class="stack-name">MySQL</div>
    <div class="stack-desc">Relational databases</div>
  </div>
  <div class="stack-item">
    <div class="stack-icon">📊</div>
    <div class="stack-name">Power BI</div>
    <div class="stack-desc">Executive dashboards</div>
  </div>
  <div class="stack-item">
    <div class="stack-icon">📈</div>
    <div class="stack-name">Excel</div>
    <div class="stack-desc">Advanced analytics</div>
  </div>
</div> </div>




<div class="cta-section">
<h2 style="color: white; border-bottom-color: #0ea5e9;">Let's Work Together</h2>
  <p>Whether you're looking to hire or explore a potential collaboration, I'd love to hear from you. Let's discuss how I can help drive your analytics initiatives forward.</p>   <div class="cta-buttons">
    <a href="mailto:claudenilsonjunior2@gmail.com" class="btn btn-primary">📧 Email Me</a>
    <a href="https://www.linkedin.com/in/claudenilson-junior" class="btn btn-secondary">💼 Connect on LinkedIn</a>
  </div>   <div class="social-links">
    <a href="https://www.linkedin.com/in/claudenilson-junior" class="social-link">LinkedIn</a>
    <a href="https://github.com/Claudenilsonjunior" class="social-link">GitHub</a>
    <a href="mailto:claudenilsonjunior2@gmail.com" class="social-link">Email</a>
  </div>
</div>




<div align="center">
<p style="color: #64748b; font-size: 0.9em; margin-top: 40px;">
    © 2024 Claudenilson Junior. All rights reserved. | 
    <a href="https://www.linkedin.com/in/claudenilson-junior" style="color: #0ea5e9; text-decoration: none;">LinkedIn</a> • 
    <a href="https://github.com/Claudenilsonjunior" style="color: #0ea5e9; text-decoration: none;">GitHub</a>
  </p>
</div>




