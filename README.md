# docs.fabreeko.com

This repo contains the code that builds the docs site.  It is designed to be built by, and hosted at GitHub Pages.  

## **Do you belong here?** 

You would only view this repository if you plan on changing the overall setup and/or admin configurations.  

Otherwise, content creators should visit and log into the admin site instead at:

https://docs.fabreeko.com/admin

## Basic Overview

The docs website uses the following technologies:

- Material for MkDocs
- Decap CMS

The deployment pipeline uses GitHub Actions that is triggered upon every commit to `main`, and deployed to the common `gh-pages` branch.  Therefore, the repository is configured to serve files from that branch.



