## Nodis

  Nodis - Prefix match search and Segment words search built on Node.js and Redis.
  
  ʹ����zookeeper��thrift, �ͻ��˿����κ�֧��thrift������ʵ��, Ҳ���Ժ����׵�ȥ����������.

  
### ʹ��

 - ����redis
 - ���������node NodisServer.js(��ע��zookeeper����)
 - ����thrift/nodis.thrift�ṩ�Ľӿ�ʵ�ֿͻ���(��ֱ����/thrift/gen-nodejs�����ɵĿͻ��˴���)
 - ͨ��zookeeper�õ������ַ����ͨ��thrift�ͻ��˵��ýӿڲ���
 
### ����

 - zookeeper�Ĵ�����Ժ����׵��Ƴ�, ������/lib/zk.js
 - ���Ŀ�ֻ��nodis.js, ��ʹ��thriftֻ��Ҫ����/NodisServer.js
 - ǰ׺ƥ������(��User), �ṩ��app.js�����ο�ʵ��