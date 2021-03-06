# mask_ssd
This is the Base Repo for my **Mask SSD** Project forked from [creotiv](https://github.com/creotiv/keras-tools)'s ssd version which is based on [rykov8](https://github.com/rykov8/ssd_keras)'s ssd keras implementation which is again a reimplementation of the original [SSD](https://github.com/weiliu89/caffe/tree/ssd) which is more or less inspired by [Yolo](https://github.com/pjreddie/darknet), [Faster R-CNN](https://github.com/rbgirshick/py-faster-rcnn) and all the other work that has been done during the last 6 years since [AlexNet](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf). Sorry to anybody who i forgot to mention.

## ToDo
- [ ] Understand necessary modifications to be able to do segmentation in parallel to box prediction
- [ ] Cleanup Model
- [ ] Extend Model to make it trainable
- [ ] Train on Model on COCO
- [ ] Test and Improve Model
- [ ] Export Model to Tensorflows object detection API and make it run on my [real_time_object_detection project](https://github.com/GustavZ/realtime_object_detection)
