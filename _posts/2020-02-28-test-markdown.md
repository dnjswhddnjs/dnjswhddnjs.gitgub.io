---
layout: post
title: OSS실습 11주차 과제
subtitle: Each post also has a subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

##| Number | Next number | Previous number |
##| :------ |:--- | :--- |
##| Five | Six | Four |
##| Ten | Eleven | Nine |
##| Seven | Eight | Six |
##| Two | Three | One |

새로운 정적페이지 작성 및 개인화 (2점)
정적페이지를 과제 목적에 맞게 선정하고 개인화 하여 구성
팀 별 진행사항 정리 (1점)
선정 프로젝트 분석 및 개선방향 (3점)
선정한 프로젝트를 구체적으로 파악하고, 개선방향을 명확히 제시
나의 개발 능력 및 역할분석 (2점)
본인의 개발 및 프로젝트 수행 능력을 상세하게 분석 및 기술
나의 개발 능력에 따른 개인별 기여 방안 및 계획 정리 (2점)
개발 능력에 따른 프로젝트 기여 방식 및 계획을 주어진 기간에 맞추어 수립.





How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
