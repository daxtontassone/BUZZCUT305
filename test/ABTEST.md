# A/B Testing Plan for Buzzcut App

## A/B Test 1: Dark Mode vs. Light Mode

### A/B Test Name:
Dark Mode Impact on User Engagement

### User Story Number:
1,2,3,9

### Metric (from the HEART grid):
Engagement

## Hypothesis:
We have observed that users tend to spend more time in apps that have a dark mode option, as it can reduce eye strain and save battery life. By providing a dark mode option in the Buzzcut app, we believe that users will spend more time browsing, leading to higher engagement and interaction with posts. Our hypothesis is that users in the dark mode variant will have a 10% higher interaction rate with posts (likes, comments, shares) compared to users in the light mode variant.

## Experiment:
### Audiences: 
50% of our user base will be exposed to the dark mode, while the other 50% will continue using the light mode. Users will be randomly assigned to each variant.
### Duration: 
The experiment will run for 10 days to collect enough data and observe user behavior.
### Tracking with Firebase Analytics:

Post interactions (likes, comments, shares)
User engagement time
Screen views for the home screen and profile screen
## Variations:
### Variant A: Light Mode (Current Design)
All UI elements will be remain in light colors (mostly white).
Text will remain dark for readability.
### Variant B: Dark Mode
All current UI elements will have a dark theme variant.
Text will be changed to a lighter color for readability.
Background colors will be adjusted for contrast and readability.
Icons and images will be adjusted if necessary to suit the dark theme.


## A/B Test 2: Grid View vs. One-at-a-Time Scroll for Image Display

### A/B Test Name:
Impact of Image Display on User Interaction

### User Story Number:
3,9

### Metric (from the HEART grid):
Engagement and Task Success (We are looking at how the different displays affect user interaction and the ability to successfully view and engage with haircuts.)

## Hypothesis:
We hypothesize that a grid view will allow users to quickly scan and find hairstyles they are interested in, leading to higher engagement (likes, comments, and shares) and a more successful user experience. We expect to see a 15% increase in post interactions and a 10% increase in time spent on the home screen for users in the grid view variant compared to the one-at-a-time scroll view.

## Experiment:
### Audiences: 
50% of our user base will experience the grid view, while the other 50% will see the one-at-a-time scroll view. Users will be randomly assigned to each variant.
### Duration: 
The experiment will run for 30 days to ensure we capture enough data to make informed decisions.
### Tracking with Firebase Analytics:
Post interactions (likes, comments, shares).
Time spent on the home screen.
Number of posts viewed during a session.
## Variations:
## Variant A: One-at-a-Time Scroll View (Current Design)
Users see one image at a time and scroll down to view the next.
## Variant B: Grid View
Users see multiple images at once, arranged in a grid.
Tapping on an image enlarges it and provides options for interaction.
