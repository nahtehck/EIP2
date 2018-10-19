# Session -1 assignment 

**Name:** *Chethan k* 

**Batch:** *Batch - 2* 



**Assignment topics  and their articles:**

---



* **Convolution**

  ---

  *Convolution* is an important operation that is used in image processing(2-dimensional) and and also in other aspects such as voice or video processing. In order to perform convolution kernel(weight matrix of the above layer) is slided over the entire image(image matrix) from top left corner and obtain output pixels with the size of kernel matrix for each of the operation performed(corresponding elements of each matrix are multiplied and added).

* **Filters/kernels**

  ---

  A *Kernel* (with respect to 2D image processing) is a part of the architecture of the layered image. In general it can be viewed as an operator applied on to the pixel information of the image so as to transform them into the information needed by the machine to process the image. The kernels are convolved with the pixel information to transform them into activation maps which defines the feature of a specific part of the image.

* **Epochs**

  ---

  An *Epoch* defines the number of times the training data is input so as to adjust the weights for which the machine is more efficient and less prone to errors. Basically an epoch represents the number of iterations performed using the training data in order to train the machine to perform the required task.

* **3x3 convolution**

  ---

  ![alt](https://www.jeremyjordan.me/content/images/2018/04/Screen-Shot-2018-04-17-at-5.32.45-PM.png)

  *3x3 convolution* (kernel matrix) is applied for feature extraction in case of image processing where it is applied on two dimensional layer of the image. This convolution is applied in order to apply filtering on the image or by performing operations using this 3x3 matrix as the operator on the image matrix and obtaining the desired results (in our case of image processing it is to obtain and categorize the image's information).

* **1x1 convolution**

  ---

  *1x1 convolution* (kernel matrix) is basically applied or used in order to minimize the dimensionality. Although lager convolutions like 3x3 or 5x5 or sometimes 7x7 could be applied, these convolutions apply only to a 2-dimensional layer whereas the third dimension(such as in 3D) would still remain the same and may introduce complexity. That's where we use 1x1 so as to reduce that third dimension of layers(in case of 3D).

* **Feature maps**

  ---

  *Feature maps* are the output of the filters (kernel matrix) applied on the image matrix information. Whenever a filter/kernel such as a 1x1 convolution or 3x3 convolution or 5x5 convolution is applied on the image matrix (operations are applied between image and kernel matrix) we obtain the processed information as output in the form of feature maps.

* **Feature engineering**

  ---

  A *feature* typically can be representation of raw data and *feature engineering* is the process of converting this raw data into useful features that represents the underlying problem in a better way. By transforming these data to features it provides flexibility to the model, making it simpler providing better results.



**Bonus topics**

---



* **Activation function**

  ---

  *Activation function* is an important feature that decides whether the given information is relevant or should it be ignored and decides whether the neuron needs to be activated or not(Artificial neural network). An activation function also allows the system to back propagate as it updates the weights since the inputs could also consist of errors.

* **How to create an account on GitHub and upload a sample project**

  ---

  1. Open any browser(Chrome or Firefox or IE or any other) and navigate to [GitHub](https://github.com).
  2. Now enter your username, email and password that you want for this account.
  3. Now wait for few seconds and you have successfully created your GitHub account.
  4. Click on the + icon and select New Repository.
  5. Now enter the name that would want to give to the repository and any description if needed.
  6. You can also make your repository private or public by selecting either of the options below the description field.
  7. Since this is your first repository check the field which says "Initialize this repository with a README" and click on create repository.
  8. Now click on upload files button.
  9. Now you can either drag and drop the files you want to upload or select them by clicking choose files.
  10. Now click on commit changes and that is how you have successfully uploaded your project.

* **Receptive field**

  ---

  *Receptive field* is a sensory neuron(Artificial neural network) which controls neuron activation based on the action or stimulus it received.In case of humans it can be skin, retina tongue and so on. The neurons that get activated are present in hidden layer and their activations depends on the information given to it.