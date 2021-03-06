

## Kaggle instructions

Kaggle provides data from intensive care patients, you need to predict how long will they live.

* Register on Kaggle  and `Join Competition` for the [WiDS Datathon 2020](https://www.kaggle.com/c/widsdatathon2020).

* You can see public notebooks related to this competition and create a new notebook at https://www.kaggle.com/c/widsdatathon2020/notebooks

## Develop in a notebook

### Use Kaggle Jupyter notebooks

You can [create a notebook hosted on Kaggle](https://www.kaggle.com/c/widsdatathon2020/notebooks) to run your algorithms. This is the recommended way if you are not used to deploy Jupyter notebooks on your machine.

The [official WiDS datathon notebook](https://www.kaggle.com/danofer/wids-2020-starter-catboost-0-902-lb ) template can be used to start quickly

> [Copy this notebook](https://www.kaggle.com/kernels/fork/7523665) in a new Kaggle Pod.

* When creating a Kaggle Pod you can access the input data of the competition directly in `/kaggle/input/widsdatathon2020` (read-only files)
* The output files generated by the notebook goes to `/kaggle/working`

### Submit your predictions

* Download your predictions from the output folder (e.g. `submission.csv`). This file should contain 2 columns:
  * `encounter_id`: the patients ID
  * `hospital_death`: probability of death between 0 and 1 (your prediction)
* Submit your predictions file on the [Kaggle website](https://www.kaggle.com/c/widsdatathon2020/submit).
* You can commit 10 predictions per day.

### Use Jupyter notebook in local

We recommend to use Kaggle Jupyter notebooks as they come with everything you need pre-installed.

But you can use Jupyter notebook in local if you prefer.

> Download the data at https://www.kaggle.com/c/widsdatathon2020/data

## Additional documentation

### IDS repositories with data science materials

* [MaastrichtU-IDS/jupyter-workshop](https://nbviewer.jupyter.org/github/MaastrichtU-IDS/jupyter-workshop/tree/master/)
* [MaastrichtU-IDS/advanced-business-analytics](https://nbviewer.jupyter.org/github/MaastrichtU-IDS/advanced-business-analytics/tree/master/)
* [MaastrichtU-IDS/data-science-bootcamp](https://nbviewer.jupyter.org/github/MaastrichtU-IDS/data-science-bootcamp-pggm/tree/master/)
* [MaastrichtU-IDS/machine-learning-workshop](https://nbviewer.jupyter.org/github/MaastrichtU-IDS/machine-learning-workshop/tree/master/)

### General repositories with data science materials

* https://github.com/firmai/industry-machine-learning
* https://github.com/TarrySingh/Artificial-Intelligence-Deep-Learning-Machine-Learning-Tutorials
* https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects
* https://github.com/drivendata/data-science-is-software
* https://ebookfoundation.github.io/free-programming-books/
* https://github.com/awesomedata/awesome-public-datasets

### Cheatsheets

[MaastrichtU-IDS/cheatsheets](https://maastrichtuniversity-ids-open.s3.eu-central-1.amazonaws.com/data-science-cheatsheets.zip)
