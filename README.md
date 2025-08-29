# Centscape Unified Wishlist

## Setup & Run Instructions

### App (React Native + Expo)
1. `cd app`
2. `npm install`
3. `npm run start` (Expo)
4. `npm run typecheck` (TypeScript check)

### Server (Node.js)
1. `cd server`
2. `npm install`
3. `npm run dev` (development)
4. `npm run test` (run tests)

## Engineering Tradeoffs & Risks
- Used OpenGraph, Twitter Card, and custom selectors for metadata extraction; may require updates for edge cases or new sites.
- SSRF, rate-limit, and size/redirect caps are enforced in the backend, but may need tuning for production scale.
- Chose Expo for rapid mobile prototyping; native modules may require extra configuration for production.
- No authentication or user management included (out of scope for MVP).

## AI Usage Disclosure
- GitHub Copilot and GPT-4 were used to generate code snippets, extraction logic, and documentation structure.
- Prompts included: PRD breakdown, extraction logic, SSRF guard, and test scaffolding.
- All code was reviewed and adapted for project requirements.
