
[![Build status](https://ci.appveyor.com/api/projects/status/bpx32xvwubh2dm72?svg=true)](https://ci.appveyor.com/project/sanjusss/besttrace)
[![](https://img.shields.io/docker/stars/sanjusss/besttrace.svg?logo=docker)](https://hub.docker.com/r/sanjusss/besttrace)
[![GitHub license](https://img.shields.io/github/license/sanjusss/besttrace.svg)](https://github.com/sanjusss/besttrace/blob/master/LICENSE)  
[![GitHub tag](https://img.shields.io/github/tag/sanjusss/besttrace.svg)](https://github.com/sanjusss/besttrace/tags)
[![GitHub issues](https://img.shields.io/github/issues/sanjusss/besttrace.svg)](https://github.com/sanjusss/besttrace/issues)

# besttrace

���� traceroute ���󣬸�����·���ӻ��������Ը��ã�֧�� JSON ��ʽ�����  
[�ٷ���վ](https://www.ipip.net/product/client.html#besttrace)

## ʹ�÷���

##### �鿴����
```bash
docker run -it --rm sanjusss/besttrace -h
```

##### ��ѯ��baidu.com����·
```bash
docker run -it --rm sanjusss/besttrace baidu.com
```

##### ������ʾ��baidu.com����·
```bash
docker run -it --rm sanjusss/besttrace baidu.com -g cn
```

##### ��ѯ��google.com��IPv6��·
```bash
docker run -it --rm sanjusss/besttrace google.com -6
```