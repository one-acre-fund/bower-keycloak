Keycloak JavaScript Adapter
===========================

Resurrected from: [Wayback Machine](https://web.archive.org/web/20201014040640/https://codeload.github.com/keycloak/keycloak-js-bower/tar.gz/9.0.3)

JavaScript adapter for [Keycloak](http://www.keycloak.org/). For documentation see our [Securing Clients and Applications Guide](http://www.keycloak.org/docs/latest/securing_apps/index.html#_javascript_adapter).

## Issues

For general questions not covered by the documentation please send a mail to our [user mailing list](https://lists.jboss.org/mailman/listinfo/keycloak-user).

To report and bugs or request new features please create an issue in [JIRA](https://issues.jboss.org/browse/KEYCLOAK).

## Reporting security vulnerabilities

If you've found a security vulnerability, please look at the [instructions on how to properly report it](http://www.keycloak.org/security.html)

## Contributions

To provide a contribution send a PR to:	https://github.com/keycloak/keycloak/blob/master/adapters/oidc/js/src/main/resources/keycloak.js.

## UGLIFY

```
uglifyjs keycloak.js -cmo keycloak.min.js --source-map url=keycloak.min.js.map
```