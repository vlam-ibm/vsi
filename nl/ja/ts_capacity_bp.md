---

copyright:
  years: 2017
lastupdated: "2018-01-03"

subcollection: virtual-servers

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:tip: .tip}
{:table: .aria-labeledby="caption"}


# 容量に関する考慮事項
{: #capacity-considerations}

## 現象

仮想サーバーのプロビジョン時に、以下のエラー・メッセージが表示されることがあります。

```
要求を完了するために使用できる容量が不足しています。(There is insufficient capacity to complete the request.)
```
{:screen}

プロビジョニングが失敗した場合、その特定の要求内のすべての仮想サーバー・インスタンスが失敗します。
{:tip}

## 現象の理由

容量エラーは、サービス要求を実行するためにルーターまたはデータ・センター内で使用可能なリソースが不足している場合に発生します。 このエラーが表示される場合、多数の理由が考えられます。 リソース・アベイラビリティーは頻繁に変わるため、しばらく待ってから後で再試行してください。

## 修正方法

以下の方法を使用して、プロビジョンを再試行できます。

1. 別のルーターを指定してプロビジョンする。  
2. ルーターを指定せずにプロビジョンする。
3. 別のデータ・センター内でプロビジョンする。
4. より少ないインスタンスをプロビジョンする。
5. 複数のデータ・センターにプロビジョンして、インスタンスを分散させる。
6. より小さいサイズのインスタンスをプロビジョンする。
7. VSI ストレージを SAN から LOCAL または LOCAL から SAN に変更する。
