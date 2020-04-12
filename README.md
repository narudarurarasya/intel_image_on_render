# Classify different landscapes 🏔🏙🛣

The [fast.ai](https://www.fast.ai) CNN model is trained on [Intel Image Classification data](https://www.kaggle.com/puneet6060/intel-image-classification) and deployed on [Render](https://render.com).

The code for training the model can be found on [kaggle](https://www.kaggle.com/kevvad/intel-image-classification-with-fastai-94-acc)

The sample app described here is up at https://landscape-classify.onrender.com. Test it out with your own images!

You can also test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```
