# awesome ConoHa cloud tools

- update 2020-08-24


## ConoHa DNS API tools
(postman)ConoHa API Postman
https://github.com/tacyan/ConoHa-API

(docker, python)osclient: ConoHaでOpenStack-CLIを使う
https://github.com/mamemomonga/docker-conoha-openstack-client

(python)osclient
https://github.com/naototty/conohacloud-osclient

(python)CLI
https://github.com/naototty/python-designateclient/tree/conoha-dns


(bin, golang)terraform
https://www.terraform.io/docs/providers/acme/dns_providers/conoha.html

(bin, golang)CLI, lego
https://go-acme.github.io/lego/dns/conoha/

(bin, golang)terraform dns
https://github.com/hanazuki/terraform-provider-conoha

(golang, CLI)conoha-api-go-client 日本語
https://github.com/is2ei/conoha-api-go-client
https://godoc.org/github.com/is2ei/conoha-api-go-client/conoha

(golang, CLI)conoha client library
https://github.com/raben/conoha

(golang, CLI)ConoHa で簡単な勉強用VPSを構築したい人向けのお手軽CLI
https://github.com/miyabisun/conoha-cli

(golang, lib) library mailservice
https://github.com/katsubushiken/conoha

(golang, lib, mail)
https://github.com/katsubushiken/conoha

(golang, UI)
https://github.com/xisj/conoha-ui




(k3s, startup-script)K3s on ConoHa (dns let's encrypt)
https://qiita.com/yhirokw/items/fd5dcb28d3f57de0cc40

(sh)certbot tool
https://github.com/k2snow/letsencrypt-dns-conoha

(certbot, python)Get certificates by certbot with ConoHa DNS API v1 (read only)
https://github.com/nakanokurenai/certbot-dns-conoha
  * https://pypi.org/project/certbot-dns-conoha/

(certbot, python3.6)ConoHa DNS Authenticator plugin for Certbot
https://github.com/masm11/certbot-dns-conoha


(bash, curl, ddns)
https://github.com/aaaa777/ddns-sh

(dehydrated)Dehydrated is a client for signing certificates with an ACME-server (e.g. Let's Encrypt) implemented as a relatively simple (zsh-compatible) bash-script.
https://github.com/dehydrated-io/dehydrated

(DotNet)DotNet lib
https://github.com/crowdy/OpenStack-ConoHa

(azure function DotNet)DdnsFunctions for ConoHa
https://github.com/azyobuzin/DdnsFunctions



### ConoHa DNS API docs

create domains
https://www.conoha.jp/docs/paas-dns-create-domain.php

create records
https://www.conoha.jp/docs/paas-dns-create-record.php

### blog
(Lexicon, Dehydrated, lego)blog : ConoHaのDNSをAPIから操作する話
https://narusejun.com/archives/25/

(curl)blog
https://access-jp.co.jp/blogs/development/234
2018-06-29Web API
ConoHa DNS API を Bash で試す

(lego)lego+docker-composeでワイルドカード証明書を爆速ゲット
https://qiita.com/dbgso/items/233e68f07eb864be60e6





## ConoHa CLI, SDK, libs

### python
(python)ConoHa_ddns
ConoHa APIを用いてDNSレコードを書き換えるCLIツール 定期的にサーバ上で実行することでDDNSとして使えます
https://github.com/hirotta/conoha_ddns


### php
(php)ConohaDnsAPI
https://github.com/soradore/ConohaDnsAPI

(php)PHP - ConoHa API for PHP (DNS available)
https://github.com/ezaki/chap

(php-laravel)Laravel Conoha API
https://github.com/xzxzyzyz/laravel-conoha-api

(DotNet)ConoHaDNS
https://github.com/iedred7584/ConoHaDNS

(php)conohaDNS
https://github.com/shirakun/conohaDNS

(php-conoha)
https://github.com/hironobu-s/php-conoha

(ruby)ConoHaAPI is api client for ConoHa
https://github.com/kinoppyd/conoha-api

(ruby)conoha ddns
https://github.com/esetomo/conoha_ddns





### java
(java-gradiew)
https://github.com/ekuro/conoha-api


### golang
(golang, CLI)ConoHa VPS 管理API CLIツール
https://github.com/aqmr-kino/conoha-cli

(golang)Unofficial SDK for ConoHa API written in golang (Identity only)
https://github.com/supermomonga/go-conoha


### ruby

### js
(js)CLI
https://openbase.io/js/conoha-dns/documentation

(js)cmd4conoha
https://github.com/taisukef/cmd4conoha
  * https://fukuno.jig.jp/2656

(js)node conoha-dns CLI
https://github.com/kaz/conoha-dns

(js, node)CoNoHa API(WIP)
https://github.com/17number/conoha-api



## ConoHa2 other API (mail, etc)
(serverless python)serverless-email-send-tool
https://github.com/kmamiya/serverless-email-send-tool
  * https://logicalrabbit.jp/serverless-email-send-tool
  
(python)conoha-mailing-api
https://github.com/64ffe1ne/conoha-mailing-api




## OpenStack Tools
* (js)SDK
  * https://github.com/gabrielhurley/js-openclient

* (java)josc -- java s3, swift object storage connector --
  * https://elderbyte-.github.io/josc/

* (java)JOSS -- JOSS is a Java client for the OpenStack Storage component REST interface.
  * https://github.com/javaswift/joss
  * http://javaswift.org/


## ConoHa2 cloud-os
(rancheros)Conoha VPSにRancherOSをインストールする手順
https://himakan.net/program/conoha-vps-install-rancheros

(rancheros, iso)ConoHaでISOダウンロードが出来なかった件
https://qiita.com/marukei/items/6b6ccee3e7a553f64f1e

(rancheros, coreos)ConohaVPSでCoreOSやRancherOSを入れる際に困ったこと
  * (vda, sdaの違いについて)
https://www.meganii.com/blog/2018/02/18/rancher-os/


## ConoHa deployment, k8s, rancher, containers
(terraform)Deployment My instance in conoha by terraform
https://github.com/maki0922/terraform_in_conoha

(DotNet, kudu)
https://github.com/shibayan/conoha-kudu-docker
  * https://blog.shibayan.jp/entry/20161217/1481972714
  * Docker Compose と Kudu を使って ConoHa 上に ASP.NET Core のデプロイ環境を作ってみた

(k3s)K3s on ConoHa
https://qiita.com/yhirokw/items/fd5dcb28d3f57de0cc40

(OpenVPN AS)Conoha_openvpnas.sh
https://github.com/Sean2525/Conoha_openvpnas.sh

(ansible)openfaas-on-conoha
https://github.com/nwiizo/openfaas-on-conoha

(ansible)kubernetes-on-conohas
https://github.com/nwiizo/kubernetes-on-conohas

(ansible)kubernetes-on-conohas
https://github.com/nwiizo/kubernetes-on-conoha

