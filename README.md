# HuntPad（ハントパッド）

<img src="https://raw.githubusercontent.com/konvarec/HuntPadCustomRepo/main/images/huntpad-v2.png" alt="HuntPad icon" width="128" height="128">

FFXIV / Dalamud向けのモブハント支援ツールです。`/huntpad`で開きます。

## できること

- 周囲のプレイヤー、モブ、FATEを地図に表示
- リスキーモブのPOP候補を地図に表示し、見つけた地点を記録
- モブハントエリアのPOP地点が収まるよう地図を自動調整
- Sモブトリガーをカウント
- 未観測POPの通知と、リスキーモブのリポップ時刻連携

## インストール

1. Dalamud設定の「試験的機能 / Experimental」を開きます。
2. 「カスタムプラグインリポジトリ」に次のURLを追加して保存します。

   ```text
   https://raw.githubusercontent.com/konvarec/HuntPadCustomRepo/main/pluginmaster.json
   ```

3. プラグインインストーラーを開き直し、`HuntPad`をインストールします。
4. 初回に利用キーを入力し、`/huntpad`で地図を開きます。

利用キーはObserver（HuntVoidWatcher）と共通です。キーはこのリポジトリやIssueに投稿しないでください。

## 基本の使い方

- 地図を開く: `/huntpad`
- POP地点を表示する: エリアごとの設定で「MOBPOS」をON
- 地図をPOP地点に合わせる: 共通設定で「モブハントエリアのPOP位置に地図を自動フィット」をON
- 記録の状態を確認する: 共通設定の「POP記録の診断情報をコピー」

## 0.2.0.0への切り替え

0.1.0.19以前を使っている場合は、旧版を無効化してから一覧を再取得し、HuntPad 0.2.0.0を新規インストールしてください。旧版と新版を同時に有効にしないでください。

初回だけ、`HuntPad.json`がなければ旧設定からPOP記録・設定・利用キー解除状態を取り込みます。旧設定ファイルはバックアップとして残ります。

## 配布内容

- `pluginmaster.json`: インストール・更新用一覧
- `HuntPad/<version>/latest.zip`: プラグイン本体
- `images/huntpad-v2.png`: プラグイン一覧用アイコン

このリポジトリにはソースコード、ログ、利用キーを含めません。
