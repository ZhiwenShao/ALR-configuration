face_align_demo.mp4 is a short video which shows the result of face alignment method proposed in [1]. "Face_align_train_val.txt" and "Face_align_solver.prototxt" are the Caffe configuration files.

Reference:
[1] Shao Z, Ding S, Zhu H, et al. Face alignment by deep convolutional network with adaptive learning rate[C]//Acoustics, Speech and Signal Processing (ICASSP), 2016 IEEE International Conference on. IEEE, 2016.

Note:
1. The video is processed frame by frame without post processing.
2. We first use the face detector provided in http://mmlab.ie.cuhk.edu.hk/archive/CNN_FacePoint.htm to detect the faces in the frame and then process face alignment for each face.
