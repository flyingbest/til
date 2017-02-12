# GitHub Flavored Markdown Language Syntax

## How to link to part of the same document in Markdown?

GitHub automatically parses anchor tags out of your headers. follow this code:

```markdown
[Foo](#foo)

# Foo
```

In the above case, the Foo header has generated an anchor tag with the name foo.

Just one # for all heading sizes, no space between # and anchor name, anchor tag names must be lowercase, and delimited by dashes if multi-word. Look at this code:

```markdown
[click on this link](#my-multi-word-header-include-this)

### My Multi Word Header (include this)
```

