# PR Viewer

This React application allows you to view open pull requests from GitHub repositories in the All-Hands-AI organization.

This software was created by [OpenHands](https://github.com/All-Hands-AI/OpenHands).

## Setup

1. Clone the repository
2. Install dependencies: `npm install`
3. Create a `.env` file in the root directory and add your GitHub token:
   ```
   VITE_GITHUB_TOKEN=your_github_token_here
   ```
4. Run the development server: `npm run dev`
5. Open your browser and navigate to the URL provided by Vite (usually http://localhost:5173)

## Running Tests

To run the tests, use the command: `npm test`

## Building for Production

To build the app for production, use: `npm run build`

## Note

Make sure to replace `your_github_token_here` with an actual GitHub personal access token that has the necessary permissions to read repository and pull request information from the All-Hands-AI organization.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
