# Point-of-Sale System for a Local Pet Store

Web-based point-of-sale system built for a pet store in Juarez, Mexico (Mascotas Rio grande mall, [Click here for the Fb business page](https://www.facebook.com/mascotasriograndemall)  to replace manual sales tracking.
The source code is private; this repository documents the project.

## Demo
![Sales flow](docs/sales-flow.gif)

## Features
- Automatic sales recording with daily and monthly cash closings
- Sales reports by day, month and department
- Currency conversion at checkout with cached exchange rates (Frankfurter API)

## Technical decisions
- Closed periods cannot be edited; corrections are recorded as post-closing adjustments
- Fixed time zone so closings stay consistent regardless of server location
- [Layered architecture, in process]

## Stack
React, Node.js, Express, MongoDB