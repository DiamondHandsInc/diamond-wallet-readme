---
layout: page
title: 使い方
permalink: /howto/
---

1. [ウォレットの作成](#anchor1)
1. [口座（チャネル）の開設](#anchor2)
1. [Bolt Linkによる受取](#anchor3)
1. [通知設定](#anchor4)
1. [ウォレットの復元](#anchor5)


---

<a id="anchor1"></a>
- ウォレットの作成
    - 「新規作成」 - 「次へ」 と進み、ウォレットを新規作成します。
    この時、シードフレーズをメモ帳などへ書き留めておくことを推奨します。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/create.png" width="300">
    </td>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/seed.png" width="300">
    </td>
    </tr>
    </table>

<a id="anchor2"></a>
- 口座（チャネル）の開設
    - 「受信」 - 「テンキー」 と進み、口座開設のために必要な手数料（3000 sat）を入力します。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/home.png" width="300">
    </td>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/type-amount.png" width="300">
    </td>
    </tr>
    </table>
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/invoice.png" width="300">
    </td>
    </tr>
    </table>
    - 口座開設に必要な手数料未満を入力すると以下のようなエラーが表示されます。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/invalid-amount.png" width="300">
    </td>
    </tr>
    </table>

<a id="anchor3"></a>
- Bolt Linkによる受取
    - Bolt LinkのWebサイトの「ウォレットで開くをクリックし、Diamond Walletを起動すると、広告サイトが表示されます。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/bolt-link-web.png" width="300">
    </td>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/loading-blocks.png" width="300">
    </td>
    </tr>
    </table>
    - 広告サイトが表示されると、アプリが報酬を受け取るための準備を開始します。
    以下の画像のように、アプリ内ブラウザのヘッダーに準備中の状態が表示されます。
    この状態は以下のように遷移していきます。
    1. loading blocks
    1. creating invoice
    1. authorizing
    1. payment requested または failed
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/loading-blocks-hightlight.png" width="300">
    </td>
    </tr>
    </table>
    - 報酬を受け取るとアプリ内ブラウザ上にダイアログ画面が表示されます。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/reward-received.png" width="300">
    </td>
    </tr>
    </table>
<a id="anchor4"></a>
- 通知設定
    - 作成中

<a id="anchor5"></a>
- ウォレットの復元
    - 作成中