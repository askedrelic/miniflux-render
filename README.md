# Miniflux on Render

This repository allows you to deploy the latest <a href="https://miniflux.app/" target="_blank">Miniflux</a> RSS feed reader web service on Render.

*Miniflux is a minimalist and opinionated feed reader.*

## Automatic Deploy
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/askedrelic/miniflux-render)

This will deploy a Blueprint, a Render template, that creates a 
- free web service, running Miniflux
- free Postgres DB, connected to the web service

Once the service is deployed, you login with user "admin" and an auto-generated password. You can find the auto-generated `ADMIN_PASSWORD` in the web service Environment Variables section:

<img width="1280" alt="Screen Shot 2023-03-27 at 12 02 55 PM" src="https://user-images.githubusercontent.com/130111/228041336-5266c6c7-9930-4d52-b35b-1627c53433a5.png">
