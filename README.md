����ӵ�����Ƽ��� Tcp_bbr (�ڴ����Ը�лԭ���ߵȿ����ߴ�����)
��΢�º͵��ħ�� by ������
ħ��Դ�� tcp_nanqinlang.c
ħ��ģ�� tcp_nanqinlang.ko
ģ��ͽű����� Debian Kernel Version v4.11.0

tcp_nanqinlang.sh һ���ű� 1.0beta

�÷�:

wget https://raw.githubusercontent.com/sinderyminami/tcp_nanqinlang/master/tcp_nanqinlang.sh && bash tcp_nanqinlang.sh ${command}

command: { install | start | stop | status }

1.��װ�ں� bash tcp_nanqinlang.sh install
2.�����㷨 bash tcp_nanqinlang.sh start
3.����״̬ bash tcp_nanqinlang.sh status
4.ͣ���㷨 bash tcp_nanqinlang.sh stop

˵��:
���� install ������ �ᴴ�� /root/tcp_nanqinlang ������ �����ں˰�: image / headers.amd64��i386 / headers.all
���� install ������ sysctl.conf�Ḳ��Ϊ���ڽű���Ԥ�õ� /etc/sysctl.conf
���� start   ������ �Ὣ tcp_nanqinlang.ko �ŵ� /root/tcp_nanqinlang �����ظ�ģ��, ����ʹ�� status �����ж��Ƿ�ɹ�����
���� �ű�    ��     ��������־�ļ� /root/tcp_nanqinlang.log