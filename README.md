# SntpClient
���������� ���������� ��� �������� ����������� �����.

*��������� ������������� Python ������ �� ����, ��� 3.6*

## ���������
��������� ����� �� �������� � ������������ ��������.

## ������ ������
����� ��������� � ����� test_smtp.py. 
������ ������� ������ (�� Windows10):
`C:\SmtpClient>python test_smtp.py`

## ��������� ������� (�����) ����������
* --help [-h] 				- ������� �� ������������� ���������.


* sender_email				- ������������ ����������� ���������� �������� ����� ����������� ����� �����������.
							
* --server-port [-s]		- ������������ ������������ ���������� �������� ����� SMTP-������� �, 
							��� ������������� ����� �������������� ����� ��� SSL-������������ ����� 
							(�� ��������� ���� ����� 465).<br />
							�������: `-s smtp.gmail.com:999`��� `-s smtp.gmail.com`
							
* --mail-topic [-t]			- �������������� ������������ ���������� �������� ���� ������.

* --zip [-z]				- �������������� ����������� ����-���������� ����������� `--zip`, � ��� ������, ���� �� ������
							�������� ����� �������.
							
* --debug [-d]				- �������������� ������������ ����-���������� ����������� `--debug`, � ��� ������, ���� �� ������
							������ ������� �������������� ������� � ��������.
							
* --attach					- �������������� ������������ ���������� ����������� ������ ���� �� �����, ������� �� ������
							���������� � ���������. � ������� ���������� ������� ����� ������� ���, � ������� ���� ����� 
							���������: `--attach filename.txt [[new filename.txt]]`
							
* --attaches				- �������������� ������������ ���������� ����������� ������ � ������ �� ������, ������� 
							�� ������ ���������� (���� �� ������ ��������� ��������):<br />
							`--attaches  filename1.txt filename2.txt filename3.txt`
							
* --open-sending [-o]		- �������������� ����������� ����-���������� ����������� `--open-sending`, � ��� ������, ���� ���������,
							����� ������ ���������� ����� ������ ����������� ������� ������.<br />
							�� ��������� ���������� �� ����� ����-�����.

* --max-size				- �������������� ������������ ����������� ����� ����� - ������������ ������ �������� ������.<br />
							� ������, ���� ���� ��������� ������, ����� �������� ������� ������ `--max-size`,
							�� �� ����������� �� ������ ������������� �������, ����� ����� ���������� ����������� 
							�����������. ���� ���� ����, ������ �������� ������ `--max-size`, ���� ����� ������ �� 
							����� ��������������� ������� � ��������� �� ������.<br />
							`--max-size` ����������� � ����������.
							
* --mail-to [-m]			- ������������ ������������ ���������� ����������� ������, ���������� �������� ������ ������������
							���������: `--mail-to receiver.first@gmail.com receiver.second@gmail.com`<br />
							... ��� ������ ���� �� �����, � ������ ������ ������ �������� ���������� ���� �������� ����� ����������:<br />
							`--mail-to @filename.txt`

## �������������
(�� Windows10)<br />
��������� ����������� � ��������� ������ � ������������� ����������� `sender_email`, `--server-port` � `--mail-to`:<br />
`C:\SmtpClient>python main.py sender@yandex.ru -s smtp.yandex.ru -m receiver@yandex.ru`<br />
�����, ������������ ����� ���������� ������ ������ ��� ��������� ����� �����������. ���� ����� ��� ������ ����������� ���� ������� �������, ������������ ����� ���� 3 ������� �� ��������� ��������������.__
����� ����� ������ ������������ � ��������� �� ������ ������ ����� ������.<br />
����� ���������� �������� ������.

## ���� ���������� ���������
* ��� ������ "0"  - ����� ��������� � ����� � �������� ����������� ������ ���������.

* ��� ������ "1"  - ����� ��������� � ����� � ���, ��� ������������ �� ��� �� ������ ������ ����������.

* ��� ������ "2"  - ����� ��������� � ����� � �������� �������� ����� ������ ����������.
					������ ������� ������� ����� ������ � �������: `receiver@yandex.ru`

* ��� ������ "3"  - ����� ��������� � ����� � �������� �������� ����� ������ SMTP �������.

* ��� ������ "4"  - ����� ��������� � ����� � �������� �������� ����� ����� SMTP �������.

* ��� ������ "5"  - ����� ��������� � ����� � ���, ��� �� ������� ����� ���� �� ���������� ����.

* ��� ������ "6"  - ����� ��������� � ����� � ������ �������� ��������� �������.

* ��� ������ "7"  - ����� ��������� � ����� � �������� �������.

* ��� ������ "8"  - ����� ��������� � ����� � �������������� �������������� ������ ����, ��� 3.6

## �����
Russia, Ural Federal University, Chernuschenko Denis Yurievich, November 2017.

## ��������
E-mail   : Denis1.618@yandex.ru