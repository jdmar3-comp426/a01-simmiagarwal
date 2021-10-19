[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6042437&assignment_repo_type=AssignmentRepo)
# a01 A series of tubes

This assignment is intended to dust off the cobwebs and get web basics into your mind since you will need them for all of the rest of the assignments. 

In this assignment, we will create a set of HTML pages that are styled using CSS.

Follow the GitHub Classroom link for a01 listed on Piazza and Sakai. Clone the repository that it sets up for you. Just like last time, there will only be LICENSE AND README.md files in the repository when you clone it. You will create the rest of the files referenced below.

These pages should describe a mythological character or mythological story. The term “mythological” can be broadly interpreted and can be from any culture, time period, media universe: any mythos is fine. The content doesn’t really matter. You are encouraged to use images and video but aren’t required to do so. Be sure to link to sources (citation) if you use images or video found on the Internet. Wikimedia Commons is a good place to find images and other media that are licensed for redistribution.

    For ease of development, you are encouraged to use the browser-sync npm plugin from a00. Remember that all of your work (and commands) should be done inside of the a01-$YOURGITHUBUSERNAME folder in your workspace. It seriously makes writing and checking easier. If you do, remember to add a copy of this .gitignore file to your repository. Be sure to rename it .gitignore.

## Making a simple website

The major requirements for this assignment are these:
### HTML

- [ ] There should be a single logical “starting” or “home” page named index.html. This is a standard in web development because it allows the server to render it without specifying which file you want to view (why index.html).
- [ ] There should be at least 3 OTHER pages, not including index.html. The others can be named whatever you like. There is no maximum limit of pages, but don’t go overboard. You’re not getting extra credit for extra pages or anything.
- [ ] index.html should contain a link to all of your other pages.
- [ ] Other pages should at least contain a link back to index.html. You might also develop some sort of set of navigation links so that you can move from one page directly to others.
- [ ] All of the pages should use the same CSS stylesheet, which should exist as a separate file styles.css.
- [ ] All of your html pages should be valid HTML5 (html validator). Minor warnings about browser incompatibility are OK.

### CSS

This is the part of the assignment where you can get creative. Googling examples of css and best practices is a great place to start.

Especially for this assignment w3schools is going to be your best friend. Refer to other resources listed under guides on this site as well (and feel free to add anything that you find useful to those guides).

At a minimum, your stylesheet should:

- [ ] Have at least 10 selectors
- [ ] Use two or more fonts for different kinds of content
- [ ] Set the background color of some elements, specifying the color by hex notation
- [ ] Set the border of some elements
- [ ] Use the :hover pseudo-class for one or more elements
- [ ] Use at least one class-based selector
- [ ] Use at least one id-based selector
- [ ] Have at least one selector rely on the hierarchical relationship between two elements
- [ ] Use width and/or height to control the geometry of an element
- [ ] Validate as CSS3 using the W3C CSS validation tool (css-validator)

The autograder will check specifically for all of the above numbered parameters in your repositories. Other than these basic features, feel free to use whatever HTML5 elements and CSS3 attributes you would like. Be creative.

### Disclaimer

Do not use any CSS preprocessors or libraries (e.g. Bootstrap, Bulma, etc.). You are required to write all of the css yourself. Later assignments will deal with using these libraries.