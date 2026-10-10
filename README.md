# Food Bridge

**Share Food. Spread Hope. Reduce Waste.**

Food Bridge is a student web project based on a simple problem: good food often goes unused while people and community organisations need it. The idea is to give food donors a place to list surplus food and let NGOs browse those listings and request a pickup.

This repository currently contains a front-end prototype of that workflow.

## What you can do

- **Browse available food** and search by food name or description.
- **Filter listings** by food category and city.
- **Create a donation listing** with details such as quantity, unit, estimated servings, pickup deadline, address, dietary type, allergens and an optional image URL.
- **Request a pickup** as an NGO and include the quantity needed and a message for the donor.
- **Manage requests** from the donor dashboard, including approving, rejecting or marking a pickup as completed.
- **View dashboard summaries** for donations and pickup requests.
- Move between the Home, Browse Food, How It Works and About pages.

## Built with

- HTML5
- JavaScript and React 18
- React DOM 18
- Tailwind CSS (loaded from its CDN)
- Babel Standalone for compiling JSX in the browser
- Google Fonts (Inter)

The current app is kept in one main file: `BWT.F.html`. React components and the sample data are included in that file, so there is no separate build step at the moment.

## Run it locally

1. Clone the repository:

   ```bash
   git clone https://github.com/MATTURIMAHESH/FOODBRIDGE.git
   cd FOODBRIDGE
   ```

2. Open `BWT.F.html` in a browser.

   You can also open the folder in VS Code and run the file with the Live Server extension.

An internet connection is needed because React, Babel, Tailwind CSS, the font and some food images are loaded from external URLs.

## A note about this version

This is a working **front-end demonstration**, not a fully connected backend application yet. The donation and pickup-request examples are stored in React state, and the initial listings are sample data written in the HTML file. Changes made while using the page are not saved to a database and will reset when the page is refreshed.

The login and registration screens are also demo flows. There is currently no real user authentication, server-side API or database configured in this repository. These are natural next steps if the project is extended into a complete application.

## Possible next steps

- Add a backend API and connect it to the React interface.
- Store users, donations and pickup requests in a database.
- Implement real authentication and role-based access for donors and NGOs.
- Add stronger validation for quantities, pickup dates and food details.
- Test the full donation-to-pickup flow with persistent data.

## Project details

- **Project:** Food Bridge — Food Donation Marketplace
- **Course:** Backend Web Technology (BWT)
- **Team:** 3
- **Team lead:** M. Mahesh

### Team members

- M. Mahesh — Team Lead
- V. Eshwar
- A. Harah
- M. Satyaanda

---

Built as an academic project to explore how a simple web interface can support food donation and pickup coordination.
