# Changelog

## v1.3.1
- Upgrade to Java 11
- Build new installers for Windows, Linux and Mac OS X
- Single instance support for the launcher
- No need anymore to configure the memory amount for image processing
- Fix Java Advanced Imaging issues with Java 11
- Add new look and feels ([Radiance Substance](https://github.com/kirill-grouchnikov/radiance))
- Use xml to store all the files (persistence of project, classes editor...). Not compliant with previous projects files.
- Fix issue with dark look and feels
- Support of HiDPI monitors
- Update help

## v1.2.7

- Fixed issues: 29 and 47
- Update Java Virtual Machine
- Other minor bugs fixed

## v1.2.5

- Fixed issues: 22, 40 to 46
- Supports Java 1.6 and Windows Vista
- Read all previous JMicroVision project files
- More texture descriptors
- Supervised classification (k-nearest neighbor)
- Improvement of UI (Table, Text field and spinner have similar behaviors)
- Aqua and GTK+ Look and Feel are supported (still some minor issues)
- Online help has been actualized
- Other minor bugs fixed

## v1.2.2

- Fixed issues: 29 to 39 (see http://www.jmicrovision.com/mantis/)
- Spatial Calibration: Custom calibration, shift the image origin, change the Y axis direction
- Profile tool optimization
- Create a slide show
- Slide show and Multiview configuration saved in the project file
- Modify object shape: Smooth, polygonal approximation and convex hull
- 1D Measurement: Polyline and freehand line, more parameters, show profile and statistics
- 2D Measurement: More statistics on histogram
- Color Parameter for Note, 1D et 2D Measurement
- Channel operations : IHS transform
- Improvement of morphological operations
- Custom persistent filters for Classical filtering and Morphology
- Custom filters and templates are recovered from the last installed version.
- Background: get real surface
- Plugins: Create your own image processing functions
- Error messages of JMicroVision sent to the file “erroLog.txt”
- Native launcher for Windows, Linux and Solaris (resolves the JRE path and the JRE parameters)
- File association (*.jmv) on Windows
- Online help has been actualized


## v1.2.0

- Fixed issues: 21, 23, 24, 25, 26, 27 and 28 (see http://www.jmicrovision.com/mantis/)
- Improvement of the image visualization system
- Time consuming processes in separate threads (stop a process by clicking on its progress bar)
- Multiview (1-8 images) of any image of the project (custom or synchronized zoom)
- Object separation module (based on a new algorithm) (experimental tool)
- Profile in all directions (+ color mode)
- Image rectification by control points (stack images representing the same scene but have a different size, orientation or deformation)
- More shortcuts: arrow keystrokes for moving the image or the selected drawings, mouse wheel for zooming, space bar for moving the image with the hand
- Export project in SVG (Scalable Vector Graphics format)
- Image Factory as new Tool, with a lot of new operations :
    - Arithmetic operations (add, subtract, multiply and divide)
    - Logical operations (not, and, or and xor)
    - Binary (hole fill, border kill, Euclidian distance map, reconstruction) (requires binary images)
    - Morphology with customized structuring element (opening, closing, erosion, dilation, external gradient, internal gradient, white tophat, black tophat)
    - Channel operation (extraction and merging)
    - Convolution filtering (blur, sharpen, edge, Gaussian ... and custom filters)
    - Nonlinear filtering (median, min, max and Kuwahara)
    - Gradient filtering (Sobel, Roberts, Prewitt, Freichen)
    - Enhancement (manual enhancement, automatic and equalized levels, background subtraction)
    - Pseudo color (15 palettes)
    - Segmentation (simple binarization, color and gray intensity threshold, k-means clustering, watershed segmentation by markers)
    - Rasterize drawings (convert vectorial objects to bitmap)
    - Plugin (add your own image processing functions, documentation available soon)
    - Icon before the image name to identify the image type (Color, gray or binary)
- Create an image from data
- New project from another project (import preferences, image operations...)
- Magic wand to create objects (experimental tool)
- Define working areas (ellipse and polygon) that can be used in most tools
- More palettes for coloring objects from a parameter
- Moves automatically the image when drawing hitting a border (option)
- Antialiasing option for drawings
- Round shape lens option
- Fix drawing refreshing with small or high zoom factor
- Calibration module improvement
- Find automatically the images linked to the project when they are in the same directory (if files have been moved)

## v1.1.1

- Fixed issues: 4, 16, 17, 19 and 20 (see http://www.jmicrovision.com/mantis/)
- Complete online help
- Java runtime 1.5 update 3 included
- Possibility to use the OpenGL acceleration
- Improved navigation for small or very high images
- Error messages when the project is not saved or loaded properly
- Resolve image paths in the project
- Read 16 and 32 bits per channel images (converted in 8 bits/channel)
- Fixed some minors bugs

## v1.1.0

- Online help (not complete)
- Java runtime 1.5 included
- New icons and shortcuts in the interface
- Define a working area (to get results from it)
- Draw within the lens
- Open images or projects by dragging them inside the workspace
- Reopen a project even when the main image is not available
- 5 automatic thresholds
- Customize the display of date and numbers
- Change the measure unit in real-time (also integrates Anglo-Saxon units)
- More exporting data formats
- Template to save settings of Object Extraction
- Texture descriptors
- Vertical Profile (shows the vertical variation of granulometry, objects or background)
- Image Factory (uses several operators, e.g. median filter to reduce noise of an image

## v1.0.1

- Resolved issues: 2, 3, 5, 7, 8, 9 ,12, 13, 14 and 15 (see http://www.jmicrovision.com/mantis/)
- Some other minor bugs resolved (in Classification and Point Counting)
- The tiled TIFF format has been improved (it uses compression, image loading is faster and the display is much more fluid when moving the image)
- Manage the memory allocated to JMicroVision and the cache memory of the image tiles.
- New installer (Installshield X multiplatform)
- Start JMicroVision with or without the console

## v1.00 Beta - 15th June 2004

- First public release on the Internet
