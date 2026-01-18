# //Wordly Dictionary SPA

This is a Single Page Application built using HTML, CSS and JavaScript, an online learning platform simulating an interactive dictionary feature.
It allows users to search ,save and preview words without page reloads as a result of its data driven web applications that fetches information from external APIs
## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Technologies used
HTML: For structuring the web page.

CSS: For styling the interface.

JavaScript: For making the page interactive and fetching data from the API.

Public Dictionary API: To retrieve word definitions and details.
## Features
Search for Words: Users can type a word into a search form to fetch definitions from a public dictionary API.

Display Definitions: Shows the word’s definition, part of speech, example usage, synonyms, and source details dynamically on the same page.

Save Favorite Words: Users can mark words as favorites for easy access later.

Dynamic Styling: JavaScript is used to update the CSS dynamically, making the page visually interactive.

Error Handling: Displays messages when a word is not found or if the API request fails.
## Tutorial
Users type a word into the search input.

JavaScript captures the input and makes a request to the dictionary API.

The API returns information about the word, including definitions, examples, and synonyms.

The application dynamically updates the page to display the word’s information without refreshing the page.

Users can save favorite words, which are highlighted on the page for easy reference.
## License

## Author
Fatuma Asman