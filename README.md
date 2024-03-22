# Datadog
At first login or create an account in [DataDog](https://www.datadoghq.com/)

You need to provide an api_key provided to you by datadog upon registration and the app_key you will create in UI.

When agent was created its connection will take 3-4 minutes.

For terraform execute the command :
```
terraform init
terraform plan
terraform apply -var="datadog_api_key=<YOUR_API_KEY>" -var="datadog_app_key=<YOUR_APP_KEY>"
```
