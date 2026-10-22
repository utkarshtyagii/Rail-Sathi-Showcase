# Rail Sathi 🚆

**A Railway Porter Booking Platform**

Rail Sathi is a web application prototype designed to help railway passengers request porter assistance for carrying luggage at railway stations.

## Overview

The project explores a digital workflow for requesting luggage assistance, assigning verified porters, tracking booking progress, and collecting feedback after service completion.

## Key Features

- **Passenger accounts and bookings** — create an account and request porter assistance.
- **Porter applications** — allow porters to apply and manage their availability.
- **Staff review and assignment** — review applications and assign bookings.
- **Booking status tracking** — follow a booking through its service stages.
- **Consent-based live-location prototype** — share participant locations for an active booking when permission is granted.
- **Handoff confirmation codes** — use booking-specific codes during service handoff.
- **Ratings and feedback** — collect feedback after a completed booking.
- **Payment integration support** — includes a Razorpay checkout flow that requires configuration and testing.
- **Support requests** — submit requests for staff review.

## Technology Stack

- Python
- Flask
- HTML, CSS, and JavaScript
- Flask-SocketIO
- Database migrations
- Google Maps JavaScript API integration
- Razorpay integration

## Project Status

Rail Sathi is a development prototype. External services and production features must be configured and tested before the application is used for real passenger trips. Depending on the deployment, this may include payment processing, email and SMS delivery, production database setup, and operational support workflows.

## Privacy and Security

- Do not commit `.env` files, credentials, private keys, or database files containing private data.
- Restrict browser API keys to approved website referrers and required APIs.
- Keep payment-provider secrets on the server and verify payment responses server-side.
- Request participant consent before sharing device location.
- Establish appropriate data-retention, support, and identity-review procedures before production use.

## Future Improvements

- Production deployment and database configuration
- Account recovery and reliable notifications
- Improved booking and location-tracking experience
- Production-ready payment, refund, and support workflows

## Disclaimer

This project is a prototype for demonstration and development. Do not use it to accept real bookings or payments until the deployment, security, privacy, and operational processes have been reviewed and tested.

---

**Rail Sathi** — making railway porter assistance easier to request and manage.
