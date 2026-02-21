# BCE Map – Bitcoin Circular Economies

Interactive map prototype designed to visualize and explore Bitcoin Circular Economies (BCEs) globally.

## Overview

BCE Map is a lightweight, browser-based geographic visualization tool built to locate, filter, and explore Bitcoin Circular Economies across different cities and regions.

The objective was to create a simple, fast, and independent interface that makes ecosystem discovery intuitive and accessible.

## Purpose

The project aims to:

- Visualize Bitcoin Circular Economies geographically  
- Enable filtering by city  
- Allow keyword-based search (name, country, region)  
- Facilitate discovery through randomized exploration  
- Provide direct access to ecosystem profiles  

It serves as a structured, visual layer over a curated dataset.

## Core Features

- Interactive world map (Leaflet + OpenStreetMap)
- Dynamic city filtering
- Search functionality (name / country / region)
- “Discovery Mode” random ecosystem selector
- Popup interface with notes and external links
- Automatic map fitting to filtered results
- Lightweight JSON-based data source (`bces.json`)
- Zero backend dependencies

## Technical Stack

- HTML
- Custom CSS
- Vanilla JavaScript
- Leaflet.js
- OpenStreetMap tiles
- JSON data structure
- Static deployment (GitHub Pages compatible)

## Architecture

- Data-driven marker rendering
- Dynamic filtering logic
- Cache-busted JSON fetch to prevent stale CDN responses
- Modular marker creation function
- FeatureGroup-based automatic bounding
- Stateless frontend implementation

The system is intentionally minimal and fully client-side.

## Status

Functional prototype.

Designed as a foundation for potential expansion, including:

- Additional metadata layers
- Category-based filtering
- Analytics integration
- API-driven data sourcing
- Community submission flow

## Notes

This project reflects an interest in ecosystem mapping, infrastructure visibility, and open digital tools that support decentralized networks.
