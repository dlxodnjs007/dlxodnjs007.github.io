---
layout: single
title: "jekyll-info"
---

```
---
layout: single <- 이거는 html파일이다.
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

