这个flask的测试文件，实现的功能是一个上传的功能，简单的测试下上传文件会不会因为网络因素造成影响。
安装flask
运行在Python2.7，
 pip install werkzeug flask
 安装之后，就可以将此仓库中全部clone到本地，运行，即可访问。


 在app.py文件中，可以通过修改“app.run("0.0.0.0",80,debug=True)”这个地方的ip+port，允许外网访问，默认只是127.0.0.1访问。
