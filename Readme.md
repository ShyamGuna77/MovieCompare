# Movie Comparison Autocomplete

## Overview

This project implements an autocomplete feature for searching movies using the OMDB API. Users can enter a movie title in the search input, and the application will provide a list of matching movies, displaying relevant information and enabling easy selection for comparison.

## Features

- **Autocomplete Search**: Users can type movie titles, and the application will suggest relevant options in real-time.
- **Dynamic Dropdown**: The results are displayed in a dropdown menu that activates when there are matching results.
- **Detailed Movie Information**: Once a movie is selected, detailed information, such as awards, box office earnings, and ratings, is shown for comparison.
- **Responsive Design**: The interface is user-friendly and adapts well to different screen sizes.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-name>


## Usage
- Start typing a movie title in the search input field.
- The dropdown will display a list of matching movies.
- Click on a movie from the dropdown to view its details for comparison.

## Code Explanation
 ### key Components
- **createAutoComplete** Function: This function initializes the autocomplete feature, rendering the search input and handling user interactions.
- **fetchData Function**: Fetches movie data from the OMDB API based on the user's input.
- **renderOption Function**: Formats the display of movie options in the dropdown.