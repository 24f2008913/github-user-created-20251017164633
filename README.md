# GitHub User Created Date Fetcher

## Description
The **GitHub User Created Date Fetcher** is a web application that allows users to input a GitHub username and retrieve the account creation date in UTC format. Built using Bootstrap for responsive design, this application provides a user-friendly interface and leverages the GitHub API to fetch user data. The application can optionally authenticate requests using a personal access token.

## Features
- **User Input**: A simple form to input a GitHub username.
- **Token Support**: Optionally use a personal access token for authenticated requests.
- **Responsive Design**: Built with Bootstrap for a seamless experience across devices.
- **Date Display**: Displays the account creation date in the format YYYY-MM-DD UTC.
- **Live Demo**: Easily accessible through a live demo link.

## Setup Instructions
To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/24f2008913/github-user-created-20251017164633.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd github-user-created-20251017164633
   ```

3. **Open the `index.html` file**:
   You can use any web browser to open the HTML file directly or set up a local server.

4. **Install Dependencies** (if necessary):
   This project uses Bootstrap, which can be included via CDN in the HTML file. No additional installations are required.

## Usage Guide
1. Open the application in your web browser:
   [Live Demo](https://24f2008913.github.io/github-user-created-20251017164633/)

2. Enter a GitHub username in the input field.

3. (Optional) If you have a personal access token, append it as a query parameter in the URL:
   ```
   ?token=YOUR_PERSONAL_ACCESS_TOKEN
   ```

4. Click the "Submit" button to fetch the account creation date.

5. The creation date will be displayed in the specified format inside the designated area.

## Code Explanation
The core functionality of the application is implemented in JavaScript, which interacts with the GitHub API. Here’s a brief overview of the main components:

- **HTML Structure**: The form is defined with an `id` of `github-user-test`, which captures the username input.
  
- **JavaScript Fetch API**: 
   - The application uses the `fetch` function to make a GET request to the GitHub API endpoint for user data.
   - Upon receiving a response, it extracts the `created_at` field from the JSON response, which contains the account creation date.
   - The date is then formatted to YYYY-MM-DD UTC and displayed in the designated output section.

- **Error Handling**: The application includes basic error handling to manage cases where the username does not exist or if there are issues with the API request.

## License Information
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

For further inquiries or contributions, please feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/24f2008913/github-user-created-20251017164633). Thank you for your interest in the GitHub User Created Date Fetcher!