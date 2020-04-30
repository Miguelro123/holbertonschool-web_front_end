# 0x03. Sass & Scss

## Learning Objectives

- What Sass means
- How to write Sass & Scss file
- What is the difference between Sass and Scss
- What is the Sass preprocessing
- How to declare a variable
- How to use nested definition
- How to import a Sass file
- How to use mixins
- How to declare extend/inheritance styles
- How to manipulate operators

## More Info

### Comments for your Scss file:

All your Scss file must start with a comment block

```
$ cat my_styles.scss
/* My style */
body {
    .container {
        color: #3D3D3D;
    }
}
$
```
## Install Sass/Scss on Ubuntu 18.04 LTS

```
$ apt-get install -y ruby2.5 ruby2.5-dev
$ gem install sass -v 3.7.4
$ sass --version
Ruby Sass 3.7.4
```

## Tasks

<details>
<summary>View Contents</summary>

### [0. Always debugging!](./0-debug_log.scss)
*Write a Sass file that prints Hello world in the debug output.

```
guillaume@ubuntu:~/$ sass 0-debug_log.scss | head -n 0
0-debug_log.scss:2 DEBUG: Hello world
guillaume@ubuntu:~/$ 
```

</details>

## Author

- **Migue** - [Miguelro123](https://github.com/Miguelro123)
