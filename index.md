## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ashish60808/ashish60808.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ashish60808/ashish60808.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


# Problem Statement


## Exercises
### Generate 100 files
* Each file should contain a line with between 1 and 65 randomly chosen
  printable characters (both the number of the characters and the characters
  themselves are random)
* Line "This is every 5th file!" should appear in every 5th file
* Every 7th file ignores the previous two rules and contains the concatencated
  contents of all of the previous files.
* Write test-suite for your implementation.

### Write a Terraform code that
* Creates an EC2 instance with
  * The latest Ubuntu LTS AMI (AMI should be discovered dynamically, not hard-coded)
  * A Security Group enabling access only on 22, 80, 443 from 5.148.131.186/32
  * Uses SSH public key from path supplied as an variable (default value
    ~/.ssh/id_rsa.pub)
* Uses an S3 bucket as the Terraform backend (to store state)

### Write a Dockerfile for redis
* That uses the latest Ubuntu LTS Docker image as its base
* That accepts port configuration from an environment variable when the server
  is started
* That accepts memory limit configuration from an environment variable when the
  server is started
