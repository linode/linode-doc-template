---
author:
    name: Linode Community
    email: docs@linode.com
description: 'One-sentence article descriptions'
keywords: 'list,of,keywords,and key phrases'
license: '[CC BY-ND 3.0](http://creativecommons.org/licenses/by-nd/3.0/us/)'
published: 'Weekday, Month 0th, 2015'
modified: Weekday, Month 0th, 2015
modified_by:
    name: Linode
title: 'Guide Title'
contributor:
    name: Your Name
    link: Github/Twitter Link
---

REMOVE THIS SECTION:
--------------------
Edit the following lines above:

description: 'Add a detailed description of what your guide accomplishes in one sentence.'
keywords: 'comma delimited list of keywords'
title: 'short title for your article'
name: 'Your name'
link: 'Only Github and Twitter links are supported'

Add the following lines to your header to link to external resources at the end of your guide:

external_resources:
 - '[Link Title 1](http://www.example.com)'
 - '[Link Title 2](http://www.example.net)'

 See https://www.linode.com/docs/style-guide for more details on guide formatting.
--------------------

Formatting examples

## Section Header

Each major section of your guide should be placed under a section header

###Sub-header Example

Subsets of each major section can be placed under a sub-header to improve guide navagation

1. Numbered list example 1.

2. Examples within a numbered list should be indented by 4 spaces, and terminal prompts should be removed from any commands removed.

3. Use unformatted text to display any terminal commands:

    ls -lah

Insert Notes and Cautions to highlight important information

{: .note}
>
> Place content that you wish to highlight or emphasize within a note.

{: .caution}
>
> Highlight warnings that could adversely affect a user's system with the Caution style.

Place contents of configuration files within File or File Excerpts.

{:.file }
/path/to/file.extension
: ~~~
  Enter full text of configuration file here
  Use this for files that need to be created from scratch
  ~~~


{:.file-excerpt }
/path/to/file.extension
: ~~~
  Enter relevant lines to edit here
  ...
  Separate sections that need to be edited within the same file with three periods
  ~~~

Links:

[Linking within Linode Docs](/docs/style-guide)

[Link to external resource](https://www.linode.com)

Images (Ensure that images are placed in the /docs/assets file path):

![description](/docs/assets/filename.png)

[![description](/docs/assets/filename_small.png)](/docs/assets/filename.png)
