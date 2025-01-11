# roxiler_assignment
Roxiler System Assessment - Frontend and Backend
# Backend Tasks
Data Source: Fetch data from the third-party API:
URL: https://s3.amazonaws.com/roxiler.com/product_transaction.json
Method: GET
Response Format: JSON

API Requirements:

Initialize Database: Create an API to fetch JSON data from the third-party API and seed the database.
List All Transactions:
Support search and pagination on product transactions.
Search by product title, description, or price.
Default pagination: page = 1, per page = 10.
Statistics API: Provide:
Total sale amount for the selected month.
Total number of sold items for the selected month.
Total number of unsold items for the selected month.
Bar Chart API: Return price ranges and the number of items for the selected month:
Ranges: 0-100, 101-200, ..., 901-above.
Pie Chart API: Find unique categories and their item counts for the selected month.
Combined API: Merge data from the above APIs into a single response.

# Frontend Tasks
Transactions Table:

Display transactions using the listing API.
Include a month dropdown (January-December) with March selected by default.
Support search functionality and pagination.
Statistics Section:

Show total sale amount, total sold items, and total unsold items for the selected month using the statistics API.
Bar Chart:

Display price ranges and the number of items using the bar chart API.
Pie Chart:

Visualize unique categories and item counts using the pie chart API.
