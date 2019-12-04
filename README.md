# Lung-Segmenter
Ai powered web app to demonstrate in browser lung segmentation.


Live Web App: http://lung.test.woza.work/

<i>For best results please use the Chrome browser to access the app.<br>
In other browsers the app may freeze.</i>



<br>

<img src="http://lung.test.woza.work/assets/webpage.png" width="500"></img>

<br>

My goal for this exercise was to develop the Python, HTML, CSS and Javascript workflow that would make it possible for a Tensorflow.js web app to display a segmented image inside a web browser. For visual context, the segmented image is overlayed on the original image. An example output is shown in the picture above.

This same code structure can be used to build web apps for other problems that combine prediction and segmentation. One drawback I found was that inference takes about 30 seconds when large images are submitted to the app. That's a long time in the web world - online users don't like waiting. This aspect of the user experience needs to be optimized.

The process used to build and train the model is described in this Kaggle kernel:<br>
https://www.kaggle.com/vbookshelf/lung-segmenter-tensorflow-js-web-app

The two datasets used to train the model can be found on Kaggle:<br>

https://www.kaggle.com/kmader/pulmonary-chest-xray-abnormalities

https://www.kaggle.com/yoctoman/shcxr-lung-mask


All javascript, html and css files used to create the web app are available in this repo.
