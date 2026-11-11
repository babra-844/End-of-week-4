
# SpendWise Dashboard Shell

## Project Overview

SpendWise is a modern personal finance dashboard interface designed to help users visualize their financial activities and spending categories.

This project focuses on building a responsive dashboard layout using HTML5 and modern CSS techniques, particularly CSS Grid and Flexbox.

The dashboard contains realistic static financial information. JavaScript functionality is not required for this stage.

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- CSS Flexbox
- Google Fonts

## Dashboard Features

### 1. Sidebar Navigation
The sidebar contains:
- SpendWise logo
- Dashboard navigation
- Transactions
- Budgets
- Reports
- Settings
- User profile
- Help section

### 2. Dashboard Header
The header displays:
- Welcome message
- Current dashboard date
- Notification icon
- User avatar

### 3. Financial Summary Cards

Three summary cards display:
- Total Balance
- Total Income
- Total Expenses

### 4. Spending Category Cards

Six category cards display realistic financial information:

- Food and Groceries
- Transport
- Rent and Housing
- Entertainment
- Savings
- Utilities

Each card includes an icon, spending amount, percentage, and progress indicator.

### 5. Recent Transactions

A transaction section displays sample financial activities, including transaction descriptions, categories, dates, and amounts.

## CSS Techniques Used

### CSS Grid
Grid is used for:
- The overall dashboard layout.
- Financial summary cards.
- Spending category cards.

### Flexbox
Flexbox is used for:
- Sidebar navigation.
- Header alignment.
- Category card content.
- Transaction rows.
- User profile section.

### CSS Custom Properties

The `:root` selector defines reusable theme variables for:
- Brand color
- Accent color
- Background color
- Surface color
- Primary text
- Secondary text
- Borders
- Shadows

### Responsive Design

A media query at 767px changes the dashboard into a single-column page layout.

The category cards adjust to two columns on smaller screens and one column on very narrow screens.

### Card Micro-interactions

Dashboard category cards include:
- Hover animations.
- Keyboard focus animations.
- Smooth transitions.
- Subtle movement using transform.
- Box-shadow effects.

All card interaction transitions last 200ms, satisfying the 250ms requirement.

### Dark Theme

The project supports automatic dark mode using:

`@media (prefers-color-scheme: dark)`

The dark theme overrides the CSS custom properties defined in `:root`.

## Project Structure

```text
spendwise-dashboard/
├── index.html
├── style.css
└── README.md
```

## How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Resize the browser to see the responsive layout.

## Responsive Testing

To test the mobile layout:

1. Open the dashboard in Google Chrome.
2. Right-click and select Inspect.
3. Click the Toggle Device Toolbar icon.
4. Select a mobile device or enter a custom screen width.
5. Test the layout below 768px.

## Conclusion

SpendWise demonstrates modern dashboard design using CSS Grid, Flexbox, CSS custom properties, responsive media queries, and accessible card micro-interactions.

The project provides the visual foundation for a future personal finance management application.
