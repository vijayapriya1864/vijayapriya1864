AI-based localization and classification of skin disease with erythema Although computer-aided diagnosis (CAD) is
used to improve the quality of diagnosis in various medical fields such as mammography and colonography, it is not
used in dermatology, where noninvasive screening tests are performed only with the naked eye, and avoidable
inaccuracies may exist. This study shows that CAD may also be a viable option in dermatology by presenting a novel
method to sequentially combine accurate segmentation and classification models. Given an image we
decompose the image to normalize and extract high-level features. Using a neural network-based segmentation
model to create a segmented map of the image, we then cluster sections of abnormal skin and pass this information
to a classification model. We classify each cluster into different common skin diseases using another neural network
model. Our segmentation model achieves better performance compared to previous studies, and also achieves a
near-perfect sensitivity score in unfavorable conditions. Our classification model is more accurate than a baseline
model trained without segmentation, while also being able to classify multiple diseases within a single image. This
improved performance may be sufficient to use CAD in the field of dermatology
