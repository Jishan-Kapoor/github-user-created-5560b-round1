# Static Web App README

## Summary
This static web app implements a Bootstrap page with a form that fetches a GitHub username and optionally uses a token to display the account creation date in YYYY-MM-DD UTC format.

## Setup
To deploy this app on GitHub Pages, follow these steps:
1. Fork this repository.
2. Upload the code to your GitHub repository.
3. Go to the repository settings.
4. Enable GitHub Pages in the Source section and choose the main branch for deployment.
5. Access your web app using the provided GitHub Pages URL.

## Usage
To access and use the web page:
1. Open the deployed web app in your browser.
2. Fill in the GitHub username and, optionally, the token using the form.
3. Submit the form to view the account creation date displayed under #github-created-at.
4. Optionally, you can pass a token as a query parameter to authenticate the GitHub API requests.

## Code Explanation
This web app consists of an HTML file with a Bootstrap form that fetches a GitHub username and displays the account creation date. The JavaScript code handles the form submission and GitHub API requests to fetch the account creation date in UTC format. It includes robust CSV parsing logic handling trailing newlines, empty rows, and more to ensure data accuracy.

## License
This project is licensed under the MIT License.