# uk.thechels.themes.nnw.template

NetNewsWire Theme Template Repository

1. Use the 'Use Template' button to create a new repository based on this template.
2. Clone the new repository to your local machine.
3. Open the project in VSCode and customize the stylesheet as needed.
4. Commit and push your changes to the new repository.
5. Build and test your theme in NetNewsWire to ensure it looks and functions as expected.

## Customization

The main file to customize is `Stylesheet.css`. You can modify the colors, fonts, and layout to create your unique theme. Refer to the NetNewsWire documentation for specific CSS classes and elements you can target.

## Testing

Locally, there is an AI generated blog post in '/test/test.html' that you can use to test your theme. Open this file in a web browser to see how your theme styles the content. Make sure to refresh the page after making changes to the stylesheet to see the updates.

## Building

To build follow these steps:

1. Run Makefile to build the theme:

   ```bash
   make build
   ```

### MacOS

1. Open NetNewsWire and go to Preferences > Appearance.
2. Click on "Add Theme" and select the built theme file by opening the Zip file from the `Dist` directory.
3. Apply the theme and verify that it looks and functions as expected.

### iOS and iPadOS

1. To test your theme on iOS or iPadOS, you will need to use the Zip file in the `Dist` directory.
2. Create a x-callback URL to install the theme on your device. The URL should look like this: `netnewswire:/theme/add?url=<URL_TO_ZIP_FILE>`
3. Replace `<URL_TO_ZIP_FILE>` with the actual URL where your Zip file is hosted (e.g., on GitHub or a personal server).
4. Open the x-callback URL on your iOS or iPadOS device to install the theme in NetNewsWire following the app prompts.
