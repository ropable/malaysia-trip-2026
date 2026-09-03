# Copilot Instructions for Malaysia Trip Planning

## Project Overview

This repository tracks planning and record-keeping for a family trip to Malaysia in December 2026. The project is used to organize itineraries, budgets, accommodations, documentation, and other travel information.

## Project Structure

```
├── itineraries/          # Day-by-day plans, activities, locations
├── accommodations/       # Hotel bookings, Airbnb, guest houses
├── flights/              # Flight bookings, e-tickets, airport details
├── transportation/       # Ground transport (rental cars, buses, trains, taxis)
├── budget/               # Expense tracking, quotes, payment records
├── documentation/        # Passports, visas, insurance, medical records
├── dining/               # Restaurant recommendations, reservations
├── activities/           # Tours, tickets, adventure activities, bookings
├── local-info/           # Maps, guides, tips, emergency contacts
└── notes/                # General observations, ideas, lessons learned
```

## File Naming Conventions

- **Dates**: Use YYYY-MM-DD format (e.g., `2026-12-15-kuala-lumpur.md`)
- **Locations**: Use lowercase with hyphens (e.g., `petronas-towers`, `cameron-highlands`)
- **Documents**: Use descriptive names with dates when relevant (e.g., `flight-booking-2026-05-01.pdf`, `hotel-confirmation.pdf`)
- **Version tracking**: If updating a file, append status or version info in the filename (e.g., `itinerary-v1.md`, `budget-final.md`)

## Key Information to Maintain

1. **Itineraries**: Organize by location and date. Include:
   - Date(s) covered
   - Location(s)
   - Activities and timing
   - Transport arrangements
   - Meal plans/reservations

2. **Budget**: Track by category:
   - Flights, accommodations, activities, meals, local transport, miscellaneous
   - Include currency conversions and payment status

3. **Documentation**: Keep copies of:
   - Flight e-tickets and confirmations
   - Hotel/accommodation bookings
   - Travel insurance documents
   - Visa/passport info (safely)
   - Emergency contacts

4. **Local Info**: Collect:
   - Currency and exchange rates
   - Weather forecasts for December
   - Public holidays and local events
   - Emergency phone numbers
   - Maps and location guides

## Conventions

- **Markdown format** is preferred for most planning documents (easily readable, version-controllable)
- **Units**: Use metric units consistently (km for distance, kg for weight, liters for volume, °C for temperature)
- **Monetary amounts**: Always specify currency with amount. For currency conversion, use Australian dollars (AUD) as the reference (e.g., "RM 150 (≈ AUD 50)" for Malaysian Ringgit)
- **Time references**: Use 24-hour format for clarity (e.g., "14:30" instead of "2:30 PM")
- **Confirmation records**: PDF or image files for booking confirmations should be organized by type and date
- **Decision tracking**: When finalizing choices (hotels, activities), include:
  - Why this option was chosen
  - Cost and booking reference
  - Cancellation policy
  - Key contact/booking details

## Common Tasks

- **Add a new location/day**: Create a dated markdown file in `itineraries/`
- **Log an expense**: Add entry to `budget/` with category, amount (with currency), and date
- **Update itinerary**: Modify the relevant day file with confirmed activities, timings, and locations
- **Track bookings**: Create confirmation file in appropriate folder with booking reference and deadlines

## Notes for Future Sessions

- Consolidate related information by location for easier reference
- Keep all booking confirmations in one place for quick access during the trip
- Maintain a running checklist of pre-trip preparations (vaccinations, packing, notifications to bank, etc.)
- Document lessons learned and tips for future trips at the end of the project
- For Python commands, use `python3`
