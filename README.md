# Image-generator
generate more images from one image for training models.

Using **ImageDataGenerator**(https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator), a popular image generator package in TensorFlow. 

Example:

The following is the original image

<div align=center><img src="original-data\8.jpg" alt="8" width="25%" height="25%"/ /></div>

We can set the parameters in the ImageDataGenerator: rotation, displacement, zoom, etc, to randomly generate new images; if we put the generated number as 9, we can develop nine new images.

<div align=center><img src="original-data\image-20230422004025218.png" alt="image-20230422004025218" width="70%" height="70%" /></div>

```
About ImageDataGenerator
tf.keras.preprocessing.image.ImageDataGenerator(
    featurewise_center=False,
    samplewise_center=False,
    featurewise_std_normalization=False,
    samplewise_std_normalization=False,
    zca_whitening=False,
    zca_epsilon=1e-06,
    rotation_range=0,
    width_shift_range=0.0,
    height_shift_range=0.0,
    brightness_range=None,
    shear_range=0.0,
    zoom_range=0.0,
    channel_shift_range=0.0,
    fill_mode='nearest',
    cval=0.0,
    horizontal_flip=False,
    vertical_flip=False,
    rescale=None,
    preprocessing_function=None,
    data_format=None,
    validation_split=0.0,
    interpolation_order=1,
    dtype=None
)
```