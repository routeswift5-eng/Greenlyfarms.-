Greenly Farm

Smart Agricultural Farm Management System: a front-end prototype for managing a farm's crops, livestock, inventory and sales from one app.

The problem

Poor farm inventory management and difficulty tracking agricultural production.

The solution

A system for managing crops, livestock, farm activities, inventory and produce sales.

Major screens

Screen
What it does
Dashboard
Sales for the month, summary tiles, monthly sales chart, livestock mix, crop progress and a "Needs attention" list
Crops
A card per crop with field, acreage, planting and harvest dates, progress and status
Livestock
Headcount chart plus a list of each animal group with housing, health status and next vaccination
Inventory
Seeds, fertilizer, feed and stored produce, with a stock-level bar and low-stock flags
Sales
Total sales and a list of orders with buyer, quantity, price and total
Reports
Revenue, expenses and profit, income vs expenses chart, sales share and revenue by product, with a print button

Pages are reached through the bottom navigation bar, like a mobile app.

Features

• Add and remove crops, livestock, inventory items and sales
• Charts with labelled axes, gridlines and values
• Low-stock, harvest and health alerts on the dashboard
• Printable report
• Responsive layout for phone and desktop
• Follows the device's light or dark mode

Tech

• A single greenly-farm.html file
• Plain HTML, CSS and JavaScript, with no framework or build step
• Charts drawn with inline SVG
• Fonts: Bricolage Grotesque and Public Sans (Google Fonts, with system fallbacks)

Running it

Open greenly-farm.html in any modern browser. No install is needed.

Current limitations

This is a front-end prototype.

• All data is sample data held in the browser's memory, so changes are lost on refresh
• There is no login, backend or database
• Monthly figures for June to October in the charts are placeholders
• Crop status and progress are fixed when a crop is added and can't be edited
• Entries can be added and removed, but not edited

Next steps

• Connect a backend and database to save data
• Add user accounts and roles
• Edit existing entries
• Replace the placeholder monthly figures with real records

Customising

• Colors: edit the CSS variables at the top of the file (--forest, --lime, --sun, --sky, --clay)
• Sample data: edit the S object in the script, plus MON, REV and EXP for the monthly charts
• Farm name: change "Greenly Farm" in the header and the page title
