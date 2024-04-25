# IAVSAI

## To start the project

The final version of our project resides within the Notebook named "IAVSAI_V2.ipynb," which has been thoroughly tested with the most recent database. 
Conversely, the initial version, "IAvsAI," serves as our initial code iteration tested with the older database, albeit less significant due to the simplified nature of the data.

Follow theses instructions below to have a better start of the project
- First of all, you'll need Onyxia in order to create a new service and launch Vscode-python-gpu.
- Open the github project on it.
- Then, please add your Onyxia user's name in the variable below :

```user_name = "juliettejin"```

> [!NOTE]
> If you want to run in your machine, you may need to adapt the code by adjusting certain file paths within the notebook.
> 

- Run the following commands to install the dependencies in the **Notebook**

```
! pip install nltk
! pip install datasets
! pip install spacy
! pip uninstall -y scipy
! pip install scipy==1.12
! pip install tensorflow

import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

- After that, restart the **KERNEL**
- Then you must comment theses commands to not run them again otherwise you may have a problem with the imports

> [!NOTE]
> There are commented-out code sections that are intentionally included to aid in the search for optimal model parameters.
>  
> You can disregard running these sections and instead refer to the accompanying report to adjust parameters and achieve the best score.

## Authors

Lina FARCHADO - Noam EL IDRISSI - Juliette JIN - Paul GUAN
