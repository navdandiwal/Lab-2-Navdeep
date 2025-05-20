# Cat Info Viewer 

## Overview
This project is a web-based application designed to view and interact with data about various cat breeds. Users can:
- View all cat names
- Filter cats by health issues
- View weights in Imperial or Metric
- See intelligence and child-friendliness
- Calculate average intelligence for all or child-friendly cats

## Files in the Project

This is HTML file that contains:
- The complete structure of the user interface
- All buttons, inputs, and a `pre` tag for output
- Inline CSS for basic styling
- Inline JavaScript (within `<script>...</script>`) for all functionalities

## Sources Used

- **Cat Data:**
  The example cat breed data (e.g., Abyssinian, Birman, Bengal) is based on real-world breed data structures from:
  - [TheCatAPI](https://thecatapi.com/)
  - Breed details like `health_issues`, `intelligence`, `child_friendly`, and `weight` ranges are simplified for demo purposes.
  - No API or external libraries were used—data is hard-coded into the JavaScript array.

## Work Done / Changes Made

1. **Display All Cat Names**
   - Button: `All Names`
   - Function: `showAllNames()`

2. **Filter Cats by Health Issue**
   - Input: Number (health issue ID)
   - Function: `filterByHealthIssue()`

3. **Show Cat Weights in Imperial or Metric**
   - Radio Buttons: `Imperial`, `Metric`
   - Function: `showWeights()`

4. **Intelligence and Child Friendliness**
   - Function: `showIntelligence()`

5. **Average Intelligence (All Cats)**
   - Function: `showAverageIntelligence()`

6. **Average Intelligence (Child-Friendly Only)**
   - Input: Child Friendly Threshold
   - Function: `averageChildFriendlyIntelligence()`
## Usage Instructions

1. Open `index.html` in any modern web browser.
2. Use the various buttons and inputs to interact with the cat data.
3. Read output in the gray box labeled `All results should be displayed here`.

## Author
- Created by: *Navdeep Singh*
