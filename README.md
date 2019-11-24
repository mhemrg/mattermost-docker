# Deploy Mattermost to Liara

Create a new project and make sure to set the following environment variable:

```
MM_SQLSETTINGS_DATASOURCE=postgres://mmuser:mmuser_password@db:5432/postgres?sslmode=disable&connect_timeout=10
```

Then, run the deploy command:
```
liara deploy
```
