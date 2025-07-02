# Images Directory

This directory contains sample images used in the `sample-markdown-test.md` file for testing relative image paths in markdown.

## Expected Image Files

To fully test the markdown file, place the following image files in this directory structure:

### Main Images Directory (`./images/`)

-   `sample-1.jpg` - Sample image 1
-   `sample-2.png` - Sample image 2 with PNG format
-   `reference-image.jpg` - Used for reference-style image linking

### Screenshots Subdirectory (`./images/screenshots/`)

-   `demo.jpg` - Demo screenshot image

### Root Directory (same level as markdown file)

-   `sample-image.jpg` - Image in same folder as markdown file
-   `local-image.gif` - Local GIF image example

### Parent Directory (`../images/`)

-   `shared-image.png` - Image in parent folder (if applicable)

## Image Formats Supported

The markdown file tests various image formats:

-   `.jpg` / `.jpeg`
-   `.png`
-   `.gif`

## Notes

-   All image paths in the markdown file use relative paths
-   Images can be referenced using direct paths or reference-style links
-   The structure demonstrates both same-level and nested directory access
-   Replace these placeholder references with actual image files for full testing

## Adding Your Own Images

1. Place image files in the appropriate directories as listed above
2. Ensure filenames match exactly what's referenced in the markdown
3. Test the markdown rendering to verify images display correctly
