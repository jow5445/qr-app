# QR Code Generator

A simple and lightweight QR Code Generator built with HTML, CSS, and JavaScript.

I built this project as part of the Hack Club 5 KB Challenge. The idea of the challenge is to build a useful website or app while keeping the project as small as possible.

## Features

* Generate a QR code from text or a URL
* Download the generated QR code
* Clear the input
* Press Enter to generate a QR code
* Basic input validation
* Error messages
* Loading state while generating the QR code

## How it works

The user enters a URL or any text and clicks the "Generate QR Code" button.

The application sends the entered value to the QR Server API and uses the returned image as the generated QR code.

The generated QR code can then be downloaded from the page.

## Technologies

This project uses:

* HTML
* CSS
* JavaScript
* QR Server API

There are no frameworks or build tools.

## Project Structure

The project is intentionally kept in one file.

```text
QR-APP-Lightweight/
└── index.html
```

The HTML, CSS, and JavaScript are all inside `index.html`.

## Running the Project

There is nothing to install.

Just clone the repository:

```bash
git clone git@github.com:jow5445/qr-app.git
```

Then open `index.html` in your browser.

You can also run it using a local development server if you prefer.

## Project Size

This project is part of the Hack Club 5 KB Challenge, so keeping the file small is one of the main goals.

The final size of the project is:

```text
[Add the final size here]
```

To check the size on Linux:

```bash
wc -c index.html
```

On Windows PowerShell:

```powershell
(Get-Item index.html).Length
```

The size above is the uncompressed size of the HTML file.

## Keeping It Small

I kept the project lightweight by:

* Using a single HTML file
* Not using React or other frameworks
* Not using CSS frameworks
* Not adding image assets
* Keeping the DOM structure simple
* Keeping the JavaScript and CSS inside the same file
* Avoiding unnecessary dependencies

## API

The project uses the QR Server API to generate the QR codes.

The request looks like this:

```text
https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=YOUR_DATA
```

The text entered by the user is encoded and sent to the API.

## Screenshots

Add screenshots of the project here.

## Hack Club 5 KB Challenge

This project was made for the Hack Club 5 KB Challenge.

The challenge is about seeing how much you can build while keeping the project extremely small. It also encourages experimenting with plain HTML, CSS, and JavaScript instead of relying on large frameworks and dependencies.

## License

This project is open source and available under the MIT License.
