# Conference Expense Planner

## Description
The **Conference Expense Planner** is a dynamic React application designed to assist in planning and budgeting for conference events. It offers an intuitive interface for selecting various event requirements such as venue rooms, audio/visual equipment, and meal plans, providing real-time cost estimations.

## Features
- **Venue Selection**: Browse and select from different venue options including Conference Rooms, Auditoriums, and Presentation Rooms. Each venue type has specific capacities and associated costs.
- **Add-ons (AV Equipment)**: Add necessary equipment like Projectors, Speakers, and Microphones to your event plan.
- **Meal Planning**: Select meal options (Breakfast, High Tea, Lunch, Dinner) and specify the number of attendees to calculate catering costs accurately.
- **Real-time Cost Calculation**: Instantly view the subtotal for each category (Venue, add-ons, Meals) and the comprehensive total cost.
- **Order Summary**: A detailed view of all selected items, quantities, and their individual costs.
- **Responsive Design**: User-friendly interface accessible on various devices.

## Technologies Used
- **Frontend**: [React](https://react.dev/)
- **State Management**: [Redux Toolkit](https://redux-toolkit.js.org/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: CSS3

## Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd conference_event_planner
   ```

2. **Install dependencies:**
   Make sure you have Node.js installed. Then run:
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   The application will typically be available at `http://localhost:5173`.

## Usage
1. **Landing Page**: Click on the **"Get Started"** button to enter the planner.
2. **Venue Selection**: Use the increment/decrement buttons to choose the number of rooms required. Note that some venues like the Auditorium Hall have quantity limits.
3. **Add-ons**: Select the quantity of AV equipment needed for the event.
4. **Meals**: Enter the **Number of People** expecting to attend. Select the desired meal types (Breakfast, Lunch, etc.) using the checkboxes.
5. **Review Costs**: The total cost for each section is displayed at the bottom of its respective card.
6. **Show Details**: Click the **"Show Details"** button in the navbar to view a comprehensive breakdown of your selected items and total expenses.

## Project Structure
```
conference_event_planner/
├── src/
│   ├── assets/             # Static assets (images, etc.)
│   ├── AboutUs.jsx         # About Us component
│   ├── App.jsx             # Main application component
│   ├── App.css             # Main stylesheet
│   ├── ConferenceEvent.jsx # Core event planning component
│   ├── ConferenceEvent.css # Styles for the event planner
│   ├── TotalCost.jsx       # Component for displaying cost summary
│   ├── avSlice.js          # Redux slice for Audio/Visual state
│   ├── mealsSlice.js       # Redux slice for Meals state
│   ├── venueSlice.js       # Redux slice for Venue state
│   ├── store.js            # Redux store configuration
│   └── main.jsx            # Entry point
├── public/                 # Public static assets
└── package.json            # Project dependencies and scripts
```

## Contributing
Contributions are welcome! If you'd like to improve this project, please feel free to fork the repository and submit a pull request.

## License
This project is open source and available under the information in the [LICENSE](LICENSE) file.