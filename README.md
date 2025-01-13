This is a website for FRAM, a webshop for food service. I made this project and aim to create a responsive website using HTML, CSS and JavaScript. 

Overview: 

- Visualises a landing page that shows the logo, information on how it works and images of some products. 
- Shows a clean layout that applies to big and smaller screens. 
- Buttons are interactive. 
- Fonts as follows are Arimo and Frank Ruhl and used accordingly.
- Renamed Files for easy checking
- Created a separate HTML file for the Product Page 

Features
Landing Page
- Displays a hero section with the FRAM logo and a tagline.
- Sections for seasonal selections and a step-by-step guide on how FRAM works.
- Includes a carousel for showcasing popular produce.
- A sign-up form to keep users updated.

Product Page
- Lists seasonal products with prices and weights.
- Includes an "Add to Basket" button within the product images.
- Features a "See Our Partnering Farms" section, with a map integration.

Responsiveness
- Uses Flexbox and media queries for a layout that adapts to both big and small screens.
- Elements such as the logo, icons, and buttons are aligned and sized appropriately across devices.

Interactivity
- Pop-up menu and chatbot feature for user convenience.
- Buttons for browsing products and chatting.
- "Add to Basket" buttons within product images.
- A carousel with smooth scrolling for mouse and touch interactions.
- JavaScript-driven chatbot for basic conversations, connected to OpenAI's API.


**Challenges and Fixes**

Challenges: 

- Keeping the logo centered and icons at the right places 
- Making it look visually appealing on both big and small screens. 
- Stock link aligned under the step description.
- Add to basket button inside the Product image.
- Creating a smooth, interactive carousel for mouse and touch interactions.
- Managing error handling for APIs and fallback designs.
  

Fixes:

- Used flexbox to align things better.
- Added media queries to stack things properly on smaller screens. 
- Moved the html for stock link inside the class step-description-container.
- Used JavaScript event listeners for interactivity while keeping the code organized.
- Added a placeholder for the map to maintain design context without an API key.
- Implemented fallback behavior for map and chatbot functionality in case of errors.


**Instructions on How to Use**

API for the Map
1. Go to the Google Cloud Console, create a project, and enable Maps JavaScript API.
2. Copy your API key (e.g., `AIzaSyA-xxxxx...`).
3. Replace `YOUR_API_KEY` in the HTML file:
   ```html
   <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY"></script>
   ```
4. Open the project in a browser. If the map doesn’t load, check the console for errors or verify your API key.

API for the Chatbot
1. Log in to OpenAI and copy your API key (e.g., `sk-xxxxx...`).
2. Replace this line in the JavaScript file:
   ```javascript
   const API_KEY = 'YOUR_API_KEY_HERE';
   ```
3. Open the project in a browser, test the chatbot by typing a message, and click "Send." If it doesn’t work, check the console for errors or API key issues.

Tips 
- Keep your API keys private and secure.
- Double-check your API key if any feature isn’t working.


Actions | Next actions:

- Continue enhancing the Product Page with additional CSS properties.
- Test and optimize other interactive elements.
- Explore more features to improve user experience.



Thank you for your time and for checking out my project!
