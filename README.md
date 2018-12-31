Code from [this tutorial](https://docs.microsoft.com/en-gb/azure/azure-functions/functions-create-first-function-python)

Some notes:
* conda environment not supported, you need a venv. I managed to create one inside this conda environment.
* I tried to get CD to work from this Azure repo, but that didn't work. I could create the infra but not push the code there. See [this pipeline](https://jbuitelaar.visualstudio.com/Test/_release?definitionId=5&view=mine&_a=releases). Don't know why, maybe it's not fully supported yet (I also couldn't find the app in the dropdown when selecting the app to deploy to)

[Here](https://jb-funcapp-python.azurewebsites.net/api/jbhttpTrigger?name=jb)'s the location of the function app.