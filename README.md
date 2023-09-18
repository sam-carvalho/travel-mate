# TravelMate: Your Intelligent Travel Planner

TravelMate app is a cutting-edge travel planning application designed to simplify and personalize the task of planning your next adventure. Powered by advanced AI and real-time weather data, this interactive platform generates customized travel itineraries that align with your preferences, budget, and the current climate of your desired destination.

## How to Run the App

To get TravelMate up and running on your local machine, please follow these steps:

### Prerequisites

- Make sure Node.js (v18.14.1 or higher) is installed on your machine before proceeding.

### Steps

1. **Clone the repository:** Clone the GitHub repository to your local machine

```sh
git clone https://github.com/sam-carvalho/travel-mate.git
```

2. **Navigate to the project directory:** Use the terminal to navigate into the directory of the cloned project

```sh
cd travel-mate
```

3. **Install dependencies:** Install the required dependencies by running the following command:

```sh
yarn install
```

4. **Start the development server:** Launch the development server using:

```sh
yarn dev
```

This will compile the project and start the app on a local development server. You should see a message indicating the server is running and listening on a specific port (e.g., http://localhost:4321).

5. **Access the app:** Open a web browser and go to the URL mentioned in the terminal. You can now explore and make use of the TravelMate app's features.

## Core Features

To be implemented:

### Interactive Chatbot "Mate"

Instead of boring forms, interact with our GPT-3-powered chatbot, "Mate". Whether you're a thrill-seeker looking for your next adrenaline rush or a relaxed traveler wanting to unwind, just tell Mate what you're looking for, and let it handle the rest.

### Real-time Weather Integration

Our application fetches real-time weather data for each of your potential travel destinations, ensuring that your travel plans align with current weather conditions. Don't let a surprise heatwave or unexpected showers ruin your vacation!

### Dynamic Itinerary Generation
Once Mate has gathered your preferences and factored in current weather data, it will provide a list of destination options. Upon selection, a detailed travel itinerary for each location will be generated, offering suggestions on activities, dining, and lodging.

### Dynamic Updates
Changed your mind or budget? With TravelMate, you're never locked in. Revisit your chat with Mate to adjust your preferences or click the "Refresh" button to get updated weather data. Your itinerary updates dynamically, offering new suggestions instantly.

### Mobile-Responsive Design

Plan your travel on the go! TravelMate is designed to be fully responsive, providing a seamless experience across all your devices—be it your desktop, tablet, or smartphone.

## Technology Stack

### Frontend

- Built using the Astro framework
- React components for dynamic user interfaces
- TypeScript for type-safe code
- Styled with Tailwind CSS for modern aesthetics

### Backend

- Serverless functions for API calls
- GPT-3 API for chatbot and itinerary suggestions
- Weather API for real-time weather updates

### State Management

- Local state management in React for user preferences and real-time updates.

## Feedback and Contributions

We welcome any feedback or contributions to enhance TravelMate. If you have any suggestions, issues, or ideas, please feel free to open an issue or fork and submit a pull request to the repository.

## License

TravelMate is released under the [MIT License](https://en.wikipedia.org/wiki/MIT_License).

Thank you for your interest in TravelMate! We hope you find it useful and enjoy using it.