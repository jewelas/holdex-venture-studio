# Welcome to Holdex

Learn more about our DNA [here](https://holdex.io/about).

## Developing

Once you've installed dependencies with `npm install` (or `npm install` or `yarn`), start a development server:

```bash
npm run dev
# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

## Environment Options

Our localhost runs the stage environment by default. You can switch it to run the production environment as you test things out and then switch back to staging. 

You can do this in the lib/config file by setting the value to true:

```bash
const previewMock = false; -> true;
```