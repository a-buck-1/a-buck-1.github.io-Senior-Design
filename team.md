---
layout: page
title: Team
permalink: /team/
---

# Meet the Team

## ECE Team

<!-- Define the grid and styling -->
<style>
  /* Base grid: 1 column for small screens */
  .team-grid {
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    gap: 1.5rem; /* Space between members */
    margin-top: 1.5rem;
    margin-bottom: 2rem;
  }

  /* Medium screens and up (Desktops/Tablets): 3 columns */
  @media (min-width: 600px) {
    .team-grid {
      grid-template-columns: repeat(3, 1fr);
    }
  }

  /* Styling for each member cell */
  .team-member {
    text-align: center;
    border: 1px dashed var(--dashed); /* Uses theme dashed line color */
    padding: 1rem;
    border-radius: 4px;
    background-color: var(--background); /* Uses theme background */
  }

  /* Headshot styling */
  .team-photo {
    width: 100px;
    height: 100px;
    object-fit: cover; /* Ensures image isn't stretched */
    border-radius: 50%; /* Makes headshot circular */
    margin-bottom: 0.75rem;
    border: 2px solid var(--dashed);
  }

  /* Text inside the cell */
  .member-name {
    margin-top: 0;
    margin-bottom: 0.25rem;
    font-size: 1.1rem;
    font-weight: bold;
  }

  .member-role {
    margin: 0;
    font-size: 0.9rem;
    color: var(--text-muted); /* Softer text color */
  }
</style>

<!-- ECE TEAM GRID -->
<div class="team-grid">

  <!-- Member 1 -->
  <div class="team-member">
    <img src="{{ '/assets/images/team/member_1.png' | relative_url }}" alt="Team Member Name" class="team-photo">
    <p class="member-name">Alex Buckwalter</p>
    <p class="member-role">Computer Engineering</p>
    <p class="member-role">Anderson, SC</p>
  </div>

  <!-- Member 2 -->
  <div class="team-member">
    <img src="{{ '/assets/images/team/member_2.png' | relative_url }}" alt="Team Member Name" class="team-photo">
    <p class="member-name">Christopher Green</p>
    <p class="member-role">Electrical Engineering</p>
    <p class="member-role"></p>
  </div>

  <!-- Member 3 -->
  <div class="team-member">
    <img src="{{ '/assets/images/team/member_3.png' | relative_url }}" alt="Team Member Name" class="team-photo">
    <p class="member-name">Wyatt May</p>
    <p class="member-role">Electrical Engineering</p>
    <p class="member-role">Grand Bay, AL</p>
  </div>

</div>

### ME Team
<div class="team-grid">

  <!-- Member 1 -->
  <div class="team-member">
    <img src="{{ '/assets/images/team/member_1.png' | relative_url }}" alt="Team Member Name" class="team-photo">
    <p class="member-name">Name</p>
    <p class="member-role">Team Role / Specific Responsibility</p>
  </div>

  <!-- Member 2 -->
  <div class="team-member">
    <img src="{{ '/assets/images/team/member_2.png' | relative_url }}" alt="Team Member Name" class="team-photo">
    <p class="member-name">Name</p>
    <p class="member-role">Team Role / Specific Responsibility</p>
  </div>

  <!-- Member 3 -->
  <div class="team-member">
    <img src="{{ '/assets/images/team/member_3.png' | relative_url }}" alt="Team Member Name" class="team-photo">
    <p class="member-name">Name</p>
    <p class="member-role">Team Role / Specific Responsibility</p>
  </div>
    
  <div class="team-member">
    <img src="{{ '/assets/images/team/member_3.png' | relative_url }}" alt="Team Member Name" class="team-photo">
    <p class="member-name">Name</p>
    <p class="member-role">Team Role / Specific Responsibility</p>
  </div>

</div>
<!-- Copy the <div class="team-grid">...</div> block from above for the ME team -->
