# tensorflow-cifar_10
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

Homepage: https://www.cs.toronto.edu/~kriz/cifar.html

Source code: tfds.image_classification.Cifar10

Versions:

3.0.2 (default): No release notes.
Download size: 162.17 MiB

Dataset size: 132.40 MiB

Auto-cached (documentation): Yes

Splits:

Split	Examples
'test'	10,000
'train'	50,000
Features:

FeaturesDict({
    'id': Text(shape=(), dtype=tf.string),
    'image': Image(shape=(32, 32, 3), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
