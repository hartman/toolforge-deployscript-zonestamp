zonestamp
======

A deployment of [Zonestamp](https://zonestamp.com) on the [Wikimedia Cloud Toolforge](https://tools.wmflabs.org/).

## Deploy
For now, this app requires local building before deploy.
Run: `npm install; npm run build`

Then to deploy: `ansible-playbook -i hosts main.yml`