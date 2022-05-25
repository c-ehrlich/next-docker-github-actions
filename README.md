# Next-Docker-Github-Actions

## What is this?
This is a sample repo for desting continuous deployment of a Next.js app to a VPS (Hetzner in this case, but could be any) using GitHub Actions

It exists for two reasons:
1. Figuring out how this works
2. As a reference for me to work from in the future

## What did I learn from this?
- How to create a Dockerfile
  - Separate builder and runner
  - Use environment variables
- How to create GitHub Actions
  - Publish an image to the Github Packages Registry, and use that image in a separate step
  - SSH into a server, upload and run the image
- Linux Server Admin
  - Learned more about SSH keys
  - I am using a Ubuntu VM on a VPS from Hetzner - this is 1/4 the price of Vercel's cheapest plan!

## What's next
- Registering a domain for a project (I already have a domain for my Portfolio, but I registered it through Vercel where the portfolio is hosted, so there was no manual configuration necessary)
- Using NGINX to create a reverse proxy
- Using the things I learned here to deploy a real project (such as my Survey App 'Anket')
