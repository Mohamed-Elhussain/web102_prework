# WEB102 Prework - *Sea Monster App*

Submitted by: **Mohamed Abdelaal**

**Sea Monster App** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **10** hours spent in total

## Required Features

The following **required** functionality is completed:

* [✓] The introduction section explains the background of the company and how many games remain unfunded.
* [✓] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [✓] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [✓] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:
* [✓] Search Functionality - Users can search for specific games by name or description keyword
* [✓] Smooth Navigation - Navigation links smoothly scroll to different sections of the page
* [✓] Enhanced Game Cards - Interactive game cards with progress bars, funding statistics, and pledge buttons
* [✓] Active Filter States - Visual feedback showing which filter is currently active
* [✓] Filter Summary - Display showing how many games are currently being shown out of total
* [✓] Animations - Fade-in animations for game cards and hover effects
* [✓] Responsive Design - Improved mobile responsiveness for better user experience
* [✓] Progress Bars - Visual representation of funding progress for each game
* [✓] Interactive Pledge Buttons - Simulated pledge functionality with user feedback
* [✓] No Results State - Helpful message when search returns no matching games

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://youtu.be/61nbY1sLZrc' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ...  
<!-- Recommended tools:
Screen Recorded on Mac. -->

## Notes

1. **Data Formatting and Grammar**: Ensuring proper comma separation for large numbers using `toLocaleString()` and handling singular/plural forms correctly with ternary operators.

2. **DOM Management**: Learning to properly clear elements using `deleteChildElements()` before adding new content to prevent game cards from accumulating when filters are applied.

3. **Event Handling**: Coordinating multiple event listeners for buttons and ensuring they work together without conflicts, especially when combining filtering and search functionality.

4. **Data Sorting and Destructuring**: Understanding how to sort games by pledged amount and use destructuring to extract the top two games for the statistics section.

5. **Search Implementation**: Creating a robust search function that filters games by both name and description while handling edge cases like empty search results.

6. **Responsive Design**: Making the game cards and search bar work well on different screen sizes, especially mobile devices.

## License

    Copyright [2026] [Mohamed Abdelaal]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
