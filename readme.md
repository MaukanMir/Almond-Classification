
## About Dataset
#### Almonds exhibit remarkable diversity. Each almond variety has distinct characteristics, which makes identifying and utilizing them a practical endeavor.

- Length (major axis)	Length of the almond in the image (based on number of pixels)
- Width (minor axis)	Width of the almond in the image (based on number of pixels)
- Thickness (depth)	Thickness of the almond in the image (based on number of pixels)
- Area	The area of the Almond region detected in the image
- Perimeter	Total length of the almond boundary
- Roundness	Roundness of the almond: 4 * area / ( π * length ** 2)
- Solidity	Area / area_hull
- Compactness	perimeter**2 / (4 * π * area)
- Aspect Ratio	Length / Width
- Eccentricity	sqrt(1 - ( Width / Length ) **2 )
- Extent	Area / area_bbox(bounding box)
- Convex hull(convex area, or area hull)	smallest convex set that contains bounding points
- Type	Almond Type


## Link To Dataset: https://www.kaggle.com/datasets/sohaibmoradi/almond-types-classification/data