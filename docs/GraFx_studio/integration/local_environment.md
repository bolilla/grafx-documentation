# Set up your local environment

JavaScript could run in the browser, served from a file. 
Running it from a webserver, will have several advantages, e.g. access to objects in the code you are writing.

## Setting up a webserver

Set up a local webserver of your choice

- [Apache](https://httpd.apache.org/)
- [Nginx](https://www.nginx.com/)
- [IIS](https://www.iis.net/overview)

## Create a Folder for you application

![Properties](https://chilipublishdocs.imgix.net/GraFx_studio/integration/folder.png?w=400&q=80)

## DNS or not?

Up to you, to serve the files from localhost / 127.0.0.1 or from a local DNS.

My preference is to use the .hosts file to setup a local domain.

```
127.0.0.1       my.grafxapp.dev
```

!!! note

	Remember to setup a local SSL certificate, to be able to run secure

## Testing the setup

Add an index.html to the root of your folder, and insert "Hello world"

![Properties](https://chilipublishdocs.imgix.net/GraFx_studio/integration/index.png?w=400&q=80)

Browse to the webserver / folder to see

![Properties](https://chilipublishdocs.imgix.net/GraFx_studio/integration/indexpage.png?w=400&q=80)

You now have a working website on a local webserver!