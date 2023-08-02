# Netflix Engineering Team - Content Recommendation and User Experience Enhancement Project
This project aims to improve the user experience on the Netflix platform by implementing various features related to search, recommendation, demographics, cache management, and more.

## Features (Challenges to complete)
- Relevant Search Results: Enable users to see relevant search results despite minor typos.


- Top-Rated Movies Worldwide: Allow users to view the top-rated movies worldwide, considering movie rankings available separately for different geographic regions.


- User Demographics: Implement functionality to efficiently update the median age of viewers whenever a new user signs up for Netflix.


- Content Popularity Analysis: Determine titles that are gaining or losing popularity scores for efficient content distribution and program recommendation.


- Cache Management (LRU): Implement a cache with a replacement strategy that replaces the least recently watched title.


- Cache Management (LFU): Implement a cache with a replacement strategy that replaces the least frequently watched titles.


- Session History Navigation (Stack): Allow users to move back and forth in the history of programs they've just browsed using a stack data structure.


- Session History Validation: Check the correctness of the "next" and "previous" functionality using session history.


- Movie Marathon Permutations: Generate all possible viewing orders of movies appearing in a specific sequence of genres.


- Buffering Event Recording: Record the median number of buffering events that might occur in a user session to improve the user experience.


- Movie Marathon Customization: Generate all possible permutations of movies in a given marathon to enhance the user experience.


- Revamped Continue Watching Bar: Improve the continue watching bar to return the most frequently watched show for users.


## Project Structure
The project is organized into several folders, each containing the necessary files to implement a specific feature:

- content-distribution-and-cache-management: Contains files related to content distribution and cache management.


- movie-marathon-and-permutation: Contains files related to movie marathon permutations.


- search-and-recommendation: Contains files related to search and recommendation functionality.


- user-demographics-and-statistics: Contains files related to user demographics and statistics.


- user-experience-and-history: Contains files related to user experience and history navigation.

## Docker Configuration
Each project folder contains a Dockerfile that specifies how to build the Docker image for that feature. The Docker images can be built and managed using docker-compose.yml


## Getting Started
Clone this repository to your local machine.

Build the Docker images for each feature using docker-compose:

    docker-compose build
    Run the Docker containers for the desired feature:


    docker-compose up <service-name>

**Replace <service-name> with the name of the feature you want to test.**


## License

This project is licensed under the MIT License - see the LICENSE file for details.