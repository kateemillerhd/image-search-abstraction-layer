# image-search-abstraction-layer

A full-stack JavaScript app that allows users to search for images using a search string, paginate through results, and view recent searches. Built to fulfill the freeCodeCamp Image Search Abstraction Layer project requirements.

## Features
- Search for images by query string
- Paginate through image results with `?page=2`
- View the most recent search queries submitted

## User Stories
- I can get the image URLs, description, and page URLs for a set of images relating to a given search string.
- I can paginate through the responses by adding a `?page=2` parameter to the URL.
- I can get a list of the most recently submitted search strings.

## Technologies
- Node.js
- Express
- MongoDB & Mongoose
- External Image API (e.g. Unsplash or Bing Image Search)
- dotenv

## Project Structure

image-search abstraction layer/
--controllers/
  --searchController.js
--models/
  ---Search.js
--routes/
  --api.js
--.env
--server.js
--README.md

1. Clone the repository:
   ```bash
   git clone https://github.com/kateemillerhd/image-search-abstraction-layer.git
   cd image-search-abstraction-layer
  ```
2. Install dependencies:
  ```bash
  npm install
  ```
3. Create a .env file in the root directory and add your environment variables:
   ```bash
   PORT=3000
   MONGO_URI=your_mongo_connection_string
   IMAGE_API_KEY=your_image_api_key_here
   ```
4. Start the development server:
   ```bash
   npm start
   ```

