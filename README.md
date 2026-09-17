COMPLETELY REDESIGN THE EXISTING WEBSITE for my DAA project:

# 🧳 TRAVELLING SALESMAN PROBLEM

### “Help the salesman find the shortest route.”

Make it modern, simple, attractive, interactive, and fully responsive for **laptop, desktop, tablet, and mobile**.

## 1. HOME

Show:

* Travelling Salesman character
* Map with city locations
* Short TSP introduction
* START SIMULATION button

## 2. TSP THEORY

Briefly explain:

* What is TSP?
* Problem statement
* Objective
* Real-life applications
* Weighted graph / Hamiltonian cycle

Use simple travel/map-themed diagrams.

## 3. INPUT

Allow the user to enter:

* Number of cities
* City names
* Starting city
* Distance matrix

Add a **Demo Input** button.

## 4. ACTUAL TSP WORKING ⭐

Show the real solution using **Dynamic Programming**, step by step:

INPUT
↓
Distance Matrix
↓
DP States
↓
DP Calculations
↓
DP Table
↓
Minimum Cost
↓
Route Reconstruction
↓
Final Route

Use:

`dp[mask][city]`

Show actual calculations and intermediate values.

**Do not use hard-coded/fake results.** The result must depend on the user's input.

## 5. VISUAL MAP

During execution:

* Highlight cities
* Highlight routes being considered
* Show salesman moving along the route
* Highlight the final shortest route

## 6. COMPLEXITY ANALYSIS ⭐

Add a dedicated section:

### Dynamic Programming

**Time Complexity:**
`O(n² × 2ⁿ)`

**Space Complexity:**
`O(n × 2ⁿ)`

Briefly explain that the number of states grows exponentially with the number of cities.

Also show a simple visual comparison:

| Method              | Time Complexity |
| ------------------- | --------------- |
| Brute Force         | `O(n!)`         |
| Dynamic Programming | `O(n² × 2ⁿ)`    |
| Nearest Neighbor    | `O(n²)`         |

Add a small graph showing how computation increases as the number of cities increases.

## 7. FINAL RESULT

Display:

**Optimal Route:**
A → B → C → D → A

**Minimum Distance:**
XX km

**Cities Visited:**
X

The salesman should celebrate after completing the optimal journey.

## 8. DESIGN

Use a clean **Travel + DAA** theme:

* Dark Navy
* Blue
* Golden/Yellow
* White
* Glowing city nodes
* Map background
* Animated routes
* Modern cards
* Clean typography

Do not overcrowd the UI.

## 9. RESPONSIVE DESIGN

Laptop/Desktop:
**Map + DP calculation side-by-side**

Mobile:
**Input → Map → DP Steps → Complexity → Result**

No horizontal scrolling, overlapping, or clipped content.

## MOST IMPORTANT

The website must demonstrate the **REAL WORKING OF TSP USING DYNAMIC PROGRAMMING**:

**Enter Input → Process Step-by-Step → Show DP States → Show Calculations → Show Complexity → Reconstruct Route → Display Actual Shortest Route.**

Keep the website simple, professional, interactive, and suitable for a DAA college project demonstration.
