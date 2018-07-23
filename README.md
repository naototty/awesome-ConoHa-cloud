# awesome-ConoHa-cloud
awesome ConoHa cloud

## menu

[menu](#menu)

* [about awesome](#about_awesome)
* [History](#history)
  * [Before ConoHa birth](#before_conoha_birth)
  * [ConoHa1 to Before ConoHa2](#conoha1_to_before_conoha2)
  * [ConoHa2](#conoha2)
* [the News of ConoHa chan](#the_news_of_conoha_chan)
* [ConoHa events](#conoha_events)
* [technical articles ConoHa1](#technical-articles-conoha1)
* [technical articles and blogs ConoHa2](#technical-articles-and-blogs-conoha2)
* [ConoHa Start-up script](#conoha-start-up-script)
* [Tools, ConoHa活用ツール](#tools)
* [Compairing, VPSの比較](#compairing)
* [installing, installing記事/blog](#installing)
* [user monitoring, 監視設定記事](#user-monitoring)
* [ConoHa1 to ConoHa2 migration or Cloud image migration, ConoHaのVPSマイグレーション記事](#conoha1-to-conoha2-migration-or-cloud-image-migration)
* [Advent Calender](#advent-calender)


<div id="about_awesome"></div>

## abount_awesome

"awesome" とは?
そのカテゴリについてのすごいリンク集

* ex) [asesome awesomes(開発系awesome)](https://github.com/fleveque/awesome-awesomes)

* ex) [awesome asesome(githubの中のawesome)](https://github.com/athityakumar/awesome-awesomes)

* ex) [awesome HANAMI(ruby lightweight MVC Framework)](https://qiita.com/park-jh/items/5ca1f48384fb5173cbb5)

* ex) [awesome Cloud Native](https://jimmysong.io/awesome-cloud-native/)

* ex) [A curated list for awesome OpenStack links!](https://github.com/ntk148v/awesome-openstack)
* ex) [A curated list for awesome openstack links](https://github.com/ramitsurana/awesome-openstack)

* ex) [A curated list of awesome open source workflow engines](https://github.com/meirwah/awesome-workflow-engines)

* ex) [Awesome Serverless](https://github.com/anaibol/awesome-serverless)
* ex) [Awesome Serverless](https://github.com/pmuens/awesome-serverless)
* ex) [Awesome Serverless](https://github.com/vegasbrianc/awesome-serverless-1)


[return to menu](#menu)


<div id="history"></div>

## History

<div id="before_conoha_birth"></div>

### Before ConoHa birth

* vps VZ時代                                                                                                                          
  * (2009-09-17) [2009.09.17 【お知らせ】自由度と拡張性を追及した本格運用向けレンタルサーバー「VPS」を提供開始！](https://www.onamae.com/news/domain/090917.html)
    - Virtuozzo(OpenVZ/Virtuozzo)ベースのContainer OS仮想化によるVPS

* GMOアプリやろうぜ
  * (2010-02-25) [GMO、「アプリやろうぜ！」プロジェクト開始
総額3億円を掛けて開発者を支援](https://codezine.jp/article/detail/4973)
    - Virtuozzo ~ libvirt + xen + GMO original controller時代

* GMOアプリクラウド、リリース
  * (2010-08-03) [GMOアプリクラウド　正式リリースしました](https://cloud.gmo.jp/news/10080300.html)
    - Virtuozzo ~ libvirt + xen + GMO original controller時代

* GMOアプリクラウド、ver2.0(KVM)リリース
  * (2011-03-25) [Ver2.0 ＆ USデータセンター 提供開始しました](https://cloud.gmo.jp/news/11032500.html)
    - Virtuozzo ~ libvirt + KVM + GMO original controller時代
    - クラウド時代到来、莫大なノード数が必要になる
    - 次期インフラとして、Eucaliptus, OpenStack検証が始まる (OpenStack Cactus, OpenStack Diablo)

* OpenStack Diablo release
  * (2011-09-22) [OpenStack Diablo release](https://releases.openstack.org/)
    - 検証結果、新規実装されたkeystoneがまともに動かないことがわかったが、運用で回避することに

* vps kvm
  * (2012-03-22) [［VPS］ お名前.comの新VPS「KVMプラン」が正式リリース](https://www.onamae.com/news/domain/120321_5.html)
  * (2012-03-22) [GMOインターネット、「お名前.com　レンタルサーバー VPS」、「KVMプラン」 正式提供開始～正式提供に合わせ、充実した新仮想専用サーバーとしてプラン内容を見直し～](https://japan.cnet.com/release/30016763/)
    - OpenStack Diabloを使ったVPSリリース(~サービス提供中)

* CloudStack
  * (2012-04-03) [米Citrix、「CloudStack」をApache Software Foundationに寄贈](https://mag.osdn.jp/12/04/04/0442220)
    - CloudStackの選択肢もちょっと頭をよぎるが、Single service構造だったので、見送る

* tenten.vn
  * (2012-04-23) [GMOインターネット、ベトナムでドメイン登録事業開始　RunSystem社を通じてドメイン登録サービス「TEN TEN.vn」を提供](https://japan.cnet.com/release/30018544/)

* pixiv
  * (2012-06-01) [pixivでGMOアプリクラウドの公式キャラクターを募集 - 内田真礼が声を担当](https://news.mynavi.jp/article/20120604-a020/)
  * (2012-06-01) [「あなたのキャラを内田真礼が演じる！　GMOアプリクラウド公式キャラクター募集」応募作品一覧](https://www.pixiv.net/contest/gmo_appscloud.php)

* Opensource community発表
  * (2012-08-03) [OSC 2012 Kyoto: OpenStack + KVM = お名前.com VPS ~開発担当者が語る、ここだけの裏話~](https://www.slideshare.net/chroum/2012-osc-kyoto-openstack-vps-kvm)

* GMOアプリクラウド、美雲あんず
  * (2012-09-20) (TGS2012: GMOインターネットのブースに痛車降臨！　ツインテールの美雲あんずがお待ちしてます。モデルキャラの声優は内田真礼さん。)(http://nlab.itmedia.co.jp/nl/articles/1209/20/news100.html)

  * (2012-11-10) [K-OF 2012, Osaka: OpenStack + KVM = onamae.com VPS #2 ~ vnc and snapshot ~](https://www.slideshare.net/chroum/openstack-vpskvmonamecom2snapshot)

* tenten.vn
  * (2012-12-12) [tenten.vn VPS release](https://tenten.vn/tin-tuc/68-tenten-chinh-thuc-ra-mat-dich-vu-may-chu-ao-vps)

* Opensource community発表
  * (2013-02-23) [OSC 2013 Spring Tokyo: OpenStack + KVM = お名前.com VPS ~開発担当者が語る、ここだけの裏話 2013~](https://www.slideshare.net/chroum/openstack-kvm-ipv6-onamecom-next-folsomgrizzly-service-development-status)

[return to menu](#menu)

<div id="conoha1_to_before_conoha2"></div>

### ConoHa1 to Before ConoHa2

* 2013/07/04 [GMOインターネット、VPS新ブランド「ConoHa byGMO」を提供開始～IPv6、複数IPアドレス、ローカルネットワークに対応、イメージキャラクター「美雲このは」初登場](https://cloud.watch.impress.co.jp/docs/news/606431.html
 
* 2013/10/04 [GMOインターネット、VPSサービス「ConoHa」のオプションサービスを値下げ](https://cloud.watch.impress.co.jp/docs/news/618167.html)

* 2013/12/26
  * https://cloud.watch.impress.co.jp/docs/news/629208.html
    * GMO、VPSとクラウドサービスの公式キャラアニメを公開～冬コミで配布も
    - （2013/12/26 15:07）
    - 「超亜空間防壁チーズ・ナポリタン」 アニメーション YouTube公開、コミケで5000人配布
    - http://www.mikumo.com/movie/
    
* GMOアプリクラウド, OpenStack Havana
  * (2014-04-22) [GMOアプリクラウド新サービス提供開始のお知らせ(OpenStack)](https://cloud.gmo.jp/news/14042200.html)

* ConoHa1, OpenStack Havana; Object Storage
  * (2014/09/03) [GMOインターネット：「ConoHa byGMO」で「オブジェクトストレージ」提供開始](https://japan.cnet.com/release/30079817/)

[return to menu](#menu)

<div id="conoha2"></div>

### ConoHa2

* 2015/05/18 [GMO、VPSサービス「ConoHa」をリニューアル、全ストレージにSSDを採用, SSD 50GB, 3 location](https://cloud.watch.impress.co.jp/docs/news/702382.html)

* 2015/10/29 [アセンテック、オールSSDの「ConoHa」を基盤として利用した仮想デスクトップサービス](https://cloud.watch.impress.co.jp/docs/news/728111.html)

* 2015-10-27 [OpenStackSummit Tokyo 2015 に協賛決定。Aiming様 C Channel様と基調講演](https://cloud.gmo.jp/news/15102300.html)

* 2016/10/28 [GMOインターネット、VPSサービス「ConoHa」に月額630円の512MBプランを追加](https://cloud.watch.impress.co.jp/docs/news/1027239.html)
    
* 2017/06/30 [【リリース】APIを利用したVPS作成におけるスタートアップスクリプト機能追加](https://www.conoha.jp/news/?ap=2015051386)


[return to menu](#menu)

<div id="the_news_of_conoha_chan"></div>

## the News of ConoHa chan

* 2013/12/29 [GMO×スタジオカラー、フル3DCGショートアニメ「超亜空間防壁チーズ・ナポリタン」を公開](https://www.gmo.jp/news/article/?id=4374)

* 2013/12/31 [「超亜空間防壁チーズ・ナポリタン」全編公開　コミックマーケット85でのDVD配布も絶好調](https://animeanime.jp/article/2013/12/31/16922.html)

* 2014/05/25 [「公式」 美雲このはの斜め上いくコミュニティ](http://com.nicovideo.jp/community/co2392550?ref=search_tag_co)

[return to menu](#menu)

<div id="conoha_event"></div>

## ConoHa events

* Akihabara Events
  * 2013-07-12,13,14 [秋葉原に電子の座敷わらし「美雲このは」－GMOのVPS新ブランド「ConoHa」提供開始で](https://akiba.keizai.biz/column/65/)

* Eject users Hands on
  * 2014-09-27 [出張このべん：猫カフェ×Ejectユーザー会、奇跡のコラボハンズオン！ConoHa byGMO](https://conoha.doorkeeper.jp/events/14471)

* case study
  * (2017-05 ~ ) [けーすた！ CASE STUDY LIGHTNING TALK](https://casestudy.connpass.com/)

[return to menu](#menu)

<div id="technical_articles_conoha1"></div>

## technical articles ConoHa1

* 2013/07/31
  * https://internet.watch.impress.co.jp/docs/column/conoha/609575.html
    * VPS同士をLANで接続～「ローカルネットワーク」機能を試す
     
* 2013/07/30
  * https://internet.watch.impress.co.jp/docs/column/conoha/609426.html
    * IPv4アドレスの追加とIPv6アドレスの利用を試す

* 2013/07/29
  * https://internet.watch.impress.co.jp/docs/column/conoha/609011.html
    * いつでも自由にVPSを作成～コントロールパネルの使い勝手を試す

* 2013/07/22
  * https://internet.watch.impress.co.jp/docs/column/conoha/608097.html
    * 開発者に聞く～自由な構成が可能な新VPSサービス「ConoHa」とは
「ITエンジニアの方に使って欲しくて作った」GMOの新VPSブランド


## technical articles and blogs ConoHa2

* 2018/04/18
  * https://www.gmo.jp/report/single/?art_id=226
    * 第216回 PowerShellでConoHaをどうにかしてみる-Vol.3
ConoHa APIを使ってPowerShellのオリジナルコマンドでサーバー管理

* 2018/03/28
  * https://www.gmo.jp/report/single/?art_id=225
    * 第215回 PowerShellでConoHaをどうにかしてみる-Vol.2
ConoHa APIを使ってPowerShellのオリジナルコマンドでサーバー管理

* 2018/02/21
  * https://www.gmo.jp/report/single/?art_id=224
    * 第214回 PowerShellでConoHaをどうにかしてみる-Vol.1
ConoHa APIを使ってPowerShellのオリジナルコマンドでサーバー管理

* 2018/02/06
  * https://syobon.jp/2018/02/06/minecraft-server-on-conoha/
    * Minecraft サーバーをConoHaで簡単構築！規模にあわせた最適なプランを選ぶには | しょぼんブログ
    * Minecraftサーバーテンプレート


## ConoHa Start-up script

* 2017/07/05
  * https://blog.oyasu.info/2017/07/05/5906/
    * ConoHa のスタートアップスクリプトを使って VM を作成してみた（CentOS 7 編）


## Tools

* ConoHa-CLI (golang) @miyabisun
  * [ConoHa CLI でVPSインスタンスをドカドカ建てる @miyabisun](https://qiita.com/miyabisun/items/558cede20bbbede2fdbb)
  * [github: ConoHa CLI @miyabisun](https://github.com/miyabisun/conoha-cli)

* ConoHa CLI (python3) @yuuki0xff(@yuuki)
  * 2016-09-19 [pypi: conoha-cli は ConoHa API のコマンドラインインターフェースとPython3用ライブラリです](https://pypi.org/project/conoha-cli/)
  * [github: ConoHa CLI (python3) @yuuki0xff(@yuuki)](https://github.com/yuuki0xff/conoha-cli)
  
* ConoHa ISO CLI (golang) @hironobu-s
  * [github: ConoHa ISO CLI (golang binary) @hironobu-s](https://github.com/hironobu-s/conoha-iso)
  

* ConoHa novassh console CLI (golang) @hironobu-s
  * https://github.com/hironobu-s/novassh
  

* ConoHa dns CLI (node.js) @N4RU5E
  * https://narusejun.com/archives/14/
  * https://github.com/kaz/conoha-dns
    * ConoHaのDNS APIをCLIから叩くやつを作った (ConoHa Advent Calendar 2016 24日目)

* Vagrant-conoha (ruby) @horonobu-s
  * https://github.com/hironobu-s/vagrant-conoha
  * https://qiita.com/hironobu_s/items/8422a427fd5571747196
    * VagrantからConoHaを使う
      - 016年06月13日に更新

* Vagrant-conoha + itamae
  * https://obel.hatenablog.jp/entry/20180110/1515555804
  * https://github.com/corselia/vagrant-conoha-with-itamae
    * コマンドラインから ConoHa のインスタンスを操作する（vagrant-conoha や ConoHa CLI を使い、さらに Itamae を使う）
    

* ConoHa docker-machine (docker-machine Version 0.5.0 or lator)
  * https://qiita.com/hironobu_s/items/db865ca43af8eca9d3ac
    * ConoHaでDocker Machineを使う


* ownCloud/NextCloud + ConoHa Object Storage @ukitiyan
  * https://qiita.com/ukitiyan/items/5e65cbe6b1a14439bc9c
    * 日本語対応な無制限ストレージ with 新しいConoHa Object Storage and ownCloud
      - 2016年01月14日に更新

* Terraform ConoHa
  * https://akichan.lolipop.io/2018/03/18/terrafromconoha/
  

* CLI nova
  * https://sirrow.info/archives/556


* ConoHa API
  * https://github.com/ezaki/chap
    - CHAP - ConoHa API for PHP
    - 6 Jan 2016 / ezaki

* API by PowerShell
  * https://www.gmo.jp/report/single/?art_id=224
    - PowerShellでConoHaをどうにかしてみる-Vol.1
    - ConoHa APIを使ってPowerShellのオリジナルコマンドでサーバー管理
    - 2018年2月21日(水)公開 / 樋口 勝一

  * https://www.gmo.jp/report/single/?art_id=225
    - PowerShellでConoHaをどうにかしてみる-Vol.2
    - 2018年3月28日(水)公開 / 樋口 勝一

  * https://www.gmo.jp/report/single/?art_id=226
    - PowerShellでConoHaをどうにかしてみる-Vol.3
    - 2018年4月18日(水)公開 / 樋口 勝一


* ConoHa DNS
  * https://access-jp.co.jp/blogs/development/234
    - ConoHa DNS API を Bash で試す
    - 2018-06-29 / Access Japan (開発室員)

  * https://www.npmjs.com/package/conoha-dns
    - conoha-dns CLI

* ConoHa Mail
  * https://blog.takekoshi.net/conoha-mailserver-api-webhook/
    - ConoHa APIを使ってみた：メールサーバでwebhook
    - takekoshi2015年7月10日

  * https://syobon.jp/2017/11/14/build-mail-server-using-conoha/
    - ConoHa でメールサーバーを簡単に構築する
    - 2017/11/14, @syobon_blog

  * https://qiita.com/ezaki/items/e7fe510b57b08170838b
    - ConoHa の メール API でアドレスの登録・一覧・削除をする。
    - @ezaki / 2017年01月31日に更新 / 2015年12月21日に投稿

  * https://packagist.org/packages/xzxzyzyz/laravel-conoha-api
    - ConohaのAPIをLaravelで利用する (メール) (Laravel 5.5+)
    - 2018/01/23 / Xzxzyzyz

* Object Storage
  * http://blog.kokuyouwind.com/archives/1129
    - ConoHaのオブジェクトストレージをPaperclipから使う
    - 2015年7月26日 / KOKUYOUWIND


## Compairing

* 2015/11/??
  * https://server-domain.info/report/conoha-rentaled-201511.html
    - ConoHaを借りてみたので、さくらのVPSと機能を比べてみた
    - 2015/11/?? phpとmysql が使えるレンタルサーバー・ドメイン選びのポイント


## installing

* wordpress
  * [ConohaサーバーへWordPressをインストールするまでの全行程（１）Conohaサーバーの立ち上げ](https://blog.ncrs.jp/conoha%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC%E3%81%B8wordpress%E3%82%92%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E3%81%99%E3%82%8B%E3%81%BE%E3%81%A7%E3%81%AE%E5%85%A8%E8%A1%8C%E7%A8%8B/)

  * [KUSAGANI for ConoHa](https://kusanagi.tokyo/cloud/kusanagi-for-conoha/)
  * [KUSANAGI(WordPress)の初期設定](https://kusanagi.tokyo/document/kusanagi-init/)
  * [KUSANAGI(WordPress)のプロビジョニング](https://kusanagi.tokyo/document/kusanagi-provision/)

* concrete5
  * [concrete5アプリケーションイメージの使い方](https://www.conoha.jp/guide/concrete5.php)


## Linux Desktop
* Linux desktop
  * [ConoHa Advent Calendar 25日目：ConoHa APIで、このはシンクライアントを試作する](http://shimadah.blogspot.com/2016/12/conoha-advent-calendar-25conoha-api.html)

## Windows Server
* Windows Container
  * 2018-04-25 [ConoHa が Windows Server に対応したので契約してみた](https://blog.shibayan.jp/entry/20180425/1524589641)

* benchmark
  * 2018-04-24 [ConoHa for Windows Server がリリースされたので、Windows Server 2016 の動作検証をしてみた](https://blog.oyasu.info/2018/04/24/6471/)

## user monitoring

* zabbix
  * 2015/12/23, @2bobobo [Zabbixでこのはちゃんを監視するお話](http://www.zumwalt.info/blog/2015/12/conoha-0san/)

* conoha API graph
  * 2017-12-14 [PrometheusでConoHa APIからメトリクスを取得してみる](https://trap.jp/post/334/)

* billing API monitoring
  * https://yoku0825.blogspot.com/2015/12/conohabilling-alert.html


## ConoHa1 to ConoHa2 migration or Cloud image migration

* migration by dump
  * http://www.zumwalt.info/blog/2015/05/migrate_newconoha/
    - 旧ConoHaから新ConoHaにサーバー丸ごと移行する方法
    - 2015/05/28 / 2bobobo

* AWS to ConoHa
  * https://makotoiwasaki.com/2016/12/aws-to-conoha.html
    - Amazon EC2 から ConoHa に移転する
    - 2016/12/15 / maco

* conoha to google
  * https://makotoiwasaki.com/2018/01/google-compute-engine-from-conoha.html
    - 無料 Google Compute Engine に ConoHa から丸ごと移転する方法
    - 2018/01/11 / maco



## Advent Calender

* 2015
  * https://qiita.com/advent-calendar/2015/conoha
* 2016
  * https://qiita.com/advent-calendar/2016/conoha
* 2017
  * https://qiita.com/advent-calendar/2017/conoha


