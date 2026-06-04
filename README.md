# Capstone Project, Epicode - Giuseppe Tavella

ZeroChiamate is a CRM software for small/medium-sized cleaning companies that want to stop coordinating everything on WhatsApp.

The project has received interest and was leading to interesting collaboration opportunities.


<p align="center">
  <img src="zerochiamate_logo.png"/>
</p>

## Links

[Backend repo](https://github.com/tave8/operavion-crm-backend)

[Frontend repo](https://github.com/tave8/operavion-crm-frontend)

Company website: [zerochiamate.com](https://zerochiamate.com)

Production frontend: [app.zerochiamate.com](https://app.zerochiamate.com)

Production backend: [api.zerochiamate.com](https://api.zerochiamate.com)

Preview frontend: [develop.operavion-crm-frontend.pages.dev](https://develop.operavion-crm-frontend.pages.dev)

Preview backend: [api-preview.zerochiamate.com](https://api-preview.zerochiamate.com)

[Original project proposal](https://docs.google.com/document/d/1EIdHb_cuk0CNfgaP7Ehr8ypcwA4ANBVfMc9PIN9Ngf4/edit?tab=t.5lrcmi48nyuv)

## Features & Systems

- Shifts availability calculations
- Map of clients worksites
- Add users to your own company / Multi-tenant
- Different logins based on user role / Temporary password to reset on first login
- On signup, create Stripe customer / Company can manage Stripe subscription
- Send custom emails / from templates / with attachments
- Custom report / PDF / CSV generation from templates 
- Notifications 
- Alerts at custom intervals (daily, weekly etc.)
- Geocoding autocomplete
- Document text extraction / AI-powered document topic classifier
- AI-powered document discrepancy detector ("Expectation vs Reality" workflows)
- QR code generation
- Backend-protected files (go through DB, not cloud provider's public URL)
- UX: minimalist UI
- UX: WhatsApp-ready messages when add a user
- UX: data seeding (default checklists seeded on signup) 
- Email verification / Forgot password
- File / image upload
- Alert developer system when errors
- Database migrations
- APIs & libraries: Resend, Stripe, Anthropic, Apache Tika, Thymelaf, Geoapify etc. 
- Reusability and decoupling everywhere

## Facts

- Designed & implemented my own domain architecture, background job, forgot password and many abstraction layers 
- Deploy on Cloudflare & Railway
- 700+ commits
- 40k lines of code
- 400+ files


