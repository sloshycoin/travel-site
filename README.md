# Travel Site

You are an expert JavaScript Developer. You have been instructed to create a travel site for your new customer. Your boss has given you a list of tasks to execute in order to satisfy the customer's requirements.

## Setting up the environment

1. Make a folder named `travelRecommendation`. This is the project folder.
2. In your project folder create `travel_recommendation.html`. This is the template.
3. In your project folder create `travel_recommendation.js`. This is the script.
4. In your project folder create `travel_recommendation_api.json`. We will use this as the source of data for our webpage.
5. In your project folder create `public` directory. We will store images here for use in our webpage.

## Tasks

1. Create a basic HTML template structure in the travel_recommendation.html file. It should include these tags:

   - `<html>`
   - `<head>`
   - `<body>`
   - Within the `<head>` tag include a `<title>` tag.

Write your website name in the `<title>` tag to set up the title of each web page.

2. For this task, you need to create a navigation bar. The navbar should contain the following:

   - Home page link using anchor tag <a> to navigate to home page
   - About us page link using anchor tag <a> to navigate to about us page
   - Contact Us page link using anchor tag <a> to navigate to contact us page
   - A search bar to allow users to enter keywords to search for recommendations
   - A Search button to execute the search after the user clicks on it
   - A Reset button to clear results.
   - You should also include your website name and logo.

3. In this task, you will design a Home page which must include:

   - A background image
   - An introduction to this website

4. In this task, you need to create an About Us page, which should include:

   - Information about the company
   - An introduction to the team members, displaying their names and their designated roles

5. In this task, you need to create a Contact Us page, which should contain the following:

   - A form for users in case they want to reach out
   - The form should contain:
     - `<input>` boxes for name and email
     - `<textarea>` for users to write their message
     - Submit button to submit the form

6. Now, you need to create logic in your JavaScript file to show results for your recommendations.

   - Fetch data from the travel_recommendation_api.json file using the fetch API method, from there you can fetch travel-related details, such as the name of the place. You need to have your own images for every imageUrl in the JSON file.
   - Fetch the data from the JSON using the fetch API() method. To check if you can access the data, you use console.log to see if the result is displayed.
   - It is good if the console.log logs the data. Otherwise, you need to look for a different API.

7. In this task, you will write JavaScript to accept these keywords and variations the user will enter in the search field in your navigation bar on the home page.

   - For example, if the user enters "beach," or "beaches," "Beach" or "BEACH," then you need to write JavaScript code so that it accepts all variations of this keyword.
   - For uppercase letters in the keyword, you can convert them to lowercase in your JavaScript using the string manipulation toLowerCase() method.
   - Similarly, you need to create logic to match keywords entered for temples and countries.
   - The website should display results only after the user clicks the Search button.

8. In this task, you need to fetch the details of the places you recommend based on which keyword the user enters: beach, temple, or country.

For each of these three keywords, your results should display at least two recommendations, an image, and a description. Example screenshot is shown below.

9. Create logic in your JavaScript file for a clear button to clear the results. To implement this feature, you can create a function that will be called after clicking on the clear button in the navbar.
