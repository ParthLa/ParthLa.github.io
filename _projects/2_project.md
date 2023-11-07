---
layout: page
title: Semi Supervised Data Programming in Python
description: Aggregating various data programming approaches while incorporating user defined heuristics 
# img: assets/img/model.webp
importance: 2
category: Research
---

<p align="justify"> We present SPEAR, an open-source python library for data programming with semi supervision. The package implements several recent data programming approaches including facility to programmatically label and build training data. SPEAR facilitates weak supervision in the form of heuristics (or rules) and association of noisy labels to the training dataset. These noisy labels are aggregated to assign labels to the unlabeled data for downstream tasks. We have implemented several label aggregation approaches that aggregate the noisy labels and then train using the noisily labeled set in a cascaded manner. Our implementation also includes other approaches that jointly aggregate and train the model for text classification tasks. Thus, in our python package, we integrate several cascade and joint data-programming approaches while also providing the facility of data programming by letting the user define labeling functions or rules. We also present some real-world use cases of SPEAR. </p>

<p align="justify"> The project implementation can be found here <a href="https://github.com/ParthLa/Data_Pgm_Subset_Slc"> here </a>. Further, extensive documentation can be found <a href="https://spear-decile.readthedocs.io/"> here </a>. Video tutorials demonstrating the usage of our package are also <a href="https://youtube.com/playlist?list=PLW8agt_HvkVnOJoJAqBpaerFb-z-ZlqlP"> available </a>. </p>
