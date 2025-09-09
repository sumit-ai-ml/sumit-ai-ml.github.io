---
layout: home
author_profile: true
title: "Sumit Pandey, PhD"
avatar: /assets/images/profile.png
header:
  overlay_image: /assets/images/banner.jpg
  overlay_filter: 0.2
  caption: "AI Scientist | Medical Imaging | MLOps | 170+ Citations"
---

<style>
  .hero-section {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 3rem 2rem;
    border-radius: 15px;
    text-align: center;
    margin: 2rem 0;
    box-shadow: 0 10px 30px rgba(0,0,0,0.2);
  }
  
  .hero-title {
    font-size: 2.5rem;
    font-weight: 700;
    margin-bottom: 1rem;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
  }
  
  .hero-subtitle {
    font-size: 1.2rem;
    opacity: 0.9;
    margin-bottom: 2rem;
  }
  
  .contact-links {
    display: flex;
    justify-content: center;
    gap: 2rem;
    flex-wrap: wrap;
    margin-top: 2rem;
  }
  
  .contact-link {
    background: rgba(255,255,255,0.2);
    padding: 0.8rem 1.5rem;
    border-radius: 25px;
    text-decoration: none;
    color: white;
    font-weight: 500;
    transition: all 0.3s ease;
    backdrop-filter: blur(10px);
  }
  
  .contact-link:hover {
    background: rgba(255,255,255,0.3);
    transform: translateY(-2px);
    color: white;
  }
  
  .expertise-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 2rem 0;
  }
  
  .expertise-card {
    background: linear-gradient(145deg, #f0f0f0, #ffffff);
    padding: 2rem;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
  }
  
  .expertise-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
  }
  
  .expertise-title {
    color: #333;
    font-size: 1.3rem;
    font-weight: 700;
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }
  
  .skills-list {
    color: #666;
    line-height: 1.8;
  }
  
  .experience-item {
    background: #f8f9fa;
    padding: 2rem;
    border-radius: 15px;
    margin: 2rem 0;
    border-left: 5px solid #667eea;
    transition: all 0.3s ease;
  }
  
  .experience-item:hover {
    background: #fff;
    box-shadow: 0 5px 20px rgba(0,0,0,0.1);
    transform: translateX(5px);
  }
  
  .experience-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 1rem;
    flex-wrap: wrap;
  }
  
  .experience-title {
    color: #333;
    font-size: 1.4rem;
    font-weight: 700;
    margin: 0;
  }
  
  .experience-date {
    color: #667eea;
    font-weight: 600;
    font-size: 0.9rem;
  }
  
  .experience-company {
    color: #666;
    font-style: italic;
    margin-bottom: 1rem;
  }
  
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
    gap: 2rem;
    margin: 2rem 0;
  }
  
  .project-card {
    background: linear-gradient(145deg, #ffffff, #f0f0f0);
    padding: 2rem;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
    border-top: 4px solid #667eea;
  }
  
  .project-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 15px 35px rgba(0,0,0,0.2);
  }
  
  .project-header {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-bottom: 1rem;
  }
  
  .project-title {
    color: #333;
    font-size: 1.3rem;
    font-weight: 700;
    margin: 0;
  }
  
  .project-category {
    background: #667eea;
    color: white;
    padding: 0.3rem 0.8rem;
    border-radius: 15px;
    font-size: 0.8rem;
    font-weight: 600;
  }
  
  .impact-highlight {
    background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    color: white;
    padding: 1rem;
    border-radius: 10px;
    margin: 1rem 0;
    font-weight: 600;
  }
  
  .tech-stack {
    color: #666;
    font-size: 0.9rem;
    margin-top: 1rem;
  }
  
  .awards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
    margin: 2rem 0;
  }
  
  .award-item {
    background: linear-gradient(145deg, #ffd89b 0%, #19547b 100%);
    color: white;
    padding: 1.5rem;
    border-radius: 15px;
    text-align: center;
    font-weight: 600;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }
  
  .education-timeline {
    position: relative;
    padding-left: 2rem;
  }
  
  .education-item {
    background: #f8f9fa;
    padding: 1.5rem;
    border-radius: 10px;
    margin: 1.5rem 0;
    border-left: 4px solid #667eea;
    position: relative;
  }
  
  .education-item::before {
    content: '';
    position: absolute;
    left: -8px;
    top: 50%;
    width: 16px;
    height: 16px;
    background: #667eea;
    border-radius: 50%;
    transform: translateY(-50%);
  }
  
  .publications-list {
    background: #f8f9fa;
    padding: 2rem;
    border-radius: 15px;
    border-left: 5px solid #667eea;
  }
  
  .publication-item {
    margin: 1rem 0;
    padding: 1rem;
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }
  
  .connect-section {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 3rem 2rem;
    border-radius: 15px;
    text-align: center;
    margin: 2rem 0;
  }
  
  .connect-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
    margin-top: 2rem;
  }
  
  .connect-item {
    background: rgba(255,255,255,0.2);
    padding: 1rem;
    border-radius: 10px;
    backdrop-filter: blur(10px);
  }
  
  @media (max-width: 768px) {
    .hero-title { font-size: 2rem; }
    .contact-links { flex-direction: column; align-items: center; }
    .expertise-grid { grid-template-columns: 1fr; }
    .project-grid { grid-template-columns: 1fr; }
    .experience-header { flex-direction: column; gap: 0.5rem; }
  }
</style>

<div class="hero-section">
  <h1 class="hero-title">🚀 AI Scientist & Data Engineer</h1>
  <p class="hero-subtitle">Transforming healthcare through production-ready AI systems</p>
  <p style="font-size: 1.1rem; line-height: 1.6; max-width: 800px; margin: 0 auto;">
    Innovation-driven Data Scientist specializing in end-to-end ML solutions for medical imaging and predictive analytics. Expert in building scalable AI pipelines from research to production, with proven impact across healthcare, telecom, and consulting domains.
  </p>
  
  <div class="contact-links">
    <a href="mailto:sumitpandey171@gmail.com" class="contact-link">📧 Contact</a>
    <a href="https://www.linkedin.com/in/sumit-pandey-ai" class="contact-link">🔗 LinkedIn</a>
    <a href="https://www.towardsdeeplearning.com" class="contact-link">📝 Blog</a>
    <a href="https://maps.google.com/?q=Copenhagen,Denmark" class="contact-link">📍 Copenhagen</a>
  </div>
</div>

## 🎯 Core Expertise

<div class="expertise-grid">
  <div class="expertise-card">
    <h3 class="expertise-title">🧠 Machine Learning & AI</h3>
    <div class="skills-list">
      Deep Learning • Computer Vision • NLP/LLMs • Time Series Forecasting • MLOps
    </div>
  </div>
  
  <div class="expertise-card">
    <h3 class="expertise-title">⚡ Technical Stack</h3>
    <div class="skills-list">
      Python • PyTorch • TensorFlow • Docker • Azure • Git/CI-CD • HuggingFace • Streamlit
    </div>
  </div>
  
  <div class="expertise-card">
    <h3 class="expertise-title">🏥 Domain Focus</h3>
    <div class="skills-list">
      Medical Imaging • Predictive Maintenance • Business Analytics • Production ML Systems
    </div>
  </div>
</div>

## 💼 Professional Experience

<div class="experience-item">
  <div class="experience-header">
    <h3 class="experience-title">🎯 Founder & Technical Writer</h3>
    <span class="experience-date">Aug 2023 - Present</span>
  </div>
  <div class="experience-company">Towards Deep Learning | 18k+ readers, 120+ premium members</div>
  <ul>
    <li>Translate complex ML research into practitioner-friendly tutorials</li>
    <li>Built global community of ML practitioners and researchers</li>
  </ul>
</div>

<div class="experience-item">
  <div class="experience-header">
    <h3 class="experience-title">🏥 External AI Consultant</h3>
    <span class="experience-date">Jun 2025 - Aug 2025</span>
  </div>
  <div class="experience-company">University of Copenhagen</div>
  <ul>
    <li><strong>Co-developed Zero-MED-YOLO</strong>: Reduced preprocessing time from 3-4 hours to 2-3 minutes</li>
    <li>Delivered no-code solution for medical imaging workflows</li>
  </ul>
</div>

<div class="experience-item">
  <div class="experience-header">
    <h3 class="experience-title">🧠 Visiting Researcher</h3>
    <span class="experience-date">Aug 2024 - Jan 2025</span>
  </div>
  <div class="experience-company">Harvard Medical School & MIT</div>
  <ul>
    <li>Developed <strong>MED-YOLO project</strong> for 2D/3D medical image segmentation</li>
    <li>Built automated preprocessing pipelines for sparse medical datasets</li>
    <li>Published research on robust medical AI systems</li>
  </ul>
</div>

<div class="experience-item">
  <div class="experience-header">
    <h3 class="experience-title">🔬 PhD Research Fellow</h3>
    <span class="experience-date">Apr 2022 - Mar 2025</span>
  </div>
  <div class="experience-company">University of Copenhagen</div>
  <ul>
    <li><strong>Led Deep Consciousness project</strong>: Improved coma patient survival prediction from 0.75 to 0.82 AUROC</li>
    <li>Established international collaboration with Chang Gung Memorial Hospital (Taiwan)</li>
    <li>Managed large-scale hospital datasets on cloud HPC infrastructure</li>
    <li>Applied statistical modeling and survival analysis for clinical decision support</li>
  </ul>
</div>

## 🚀 Key Projects & Impact

<div class="project-grid">
  <div class="project-card">
    <div class="project-header">
      <h3 class="project-title">🏆 Deep Consciousness</h3>
      <span class="project-category">Clinical AI</span>
    </div>
    <p>Developed predictive models for comatose patient outcomes using time-series CT imaging</p>
    <div class="impact-highlight">
      <strong>Impact:</strong> 0.82 AUROC, deployed at Rigshospitalet Copenhagen
    </div>
    <div class="tech-stack"><strong>Tech:</strong> PyTorch, CNN, Survival Analysis, Time Series Modeling</div>
  </div>
  
  <div class="project-card">
    <div class="project-header">
      <h3 class="project-title">🎯 Zero-MED-YOLO</h3>
      <span class="project-category">Medical Imaging</span>
    </div>
    <p>No-code solution for medical image analysis with automated preprocessing</p>
    <div class="impact-highlight">
      <strong>Impact:</strong> 95% reduction in setup time (3-4 hours → 2-3 minutes)
    </div>
    <div class="tech-stack"><strong>Tech:</strong> YOLO, Computer Vision, Process Automation</div>
  </div>
  
  <div class="project-card">
    <div class="project-header">
      <h3 class="project-title">💬 GPT-4 Customer Analysis</h3>
      <span class="project-category">NLP/Business</span>
    </div>
    <p>Automated sentiment analysis and classification system for customer feedback</p>
    <div class="impact-highlight">
      <strong>Impact:</strong> Reduced manual work from 30 hours to 1 hour per analysis cycle
    </div>
    <div class="tech-stack"><strong>Tech:</strong> GPT-4.1, Gemma-2B, Python, GDPR-compliant deployment</div>
  </div>
  
  <div class="project-card">
    <div class="project-header">
      <h3 class="project-title">🔧 Predictive Maintenance System</h3>
      <span class="project-category">Industrial AI</span>
    </div>
    <p>Optimized hemodialysis machine maintenance using genetic algorithms</p>
    <div class="impact-highlight">
      <strong>Impact:</strong> 60% cost reduction (~$34k per machine), maintained 99%+ availability
    </div>
    <div class="tech-stack"><strong>Tech:</strong> Root Cause Analysis, Genetic Algorithms, Weibull Analysis</div>
  </div>
</div>

## 🏆 Recognition & Awards

<div class="awards-grid">
  <div class="award-item">
    🏆 <strong>Corti Hackathon Winner (2025)</strong><br>
    "Nurse Agent" for patient voice prioritization
  </div>
  <div class="award-item">
    🎓 <strong>PhD Fellowship Recipient</strong><br>
    University of Copenhagen (2022-2025)
  </div>
  <div class="award-item">
    📚 <strong>170+ Academic Citations</strong><br>
    Established reputation in computer vision research
  </div>
  <div class="award-item">
    ✍️ <strong>Published Author</strong><br>
    3 peer-reviewed journal articles in top-tier venues
  </div>
</div>

## 🎓 Education & Certifications

<div class="education-timeline">
  <div class="education-item">
    <h3><strong>PhD in Computer Science</strong> | <em>University of Copenhagen</em> | 2022-2025</h3>
    <p><em>Thesis: "From Deep Learning to Deep Consciousness"</em></p>
  </div>
  
  <div class="education-item">
    <h3><strong>MS in Electronic Engineering</strong> | <em>Chang Gung University, Taiwan</em> | 2020-2022</h3>
    <p><em>CGPA: 3.6/4.0 | Thesis: "ML-Based Prediction and Analysis Algorithms"</em></p>
  </div>
</div>

## 📚 Recent Publications

<div class="publications-list">
  <div class="publication-item">
    <strong>Pandey, S.</strong> et al. "Validating YOLOv8 & SAM for Robust POCUS Aorta Segmentation" (2024)
  </div>
  <div class="publication-item">
    <strong>Pandey, S.</strong> et al. "Multi-Planar U-Net for Kidney/Tumor Segmentation", ICCV Workshop (2023)
  </div>
  <div class="publication-item">
    <strong>Pandey, S.</strong> et al. "Fully Automated Hypopharyngeal-Cancer MRI Segmentation", <em>European Radiology</em>
  </div>
  
  <div style="text-align: center; margin-top: 1.5rem;">
    <a href="https://scholar.google.com/citations?user=your_id" style="color: #667eea; font-weight: 600;">📖 Complete Publication List</a>
  </div>
</div>

<div class="connect-section">
  <h2 style="margin-top: 0;">🌐 Let's Connect</h2>
  <p style="font-size: 1.1rem; margin-bottom: 2rem;">
    I'm always interested in discussing AI applications in healthcare, MLOps best practices, and opportunities to collaborate on impactful projects.
  </p>
  
  <div class="connect-grid">
    <div class="connect-item">
      <strong>📧 Email</strong><br>
      sumitpandey171@gmail.com
    </div>
    <div class="connect-item">
      <strong>📍 Location</strong><br>
      Copenhagen, Denmark
    </div>
    <div class="connect-item">
      <strong>💼 Available for</strong><br>
      Consulting • Collaboration • Speaking
    </div>
  </div>
</div>
