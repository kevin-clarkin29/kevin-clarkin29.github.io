---
layout: essay
type: essay
title: "Aloha Archives: Your Window into Hawaii’s Data and Insights"
# All dates must be YYYY-MM-DD format!
date: 2024-11-04
published: true
labels:
  - Software Engineering
  - Website
---

<img width="200px" class="rounded float-start pe-4" src="https://i.postimg.cc/YpQ0cdnF/d66076d0-b28e-4856-bf49-7f8cc24cd302.webp">

# Project: Aloha Archives

**Authors:** JR (Jonathan) Lee, Jared Seto, Shaelyn Loo, and Kevin Clarkin

## Overview

### The Problem
The existing Hawaii Open Data portal is challenging for the average citizen to navigate. Citizens often encounter difficulties due to:
- Inconsistent dataset tagging
- Lack of data visualizations
- Limited accessibility for those without technical skills

### The Solution
Aloha Archives will provide an intuitive and visually appealing portal that personalizes data access for citizens based on their needs. This portal will feature:
- **Citizen Personas:** Customized experiences for different user profiles (e.g., students, researchers, residents) with relevant data and visualizations.
- **Enhanced Navigation:** Simplified and clear layout with accessible search filters for datasets by category, organization, or tags.
- **Data Visualization Links:** Links to existing visualizations.

## Approach

This application will serve as a unified platform for organizing, uploading, and exploring datasets relevant to various user personas in Hawai’i, such as education, community, and professional users.

### Roles
There are three main roles:
- **Users:** Can log in, set up profiles, and personalize their experience based on an optional quiz to help determine a user “persona.”
- **Admins:** Have additional capabilities to manage and edit datasets, oversee organization information, and handle system-wide operations.
- **Guests:** May browse datasets without options to save their favorites.

### Features
The app will offer a clean and interactive interface, including:
- **Comprehensive search page:** With filtering options.
- **Individual dataset pages:** Showcasing details like topic, view count, and organization information.
- **User profile:** Reflecting preferences or personas for tailored dataset recommendations.
- **Admin home page:** With tools for uploading, editing, and managing datasets.
- **Legal information:** Such as terms of use, privacy policy, and contact details accessible in the footer for transparency and compliance.

### Mockup Pages
Some mockup pages include:
- **Landing Page**
  - Header with Login
  - Search bar
  - Trending section
  - Footer
- **User Home Page**
  - Profile Page
  - Optional quiz for personalized experience
    - Helps determine “persona” (e.g., Education, Community, Professional)
  - Saved datasets with options to add or remove
- **Admin Home Page**
  - Separate header
  - Options to upload and edit datasets
  - Profile Page with Organization Icon, Description, etc.
- **Upload Page** (for datasets)
- **Edit Dataset Page**
- **Search Page**
  - Search bar
  - Search results
  - Filter component on the left
- **Dataset Page**
  - Title, Topic, View count
  - Dataset preview in table format
  - Organization Logo and data description
- **Footer**
  - Legal links (terms of use, privacy policy, about us, contact us, etc.)

## Use Case Ideas

### Completed End-to-End Scenarios
- **Regular User:**
  - **First visit:** Go to the landing page, register, take quiz, get personalized data recommendation, visit dataset page, add favorites, go to favorites, compare data in favorites list, and enjoy personalized data insights.
  - **Return visit:** Same steps as the first time, but without registering.

- **Admin:** Go to the landing page, log in, visit upload page, upload dataset, go to edit dataset page, edit or remove datasets, and experience a sense of accomplishment.

## Beyond the Basics

After implementing the basic functionality, here are ideas for more advanced features:
- **Interactive visualizations** for datasets that lack visualizations.
- **User-customizable visualizations** for further data exploration.
- **"Schizo mode"** to appeal to non-mainstream audiences.
