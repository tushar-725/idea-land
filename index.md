---
layout: default
title: Idea Land
---

<style>
  .page-content .wrapper {
    max-width: 1460px;
    padding-left: 20px;
    padding-right: 20px;
  }

  .home-main h1 {
    margin-top: 0;
    line-height: 1.2;
  }

  .home-badge {
    display: inline-block;
    margin: 8px 0 14px;
    padding: 4px 10px;
    border-radius: 999px;
    background: #e8f3ff;
    color: #0d4f78;
    font-size: 0.82rem;
    font-weight: 600;
  }

  .idea-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 14px;
    margin-top: 12px;
  }

  .idea-card {
    border: 1px solid #d0d7de;
    border-radius: 12px;
    padding: 16px;
    background: linear-gradient(160deg, #ffffff 0%, #f8fbff 100%);
  }

  .idea-card h3 {
    margin-top: 0;
    margin-bottom: 8px;
  }

  .idea-card p {
    margin-top: 0;
    margin-bottom: 10px;
  }

  @media (max-width: 960px) {
    .idea-grid {
      grid-template-columns: 1fr;
    }
  }

  @media (max-width: 640px) {
    .page-content .wrapper {
      padding-left: 14px;
      padding-right: 14px;
    }
  }
</style>

<div class="home-main" markdown="1">
# Idea Land

<span class="home-badge">Product Idea Repository</span>

## Ideas

Browse ideas and open each one for deep documentation.

<div class="idea-grid">
  <div class="idea-card">
    <h3>Transformation Tracker</h3>
    <p>Track visible progress in hair, skin, and physique journeys with structured entries and AI-assisted insights.</p>
    <p><a href="docs/transformation-tracker.md">Open Idea</a></p>
  </div>

  <div class="idea-card">
    <h3>More Ideas</h3>
    <p>Use this slot for your next idea. Keep one card per idea and link to its dedicated idea page.</p>
    <p>Coming soon</p>
  </div>
</div>
</div>
