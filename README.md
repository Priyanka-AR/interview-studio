# Interview Studio

A public interview preparation and tracking application built with AI-assisted development.

Live demo: https://priyanka-interview-studio.priyankagltz.chatgpt.site/

## Features
- Eight career tracks spanning data, clinical programming, technology and engineering
- Role tracking, job-description keyword suggestions and preparation checklists
- STAR stories, technical answer outlines and communication practice
- Question-theme comparisons, interview feedback and weekly reviews
- Individual signed-in workspaces, with anonymous session-only practice
- JSON backup and restore

## Stack
React, TypeScript, Vinext/Vite, Cloudflare Workers, D1 and Drizzle ORM.

## Getting started
Use Node.js 22.13 or later. Run `npm ci`, then follow SETUP_REFERENCE.md for build and local D1 migrations. This app uses Sites-hosted ChatGPT authentication; running locally does not provide production sign-in. Anonymous demo mode does not save to the server. Publishing source to GitHub does not recreate the hosted database or sign-in integration. GitHub Pages cannot run this server-backed app.

## Export notes
This export contains source code, not private interview records or database contents. Git history, credentials, dependencies and build outputs are excluded. The original Site project ID was removed from .openai/hosting.json. The legacy-owner email mapping in app/api/workspace/route.ts is replaced with priyankagltz@gmail.com. Configure that server-side mapping for your own deployment if needed; never let arbitrary visitors select another user's record key. The existing published Site is unchanged.

The job-description planner uses keyword matching and editable preparation templates. It does not call an AI model. Experience examples are illustrative and must be replaced with each person's verified work.

## Attribution
Product requirements and workflow direction: Priyanka Asok Kumar. Implementation created with AI-assisted development.
