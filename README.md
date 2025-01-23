# CineeBot | Movies Heaven

CineeBot is a movie discovery platform where users can explore various movies based on genres, providing a seamless and interactive experience powered by IBM WatsonX Assistant for personalized interactions.

## Features
- **Movie Search**: Users can search for movies by selecting a genre or term. Genres include Horror, Action, Drama, and more.
- **WatsonX Assistant**: Embedded chat feature to assist users and enhance interaction.
- **Movie Gallery**: Displays movie posters with detailed information like title, year, and type.
- **Endless Scroll**: Infinite loading feature for seamless navigation of search results.
- **Random Genre**: Clicking on "Random Genre" provides a random movie genre for quick suggestions.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Movie Data Source**: OMDB API
- **IBM WatsonX Assistant**: Chatbot for personalized user interaction
- **Cloud Integration**: IBM Cloud Object Storage for storing assets like movie posters, images, and other media

## Setup Instructions

### Prerequisites
1. **IBM Cloud Account**: Create an IBM Cloud account if you don't already have one.
2. **IBM WatsonX Assistant**: Set up a WatsonX Assistant instance and integrate your `integrationID` and `serviceInstanceID` into the script.
3. **OMDB API Key**: Sign up at [OMDB API](https://www.omdbapi.com/apikey.aspx) to get an API key for retrieving movie data.

### How to Use
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/ranjitcj/CineeBot.git
   cd cineebot
