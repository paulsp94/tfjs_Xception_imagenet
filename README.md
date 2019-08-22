# Xception TFJS

The Xception model pretrained on imagenet for TensorFlow.js as a layers model.

This model has been converted, using the tfjs-converter.
The base model and weights were taken from keras.

To try the model you can just load it using:

XceptionURL = 'https://github.com/paulsp94/tfjs_Xception_imagenet/blob/master/model/model.json';
const Xception = await tf.loadLayersModel(XceptionURL);

[1]: https://www.npmjs.com/package/@tensorflow/tfjs-converter
[2]: https://keras.io/applications/#xception
