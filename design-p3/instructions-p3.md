# IDMX 225 Project 3
## Add three (3) images to the About Me page as figure elements with figure captions


### Project Summary 

You will copy the files from Project 2 into this repo. Then you will make sure that you are only editing within a P3 development environment.

For imagery, you are going to take three (3) photos (as jpg files) that make up a coherent theme. You'll resize the images using a photo editor and add them to your images folder with proper filenames. Then you'll edit `index.html` and `styles.css` to make the required changes.

I expect you to have read your textbook as preparation for this assignment. Also, you must use our CSS formatting rules from the CISY 225 Style Guide.

A complete project will have 1) the Project 3 `README.md`, 2) three properly sized and named `jpg` files, and 3) correctly edited and validated `index.html` and `styles.css` files.

### Instructions

1.  Clone your completed Project 2 repo and this P3 repo to your local computer. 

2.  On your local computer, move the P2 files into this P3 repo and remove the empty P2 folder from your local computer. 

3. Refer to `Screencast: Copy Previous Project Into New Project` in `Canvas` for a refresher of how to do that. The remove is super important because it will keep you and your code editor from being confused.

4.  Add or edit the `README.md` file with information about this project. Commit and push all changes in this P3 repo up to GitHub. __VERY IMPORTANT:__ Refresh your GitHub P3 homepage (after every `push`) and check it out thoroughly to see it has your have updated files.

5.  Decide on your theme and go out and take some photos. __VERY IMPORTANT:__ Store (archive) the originals somewhere on your computer, USB flash drive, or cloud storage. Better yet, archive your images in two (2) different places.

6.  You will edit three (3) of your best photos and resize the pictures to fit best on a mobile screen. Do that by opening each file in a photo editor and find the resize menu. Make the __width__ of the picture `320px`. Be sure you are making the width be `320px` and not the height. (You will not specify the height because, when you change the width, the height will automaticall change according to the aspect ratio of the picture.) 

7.  Save the edited picture as a `jpg` file with a filename (simple, lower-case, and no spaces) that includes `-320w` at the end of the filename but before the `.jpg` file extension. All letters in the filename should be lowercase. This example of a good filename `red-rose-320w.jpg` is simple, all lowercase, using dashes to separate words (no spaces), and has lowercase `.jpg` as its file extension.

8.  __DO NOT__ save the original photos in the repo. Only the edited photos should go in the repo. Remember, you need to save the original pictures somewhere you can find them later.

9.  Copy the `-320w` pictures into the images folder.

10.  In your `index.html` file make a new html5 `section` element below the `about-me` section but before the close of the `main` element. That new `section` will have an `about-me` class. __NOTE:__ Putting the new `section` element in the right place is important. Carefully read your `index.html` to check that it has no errors. If the code editor has turned anything red, this is a warning that there is a serious typo somewhere.

11.  Inside this new `section` element, insert three (3) html `figure` elements using the proper html5 tags. Refer to the Mozilla page https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure for the example `html` code I want you to use. (Do not copy their example CSS.) Make sure each `src` attribute has a relative link to the proper `jpg` file in your images folder and it works. Make sure you include a meaningful `alt` attribute to each image. 

12. For each `figure` element, an `img` element and a `figcaption` element will be its children. Put the `figcaption` element after the `img` element. The text for the `figcaption` should be short and simple but try to to make it descriptive to the photo.

13. At the bottom of your CSS put a new rule for the `figure` element and make it so that text is center aligned.

14. The CSS for __every__ image on your page should make the image have a maximum width of 100% of its parent element. Include a new CSS rule in `styles.css` that uses CSS inheritance and meets the above requirement. Find the best CSS selector to use that gives you a low specificity so the rule can be easily overwritten if needed. Taking the cascade into account, put your new rule declaration block right after the `body` declaration block in `styles.css`. 

15.  In the `index.html` file, put two (2) horizontal rules between the three images. Refer to your text to find the correct tag for a horizontal rule. __Think carefully about where in the html the horizontal rules need to go.__ You have 3 figures and 2 horizontal rules and the horizontal rules should __not be__ inside a figure element. Using your code editor, format your code to get proper nesting. Look at how elements are nested. The horizontal rules will be children of the `section` element and siblings of the `figure` elements.

16. You now have 3 `section` elements in your `index.html` file. Add an `h2` heading right after the open of each `section` tag.These `h2` heading elements will be the section titles and will say:
* Hello, I'm
* Did you know
* Photo Gallery

17. There is an error in P2 that you will correct. The CSS uses a `italic font-style` but the `Fira Sans` italic font is not being downloaded. The fix is in the `<link>` in your `index.html` that downloads from `Google Fonts`. Figure out what to do and update `index.html`.

18. Delete the P2 `instructions.md` file and the `design` folder from your repo.

19.  __Validation:__ Look carefully for anything displayed in red and, if so, fix them. Then, validate your html.

20.  __Validation:__ Look carefully for anything displayed in red and, if so, fix them. Then, validate your CSS.

21. Commit and push all local changes to your GitHub repo and refresh that page to see that your changes pushed.

## Sample
Below is a sample of a complete Project 3. 

<img src="https://github.com/cynthiateeters/about-me-3/blob/master/instructions/screenshot.png" width="600" style="border: 2px solid black;">
