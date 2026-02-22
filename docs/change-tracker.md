---
layout: default
title: Change Tracker - Product Specification
---

<style>
  .spec-layout {
    display: grid;
    grid-template-columns: 260px minmax(0, 1fr);
    gap: 28px;
    align-items: start;
  }

  .spec-sidebar {
    position: sticky;
    top: 1.25rem;
    padding: 14px 16px;
    border: 1px solid #d8dee4;
    border-radius: 12px;
    background: linear-gradient(160deg, #f8fbff 0%, #f2f7f4 100%);
  }

  .spec-sidebar h3 {
    margin: 0 0 10px;
    font-size: 0.95rem;
    letter-spacing: 0.01em;
  }

  .spec-sidebar ul {
    margin: 0;
    padding-left: 18px;
  }

  .spec-sidebar li {
    margin: 6px 0;
  }

  .spec-sidebar a {
    text-decoration: none;
  }

  .spec-sidebar a:hover {
    text-decoration: underline;
  }

  .spec-main {
    padding: 4px 2px;
  }

  .spec-main h1 {
    margin-top: 0;
    line-height: 1.2;
  }

  .spec-main blockquote {
    margin-left: 0;
    padding: 8px 14px;
    border-left: 4px solid #2f7d4d;
    background: #f4fbf6;
  }

  .spec-main table {
    width: 100%;
    border-collapse: collapse;
  }

  .spec-main th,
  .spec-main td {
    border: 1px solid #d0d7de;
    padding: 8px 10px;
    text-align: left;
  }

  .spec-main th {
    background: #f6f8fa;
  }

  .spec-badge {
    display: inline-block;
    margin: 8px 0 14px;
    padding: 4px 10px;
    border-radius: 999px;
    background: #e8f4ec;
    color: #1f6f43;
    font-size: 0.82rem;
    font-weight: 600;
  }

  @media (max-width: 960px) {
    .spec-layout {
      grid-template-columns: 1fr;
      gap: 16px;
    }

    .spec-sidebar {
      position: static;
    }

    .spec-sidebar ul {
      columns: 2;
      column-gap: 18px;
    }
  }

  @media (max-width: 640px) {
    .spec-sidebar ul {
      columns: 1;
    }
  }
</style>

<div class="spec-layout">
  <aside class="spec-sidebar">
    <h3>Quick Navigation</h3>
    <ul>
      <li><a href="#overview">Overview</a></li>
      <li><a href="#problem-statement">Problem Statement</a></li>
      <li><a href="#what-the-app-does">What The App Does</a></li>
      <li><a href="#core-concepts">Core Concepts</a></li>
      <li><a href="#key-features">Key Features</a></li>
      <li><a href="#target-users">Target Users</a></li>
      <li><a href="#competitor-analysis">Competitor Analysis</a></li>
      <li><a href="#where-our-app-stands">Market Position</a></li>
      <li><a href="#strengths-of-our-idea">Strengths</a></li>
      <li><a href="#gaps-in-existing-apps">Gaps</a></li>
      <li><a href="#unique-selling-points-usp">USP</a></li>
      <li><a href="#mvp-definition">MVP Definition</a></li>
      <li><a href="#how-we-can-build-it">Architecture</a></li>
      <li><a href="#future-features">Future Features</a></li>
      <li><a href="#design-principles">Design Principles</a></li>
      <li><a href="#vision">Vision</a></li>
    </ul>
  </aside>

  <div class="spec-main" markdown="1">
# Change Tracker - Product Specification

<span class="spec-badge">Product Draft v1</span>

## Overview

**Change Tracker** is a mobile app that helps people **see real-life progress over time** through photos, notes, goals, and streaks.

The app is designed for journeys such as:

- Hair growth
- Fitness transformation
- Plant growth
- Reading progress
- Habits
- Personal projects

Unlike typical habit trackers or photo journals, the focus is:

> Visual and measurable change over time.

**Core idea:** the simplest way to track real-life change.

---

## Problem Statement

People try to improve different areas of life, but usually struggle to:

- Measure progress
- Stay motivated
- Remain consistent
- See long-term results

Existing tools are fragmented:

| Tool Type | Problem |
| --- | --- |
| Photo Apps | Store images but do not track progress clearly |
| Habit Apps | Track streaks but do not show visual change |
| Journals | Store notes but do not quantify outcomes |

There is no unified and simple system for tracking real-world change.

---

## What The App Does

Users create **Journeys** for a specific type of progress.

### Hair Growth Journey

- Take photos regularly
- Track growth over time
- Add notes
- Compare day 1 vs today

### Fitness Journey

- Capture body photos
- Track transformation
- Maintain streaks
- Monitor long-term consistency

### Plant Growth Journey

- Capture growth stages
- Track development timeline
- See evolution clearly

### Reading Journey

- Log reading sessions
- Track books completed
- Maintain consistency streaks

### Personal Collections

Users can track structured collections such as:

- Cooking experiments
- DIY projects
- Artwork

This is structured progress tracking, not generic photo backup.

---

## Core Concepts

### Journeys

A Journey is the primary tracking unit.

Examples:

- Hair Journey
- Gym Journey
- Reading Journey
- Plant Journey

Each Journey contains:

- Photos
- Notes
- Timeline
- Goals
- Streaks

### Entries

Each Journey contains Entries.

An Entry includes:

- Photo
- Optional note
- Date

Example:

- Date: March 10
- Photo: Hair image
- Note: Reduced hair fall this week

### Goals

Users can define outcome-focused goals.

Examples:

- Read 10 books this year
- Upload gym progress daily
- Track hair growth for 6 months

### Streaks

Streaks reward consistency.

Examples:

- 15-day reading streak
- 30-day fitness streak

---

## Key Features

### Visual Timeline

Each Journey shows visual milestones:

Day 1 -> Day 30 -> Day 90 -> Day 180

### Before vs After Comparison

Users can compare:

- First entry vs latest entry
- Any two custom entries

### Auto Timelapse

The app generates transformation videos from journey photos.

Example: 60 photos -> one progress video.

### Smart Reminders

Context-aware reminders replace generic notifications.

Example: "You have not updated your Hair Journey in 6 days."

### Streak Motivation

Examples:

- "Great job. 7-day streak."
- "Only 2 books left this year."

### Guided Photo Mode

Photo consistency features:

- Previous-photo overlay
- Alignment guides
- Same-angle capture

This improves comparison accuracy and acts as a key differentiator.

---

## Target Users

### Primary Users

#### Fitness Users

- Weight loss tracking
- Muscle gain tracking
- Body transformation tracking

#### Hair and Skin Treatment Users

Users undergoing treatment who need visual proof of outcomes.

### Secondary Users

#### Self-Improvement Users

- Reading
- Skills
- Habits

#### Hobby Users

- Plants
- Cooking
- DIY projects

---

## Competitor Analysis

### Photo Progress Apps

Examples: SnapProgress, Metamorph, PhotoProgress

Strengths:

- Visual comparison
- Simple workflow

Weaknesses:

- Fitness-only focus
- Poor organization
- Limited goals and streak support

### Habit Tracker Apps

Examples: Habitica, Loop Habit Tracker, HabitBull

Strengths:

- Streak tracking
- Reminder systems

Weaknesses:

- No visual progress layer
- Feels like task management

### Photo Journal Apps

Strengths:

- Quick daily logging

Weaknesses:

- No goals
- No structured tracking model

---

## Where Our App Stands

| Feature | Photo Apps | Habit Apps | Change Tracker |
| --- | --- | --- | --- |
| Photo Tracking | Yes | No | Yes |
| Goals | Limited | Yes | Yes |
| Streaks | No | Yes | Yes |
| Timeline | Limited | No | Yes |
| Generic Use Cases | No | Yes | Yes |

---

## Strengths of Our Idea

### Broad Use Cases

Works across fitness, hair, plants, reading, and projects.

### Emotional Motivation

Users can see real improvement, which is psychologically strong.

### Daily Engagement

Streaks and goals encourage frequent app usage.

### Simple Concept

Clear value proposition: track change over time.

---

## Gaps in Existing Apps

### Generic Progress Tracking

Most products are single-purpose; this app is multi-purpose.

### Photo Consistency

Few apps help users take consistent comparison photos.

### Motivation Systems

Most apps lack emotional feedback loops; this product includes:

- Streak feedback
- Goal progress feedback
- Smart reminders

---

## Unique Selling Points (USP)

1. Generic visual progress tracking for multiple domains.
2. Guided photo capture for accurate comparisons.
3. Auto-generated progress videos.
4. Minimal-friction workflow: Open -> Capture -> Save.

---

## MVP Definition

Version 1 should include only essential capabilities.

### Core MVP Features

- Journey creation
- Entry creation (photo + note)
- Timeline view
- Streak counter
- Reminder system

### Optional MVP Feature

- Before/After comparison mode

---

## How We Can Build It

### Mobile Framework

Recommended:

- React Native, or
- Flutter

Reasons:

- Faster development
- Cross-platform support

### Backend

Recommended: Firebase or Supabase

Required services:

- Authentication
- Database
- Storage
- Notifications

### Storage

Cloud object storage for user photos (for example, Firebase Storage).

### Architecture

Mobile App -> Backend -> Storage

---

## Future Features

### AI Progress Detection

Examples:

- Hair density trend detection
- Plant growth estimation
- Body transformation metrics

### Smart Insights

Example: "You improved 15% in 60 days."

### Advanced Comparisons

Automatic best-pair comparison selection.

---

## Design Principles

### Extreme Simplicity

Keep the interface clean and focused.

### Fast Entry Creation

Target: less than 10 seconds per update.

### Clean UI

Avoid clutter and highlight progress.

---

## Vision

> The simplest and most effective way to track real-life change.
  </div>
</div>
