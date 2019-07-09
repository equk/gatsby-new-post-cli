# gatsby-new-post-cli

CLI script for creating markdown posts using core nodejs features.

No extra dependencies required.

More detailed information can be found on my blog article: [Gatsby New Post CLI Script](https://equk.co.uk/2019/07/06/gatsby-new-post-cli-script)

**License:** MIT

# Requirements

- NodeJS

# Usage

Place the script into the base directory your gatsby project.

Check your posts folder is configured correctly (change `blogPostFolder` if required)

Execute script & fill out the Post Title

```bash
$ ./newpost.js
Post Title:
```

The script should create a markdown file with frontmatter filled out.

```bash
$ ./newpost.js
Post Title:test
Post test was created successfully
Location: ./content/posts/2019-07-09-test.md
```

# Contact

Website: https://equk.co.uk

Twitter: [@equilibriumuk](https://twitter.com/equilibriumuk)