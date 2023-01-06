# Getting Started with Keycloak-15.0.2

## Keycloak Application Server

### Run the server.

- download git: https://github.com/chanabnus/keycloak-react-15.0.2
- navigate downloaded project folder and execute:
`$ ./bin/standalone.bat`
- run browser: https://localhost:8443/auth/
- select "Administration console"
- login: admin/admin
- select realm "Keycloak-auth"
- credentials: admin/adminaccess, user/useraccess

### Start the Keycloak application server

#### Powered by WildFly version: (i.e. 15.x.x)
- Linux/Unix
    - $ cd bin
    - $ ./standalone.sh

- Windows
    - ./bin/standalone.bat

#### Powered by Quarkus version: (i.e. latest 20.x.x)
- Linux/Unix
    - $ cd bin
    - $ ./kc.sh

- Windows Options
    - ./bin/kc.bat start-dev
    - ./bin/kc.bat start --hostname localhost
    - ./bin/kc.bat start --db postgres --db-username <username> --db-password <password> --db-url-host keycloak --hostname localhost

## ___________
## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
