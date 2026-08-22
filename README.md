# Food Nutrition & Health Tracker

A lightweight, single-page web application to track your daily food consumption, calculate total calorie and fat intake, and view automated healthiness ratings.

Built entirely with clean HTML, CSS, and vanilla JavaScript—no external dependencies, frameworks, or internet connection required.

## Features

* **Instant Search & Log:** Type a food item, specify the weight in grams, and log it instantly.
* **Proportional Scaling:** Dynamically calculates precise nutrition metrics based on custom food weights.
* **Health Indicators:** Displays clear, visual health tags (`Healthy`, `Moderate`, `Unhealthy`) based on established nutrient densities.
* **Live Aggregates:** Keeps a running tally of your total calories and fat consumed.
* **Removable Entries:** Quickly delete logged entries to correct mistakes.

##  Quick Start Guide

Since this application is bundled into a single file, setup takes less than a minute:

1. **Download the File:** Copy the provided code and save it as `index.html`.
2. **Launch the App:** Double-click `index.html` to open it locally in your preferred web browser (Chrome, Edge, Safari, Firefox, etc.).
3. **Start Tracking:** Type a food item (e.g., `apple`, `pizza`) and click **Add**.



The codebase consolidates three critical web layers into one easily manageable asset:

* **Markup (`HTML5`):** Structuring the inputs, numerical tallies, and logged lists.


*Note: If an entry is typed that isn't inside the database, the app smoothly generates a balanced, mid-range fallback entry so your workflow is never interrupted.*
