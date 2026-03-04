---
layout: default
title: "Lab 5: Advanced Layout and Via Management"
parent: Labs
nav_order: 5
---

[Open Lab 5 (Google Doc)](https://docs.google.com/document/d/TBD){: .lab-button target="_blank" rel="noopener"}

Overview: Advanced layout techniques, via management, and signal integrity.

Due date: 3/10

<script>
// EASY TOGGLE: Set to false to disable the troll feature
const ENABLE_TROLL_MODE = true;

if (ENABLE_TROLL_MODE) {
  // Function to spawn a new troll
  function spawnTroll(trollCount) {
    if (trollCount >= MAX_TROLLS) return trollCount;
    
    const newTroll = document.createElement('img');
    newTroll.src = '/assets/images/troll.png';
    newTroll.style.width = '100px';
    newTroll.style.cursor = 'pointer';
    newTroll.style.position = 'fixed';
    newTroll.style.left = Math.random() * (window.innerWidth - 100) + 'px';
    newTroll.style.top = Math.random() * (window.innerHeight - 100) + 'px';
    newTroll.style.zIndex = '9999';
    newTroll.classList.add('troll-image');
    
    document.body.appendChild(newTroll);
    trollCount++;
    
    // Add click listener to this troll too
    newTroll.addEventListener('click', function() {
      window.trollCount = spawnTroll(window.trollCount);
    });
    
    return trollCount;
  }

  window.addEventListener('DOMContentLoaded', function() {
    const MAX_TROLLS = 20;
    window.trollCount = 0;
    
    // Create the first troll image
    const firstTroll = document.createElement('img');
    firstTroll.src = '/assets/images/troll.png';
    firstTroll.style.width = '100px';
    firstTroll.style.cursor = 'pointer';
    firstTroll.style.position = 'relative';
    firstTroll.style.display = 'block';
    firstTroll.style.margin = '20px auto';
    firstTroll.classList.add('troll-image');
    
    // Add "Click me!" text below the image
    const clickText = document.createElement('div');
    clickText.textContent = 'Click me!';
    clickText.style.textAlign = 'center';
    clickText.style.fontWeight = 'bold';
    clickText.style.fontSize = '16px';
    clickText.style.marginTop = '10px';
    clickText.style.cursor = 'pointer';
    clickText.style.color = '#333';
    
    // Create a container div
    const container = document.createElement('div');
    container.style.textAlign = 'center';
    container.style.margin = '20px 0';
    
    // Insert after the overview text
    const content = document.querySelector('.main-content') || document.body;
    container.appendChild(firstTroll);
    container.appendChild(clickText);
    content.appendChild(container);
    window.trollCount = 1;
    
    // Add click listeners
    firstTroll.addEventListener('click', function() {
      window.trollCount = spawnTroll(window.trollCount);
    });
    clickText.addEventListener('click', function() {
      window.trollCount = spawnTroll(window.trollCount);
    });
  });
}
</script>
