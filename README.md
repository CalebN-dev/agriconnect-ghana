# AgriConnect Ghana

A responsive digital agriculture platform for Ghanaian farmers, buyers, and agricultural experts.  
Empowers users to trade crops, view weather updates, and access agricultural knowledge.

## Features

- **Authentication:** Login/Sign Up modal for Farmers, Buyers, and Experts (mock logic).
- **Dashboard:** Quick stats for logged-in users (Active Crops, Total Sales, Pending Orders).
- **Marketplace:** Add, edit, delete, search, and filter crop listings. Only logged-in farmers can manage their own crops.
- **Weather Information:** Displays current weather and a 7-day forecast for Accra (mock data), plus weather alerts.
- **Knowledge Hub:** Farming tips, market insights, and expert advice cards.
- **Responsive Design:** Built with Tailwind CSS for mobile and desktop.
- **Dark Mode:** Automatically adapts to system theme.

## Technology Stack

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript

## Usage

1. Open `agric.html` in your browser.
2. Use the navigation bar to access Dashboard, Marketplace, Weather, and Knowledge Hub.
3. Log in or sign up to manage crops and view dashboard stats.
4. Add crop listings via the "Add Crop Listing" button.
5. Browse weather info and knowledge hub resources.

## Data Model

- All data is stored in-memory and resets on page reload.
- No backend or persistent storage is used.

## Customization

- To add real authentication or backend, integrate with an API.
- Replace mock weather/crop data with live sources as needed.
- Update contact info and branding in the footer.

# License

This project is licensed under the MIT License.

---

## MIT License

Copyright (c) 2024 AgriConnect Ghana

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
