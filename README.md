Font-Adjuster
=============

Just a simple little jQuery script to automatically adjust text to be about 75 characters per line
by <a href='https://plus.google.com/104536213394512642005?rel=author'>Chris Walker</a><br/>

##How Does This Thing Work?
Well, it's pretty easy.
1. Download the file font-adjuster.js from here.
2. Include it in your theme somewhere.
3. Link to it somewhere in your theme.
4. Start using rem in CSS for all your text sizes.
5. Quit using Internet Explorer 8!

### Why is this here?
Well, to be honest I got tired of re-writing this code. So I decided to make it an external file. Why not? Then I can just link to it every time I have to remake a website.

#### Yeah, but what's the backstory?
Oh, that! Well, there was this article I read once stating that eyestrain on computers doesn't come from staring at the screen's bright lights, but from straining over tiny fonts all days. This website said that the best way to prevent eye strain was to use fonts like books. Publishers figured that the optimal line width was 45 to 75 characters. Well, it's pretty, but I hate wasting space so I configured it to 75 characters. It took a little poking around. It's more like 75-ish, but this is the script I eventually resolved on. It isn't perfect because not all characters are the same width. It's close though.

If you want larger text divide by a larger number. If you want smaller text divide by a smaller number in the third line. It's set to measure the body width. If you want to base it on something else like article width that's on line 2 in the quotes. Remember to include a hashtag when referencing an HTML element with an ID!

I wish I could remember where I first saw this, but I don't. It seems like the following link is where I saw where to use <a href='http://mikeyanderson.com/optimal_characters_per_line'>optimal characters per line</a> in a web page. I found it from <a href='http://dustn.tv/stunning-reading-experience/'>Dustin Stout</a>. Who's awesome by the way. I don't get half of what he says, but he's still worth following. 

##### License
Copyright (c) 2013 Chris Walker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

<img src='https://lh6.googleusercontent.com/-NoJxB98RGC8/UMDEznmPTiI/AAAAAAAAAcQ/cfDucT8eu4A/s800/squinty.jpg'>