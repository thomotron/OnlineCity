# OnlineCity
Mod OnlineCity for game RimWorld
Author Vasilii Ivanov aka Aant


# OnlineCity
OnlineCity ��� ��� ���� RimWorld
����� ������� ������ aka Aant

OnlineCity � ��� ������ ������� ���� ��� ���������� ��������� RimWorld. �� ��������� ���������� ������� ������ �� ����� ������� � ������ ������. ����� �����������, �� ������� ������� ���� ��������� � ������ ����������� ��� � ��� � ������� �����������. �� ������� ��������� �� ���������� �������, �� ����������� � ����������, �� ����� ������� �� ������� ��������� ���� ����� ������ ������������ ������, ��������� ���, �����������, ������ ��� ����� ������ ����, ������� ����������. ��� ����� ���������� ���� �� ���� �������� ���� ������� ������� � ��������� �� ���! 

���� ���� � ������� ��������� ���� � ��������, �� ������� ������� � �� ������ ������� ���������� � ����. �� ������ ������ ��������� ���� ���� ������ �������. �� �������� ����������� ������� �������, ����� ������������ ��� ����������� ���������� ����. �� ������ ������ ������ ������� �� ����� �������, �������������� � ���� � ���� � ������������ �������� � ���������� � ����������. � ���������� ������������! �� �� ���������� �� ������ ������� � �������� ������. 


# ������

����������� �������� ����: https://vk.com/rimworldonline
(��� �� ���� ������ ��� ���������� ������ ������)

������� � �������: https://discord.gg/5DzWrnR

����� emAnt@mail.ru

������� ���������� �� Trello: https://trello.com/b/gXtWtDjy/onlinecity-mod-rimworld

������� ������ ��� ���� � ������ 194.87.95.90 (��������� �� 09.2018) 


# �������

������� ������ RimWorld A18

����� ������ ������ ���������� ��� ��� ������ � ����� Mods. ��� ������ ����� ��������� ������������� ��� HugsLib. ����� ������� ����������� ����� ����� ���� � ����� ������������������:
Core
HugsLib
OnlineCity

��� ������ ���� ��������� ����������� �� ����� ������� ������. ������ ����� ����� �, ��������, �����-�� �������� ����� �������������� ��������, �� ������� �� ������ ������. �.�. �� ����� ������� ����� ������������ (�����������) ����� ������ ���� �������� � ���� �������.


������������� � �������� ���������� ������ 5 ������, ����������� ���������� � ��� � 15 ����� ��� ��� ������ �� ���� ����������� ����. 
�� ������������� ��������� ���� �������� �� �������! ��� ����� �������� � ������ ��������� ���� � ���������� ����������. 

������� �����: 

* ���� ������� ���� ������������� ������ �� ������������ � ���������. 

* ���� ����� � ��������� ������ ������� � �����. � ���� ����� �����������������, ������� ���� ������� � ����� �� ��� ������ ������� ����. 

* ��� �������� ������� ���������� ���������������� ���������. ��� ��������� ������� �� ������ �������������. ������� �������, ����� ������ ������� ����� �� ��� ����� �������. 

* ����� ������, ���������� �� ������ � ������� ��������, �������������� � ������������ ����� ������ ���������, ������������ ������ ����� ���, ����� �� �������� ������� "����" ��� "trad".

* � ����� ���� ����� �������� �� ����� ��������, ������� ��������� ������. ��� �� ����� ������� ��������� ����� ��� ������� � ����� ������� �����. 

* �� ������ ����� ������ ���� �� �������� ������ ���������� ���������� ������ � �������� ���, �������� ���������� ������ ����, ���� �������� ����� ���������� �� ������ �� �����. 


# ������ � ����������

���������� ������������ �� ����� OnlineCity � ������� ����� Mods.

�������:
* Chat - ������� ����� ������� ����� ������������ � �������� � ����� ����
* Converter - ������� ��� �������� ����� ������������ ���� �� ����� ����� ������
* RimWorldOnlineCity - ���������� ���� ������������� � ����
* ServerConsole - �������� ������� �������
* ServerDll - ������, ��������� ��������� ���� � ������ ������� (�� �������)
* UnionDll - �������� ������ � ��������� ���, ������� ������������ � �������� � ��������

������ ������� ServerConsole ��������������� � ����������� ����� RimWorldOnlineCityServerOut 
���� ���������� ���� RimWorldOnlineCity � ����� Assemblies ���, ��� ����� ���������� ����� ����� ����������� � ����.


������ ���������� ����� �:
* StartPoint.cs - ����� ����� ������� ������ ����. ������ ��� ��� ������ ������� ��������� ������ �� ������ ������ � ����. � ����� �� (� ������������) ���� ������ �������������. �������� ������������� ���������� ����� ����� � ���� (����� ������ ��� �����������).
* SessionClientController.cs - ��� ���������� Init (������� ����������� �� StartPoint), � InitConnected (������ ������ ��� ����� ����� ����� �������� � ����������� �� �������). � ����� ��� ������� � ������ ����������.
* Dialog_MainOnlineCity.cs - �������� ����� ����, ������� ����������� �� ������ �� ������ ������ � ����. ������, ��������, ��� ������ ����� ���������� ������ ����������� � ������� � ������ ���� �������� � �������������.


## ����� ������ ������.



### ������ ������ (��� ��� ��� ��������)

������.

* ������ ������ ���������� �� ����� Dialog_LoginForm, ���� Dialog_Registration.
* ��� �������� ������� SessionClientController Login � Registration ��������������.
* ��� �������� �������� ����������� �������� SessionClientController.Connect.
* ��� �� �������� Connect �� ������ SessionClient (�� ���������� ��� ��������).
* ����� ���������� ��������� (���� ���� �� ������ ��������� �������):
*  �������� ������� ������ ����� � ���� ���� 0x00
*  � ����� ��� �������� ������������ ���� �� ������, ������� �� ����� ��������� � �������������� ������
* ���������������� ����� ������������ ConnectClient � ����� ����������� ���� �� ������� ConnectServer.

���� ���������� ����� ���������� ����� ������� TransObject<>
* � TransObject<> ������������ ��������� ������ � ����������� ������ ��������� ModelContainer � �������� ������� ������� Trans.
* � Trans �� ����������� ������ � ����� � ������� (GZip.ZipObjByte), ������� (CryptoProvider.SymmetricEncrypt) � ���������� �� ������.
* �������� ��������� �� ������� ��������������, ��������� � ������������� � ����� �� ����������� ������ ��������� ModelContainer.
� ���, �����, ����� ���� �������� ��������� �� ������.

������.

��� ������������ ����������� ��������� ������� ServerManader.ConnectionAccepted � ������� ����������� ��������� ���� � ����������� ���������� DoClient, ������� ��������� ������� ������ �� ������� � ���� ������ SessionServer � ��������� � ��� ����� Do.

� ���� ������ �� ���������� ������� ����� � ��������� ������ ���������� ���������� � ������� ����, ����� ���� ���������� ����� "��������������" ������� Service. ��������� ������ ���� ��� ������.

### ������ - ����� (��� ��� ������������)

������.

��� ���� ����� �������� ��������� ���� ������� � SessionClient.

� ��� ���������� ��������� ������������ ���������� � ������ � ����������� TransObject<> ��� �������� �� ������ � ������ ������ �� ����. � TransObject<> ������ ������ ���������� ����� ������ ���������� ������ � ���� ������-�������� (������ �������� - ������, � ����� ��� +1 �� ����).

������.

* �������� ������ � ���� ������������ ���������� ModelContainer ���������������� �������� SessionServer.Service.
* ����� �� ������ ���� ������� ���������� �������������� ������� � ������ Service.
����� �������, ��� ����� Service ��� ������ SessionClient ��� ������� (� ��� ������, ��� � SessionClient �� �������� �������, � ������ ������������ � � ���������� ��������� � ������ Service)

��� ���������� ������ ����������� �� ������� �������������� ��������� ������� � ������ SessionClient � Service, � ������ � ������ ������ ������ ������� SessionServer.Service.



## �������������� � �����


### �����������

� �������� ������� ������ ��������� � ������ SessionClientController � ClientData Data.

* ������ ������ ���� ���������� �� ����� Dialog_LoginForm, ���� Dialog_Registration.
* ��� �������� ������� SessionClientController Login � Registration ��������������, � ������� ���������� ����������� � �������.
* ����� ��������� ����������� ����������� InitConnected:

���� ��� �� ������� �� ������, � ����� �����, �� ���������� ������ �������� ���� Dialog_CreateWorld. �� ��� ���������� ����������� �������� ���� GameStarter.GameGeneration, ����� ��������� �������� ����������� CreatingWorld. ��� ���� ������������ ���� (���� �����������) � ���������� ��� ������ �� ������ connect.CreateWorld(toServ) ����� ���� ������������ ���������� � ������� ����.

���� � ������ ��� ����� �� �������, �� ������� �������, ��������� ���� ��������� ������ ������� � �������� ��������� ������������ ��� ������ ���� ������� �, �����, ����������� �������� ������ ���������� � ������. �� ��������� ������� ������������ ������� ���� �������� � ������������ ������� GameStarter.AfterStart = CreatePlayerMap; (����������� ������� CreatePlayerMap). � ���� ������� ���������� ������ ���������� ���� � ������� � InitGame (�� ����).

���� ���� �� ������� ����, �� ��������� ��� � �� ������� GameLoades.AfterLoad ��������� ����� � InitGame

* ���� ������������ ������ ��� ������ ����, ��� �������� �, �� � ������ ���������� ����� �������� ������� InitGame.
� ��� �����������:

* ������������� ���� � UpdateWorldController.ClearWorld() (���� ������ �������� ��� ����� �������� (��������� ������� ������� � �� �������� ����������� �� CaravanOnline)) 
* ���������� ��������� UpdateWorldController.InitGame(); ������� ����� ���������������� ������� � ��������
* ������ ������� ���������� ��� UpdateWorld(true); ������ ���������� ���, ��� �� ������ �������� ������, ����� ���������� ��� ����� ��������� (������� ��� ���� �� �������) serverId ��� ���������� �����. ����� ��� �������� ����� �� �� ������ ��� ����������, ��� � ��� ����� ��������� � ��������.
* ������ ��� ����������� ������� �� ������� (�� ����)
* ��������� ������� ������������ ��� ������ �� ���� ����� ��������. � �� ���������� ������������ ���������� ���� �� ������ � ����������.

### ����������� ������� �� ����� ���� �� �������

* ������ ��� ���. ���������� ������ ���� UpdateChats()
�������� ������ � ������� dc = connect.UpdateChat(Data.ChatsTime);

����� �������� ���� � ����� �������� �������. � ����� ������ ������ ��� ��������� �� ����������� ������� �� �������� �������. ����� ������� ����� ������� ��������� �� ���������� �������.

����� ��������� ������� ���������� ������� ������ ���� ����, ��� ������ � ������� � Data.ApplyChats(dc);

������ ����� � ���� ����������� ����� ���������� ������� �������. � ���� ������ �� ��� ���, �� �� �������� � ClientData � �������� bool ServerConnected ��������� �� ����������� (�� ���� ������� ����� 8 ������)


* ������ ��������� ������ ������������� ���� UpdateWorld(false)
C������� ������ � ������� UpdateWorldController.SendToServer (�� ����������� ������ ���)

��������� ���������� �� �������, ����� ���������� � ������

��������� ������� UpdateWorldController.LoadFromServer


* ������ 15 ����� ���������� � �������� ����� �� ������ BackgroundSaveGame()
��������� �������� ������� ���������� SaveGame, � ��������� ��������� � ����������, ������� �������� �� ������ ��������� ������ ������������ ����




