---
title: Hacker Guide
nav_order: 2
has_children: true
---

# Hacker Guide

Practical guides and real world experience for hackers participating in hackathons.

---

## Recommended Reading

<br>

<div
  class="guide-card"
  onclick="window.open('https://dorahacks.io/blog/news/hacker-success-guide/', '_blank')"
>
  <img
    src="https://raw.githubusercontent.com/ylin0504/dorahacks/main/assets/Banner-Blog-4.jpg"
    alt="Beginner Hacker Guide"
  />
  <div class="guide-card-content">
    <h3>
      The Beginner Hacker's Guide: How to Make the Most of Your First Hackathons
    </h3>
    <p>
      A practical guide for first-time hackers on how to choose the right hackathons, avoid common mistakes, learn from others, and turn each event into long-term growth rather than just a shot at prizes.
    </p>
  </div>
</div>

<style>
/* === Guide Card Base === */
.guide-card {
  display: flex;
  gap: 20px;
  align-items: center;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 16px;
  cursor: pointer;
  margin-bottom: 24px;
  transition: box-shadow 0.2s ease, transform 0.2s ease;
}

.guide-card:hover {
  box-shadow: 0 8px 24px rgba(0,0,0,0.08);
  transform: translateY(-2px);
}

/* Image */
.guide-card img {
  width: 320px;
  height: auto;
  object-fit: cover;
  border-radius: 8px;
  flex-shrink: 0;
  display: block;
}

/* Content */
.guide-card-content h3 {
  margin: 0 0 6px 0;
}

.guide-card-content p {
  margin: 0;
  color: #555;
  line-height: 1.5;
  font-size: 15px;
}

/* === Mobile === */
@media (max-width: 768px) {
  .guide-card {
    flex-direction: column !important;
    align-items: stretch !important;
    gap: 12px !important;
  }

  .guide-card img {
    width: 100% !important;
    max-height: 240px;
  }
}
</style>
