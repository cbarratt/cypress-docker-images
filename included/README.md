# cypress/included

Docker image with operating system and Cypress installed globally.

Name + Tag | OS image
--- | ---
[cypress/included:3.2.0](3.2.0) | `cypress/base:12.1.0`

This image should be enough to run Cypress tests headlessly or in the interactive mode with a single Docker command like this:

```shell
$ docker run -it -v $PWD:/e2e -w /e2e cypress/included:3.2.0
```

For more information, read [Run Cypress with a single Docker command](https://www.cypress.io/blog/2019/05/02/run-cypress-with-a-single-docker-command/) and [End-to-End Testing Web Apps: The Painless Way](https://mtlynch.io/painless-web-app-testing/)
