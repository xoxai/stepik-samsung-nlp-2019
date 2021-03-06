# 3. ������� ������������ ������ ������ � ��������
## 3.5. �������� ����������� ���������� ��� ����� NLP

��������� ����������� ��� ������� �������, ��������� ����������� �� �������� � ���������� ��������� �������� ���������� ��������� ������������ ������ � ������������ (���������), � ����� ��������� ��������.

����� ��������� ����� ��������� ������������� ��������� ����� �������, ���������� ��������. �������������� ������, ������� � �� ������ � ������� � ������� (������ ������, ���� ����� ���� � �������).

### ��������� ����� (Convolutional Neural Networks, CNNs)
* 1D ������
* ����������� � ��������
* ���������� ����������� �� ���, ������ �����������������
* !�� ������������ ����� ��� ���������� ������� ���������

### ������������ ���������
* ������ ������ �� �������� � ������������� ��������� 
* ������ ���������, ������� ��� ����� ����������� ��� ������� �������������������
* ��������� ������� ������� ��������
* !�� ����� ������

����� ����������� ��������� ��� pooling'�:

* ��� ��������� ������� ������ �����������, ����� (�����������) �����������.
* ��� ���������� ������� � �������� ������, �� ��������� �� ����� ������

�������� � ������� ���������� ����� ���������� **��������� ��������** (attention mechanism, self-attemntion) � ��������� �������� �������� �������� �������� ������������������. ����� ������������� ���� �������� ��� ����� (����������) ���������.

�����������, ������� �� ����� �������� ��������������� � �����, �� � ��� ������� �����:
* **����������� � �������** (memory Neural network, Neural Turing machine) �� ���� ������ ������, � ����� � ������������ ������, ������ ������ � ���� ����������. 
    * ��������� ��������� ������� ��������
    * ������������ (������������) ����� ���� ��������� ��� ������� ���������� ����� �����
    * !������ �� ����� ������ � ������ �������� �� ��������
    * !������� ������ ��������

* **����������� ���������** (tree-recursice NN). ������������ ��� ������ ������������ ��������. ������� ��� ������� �������������� �������� � ��������� ���������� ����� ������. ����� ��������� ��� ������� ������ �� ��������� �������� ����, �� � ��������� ����� ����������� �������.

* �������� ��������� ��������� (graph Convolutional NN gcnns). ��������� ��������� � ������������ ����� �� ������������ ��������� �����. ������������� �����������, ������� �����������. �� ������� ����� �������������� ���������.

## 3.6. ��������� ��������� ��� ��������� �������.

**������** � �������������� ��������, ����������� �� ���� ��� ����������� ��� ���������� ������� (������ � ����) � �� ������ �������� ������, ����� ������������� ������. ������������� ������� ��������� ������� �� ����. ��������� ��������� �� ������������������ ��������.

��������� �������� ���������� CNNs � ������� ��������� ������:
* ������ ������� ���������� ���� ��� �������� (����� �������� � ����������� ���������, � ����� ����� � ����� ������)
* ��-������� ���������� �������� � ��� ������� �������� �������� ������ �������� k ����� ����� �� ������� �������, ��� k � ������ ����
* ���������� ��������� ������ � ���� ������ �� k*s ��������� � ������� ��������� ������������ � �����. ���������� ��������� ������� � ������ ����� �������.
* ��������� � ����� ��������� �������� ���� � �.�.

������ ����� ������ ����������� ���������� � ������� ��������� � ���������. ������ ��� ��� ����, ����� ��������� ����� ����������, �� ���� �������� ����������� ������������ ����� ������� ��������. �������������� � ������ ������������ ����.

`(k-1)d+1=n` -- ������� ��� ���������� ������ ������������� ���� ��� ��������� ��������� ������� `d` � ����� ������ `k`.

��� �������, ��������� ��������� ������ ��������. ������ ����� ����������� (dilated convolutions), ��� ��������� ��������� ����� ���������� (����������� ����) ��� ���, ��� ����� ���������� ��������� ��� �� (��� ���������� �� ��� ������, ��� ��� ������������� ������ ������). ���� ��������� ������������ � ������ ���� ��, �� ��� ����� �������, ��� �� ���������� ��������� �� ���� (�� ��������� ������) � ������� ������� �����. ��� �� ��, ��� �� �����, ������� �� ������ ����� dilated convolutions �� �����������, � �� ����� �������� -- ��.

����������������� ������ -- ����� ������� ����� ���������� � ������������� �����������.