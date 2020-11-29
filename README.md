# Neural Style Transfer
In this project, we use an image recognition neural network to transfer the style of one image to another.
<br>
You can use the Jupyter notebook file to try the process with two images of your choosing. It runs in [Colab](https://colab.research.google.com/github/gregory-m-mullen/neural_style_transfer/blob/master/style_transfer_adapted_octaves.ipynb). The notebook is an adapted version of [this notebook](https://github.com/tensorflow/models/blob/master/research/nst_blogpost/4_Neural_Style_Transfer_with_Eager_Execution.ipynb), which provides more discussion of the machinery of the neural style transfer program. I tried to simplify the notebook to make it plug and play. Anyone should be able to use it with their own content and style images without changing any of the code. I also added a few features to facilitate running the process on iterations on scaled images. 
<br>
Examples of adapted images are shown in the [examples folder](https://github.com/gregory-m-mullen/neural_style_transfer/tree/master/examples). Each subfolder shows the style and content images along with the composite image produced by the style transfer program.
