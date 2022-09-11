# SNGuess Notebooks

This folder contains [Jupyter](https://jupyter.org/) notebooks that display and save the plots and overall results of the SNGuess article.

After installing SNGuess, you can just run in this folder the conmmand:
```
jupyter notebook
```
and the Jupyter notebook web interface should automatically open in your browser.

## Training and testing

The notebooks for training and testing SNGuess should be executed in the following order:

1. ``snguess_training_data.ipynb``
2. ``snguess_training.ipynb``
3. ``bts_transient_query.ipynb``
4. ``logreg_results.ipynb``
5. ``snguess_results.ipynb``

## Running SNGuess over ZTF alerts

The notebook ``snguess_ztf_alert.ipynb`` shows an example of how to query the alerts of an arbitrary ZTF candidate from the DESY archives, and obtain an SNGuess score for them.

Access to the DESY archives is mediated via GitHub. If your GitHub user is not a member of the ZTF or AMPEL organizations, please send an e-mail to ampel-info@desy.de in order to request access.

Once your GitHub user is granted access, log in to your account and visit https://ampel.zeuthen.desy.de/live/dashboard/tokens , where you will be able to generate a token string that can you can add as a `token` variable in the notebook.

**Note**: please make sure that you generate a permanent **archive token** for accessing the DESY archives. You can do this by accessing the "Archive tokens" tab in the aforementioned url.

## Auxiliary notebook

Notebook ``roc_curve.ipynb`` generates an example of a ROC curve for didactic purposes.