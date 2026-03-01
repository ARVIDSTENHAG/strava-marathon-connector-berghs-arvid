# Strava Marathon Connector (Chrome Extension, Manifest V3)

A lightweight Chrome extension that helps you connect Strava and preview a marathon time prediction based on your recent activities.

## What it does
- Lets you connect Strava (OAuth)
- Fetches recent activity data (via backend)
- Computes an estimated marathon finish time
- Shows the result in a simple popup UI

## Install (Developer Mode)
1. Download or clone this repo
2. Open Chrome → `chrome://extensions`
3. Enable **Developer mode**
4. Click **Load unpacked**
5. Select the folder containing `manifest.json`

## Tech
- Manifest V3
- Vanilla JavaScript
- Service worker (`sw.js`)
- Strava OAuth (token flow handled via backend)
- Backend API (for data fetch + calculation)

## Portfolio
Used as part of my portfolio: https://arvidstenhag.github.io/
