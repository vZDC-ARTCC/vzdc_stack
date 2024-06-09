Make sure version numbers are the ones you want to use.

Docker build and push command for website:
`docker build -t vainnor/vzdc_website:<VERSION> .`
`docker push vainnor/vzdc_websit:<VERSION>`

Docker build and push command for updater:
`docker build -t vainnor/vzdc_website_updater:<VERSION> .`
`docker push vainnor/vzdc_website_updater:<VERSION>`

Environment variables are configures in `.env.example`
Create a `.env` file with all the configured variables to be used in the compose file.
