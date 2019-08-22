# Xception TFJS

The Xception model pretrained on imagenet for TensorFlow.js as a layers model.   
On ImageNet, this model gets to a top-1 validation accuracy of 0.790 and a top-5 validation accuracy of 0.945.   
The default input size for this model is 299x299.   

This model has been converted, using the [tfjs-converter][1].  
The base model and weights were taken from [keras][2].

To try the model you can just load it using:    
```javascript
XceptionURL = 'https://github.com/paulsp94/tfjs_Xception_imagenet/blob/master/model/model.json';
const Xception = await tf.loadLayersModel(XceptionURL);
```

[1]: https://www.npmjs.com/package/@tensorflow/tfjs-converter
[2]: https://keras.io/applications/#xception
