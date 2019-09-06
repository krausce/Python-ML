###Image Classification with Keras###

This project demonstrates how to use Python CNN over google Colab. To complete this project, I referenced several articles from:
https://www.analyticsvidhya.com/ as well as others from https://medium.com/.

To understand how this is possible and/or how it works, I first had to understand how images are represented in machine languages.
To gain this understanding I worked through an image processing exercise here: https://www.analyticsvidhya.com/blog/2014/12/image-processing-python-basics/. You can see the output of that in my "Count_Stars" notebook.

In general, I followed the basic steps for approaching a machine-learning project detailed here: https://www.geeksforgeeks.org/how-to-approach-a-machine-learning-project-a-step-wise-guidance/.

Lastly, once I had a working model. I had to think about hyper-parameter optimization to improve the performance and/or efficiency of my algorithm. To understand how to do this, I read a really great article at: https://www.analyticsvidhya.com/blog/2018/12/guide-convolutional-neural-network-cnn/. With all that said, implementation matters. Having a convuluted/messy code base would make debugging or adjusting my algorithm difficult. Therefore, I read more articles and looked at examples from various sources. Ultimately, I found this article which I modeled my implementation after: https://towardsdatascience.com/keras-hyperparameter-tuning-in-google-colab-using-hyperas-624fa4bbf673.

#The most important part SO WHAT#:

    - As many of us know or at least have an intuition about, using external libraries may save time in the implementation phase, however, using them can hide the fact that they house some inefficiencies. I experimented with several options before deciding on the technologies used here.
    
    - Google Colab is perhaps the data scientist's best friend. Kudos to the google team for adding in functionality for python which makes using their platform user-friendly. Using optimized data processing libraries in conjunciton with the GPU/TPU technologies hosted by the Google Cloud Platform (GCP), makes short work of these complex problems.