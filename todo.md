# Davi Capuzzo Website - Project TODO

## Core Features
- [x] Complete website with cinematic Neo-Noir design
- [x] Bilingual system (EN/ES) with language toggle
- [x] Hero section with parallax background
- [x] About section (The Player / The Journey)
- [x] Career Timeline with country flags (Brazil, Italy, Spain)
- [x] Player stats (Age 18, Height 177cm)
- [x] Testimonials section with coach photos
- [x] Skills section (Intelligence, Ability, Speed)
- [x] Scout Evaluation section with BeSoccer and Transfermarkt links
- [x] Highlights section with video placeholders
- [x] Beyond the Pitch section (About the Person)
- [x] Contact section with email and WhatsApp

## Media & Assets
- [x] Migrate all large media files to S3 CDN
- [x] Update all image references to CDN URLs
- [x] Add realistic country flags (Brazil, Italy, Spain)
- [x] Integrate real coach photos (Thiago Antunes, Paolo Moretti, Yassin Mohamed)

## Backend Integration
- [x] Add web-db-user feature (Express + PostgreSQL + tRPC)
- [x] Create submissions table in database schema
- [x] Implement saveSubmission database function
- [x] Create tRPC submissions.create procedure
- [x] Integrate notifyOwner for email notifications
- [x] Update PDFDownloadForm to use API endpoint
- [x] Add form submission validation
- [x] Add loading states to form
- [x] Add error handling to form

## Testing
- [x] Create submissions.test.ts with validation tests
- [x] Test required field validation (name, club, whatsapp)
- [x] Test valid submission data acceptance
- [x] All tests passing (5/5)

## Form Updates
- [x] Remove PDF download checkboxes/options
- [x] Change button text to "Enviar studio@rodrigoresende.com"
- [x] Connect form to backend API
- [x] Add success message after submission
- [x] Add network error handling

## Deployment Ready
- [x] Build passes successfully
- [x] All tests pass
- [x] No critical TypeScript errors (LSP warning only)
- [x] Database schema migrated
- [x] All images on CDN

## Next Steps
- [ ] Manual testing of form submission flow
- [ ] Verify email notifications work
- [ ] Test bilingual form submission
- [ ] Deploy to production

## Recent Updates
- [x] Remove logo from navigation menu
- [x] Replace with "Davi Capuzzo" text in elegant italic typography
- [x] Match hero section font style in navigation bar
