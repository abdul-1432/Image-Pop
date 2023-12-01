# Image Pop

Image Pop is a lightweight JavaScript library that allows you to display a collection of images in a formatted grid. When an image is selected, it pops up in a full-screen view with navigation buttons and a close button for a seamless user experience.

## Features

- Responsive image grid display
- Full-screen view with zoom functionality
- Next and previous navigation buttons
- Close button for easy exit

## Demo

Check out the [live demo](#) to see Image Pop in action!

## Usage

1. Include the necessary CSS and JavaScript files in your HTML:

```html
<link rel="stylesheet" href="imagepop.css">
<script src="imagepop.js"></script>
```

2. Create a container for your images:

```html
<div id="image-container">
  <!-- Add your images here -->
  <img src="image1.jpg" alt="Image 1">
  <img src="image2.jpg" alt="Image 2">
  <!-- Add more images as needed -->
</div>
```

3. Initialize Image Pop:

```html
<script>
  // Initialize Image Pop
  const imagePop = new ImagePop('#image-container');
</script>
```

That's it! Now your images will be displayed in a grid, and clicking on an image will open it in a full-screen view.

## Options

You can customize Image Pop by passing options during initialization:

```html
<script>
  const options = {
    // Add your custom options here
  };

  // Initialize Image Pop with options
  const imagePop = new ImagePop('#image-container', options);
</script>
```

For more customization options, refer to the [documentation](#).

## Inspired by

This project is inspired by the [Image Pop on CodePen](#).

## License

This project is licensed under the [MIT License](LICENSE).
