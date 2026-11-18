# Aura Coffee Roasters — Final Project

A responsive website for a specialty café in Astana. It helps students, coffee lovers and other visitors explore the menu, plan a visit and try a demo account.

**Team SE-2510**

- Shalabay Madi
- Ibragim Yerkhan

## Run locally

Open the project folder in VS Code and use Live Server, or run `python -m http.server 8000` there and visit `http://localhost:8000/`. Bootstrap 5.3.3 and jQuery 4.0.0 are included. Only the live coffee guide requires an internet connection.

## Pages

| Page | What to try |
| --- | --- |
| Home | Explore the café, open the demo newsletter, and watch the counters. |
| Menu | Filter Hot or Cold, search by name or description, choose a suggestion, rate a drink, or explore the gallery and the live Coffee Guide. |
| About Us | Meet the team and search the FAQ. |
| Contact Us | Try the demo inquiry, choose Phone to validate a callback number, or copy the café's contact information. |
| Sign Up | Try invalid values, then create a demo account with a sample name, email, phone and password. |
| Log In | Test an incorrect password, then log in with the demo account. |
| Profile | Check the saved account details, reload the page, and log out. |

Use the Dark mode switch on any page, then navigate to another page to see the saved preference. Use only sample details for the demo forms. Account data and newsletter signups stay in this browser. The inquiry form simulates sending a message.

## Files

- `css/style.css` contains shared layouts, colors and animations.
- `js/theme.js` applies and stores the theme.
- `js/forms.js` contains shared field validation and local storage helpers.
- `js/account.js` handles sign-up, login, profile and logout.
- `js/script.js` drives the café's shared interactions, menu and contact form.
- `js/coffee-guide.js` loads ingredients from the [SampleAPIs Coffee endpoint](https://api.sampleapis.com/coffee/hot) and shows a fallback guide if the API is unavailable.
- `images/` stores the café photos. `vendor/` stores Bootstrap and jQuery with their licenses.

## Publish on GitHub Pages

Copy the **contents** of the project folder into the publishing folder of your GitHub repository so `index.html` is at the top level of that folder. Commit and push the changes, then check the Pages deployment and open the published site. Confirm that it shows Sign Up, Log In and Profile in its navigation.
