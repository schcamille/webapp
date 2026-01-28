# Next.js with Strict Content Security Policy (CSP)

This repository contains a Next.js application that demonstrates how to implement a strict Content Security Policy (CSP) with a nonce. This is a security feature that helps to prevent cross-site scripting (XSS) attacks by controlling which resources (scripts, styles, etc.) are allowed to be loaded by the browser.

## How it works

The implementation uses Next.js middleware to:

1.  **Generate a unique nonce** for each request using `crypto.randomUUID()`.
2.  **Construct a strict CSP header**. This header specifies the allowed sources for various types of content. The generated nonce is included in the `script-src` and `style-src` directives.
3.  **Apply the CSP header** to the response.
4.  **Pass the nonce** to the frontend via a custom `x-nonce` header.

The frontend code then retrieves the nonce from the headers and applies it to the `<Script>` and `<style>` tags. This ensures that only scripts and styles with the correct nonce are executed by the browser.

## Project Structure

The main logic for this implementation can be found in the following files:

-   `with-strict-csp-app/middleware.js`: This file contains the middleware that generates the nonce and sets the CSP header.
-   `with-strict-csp-app/app/page.js`: This file shows an example of how to retrieve the nonce and apply it to a `<Script>` tag.

## Getting Started

To run the application locally, you will need to have Node.js and npm (or yarn/pnpm) installed.

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2.  Navigate to the `with-strict-csp-app` directory:
    ```bash
    cd with-strict-csp-app
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```
4.  Run the development server:
    ```bash
    npm run dev
    ```

The application will be available at `http://localhost:3000`.