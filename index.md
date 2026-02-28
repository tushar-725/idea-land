---
layout: default
title: Product Ideas and Specifications
---

<style>
  .page-content .wrapper {
    max-width: 1400px;
    padding-left: 20px;
    padding-right: 20px;
  }

  @media (max-width: 640px) {
    .page-content .wrapper {
      padding-left: 14px;
      padding-right: 14px;
    }
  }

  .home-layout {
    display: grid;
    grid-template-columns: 240px minmax(0, 1fr);
    gap: 28px;
    align-items: start;
  }

  .home-sidebar {
    position: sticky;
    top: 1.25rem;
    padding: 14px 16px;
    border: 1px solid #d8dee4;
    border-radius: 12px;
    background: linear-gradient(160deg, #f8fbff 0%, #f5fbf7 100%);
  }

  .home-sidebar h3 {
    margin: 0 0 10px;
    font-size: 0.95rem;
  }

  .home-sidebar ul {
    margin: 0;
    padding-left: 18px;
  }

  .home-sidebar li {
    margin: 6px 0;
  }

  .home-sidebar a {
    text-decoration: none;
  }

  .home-sidebar a:hover {
    text-decoration: underline;
  }

  .home-main {
    padding: 4px 2px;
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
    background: #e8f4ec;
    color: #1f6f43;
    font-size: 0.82rem;
    font-weight: 600;
  }

  .project-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 14px;
    margin-top: 10px;
  }

  .project-card {
    border: 1px solid #d0d7de;
    border-radius: 12px;
    padding: 14px;
    background: #ffffff;
  }

  .project-card h3 {
    margin-top: 0;
    margin-bottom: 8px;
  }

  .project-card p {
    margin-top: 0;
  }

  @media (max-width: 960px) {
    .home-layout {
      grid-template-columns: 1fr;
      gap: 16px;
    }

    .home-sidebar {
      position: static;
    }

    .project-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="home-layout">
  <aside class="home-sidebar">
    <h3>Quick Navigation</h3>
    <ul>
      <li><a href="#overview">Overview</a></li>
      <li><a href="#projects">Projects</a></li>
    </ul>
  </aside>

  <div class="home-main" markdown="1">
# Product Ideas and Specifications

<span class="home-badge">Documentation Hub</span>

## Overview

This repository contains product ideas, technical planning, and design documents.

## Projects

<div class="project-grid">
  <div class="project-card">
    <h3>Change Tracker Specification</h3>
    <p>Full product specification for the Change Tracker application.</p>
    <p><a href="docs/change-tracker.md">Open Document</a></p>
  </div>

  <div class="project-card">
    <h3>Phase 1 Features</h3>
    <p>Detailed scope and execution plan for Phase 1 transformation tracking.</p>
    <p><a href="docs/phase1-features.md">Open Document</a></p>
  </div>
</div>

More projects coming soon.
  </div>
</div>
