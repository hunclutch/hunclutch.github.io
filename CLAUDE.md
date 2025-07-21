# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static personal website for Japanese musician "hunclutch", hosted on GitHub Pages. The site showcases music releases, streaming platform links, profile information, and video production services.

## Project Structure

- `index.html` - Single-page website with embedded CSS
- `art/` - Media assets directory
  - `hunclutch.jpg` - Profile image
  - `コンポ 1_8.mp4` - Video showcase for video editing services

## Architecture

This is a simple static HTML website with:
- Embedded CSS styling within `<style>` tags
- Japanese language content (lang="ja")
- Responsive design with mobile breakpoints
- External embeds (YouTube iframe, streaming service icons)
- Local media assets (profile image and video)

## Development Notes

- No build process required - direct HTML/CSS editing
- GitHub Pages deployment automatically handles the main branch
- Mobile-responsive design with breakpoint at 768px
- Color scheme: dark theme with gradient header (#3a1c71, #d76d77, #ffaf7b)
- External dependencies: None (pure HTML/CSS)

## Content Structure

The site contains these main sections:
- Header with artist name and tagline
- Latest release (YouTube embed)  
- Profile section with image and bio
- Streaming platform links (Apple Music, Spotify, YouTube Music)
- Video production services showcase
- Contact footer