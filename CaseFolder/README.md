# Tutorial for an FSI simulation of an elastic flap perpendicular to a channel flow

******
オープンソースの preCICE/OpenFOAM/CaliculiX での流体構造連成シミュレーション
******

DEXCS2020アドバンス版の上で動作確認をしています。
DEXCS2020アドバンス版のダウンロードの情報は以下のサイトを見てください。
https://sites.google.com/view/dexcs-of

フラップ部はシェル要素を使っています。

これは下記の論文で提案された問題です。もとの論文は安定化有限要素法の研究論文でフラップ部にソリッド要素が使われています。


********
Fluid StructureInteraction Simulation with  preCICE/OpenFOAM/CaliculiX(Opensoure)
********

Operation has been confirmed with DEXCS2020 advanced version.
Please see the following site for information on downloading the DEXCS2020 Advanced version.
https://sites.google.com/view/dexcs-of

The flap part uses a shell element.

This is the problem proposed in the paper below,which is a research paper on the stabilized finite element method.The flap part uses a solid element.


===================

Fluid?Struktur?Interaktion mit stabilisierten Finiten Elementen(1999)
Autor(en): Wall, Wolfgang A.

p194-197 
7.5.3 Wirbelerregte flexible Struktur

https://elib.uni-stuttgart.de/handle/11682/144
