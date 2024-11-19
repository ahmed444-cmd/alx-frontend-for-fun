### README.md

# Sass Basics Project

## Resources
To complete this project, you should read or watch the following resources:
- [Sass Basics](https://sass-lang.com/guide)
- [Sass flow control directives: @if, @for, @each, and @while](https://sass-lang.com/documentation/at-rules/control)
- [Sass references](https://sass-lang.com/documentation)

## Learning Objectives
By the end of this project, you should be able to explain the following concepts clearly, without the help of Google:

### General
- What Sass means
- How to write Sass & Scss files
- The difference between Sass and Scss
- What Sass preprocessing is
- How to declare a variable in Sass
- How to use nested definitions
- How to import a Sass file
- How to use mixins
- How to declare and use extend/inheritance styles
- How to manipulate operators in Sass

## Requirements
### General
- Allowed editors: `vi`, `vim`, `emacs`
- All files will be executed on **Ubuntu 18.04 LTS** using **Sass 3.7.4** (or higher).
- All files should end with a new line.
- All Scss files should include a comment block at the beginning (example provided below).
- All files should start with a comment describing the task.
- A `README.md` file is mandatory at the root of the project folder.
- File lengths will be tested using `wc`.

### Example of Comment Block for Scss Files:
```scss
/* My style */
body {
    .container {
        color: #3D3D3D;
    }
}
```

## Installation
Follow the steps below to install Sass/Scss on Ubuntu 18.04 LTS:

1. Install Ruby 2.5 and its development tools:
   ```bash
   sudo apt-get install -y ruby2.5 ruby2.5-dev
   ```

2. Install additional development tools:
   ```bash
   sudo apt-get install ubuntu-dev-tools
   ```

3. Install Sass version 3.7.4:
   ```bash
   gem install sass -v 3.7.4
   ```

4. Verify the installation:
   ```bash
   sass --version
   ```

   The output should display:
   ```bash
   Ruby Sass 3.7.4
   ```

## More Information
- Always start your Scss files with a descriptive comment block.
- Use the provided resources to familiarize yourself with Sass concepts and directives.

Happy coding!
