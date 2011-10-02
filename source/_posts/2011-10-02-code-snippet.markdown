---
layout: post
title: "Code Snippet"
date: 2011-10-02 12:32
comments: true
categories: 
---

TEST Code Snippeting
=====

{% img /images/post/lenaMOSAIC.jpg  %}
{% img /images/post/lenaMOSAIC.jpg  50 50 %}

{% gist 1177764 %}


{% codeblock %}
var test;
function () {
  console.log("Javascript")

  for(var i in arr) {
    if (!arr.hasOwnProperty(i)) {
      return;
    }
  }
}
{% endcodeblock %}



{% codeblock test lang:js %}
var test;
function () {
  console.log("Javascript")

  for(var i in arr) {
    if (!arr.hasOwnProperty(i)) {
      return;
    }
  }
}
{% endcodeblock %}

{% codeblock test.js %}
var test;
function () {
  console.log("Javascript")

  for(var i in arr) {
    if (!arr.hasOwnProperty(i)) {
      return;
    }
  }
}

{% endcodeblock %}


``` js Test 
var test;
function () {
  console.log("Javascript")

  for(var i in arr) {
    if (!arr.hasOwnProperty(i)) {
      return;
    }
  }
}
```


``` js Test 
var test;
function () {
  console.log("Javascript")

  for(var i in arr) {
    if (!arr.hasOwnProperty(i)) {
      return;
    }
  }
}
```



