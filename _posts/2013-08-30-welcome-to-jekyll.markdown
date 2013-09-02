---
layout: post
title:  "Welcome to Jekyll!"
date:   2013-08-30 10:15:40 +0800
tags: me blog
categories: html5 webgl
---

You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

Jekyll also offers powerful support for code snippets:

<div class="high-light-area">
<pre class="brush: js">
/***********************************
 ** Multiline block comments
 **********************************/
 
$stringWithUrl = "http://alexgorbatchev.com";
$stringWithUrl = 'hello world';
 
ob_start("parseOutputBuffer");      // Start Code Buffering
session_start();
 
function parseOutputBuffer($buf) {
    global $portal_small_code, $portal_gzcompress;
    global $PHP_SELF, $HTTP_ACCEPT_ENCODING;
 
    // cleaning out the code.
    if($portal_small_code && !$portal_gzcompress) {
        $buf = str_replace("    ", "", $buf);
        $buf = str_replace("\n", "", $buf);
        $buf = str_replace(chr(13), "", $buf);
    }
}
</pre>
</div>
Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].
<div>page path:{{ page.path }}</div>
[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
