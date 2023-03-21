# Software engineering best practices for Databricks notebooks

This repository is a companion for the example article "Software engineering best practices for Databricks notebooks" ([AWS](https://docs.databricks.com/notebooks/best-practices.html) | [Azure](https://docs.microsoft.com/azure/databricks/notebooks/best-practices) | [GCP](https://docs.gcp.databricks.com/notebooks/best-practices.html)).

Going through the example, you will:

* Add notebooks to Databricks Repos for version control.
* Extracts portions of code from one of the notebooks into a shareable component.
* Test the shared code.
* Automatically run notebooks in git on a schedule using a Databricks job.
* Optionally, apply CI/CD to the notebooks and the shared code.

The example is hands-on. We recommend working it step-by-step to learn how to apply these techniques to your own Databricks notebooks.


## Notes on setting up project in VSCode

* Create `settings.json` to eanable pytest in the VSCode folder
* Running Databricks Notebooks on Databricks (Notebooks have a header) - Use "Run File as Workflow on Databricks"
* Running Python files on Databricks - Use "Run File as Databricks"