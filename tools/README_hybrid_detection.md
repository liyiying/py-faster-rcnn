Tools for training, testing, and compressing Fast R-CNN networks.

demo_hybrid is a demo to detect an image combining Faster R-CNN and CloudSight: the object which Faster R-CNN may recognize wrongly can be transferred into CloudSight for re-recognition. (CloudSight is an open cloud service to recognize objects based on the Internet big data). Final results detected by the hybrid engine can be returned.

To run the demo_hybrid.py to get the hybrid detection results, you should pay attention:
(1).You should modify the path '/home/lyy/py-faster-rcnn' to your path where py-faster-rcnn is located.
(2).The default picture format is 500*375 pixels.

Then run ‘python demo_hybrid.py’