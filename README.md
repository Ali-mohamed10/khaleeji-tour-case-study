# Khaleeji Tour

[Visit the live event and ticketing platform](https://www.khaleejitour.com/)

I worked across the booking flow, from choosing a table on a venue map to issuing a QR ticket after payment. This case study describes the production application.

## Venue selection

I built an interactive React seat map that reflects the physical layout of each venue. Guests can zoom and pan, inspect a table, and review their selection before checkout. The map renders the room geometry and table positions. Separate components handle zoom controls, table details and the booking summary.

## From checkout to admission

I integrated Stripe Checkout and payment webhooks with the ticket service. A successful payment leads to a QR ticket that event staff can scan at the venue. The admin scanner gives staff a dedicated interface for check-in.

## Technologies

React, JavaScript, TypeScript, Node.js, Supabase and Stripe.

[Ali Mohamed’s portfolio](https://ali-dev400.vercel.app/)
