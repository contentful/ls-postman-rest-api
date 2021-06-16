# Contentful REST API Postman Tutorial
This repo contains two Postman export files. Import both the API collection as well as the environment settings into Postman, choose the environment you just uploaded, and start making Contentful REST API calls!

## API Access token 
You need to have the API access token to test API calls. If you don't have the API access token, see [how to get a personal access token](https://www.contentful.com/help/personal-access-tokens/#how-to-get-a-personal-access-token-the-web-app).
Update `cdaToken` value with **Content Delivery API - access token** and `cpaToken` value with **Content Preview API - access token** in Contentful REST API calls environment variables on Postman. 

We have example API calls for the Content Delivery API, Preview API and Images API. Since the Content Management API writes data we will provide a set of tutorial API calls in a future release that will reference content in a space that you own.

You can watch this [video](https://contentful.wistia.com/medias/lvmofw41fi) to see a quick demo of the API calls.

![Postman screenshot](./postman.png)
