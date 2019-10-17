# Numipulator
Numpy-based image manipulation library.

### Installation
Run `pip install numipulator`.

### Sample usage
```python
from numipulator import NImage

image = cv2.imread('image.jpg')

# Add borders and set background color to black for 3 channels image, or transparent for 4 channels image.
image_with_border1 = NImage.add_border(image, width=224, height=224)

# Add borders with custom color.
image_with_border2 = NImage.add_border(image, width=224, height=224, color=(255, 255, 255))
```
