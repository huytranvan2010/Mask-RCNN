# Mask-RCNN
Mask R-CCN

## Faster R-CNN

Faster R-CNN sử dụng CNN feature extract để extract convolution feature map, sau đó feature map này được đưa vào Region Proposal Network để tại ra các ROIs. Áp dụng ROI pooling để chuyển các region proposals về cùng dimensions. Sau đó nó đựa đưa vào FC layers cùng với 2 đầu ra để classify và predict offset values cho bounding boxes.
![FasterRCNN](/images/FasterRCNN.jpeg)

## Mask R-CNN
Để từ bài toán object detection sang object segmentation, ta bổ sung thêm 2 convolutional layers vào mô hình Faster R-CNN.
![piggyback](/images/piggyback.png)







https://jonathan-hui.medium.com/image-segmentation-with-mask-r-cnn-ebe6d793272
