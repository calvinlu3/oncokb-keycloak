# OncoKB Keycloak
#### Keycloak service
- Use helm to install codecentric helm charts 
 `helm repo add codecentric https://codecentric.github.io/helm-charts`
- Create a keycloak service with `keycloak-config.yaml` configuration file.
  `helm install keycloak -f ./keycloak-config.yaml codecentric/keycloak`

#### Custom themes
Keycloak allows you to add your own themes. [[Documentation]](https://www.keycloak.org/docs/latest/server_development/#_themes)
- [Tutorial](https://www.baeldung.com/spring-keycloak-custom-themes) for creating custom theme.
- Follow the steps from codecentric's [README](https://github.com/codecentric/helm-charts/tree/master/charts/keycloak#providing-a-custom-theme) for adding a theme to keycloak service
