# News portal

Important notes:

- Use context or any other state manager

- Use react-router or any other router library

- UI needs to be fully responsive

- The news posts on the landing page should be displayed in cards

- You are allowed to use a UI library of your own choosing.

API: https://newsapi.org/

You will need to create a free api key at https://newsapi.org/account for developers

## Landing page with search

Landing page should initially display news from the top headlines end-point.

Display 20 of those results in 'top-headlines cards' and the rest (if there are more) after 'load more' button click at the bottom.

Each 'top headline card' should display title and description with an image if there is a url to the image in the response. User can then click on a 'READ FULL ARTICLE' button to read the article on a new page, 'Article'.

## Article page

Article page should display:

Source, author, title, description, image, published at date and the content (if all of these have been provided by the endpoint).

## Search and sorting

User should be able to search for a term (everything endpoint).

Search results should be displayed in the same way as the top headlines - in cards and user should also be able to read full article in articles page.

Once the user searches for the first term there should appear a 'sort by section' offering options to sort results by popularity or relevance or published date (Top headlines should not have sorting option).

The user should be able to click button load more to 'load more' articles for specific search.

User should be able to go back to home page displaying top headlines.

## BONUS:

Do it with Typescript!
