# senSPure Viewer

TOPPANのToFカメラ「senSPure」用のビューアアプリケーションです。
深度データや点群データをリアルタイムで表示、記録することができます。

---

## 更新履歴

* **Version 3.0.5 [2025/7/4]**
    * 点群変換処理に関する不具合を修正しました。

---

## 動作環境

このアプリケーションは、以下のOSで動作確認済みです。

* **Windows:**
    * Windows 10
    * Windows 11
* **Linux:**
    * Ubuntu 20.04
* **NVIDIA Jetson:**
    * JetPack 5.0.1

---

## 使い方

### Windows

1.  `windows_x64` フォルダ内の `install_env_execute.bat` を実行し、初回環境設定を行ってください。
2.  `TOPPAN_ToF_Viewer.exe` をダブルクリックしてアプリケーションを起動します。

### Linux (Ubuntu / Jetson)

1.  お使いの環境に対応するフォルダ（`ubuntu_x64` または `jetson_arm64`）に移動します。
2.  ターミナルで以下のコマンドを実行し、初回環境設定と実行権限の付与を行います。

    ```bash
    sh install_env_execute.sh
    ```

3.  以下のコマンドでアプリケーションを起動します。

    ```bash
    ./run.sh
    