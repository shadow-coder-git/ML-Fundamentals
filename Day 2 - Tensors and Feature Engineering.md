## Tensors

Tensors is a data structure which stores the data in array/list form. People started calling it tensors as it is hard to call a name for a matrix after 3 Dimensions.

In ML Basically below are the main Dimnesional tensors:

**Not to Confuse: Basically even though a vector has multiple dimensions that is the dimension of the vector. When we consider tensor we choose the dimension of array and not the value inside it**
0D Tensor: Only a single dimension will be there -> [3] (Scalar Value)

**1D Tensor**: Basically a vector -> [1,4,6] it has list of values. According to the first statement this is 1D Tensor/Array but 3D vector. Basically used to calulate different parameters of a single person. 

**2D Tensor**: Basically a Matrix -> [[1,0],[2,0]]. Mainly used in tabular data where we have multiple rows and columns.

**3D Tensor**: Mainly used in NLP. Basically we create tokens of texts and we convert them into numbers and we combine common tokens in a set and we keep an array of thoese sets. (tokens,common token set, array of common token set)

**4D Tensror**: Mainly used in Image processing. Each pixel has 3 layers and each image has set of pixels in 2D Tensor (like 1200*800 pixels) and if we have 3 layers of these it makes an image, and if we have multiple set of image then its 4D Tensor. (RGB layer, width, height, no. of images)

**5D Tensror**: Mainly used in Video processing. If we have multiple image  (Frame per second) and we have 60 such seconds then its 5D tensor.(RGB layer, width, height, no. of images per second, no. of seconds)
