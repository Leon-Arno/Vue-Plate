# A VueJS Boilerplate with BootstrapVue configured with Webpack

<p align="center"> 
<img src="./src/assets/logo.png">
</p>

This is a minimal VueJS boilerplate powered by [Webpack](https://webpack.js.org/) configured with:

- VueJS
- BootstrapVue
- SASS
- **Extra:** .gitignore file for all operating systems.

## Quick Start

1. Clone the repository into your project folder
   <br>

```bash
git clone git@github.com:Leon-Arno/Vue-Plate.git .
```

<br>
2. Remove the .git directory to add your own repository

```bash
rm -rf .git
```

<br>
3. Update the package.json file where necessary.
   e.g

```JSON
   {
     "name": "your-project-name",
     "description": "your project description",
     "author": "your name",
     "license": "MIT",
   }
```

<br>
<br>
4. Install the required dev-dependencies

```bash
npm install
```

**and**

```bash
npm update
```

to update the dev-dependencies from their initial versions.
<br>
<br>
<br>

5. To start, run the dev command

```bash
npm run serve
```

This runs the app in dev mode. A browser tab will be automatically opened.<br>
In case a tab isn't opened, simply go to this address [http://localhost:8080](http://localhost:8080) on your browser.<br>
**Note: to stop the dev-mode simply press `ctrl + c`**
<br>
<br>
<br>

6. To clean cache, run

```bash
npm run clean
```

This uses [rimraf](https://www.npmjs.com/package/rimraf) to clean the existing `dist folder`
<br>
<br>
<br>

7. To build, run the build command

```bash
npm run build
```

Builds the app for production to the `dist` folder.<br>
All static files to be deployed are generated in this folder

See the section about [deployment](https://cli.vuejs.org/guide/deployment.html#gitlab-pages) for more information.
<br>
<br>
<br>

## Learn More

To learn VueJS, check out the [VueJS documentation](https://vuejs.org/).
