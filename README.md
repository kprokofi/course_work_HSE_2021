# course_work_HSE_2021
This is repository for the course work of the HSE University. Theme: "Effective methods of neural network compression"

This course work will discuss effective methods for calculating root operations in neural networks, which machine learning models can be optimized and how, which different architectures are suitable for running on mobile devices. Particular attention will be paid to optimization processes such as quantization and pruning. Existing frameworks for these tools will be considered, in particular NNCF, why this particular framework is suitable for industrial machine learning, and why do we generally have any framework for model compression algorithms.

The practical part presents the implementation of algorithms for distilling knowledge between neural networks, static pruning after training, iterative pruning, post-training quantization methods and a dynamic type of quantization during training. To test these algorithms, convolutional and fully connected neural networks were taken, in particular, the most popular ResNet architecture and the FashionMNIST academic dataset were chosen for compression algorithms. In the final part, we will look at and apply the NNCF framework to a real problem of anti-spoofing faces, where MobileNetV3 is taken as the backbone.

Language: Russian
