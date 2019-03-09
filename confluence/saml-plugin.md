# ConfluenceでSAMLプラグインを使用したSSOの実現
 
## 今回、採用してみたプラグイン
 
resolution Reichert Network Solutions GmbH さんが出している「SAML Single Sign On (SSO) Confluence」
https://marketplace.atlassian.com/apps/1212129/saml-single-sign-on-sso-confluence

## 使用感
 
 設定方法については慣れている人であれば、5分もあれば設定が完了する。本来は本番環境で行わないべき操作だが、本番環境でも十分に安定して作業を進められる。
 移行中のダウンタイムについても発生はほぼない。
 
## 困ったこと＆解決策

### SSOなしでログインしたい時の回避方法
 https://インストールドメイン/login.action?nosso
