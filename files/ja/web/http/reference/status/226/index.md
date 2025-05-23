---
title: 226 IM Used
slug: Web/HTTP/Reference/Status/226
original_slug: Web/HTTP/Status/226
l10n:
  sourceCommit: 592f6ec42e54981b6573b58ec0343c9aa8cbbda8
---

{{HTTPSidebar}}

> [!NOTE]
> ブラウザーは HTTP で _デルタエンコーディング_ に対応していません。このステータスコードは特定のクライアントで用いられるカスタムされたサーバーから送り返されます。

デルタエンコーディングの文脈において、HTTP **`226 IM Used`** ステータスコードは受信した {{HTTPMethod("GET")}} リクエストに対する _デルタ_ を返していることを示すためにサーバーによって設定されます。

デルタエンコーディングでは、サーバーは {{HTTPMethod("GET")}} リクエストに対して (現在のドキュメントではなく) 指定のベースドキュメントからの (_デルタ_ と呼ばれる) 違いで応答します。クライアントは `A-IM:` HTTP ヘッダーにより使用する差分アルゴリズムを示し、`If-None-Match:` ヘッダーで取得した最新バージョンに関するヒントをサーバーに与えます。サーバーはデルタを生成し、ステータスコードが `226` で、(使用したアルゴリズムの名前を伴う) `IM:` HTTP ヘッダーおよび (デルタに紐づくベースドキュメントに対応する {{HTTPHeader("ETag")}} を伴う) `Delta-Base:` HTTP ヘッダーが含まれる HTTP レスポンスで返します。

IM は _instance manipulations_ を表します。これは _デルタ_ の生成アルゴリズムを記述する際に用いられる用語です。

## ステータス

```plain
226 IM Used
```

## 仕様書

{{Specifications}}
