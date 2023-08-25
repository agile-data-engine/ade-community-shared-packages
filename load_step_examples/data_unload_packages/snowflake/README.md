## Unloading data from Snowflake to cloud storage
In this example package, entity F_SALES is loaded and unloaded from Snowflake to cloud storage.

## Pre-requisites
Example package utilizes environment variables from CONFIG_ENVIRONMENT_VARIABLES -package (https://docs.agiledataengine.com/docs/config_environment_variables)

Variable in configuration package:
```
{
    "environmentName": "DEV",
    "variableName": "stage_name",
    "variableValue": "@[put-stage-schema-here].[put-stage-name-here]"
},
{
    "environmentName": "TEST",
    "variableName": "stage_name",
    "variableValue": "@[put-stage-schema-here].[put-stage-name-here]"
},
{
    "environmentName": "PROD",
    "variableName": "stage_name",
    "variableValue": "@[put-stage-schema-here].[put-stage-name-here]"
}
```