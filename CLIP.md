<H1>CLIP MODEL</H1>  
CLIP Stands Contrastive Language Image Pretraining<br>
CLIP is Virtual Language Model Powered by OpenAI<br>
CLIP is neural network that jointly trains an image encoder and text encoder to map respective modalities to the same embedding space 
Example : Image + text or prompt

Why to use CLIP:
1) Normally image classification models need task-specific labels, creating these labels manually for millions of images is expensive and time consuming <br>
But In CLIP,Instead of assigning a single label,people naturally describe images with sentences and these captions or sentences are<br> easily available on the internet 
<br><br>
How CLIP Uses This :<br>
CLip learns from image-text pairs:<br>
1)It looks at an image<br>
2)It reads the accompanying text
3)It learns to connect visual concepts with language<br>
As a result ,CLIP can recognize objects without being trained on a fixed set of labels<br>

<b>Example</b><br>
If you show CLIP a new image and ask:<br>
is this a dog<br>
is this a car<br>
is this a husky<br>
1)It can compare the image with those text description and choose the best match<br>
2)Natural lamguage supervision allow the image encoder to create rich vectors that better encode the meaning of the image <br>
3)Clip learns via contrastive learning and clip's image encoder is usually a convolution or transformer architecture.








  


   

 
