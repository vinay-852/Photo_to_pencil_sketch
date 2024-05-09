# LetsGrowMore Virtual Internship Program
![image](https://github.com/vinay-852/LGMVIP-DataScience-2/assets/132639307/be2c4666-662f-477c-9392-fce50a174abf)


This program provides a unique opportunity for students to work on real-world problems, enhancing their understanding of the industry and enriching their learning experience.


## Task 3: Image to Pencil Sketch with Python



This project is about converting an image into a pencil sketch. We use Python and its libraries to achieve this.

### Process

1. **Read the Image in RBG Format**: The first step in this process is to read the image in RBG format. This is the standard format that images are usually in.

2. **Convert Image to Grayscale**: Next, we convert the RBG image to a grayscale image. This turns the image into a classic black and white photo. We do this because pencil sketches are monochrome and converting our image to grayscale gets us closer to that effect.

3. **Invert the Grayscale Image**: The next step is to invert the grayscale image. The result is what's often referred to as a "negative" image. Inversion can be used to enhance details in the image.

4. **Create the Pencil Sketch**: Finally, we create the pencil sketch. We do this by mixing the grayscale image with the inverted blurry image. This is done by dividing the grayscale image by the inverted blurry image. Since images are just arrays of pixels, we can easily do this programmatically using the `divide` function from the `cv2` library




