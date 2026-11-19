# Closer: an app for long-distance couples

An app that helps long-distance couples reconnect after an argument. If both partners opt in, the app can use audio from an in-app call to suggest a moment to pause and revisit a shared memory. It finds photos of the couple in albums they've approved and automatically creates a collage or a short video set to one of their favorite songs.

## The prototype

`index.html` is a single-file demo (no build step) in light purple, with lilies and a rose:

- **Both partners opt in:** nothing runs until both switches are on, and either partner can turn it off.
- **Call room:** a practice call, or your microphone's volume (processed on the device; no audio is recorded or uploaded), drives a "conversation temperature" meter. When it stays heated, Closer suggests a pause and shows a shared memory.
- **Shared album:** add photos and approve them; only approved photos are used.
- **Make a memory:** a downloadable collage and a slideshow "memory video", with your song's name and, optionally, the song file.

Run it by opening `index.html` in a browser. Everything stays in your browser.
