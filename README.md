# drafts
#include <iostream>
#include <string.h>

#define sz1 25


using namespace std;



int main()
{
 setlocale(LC_ALL, "Rus");

    string arr [sz1]={
    "������������ ��������� ��������������",
    "�������������� ��������� ������������",
    "���������� ��������� ��������������� ",
    "������������ ����� ��������������    ",
    "������������ ������� ������������    ",
    "�������� ��������� ��������������    ",
    "������������ ������ �������������    ",
    "����������� ������� �������������    ",
    "�������� ��������� ��������������    ",
    "����������� ������ ������������     ",
    "��������� ��������� ������������     ",
    "����������� ����� ��������������     ",
    "������������� ������ �����������     ",
    "��������� �������� �������������     ",
    "������� ��������� �������������      ",
    "������������ ������� ����������      ",
    "���������� ������ �������������      ",
    "����������� �������� ����������      ",
    "�������� ������� ������������        ",
    "�������� ������ �������������        ",
    "��������� ������ �����������         ",
    "���������� ������ ����������         ",
    "��������� �������� ���������         ",
    "����������� ����� ���������          "};

    for (int i=0;i<sz1;i++)
    {
        cout << "\t" << arr[i] << endl;
    }
    return 0;
}

