# Requirements

## Purpose

This document describes the functional and non-functional requirements of Nomad Guide.

The focus is on solving real problems experienced by individual travellers.

---

# Functional Requirements

## FR-001 Travel Management
Priority: High

The user can create and manage multiple trips.

Acceptance Criteria:
- Create a trip
- Edit a trip
- Delete a trip
- Select the active trip

---

## FR-002 Places
Priority: High

The user can save places that are relevant during a trip.

Examples:
- Accommodation
- Beach
- Restaurant
- Waterfall
- Viewpoint
- ATM
- Shop
- Dive Center

Acceptance Criteria:
- Save a place
- Edit a place
- Delete a place
- Categorize a place

---

## FR-003 Expenses
Priority: High

The user can track travel expenses.

Acceptance Criteria:
- Add expense
- Edit expense
- Delete expense
- Assign expense to a category
- Display total trip costs

---

## FR-004 Photos
Priority: High

The user can attach photos to places.

Acceptance Criteria:
- Add photos
- View photos
- Delete photos

---

## FR-005 Notes
Priority: High

The user can store notes for every place and trip.

Examples:
- Opening hours
- Personal experience
- Recommendations
- Things to remember

---

## FR-006 Favorites
Priority: Medium

The user can mark places as favorites.

---

## FR-007 Offline Usage
Priority: High

Important travel information remains available without an internet connection.

---

## FR-008 Travel Timeline
Priority: Medium

The user can view visited places in chronological order.

---

## FR-009 Search
Priority: High

The user can search for:

- Places
- Notes
- Expenses
- Trips

---

## FR-010 AI Travel Assistant
Priority: Future

The assistant helps the traveller make better decisions.

Examples:
- Recommend nearby places
- Suggest activities
- Compare products
- Suggest dive schools
- Recommend restaurants
- Estimate costs

The assistant should support the traveller without taking control.

---

## FR-011 External Services
Priority: Future

Nomad Guide integrates external services whenever possible.

Examples:
- Booking.com
- Google Maps
- Dive shops
- Public transport
- Weather services

Nomad Guide should integrate instead of reinventing.

---

## FR-012 Travel Insights
Priority: Future

The application learns from previous trips.

Examples:
- Favorite activities
- Preferred accommodation
- Budget
- Travel style

The app should understand the traveller better over time without being intrusive.

---

# Non-Functional Requirements

## NFR-001 Easy to use

The application should require little explanation.

---

## NFR-002 Fast

The application should respond quickly.

---

## NFR-003 Offline First

Important information should be available offline.

---

## NFR-004 Reliable

User data must not be lost.

---

## NFR-005 Privacy

The user owns their travel data.

---

## NFR-006 Cross Platform

The application should work on Android, iOS and Desktop.

---

## NFR-007 Maintainable

The project should be modular and easy to extend.

---

## NFR-008 Scalable

Future features should be easy to integrate.

---

# Out of Scope

Nomad Guide is NOT:

- a booking platform
- a navigation replacement
- a travel agency
- a social media platform
- a photo editor

Instead, Nomad Guide integrates existing services whenever useful.

---

# Design Principles

- Built by travellers, for travellers.
- Solve real travel problems.
- Encourage discovery.
- Help users make better decisions.
- Learn without being intrusive.
- Integrate before reinventing.
- Simplicity over complexity.