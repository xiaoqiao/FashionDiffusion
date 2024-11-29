# Fashion Diffusion Dataset

This dataset is a collection of fashion runway images with detailed annotations for various attributes, visual features, and generated descriptions. It was created to support research in fashion analysis and image generation.

> **Note**: This is a sample dataset. A larger-scale dataset will be released after the paper's acceptance.

## Dataset Overview

The dataset contains fashion runway images with extensive annotations including:
- Show information (ID, title, brand)
- Clothing attributes (gender, season, style, category, etc.)
- Bounding box coordinates
- Visual features (aesthetic scores, color analysis)
- Generated captions
- Face detection information
- Color schemes
- Image specifications

## Data Availability

- Current Release: Sample dataset with 1000 images for preview and initial experimentation
- Future Release: A comprehensive, larger-scale dataset will be made publicly available following the paper's acceptance
- Location: The sample images can be found in the "fashion_diffusion_sample_1000" folder

## Data Structure

Each entry in the dataset contains the following fields:

### Show Information
- `show_id`: Unique identifier for the fashion show
- `show_title`: Title of the fashion show
- `brand`: Fashion brand name

### Garment Details
- `gender`: Type of clothing (men's/women's wear)
- `season`: Fashion season (e.g., Spring/Summer)
- `style`: Style classification (e.g., Minimalist, Urban)
- `category`: Garment category (e.g., jacket, trousers)
- `collar`: Collar type
- `sleeve`: Sleeve length
- `sleeve_type`: Type of sleeve design
- `fabric`: Material type
- `contour`: Silhouette type (e.g., A-line, H-line)
- `clothes_length`: Length classification
- `technology`: Manufacturing technique
- `texture`: Texture description
- `accessories`: Accessory details

### Visual Features
- `aesthetic`: Aesthetic score
- `cv_var`: Computer vision variance
- `cv_lightness`: Brightness measurement
- `cv_saturation`: Color saturation measurement
- `color_1/2/3`: Dominant colors in the image

### Image Metadata
- `ori_w`: Original width
- `ori_h`: Original height
- `tgt_w`: Target width
- `tgt_h`: Target height
- `ratio`: Aspect ratio
- `path`: Image file path

### Annotations
- `caption-base`: Basic image description
- `caption-large`: Detailed image description
- `prompt_image`: Generated image prompt
- `prompt_clothes`: Detailed clothing prompt

### Face Analysis
- `face_count`: Number of faces detected
- `face_loc`: Face location coordinates
- `face_col`: Face column information
- `look_at_viewer`: Boolean indicating if subject is looking at camera

## Usage

This dataset can be used for:
- Training fashion image generation models
- Analyzing fashion trends and attributes
- Developing computer vision models for fashion analysis
- Studying runway fashion characteristics

## License

This dataset is released under Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC).

## Citation

If you use this dataset in your research, please cite:
```
[Citation information to be added after publication]
```
