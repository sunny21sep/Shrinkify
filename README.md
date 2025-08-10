# Shrinkify

Hey there! Welcome to Shrinkify, your friendly URL shortener. Imagine turning that long, messy link into something sleek and easy to share—just paste it in, hit a button, and voilà!

## Why Shrinkify?

* **Quick and Simple**: No fuss—just paste your link, and Shrinkify does the rest.
* **Instant Redirect**: Click the short link, and you’re whisked off to the original destination.

## See It in Action

Take it for a spin here: [Live Demo](https://shrinkify2026.onrender.com/)

## How to Set It Up Locally

1. Clone this repo:

   ```bash
   git clone https://github.com/sunny21sep/Shrinkify.git
   cd Shrinkify
   ```
2. Install the goodies:

   ```bash
   npm install
   ```
3. Create a `.env` file in the project root and add:

   ```env
   PORT=3000
   MONGODB_URI=your_mongo_string
   BASE_URL=http://localhost:3000
   ```
4. Fire up the server:

   ```bash
   npm run dev
   ```
5. Open your browser at `http://localhost:3000` and start shrinking links!

## How It Works

* **Homepage**: Enter your long URL and optional custom alias.
* **Shorten**: Click the button and get your tiny link.
* **Redirect**: Visit `BASE_URL/yourAlias` to go to the original URL.

## What’s Next

I’m planning to add click stats and link analytics soon—stay tuned!

## Want to Help?

Contributions are welcome: fix bugs, add features, or suggest improvements.

1. Fork the repo.
2. Create a branch for your feature: `git checkout -b feature-name`.
3. Commit your changes and push.
4. Open a pull request. Let’s build something awesome together!

---

Made with ❤️ by Sunny21Sep
