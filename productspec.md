---
title: productspec

---

✏️ Milestone 1 – Activity 2: Product Spec
App Name: Strike Ride
Team: SmartDroids

This document outlines the required and optional features, chosen APIs, and user interaction flows for our app.

📱 App Overview
App Name

Strike Ride

One-Sentence Description

A FAMU-exclusive scooter rental app that allows students to locate, unlock, and ride electric scooters around campus.

Detailed Description

Strike Ride improves campus mobility by giving FAMU students access to a fleet of electric scooters. Through the app, users can log in using their FAMU credentials, view nearby scooters on a map, unlock scooters, track rides, and end rides in approved zones. This solution addresses long walking distances, inefficiencies with the Venom bus, and the lack of on-demand campus transportation.

📊 App Evaluation

(Copied from Activity 1, updated as needed.)

Mobile:

GPS tracking, map features, unlocking = highly mobile-dependent.

Story:

Solves a major student pain point: mobility across a large campus where city scooters are banned.

Market:

FAMU undergraduates, graduates, faculty, staff.

Habit:

Used multiple times a day for transportation.

Scope:

MVP is realistic; many optional advanced features can scale later.

🧩 App Specification
1. Required Features (MVP)

Student login using FAMU credentials

Real-time map showing scooter availability

Scooter detail screen (battery %, distance, parking zone)

Unlock/start ride via button or QR scan

End ride with parking zone validation

Basic ride timer/summary

2. Optional Features

Tap-to-pay via FAMU ID

Ride history

Parking and charging overlays

Push notifications

Report damaged scooter

In-app safety instructions

Post-ride feedback form

🔌 3. Chosen API(s)
A. Mapbox SDK or Google Maps SDK

Used for:

Campus map rendering

Scooter pins

User GPS

B. Mock Scooter API (JSON/Firebase)

Data includes:

Scooter ID

Latitude/longitude

Battery level

Status

Parking zone data

🧭 4. User Interaction Plan
Home / Map Screen

Users see scooters on a map

Tap a scooter → view details

Start ride from bottom panel

Scooter Details Screen

Displays battery %, distance, location

“Unlock Scooter” button

QR option available

Active Ride Screen

Ride timer

GPS tracking

“End Ride” button

End Ride Summary

Validates parking zone

Shows summary of ride

Optional feedback

End of Activity 2 - Product Spec