# Spatial Transformer Network
Spatial Transformer Network (STN) provides attention to a particular region to in an image, by doing transformation to the input image. The code in this repository does Affine transformation to image, but other transformation can be explored. Detailed explanation of the concept is explained in the [blog post](https://towardsdatascience.com/implementing-spatial-transformer-network-stn-in-tensorflow-bf0dc5055cd5)


## Visualizations

You can clone the repository and directly run the [Visualization-STN-MNIST.ipynb](https://github.com/dedhiaparth98/spatial-transformer-network/blob/main/Visualizing-STN-MNIST.ipynb) file where you will see how the STN network applies transformation to the Input image. These transformations can be not only restrcited to the first layer but could be applied to other layers as well.

Below are the visualizations when applied to the input image directly

![Visualizations](https://github.com/dedhiaparth98/spatial-transformer-network/blob/main/images/visualization.jpg)


## Custom Training and Model Design

If you wish to train the network, then you can run the [Spatial Transformer Network.ipynb](https://github.com/dedhiaparth98/spatial-transformer-network/blob/main/Spatial%20Transformer%20Network.ipynb). The model will generate following graph

![Model Architecture](https://github.com/dedhiaparth98/spatial-transformer-network/blob/main/images/model.png)

## References

1. M. Jaderberg, K. Simonyan, A. Zisserman, K. Kavukcuoglu, Spatial Transformer Networks, CVPR, 2015

2. https://kevinzakka.github.io/2017/01/10/stn-part1/

3. https://kevinzakka.github.io/2017/01/18/stn-part2/
