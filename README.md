# image-colorization

The project aims to color black and white images via Machine Learning without any human supervision. More specifically, 
the project uses anime (One-Piece) manga data to train the colorization algorithm. The project is far from completion, 
and is being worked upon actively by me. The case of colorizing a black and white comic may seem impractical and not useful 
to some. But since the algorithm is trained only based on data, and without any domain knowledge of comics specifically, it
should directly carry on to more useful cases, like colorizing historical photographs and likely cases. Also, colorizing manga 
and comics is a very hard and work-intensive tasks. Such an application, if it reaches current human level, can have many real-world
use cases.

The following images show performance of model at its current training
![Left=(Black-White Input), Middle=(Colored Target), Right=(Predicted by Network)](https://github.com/vaibhav369/image-colorization/blob/master/assets/img1.PNG)
![Left=(Black-White Input), Middle=(Colored Target), Right=(Predicted by Network)](https://github.com/vaibhav369/image-colorization/blob/master/assets/img2.PNG)
![Left=(Black-White Input), Middle=(Colored Target), Right=(Predicted by Network)](https://github.com/vaibhav369/image-colorization/blob/master/assets/img3.PNG)

## Getting Started

This section describes how someone curious enough about this project can get themselves started on the project.

### Prerequisites

For running the project, the system must have Python3 installed. Also, the project uses some standard python libraries like numpy, keras, tensorflow. The repository, however, does not contain the entire data that was used for training because of Github's size limit, and also to keep the repository light. 

### Description

There are two IPython notebooks in the project :- image-colorization.ipynb and image-colorization-tester.ipynb. Both are nearly identical. I myself use the first to train the model. However, for testing and checking how the trained models respond, I go to the second one.

### Future Plans for Work

After having gone through literature in this field, it seems that the best way to go around this problem is GANs. Using a mean-squared error on such problems discourages sharpness and high contrast colors in output images because it is an average of many different scenarios. However, GANs do not face this problem since they can solve multiodal output problems. 

### Contributing

Contributions from anyone interested in this project are welcome. As mentioned above, the repo does not contain full training data used by the project. For getting the training data, please write to me at vaibhav.gupta.personal@gmail.com.
