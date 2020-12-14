Before setting up check whether you have Node.js Version 10.0 (or higher) set up on your machine as it's a requirement for running latest versions of Cypress.io

# Setting up the Project locally:

1. Clone the repository
2. Open your terminal and position yourself in the cloned repository
3. Run "npm install" (might take a while to set up the necessary packages)
4. Run "npm run cypress:open"
5. Select NopCommerce from the Integration Tests selection on Dashboard
6. The selected scrypt will start the automated test (initial run takes longer due to page load and setting cookies, needs some more workaround, every following run in the same session will take around 12 seconds)
