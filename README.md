# nlpir_python_linux
python wrapper package of nlpir

基于[haobibo/ICTCLAS_Python_Wrapper](https://github.com/haobibo/ICTCLAS_Python_Wrapper) 
将其封装为一个package, 用于linux 64-bit

用法:
将 nlpir_python_linux 目录命名为nlpir放置于当前目录或者 site-packages 目录
通过from nlpir import nlpir来引用
```python
from nlpir import nlpir
p = "链接:http://www.iqiyi.com/l_rrfa4slf.html"
for t in Seg(p):
	print '{} {}'.format(t[0], t[1])
# 结果
链 ng
接 v
: wp
http://www.iqiyi.com/l_19rrfa4slf.html url
```