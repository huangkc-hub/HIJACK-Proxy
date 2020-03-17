#  HIJACK-Proxy 劫持代理
本项目起源于2020年3月  
来自对代理知之甚少的人  
实现原理是通过搭建一个DNS服务器  
访问example.com的时候，自动劫持example-reverse.com这个reverse proxy网站。
而reverse proxy站点通常在TW、HK  
因为通常情况下查找谷歌IP，会出现距离中国大陆距离较远的IP，导致体验下降  
在DNS服务器自动检测example-reverse.com是否被墙，如果无法访问自动切换劫持为可用的example-reverse.com站点例如example-reverse1.com  
如果DNS被墙，可以在Github项目主页查看。这里会公布最新的HIJAC-Proxy DNS  

