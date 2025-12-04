---
layout: page
title: People
permalink: /people/
---

## Principal Investigator

<div class="people-hero">
 <img src="{{ '/assets/ruaa.png' | relative_url }}" alt="Ruaa Al-Juboori headshot">
  <div>
    <h2 class="name">Ruaa Al Juboori, PhD, MPH, MBChB</h2>
    <div class="title">Assistant Professor of Public Health & Data Analytics Statistician</div>
    <div class="affil">University of Mississippi · Department of Public Health · Institute of Child Nutrition</div>

    <p><strong>Research areas:</strong> geospatial analytics; rural–urban health disparities; telehealth readiness; resilience metrics; spatial epidemiology.</p>

    <p class="links">
      <a href="mailto:ruaa@olemiss.edu">Email</a>
      <a href="https://olemiss.edu/profiles/ruaa" target="_blank" rel="noopener">Profile</a>
      <a href="https://www.linkedin.com/in/ruaa-al-juboori-phd-502886126/" target="_blank" rel="noopener">LinkedIn</a>
      <a href="https://orcid.org/0000-0002-8804-3755" target="_blank" rel="noopener">ORCID</a>
    </p>
  </div>
</div>

## Students

## Students

<div style="display:flex; flex-wrap:wrap; gap:20px;">

  <!-- Dylan Barker -->
  <div class="flip-card">
    <div class="flip-card-inner">
      
      <div class="flip-card-front">
        <img src="{{ '/assets/dylan.jpg' | relative_url }}" alt="Dylan Barker photo">
        <h4>Dylan Barker</h4>
        <div>MPH Student</div>
      </div>

      <div class="flip-card-back">
        <h4>Dylan Barker</h4>
        <p>Dylan Barker is a second-year Master of Public Health student at the University of Mississippi with a concentration in Epidemiology. He serves as a Graduate Assistant in the Institute of Child Nutrition’s Data Analytics Lab...</p>
      </div>

    </div>
  </div>

  <!-- Annina -->
  <div class="flip-card">
    <div class="flip-card-inner">
      
      <div class="flip-card-front">
        <img src="{{ '/assets/placeholder.png' | relative_url }}" alt="Annina photo">
        <h4>Annina Liebner</h4>
        <div>MPH Student</div>
      </div>

      <div class="flip-card-back">
        <h4>Annina Liebner</h4>
        <p>Literature synthesis, data curation, manuscript writing, spatial analysis.</p>
      </div>

    </div>
  </div>

  <!-- Emily -->
  <div class="flip-card">
    <div class="flip-card-inner">

      <div class="flip-card-front">
        <img src="{{ '/assets/placeholder.png' | relative_url }}" alt="Emily photo">
        <h4>Emily Welker</h4>
        <div>MPH Student</div>
      </div>

      <div class="flip-card-back">
        <h4>Emily Welker</h4>
        <p>Literature synthesis, data curation, manuscript writing, spatial analysis.</p>
      </div>

    </div>
  </div>

  <!-- Aminul -->
  <div class="flip-card">
    <div class="flip-card-inner">

      <div class="flip-card-front">
        <img src="{{ '/assets/placeholder.png' | relative_url }}" alt="Aminul photo">
        <h4>Aminul Apu</h4>
        <div>MPH</div>
      </div>

      <div class="flip-card-back">
        <h4>Aminul Apu</h4>
        <p>Literature synthesis, data curation, manuscript writing, spatial analysis.</p>
      </div>

    </div>
  </div>

</div>

## Alumni

<div class="cards">
  <div class="card">
    <h4>Elizabeth Swindell</h4>
    <div class="role">MPH (Alumni)</div>
    <p>Literature synthesis, data curation, manuscript writing, spatial analysis.</p>
  </div>

  <div class="card">
    <h4>Riley Morgan</h4>
    <div class="role">MPH (Alumni)</div>
    <p>Literature synthesis, data curation, manuscript writing, spatial analysis.</p>
  </div>
</div>

################################################
/* ---- FLIP CARDS FOR STUDENTS ---- */
.flip-card {
  background-color: transparent;
  width: 260px;
  height: 340px;
  perspective: 1000px;
  margin: 20px;
  display: inline-block;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.6s;
  transform-style: preserve-3d;
  border-radius: 12px;
}

.flip-card:hover .flip-card-inner,
.flip-card:active .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  padding: 20px;
}

.flip-card-front {
  background: #fff;
}

.flip-card-front img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin-top: 15px;
}

.flip-card-back {
  background: #f8f9fa;
  transform: rotateY(180deg);
  overflow-y: auto;
}











