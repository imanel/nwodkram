work in progress ...

# Nwodkram #

nwodkram (markdown in reverse) is a tool to reverse html into markdown.

## Usage ##

nwodkram = Nwodkram.new(string)
markdown = nwodkram.to_markdown

## Use case ##

My use case was to migrate a blog from wordpress.com to something more civilised (and self-hosted).

## Supports ##

*tags*:
p, a, img, ul, ol, li, h1, h2, h3, em, strong
*rubies*:
tested with MRI ruby 1.8.7 and 1.9.2 (preview1)

## TODO ##

The tool doesn't support the [full markdown syntax](http://daringfireball.net/projects/markdown/syntax).

If this tool gets used, I could extend it.  For now, it's suffient for my limited purposes.