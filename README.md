# Xception TFJS

The Xception model pretrained on imagenet for TensorFlow.js as a layers model.

This model has been converted, using the [tfjs-converter][1].  
The base model and weights were taken from [keras][2].

To try the model you can just load it using:    
```javascript
XceptionURL = 'https://github.com/paulsp94/tfjs_Xception_imagenet/blob/master/model/model.json';
const Xception = await tf.loadLayersModel(XceptionURL);
```

[1]: https://www.npmjs.com/package/@tensorflow/tfjs-converter
[2]: https://keras.io/applications/#xception


# VGG19 TFJS

The VGG19 model pretrained on imagenet for TensorFlow.js as a layers model.

This model has been converted, using the [tfjs-converter][1].  
The base model and weights were taken from [keras][2].

To try the model you can just load it using:   
```javascript
vgg19URL = 'https://github.com/paulsp94/tfjs_vgg19_imagenet/blob/master/model/model.json';
const vgg19 = await tf.loadLayersModel(vgg19URL);
```

[1]: https://www.npmjs.com/package/@tensorflow/tfjs-converter
[2]: https://keras.io/applications/#vgg19
