# GitHub User Lookup

## Summary
This is a simple web application that allows users to look up GitHub user profiles. It displays the user's account age and caches the last successful lookup in localStorage.

## Setup
1. Clone the repository.
2. Open `index.html` in a web browser.

## Usage
- Enter a GitHub username in the input field and click 'Lookup'.
- The application will display the account age in years and the creation date of the account.

## Code Explanation
- The app uses the GitHub API to fetch user data.
- It displays status updates using `aria-live` for accessibility.
- The account age is calculated based on the creation date of the GitHub account.
- The last successful lookup is cached using localStorage.

## License
This project is licensed under the MIT License.

## Description
This app enhances user experience by providing real-time feedback on lookups and caching results for quicker access.