# Docusaurus project for building a documentation site

This repo shows you step by step process of building a documentation site using the open-source frame Docusaurus.

## Install Node.js

Simply use go to the Node.js official website to download the installer for your OS, and proceed with the installation. This process is very simple.

Although Docusaurus also recommends installing Yarn. If you are using Mac OS, you may encounter some assess permission issues. Therefore, we will skip this step.

Check if the Node.js is successfully installed. To do that, run the command:
```
[server]$ which node
```

## Install Docusaurus into your defined directory

The next step is to create a directory that you want to put your project folder in. Then run the following code:
```
[server]$ npx create-docusaurus@latest [name] [template]
```
Example:
```
[server]$ npx create-docusaurus@latest aropha-docs classic
```
In order to make the project folder `aropha-docs` generated in your target directory, you have to navigate to that folder before running above command.


## Running the development server

Once Docusaurus has been installed and your project folder created, **navigate into your project folder** and run the below command:
```
[server]$ npm run start
```
By default, a browser window will open at http://localhost:3000.

Then you can open the files in your favorite text editor to create your website. More guidelines can be found in Docusaurus's official documentation at https://docusaurus.io/docs.

## Build
Once you have finished editing the contents of your website, simply run below command to build the static files:

```
[server]$ npm run build
```
The contents will be generated within the /build directory, which can be copied to any static file hosting service like GitHub pages, Vercel or Netlify. 

## Reference
1. https://docusaurus.io/docs
