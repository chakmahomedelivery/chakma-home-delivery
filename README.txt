CHAKMA HOME DELIVERY — PWA STARTER

Included files:
- index.html: menu, cart, checkout and WhatsApp ordering
- manifest.json: installable app metadata
- service-worker.js: basic offline shell caching
- icon.svg: app icon

WhatsApp:
The order recipient is configured as 918798567790 (India country code 91 + the number provided). This opens a prefilled WhatsApp message. The customer must review and tap Send; the seller must reply to confirm the order. No order is automatically accepted or saved in a private database.

Menu:
All prices start unset. Before launch, edit the products array in index.html and replace price:null with a numeric price. Example: price:60. Adjust item portion/weight descriptions to match the real item. Do not take live orders until prices and stock are correct.

Publish free (one possible route):
1. Keep all four files together.
2. Upload the files to a static HTTPS host that supports free publishing, such as a GitHub Pages repository or a free static hosting tier. Free-plan limits can change.
3. Make sure index.html is at the site root and manifest.json, service-worker.js and icon.svg are accessible at the same path.
4. Open the HTTPS URL on Android Chrome, test checkout, and use browser menu > Add to Home screen / Install app if offered.
5. Test an order on your own phone before sharing the link.

Privacy and safety:
- The checkout sends name, phone and address to the business WhatsApp account when the customer sends the message.
- Keep the WhatsApp account secured with two-step verification and never request customer OTPs, PINs or passwords.
- Do not publish the site URL as a claim of verified order processing until tested.
- This is a front-end prototype, not a secure backend. It does not store orders in an owner dashboard, calculate delivery fees or provide automated order tracking.
- Add a clear privacy notice and use an authenticated backend before scaling or storing customer data.
