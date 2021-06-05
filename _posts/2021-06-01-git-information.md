---
layout: single
title: "git에 대한 정보"
---

<https://github.com/topics/jekyll-theme>  
-> 여러가지 theme이 있다.

<https://www.youtube.com/watch?v=ACzFIAOsfpM>  
-> 처음 github pages를 만들 때, 참고한 영상이다.

line break를 하려면 

``` 
Hello <- two spaces
World
```
Hello  
World  

<hr style="border:3px solid gray"> <!-- html 태그를 써도 되나보다...-->

```
Hello <- without two spaces
World
```
Hello World

<hr style="border:3px solid gray">

```
<br/>
```

을 사용해도 된다.

<hr style="border:3px solid gray">

```
Hello

World
```

Hello  
World

<hr style="border:3px solid gray">

```
---
layout: post
title: Blogging Like a Hacker
---
```
<div>
md파일에서 맨 위에 쓰는 이것은 YAML front matter block이라고 한다.
Jekyll에 의해서 특별한 파일로 처리가 된다. 
이 front matter는 파일의 맨 처음 부분에 써야 하고, 
triple-dashed line 사이에 YAML 형태로 써야 한다. 
title처럼 내가 변수를 만들어 놓으면 layout.html에서 정의해 놓은 대로
title을 liquid를 통해 사용 가능하다.
(<a href="https://jekyllrb.com/docs/front-matter"> https://jekyllrb.com/docs/front-matter</a>참고)
</div>
