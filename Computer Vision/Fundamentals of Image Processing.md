# Where is image processing used?
- **Machine/Robot Vision**
- **Color Processing**
- **Pattern Recognition**
- **Video processing**
- **Transmission and Encoding**
- **The Medical Field**
- **Image Sharpening and Restoring**
- **Facial Recognition.**

# How Image Processing Impacts Our World

- **Enhances medical diagnosis accuracy.**
- **Improves security and surveillance systems.**
- **Powers autonomous vehicles’ vision.**
- **Enables facial recognition technology.**
- **Enhances photo and video editing tools.**
- **Drives innovations in augmented reality.**

# What is Image Processing?

- **Enhances image quality and features.**
- **Converts images into useful data.**
- **Uses filters and algorithms effectively.**
- **Enables object detection and recognition.**
- **Applied in medical, security, and media.**
- **Powers AI, AR, and VR technologies**

# What is an Image?

- Composed of pixels or visual elements.
- Captures real-world or designed scenes.
- Includes 2D or 3D visual structures.
- Stored in digital or physical format.
- Used in art, communication, and science.
- Basis for graphics and media

# How Images Are Captured

- **Light hits the camera sensor.**
	- Light reflects off objects into the lens.
- **Lens focuses the light**
	- Creates a sharp image on the sensor.
- **Sensor records light data**
	- Digital sensors use pixels to capture brightness and color.
- **Shutter controls exposure**
	- Determines how much light reaches the sensor.
- **Image processed digitally**
	- Software adjusts colors, brightness, and details.
- **Saved in digital format**
	- Stored as JPEG, PNG, or RAW files.

# From Pixels to Pictures

- **Pixel: the smallest unit of a digital image.**
- **Each pixel holds color values.**
- **Pixels form a grid structure.**
- **Higher pixel density = clarity.**
- **Software arranges pixels into visuals.**

# How are images represented in the computer?

![[Screenshot From 2025-02-26 21-33-59.png]]

# Image Sampling and Quantization

![[Screenshot From 2025-02-26 21-37-27.png]]

# Image Sampling

- **Converts continuous image to discrete.**
- **Divides the image into pixels.**
- **Quantization: Assign discrete intensity values.**
- **Determines image resolution.**
- **Higher rate = Better detail.**
- **Affects image sharpness.**

# Image sampling (example):

![[Screenshot From 2025-02-26 21-43-22.png]]
![[Screenshot From 2025-02-26 21-43-43.png]]

# Computer Vision vs. Human Vision
![[Screenshot From 2025-02-26 21-46-24.png]]

## Computer Vision
![[Screenshot From 2025-02-26 21-48-19.png]]

- Enables computers to interpret images.
- Part of AI and machine learning.
- Vision depends on:
	- Geometry
	- Physics
	- The nature of the object in the world
## Vision – An Ill-Posed Inverse Problem
![[Screenshot From 2025-02-26 21-49-46.png]]
![[Screenshot From 2025-02-26 21-50-17.png]]
## How Computer Vision Works

![[Screenshot From 2025-02-26 21-51-12.png]]

## Image Processing vs. Computer Vision

![[Screenshot From 2025-02-26 21-52-16.png]]

## Image Processing vs. Computer Vision

![[Screenshot From 2025-02-26 21-52-44.png]]

# Applications

![[Screenshot From 2025-02-26 21-53-11.png]]
![[Screenshot From 2025-02-26 21-53-25.png]]

# Image File Formats

- Standardized methods for storing images.
- Differ in compression and features.
- Tailored for specific intended uses.
![[Pasted image 20250226215449.png]]

# Raster vs. Vector

| Parameter    | Raster                     | Vector                       |
| :----------- | :------------------------- | :--------------------------- |
| Basis        | Pixel-based images         | Math-based shapes            |
| Scalability  | Loses quality when resized | Infinitely scalable, no loss |
| File Size    | Larger for high resolution | Generally smaller sizes      |
| Best Uses    | Photos, detailed images    | Logos, illustrations, icons  |
| File Formats | JPEG, PNG, GIF, BMP        | SVG, EPS, PDF, AI            |
| Editing      | Pixel-level adjustments    | Shape-level editing          |
# Raster Dominates
- Most real-world images are raster-based.
- Pixel-level detail needed for analysis.
- Vector Used for annotations (bounding boxes).
- Helpful in representing simplified shapes.

# Image Formats


| Format | Description                                                                 | Uses                                     | Pros                                         | Cons                                          |
| ------ | --------------------------------------------------------------------------- | ---------------------------------------- | -------------------------------------------- | --------------------------------------------- |
| JPEG   | Compressed format with lossy<br>compression.                                | Web, photography,<br>general use         | Small file size, widely<br>supported         | Loss of quality with high<br>compression      |
| PNG    | Lossless compression, supports<br>transparency (alpha channel).             | Web graphics, icons,<br>images with text | High-quality, supports<br>transparency       | Larger file size than JPEG                    |
| GIF    | Limited to 256 colors, supports<br>simple animations.                       | Web animations,<br>small icons           | Lightweight for<br>animations                | Limited color depth, not<br>ideal for photos  |
| BMP    | Uncompressed or minimally<br>compressed format.                             | Printing, simple<br>applications         | High quality, simple<br>structure            | Large file size                               |
| TIFF   | Versatile format supporting<br>lossless compression and multiple<br>layers. | Professional<br>photography,<br>printing | Excellent quality,<br>retains image details  | Large file size, less<br>web-friendly         |
| WebP   | Combines lossy and lossless<br>compression, designed for web use.           | Modern websites                          | High-quality<br>compression, smaller<br>size | Limited support in older<br>software          |
| SVG    | XML-based format for vector<br>graphics, scalable and editable.             | Web graphics, logos,<br>icons            | Scalable, small file size                    | Not ideal for complex<br>images               |
| EPS    | PostScript-based format for vector<br>graphics.                             | Printing, professional<br>graphics       | High-quality vector<br>representation        | Limited compatibility with<br>modern software |

# Medical Image File Formats

- DICOM (Digital Imaging and Communications in Medicine)
	- Universal format for medical images.
	- Stores images and patient metadata.
	- Radiology (MRI, CT, X-ray).
- NIfTI (Neuroimaging Informatics Technology Initiative)
	- Format for brain imaging.
	- Compatible with fMRI, 3D scans.
	- Neuroscience, brain mapping.
- Analyze Format
	- Legacy neuroimaging format.
	- Supports 3D imaging.
	- Early-stage MRI and CT scans.