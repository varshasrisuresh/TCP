# NutriSync Student Nutrition Dashboard

A static, browser-based student nutrition dashboard.

## Dashboard

Open the [1.96-inch OLED Display Simulator](./1_96_inch_oled_display_simulator.html).

Open the [Student Nutrition Dashboard](./student_nutrition_dashboard.html).

## GitHub Pages

The `main` branch deploys automatically through GitHub Actions. Enable GitHub Pages for this repository with **Settings → Pages → Build and deployment → Source: GitHub Actions** if it is not already enabled.

The dashboard stores profile, meal, and lab entries in the visitor's browser LocalStorage. ESP32 polling uses `http://localhost:5000/api/logs`, so it only connects to a backend running on the same device as the visitor's browser.
