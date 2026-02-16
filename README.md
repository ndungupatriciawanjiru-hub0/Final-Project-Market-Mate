 #  Market Mate 

##  Project Overview
Market Mate is a simple browser-based web application designed to help mama mboga,small-scale vegetable and grocery sellers in Kenya,manage their roadside or kiosk businesses more effectively.
It allows users to add products, track stock levels, record daily sales, and view key summaries (total items ), with all data stored locally using localStorage for offline access.


## Problem Statement

Many mama mboga track stock and sales manually in notebooks or memory. This often leads to mistakes, forgotten stock levels, inaccurate sales records, and challenges in monitoring daily business activity. Market Mate offers a free, easy-to-use digital tool to manage stock and track sales more reliably without needing expensive software or constant internet.

## Features

1. Add new products (e.g. sukuma wiki, tomatoes, onions) using a simple form
2. Basic form validation with clear error messages
3. Store all data securely in the browser using localStorage
4. Automatically display saved products and stock on load
5. Dashboard with key business stats: Total Items
6. Record sales and update stock
7. Responsive layout that works perfectly on mobile phones, tablets, and desktops
8. Easy navigation across multiple linked pages

## Pages Included

1. Dashboard (index.html) – Welcome screen + summary stats cards (Total Items)
2. Add Stock (add-stock.html) – Form to add new products with fields like name, quantity, buy price, sell price
3. Sales (sales.html) – Page to record daily sales, select items and enter quantities sold
4. About (about.html) – Project purpose, team info, and possibly extra stats or tips for mama mboga
5. Inventory (inventory.html) – Displays inventory in a table.
All pages share data via JavaScript and are linked through a clean navigation menu.

##  Technologies Used

1. HTML5 – Semantic structure and accessibility
2. CSS3 – Styling, Flexbox/Grid, media queries for responsive design
3. JavaScript  – Form handling, validation, DOM updates, calculations, and localStorage
4. Git & GitHub – Version control and project hosting

##  Data Persistence

All the inventory, stock value and sales records data are saved in the browser's localStorage. Data persists across page refreshes and navigation,until the browser cache is cleared.

##  How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/ndungupatriciawanjiru-hub0/Final-Project-Market-Mate.git
 2.  Open the project folder in VS Code (or any code editor)
3.  Install the Live Server extension in VS Code 
4.  Right-click on index.html → Open with Live Server
5.  Use the navigation menu to switch between pages
6.  Start by adding products on the Add Stock page, then record sales!
 ## Live Demo

## Known Limitations
1. Data is stored only in your browser (lost if cache is cleared, different device, or incognito mode)
2.  No edit or delete options for products/sales yet
3. No backend/database,no cloud sync or multi-user support
4.  Basic features only (no advanced reports, categories, expiry dates for perishables, or expense tracking)
## Learning Outcomes
1. Semantic HTML for better structure and accessibility
2. Mobile-first responsive design with CSS media queries
3. JavaScript DOM manipulation, event listeners, and form validation
4. Persistent data management across pages using localStorage
5. Practical application of front-end skills to solve real Kenyan small-business problems
6. Team collaboration and Git/GitHub workflows
## Collaborators (Syntax Sisters)
1. Mercy (@mercymnn6) – mercymnn6@gmail.com
2. Patricia – ndungu.patriciawanjiru@gmail.com
3. Michelle – michellemugo93@gmail.com
Questions, feedback, or ideas? Reach out via email or open an issue!
## License
MIT License
Copyright (c) 2026 Syntax Sisters.
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction.