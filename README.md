# piedpiper

Coding challenge

Your task is to set up the initial infastructure for a fictional company's website. The company is called Pied Piper and its main product is a compression algorithm.

Mockups for the components can be found at https://github.com/modipeluri/piedpiper


## 1. Get content for the website
  Content for the website already exists in Pied Pipers CMS - Contentful.
  - Log in to contentful at contentful.com with the username/password provided
  - Fetch content using the contentful javascript SDK
  - Documentation can be found in contentful "Space Home" under "Use the API"


## 2. Set up a new VueJS project
  - Create the 2 components in a modular fashion using BEM CSS methodology (html/css)
    - Testimonial block
    - Feature block
  - Make the components into Vue Single File Components (example here: https://vuejs.org/v2/guide/single-file-components.html)


## 3. Render pages
  - Create a testimonials.html -template that renders the testimonials

  - Render feature pages dynamically
    - Use Vue router to dynamically render the feature -pages
    - The URL should be the title of the feature
    - Add the feature's content to the page
    - If the feature's title changes in Contentful, the URL should also change.

## 4. Results
  Send results to Pekka in zip file by email.
