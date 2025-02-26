# Request Header Parser Microservice

This is the boilerplate for the Request Header Parser Microservice project, which is a solution for a freeCodeCamp project. This microservice parses the request headers and provides information about the client's IP address, language, and software.

## Usage

This microservice provides an API endpoint that returns the client's IP address, language, and software information. You can test the API by sending a GET request to `/api/whoami`.

Example response:
```json
{
  "ipaddress": "127.0.0.1",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.150 Safari/537.36"
}
```

## Dependencies

- dotenv
- express
- cors

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/KamogeloMahlake/headerparser.git
   ```

2. Navigate to the project directory:
   ```
   cd headerparser
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add the following line:
   ```
   PORT=3000
   ```

5. Start the application:
   ```
   npm run start
   ```

Your app should now be running on `http://localhost:3000`.

## Project Structure

- `index.js`: The main entry point of the application.
- `public/`: Directory for static files.
- `views/`: Directory for the HTML views.
