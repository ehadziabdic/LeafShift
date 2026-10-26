# LeafShitf - Leaf Disease Detection

## Problem Statement
For small vegetable growers in Bosnia and Herzegovina and the advisers who support them, we will use photos of tomato and potato leaves taken in uncontrolled conditions to support early recognition of common leaf diseases by producing one of 10 disease classes with a confidence score and an "uncertain - consult an agronomist" fallback. We will compare the proposed AI approach, an ImageNet-pretrained CNN fine-tuned on lab images (PlantVillage), with a majority-class baseline and a HOG + colour histogram linear SVM, and evaluate it using macro-F1 on uncontrolled photos (PlantDoc) together with the lab-to-field gap, subject to the domain shift between lab and uncontrolled images, label noise in the test data, and the risk that a wrong prediction leads to a wrong treatment.

**Team Members:**
- Emin Hadziabdic - Data and Evaluation lead
- Armin Memisevic -  ML and prototyping lead
- Muhammed Pasic - Problem and Project Lead