---
layout: post
title: "Example Post"
date:   2020-05-09 14:24:13 -0600
categories: example

---

## creating a post

1. can create a new file and follow naming `YEAR-MONTH-DAY-title.markdown` where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers.
2. Copy existing post and adjust accordingly.

## post meta data

_Layout_
Will be post no matter use at this time

_Title_
Short and sweet is usually best, for release notes v major#.Feature#.patch#. For status update posts keep it the feature title, the home page uses title to filter and show what we expect.

*Date*
 `2020-05-09 14:24:13 -0600` format only

*Categories*

release-note, status-profile, status-autoemails, status-signup are current options. Considering each category is used for a different part of this site at the moment you will only use one. However, in the future if multiple are needed they need to be in an array.

*_*status*

not always used in the post, is used for feature status update indication. Available statuses are live, blocked, on-roadmap, in progress.


## content formatting

Most markdown syntax will apply for posts. The usuall will be

1. Headers the number of # will determine level of heading `#` is h1 `##` is h2 and so forth. For whatever reason this theme's h1 is smaller than h2.

2. Lists, for ordered aka numbered type the numeber then period and type whatever content. For unordered a single hyphen is needed -

3. text formatting `*bold*` *bold* `_italic_` _italic_ `*_bold and italic_*` *_bold and italic_* `~~strike through~~` ~~strike through.~~

4. blockquotes work like slack with > in front of the text.
   > blockquote example

5. task lists
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

6. horizontial rules `<hr>`
<hr>

7. Tables, are not pretty but doable. (copy ripped from markdown cheetsheet)
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

## Additional formatting worth noting.

1. [helpful markdown examples](https://www.markdownguide.org/extended-syntax/#definition-lists)
2. Jekyll is powerful for code snippets:
   {% highlight ruby %}
   def print_hi(name)
   puts "Hi, #{name}"
   end
   print_hi('Tom')
   #=> prints 'Hi, Tom' to STDOUT.
   {% endhighlight %}
