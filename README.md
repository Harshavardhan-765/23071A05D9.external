# Student Management System React App

This is a React application for a Student Management System with the following pages:
- Registration
- Login
- Check Details
- Apply for Scholarship
- Payment
- CGP Calculator

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.  
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm run build`

Builds the app for production to the `build` folder.

## Deployment to GitHub Pages

1. Install the GitHub Pages package:

```bash
npm install gh-pages --save-dev
```

2. Add the following properties to your `package.json`:

```json
"homepage": "https://<your-github-username>.github.io/<repository-name>"
```

3. Add the following scripts to your `package.json`:

```json
"predeploy": "npm run build",
"deploy": "gh-pages -d build"
```

4. Deploy the app by running:

```bash
npm run deploy
```

Replace `<your-github-username>` and `<repository-name>` with your GitHub username and repository name respectively.

## Notes

- Make sure your repository is initialized and pushed to GitHub.
- The app uses React Router for navigation between pages.
