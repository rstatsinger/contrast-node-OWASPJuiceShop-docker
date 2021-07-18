# Contrast Node.js agent deployment in Dockerized OWASP juice-shop

This is the Node.js OWASP juice-shop app, instrumented with Contrast Security, and running in a Docker container to isolate it from your environment.
## Prerequisites


git and docker

## Instructions

1. Clone this repo
2. Drop your contrast_security.yaml file into the project root directory
3. Run the **build** script
4. Run the **start** script
5. Interact with the application, which should be running on your desktop at http://localhost:3000
6. Observe the results of your interactions in the Contrast Security UI, where the **juiceshop-guide** app should be onboarded and online.
