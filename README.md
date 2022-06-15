# Crime-Deprivation-Index-Prediction
Deep learning model for the prediction of the deprivation index linked to crime using the LIDAR images of the city of London.  GradCAM is used to visualize the model insights.

![alt text](https://github.com/unnikrishnansivakumar/Crime-Deprivation-Index-Prediction/blob/main/images/gradcamlidar.JPG)

* Gradient-weighted Class Activation Mapping (Grad-CAM), uses the gradients flowing into the final convolutional layer to highlight important regions in the image[8] .
* We use the Grad-CAM technique to check the regions of the LIDAR image that the model considered for prediction.
* This technique improves explainability and can act as signal for further training, network redesign or hyperparameter tuning if the model is not learning the right insights.


![alt text](https://github.com/unnikrishnansivakumar/Crime-Deprivation-Index-Prediction/blob/main/images/gradcamactivations.JPG)
