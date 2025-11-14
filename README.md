# Image Assets for the Herbs App

This repository hosts all the image assets for the **[pharmacist-sabot/herbs-app](https://github.com/pharmacist-sabot/herbs-app)** project.

The purpose of this repository is to provide a simple, free, and version-controlled way to manage the visual content used within the application. All images stored here are publicly accessible and are fetched by the app to display pictures of various herbs.

---

## Usage

To use an image from this repository in the application (or anywhere else), you must use the **raw file URL**. Using the standard GitHub URL will not work inside an `<img>` tag.

Follow these steps to get the correct URL:

1.  Navigate to the image file you want to use.
2.  Click on the file to open its preview page.
3.  Right-click on the image itself and select **"Copy Image Address"** (or a similar option in your browser).

The resulting URL will be in the following format:

```
https://raw.githubusercontent.com/pharmacist-sabot/<YOUR_REPOSITORY_NAME>/main/<image_name.png>
```

**Example:**
If your repository is named `herbs-app-assets` and you want to use `garlic.jpg`, the URL would be:
`https://raw.githubusercontent.com/pharmacist-sabot/herbs-app-assets/main/garlic.jpg`

This is the URL that should be placed in the `ImageUrl` column of the Google Sheet.

---

## Adding New Images

To add new images to this collection, follow these steps:

1.  In the main page of this repository, click on **`Add file` > `Upload files`**.
2.  Drag and drop the new image files into the upload area, or use the file selector.
3.  Once the files are uploaded, scroll to the bottom of the page.
4.  Add a brief, descriptive commit message (e.g., "Add images for turmeric and ginger").
5.  Click the **`Commit changes`** button.

### Naming Convention

For consistency and to avoid potential issues, please use the following naming convention for all image files:
-   Use lowercase letters only.
-   Use hyphens (`-`) to separate words instead of spaces (e.g., `holy-basil.jpg` instead of `Holy Basil.jpg`).
-   Use descriptive names.

---

## Directory Structure

Currently, all images are stored in the root directory for simplicity. If the number of images grows significantly, they may be organized into subdirectories based on categories in the future.

---

## License

The images in this repository are intended for use within the associated project. Please ensure you have the rights to use any images you upload.
