# Resources for Machine Learning Operations with R

This repository contains resources for the talk "Machine Learning Operations with R".

Azure Machine Learning service (Azure ML) is Microsoft’s cloud-based machine
learning platform that enables data scientists and their teams to carry out
end-to-end machine learning workflows at scale. With Azure ML's new open-source
R SDK and R capabilities, you can take advantage of the platform’s
enterprise-grade features to train, tune, manage and deploy R-based machine
learning models and applications. 

## Presentations

Jan 2020: RStudioConf, San Francisco.  
MLOPS for R with Azure Machine Learning: [slides (PPTx)](MLOPS%20and%20R%20-%20rstudioconf%20-%2020200130.pptx) | [slides (PDF)](MLOPS%20and%20R%20-%20rstudioconf%20-%2020200130.pdf) | [Video Recording](https://resources.rstudio.com/rstudio-conf-2020/mlops-for-r-with-azure-machine-learning-david-smith)  
  

## Resources

Azure Machine Learning service: [Documentation](https://docs.microsoft.com/azure/machine-learning/overview-what-is-azure-ml?WT.mc_id=mlopsr-github-davidsmi)

Azure DevOps: [Documentation](https://docs.microsoft.com/azure/devops/user-guide/what-is-azure-devops?view=azure-devops&WT.mc_id=mlopsr-github-davidsmi)

**azuremlsdk** R package: [CRAN](https://cran.r-project.org/package=azuremlsdk), [GitHub Repository](https://github.com/azure/azureml-sdk-for-r), [Documentation](https://azure.github.io/azureml-sdk-for-r/reference/index.html). New to the package? Start with these vignettes:

* [Tutorial: Create a logistic regression model in R with Azure Machine Learning](https://docs.microsoft.com/azure/machine-learning/tutorial-1st-r-experiment?WT.mc_id=mlopsr-github-davidsmi)

* [A Deeper Dive into Experiments with R](azuremlsdk-vignettes/experiments-with-R.pdf) (this is also provided as a vignette in the `azuremlsdk` package)

Free azure credits: [register here](http://azure.com/free?view=azure-devops&WT.mc_id=mlopsr-github-davidsmi). (Credit card required, but won't be charged until you remove limits to allow it.)

## Code from presentation

Accidents model, trained and deployed with Azure ML, and shiny app: [GitHub](https://github.com/Azure/azureml-sdk-for-r/blob/master/vignettes/experiments-deep-dive.Rmd)  
(included in vignettes of [azuremlsdk package](https://github.com/Azure/azureml-sdk-for-r)).

## Related Presentations

Machine learning operations: Applying DevOps to data science  
AIML50: [Slides, code and recording on GitHub](https://aka.ms/AIML50repo)

# Feedback

If you have comments, suggestions, or questions, feel free to leave an issue in this repository.

David Smith  
Cloud Advocate, Microsoft  
Twitter: [@revodavid](http://twitter.com/revodavid)