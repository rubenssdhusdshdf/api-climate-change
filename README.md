# api-climate-change

# Climate Change News API

Welcome to the Climate Change News API! This Node.js application scrapes articles related to climate change from various news websites.

## Installation

Make sure you have Node.js and npm installed on your machine.

Then clone this repository:

   ```bash
git clone https://github.com/your-username/your-repository.git
   ```
   

Navigate to the project directory:

   ```bash
  cd your-repository
   ```

## Install dependencies:

```bash
npm install
```

## Usage

Running the Server

```bash
npm start
```

This will start the server on the default port (8000) or the one specified in the PORT environment variable.

Endpoints

1. Get all articles:

```bash
GET http://localhost:8000/news
```

Returns a JSON array of articles from various sources.

2. Get articles from a specific newspaper:
   
```bash
GET http://localhost:8000/news/:newspaperId
```

Replace :newspaperId with the name of the newspaper (e.g., thetimes, guardian, telegraph).

Example
To retrieve articles from The Times, make a GET request to:

```bash
GET http://localhost:8000/news/thetimes
```

## Dependencies

- Express: Fast, unopinionated, minimalist web framework for Node.js.
- Axios: Promise-based HTTP client for the browser and Node.js.
- Cheerio: Fast, flexible, and lean implementation of core jQuery for the server.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

License
This project is licensed under the MIT License - see the LICENSE file for details.

