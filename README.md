nginx-bjtu
==========

Nginx modified for mirror.bjtu.edu.cn

There's only a patch based on nginx 1.2.5 currently. The patch mainly does 3 modifications:

1. add an optione `keepalive_autoclose`, and it will auto disable keep-alive when the request is for some specific file types (such as .iso, .gz).

2. a nicer directory listing look for mirror.bjtu.edu.cn.

3. some error page are directly put into source code.

