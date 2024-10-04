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
1. [口座（チャネル）閉鎖に伴う残高の回収](#anchor6)


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

---
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

---
<a id="anchor3"></a>
- Bolt Linkによる受取
    - 各Bolt LinkのWebサイト（デモサイトは[こちら][demo]）の「ウォレットで開くをクリックし、Diamond Walletを起動すると、広告サイトが表示されます。
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
    - 口座（チャネル）が未開設の場合にBolt Linkをアプリで開くとエラーメッセージが表示されます。[口座（チャネル）の開設](#anchor2)を参考に口座を開設後に再度Bolt Linkを開いてください。
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

---
<a id="anchor4"></a>
- 通知設定
    - 通知設定をすることで、アプリが起動していない場合でもビットコインを受け取ることができます。
    - 通知設定の許可がされているか確認するには、「設定」タブの「通知設定」画面へ遷移して、「通知設定」をタップしてください。
    通知許可されている場合、以下の図のようなメッセージが表示されます。通知設定を拒否する場合は「システム設定」から設定してください。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/notification.png" width="300">
    </td>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/notification-enabled.png" width="300">
    </td>
    </tr>
    </table>

---
<a id="anchor5"></a>
- ウォレットの復元
    - スマフォの紛失などでアプリが削除された場合、再度、アプリをインストールして起動します。
    - バックアップしておいた復元シードを入力し、「次へ」をタップします。この際、復元シードは半角スペースで区切ってください。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/create.png" width="300">
    </td>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/restore-seed.png" width="300">
    </td>
    </tr>
    </table>
    - 復元が開始され、通知許可のダイアログが表示されたら、「許可」を選択してください。
    - 復元が完了すると、ホーム画面が表示されます。残高があるにも関わらず表示されない場合、「更新」をタップしてください。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/restore-notification.png" width="300">
    </td>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/restore-home.png" width="300">
    </td>
    </tr>
    </table>

---
<a id="anchor6"></a>
- 口座（チャネル）閉鎖に伴う残高の回収
    - 口座閉鎖に伴うオンチェーン上のビットコイン（💤 マークの残高）を回収するには、
    💤 をタップしてください。
    - 送金したいビットコインアドレスを入力し、手数料を選択してから、「手数料を計算」をタップして、送金手数料を計算します。
    ※手数料の選択ではより大きな手数料率のほうが送金が成功しやすくなります。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/redeem.png" width="300">
    </td>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/redeem-fee.png" width="300">
    </td>
    </tr>
    </table>
    - 手数料と送金される金額を確認し、よろしければ「送金」をタップします。送金が成功すると以下の図のような「Redeemed on-chain funds...」と表示されます。送金データがブロックチェーンに書き込まれるまで数分〜数時間かかる場合があります。
    <table>
    <tr>
    <td>
    　<img src="{{ site.baseurl }}/assets/images/redeem-success.png" width="300">
    </td>
    </tr>
    </table>

[demo]: https://ads.diamondhands.technology/c/demo