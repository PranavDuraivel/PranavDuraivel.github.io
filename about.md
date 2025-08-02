---
title: About
layout: page
---

<div class="about-wrapper" style="display: flex; flex-direction: column; align-items: center; gap: 1rem; text-align: center; max-width: 800px; margin: 0 auto;">

  <img 
    class="profile-about" 
    src="{% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %}" 
    alt="{{ site.title }} profile image"
    style="width: 160px; height: 160px; object-fit: cover; border-radius: 50%; box-shadow: 0 4px 12px rgba(0,0,0,0.1);" 
    loading="lazy"
  />
  
<p style="text-align: justify;">	Hi, I’m Pranav – an acoustics engineer with a deep passion for sound and musical systems. I hold a Bachelor’s degree in Mechanical Engineering and a Master’s in Acoustical and Vibration Engineering. My academic journey and industry experience span mechanical systems, computational acoustics, numerical modelling, along with hands-on exposure to MATLAB, Python and COMSOL Multiphysics.</p>

<p style="text-align: justify;">My curiosity has always revolved around how systems work—be it a vibrating structure, a musical instrument, or a complex software environment. During my Master’s, I focused on vibroacoustic modelling, sound radiation, and finite element analysis. The project involved scanning and modelling an 18th-century square piano to analyse its acoustic behaviour. This work combined CT scanning, experimental testing (hammer test), and numerical optimisation, helping me develop advanced modelling skills using COMSOL Multiphysics, MATLAB, and other simulation tools.</p>

  <hr style="margin: 3rem 0;" />

  <h2 style="text-align: toleft;">🎓 Education</h2>

  <div style="text-align: toleft; line-height: 1.8;">
    <p>
      <strong>University of Southampton</strong><br>
      MSc. Acoustical and Vibration Engineering (2023–2025), with Distinction
    </p>
    <p>
      <strong>Pondicherry University</strong><br>
      B.Tech in Mechanical Engineering (2017–2021), First Class
    </p>
  </div>

 <hr style="margin: 3rem 0;" />

  <h2 style="text-align: toleft;">🛠️ Technical Skills</h2>

  <div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 2rem; margin-top: 2rem;">
    <div style="flex: 1 1 250px;">
      <h3>🔊 Audio & Acoustics</h3>
      <ul>
        <li>Signal Processing</li>
        <li>Electroacoustics</li>
        <li>Active Control of Sound and Vibration</li>
        <li>Basic Machine Learning</li>
      </ul>
    </div>

   <div style="flex: 1 1 250px;">
      <h3>💻 Programming & Scripting</h3>
      <ul>
        <li>Python</li>
        <li>MATLAB / Simulink</li>
        <li>OpenCV</li>
        <li>LaTeX</li>
        <li>C++</li>
        <li>MySQL</li>
        <li>Mathematica</li>
        <li>JCL / NATURAL</li>
      </ul>
    </div>

   <div style="flex: 1 1 250px;">
      <h3>🧰 Simulation & Design</h3>
      <ul>
        <li>COMSOL Multiphysics</li>
        <li>AutoCAD</li>
        <li>SolidWorks</li>
      </ul>
    </div>
  </div>

  <hr style="margin: 3rem 0;" />

  <h2 style="text-align: toleft;">💬 Get in Touch</h2>

  <div style="text-align: toleft; font-size: 1.1rem;">
    <p>📞 <strong>Phone:</strong> +44 7383 773550</p>
    <p>📧 <strong>Email:</strong> <a href="mailto:rickypranav@outlook.com">rickypranav@outlook.com</a></p>
  </div>

</section>
