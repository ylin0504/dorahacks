---
title: Hackathon AI
parent: Features
nav_order: 2
---

# Hackathon AI

🔑 Hackathon AI access: [https://dorahacks.io/buidl-ai](https://dorahacks.io/buidl-ai)

AI-powered infrastructure for automating hackathon operations and improving efficiency across design, execution, and scaling.

Hackathon AI is DoraHacks’ built-in agent system that assists organizers across the full hackathon lifecycle, from setup and review to judging and participant support. It reduces manual work while preserving full human oversight and decision-making.

Explore how Hackathon AI enables supervised automation, scalable operations, and the next generation of agentic hackathons. Click the card to read the full article.

Need direct help? Contact us via Telegram [@dorahacksofficial](https://t.me/dorahacksofficial)

<section>

  <!-- Introducing Hackathon AI -->
  <div
    class="guide-card"
    onclick="window.open('https://dorahacks.io/blog/guides/hackathon-ai/', '_blank')"
  >
    <img
      src="https://raw.githubusercontent.com/ylin0504/dorahacks/main/assets/hackathon-ai.jpg"
      alt="Hackathon AI"
    />
    <div class="guide-card-content">
      <h3>
        Introducing Hackathon AI
      </h3>
      <p>
        An overview of Hackathon AI as an always-on co-host that supports setup, reviews, judging, and participant communication while keeping organizers fully in control.
      </p>
    </div>
  </div>

  <!-- FAH -->
  <div
    class="guide-card"
    onclick="window.open('https://dorahacks.io/blog/news/fah-dorahacks-product-update/', '_blank')"
  >
    <img
      src="https://raw.githubusercontent.com/ylin0504/dorahacks/main/assets/fah.jpg"
      alt="Fully Autonomous Hackathon"
    />
    <div class="guide-card-content">
      <h3>
        Supervised Fully-Autonomous Hackathon (FAH)
      </h3>
      <p>
        FAH consolidates Hackathon AI capabilities into a single console, automating reviews, judging, messaging, and analytics under human supervision.
      </p>
    </div>
  </div>

  <!-- BUIDL AI 3.0 -->
  <div
    class="guide-card"
    onclick="window.open('https://dorahacks.io/blog/news/buidl-ai-3-0/', '_blank')"
  >
    <img
      src="https://raw.githubusercontent.com/ylin0504/dorahacks/main/assets/buidl-ai-3-0.jpg"
      alt="BUIDL AI 3.0"
    />
    <div class="guide-card-content">
      <h3>
        BUIDL AI 3.0: From Builder to Organizer
      </h3>
      <p>
        How BUIDL AI 3.0 lowers the barrier for organizing hackathons through AI-assisted setup, review automation, and operational guidance.
      </p>
    </div>
  </div>

</section>

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

.guide-card img {
  width: 320px;
  height: auto;
  object-fit: cover;
  border-radius: 8px;
  flex-shrink: 0;
  display: block;
}

.guide-card-content h3 {
  margin: 0 0 6px 0;
}

.guide-card-content p {
  margin: 0;
  color: #555;
  line-height: 1.5;
  font-size: 15px;
}

/* === Mobile (THIS WILL WORK) === */
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
