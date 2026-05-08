Project Prompt: Interactive Personal Finance Tracker
Goal: Create a functional, single-page "Personal Finance Tracker" that allows users to log income and expenses, see a live balance, and visualize their spending.

Requirements:

1. Layout & Sections (HTML):

Header: A clean title (e.g., "WealthWatch") and a large, prominent Current Balance display.

Transaction Form: Fields for "Description" (text), "Amount" (number), and "Category" (dropdown: e.g., Food, Rent, Salary, Entertainment).

Summary Cards: Two separate boxes: one showing Total Income (green text) and one showing Total Expenses (red text).

History List: A scrollable area that displays all past transactions with timestamps.

2. Styling & Design (CSS):

Theme: Use a "Dark Mode" aesthetic (dark charcoal background, neon accent colors) or a "Minimalist Mint" theme.

Responsiveness: The input form should sit next to the history list on desktops but stack on top for mobile users.

Visual Cues: Expenses should automatically have a minus sign (-) and a red border, while income has a plus sign (+) and a green border.

3. Interactive Logic (JavaScript):

Calculation Engine: Automatically update the Balance, Total Income, and Total Expense whenever a new item is added.

DOM Manipulation: Use JavaScript to create new list items dynamically so the page doesn't need to refresh.

Validation: Prevent submission if the amount is empty or not a number.

Delete Function: Each transaction should have a "Delete" button that removes the item and correctly updates the balance.

Persistence (Bonus): Use localStorage so the data stays saved even if the user refreshes the browser.

4. Documentation:

Keep the code in one single HTML file.

Add detailed comments explaining the math behind the balance calculation and how localStorage works.
