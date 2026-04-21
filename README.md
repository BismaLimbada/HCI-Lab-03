# Lab 03: Interactive Feedback and System State
---

### Student Information
* **Name:** Bisma
* **Seat No:** B23110006022
* **Section:** A

---

## 1. Objective
This lab uses JavaScript to implement **Visibility of System State** and real-time user feedback.

## 2. HCI Concepts Applied
* **Visibility of System State:** A status `div` updates constantly to show the user exactly what is happening.
* **Feedback:** * **Hover:** The button changes color on `mouseover` to show it is clickable.
    * **Click:** The button shrinks slightly (`scale(0.95)`) when pressed to mimic a physical click.
* **Constraints:** A click limit is set to prevent errors. After 3 clicks, the system stops further input.

## 3. Implementation
* **Logic:** A counter tracks clicks. Once it hits the limit, `btn.disabled = true` is executed.
* **Visuals:** The button fades to 50% opacity and a red warning (⚠️) appears when the limit is reached.

---
