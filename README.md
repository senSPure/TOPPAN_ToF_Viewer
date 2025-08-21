# senSPure Viewer

TOPPAN senSPure ToFカメラ「senSPure」用のビューアアプリケーションです。
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

## セットアップ

### Windows

`windows_x64/sdk/` フォルダ内の `install_env_execute.bat` を実行し、セットアップを行ってください。

### Linux (Ubuntu / Jetson)

お使いの環境に対応するフォルダ（`ubuntu_x64/sdk/` または `jetson_arm64/sdk/`）に移動し、ターミナルで以下のコマンドを実行してください。

```bash
./install_env_execute.sh
```



---

## 使い方

### Windows

`windows_x64/sdk/` フォルダ内の `TOPPAN_ToF_Viewer.exe` をダブルクリックしてアプリケーションを起動します。

### Linux (Ubuntu / Jetson)

セットアップを行ったフォルダ内で、以下のコマンドを実行します。

```bash
./run.sh
```
