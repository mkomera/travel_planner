
# Travel_Planner_AI_Chatbot

This intelligent AI-powered Travel Planner chatbot is capable of managing user profiles, delivering real-time hotel and activity recommendations, and tailoring its responses based on individual preferences. It integrates external APIs to retrieve flight and hotel information.

## Background

The chatbot is developed to improve the user experience in travel planning by delivering customized support. It suggests top hotels and builds personalized itineraries based on selected destinations. With the help of advanced algorithms and user data, it simplifies the travel planning process for greater ease and enjoyment. 

## Objectives

1. **User Support:**  
   Offer a conversational platform that assists users in booking hotels, activities, and flights.

2. **API Connectivity:**  
   Connect with OpenAI for natural language understanding and Amadeus for accessing travel content.

3. **User Interface:**  
   Develop an intuitive and clean web interface for easy interaction.

4. **Responsive Dialogue:**  
   Enable the chatbot to respond dynamically, based on user context.

5. **Profile Handling:**  
   Create and maintain personalized user profiles for tailored service.

## Development Approach

### 1. Define Functional Needs

- Core features: search for hotels, flights, and destination activities.
- Establish chatbot interaction flows and expected responses.

### 2. Environment Setup

- Required libraries:  
  - Flask (backend framework)  
  - OpenAI SDK (ChatGPT integration)  
  - Amadeus SDK (travel data access)  
- Use a virtual environment for dependency management.

### 3. System Design

**Main Components:**  
- **UI:** Built using HTML and JavaScript for user interaction.  
- **Backend (app.py):** Manages routing and requests via Flask.  
- **OpenAI API:** Powers NLP for chatbot responses.  
- **Amadeus API (travel_api.py):** Gathers hotel, flight, and activity data.  
- **User Profiles (user_profiles.py):** Stores preferences and history.  
- **Logic Layer (functions.py):** Handles user input and API communication.

### 4. Backend Implementation

- `app.py`:  
  - Sets up routes for the home page and chatbot interaction.  

- `user_profiles.py`:  
  - Manages user data and preferences.

- `functions.py`:  
  - Contains the core logic for interpreting queries and using APIs.  
  - Leverages OpenAI for activity suggestions.

### 5. Frontend Design

- `bot.html`:  
  A user-friendly interface built with HTML and JavaScript for smooth chatbot interaction.

## System Architecture

*(Architecture visuals or details to be added as required.)*

## Prerequisites and Tech Stack

### Frontend

- **HTML:** Page structure and layout  
- **CSS:** Styling and presentation  
- **JavaScript:** Adds interactivity and handles user events  
- **jQuery:** Simplifies AJAX and DOM operations

### Backend

- **Python:** Primary language for server logic  
- **Flask:** Web framework for routing and handling requests  
- **OpenAI API:** NLP capabilities for chatbot dialogue  
- **Amadeus API:** Fetches travel-related information

## Challenges

1. **API Integration:**  
   - Addressing authentication, response parsing, and rate limits across multiple APIs.

2. **Data Formatting:**  
   - Ensuring clean, readable output from complex JSON API responses.

3. **Parsing Inputs:**  
   - Extracting relevant travel info from diverse user expressions.

4. **Robust Error Handling:**  
   - Managing API errors gracefully while giving users useful feedback.

## Lessons Learned

1. **Value of Documentation:**  
   - Thoroughly studying API docs is essential for proper integration.

2. **User-Centric Thinking:**  
   - Prioritizing user experience results in better engagement and usability.
