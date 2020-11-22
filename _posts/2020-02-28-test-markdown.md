---
layout: post
title: OSS실습 11주차 과제
subtitle: Quiz (2)를 대신하는 수행 과제 - 깃허브 페이지 작성 부문
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---


팀 별 진행사항 정리 (1점)

-6조 진행사항
  프로젝트 선정 - 뉴스 크롤러 https://github.com/lumyjuwon/KoreaNewsCrawler
  프로젝트 fork 및 팀 정적페이지 구성
  역할 분담 완료
 
 <공통>
1)코드 분석 및 버그찾기,수정이 필요한 내용 탐색 
2)수정 및 보완내용을 commit 및 issue활동

<그룹별 역할>

| 그룹 | 멤버 | 역할 | 
| 1 | 이찬구,박병규 | Readme에 내용 추가 및 번역작업 | 
| 2 | 원종원,임성용,최호준,임현서 |  정적 페이지 만들기 및 관리작업 | 


<개인별 역할>

| 이름 | 역할 | 
| 원종원 | 크롤링 카테고리 추가  | 
| 박병규 | 특정기간내 키워드 랭킹  | 
| 이찬구| 기사에 대한 좋아요와 싫어요 같은 반응까지 크롤링  | 
| 임성용 | 네이버 이외의 사이트에서도 크롤링 가능하도록 코드수정  | 
| 최호준 | 특정기간의 좋아요 싫어요에 따른 랭킹 | 
| 임현서 | 스포츠기사란 html 분석해서 커밋하는 역할 | 
 
 
 프로젝트 개선 아이디어 추가 제안
 ->특정기간내 기사의 좋아요와 싫어요 숫자에 따른 랭킹을 매기는 코드 추가하기
 ->현재 프로젝트의 이슈인 스포츠기사가 크롤링 되지 않는 문제에 대해 분석 및 개선하기
 

선정 프로젝트 분석 및 개선방향 (3점)
선정한 프로젝트를 구체적으로 파악하고, 개선방향을 명확히 제시
나의 개발 능력 및 역할분석 (2점)
본인의 개발 및 프로젝트 수행 능력을 상세하게 분석 및 기술
나의 개발 능력에 따른 개인별 기여 방안 및 계획 정리 (2점)
개발 능력에 따른 프로젝트 기여 방식 및 계획을 주어진 기간에 맞추어 수립.


##This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdownhttps://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:








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
