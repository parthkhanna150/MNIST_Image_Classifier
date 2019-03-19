# MNIST_Image_Classifier

To properly use the Google Colab Notebook (and it's tasty free Tesla GPU), the dataset has to be imported using the Kaggle API. The first few cells of the submitted notebook deal with this process, and need to be run.
The notebook should be opened through colab.research.google.com to take full advtange of these features.

When run, the first cell...

from google.colab import files
files.upload()

...will prompt you to choose a file.

This is a json file generated by your kaggle account. To obtain it:
1. Go to Kaggle and log in.
2. In the top right, go to "my account".
3. Scroll to the button that says "create new API token".
4. Click said button.

This downloads the json file that should be uploaded.

The rest of the cells download the API and the dataset direcly from Kaggle, and extract the zip files. From this point on, everything should work like a normal jupyter notebook.
