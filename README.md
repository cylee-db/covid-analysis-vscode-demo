# COVID analysis - Demo of the Databricks VSCode Extension

To use this demo:

- Clone this repository to your laptop's development environment
- Import the root folder into an empty VSCode workspace
- Install the Databricks VSCode Extension
- Configure the extension for use with your Databricks workspace
- Run notebooks in `notebooks` using "Run File as Workflow on Databricks"
- Run python files in `src` using "Run File on Databricks"
- Leverage the unit tests already created in the project
- Leverage the VSCode Launch Configurations already created for you in `.vscode/launch.json`



## Notes on setting up and running the project in VSCode

* Create `settings.json` to eanable pytest in the VSCode folder (This is already done for you)
* Running Databricks Notebooks on Databricks (Notebooks have a header) - Use "Run File as Workflow on Databricks"
* Running Python files on Databricks - Use "Run File as Databricks"


# Credits

This repository is a combination of the assets found in:
- https://github.com/databricks/notebook-best-practices
  - This is a companion for the example article "Software engineering best practices for Databricks notebooks" ([AWS](https://docs.databricks.com/notebooks/best-practices.html) | [Azure](https://docs.microsoft.com/azure/databricks/notebooks/best-practices) | [GCP](https://docs.gcp.databricks.com/notebooks/best-practices.html)).
- https://github.com/databricks/ide-best-practices