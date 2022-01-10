# Notebooks
Home to jupyter notebooks for Mindee OSS projects


## Using notebooks

This repository was made to store Jupyter notebooks, but users are expected to access them through the corresponding projects. For instance, in [docTR](https://github.com/mindee/doctr), you can find a reference to the dedicated notebooks [here](https://github.com/mindee/doctr/tree/main/notebooks), which is automatically deployed in the documentation over [there](https://mindee.github.io/doctr/latest/notebooks.html).

This will provide you with better options to interact with those, such as [Google Colab](https://research.google.com/colaboratory/).


## Adding/modifying notebooks

Should you wish to add a jupyter notebook here, please update the corresponding documentation references to those notebooks in each project.

For instance, if you modify a notebook in `doctr/`, you might consider editing its [README](https://github.com/mindee/doctr/blob/main/notebooks/README.md).



### Notebook guidelines

Here are a few things we try to keep uniform between all notebooks for a clearer understanding by viewers:

1. **Picking a good title**: it shouldn't be too long but remain explicit. The notebook will be referenced in the documentation "Notebook tutorials" section, so no need to include "tutorial" in it.
2. **Picking the file name**: as the number of notebooks grows, we need to keep a sane naming convention that should reflect the notebook title (`export_as_pdfa.ipynb` for instance).
3. **A description goes a long way**: while the title should be informative, please add a description right after it. Your description should explain the purpose of this notebook tutorial.
4. **Title/section hierarchy**: just like markdown, use `#` for the notebook title, `##` for section title, `###` for subsections and so on.
5. **Cell ordering**: please move all imports up into a single cell, and ensure that the notebook can be run successfully with the cell order arrangement.
6. **Asset accessibility**: if you use some assets (image, etc.) in your notebook, provide the code to download the corresponding asset. This means that all assets have to be publicly accessible, and that you have the right to use them.
7. **Use text cells**: your content will help other users who have different coding skills, so please don't refrain from adding explanations in text cells (hyperlinks if necessary, etc.).
8. **Dear grammar**: watch out for your grammar; for instance, sentences should begin with an uppercase letter & end with a dot, etc.
9. **Credits where it's due**: the golden rule in open source; remember to credit all external works that you've been using.



## License

Distributed under the Apache 2.0 License. See [`LICENSE`](LICENSE) for more information.
