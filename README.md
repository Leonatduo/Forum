<p align="center">
	<img alt="logo" src="https://oscimg.oschina.net/oscnet/up-b99b286755aef70355a7084753f89cdb7c9.png">
</p>
<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">RuoYi v3.6.3</h1>
<h4 align="center">Vue と Spring Boot/Spring Cloud & Alibaba をベースとした、前後端分離型の分散マイクロサービスアーキテクチャ</h4>
<p align="center">
	<a href="https://gitee.com/y_project/RuoYi-Cloud/stargazers"><img src="https://gitee.com/y_project/RuoYi-Cloud/badge/star.svg?theme=dark"></a>
	<a href="https://gitee.com/y_project/RuoYi-Cloud"><img src="https://img.shields.io/badge/RuoYi-v3.6.3-brightgreen.svg"></a>
	<a href="https://gitee.com/y_project/RuoYi-Cloud/blob/master/LICENSE"><img src="https://img.shields.io/github/license/mashape/apistatus.svg"></a>
</p>

## プラットフォーム紹介

前後端分離モードを採用し、マイクロサービス版のフロントエンドを使用します。
バックエンドには Spring Boot、Spring Cloud & Alibaba を採用しています。
レジストリセンターとコンフィギュレーションセンターには Nacos を選択し、権限認証には Redis を使用しています。
トラフィック制御フレームワークには Sentinel を、分散トランザクションには Seata を選択しています。
  

## アーキテクチャ図

<img src="https://oscimg.oschina.net/oscnet/up-82e9722ecb846786405a904bafcf19f73f3.png"/>

## 機能

ユーザー管理：ユーザーはシステムの操作者で、この機能は主にシステムユーザーの設定を完了します。

部署管理：システムの組織構成（会社、部署、グループ）を設定し、ツリー構造で表示し、データ権限をサポートします。

職位管理：システムユーザーの所属する職務を設定します。

メニュー管理：システムメニュー、操作権限、ボタン権限の識別子などを設定します。

役割管理：役割のメニュー権限の割り当て、役割による組織単位でのデータ範囲権限の設定を行います。

辞書管理：システムでよく使用される比較的固定されたデータをメンテナンスします。

パラメータ管理：システムの動的設定によく使用されるパラメータを管理します。

通知・公告：システムの通知・公告情報の発信とメンテナンスを行います。

操作ログ：システムの通常操作のログ記録と照会、システムの異常情報のログ記録と照会を行います。

ログインログ：システムのログインログの記録照会（ログイン異常を含む）を行います。

オンラインユーザー：現在のシステム内のアクティブなユーザーの状態をモニタリングします。

タイマータスク：オンラインでの（追加、修正、削除）タスクスケジューリング（実行結果のログを含む）を行います。

コード生成：前後端のコード生成（java、html、xml、sql）を行い、CRUD ダウンロードをサポートします。

システムインターフェース：業務コードに基づいて自動生成される関連する API インターフェースドキュメントを作成します。

サービスモニタリング：現在のシステムの CPU、メモリ、ディスク、スタックなどの関連情報を監視します。

オンラインビルダー：フォーム要素をドラッグして対応する HTML コードを生成します。

コネクションプールモニタリング：現在のシステムのデータベースコネクションプールの状態を監視し、SQL 分析を行い、システムのパフォーマンスボトルネックを特定することができます。



## 展示図

<table>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/cd1f90be5f2684f4560c9519c0f2a232ee8.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/1cbcf0e6f257c7d3a063c0e3f2ff989e4b3.jpg"/></td>
    </tr>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-8074972883b5ba0622e13246738ebba237a.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-9f88719cdfca9af2e58b352a20e23d43b12.png"/></td>
    </tr>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-39bf2584ec3a529b0d5a3b70d15c9b37646.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-4148b24f58660a9dc347761e4cf6162f28f.png"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-b2d62ceb95d2dd9b3fbe157bb70d26001e9.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-d67451d308b7a79ad6819723396f7c3d77a.png"/></td>
    </tr>	 
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/5e8c387724954459291aafd5eb52b456f53.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/644e78da53c2e92a95dfda4f76e6d117c4b.jpg"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-8370a0d02977eebf6dbf854c8450293c937.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-49003ed83f60f633e7153609a53a2b644f7.png"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-d4fe726319ece268d4746602c39cffc0621.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-c195234bbcd30be6927f037a6755e6ab69c.png"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-ece3fd37a3d4bb75a3926e905a3c5629055.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-92ffb7f3835855cff100fa0f754a6be0d99.png"/></td>
    </tr>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-ff9e3066561574aca73005c5730c6a41f15.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-5e4daac0bb59612c5038448acbcef235e3a.png"/></td>
    </tr>
</table>
