# Earthworks Site Manpower Manager

An offline-ready Progressive Web App (PWA) for employee registration, crew-based attendance, and manpower reporting on earthworks projects.

## Features
- Register employees using a unique employee ID, full name, and work crew
- Record weekly attendance from Monday to Sunday
- View daily crew headcounts
- Produce monthly present/absent totals and attendance rates
- Export weekly, monthly, and employee-register CSV files for Excel
- Back up and restore all records using JSON
- Cache the app for offline use after the first online visit

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then click **Save**.
4. Wait for GitHub Pages to finish deploying.

The app should then be available at:
https://asigrijesse-commits.github.io/earthworks-manpower-tracker/

## Install on Android
1. Open the published HTTPS site in Google Chrome on the Android phone.
2. Open Chrome's three-dot menu and choose **Install app** or **Add to Home screen**.
3. Confirm the installation.
4. Open the app once while online so its offline cache is created.

## Data and privacy notes
- Attendance records are saved in the browser's local storage on that device.
- Records do not automatically synchronize to another phone or another user.
- Back up regularly using **Exports & backup → Download full JSON backup**.
- Clearing Chrome site data can erase records stored on that device.
- The app has no login, encryption, server-side backup, or access control. Avoid entering highly sensitive personal information.

## Important
This repository contains the PWA source files. It is **not a compiled Android APK**. The app is installed through Chrome after GitHub Pages is enabled and the site is published.
