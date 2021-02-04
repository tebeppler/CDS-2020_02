# CDS-2020_02
Requisito parcial para disciplina de período especial.

Dataset:

------ Malware static and dynamic features VxHeaven and Virus Total Data Set ------
https://archive.ics.uci.edu/ml/datasets/Malware+static+and+dynamic+features+VxHeaven+and+Virus+Total#
3 datasets: 
- staDynBenignLab.csv,        features extracted from 595 files (Win 7 and 8); (1086 features from 595 files on Win 7 and 8, obtained Program Files directory). 
- staDynVxHeaven2698Lab.csv,  from 2698 files of VxHeaven and                  (1087 features extracted from 2698 files of VxHeaven dataset)
- staDynVt2955Lab.csv,        from 2955 files of Virus Total.                  (1087 features extracted from 2955 provided by Virus Total in 2018)
	
Data Set Characteristics:  
	Multivariate
Number of Instances:
  2955
Area:
  Computer
Attribute Characteristics:
  Integer, Real
Number of Attributes:
  1087
Date Donated
  2019-01-31
Associated Tasks:
  Classification
Missing Values?
  N/A
Number of Web Hits:
  2129
Source:
  Alberto Redondo Hernandez, alberto.redondo '@' icmat.es
Attribute Information:
  Static features: ASM, Hex dump and PE Header (discreate, continuous)
  Dynamic features: extracted from a Cuckoo sandbox 
  
  
  ------ Investigation of the Android Malware (CIC-InvesAndMal2019) ------
https://www.unb.ca/cic/datasets/invesandmal2019.html
426 malware and 5,065 benign
4 classes:

    Adware
    Ransomware
    Scareware
    SMS Malware

42 famílias
  Adware
    Dowgin family, 10 captured samples
    Ewind family, 10 captured samples
    Feiwo family, 15 captured samples
    Gooligan family, 14 captured samples
    Kemoge family, 11 captured samples
    koodous family, 10 captured samples
    Mobidash family, 10 captured samples
    Selfmite family, 4 captured samples
    Shuanet family, 10 captured samples
    Youmi family, 10 captured samples
  Ransomware
    Charger family, 10 captured samples
    Jisut family, 10 captured samples
    Koler family, 10 captured samples
    LockerPin family, 10 captured samples
    Simplocker family, 10 captured samples
    Pletor family, 10 captured samples
    PornDroid family, 10 captured samples
    RansomBO family, 10 captured samples
    Svpeng family, 11 captured samples
    WannaLocker family, 10 captured samples
  Scareware
    AndroidDefender 17 captured samples
    AndroidSpy.277 family, 6 captured samples
    AV for Android family, 10 captured samples
    AVpass family, 10 captured samples
    FakeApp family, 10 captured samples
    FakeApp.AL family, 11 captured samples
    FakeAV family, 10 captured samples
    FakeJobOffer family, 9 captured samples
    FakeTaoBao family, 9 captured samples
    Penetho family, 10 captured samples
    VirusShield family, 10 captured samples
  SMS Malware
    BeanBot family, 9 captured samples
    Biige family, 11 captured samples
    FakeInst family, 10 captured samples
    FakeMart family, 10 captured samples
    FakeNotify family, 10 captured samples
    Jifake family, 10 captured samples
    Mazarbot family, 9 captured samples
    Nandrobox family, 11 captured samples
    Plankton family, 10 captured samples
    SMSsniffer family, 9 captured samples
    Zsone family, 10 captured samples

 Source:
  Laya Taheri, Andi Fitriah Abdulkadir, Arash Habibi Lashkari; Extensible Android Malware Detection and Family Classification Using Network-Flows and API-Calls, The IEEE (53rd) International Carnahan Conference on Security Technology, India, 2019
