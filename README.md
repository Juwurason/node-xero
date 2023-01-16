### Configure with your credentials
Create Xero to get a *CLIENT_ID* and *CLIENT_SECRET*.

* Enter your app details (your redirect URI: `http://localhost:${PORT}`)
* Create a `.env` file in the root of your project & replace the 3 variables
> `touch .env`
```
CLIENT_ID=...
CLIENT_SECRET=...
REDIRECT_URI=...
```

### run

```sh
npm install
npm run dev
```