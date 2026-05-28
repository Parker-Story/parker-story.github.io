---
title: "CaddieWind"
excerpt: "Native iOS golf utility in SwiftUI that calculates wind-adjusted yardage using live weather and your phone's compass."
collection: portfolio
---

CaddieWind is a native iOS app that helps golfers account for wind when selecting a club. It reads your phone's compass, pulls live wind data from OpenWeatherMap, and computes a "Plays Like" yardage — adjusting for headwind, tailwind, and crosswind drift using a non-linear model that reflects real shot variance.

True north vs. magnetic north is handled automatically, and compass rotation is smoothed across the 0°/360° boundary. My first iOS project, built to solve an actual problem on the course.

**Tech Stack:** SwiftUI, Swift 5.9, OpenWeatherMap API, XcodeGen

[View on GitHub](https://github.com/Parker-Story/CaddieWind)
