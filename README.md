# GatsbyJSNetlify CMS Documentation Starter project

The goal of this project is to create a kickstarter for project documentation using GatsbyJS to generate the static site frontend while using Netlify CMS as the backend for content creation & editing.

## This is a work in progress

Status 2019-02-24: 

- I've configured a baseline GatsbyJS starter repo which works on running `yarn develop`
- I've integrated a basic Netlify CMS backend and configured the plugins in `gatsby-config.js`
- I've scaffolded out the project structure but it's not final
  - having trouble deciding on hoe to structure the docs folder contents to work with NetlifyCMS collection definition
  - Can't decide whether to create multiplecollections for separate subfolders of docs
  - Or to create one flat `docs` folder and add a categorization option in the page creation editor using a Select widget that would add a term to the filename. 