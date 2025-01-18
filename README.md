# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# To make changes:
if you've made any changes to the code and want them to reflect on GitHub Pages, you need to run the build command again to generate the production-ready files.

Here's what you need to do:

Make Sure You're on the Correct Branch (gh-pages):
If you're on the gh-pages branch, that's great. If not, switch to the gh-pages branch by running:

**git checkout gh-pages**

Build the Project:
Run the build command to generate the files for production:
**npm run build**

Deploy the Files:
After the build is complete, use the gh-pages package to deploy the generated dist folder to the gh-pages branch:
**npm run deploy**

Push to GitHub:
If necessary, push the changes to the remote repository:
**git push origin gh-pages**

Once you've completed these steps, your changes should be reflected on the live site. If the page is still showing as empty, try clearing the browser cache or opening the page in incognito mode.
