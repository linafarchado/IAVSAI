# IAVSAI

## To start the project

- First of all, you'll need Onyxia in order to create a new service and launch Vscode-python-gpu.
- Open the github project on it.
- Then, please add your Onyxia user's name in the variable below :

```user_name = "juliettejin"```

After that you have to follow theses instructions :

- Run the following commands to install the dependencies
- After that, restart the kernel
- Then you can comment theses commands to not run them again

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
