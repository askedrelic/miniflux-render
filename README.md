# Miniflux on Render

This repository allows you to deploy the latest <a href="https://miniflux.app/" target="_blank">Miniflux</a> RSS feed reader web service on Render.

*Miniflux is a minimalist and opinionated feed reader.*

## Automatic Deploy
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/askedrelic/miniflux-render)

This will deploy a Blueprint, a Render template, that creates a 
- free web service, running Miniflux
- free Postgres DB, connected to the web service

Once the service is deployed, you login with user "admin" and an auto-generated password. You can find the password in the web service Environment variables section: