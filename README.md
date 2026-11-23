# Chaurasiya Traders Billing System

A mobile-friendly, single-page billing app. Open `index.html` in a browser or publish the folder with GitHub Pages.

## Included
- Customer details and sequential bill numbers
- Multiple line items, quantity, rate and automatic totals
- Optional GST percentage and discount
- Invoice preview and print
- Saved bill history, search, dashboard
- Shop details, JSON backup and restore
- Responsive layout for phones

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` to the repository root (the main folder).
3. Commit changes.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then Save.
7. Wait for GitHub Pages to publish the site.

## Important data note
This starter version stores bills in the browser's local storage on the device/browser being used. It does not sync across devices or provide staff logins/cloud backup. Use **Settings → डेटा बैकअप डाउनलोड** regularly. Do not clear browser data before exporting a backup.

## WhatsApp invoice image
The app generates a designed PNG invoice. On supported Android/mobile browsers, **WhatsApp पर भेजें** opens the system share sheet with the image and message; choose WhatsApp and the customer's chat. If file sharing is not supported, it downloads the PNG and opens WhatsApp with the message; attach the downloaded image manually. A browser cannot silently send a WhatsApp message or image without the user's confirmation.

Invoice layout updated to match the supplied navy-and-white sample design. GST defaults to 1.25% and can be changed per bill. Proprietor text is configurable in Settings.
