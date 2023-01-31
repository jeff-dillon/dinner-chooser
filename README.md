# virtual-env-demo

Demonstration of virtual environments for Code Louisville Data Analysis 1.

## Instructions

**Use the notebook functionality**

1. Clone the repository and `cd` into it
1. Create a virtual environment, activate it, and install the libraries in requirements.txt
1. Type `jupyter notebook` in a shell to start the jupyter notebook server
1. Open the dinner.ipynb file to run the restaurant chooser script



**Add a wikipedia lookup script**

1. Use pip to install the `wikipedia` library
1. Update the `requirements.txt` file
1. Create a new file called `wiki.py` and add the following code:

```
import wikipedia

result = wikipedia.page("Louisville Kentucky")
print(result.summary)
```
