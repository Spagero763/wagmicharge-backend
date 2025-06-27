# WagmiCharge Backend

WagmiCharge is the backend service for the WagmiCharge application, a Web3-powered utility platform that allows users to convert cryptocurrency into mobile airtime instantly.

## Features

- User authentication (signup and login)
- Payment processing for airtime purchases
- Integration with external telco APIs
- Middleware for request authentication

## Tech Stack

- **Node.js**: JavaScript runtime for building the backend
- **Express**: Web framework for building APIs
- **MongoDB**: NoSQL database for storing user data (or any other database of your choice)
- **JWT**: For secure user authentication
- **dotenv**: For managing environment variables

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/qasim-rokeeb/wagmicharge-backend.git
   cd wagmicharge-backend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file based on the `.env.example` template and fill in your environment variables.

4. Start the server:
   ```
   npm start
   ```

## Usage

- The server runs on `http://localhost:3000` by default.
- Use the `/auth` routes for user authentication.
- Use the `/payment` routes for processing payments.

## Contributing

PRs are welcome! If you’d like to contribute, feel free to fork this repo and submit a pull request.

## License

MIT © [Qasim Rokeeb](https://github.com/qasim-rokeeb)