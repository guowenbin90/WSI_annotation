# WSI_annotation
## Lab#1: 
### Use the [Aperio](https://www.leicabiosystems.com/us/digital-pathology/manage/aperio-imagescope/) to draw the glom and tubule. Here the green color is glom and yellow color is tubule. Export XML file from annotation.
<img src="https://github.com/guowenbin90/WSI_annotation/blob/main/figures/Glom%20and%20tubular%20annotation%20in%20Aperio.png" width=40% height=40%><img src="https://github.com/guowenbin90/WSI_annotation/blob/main/figures/XML%20file%20from%20annotation.png" width=41% height=41%>

### Our objective is to convert annotations to OME TIFF format and JSON file. 
Here are steps ([WSI_annotation.ipynb](https://github.com/guowenbin90/WSI_annotation/blob/main/WSI_annotation.ipynb)):
1. Use lxml package to parse the separate annotation layers.
2. Use the openslide package to read the image regions corresponding to annotations.
3. Save the extracted image along with its boundary mask (1’s inside boundaries and 0’s outside).

<img src="https://github.com/guowenbin90/WSI_annotation/blob/main/figures/glom1.png" width=12% height=12%><img src="https://github.com/guowenbin90/WSI_annotation/blob/main/figures/mask1.png" width=12% height=12%><img src="https://github.com/guowenbin90/WSI_annotation/blob/main/figures/glom2.png" width=15% height=15%><img src="https://github.com/guowenbin90/WSI_annotation/blob/main/figures/mask2.png" width=15% height=15%><img src="https://github.com/guowenbin90/WSI_annotation/blob/main/figures/tubule.png" width=13% height=13%><img src="https://github.com/guowenbin90/WSI_annotation/blob/main/figures/tubule_mask.png" width=13% height=13%>

### Here is the JSON file from given XML file.

<img src="https://github.com/guowenbin90/WSI_annotation/blob/main/figures/XML%20file%20from%20annotation.png" width=50% height=50%>
