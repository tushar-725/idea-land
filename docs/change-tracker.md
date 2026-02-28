---
layout: idea-doc
title: Change Tracker - Product Specification
doc_id: change-tracker
---

# Change Tracker - Product Specification

<span class="doc-badge">Product Draft v1</span>

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
