AI-FLIGHT-RESERVATION-CHATBOT

Overview

This project is a React (Next.js) + TypeScript implementation of a flight booking interface. It allows users to select a source city, destination city, and travel date, then fetches available flights based on the selected route.

Features

Step-based Booking Flow: Source & destination selection, date selection, and flight listing.

Interactive UI: Uses ShadCN UI components for a smooth user experience.

Flight Filtering: Retrieves flights based on user input.

Date Selection: Uses date-fns for date formatting.

Technologies Used

TypeScript – Strongly typed JavaScript.

React (Next.js) – Modern frontend framework.

ShadCN/UI – For UI components like buttons, input fields, and calendars.

Date-fns – For handling and formatting dates.

Lucide-react – For icons.

Installation

Clone the repository:

git clone https://github.com/your-username/flight-booking.git
cd flight-booking

Install dependencies:

npm install

Run the development server:

npm run dev

Open in your browser:

http://localhost:3000

File Structure

├── components/
│   ├── ui/
│   │   ├── button.tsx
│   │   ├── input.tsx
│   │   ├── label.tsx
│   │   ├── calendar.tsx
│   │   ├── popover.tsx
│   ├── BookingFlow.tsx
│
├── lib/
│   ├── data.ts (Flight filtering logic)
│   ├── types.ts (Type definitions for Flight object)
│   ├── utils.ts (Helper functions)
│
├── pages/
│   ├── index.tsx (Main page rendering BookingFlow)
│
├── public/
├── styles/
├── README.md
├── package.json
├── tsconfig.json

How It Works

User selects a departure and destination city.

User picks a travel date.

System fetches available flights based on the route and date.

Flights are displayed, allowing the user to select one.

Future Enhancements

Integrate a real flight API (e.g., Amadeus API, Skyscanner API).

Add user authentication.

Improve UI with animations and better styling.

Contributing

Feel free to contribute! Open an issue or submit a pull request.

License

This project is licensed under the MIT License.

