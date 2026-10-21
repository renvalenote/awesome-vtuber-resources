# Awesome VTuber Resources

[English](README.md) · **日本語**

VTuber活動に役立つツール、チュートリアル、検索サービス、クリエイター向けリソースをまとめたリンク集です。モデル制作、トラッキング、配信の準備から、作品を手がけたクリエイターを探すところまで、目的に合う入口を紹介します。

## はじめに

- **モデルを作りたい：** [モデル制作](#モデル制作)と[学習リソース](#学習リソース)から始めましょう。
- **配信を始めたい：** [トラッキングと配信](#トラッキングと配信)で、モデルに対応するアプリを探しましょう。
- **制作を依頼したい・素材を探したい：** [制作依頼・素材・利用条件](#制作依頼素材利用条件)を確認してください。
- **VTuberや制作実績を知りたい：** [VTuber検索と公開クレジット](#vtuber検索と公開クレジット)を参照してください。
- **連携機能を開発したい：** [開発者向けリソース](#開発者向けリソース)を確認してください。

言語表記はリンク先のサイトやドキュメントの言語を示します。アプリの全機能がその言語に対応していることを保証するものではありません。対応環境、料金、利用条件の最新情報は公式サイトで確認してください。

## 目次

- [モデル制作](#モデル制作)
- [トラッキングと配信](#トラッキングと配信)
- [学習リソース](#学習リソース)
- [制作依頼・素材・利用条件](#制作依頼素材利用条件)
- [VTuber検索と公開クレジット](#vtuber検索と公開クレジット)
- [開発者向けリソース](#開発者向けリソース)
- [掲載方針と追加・修正の提案](#掲載方針と追加修正の提案)

## モデル制作

- [Live2D Cubism](https://www.live2d.com/) — イラストをもとに2Dモデルを制作し、動きを付けるためのソフトウェア。イラストレーターやLive2Dモデラーの制作の入口に。**サイト：英語・日本語。**
- [VRoid Studio](https://vroid.com/studio) — 人型の3Dキャラクターを制作し、対応アプリで使えるVRMモデルとして書き出せるツール。**サイト：英語・日本語。**
- [Inochi Creator](https://github.com/Inochi2D/inochi-creator) — レイヤー分けした2Dイラストに動きを付け、VTuber活動などのリアルタイム用途に使うInochi2D形式のモデルを制作するエディター。ソースコードは[BSD-2-Clauseライセンス](https://github.com/Inochi2D/inochi-creator/blob/v0_8/LICENSE)で公開されていますが、ブランド素材には別の制限があることがリポジトリに明記されています。**リポジトリ：英語。**
- [Krita](https://krita.org/ja/features/) — 2Dモデル制作向けにパーツを分けたレイヤー付き原画を作成し、PSDファイルを書き出すための描画ツール。[PSD形式の制限](https://docs.krita.org/en/general_concepts/file_formats/file_psd.html)を確認し、使用するモデリングツールで読み込みをテストしてください。KritaはLive2Dの[読み込み確認済み描画アプリ](https://docs.live2d.com/en/cubism-editor-manual/precautions-for-psd-data/)には含まれていません。**サイト：英語・日本語。リンク先の互換性資料：英語。**
- [VRM Add-on for Blender](https://github.com/saturday06/VRM-Addon-for-Blender) — BlenderでVRMアバターを読み込み・編集・書き出しし、HumanoidやMToonの設定を行えるアドオン。使用するBlenderのバージョンに合った導入手順を参照してください。**リポジトリ：英語・日本語。**

## トラッキングと配信

導入前に、モデルの形式と使用するトラッキング機器がアプリの要件に合っているか確認してください。

- [VTube Studio](https://denchisoft.com/) — フェイストラッキングでLive2Dモデルを動かし、表情や小物、シーン内の動作を制御するアプリ。[公式ドキュメント・APIリポジトリ](https://github.com/DenchiSoft/VTubeStudio)はプラグイン開発にも利用できますが、アプリ本体のソースコードではありません。**サイト：英語。**
- [VSeeFace](https://www.vseeface.icu/) — 64ビットWindowsでフェイストラッキングによりVRM 0アバターを動かし、VMC経由でトラッキングデータを送受信するアプリ。VRM 1.0は非対応で、追加の手のトラッキングにはLeap Motion機器が必要です。**サイト：英語。**
- [Warudo](https://www.warudo.app/) — アバター、背景、小物、インタラクションを組み合わせて3D VTuberの配信シーンを構築するアプリ。初期設定と対応トラッキング方式は[公式ハンドブック](https://docs.warudo.app/jp/docs)を参照してください。**ハンドブック：英語・日本語。**
- [veadotube mini](https://veado.tube/) — マイク入力に反応する画像でPNGTuberアバターを作り、まばたきや表情の切り替えを設定できるアプリ。[公式の使い方ガイド](https://veado.tube/docs/usage/mini/)と[OBSへの取り込みガイド](https://veado.tube/docs/usage/obs/)も参照してください。**サイト・ドキュメント：英語。**
- [nizima LIVE](https://nizimalive.com/) — Webカメラや連携するiPhone用トラッカーでLive2Dモデルを動かす、Live2D社のトラッキングアプリ。パラメータ調整やコラボ機能も備えています。マーケットプレイスのnizimaとは別のサービスです。**サイト：英語・日本語。**
- [OBS Studio](https://obsproject.com/) — アバターアプリの映像とゲーム画面、音声、オーバーレイを組み合わせ、ライブ配信や録画を行うソフトウェア。[VTube Studioのガイド](https://github.com/DenchiSoft/VTubeStudio/wiki/Recording-Streaming-with-OBS)など、使用するアバターアプリの取り込み手順を参照してください。**サイト：英語・日本語ほか。リンク先ガイド：英語。**
- [わんコメ（OneComme）](https://onecomme.com/) — 複数の配信サイトのコメントをまとめて取得し、読み上げ、コメント表示、参加型配信の順番管理を行えるアプリ。[公式ドキュメント](https://onecomme.com/docs/about/)と[利用規約](https://onecomme.com/terms/)を参照してください。無料版は原則クレジット表記が必要で、例外もあります。一部機能・テンプレートは有料です。**リンク先サイト・ドキュメント：日本語。**
- [VNyan](https://suvidriel.itch.io/vnyan) — VRM、VRM 1.0、VSFAvatarモデルを使えるWindows向けVTuberアプリ。ノードグラフで視聴者とのインタラクションを組み、OBSのイベントとも連携できます。**製品ページ：英語。**
- [VDO.Ninja](https://vdo.ninja/) — 遠隔のコラボ相手の映像と音声をOBSへ取り込むサービス。VTuberのアバター映像には、同プロジェクトの追加Windowsアプリ[Game Capture](https://github.com/steveseguin/game-capture/blob/main/docs/windows-guide.md)でVTube StudioやVSeeFaceなどのSpout2出力をVDO.Ninja経由で送れます。アルファチャンネルによる透過表示には通常のブラウザーソースではなく、VDO.Ninja OBSプラグインの実験的なネイティブ受信機能が必要です。**サイト・ドキュメント：英語。**
- [Streamer.bot](https://streamer.bot/) — チャットや配信プラットフォームのイベントから、アバターやシーンの操作を実行するツール。[VTube Studio連携](https://docs.streamer.bot/guide/integrations/vtube-studio)でモデル、表情、ホットキーを操作し、OBSの制御とも組み合わせられます。Windows向けで、[macOS・Linuxでの導入](https://docs.streamer.bot/get-started/installation)は実験的です。**サイト・ドキュメント：英語。**

- [OBS Spout2 Plugin](https://github.com/Off-World-Live/obs-spout2-plugin) — VTube StudioやVSeeFaceの設定画面を映さず、透過したアバター映像をOBSへ取り込む64ビットWindows向けプラグイン。使用するOBSのバージョンに対応したリリースが必要です。アプリごとの設定は[VTube Studioの取り込みガイド](https://github.com/DenchiSoft/VTubeStudio/wiki/Recording-Streaming-with-OBS)または[VSeeFaceのガイド](https://www.vseeface.icu/spout)を参照してください。**リポジトリ・ガイド：英語。**

## 学習リソース

- [Live2D Cubism チュートリアル](https://docs.live2d.com/cubism-editor-tutorials/top/) — イラストの準備から表情、体の動き、アニメーションまで、モデル制作の流れを学べる公式教材。**ドキュメント：英語・日本語。**
- [VRMドキュメント](https://vrm.dev/en/) — VRM形式と関連ツール、形式のバージョンによる違い、モデルの利用許諾について学べる公式資料。**ドキュメント：英語・日本語。英語版のURL配下にも未翻訳の日本語ページがあります。**
- [OBS Studio Quick Start Guide](https://obsproject.com/kb/quick-start-guide) — 自動構成、シーンへのソース追加、音声設定、本番配信前のテスト録画まで、初回配信の準備を学べる公式ガイド。**ガイド：英語。**

## 制作依頼・素材・利用条件

掲載サービスは、依頼先や素材を探すための入口です。商用利用、クレジット表記、改変、独占利用、再配布の条件は、各クリエイターや権利者に確認してください。サービスの掲載は、そこに出品されているすべての作品や出品者を推奨するものではありません。

- [VGen](https://www.vgen.co/) — モデル用イラスト、Live2Dモデリング、配信用グラフィックなどの制作を依頼できるクリエイターを探せるサービス。実績、納品内容、依頼条件は個別に確認してください。**サイト：英語。**
- [nizima](https://nizima.com/) — Live2D公式のマーケットプレイスで、Live2Dモデルやイラストを探せるサービス。作品ごとの利用条件を確認してください。**サイト：日本語。**
- [VRoid Hub](https://hub.vroid.com/en) — 3Dキャラクターとその利用条件を閲覧できるサービス。モデルが公開されていても、ダウンロード、配信利用、再配布が許可されているとは限りません。**サイト：英語・日本語。**
- [Live2D サンプルモデル](https://www.live2d.com/learn/sample/) — 公式サンプルモデルの構造を学ぶための資料。自身の制作物に使用する前に、対象データの利用規約を確認してください。**サイト：英語・日本語。**
- [ホロライブプロダクション 二次創作ガイドライン](https://hololivepro.com/terms/) — ホロライブ関連の二次創作を行う際に確認する権利者の公式ガイドライン。他のクリエイターの作品への利用許諾を与えるものではありません。**ガイドライン：英語・日本語。**
- [BOOTH](https://booth.pm/ja) — クリエイターのショップから3Dモデル、テクスチャ、配信素材を探せるマーケット。購入・使用前に、各商品の形式、対応アプリ、制作者が定める利用条件を確認してください。**サイト：英語・日本語。商品説明の言語は出品ごとに異なります。**

## VTuber検索と公開クレジット

検索サービスやデータベースで手がかりを見つけたら、元のプロフィール、告知、ポートフォリオを確認してください。キャラクターデザイン、イラスト、Live2Dモデリング、3Dモデリング、衣装ごとの制作担当は区別します。一つの担当表記から、他の工程も同じ人が担当したと推測しません。

- [Holodex](https://holodex.net/) — VTuberの配信や動画を探せるサービス。[公式フロントエンドリポジトリ](https://github.com/HolodexNet/Holodex)でプロジェクト情報とソースコードを確認できます。**リポジトリ：英語。**
- [ホロライブ公式タレントプロフィール](https://hololive.hololivepro.com/talents/) — 公式プロフィールと、掲載されているイラストレーターのクレジットを確認できるページ。たとえば[一伊那尓栖のプロフィール](https://hololive.hololivepro.com/en/talents/ninomae-inanis/)にはイラストレーターが記載されていますが、制作担当者全員を網羅した一覧ではありません。**サイト：英語・日本語。**
- [VTuber図鑑](https://vtuberzukan.com/) — VTuber、クリエイター、会社・事務所・団体の項目を備えたディレクトリ。**サイト：日本語・英語・中国語。掲載内容は言語によって異なります。関係性の開示：本リストの管理者が手がけるプロジェクトです。**

## 開発者向けリソース

- [UniVRM](https://github.com/vrm-c/UniVRM) — UnityでVRMアバターを読み込み・書き出しするための実装。VRMコンソーシアムのGitHub Organizationで管理されています。**ドキュメント：英語・日本語。**
- [three-vrm](https://github.com/pixiv/three-vrm) — Three.jsを使ったWebアプリでVRMアバターを読み込み、扱うためのライブラリ。**リポジトリ：英語。**
- [VMC Protocol](https://protocol.vmc.info/english.html) — 対応アプリ間でモーションや表情のデータをやり取りするための、OSCを利用した公開プロトコル仕様。**仕様書：英語・日本語。**

## 掲載方針と追加・修正の提案

実用的な用途があり、提供元と一次情報が確認できるリソースを優先します。汎用ツールもVTuber活動での用途が明確であれば対象です。転載サイトより、公式製品ページ、公式ドキュメント、クリエイター自身のページを優先します。

リソースを提案する際は、次の点を確認してください。

1. 正式なURLと、どのような作業に役立つかを簡潔に記載する。
2. 適切なカテゴリを選び、既存の項目と重複していないか確認する。独立した学習資料としての用途がなければ、ドキュメントは既存項目にリンクを追加する。
3. サイトやドキュメントの言語を明記する。同じカテゴリの別製品から、対応OS、料金、ライセンスを推測しない。
4. 制作クレジットには、VTuber本人、権利者、または担当クリエイターによる公開情報を示す。分かる範囲で担当工程とモデル・衣装のバージョンを明記し、不明な担当は補完しない。
5. プロジェクトとの関係を開示し、英語版と日本語版の内容を揃える。

非公開の個人情報、前世・転生・別名義についての推測、流出データや無断配布モデル、本人の許可なく作られた音声クローン素材は掲載対象外です。声、外見、交友関係から人物の同一性を推測しません。

