# LinkedIn In-App Browser Detector and Redirector

This is a simple website that detects when it's being opened in LinkedIn's in-app browser and provides options to open the page in the user's default browser. It's designed to be easily deployed on GitHub Pages.

## Features

-   Automatically detects LinkedIn's in-app browser
-   Attempts automatic redirection to the default browser
-   Provides a manual "Open in Browser" button as fallback
-   Clean, modern UI design
-   Mobile-responsive layout
-   No external dependencies

## How to Use

1. Fork this repository
2. Go to your repository settings
3. Navigate to "Pages" under "Code and automation"
4. Under "Source", select "Deploy from a branch"
5. Select the "main" branch and "/ (root)" folder
6. Click "Save"
7. Wait a few minutes for GitHub Pages to deploy your site
8. Your site will be available at `https://[your-username].github.io/[repository-name]`

## Testing

To test if it's working:

1. Share your GitHub Pages URL on LinkedIn
2. Open the link from the LinkedIn mobile app
3. The page should attempt to redirect automatically to your default browser
4. If automatic redirect doesn't work, click the "Open in Browser" button

## Customization

You can customize the website by modifying the following:

-   Edit the HTML content in `index.html`
-   Modify the CSS styles in the `<style>` section
-   Adjust the JavaScript behavior in the `<script>` section

## How It Works

The website uses the browser's User Agent string to detect if it's being opened in LinkedIn's in-app browser. When detected, it:

1. Attempts automatic redirection using various URL schemes
2. Displays a message informing the user they're in the LinkedIn browser
3. Provides a button to manually open the page in their default browser

## License

MIT License - feel free to modify and use as needed.
