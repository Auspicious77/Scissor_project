
# Scissor URL Shortener

Scissor URL Shortener is a simple yet powerful tool built with Node.js and Express.js that allows users to shorten long URLs into shorter, more manageable links. With the increasing need for brevity in today's fast-paced digital world, Scissor aims to provide a seamless solution for sharing URLs efficiently across various platforms.

## Features

- **URL Shortening:** Convert long URLs into shorter, easy-to-share links.
- **Custom URLs:** Customize shortened URLs with your own custom alias.
- **QR Code Generation:** Generate QR codes for shortened URLs, making it convenient for offline sharing.
- **Basic Analytics:** Track the performance of shortened URLs, including the number of clicks and their sources.
- **Link History:** Easily access and manage the history of shortened links.

## Getting Started

To get started with using Scissor URL Shortener, follow these steps:

1. Clone the repository to your local machine.
2. Install dependencies using `npm install`.
3. Start the server using `npm start`.
4. Access the API endpoints to shorten URLs, customize links, generate QR codes, and more.

## API Endpoints

- **POST /shorten:** Shorten a long URL. Optionally provide a custom alias for the shortened URL.
  - Request Body:
    ```json
    {
      "longUrl": "https://example.com/very/long/url",
      "customAlias": "customalias"
    }
    ```
  - Response:
    ```json
    {
      "shortUrl": "https://scissor.com/customalias",
      "qrCodeUrl": "https://scissor.com/qr/customalias"
    }
    ```

## Usage

You can use the Scissor URL Shortener API to integrate URL shortening functionality into your applications or services. The API follows the OpenAPI specification, ensuring consistency and compatibility with various development environments.

## Contributing

Contributions to Scissor URL Shortener are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
