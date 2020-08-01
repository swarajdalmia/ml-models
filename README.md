Implementations of different machine learning models like(RNNs, LSTMs, Transformers etc.) with different frameworks(PyTorch, Tensorflow, MXNet etc).

### Popular Frameworks:

- Tensorflow : Developed by Google. Popularly used with Python but supports JavaScript, C ++, Java and Go, C # and Julia. It operates with a static computational graph. Tensorflow.js(on the web), TF Lite(mobile, IoT).

- PyTorch : Developed at Facebook. Unlike Tensorflow it used a dynamic computational graph which gives it many advantages. PyTorch Lightning(high-level interface for PyTorch). 

- Sonnet : Built on top of TensorFlow by DeepMind. It has High-level object-oriented libraries that bring about abstraction when creating models. The idea of Sonnet is to construct the primary Python objects corresponding to a specific part of the neural network. Separating the process of creating objects and associating them with a graph simplifies the design of high-level architectures.

- Keras : Now a high level API over TensorFlow 2.0. Ideal for prototyping and using it does not block access to lower level frameworks. 

- MXNet : It is a highly scalable deep learning tool that can be used on a wide variety of devices. Its under the Apache Project. The main emphasis is placed on the fact that the framework is very effectively parallel on multiple GPUs and many machines. One can choose between imperative and symbolic programming styles. 

- Gluon : Gluon is based on MXNet and offers a simple API that simplifies the creation of deep learning models. Similar to PyTorch, the Gluon framework supports work with a dynamic graph, combining this with high-performance MXNet. 

- ONNX : ONNX enables models to be trained in one framework and transferred to another for inference. ONNX models are currently supported PyTorch, Keras, TF, MXNet.

Some others : Swift(iOS), Chainer, DL4J(supports JVM, Spark), Microsoft Cognitive ToolKit, Shogun(C++), Caffe, 

#### [Some recommendations on the framework to choose](https://towardsdatascience.com/top-10-best-deep-learning-frameworks-in-2019-5ccb90ea6de):
- If you are just starting out and want to figure out what’s what, the best choice is Keras.
- For research purposes, choose PyTorch.
- For production, you need to focus on the environment. So, for Google Cloud, the best choice is TensorFlow, for AWS — MXNet and Gluon.
