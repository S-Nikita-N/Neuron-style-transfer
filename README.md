# Neuron-style-transfer

Using models: VGG16 VGG19 ResNet50 from torchvision model

I have made 3 experiments with different input content and style images.<br>
All 3 generative output pictures went trough 50 epochs on each CNN<br>

ResNet (as it expected) appears more powerful in Neuron Style Transfer. But Vgg 19 showed worse results then Vgg 16 - I explain it as the result of better choice style and content layers/weights on Vgg 16 than on Vgg 19. So I think we can reach much better results on Vgg 19 and even on ResNet if try to experiment with style/content layers weights.

<img src="style and content images/content1.jpg" width="300"/>  +  <img src="style and content images/style1.jpg" alt="total loss" height="300"/> =
<br/>
=
## VGG16:<br/> ##
<img src="output images/VGG16_1.png"  width="300"/>
<br/>

## VGG19:<br/>
<img src="output images/VGG19_1.png"  width="300"/>
<br/>

## ResNet50:<br/>
<img src="output images/ResNet50_1.png"  width="300"/>
<br/><br/><br/><br/>

<img src="style and content images/content2.jpeg" width="300"/>  +  <img src="style and content images/style2.jpeg" height="300"/> =
<br/>
=
## VGG16:<br/> ##
<img src="output images/VGG16_2.png"  width="300"/>
<br/>

## VGG19:<br/>
<img src="output images/VGG19_2.png"  width="300"/>
<br/>

## ResNet50:<br/>
<img src="output images/ResNet50_2.png"  width="300"/>
<br/><br/><br/><br/>

<img src="style and content images/content3.jpg" height="250"/>  +  <img src="style and content images/style3.jpg" height="250"/> =
<br/>
=
## VGG16:<br/> ##
<img src="output images/VGG16_3.png"  width="300"/>
<br/>

## VGG19:<br/>
<img src="output images/VGG19_3.png"  width="300"/>
<br/>

## ResNet50:<br/>
<img src="output images/ResNet50_3.png"  width="300"/>
<br/>


