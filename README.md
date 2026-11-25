# Soundwave

A responsive React music-library demo built with Vite and Bootstrap. The interface is composed of reusable React components for navigation, account forms, the admin panel, track library, and audio player. Browse the sample tracks, create an in-session demo account, and use the audio player. The demo admin can add audio files for the current page session or remove tracks.

## Run locally

```sh
npm install
npm run dev
```

Create a regular account through **Sign up**. Demo admin access is `admin` / `soundwave123`.

Accounts, uploaded audio, and library changes exist only in the current page session. This frontend demo does not provide real authentication or persistent storage.

## Verify

```sh
npm run lint
npm run build
```
