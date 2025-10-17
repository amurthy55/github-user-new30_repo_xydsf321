# GitHub User Fetcher

## Summary
A simple web application that fetches a GitHub user's account creation date based on their username and displays the account age.

## Setup
1. Clone the repository.
2. Open `index.html` in a web browser.

## Usage
1. Enter a GitHub username in the input field.
2. Click the 'Fetch User' button to display the account creation date and age.

## Code Explanation
- The form with id `github-user-1` captures the GitHub username.
- On form submission, a fetch request is made to the GitHub API to retrieve user data.
- The account creation date is displayed alongside the calculated account age in years.
- Status updates are provided via an aria-live alert for accessibility.
- The last successful lookup is cached in localStorage for repopulation on page load.

## License
This project is licensed under the MIT License.