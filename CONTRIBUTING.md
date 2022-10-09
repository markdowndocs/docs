# Contributing guidelines for docs
This contains the contributing guidelines for the documentation.

## GitHub pull requests | Contributing to docs code
GitHub pull requests is a great way to contribute. Here's how you use them.

### Proposing changes
1. Fork this repository. <https://github.com/markdowndocs/docs/fork>
2. Go to the `\published` folder. This contains the docs.
3. **If you are using web editor** Enable sign-off on your fork. We use sign-off on commits so that we know that you are legally allowed to contribute.
4. Go to the doc you want to contribute to.
5. Click the "Edit" icon at the upper left corner.
6. Propose your changes.
7. Add a commit message.
8. Commit.

Some notes:

- **Don't use the Git terminal.** We like using the "Edit" button instead on GitHub. We will ask you if you did your commit using the Git terminal. If you say no, we will close your PR.
- **Major changes should be discussed on an issue first.** In our opinion, we like to use issues to discuss major changes.


## Website Important Text block for new pages
New pages should **ALWAYS** contain this text block.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Home | MarkdownDocs | Documentation</title>
        <link rel="stylesheet" href="./assets/globalstyle.hKgZHsNy1o.css">
    </head>
    <body>
        <div class="navbar">
            <h2>MarkdownDocs Docs</h2>
            <a href="#">Home</a>
        </div>
    </body>
</html>
```

Optional ones are hosted on [this unpublished file](./unpublished/text-blocks.md).
