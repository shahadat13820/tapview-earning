# TapView Earning

## GitHub
Upload `public/index.html` to a GitHub repository if you only want to host the frontend.

## Backend
The secure balance/limit logic is in `server.js`. Deploy it on a Node.js HTTPS host and replace `YOUR-BACKEND-URL` in `public/index.html`.

Set `BOT_TOKEN` as an environment variable. Never put the bot token in GitHub.

## Important
The ad completion endpoint is only a starter. Before real payouts, integrate your ad provider's official server-side callback/verification. Client-side 20-second timers cannot prove that an ad was actually viewed.
