デバッグ・ユーティリティの利用方法
======================================

デバッグ・ユーティリティは、以下の方法で利用可能です。

クライアントでSSH公開鍵を作成
--------------------------------------

クライアント端末で、SSH公開鍵を作成します。(~/.ssh/id_rsa_pub)


BIG-IP Central Managerでデバッグ・セッションを設定
--------------------------------------

My instancesから、デバッグ・セッションを行うBIG-IP Nextインスタンスを選択します。

.. figure:: images/c14-m1-4.png
   :scale: 40%
   :align: center


“Debug”を選択し、“Proceed”をクリックします。

.. figure:: images/c14-m1-5.png
   :scale: 50%
   :align: center


クライアント端末で作成したSSH公開鍵をコピーして、"Start Debug Session"をクリックします。

.. figure:: images/c14-m1-6.png
   :scale: 50%
   :align: center


Central Manager GUIで表示されたSSHコマンドを、ターミナルソフトで実行します。

.. figure:: images/c14-m1-7.png
   :scale: 50%
   :align: center


NextインスタンスにSSH接続できることを確認します。

.. figure:: images/c14-m1-8.png
   :scale: 50%
   :align: center


デバッグ・セッションの終了
--------------------------------------

Central Manager GUIで、"Stop Debug Session"をクリックします。

.. figure:: images/c14-m1-9.png
   :scale: 35%
   :align: center


ターミナルのセッションが終了したことを確認します。

.. figure:: images/c14-m1-9.png
   :scale: 35%
   :align: center
