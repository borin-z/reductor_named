���������!

1) �� Carbon Reductor
```yum -y install git m4```

!!!��������, ���� �� ��� ���������� ��� ��� load_ip.sh, �� ���������� ����� load_ip.sh ������� ��������� �������
�������� ���������� ���������� hooks �� ������ Carbon Reductor � /usr/local/Reductor/userinfo/hooks

2) �� ������e c BIND9
���������� named_client, �������� �� ������ � BIND9, ���� � ������� ������������ ��� FreeBSD, ������ �������� �� ����.
������ ���������� ������� client.sh �� crontab, ������� � ����� fakezone.crontab
��������!!! �� ������� ���������� ������������ ������ � ��������� �� ssh ��� ������.

3) �� ������� ��������� ������������� ��������������� ���.
� ������ named ������� (/usr/local/etc/namedb/named.conf) ���������:
```include "/usr/local/etc/namedb/reductor.conf";```
