![OWND Project Logo](https://raw.githubusercontent.com/OWND-Project/.github/main/media/ownd-project-logo.png)

# 概要

OWND Project は個人が主体となるデジタルアイデンティティーの社会実装を目指し、よりトラストできるコミュニケーションを実現するための非営利プロジェクトです。

このプロジェクトは内閣官房デジタル市場競争本部の推進する"Trusted Web"のユースケース実証事業の一部として誕生しました。

国際標準技術に準拠したホワイトラベルのデジタルアイデンティティーウォレットおよび、E2E暗号化に対応したFederation型のメッセージングアプリケーションをオープンソースソフトウェアとして開発し、トラストを担保するガバナンスについても議論を行います。

[OWND Project の概要説明資料](https://github.com/OWND-Project/.github/blob/main/profile/ownd-project.pdf)

[Trusted Web についてはこちら](https://trustedweb.go.jp/)

# 参加方法

興味をもった方はどなたでもご参加ください。

[OWND Project Matrix スペース](https://matrix.to/#/!EdKfOXCYPSFCXmxTqw:matrix.org?via=matrix.org)

## OWND Wallet

国際標準技術に準拠したホワイトラベルのデジタルアイデンティティーウォレット。

OWND walletをベースとしたさまざまなウォレットやユースケースが創出されることを想定し、それぞれのウォレットの相互運用性を確保することを目指す。

![OWND Wallet Image](https://raw.githubusercontent.com/OWND-Project/.github/main/media/ownd-wallet.png)

#### 開発物（予定）

* OpenID for Verifiable Credential Issuance（OID4VCI）の Holder,Issuer 実装
* OpenID for Verifiable Presentations（OID4VP）の Holder,Verifier 実装
* Self-Issued OpenID Provider v2（SIOPv2）の Holder,Verifier 実装
* Selective Disclosure for JWTs（SD-JWT）証明書
* JSON-LD ZKP with BBS+ 証明書

## OWND Messenger

OWND walletを用いてアイデンティティを管理できる、E2E暗号化に対応したメッセージングアプリケーションおよびプロトコル。

特定の事業者に過度に依存せず、誰でもメッセージングサーバを構築することができ、サーバ同士の相互運用が可能(Fediverse)。

年齢証明書や所属証明書を活用し、相手方を確認してメッセージングを行う。

![OWND Messenger Image](https://raw.githubusercontent.com/OWND-Project/.github/main/media/ownd-messenger.png)

#### 開発物（予定）

* プロトコルには [Matrix](https://github.com/matrix-org) を採用
* サーバーサイドは [Synapse](https://github.com/matrix-org/synapse) にSIOPv2、OID4VPおよび各種証明書へ対応するためのを機能を追加実装
* クライアントサイドは [Element Web](https://github.com/vector-im/element-web) にSIOPv2、OID4VPおよび各種証明書へ対応するためのを機能を追加実装

