# fastai-v2-exercises

## Get Started

```bash
git clone https://github.com/sravanrekandar/fastai-v2-exercises.git && cd fastai-v2-exercises
```

Give permissions to execute shell script

```bash
chmod 777 setup_dev.sh
```

Run this to create a virtual environment and install dependencies

```bash
./setup_dev.sh
```

From here, you can start ```jupyter notebook``` or open the apps using ```voila```

**Example**

```bash
voila apps/dog_types/dog_types_app.ipynb
```

This should open a webpage

### 1. Dog Breed Detection App

Following [Lesson 02 in FastAIBook](https://github.com/fastai/fastbook/blob/master/02_production.ipynb), where bears data set is downloaded and trained, I have created an exercise to download dog images and train a model to predict a given dog(image) breed.

- **To run the app**

    ```bash
    voila apps/dog_types/dog_types_app.ipynb
    ```

- [View the app here](apps/dog_types/dog_types_app.ipynb)
