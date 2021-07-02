---
layout: single
title: "jekyll 사용법 - github pages와 함께"
---

jekyll이란? [jekyll 공식 사이트](https://jekyllrb.com/)

jekyll은 ruby언어로 쓰인 ruby gem의 일종이며,  
정적 사이트 생성기(static site generator)이다.  


github에 push를 해가면서 수정할 수 있다.  
근데 push를 하고 나서 수정된 사항이 반영되는 시간이  
좀 길어서 ruby를 설치하자.&nbsp;[ruby 공식 사이트](https://www.ruby-lang.org/en/)<br/>
start command prompt with ruby를 이용하면 로컬서버로  
수정하고 저장하고 rendering하는 시간이 줄어든다.
run하려면 start command prompt with ruby를 켜고   
```
bundle exec jekyll serve 
```
를 입력하면 된다.  
<hr style="border:3px solid gray">
```
---
layout: single <- 이거는 single.html이다.
title: "제목"
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

<hr style="border:3px solid gray">

<https://jekyllrb.com/docs/variables/>  
-> 여기에서 site, page, layout, content, paginator라는 variables가 liquid와 함께 사용된다.

