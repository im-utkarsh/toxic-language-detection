# toxic-language-detection

predicts toxicity present in a sentence using tensorflow.js  
  
  
Bundle model can be used via script tag in hedder:
```html
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@latest"></script>
<script src="https://cdn.jsdelivr.net/npm/@tensorflow-models/toxicity"></script>
```
Model can be loaded in javascript like this: 
```javascript
toxicity.load(/*variables*/)
  .then(model=>{
    //do predictions with model
  })
```

Some pretrained tfjs models can be found [here](https://github.com/tensorflow/tfjs-models)  
Most  of the code is taken from [here](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20Deployment/Course%201%20-%20TensorFlow-JS/Week%203/Examples/toxicity.html)  


