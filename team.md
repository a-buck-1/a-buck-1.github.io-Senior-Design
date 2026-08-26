---
layout: default
title: Team
permalink: /team/
---

# Meet the Team

## ECE Team

<style>
  .team-list {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    margin-top: 1.5rem;
    margin-bottom: 2.5rem;
  }

  .team-card {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 1.5rem;
    padding: 1.25rem;
    border: 1px dashed var(--dashed);
    border-radius: 6px;
    background-color: var(--background);
  }

  .team-photo {
    width: 110px;
    height: 110px;
    min-width: 110px; /* Prevents the image from shrinking */
    object-fit: cover;
    border-radius: 50%;
    border: 2px solid var(--dashed);
  }

  .team-info {
    flex: 1;
  }

  .team-name {
    margin: 0 0 0.25rem 0;
    font-size: 1.2rem;
    font-weight: bold;
  }

  .team-role {
    margin: 0 0 0.5rem 0;
    font-size: 0.95rem;
    font-weight: 600;
    color: var(--text-muted);
  }

  .team-bio {
    margin: 0;
    font-size: 0.9rem;
    line-height: 1.4;
  }

  /* Responsive: stack image on top for very narrow screens */
  @media (max-width: 500px) {
    .team-card {
      flex-direction: column;
      text-align: center;
    }
  }
</style>

<div class="team-list">

  <!-- Member 1 -->
  <div class="team-card">
    <img src="{{ '/assets/images/team/member_1.png' | relative_url }}" alt="Member Name" class="team-photo">
    <div class="team-info">
      <h3 class="team-name">Alex Buck</h3>
      <p class="team-role">Lead Systems Engineer</p>
      <p class="team-bio">Responsible for overall system integration, power subsystem architecture, and GitHub Pages documentation management.</p>
    </div>
  </div>

  <!-- Member 2 -->
  <div class="team-card">
    <img src="{{ '/assets/images/team/member_2.png' | relative_url }}" alt="Member Name" class="team-photo">
    <div class="team-info">
      <h3 class="team-name">Jane Doe</h3>
      <p class="team-role">Embedded Firmware Engineer</p>
      <p class="team-bio">Focusing on micro-controller programming, sensor communication over I2C/SPI, and telemetry data collection.</p>
    </div>
  </div>

</div>

## ME Team

<div class="team-list">

  <!-- Member 3 -->
  <div class="team-card">
    <img src="{{ '/assets/images/team/member_3.png' | relative_url }}" alt="Member Name" class="team-photo">
    <div class="team-info">
      <h3 class="team-name">John Smith</h3>
      <p class="team-role">Chassis & CAD Lead</p>
      <p class="team-bio">Handling CAD modeling, FEA stress simulations, enclosure fabrication, and thermal management.</p>
    </div>
  </div>

</div>
