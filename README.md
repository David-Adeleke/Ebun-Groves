# Ebun-Groves

Ebun-Groves is an app concept for connecting customers with trusted local gardening professionals.

## Vision
Create a simple, reliable platform where people can:
- Request gardening services (one-time or recurring)
- Get transparent pricing and availability
- Track job progress and communicate with providers
- Leave reviews and build trust in the marketplace

## Target Users
- **Homeowners / renters** who need garden care
- **Small gardening businesses** looking for steady bookings
- **Property managers** coordinating routine maintenance

## Core Service Types
- Lawn mowing and edging
- Weeding and bed maintenance
- Hedge/shrub trimming
- Seasonal clean-up
- Planting and garden setup
- Irrigation checks (basic)

## MVP Scope
### Customer Features
- Account creation and login
- Address + garden details profile
- Create service request (service type, date/time window, notes, photos)
- View quote estimate and booking status
- In-app chat with gardener
- Ratings and reviews after completion

### Gardener Features
- Professional profile setup
- Service area and availability calendar
- Accept/decline jobs
- Job status updates (accepted, in progress, completed)
- Basic earnings dashboard

### Admin Features
- User/provider verification
- Dispute handling
- Service/category management
- Basic operational reporting

## Suggested Initial Tech Stack
- **Frontend:** React + TypeScript
- **Backend:** Node.js (Express or NestJS)
- **Database:** PostgreSQL
- **Auth:** JWT or managed auth provider
- **Storage:** Object storage for garden/job photos
- **Payments:** Stripe (for card payments and payouts)

## Data Model (High-Level)
- `users` (customer/admin)
- `gardeners` (business profile, verification status)
- `services` (types/categories)
- `bookings` (request + assignment + status)
- `messages` (chat threads)
- `reviews` (ratings/comments)
- `payments` (charges/payouts)

## Product Milestones
1. **M1: Discovery & UX**
   - User journeys, wireframes, and requirements
2. **M2: MVP Build**
   - Auth, booking flow, provider dashboard, admin basics
3. **M3: Pilot Launch**
   - 1 city/region rollout, onboarding first providers
4. **M4: Optimization**
   - Pricing improvements, notifications, analytics, retention loops

## Next Build Steps
1. Initialize app monorepo (frontend + backend)
2. Implement authentication and user roles
3. Build booking workflow end-to-end
4. Add provider availability + assignment logic
5. Integrate payments and review system
6. Add monitoring, logging, and CI checks

## Contribution
As code is added, this repository should include:
- Setup instructions
- Architecture docs
- API contracts
- Testing and deployment workflows
