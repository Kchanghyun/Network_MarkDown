# ��Ʈ��ũ ���� ����
1. TCP/IP ��
2. **OSI 7����** : 1984�� ��Ʈ��ũ ����� ü�������� �ٷ�� ISO���� ǥ������ ������ ��, �����͸� �ְ����� �� ������ ��ü�� �帧�� �� �������� ���� ���� ��

|����|�ܰ�|����|
|:--:|:--:|:--:|
|7����|����|**HTTP**, SMTP....|
|6����|ǥ��|SMB....|
|5����|����|NetBios|
|4����|����|**TCP, UDP**...|
|3����|��Ʈ��ũ|**IP, ICMP, ARP**...|
|2����|������ ��ũ|**�̴���**...|
|1����|����|����, ����, ������, ������...|

#### ������
1. ������ ��Ʈ��ũ ��
2. ���� �� ���� ����

#### ������
1. ������ �� ����
2. OSI�� ���� ���(����), TCP/IP�� �������� ���(�ǹ�)
3. OSI�� ��� ���ݿ� ���� ǥ��
4. TCP/IP�� ������ ���۱�� Ưȭ

## ��Ŷ
��Ʈ��ũ �󿡼� ���޵Ǵ� �����͸� ��Ī�ϴ� ���� ��Ʈ��ũ���� �����ϴ� �������� ����ȭ�� �����̴�. ��Ŷ�� ���� ������ ����� �����ͷ� �̷������ ����� �����ʹ� ���̷ε��� �Ѵ�.

|--|--|--|
|--|--|--|
|���|���̷ε�|ǲ��|
|--|--|--|

|--|--|--|--|
|--|--|--|--|
|Ethernet|IPv4|TCP|������|
|--|--|--|--|

#### ���� ��(ĸ��ȭ)
1. ���̷ε� : HTTP\
��� : TCP

2. ���̷ε� : TCP + HTTP\
��� : IPv4

3. ���̷ε� : IPv4 + TCP + HTTP\
��� : Ethernet

#### ���� ��(��ĸ��ȭ)
1. ���̷ε� : IPv4 + TCP + ������\
��� : Ethernet

2. ���̷ε� : TCP + ������\
��� : IPv4

3. ���̷ε� : ������\
��� : TCP

### PDU(���� �� �̸�)
4������ PDU(TCP + ������) = ���׸�Ʈ\
3������ PDU(IPv4 + TCP + ������) = ��Ŷ(���� ��Ŷ���� �ٸ� ��, �Ϲ������� ��Ŷ�̶� �ϸ� �� �溸�� ���� ���޵Ǵ� �����͸� ��Ī�ϴ� ����� ��Ŷ�� ������ ���ȴ�. )\
2������ PDU(Ethernet + IPv4 + TCP + ������) = ������