# **Project**: **Apple Fruit Disease Detection**: Detecting type of disease for apple leaves

**Problem**: Each year, diseases like 'apple scab', 'apple rot', and 'cedar apple rust' etc. damage apple trees, reduce fruit yields, compromise fruit quality, and threaten the economic viability of apple orchards.
            Additionally, they can lead to increased reliance on pesticides, environmental degradation, and challenges in maintaining sustainable agricultural practices.

**Purpose**: To reduce the economic loss economic loss beared by farmers due to apple plant diseases.

**Approch**:Periodic images of the leaves can be taken, can be processed using a **CNN Model** which can classify if the leaves of the tree are healthy or which type of disease they are have. 

- Apple leaf images form the **PlantVillage Dataset** dataset was used. Dataset link - https://www.kaggle.com/datasets/tushar5harma/plant-village-dataset-updated/data
- A **sequential CNN model** was build.
- Model had  **Total parameters**: 3,831,556 (14.62 MB)
             **Trainable parameters**: 3,830,468 (14.61 MB)
             **Non-trainable parameters**: 1,088 (4.25 KB)
- Model was trained over **7.7K images** of **PlantVillage Dataset**, and validation was done over **1.7K images**. Further testing on unseen **196 images** was done by the model.
- Best weights for the model was selected using the keras callback **model checkpoint**.
- Model showed **99.6%** accuarcy for the **training data**, **99%** accuracy for the **validation data** and **98%** accuarcuy for the **testing data**.

**Project Document** - Jupyter Notebook

**Libraries Used** - Tensorflow, Keras, Pandas, Numpy, matplotlib and pandas
