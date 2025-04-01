Lichess OAuth API with a personal token
You can make OAuth requests without going through the authorization code flow.

Instead, generate a personal token that you can directly use in API requests.

Be careful, these tokens are like passwords so you should guard them carefully. The advantage to using a token over putting your password into a script is that a token can be revoked, and you can generate lots of them.

Run this example
Copy .env.default to .env
Create a personal token
Set the token in .env
Install dependencies with npm install
Run with node index.js
