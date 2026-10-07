# Ad Director

An AI creative director for ads. Enter a product's details (or a product link) and get a creative brief, four different creative directions, a script, a shot-by-shot storyboard, a playable video-ad preview, a production workflow, and four ad variations.

The live version is linked in this repository's About section.

## Try it
1. Open the live page and choose **Run the Velocity X demo**, or enter your own product's name, price, features and selling points.
2. Pick a creative direction.
3. Edit any shot, preview the ad, and export the plan as JSON.

## How it works
Everything runs in the browser from a single `index.html`. Nothing is uploaded and no API keys are used. The script and storyboard are currently built from templates using the details you enter. Real page reading and AI-written scripts need a backend, which is planned.

## Run it locally
Open `index.html` in a browser. No build step.

## Mobile
The `mobile/` folder is a Capacitor project that wraps the same app for Android and iOS. See `mobile/README.md`.

## License
MIT. See `LICENSE`.
