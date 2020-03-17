#  HIJACK-Proxy 劫持代理
本项目起源于2020年3月  
一个对代理了解甚少的人的想法  
实现原理是通过搭建一个DNS服务器  
访问example.com的时候，自动劫持example-reverse.com这个reverse proxy网站。而reverse proxy站点通常在TW、HK这几个地区  
自动优化大陆用户使用体验，因为通常情况下用普通方式查找可用的谷歌IP，会出现距离中国大陆距离较远的IP，导致访问体验下降  
在DNS服务器自动检测example-reverse.com是否被墙，如果无法访问自动切换劫持为可用的example-reverse.com站点例如example-reverse1.com  
