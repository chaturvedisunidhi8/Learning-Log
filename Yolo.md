<h1>YOLO</h1> 
YOLO stands You Only Look Once <br>
YOLO is an object detection model<br>
You Only Look Once (YOLO) is a series of real-time object detection systems based on convolutional neural networks. First introduced by <br>Joseph Redmon et al. in 2015, YOLO has undergone several iterations and improvements, becoming one of the most popular object detection<br> frameworks.

Previously people used Sliding Window Object Detection the more faster version such as R CNN,Fast R CNN,Faster R CNN          
<h3>Difference between Image Classification and Object Detection </h3>
<h4>Image Classification:</h4>
In image classification, the model looks at the entire image and assigns it a single label<br>
Goal: What is in the image?<br>
Output: One class label (e.g., “cat”) <br>
Granularity: Whole image (no location info)<br>
Example:<br>
Input: Photo of a cat on a couch<br>
Output: “Cat”<br>
This task is widely used in fields like Computer Vision for applications such as medical diagnosis or content tagging.<br>
It is simple.
 <br><br>
<h4>Object Detection:</h4>
In object detection, the model not only identifies objects but also locates them in the image.<br>
Goal: What objects are present and where are they?<br>
Output: Multiple labels + bounding boxes (coordinates)<br>
Granularity: Object-level<br>
Example:<br>
Input: Street image<br>
Output:Car → box at (x₁, y₁, x₂, y₂)<br>
Pedestrian → another box<br>
Modern object detection models include YOLO (You Only Look Once) and Faster R-CNN.<br>
It is complex process.<br>

Intuition
Classification answers: “What is this image?”<br>
Detection answers: “What objects are in this image and where?”

Example<br>

Suppose an image contains a dog:<br>

Image Classification<br>

Output: "Dog"<br>

Object Localization<br>

Output:<br>
Class: "Dog"<br>
Location: Bounding box around the dog<br>

| Task             | What? | Where?               |
| ---------------- | ----- | -------------------- |
| Classification   | ✅     | ❌                    |
| Localization     | ✅     | ✅ (one object)       |
| Object Detection | ✅     | ✅ (multiple objects) |

Note:Yolo can detect multiple objects
| Need                                   | Recommended Model |
| -------------------------------------- | ----------------- |
| Real-time detection of many objects    | YOLO              |
| Highest detection accuracy             | Faster R-CNN      |
| Balanced speed and accuracy            | SSD((Single Shot Detector)               |
| Exact object outlines (not just boxes) | Mask R-CNN        |

If Objects Overlap or Need Exact Shapes<br>

Use instance segmentation models such as:<br>

Mask R-CNN<br>

Instead of just boxes, it produces a pixel-level mask for each object.<br>



 
