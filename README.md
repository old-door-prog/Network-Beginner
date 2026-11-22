# BGP-Network
#AS1
<img width="1288" height="642" alt="スクリーンショット 2026-11-22 111048" src="https://github.com/user-attachments/assets/8792c5a0-af4a-4d4f-8ef0-6938056c8f36" />

##Area0
・L3Switch12
  Area0のABR、L3Switch13とL3リンクアグリゲーション、Area3のRouter20とVirtual-link
・L3Switch13
　Area0のABR、L3Switch12とL3リンクアグリゲーション、Area3のRouter20とVirtual-link
 ・Router19
  AS1のASBR
##Area1
・L3Switch15
　L3Switch14とHSRP、VLAN10のActiveRouter、L3Switch14とL2リンクアグリゲーション、Switch19,20とトランクポート、VLAN側にpassive-interface
・L3Switch14
　L3Switch15とHSRP、VLAN20のActiveRouter、L3Switch15とL2リンクアグリゲーション、Switch19,20とトランクポート、VLAN側にpassive-interface
 ・Switch19,20
  L3Switch15,14とトランクポート、Switch19はPCとアクセスポート、Switch20はPCとアクセスポート
##Area2
  Area2はTottaly Stub Areaであり、内部ルーターに対してデフォルトルートしか通さない
・Router17
  Area2のABR、
・Router21
　Area2の内部ルーター、PCに対してpassive-interface
##Area3
・Router20
　L3Switch12,13とVirtual-link、Area3のABR
・Router18
　Area3の内部ルーター、PCに対してpassive-interface
#AS2
<img width="1277" height="638" alt="スクリーンショット 2026-11-22 112350" src="https://github.com/user-attachments/assets/40cdd2da-c610-413e-9fbc-b0502fd00f19" />

