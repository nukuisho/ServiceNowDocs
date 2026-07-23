# Integrate Strategic Portfolio Management (SPM) with Enterprise Architecture (EA)

**Lab 6.01** 15m

## Lab objectives

The Ideation Domain is a net new addition to CSDM 5. It represents the ideas, concepts and considerations for both the creation of new or additional services as well as improvements and enhancements around existing services. Additionally, it represents the strategic efforts of the organization to provide value to its customers. Common personas in this domain include product owners.

In this lab, you achieve the following objectives:

- Configure a product idea with a planning item
- Link a product idea and planning item to a business application
- Configure the business application form to view associated product ideas and planning items

Design & Planning and Ideation & Strategy Domain

## A. Configure Product Idea and Planning Item

For new products or existing products, everything begins because a new request arises due to a product idea, the need to digitalize a business process or capability, or the product owner receives feedback to improve the product, based on the service offered.

These initial actions are done in the Ideation and Strategy domain, and the ServiceNow solution used is Strategic Portfolio Management.

1.  Navigate to the **Strategic Planning Workspace.**

1.  Close any pop-up windows if displayed.

1.  Select the **Feedback** icon.

1.  From the **Welcome to Feedback!** dialog window, select **Got it**.

1.  Select the **Product Ideas** tab.

**Note**_: A product idea can represent a complete product, feature, enhancement, change proposal or suggestion that can be curated and/or promoted into a demand, project, epic, or story. Product ideas are recorded in the Product Idea \[sn_align_core_product_idea\] table extended from the Planning Item table._

1.  Select the **New product idea** button.

1.  In the **Name** field, enter **CD-Product Idea**.

**Note:** _The product owner, enterprise architect or other users register a new Product Idea based on feedback received or a business requirement._

1.  Select **Submit**.

1.  Select the **Lists** icon.

1.  Under **Planning items**, select **Demands**.

**Note:** _A Planning Item represents any type of work that can be aligned to business goals, planned, and executed. It can be of different types such as demands, projects, epics, or custom work items defined by the organization with their own life cycle._

_Planning Items can be grouped into portfolio structures (provided out of the box in the CSDM) to support investment decisions for both new and ongoing work that drive strategic objectives. All Planning Items are stored in the Planning Item \[sn_align_core_planning_item\] table or tables such as Demands \[sn_align_core_demand\], which extend this table._

**Note**_: The following tables extend the Planning Item table._

1.  From the **Demands** list under **Planning Items**, select **New**.

**Note:** _The initial evaluation of the product idea indicates its potential value for the product, leading the product owner to convert it into a planning item._

1.  In the **Name** field, enter **CD-Demand.**
2.  From the **Create New Demand** form, under the **Details** section, in the **Business application**

field, enter **CD-Business Application**.

1.  Select **Save**.

1.  Navigate back to the **Product Ideas** list.

1.  From the **Product Ideas** list, search for and open the **CD-Product Idea** record.

1.  From the top right, select the **Link capability** button and select **Link demand**.

1.  Search for and checkmark the demand you just created called **CD-Demand**.

1.  Select **Confirm**.

1.  From the **CD-Product Idea** record, select the **Planning items** tab to view the linked demand.

**Note**_: The demand shows up in the Planning Item column because a demand is just one of many types of planning item._

1.  Select **Save**, then navigate back to the **Product Ideas** list.

1.  Select the **Personalize List** icon.

1.  Search for and checkmark **Business Application** to add it as a new column to the list.

**Note_:_** _The product owner collaborates with the Enterprise architect on the idea, and if it pertains to an existing business application, the idea is assigned to a business application record._

1.  Select **Apply**.

1.  From the **CD-Product Idea** record, double-click in the **Business application** field and enter

**CD-Business Application**, then select **Apply**.

**Note**_: A product idea and planning item have both been created and linked to a business application. The product idea and planning item can be related to an existing business application or a net new business application._

## Configure Business Application View

Design & Planning is a CSDM Domain that represents those tables currently used by Enterprise Architecture EA (formerly known as Application Portfolio Management APM). In this section you configure the business application form to provide visibility to the associated product ideas and planning items created within the Ideation and Strategy domain.

1.  Navigate to the **Enterprise Architecture Workspace**.

1.  Under the **Portfolio Overview** section, select and open the **Business applications** tile.

1.  Search for and open the **CD-Business Application** record.

**Note**_: Currently the business application view does not display any linked product ideas or planning items. The workspace view currently only has tabs for CI Scores and Ideas._

1.  From the upper right, select the **More Actions** icon.

1.  Select **View form in core UI**.

1.  From the **Business Application** form, select the **Additional actions** menu and select **View > Default view**.

**Note**_: This is the view that represents the view seen within the workspace as it also contains just the CI Scores and Ideas tabs._

1.  Select the **Additional actions** menu and select **Configure > Related Lists**.

1.  Search for and add **Planning Item -> Business application** to the **Selected** pane.

1.  Select **Save**.

1.  Select the **Planning Items** related list and notice the associated planning items are displayed.

**Note**_: Both the demand and product idea display as both records are stored in tables that extend the Planning Item table._

1.  Navigate back to the **CD-Business Application** form within the Enterprise Architecture Workspace.

1.  Refresh the form.

1.  Select the new **Planning Items** tab and verify both the associated product idea and demand are displayed also from the workspace.

In summary, by following CSDM guidelines and linking strategy (ideas, demands, planning) to its associated business application provides application owners with the advantage to see what new ideas and planned work are tied to their application without the need to navigate to multiple modules or workspaces to view the data.

When reviewing a business application, owners can instantly understand what’s in the pipeline, and what new features, upgrades, or modernization efforts are in the works. In addition, if an application is slated for retirement, it can avoid wasted planning efforts.

## Lab Complete

**Congratulations! You have completed this lab.**
# CSDM の概要

**ラボ 1.01** 30 分

**ラボの目標**

Common Service Data Model (共通サービスデータモデル (CSDM)) は ServiceNow の製品およびプラットフォーム全体で共有される、サービス関連の定義に関する標準セットです。真のサービスレベル管理の実現をサポートするとともに、サービスモデリングに関する規範的ガイダンスを提供します。 これらのサービス関連定義は、ServiceNow® 製品ポートフォリオと ServiceNow AI Platform® の両方にまたがって適用されます。

このデータモデルは、製品およびプラットフォーム全体にわたるフレームワークとして機能し、複数の構成および管理戦略を可能にするとともに、それらの実行をサポートします。標準提供 (OOB) されるテーブル、リファレンス、リレーションシップを用いた、データを適切にモデリングするための現在のベストプラクティスも含まれています。 多くの ServiceNow 製品は、このデータモデル内のデータに依存しています。

このラボでは、Cloud Dimensions (CD) サービスのうち 1 つを対象にサービスモデリングを行い、そこから得られるさまざまな成果を確認します。

このラボで達成する目標は、次のとおりです。

- CSDM Data Foundations Dashboard (CSDM のデータファンデーションダッシュボード) を分析する
- 基盤データを作成する
- ビジネスアプリケーションと機能を構成する
- ビジネスサービスとビジネスサービスオファリングを構成する
- 技術管理サービスと技術管理サービスオファリングを構成する

- Service Instance (サービスインスタンス) を作成し、関連するサービス、オファリング、およびビジネスアプリケーションのリレーションシップを構成する

**重要**： このラボの目的は、AI Platform 内で相互に連携するServiceNow 製品スイート全体に依存することなく、Common Service Data Model (CSDM) の概要を理解することです。具体的には、主要なドメイン、要素、テーブル、レコードに加え、それらがどのように関連付けられているかを扱います。 たとえば、このラボではサービスを手動で作成しますが、ServiceNow の Service Mapping (サービスマッピング) などのツールを使用すると、実際のシナリオではこのプロセスを自動化できます。 同様に、CSDMアプリケーションから直接ビジネスアプリケーションを作成します。これらのテーブルは通常、Enterprise Architecture (エンタープライズアーキテクチャ) (旧 Application Portfolio Management (アプリケーションポートフォリオ管理)) で使用されます。

# CSDM Data Foundations Dashboard (CSDM のデータファンデーションダッシュボード)

ServiceNow の CSDM Data Foundations Dashboard は、ServiceNow が提示する推奨プラクティスに基づいて、組織による Common Service Data Model (CSDM) の実装状況を評価し、改善につなげるためのビルトインの可視化およびレポート作成ツールです。

このダッシュボードは、CSDM 実装の健全性を診断し、CMDB を完全に CSDM 準拠のモデルに成熟させるためのロードマップを提供します。これは、正確なサービスマッピング、影響分析、および IT 運用の効率化に不可欠です。

- 1.  **admin (アドミン)** ユーザーとして ServiceNow インスタンスにログインしていることを確認します。

**重要**： このラボではシステムアドミニストレーターとしてログインしますが、所属企業の環境では _CSDM_ オーナーなど、より具体的なロールが定義されている場合があります。

- 1.  ログイン後に **\[Work your way (自由にカスタマイズ)\]** バナーが表示された場合は、閉じます。

- 1.  メニューの左上にある **\[All (すべて)\]** を選択します。

- 1.  次に、ピンアイコンを選択して、左側のナビゲーションペインを固定します。

- 1.  **\[Configuration (構成)\] > \[CSDM Data Foundations Dashboard (CSDM のデータファンデーションダッシュボード)\]** に移動します。

**注：** 複数の _CSDM_ ドメインにまたがって作業し、_\[CSDM Data Foundations Dashboard (CSDM_ のデータファンデーションダッシュボード_)\]_ 上で良好な成果をもたらすベストプラクティスを用いて、サービスモデルを構成します。

- 1.  各タブを選択して、提供されるさまざまなメトリクスを確認します。

**注：** メトリクスは、左から右に進むにつれて、より成熟した _CSDM_ 実装をサポートする内容になっています。たとえば、_\[Foundation (_基盤_)\]_ タブのメトリクスは、_\[Fly (_フライ_)\]_ タブで提供されるメトリクスと比べて、顧客の _CSDM_ ジャーニーにおいて、より容易にサポートおよび実装できます。

# 基盤データを構成する

Foundation (基盤) ドメインは、他の CSDM ドメイン内のオブジェクトとの間で参照されるベースデータを格納するテーブルを表します。 Foundation ドメインに属するテーブルは CMDB リレーションシップには使用されず、 重要な参照データとして扱われます。 一部のシナリオでは、ServiceNow 製品の実装や CMDB の構築に先立って基盤データが必要になる場合があります。 Business Process (ビジネスプロセス) テーブルは CMDB テーブルですが、それ以外のテーブルは CMDB の外部に存在します。

このドメインにおける代表的なペルソナは、プロセスオーナー、データスチュワード、プロダクトオーナー、および契約マネージャーです。

このセクションでは、CSDM において基盤データと見なされるグループと場所を構成します。

## グループ

グループは、共通の目的や機能を持つユーザーをグループ化して管理するために使用されます。 グループには、変更要求の承認、インシデントの解決、通知の受信、作業指示タスクの完了などの責任をアサインできます。 CMDB では、グループは参照データとしても機能します。たとえば、Configuration Item (構成アイテム (CI)) の管理主体 (\[Managed by Group (管理担当者グループ)\]) やサポート提供者 (Support Group (サポートグループ)) を識別するために使用されます。グループに関連付けられたビジネスルール、アサインルール、ロール、または属性は、自動的にそのすべてのメンバーに適用されます。

- 1.  **\[User Administration (ユーザー管理)\] > \[Groups (グループ)\]** に移動します。

- 1.  **\[New (新規)\]** を選択します。

- 1.  **\[Name (名前)\]** フィールドに「**CD-Support Group (CD-サポートグループ)**」と入力します。

- 1.  レコードを保存します。

- 1.  **\[Group Members (グループメンバー)\]** 関連リストを選択します。

- 1.  **\[Edit (編集)\]** を選択します。

- 1.  「**System Administrator (システムアドミニストレーター)**」を検索して選択し、**\[Group Members List (グループメンバーリスト)\]** ペインに追加します。
    2.  **\[Save (保存)\]** を選択します。

**注**： グループを _CI_ またはサービスオファリングの _\[Support Group (_サポートグループ_)\]_フィールドに関連付けると、インシデントルーティングを簡素化できます。これは、ラボの後半で説明するように、新しいインシデントの _\[Assignment Group (_アサイン先グループ_)\]_ フィールドが自動的に設定されるためです。

- 1.  フォームを再ロードし、**\[Groups Members (グループメンバー)\]** 関連リストの下に **\[System Administrator (システムアドミニストレーター)\]** が表示されていることを確認します。

- 1.  先ほどの手順を参考に、2 つ目のグループを作成します。

- - - Name (名前)： **CD-Change Group (CD-変更グループ)**

- - - Groups Members (グループメンバー)： **System Administrator (システムアドミニストレーター)**

**注**：グループを _CI_ またはサービスオファリングの _\[Change Group (_変更グループ_)\]_ フィールドに関連付けると、変更ルーティングを簡素化できます。これは、ラボの後半で説明するように、新しい変更要求の _\[Assignment Group (_アサイン先グループ_)\]_ フィールドが自動的に設定されるためです。

## Locations (場所)

\[Locations (場所)\] テーブルは、地理的な位置を定義するために使用されます。組織のレポートニーズに合わせて、Parent (親) 属性を使用して場所の階層を構成できます。たとえば、この階層には地域、都市、建物、部門などを含めることができます。

より詳細なレポートが必要な場合は、階層を拡張して、フロア、ルーム、データセンターなどの具体的な領域を含めることができます。 階層構造のサポートと信頼できるソースデータ、明確な要件が揃えば、正確で意味のある場所レコードを作成し、現在および将来のレポートニーズをサポートすることができます。

1.  **\[User Administration (ユーザー管理)\] > \[Locations (場所)\]** に移動します。

1.  **\[New (新規)\]** を選択します。

1.  指定された情報に従ってフォームを構成します。

- - Name (名前)： **CD-Parent Location (CD-親の場所)**

1.  **\[Submit (送信)\]** を選択します。

1.  **\[New (新規)\]** を選択して、子の場所を作成します。

1.  指定された情報に従ってフォームを構成します。

- - Name (名前)： **CD-Child Location (CD-子の場所)**

- - Parent (親)： **CD-Parent Location (CD-親の場所)**

1.  **\[Submit (送信)\]** を選択します。

**注**： 場所の階層構造が正常に作成されました。これにより、場所が _CI_ レコードにリンク されている場合のレポート機能が大幅に強化されます。 先ほど表示した _\[CSDM Data Foundations Dashboard (CSDM_ のデータファンデーションダッシュボード_)\]_ には、 _\[Locations with Parents (_親が設定されている場所_)\]_ というメトリクスが含まれています。このメトリクスは、場所データと階層構造への準拠状況に関するインサイトを提供します。

# Design and Planning (設計と計画) ドメイン

Design and Planning は、Enterprise Architecture (エンタープライズアーキテクチャ) EA (旧 Application Portfolio Management (アプリケーションポートフォリオ管理) APM) で現在使用されているテーブルを表すCSDM ドメインです。これらのテーブルは設計と計画に使用されるため、テーブル内のレコードはITSM プロセス (インシデント管理、問題管理、および変更管理) の直接の対象にはなりません。 これらのテーブルは、ビジネスで展開および利用されるエンタープライズアプリケーションの論理設計を表します。

**Design and Planning ドメインの全体像**：新しいサービスをどのように構築するか、また、そのために何が必要かを示します。 ペルソナには、エンタープライズアーキテクトやデジタルプロダクトオーナーが含まれます。

## ビジネスアプリケーション

ビジネスアプリケーションとは、アプリケーションのインベントリ/ポートフォリオとそのメタデータを表します。 ビジネスアプリケーションについて、以下のことを理解しておくことが重要です。

- 運用 CI ではなく、インシデント、問題、または変更では使用しないこと

- 特定バージョンに依存しないこと

- 1.  **\[CSDM\] > \[Design (デザイン)\] > \[Business applications (ビジネスアプリケーション)\]** に移動します。

- 1.  **\[New (新規)\]** を選択します。

- 1.  指定された情報に従ってフォームを構成します。

- - - Name (名前)： **CD-Business Application (CD-ビジネスアプリケーション)**

- - - Application Type (アプリケーションタイプ)： **COTS**

- - - Architecture type (アーキテクチャタイプ)： **Web Based (Web ベース)**

- - - Description (説明)： **CD-Business Application (CD-ビジネスアプリケーション)**

- - - Application Category (アプリケーションカテゴリ)： **Customer Support (カスタマーサポート)**

**注**： _COTS_ は _Commercial Off The Shelf (_既製品_)_ の略で、社内開発ではなく、購入したアプリケーションを指します。

- 1.  **\[Owners (オーナー)\]** タブを選択します。

- 1.  **\[IT Application owner (IT アプリケーションオーナー)\]** フィールドに「**Abel Tuter**」と入力します。

- 1.  **\[Submit (送信)\]** を選択します。

## Business Capability (ビジネス機能)

ビジネス機能とは、組織がビジネスモデルを実行し、ミッションを遂行するために必要な高レベルの機能を表します。 これらの機能を使用することで、ビジネスアプリケーションおよびビジネスサービスのコストを合理化し、優先順位付けを効果的に行うことができます。

1.  **\[CSDM\] > \[Design (デザイン)\] > \[Business capabilities (ビジネス機能)\]** に移動します。

1.  **\[New (新規)\]** を選択します。

1.  **\[Name (名前)\]** フィールドに「**CD-Capability (CD-機能)**」と入力します。

1.  レコードを保存します。

1.  **\[Related Items (関連アイテム)\]** の右側にあるプラス記号を選択します。

**注**： サービスをさまざまな製品の観点から表示する際に、有益なインサイトを得るためのリレーションシップを設定できます。

1.  指定された情報に従って、**\[Relationship Editor (リレーションシップエディター)\]** を構成します。

- - Suggested Relationship types (提案されたリレーションシップタイプ)： **Provided by (Parent) (提供者 (親))**
    - Filter (フィルター)：**Business Application.Name | starts with | CD (ビジネスアプリケーション名 | 次の値で始まる | CD)**

**注**： フィルターには、条件の選択方法に応じて、_\[Name (_名前_)\]_ または _\[Business Application.Name (_ビジネスアプリケーション名_)\]_ が表示されます。 _CD-Business Application_ を正常に検索できていれば、このステップは正しく完了しています。

1.  **\[Run filter (フィルターを実行)\]** を選択します。

1.  **\[CD-Business Application (CD-ビジネスアプリケーション)\]** の左側にあるチェックボックスをオンにします。

1.  フォームの右下にあるプラス記号を選択し、リレーションシップを追加します。

1.  **\[Save and Exit (保存して終了)\]** を選択し、**\[OK\]** を選択します。

#### \[Show dependency views (依存関係ビューを表示)\] を選択し、

**当該機能** と **\[Business Application (ビジネスアプリケーション)\]** の間に構成された新しいリレーションシップを表示します。

1.  次のセクションに進む前に、**\[Dependency Views (依存関係ビュー)\]** ブラウザタブを閉じます。

## Information Object (情報オブジェクト)

情報オブジェクトとは、アプリケーションやサービスによって使用または管理されるビジネス関連データやデジタルコンテンツの概念的な表現です。 CSDM (Common Service Data Model) のコンテキストでは、情報オブジェクトは、ビジネスアプリケーションやサービスが生成、使用、または管理する「データ」を表現する上で重要な役割を果たします。 例としては、顧客データ、財務取引、医療記録、ドキュメントやファイルなどがあります。

1.  **\[CSDM\] > \[Design (デザイン)\] > \[Information object (情報オブジェクト)\]** に移動します。

1.  **\[New (新規)\]** を選択します。

1.  **\[Name (名前)\]** フィールドに「**CD-Information Object (CD-情報オブジェクト)**」と入力します。

1.  **\[Submit (送信)\]** を選択します。

1.  **\[CSDM\] > \[Design (デザイン)\] > \[Business applications (ビジネスアプリケーション)\]** に移動します。

1.  「**CD-Business Application (CD-ビジネスアプリケーション)**」を検索して開きます。

1.  **\[Related Items (関連アイテム)\]** の右側にあるプラス記号を選択します。

**注**： サービスをさまざまな製品の観点から表示する際に、有益なインサイトを得るためのリレーションシップを設定できます。

1.  指定された情報に従って、**\[Relationship Editor (リレーションシップエディター)\]** を構成します。

- - Suggested Relationship types (提案されたリレーションシップタイプ)： **Uses (Parent) (使用 (親))**
    - Filter (フィルター)： **Class | is | Information Object (クラス | is | 情報オブジェクト) AND Name | starts with | cd (名前 | 次の値で始まる | cd)**

1.  **\[Run filter (フィルターを実行)\]** を選択します。

1.  **\[CD-Information Object (CD-情報オブジェクト)\]** の左側にあるチェックボックスをオンにします。

1.  フォームの右下にあるプラス記号を選択し、リレーションシップを追加します。

1.  **\[Save and Exit (保存して終了)\]** を選択し、**\[OK\]** を選択します。

1.  **\[Show dependency views (依存関係ビューを表示)\]** を選択し、**\[Business Capability (ビジネス機能)\]**、 **\[Information Object (情報オブジェクト)\]**、および **\[Business Application (ビジネスアプリケーショ ン)\]** 間で構成された新しいリレーションシップを表示します。

# Service Consumption (サービス消費) ドメイン

サービス消費は、Service Portfolio Management (サービスポートフォリオ管理) (SPM) および Customer Service Management (カスタマーサービス管理) (CSM) で現在使用されているテーブルを表す CSDM ドメインです。さらに、Service Delivery (サービスデリバリ) ドメインの要素を販売または消費する可能性があるサービスのビジネスポートフォリオも表します。\[Service Consumption (サービス消費) \] の各テーブルは「運用」テーブルであるため、インシデント、問題、変更などの ITSM プロセスで選択可能です。

**Service Consumption ドメインの全体像**： 人々がサービスを利用できるよう支援し、それらが適切に機能しているかどうかを測定します。 ペルソナには、事業関係マネージャーおよびカスタマーサービスマネージャーが含まれます。

## ビジネスサービスおよびビジネスサービスオファリング

ビジネスサービスとビジネスサービスオファリングは、CSDM における Service Consumption ドメインの主要コンポーネントであり、サービスがビジネスにどのように提供され、ビジネスによってどのように消費されるかを表します。

ビジネスサービスは、ビジネスユーザーに公開されるサービスタイプで、通常は 1 つ以上のビジネス機能をサポートする役割を果たします。ビジネスサービスは、多くの場合、ビジネスユーザーが要求できるサービスです。 ビジネスユーザーは、要求カタログを使用して、目的のオファリングとサービスコミットメントレベルを選択できます。 ビジネスサービスは、1 つ以上のビジネスサービスオファリングで構成されています。

ビジネスサービスオファリングは、Service Portfolio Management (SPM) を構成する際の起点となります。 Service Offerings (サービスオファリング) (SO) は、可用性、スコープ、価格設定などの観点から、サービスのレベルを一意に定義する 1 つ以上のサービスコミットメントで構成されています。 たとえば、組織内で 2 つのレベルのデスクトップサポートを提供している場合があります。「スタンダード」ではアップグレードとウイルス保護を提供し、「エグゼクティブ」ではスタンダードのコミットメントに加えて、平日 8 ～ 17 時の間は 30 分以内に応答するなどの応答保証を提供します。

ビジネスサービスとビジネスサービスオファリングは、フォームやリストを使用して作成することも、 Service Builder (サービスビルダー) を使用してより簡単に作成することもできます。 このセクションでは、Service Builder を使用してサービスとオファリングを定義します。

- 1.  **\[Service Portfolio Management (サービスポートフォリオ管理)\] > \[Service Builder (サービスビルダー)\]** に移動します。

- 1.  右側のペインで、Service Builder に表示される情報を確認します。

#### \[Create a business service (ビジネスサービスの作成)\] を選択します。

- 1.  **\[Getting Started (はじめに)\]** ページで **\[Continue (続行)\]** を選択します。

- 1.  **\[Details (詳細)\]** タブの右側のペインで、サービスを定義する際のベストプラクティスについて提供されている情報を確認します。

- 1.  **\[Service name (サービス名)\]** フィールドに「**CD-Business Service (CD-ビジネスサービス)**」と入力します。
    2.  **\[Life cycle phase and status (ライフサイクルのフェーズとステータス)\]** で、以下のフィールドを構成します。
        - Phase (フェーズ)： **Catalog (カタログ)**

- - - Status (ステータス)： **Operational (稼働中)**

- 1.  構成可能な他のフィールドを確認し、**\[Continue to Team (チームに進む)\]** を選択します。

**注：** _\[Life cycle phase and status (_ライフサイクルのフェーズとステータス_)\]_ フィールドは、_Digital Portfolio Management (_デジタルポートフォリオ管理_)_ でサービスポートフォリオを表示する際に、正しく構成しておくことが重要です。

- 1.  **\[Team (チーム)\]** タブの右側のペインで、表示される情報を確認します。

- 1.  構成可能な他のフィールドを確認し、**\[Continue to Service Performance (サービスパフォーマンスに進む)\]** を選択します。

**注：** _\[Owned by (_オーナー_)\]_ フィールドは、サービスの最終的な責任者を示すフィールドであり、_Digital Portfolio Management_ でサービスポートフォリオを表示する際に、正しく構成しておくことが重要です。

- 1.  **\[Service Performance (サービスパフォーマンス)\]** タブの右側のペインで、サービスを定義する際のベストプラクティスについて提供されている情報を確認します。
    2.  構成可能な他のフィールドを確認し、**\[Continue to Manage Offerings (オファリングの管理に進む)\]** を選択します。

**注**： _KPI_ グループについては、_Digital Portfolio Management_ を使用する際の別のラボで説明します。

- 1.  **\[Manage Offerings (オファリングの管理)\]** タブの右側のペインで、表示される情報を一通り確認します。
    2.  **\[New (新規)\]** を選択します。

- 1.  **\[Create a new offering (新しいオファリングの作成)\]** フォームの右側のペインで、表示される情報を一通り確認します。

#### \[Offering name (オファリング名)\] フィールドに「CD-Business Service Offering (CD-ビジネスサービスオファリング)」と入力します。

- 1.  **\[Life cycle phase and status (ライフサイクルのフェーズとステータス)\]** で、以下のフィールドを構成します。
        - Phase (フェーズ)： **Catalog (カタログ)**

- - - Status (ステータス)： **Operational (稼働中)**

**注：**_\[Life cycle phase and status (_ライフサイクルのフェーズとステータス_)\]_ フィールドは、 _Digital Portfolio Management (_デジタルポートフォリオ管理_)_ でサービスポートフォリオを表示する際に、正しく構成しておくことが重要です。 _KPI_ メトリクスを表示できるのは、カタログフェーズのサービスとオファリングのみです。カタログフェーズとは、サービスがアクティブで、コンシューマーが利用可能な状態であることを意味します。

- 1.  **\[Team (チーム)\]** タブを選択します。

- 1.  指定された情報に従って、サポートグループと変更グループの各フィールドを構成します。

- - - Support group (サポートグループ)： **CD-Support Group (CD-サポートグループ)**

- - - Change Group (変更グループ)： **CD-Change Group (CD-変更グループ)**

- 1.  必要に応じて、残りの各タブを選択し、右側のペインに表示されている情報を確認します。

- 1.  **\[Save & Close (保存して閉じる)\]** を選択します。

#### \[Continue to Review and Submit (確認と送信に進む)\] を選択します。

- 1.  **\[Submit (送信)\]** を選択し、新しいビジネスサービスおよびオファリングを作成します。

- 1.  **\[Return to my dashboard (自分のダッシュボードに戻る)\]** を選択します。

# Service Delivery (サービスデリバリ) ドメイン

Service Delivery ドメイン (旧 Manage Technical Services (テクニカルサービスの管理)) は、Service Mapping や ServiceNow Discovery (ServiceNow ディスカバリー) などの IT Operations Management (ITOM) で従来使用されてきたテーブルを表す CSDM ドメインです。 さらに、ビジネスが利用するために提供される技術管理サービスポートフォリオを表します。\[Service Delivery (サービスデリバリ)\] の各テーブルは「運用」テーブルであるため、インシデント、問題、変更などのITSM プロセスで選択可能です。

**Service Delivery ドメインの全体像**： サービスを実行に移し、スムーズな運用を維持します。ペルソナには、_Service Instance_ オーナー、_Service Delivery_ オーナー、および _Service Provider (_サービスプロバイダー_)_ が含まれます。

## 技術管理サービスおよび技術管理サービスオファリング

技術管理サービス (旧テクニカルサービス) は、サービスオーナーに公開されるテクニカルサービスのサービスタイプを表し、通常は 1 つ以上の ビジネスサービスまたはアプリケーションサービスをサポートする役割を果たします。 技術管理サービスを使用すると、ビジネス向けに提供しているテクノロジーを表示し、管理できます。 技術管理サービスには、1 つ以上の技術管理サービスオファリングで構成される運用ビューが含まれる場合があります。

技術管理サービスオファリング (旧テクニカルサービスオファリング) は、ローカリゼーション/地域、環境 (本番/非本番)、価格設定、可用性、サポートグループ (インシデント用)、変更グループ (変更用)、パッケージオプション (コミットメント) などのオプション単位に分けて定義できます。

### 課題

Service Builder で学んだスキルを活用し、提供された情報を使用して新しい技術管理サービス (テクニカルサービス) とそれに対応するサービスオファリングを作成します。

- Service name (サービス名)： **CD-Technology Management Service (CD-技術管理サービス)**

- Service Life cycle phase and status (サービスライフサイクルのフェーズとステータス)：

- - Phase (フェーズ)： **Catalog (カタログ)**

- - Status (ステータス)： **Operational (稼働中)**

- Offering name (オファリング名)： **CD-Technology Management Service Offering (CD-技術管理サービスオファリング)**

- Offering Life cycle phase and status (オファリングライフサイクルのフェーズとステータス)：

- - Phase (フェーズ)： **Catalog (カタログ)**

- - Status (ステータス)： **Operational (稼働中)**

- Support Group (サポートグループ)： **CD-Support Group (CD-サポートグループ)**

- Change Group (変更グループ)： **CD-Change Group (CD-変更グループ)**

## Service Instance と CSDM Application Service Wizard (アプリケーションサービスウィザード)

Application Service Wizard は、Service Instance (旧 Application Service (アプリケーションサービス))を作成するために使用されます。 このウィザードでは、名前などの基本情報に加えて、サポート、変更グループ、場所データなどの基盤データを入力できます。さらに、サービスと、関連するビジネスアプリケーション、テクニカルサービスオファリング、およびビジネスサービスオファリングとの間のリレーションシップを簡単に構成できます。 最後に、データ入力方法を選択できますが、Application Service を作成するための従来の方法も引き続き利用できます。

このセクションでは、Service Instance を作成し、これまでに作成したテクニカルサービスオファリングとビジネスサービスオファリング、およびビジネスアプリケーションに関連付けます。

1.  **\[CSDM\] > \[Manage Technology Management Services (技術管理サービスを管理)\] > \[Technical Service Offering (テクニカルサービスオファリング)\]** に移動します。

**注：**_Service Builder_ を使用して作成されたサービスオファリングも、ここに表示できます。さらに、_CSDM_ アプリケーション内のさまざまなモジュールから、他のサービスやオファリングにアクセスできます。

1.  **\[CSDM\] > \[Manage Technology Management Services (技術管理サービスを管理)\] > \[Service Instance (サービスインスタンス)\]** に移動します。

#### \[New (新規)\] を選択し、\[CSDM Application Wizard (CSDM アプリケーションウィザード)\] を開きます。

1.  **\[Provide Basic Details (基本的な詳細を入力)\]** タブで、指定された情報に従ってフォームを構成します。

- - Number (番号)： **CD0001**

#### Name (名前)： CD-Service Instance/Application Service (CD-サービスインスタンス/

**アプリケーションサービス)**

- - Environment (環境)： **Production (本)**

- - Operational Status (運用ステータス)： **Operational (稼働中)**

- - Support Group (サポートグループ)： **CD-Support Group (CD-サポートグループ)**

- - Change Group (変更グループ)： **CD-Change Group (CD-変更グループ)**

- - Owned by (オーナー)： **Abel Tuter**

- - Short Description (簡単な説明)： **Cloud Dimensions Service Instance (Cloud Dimensions**

#### サービスインスタンス)

- - Business Application (ビジネスアプリケーション)： **CD-Business Application (CD-ビジネスアプリケーション)**

- - Technical Service Offering (テクニカルサービスオファリング)： **CD-Technology Management Service Offering (CD-技術管理サービスオファリング)**
    - Business Service Offering (ビジネスサービスオファリング)：**CD-Business Service Offering (CD-ビジネスサービスオファリング)**

1.  **\[Next (次へ)\]** を選択します。

#### \[Choose a Method (メソッドを選択してください)\] を選択します。

1.  **\[Service Population Method (サービスの作成方法)\]** 選択リストオプションを選択します。

1.  利用可能な選択肢を確認し、**\[Manual (手動)\]** を選択します。

**注：** このリストには、サービスを検出してデータを入力するための複数の方法が用意されています。 この例では _\[Manual (_手動_)\]_ を選択しますが、表示されているように、検出とデータ入力のニーズに応じて利用できるオプションが複数用意されています。

1.  指定された情報に従ってフォームを構成します。

- - Class (クラス)： **Windows Server \[cmdb_ci_win_server\] (Windows サーバー**

**\[cmdb_ci_win_server\])**

#### CI： CD-Windows Server (CD-Windows サーバー)

1.  **\[Choose a Method (メソッドを選択してください)\]** フォームを構成した後で、**\[Save (保存)\]** を選択します。
2.  **\[Next (次へ)\]** を選択し、新しい Service Instance で構成されたさまざまなリレーションシップを確認します。

1.  **\[Done (完了)\]** を選択して新しいサービスを保存します。

**重要**： _ServiceNow Common Services Data Model (CSDM)_ を実装すると、_IT_ 運用、サービス管理、データガバナンスを強化するさまざまな貴重な成果が得られます。次のラボでは、こうした期待される成果の一例を確認します。

CSDM データモデルは、ServiceNow 製品全体にわたるフレームワークとして機能し、複数の構成および管理戦略を可能にし、それらの実行をサポートします。標準提供 (OOB) されるテーブル、リファレン

ス、リレーションシップを用いた、データを適切にモデリングするための現在のベストプラクティスも含まれています。 多くの ServiceNow 製品は、このデータモデル内のデータに依存しています。

**ラボ完了**

**お疲れさまでした！ このラボはこれで完了です。**
# CSDM で実現される成果

**ラボ 2.01** 45 分

**ラボの目標**

ServiceNow の Common Service Data Model (共通サービスデータモデル (CSDM)) を実装すると、組織はサービス管理を成熟させ、可視化を高め、IT をビジネスゴールに整合させるための基本的なメリットを得られます。

このラボで達成する目標は、次のとおりです。

- CSDM Data Foundation Dashboard (CSDM のデータファンデーションダッシュボード) で拡張されたメトリクスを確認する
- インシデントレコードを一通りたどり、CSDM の動作を確認する
- CSDM が変更要求にどのような付加価値をもたらすかを理解する
- Unified Map (統一マップ) を使用して、構成されている CSDM のリレーションシップを確認する
- CSDM が Enterprise Architecture (エンタープライズアーキテクチャ) をどのようにサポートし、強化するかを体験する
- Event Management (イベント管理) を使用して、影響を受けた CI を確認し、対応を簡素化する

# 成果

ServiceNow Common Services Data Model (CSDM) を実装すると、IT 運用、サービス管理、データガバナンスを強化するさまざまな貴重な成果が得られます。 このセクションでは、期待される成果の一例を確認します。

## CSDM Data Foundations Dashboard (CSDM のデータファンデーションダッシュボード)

- 1.  **\[Configuration (構成)\] > \[CSDM Data Foundations Dashboard (CSDM のデータファンデーションダッシュボード)\]** に移動します。

**注**： このダッシュボードには、_CSDM_ の原則を活用してサービスを確立する上での推奨プラクティスとして、_ServiceNow_ が提示する一連のメトリクスが表示されます。

1.  **\[Foundation (基盤)\]** タブで、これまでに行った構成に基づき、以下のメトリクスが維持または改善されていることを確認します。

- - Locations with Parents (親が設定されている場所)

**注**： 各メトリクスの右側には、当該メトリクスを維持する重要性や、その上流や下流への影響を説明し、スコアが低い場合にメトリクスを改善するための是正手順を提示するプレイブックが用意されています。

1.  **\[Crawl (クロール)\]** タブで、これまでに行った構成に基づき、以下のメトリクスが維持または改善されていることを確認します。

- - ビジネスアプリケーションとリレーションシップを持つアプリケーションサービス

- - アプリケーションサービスとリレーションシップを持つビジネスアプリケーション

- - ビジネスアプリケーションに対する「Consumes::Consumed By」リレーションシップを持つアプリケーションサービス

1.  **\[Walk (ウォーク)\]** タブで、これまでに行った構成に基づき、以下のメトリクスが維持または改善されていることを確認します。

- - テクニカルサービスへの参照を備えたテクニカルサービスオファリング

- - サポートグループまたは変更グループが設定されているテクニカルサービスオファリング

1.  **\[Run (ラン)\]** タブで、これまでに行った構成に基づき、以下のメトリクスが維持または改善されていることを確認します。

- - ビジネスサービスオファリングとリレーションシップを持つアプリケーションサービス

- - アプリケーションサービスとリレーションシップを持つビジネスサービスオファリング

- - ベースシステムサービステーブル

- - ベースシステム CMDB テーブルを使用するサービス

**注**： サービスインスタンスとそのリレーションシップを構成するために、カスタムテーブルは作成されていません。

1.  **\[Fly (フライ)\]** タブで、これまでに行った構成に基づき、以下のメトリクスが維持または改善されていることを確認します。

- - ビジネスアプリケーションとリレーションシップを持つ情報オブジェクト

- - 情報オブジェクトとリレーションシップを持つビジネスアプリケーション

**注**： _\[Crawl (_クロール_)\]_ タブは、顧客の _CSDM_ ジャーニーにおけるより成熟したメトリクスを扱います。

## Incident Management (インシデント管理)

CSDM を実装すると、サービスとサポートグループの関連付けによりタスクをより迅速かつ正確にアサインできるようになり、インシデント管理プロセスが簡素化されます。また、サービスがどのように提供され、サポートされているかをエンドツーエンドで可視化できるようになり、根本原因分析と影響度アセスメントが改善され、平均解決時間 (MTTR) が短縮されます。

1.  **\[Incident (インシデント)\] > \[Create New (新規作成)\]** に移動します。

1.  指定された情報に従ってフォームを構成します。

- - Caller (問い合わせユーザー)： **Abel Tuter**

- - Short description (簡単な説明)： **CSDM benefits for Incident Management (インシデント管理における CSDM のメリット)**

1.  **\[Service (サービス)\]** フィールドに「**CD**」と入力し、サービスインスタンス、ビジネスサービス、および技術管理サービスがすべて選択可能であることを確認します。
2.  **\[Service (サービス)\]** フィールドから **\[CD\]** を削除します。

1.  **\[Service offering (サービスオファリング)\]** フィールドに「**CD**」と入力し、ビジネスサービスオファリングと技術管理ビジネスオファリングがすべて選択可能であることを確認します。

**注：**_\[Service Consumption (_サービス消費_)\]_ と _\[Service Delivery (_サービスデリバリ_)\]_ の各テーブルは「運用」テーブルであるため、インシデント、問題、変更などの _ITSM_ プロセスで選択可能です。 したがって、これまでに作成したサービスとオファリングを選択できます。

1.  **\[Service offering (サービスオファリング)\]** フィールドから **\[CD\]** を削除します。

### \[Configuration item (構成アイテム)\] フィールドに「CD-Service Instance/Application Service (CD-サービスインスタンス/アプリケーションサービス)」と入力します。

**注：** _\[Configuration Item (_構成アイテム_)\]_ の参照フィールドには、デフォルトで _CMDB_ 内のすべてのエントリが表示されます。このリストを絞り込むには、コア _CI_ クラスをプリンシパルクラスとして指定することがベストプラクティスです。 このフィルタリングは、_CI_ クラスマネージャーを使用して構成できます。

1.  **\[Configuration Item (構成アイテム)\]** フィールドの右側にある **\[Show dependency views (依存関係ビューを表示)\]** ボタンを選択します。

1.  マップを表示し、サービスインスタンス、サービス、オファリング、および機能の間で可視化されているさまざまなリレーションシップを確認します。

**注**： マップは、サポートエージェントがどのオファリングを選択するべきかを判断する際のインサイトを提供します。

1.  **\[Business Application (ビジネスアプリケーション)\]** ノードを右クリックし、**\[View Map (マップを表示)\]** を選択して視点を切り替えます。

**注：** 情報オブジェクトを可視化できるようになります。

1.  \[Map (マップ)\] タブを閉じます。

### \[Service offering (サービスオファリング)\] フィールドで、\[CD-Technology Management Service Offering (CD-技術管理サービスオファリング)\] を選択します。

1.  インシデントレコードを保存し、選択した CI に基づいて **\[Assignment Group (アサイン先グループ)\]** フィールドが自動入力されることを確認します。

**注**： _\[Assignment Group (_アサイン先グループ_)\]_ は、構成アイテムにアサインされたサポートグループに基づいて自動入力されます。_CI_ レベルでサポートグループがアサインされていない場合、オファリングレベルで定義された _Assignment group_ が使用されます。

## Change Management (変更管理)

CSDM は、サービス、アプリケーション、およびインフラストラクチャの間のリレーションシップをマッピングします。 これにより、提案された変更のビジネスインパクトに関するインサイトが得られ、リスクアセスメントが改善され、より十分な情報に基づいた変更の意思決定を行うことができます。また、CI またはサービスオファリングの変更グループ構成を通じて、変更タスクを適切な Assignment group に自動的にルーティングできます。

1.  **\[Change (変更)\] > \[Create New (新規作成)\]** に移動します。

1.  **\[All (すべて)\]** タブで **\[Normal (標準)\]** タイルを選択します。

1.  指定された情報に従ってフォームを構成します。

- - Short description (簡単な説明)： **CSDM benefits for Change Management (変更管理における CSDM のメリット)**

1.  **\[Service (サービス)\]** フィールドに「**CD**」と入力し、サービスインスタンス、ビジネスサービス、および技術管理サービスがすべて選択可能であることを確認します。

### \[CD-Business Service (CD-ビジネスサービス)\] を選択します。

1.  **\[Service (サービス)\]** フィールドの右側にある **\[Open in Dependency Views (依存関係ビューを表示)\]** ボタンを選択します。

1.  マップを表示し、ビジネスサービス、そのオファリング、サービスインスタンス、およびサポートしている Windows サーバーの間のリレーションシップと、サービスインスタンスのオープンインシデントを示すインジケーターを確認します。

1.  **\[Dependency Views (依存関係ビュー)\]** タブを閉じます。

1.  マップに表示される情報に基づいて、以下の追加フィールドを構成します。

- - Service Offering (サービスオファリング)： **CD-Business Service Offering (CD-ビジネスサービスオファリング)**
    - Configuration item (構成アイテム)： **CD-Service Instance/Application Service (CD-サービスインスタンス/アプリケーションサービス)**

1.  レコードを保存し、**\[Assignment group (アサイン先グループ)\]** フィールドがサービスオファリングの **\[Change group (変更グループ)\]** フィールドの構成に基づいて自動入力されることを確認してください。

**注**： _\[Assignment Group (_アサイン先グループ_)\]_ は、構成アイテムにアサインされた変更グループに基づいて自動入力されます。_CI_ レベルでサポートグループがアサインされていない場合、オファリングレベルで定義された _Assignment group_ が使用されます。

1.  **\[Configuration Item (構成アイテム)\]** フィールドの右側にある **\[Show dependency views (依存関係ビューを表示)\]** ボタンを選択します。

1.  CI の視点からマップを表示し、サービスインスタンス、サービス、オファリング、ビジネスアプリケーション、および機能の間で可視化されているさまざまな上流のリレーションシップを確認します。

**注：** _CSDM_ は、サービスのコンテキストとオーナーシップを十分に理解した上で変更を評価、実行、監視できるようにすることで、変更管理を強化します。

サービスをさらに詳細にモデル化し、それをサポートする追加のインフラストラクチャも含めた場合、マップはそれらのリレーションシップを含むように拡張され、根本原因分析、ビジネスインパクトの把握、および変更の意思決定における適切なリスクアセスメントを大きく支援します。

1.  **\[Dependency Views (依存関係ビュー)\]** タブを閉じます。

1.  変更レコードから、**\[Affected CIs (影響を受ける CI)\]** タブ、**\[Impacted Services/CIs (影響するサービス/CI)\] タブ、および \[Service Offerings (サービスオファリング)\]** タブを選択し、マップに表示されているものとは異なる視点から CI 関係を表示します。

**注**： _\[Service Offerings (_サービスオファリング_)\]_ 関連リストが表示されない場合は、ヘッダーを右クリックして構成する必要があります。_\[Configuration (_構成_)\] > \[Related Lists (_関連リスト_)\]_ に移動し、_\[Impacted CIs (_影響を受ける _CI)\]_ で「_Service Offerings (_サービスオファリング_)_」を検索して追加します。

## Unified Map (統一マップ)

ServiceNow の Unified Map は、CMDB 内の構成アイテム (CI)、サービス、アプリケーション、およびその他の関連エンティティの間のリレーションシップを視覚的に表現したもので、単一の統合ビューに表示されます。 Unified Map には以下のメリットがあります。

- - 複数のソース (Service Mapping (サービスマッピング)、Discovery (ディスカバリー)、CSDM

リレーションシップなど) からデータを結合する

- - 上流と下流の依存関係を表示する

- - インフラストラクチャ、アプリケーション、およびサービスがどのようにつながっているかを示す

- - インシデント、変更、および問題に対する影響分析を可能にする

1.  **\[Configuration item (構成アイテム)\]** フィールドの右側にある変更レコードから、**\[Open in CMDB Workspace (CMDB ワークスペースで開く)\]** ボタンを選択します。

1.  少し時間を取って、ワークスペース内のレコードを確認します。

1.  **\[CI Health (CI 健全性)\]** タイルを表示し、CI を対象とした最近のインシデントと変更を確認します。

1.  右上の **\[Open map (マップを開く)\]** を選択し、Unified Map を開きます。

1.  **\[Open filter panel (フィルターパネルを開く)\]** ボタンを選択します。

1.  **\[Select All (すべて選択)\]** チェックボックスをオンにし、このラボ全体で構成されたすべてのリレーションシップを表示します。

1.  **\[Map filter (マップフィルター)\]** パネルを閉じます。

1.  右側のペインで **\[Related items (関連アイテム)\]** アイコンを選択し、サービスに関連するアクティブなインシデントを表示します。

1.  **\[Active incidents (アクティブなインシデント)\]** タブを選択し、アクティブなインシデントの詳細を表示します。

1.  アクティブなインシデントタイルを選択し、そのインシデントが参照しているマップ上の CI がハイライト表示されていることを確認します。

## Enterprise Architecture (エンタープライズアーキテクチャ)

Enterprise Architecture (EA) (旧 Application Portfolio Management (アプリケーションポートフォリオ管理)) は、Strategic Portfolio Management (戦略的ポートフォリオ管理) (SPM) スイートに含まれる製品です。ビジネス機能、アプリケーション、テクノロジーの相互関係を、構造化された視覚的かつデータ駆動型のビューで提供することで、組織がビジネス戦略と IT の実行を整合させることを支援します。

CSDM は、Enterprise Architecture (EA) 製品が正確なインサイトやリレーションシップ、ビジネスと IT 間の整合性を提供する上で依存する、標準化された構造化データモデルを提供するため、EA 製品は CSDM から大きなメリットを得られます。

1.  **\[Digital Portfolio Management (デジタルポートフォリオ管理)\] > \[All Business Applications (すべてのビジネスアプリケーション)\]** に移動します。
2.  「**CD-Business Application (CD-ビジネスアプリケーション)**」を検索して開きます。

1.  **\[Show Dependency Views (依存関係ビューを表示)\]** アイコンを選択します。

**注：** ビジネスアプリケーションモデルにサポートインフラストラクチャが含まれ、関連するオープンインシデントが表示されるようになりました。

# Event Management (イベント管理)

ServiceNow の Common Services Data Model (CSDM) は、インフラストラクチャとサービス健全性を監視し対応するプロセスにおいて、コンテキスト、自動化、正確性を向上させることで、Event Management を大幅に強化します。 CSDM によって、Event Management は単なる技術中心のアプローチではなく、サービス中心のアプローチで運用されるようになります。 この移行により、サービス停止の減少、より迅速な解決、よりスマートな自動化、ビジネスとより整合した IT 運用戦略が実現します。

- 1.  **\[Workspace Experience (ワークスペースエクスペリエンス)\] > \[Workspace (ワークスペース)\] > \[Service Operations Workspace (サービスオペレーションワークスペース)\]** に移動します。
    2.  **\[Service Dashboard (サービスダッシュボード)\]** アイコンを選択し、**\[not critical (重大ではない)\]** セクションでプラス記号を選択して、すべてのサービスを表示します。

- 1.  構成した Cloud Dimensions サービスが緑色で表示されていることを確認します。これは、サービスが正常で、運用状態が良好であることを示します。

- 1.  **\[Event Management (イベント管理)\] > \[Simulation (シミュレーション)\] > \[Event Generator (イベントジェネレーター)\]** に移動します。

**注：** _Event Generator_ は、イベントをシミュレートするためのカスタムアプリケーションです。 更新セットを使用して、インスタンスにあらかじめインストールされています。

- 1.  以下のようにフォームに入力します。
        - Source (ソース)： **SolarWinds**
        - Node (ノード)： **CD-Windows Server (CD-Windows サーバー)**
        - Message key (メッセージキー)：**solar_msg_key**
        - Severity (重大度)： **Major (重大)**
        - Description (説明)： **Memory exceeds expected threshold (メモリが予想しきい値を超えている)**

- 1.  **\[Generate Event (イベントの生成)\]** を選択します。

- 1.  ポップアップメッセージで **\[Leave (終了)\]** を選択します。

- 1.  イベントに関連付けられたアラート番号が表示されるまで、**\[Events (イベント)\]** リストを更新します。

- 1.  **\[Source (ソース)\]**が「**SolarWinds**」のレコードでアラート番号を選択し、アラートレコードを開きます。

**注：**相関アラートが自動的に開き、サービスの一部である構成アイテムに関連付けられます。

- 1.  **\[Impacted Services (影響を受けるサービス)\]** タブで、影響を受けるサービスとその重大度を確認します。

- 1.  アラートを表示した後、**\[Open in Workspace (ワークスペースで開く)\]** ボタンを選択します。

**注：** アラートの詳細がワークスペースに表示されます。

- 1.  **\[Service Dashboard (サービスダッシュボード)\]** アイコンを選択し、**\[CD-Service Instance/Application Service (CD-サービスインスタンス/アプリケーションサービス)\]** がオレンジ色で表示され、重大度が「重大」の問題であることを確認します。

### \[CD-Service Instance/Application Service (CD-サービスインスタンス/アプリケーションサービス)\] タイルを選択します。

- 1.  **\[Service Map (サービスマップ)\]** を選択します。

- 1.  オレンジ色で表示されている CI が示すマップ上の表示から、サービス停止の根本原因を簡単に特定できることを確認します。

**注：** _\[CD-Service Instance/Application Service (CD-_サービスインスタンス_/_アプリケーションサービス_)\]_ マップが _Unified Map_ インターフェイスで開き、重大度が「重大」の問題の原因となっている下流の _CI (CD-Windows Server)_ にリンクされたアラートが強調表示されます。 これにより、即時のアクションが必要な影響を受ける _CI_ を明確に可視化できます。

サービス全体ビューとその影響を受ける _CI_ にアクセスできることにより、関連するインシデントや潜在的なサービスへの影響に対する平均修理時間 _(MTTR)_ が大幅に短縮されます。特に _CD-Windows Server_ に対する変更が計画されている場合は、その効果は顕著です。

# Challenge (Optional) (課題 (オプション))

Cloud Dimensions は、エンタープライズ内で ITSM 機能を提供するためにServiceNow (SN) の実装を計画しており、CSDM の推奨プラクティスを活用して、次の新しいレコードとリレーションシップを構成する予定です。

これまでに学んだ CSDM の知識を活かし、指定された情報を活用して、以下の新しいサービスインスタンスと CSDM 要素を構成します。

- Support Group (サポートグループ)： **SN-ITSM Support Group (member is System Administrator) (SN-ITSM サポートグループ (メンバーはシステムアドミニストレーター))**

### Change Group (変更グループ)： SN-ITSM Change Group (member is System Administrator) (SN-ITSM 変更グループ (メンバーはシステムアドミニストレーター))

- Business Application (ビジネスアプリケーション)： **SN-ServiceNow**

- Capability (機能)： **SN-ITSM**

- Information Object (情報オブジェクト)： **SN-Configuration Items (SN-構成アイテム)**

- Business Service (ビジネスサービス)： **SN-Manage ITSM Services (SN-ITSM サービスの管理)**

- Business Service Offerings (ビジネスサービスオファリング)：

### SN-Provide Incident Management (SN-インシデント管理の提供)

- - **SN-Provide Change Management (SN-変更管理の提供)**
- Technology Management Service (技術管理サービス)： **SN-Manage Identify Services (SN-識別サービスの管理)**
- Technology Management Service Offering (技術管理サービスオファリング)： **SN-Provide Active Directory Services (SN-Active Directory サービスの提供)**

- Service Instance (サービスインスタンス)：**SN-ServiceNow (Service Instance) (SN-ServiceNow (サービスインスタンス))**

前のセクションで示したのと同じ成果を得られるように、必要なリレーションシップやグループを含めて、さまざまなレコードを構成します。

CSDM の実装は、単に CMDB を整理することではなく、サービスを中心に捉え、ビジネスに整合し、運用効率の高い IT エコシステムを構築することを意味します。 また、ITSM、ITOM、Enterprise Architecture (旧 APM)、SPM にまたがるクロスプラットフォームの価値を引き出すと同時に、組織を将来のイノベーションに向けて位置づけることができます。

**ラボ完了**

**お疲れさまでした！ このラボはこれで完了です。**
# ダイナミック CI グループおよび盤グループデータ

**ラボ 3.01** 30 分

**ラボの目標**

ServiceNow のダイナミック Configuration Item (構成アイテム) (CI) グループは、Common Service Data Model (共通サービスデータモデル) (CSDM) とともに、IT 資産とサービスの管理において重要な役割を果たします。

Cloud Dimensions は、ServiceNow の Discovery (ディスカバリー)、Service Mapping (サービスマッピング)、IntegrationHub ETL (統合ハブ ETL) を導入し、大量の価値ある CI データを ServiceNow CMDBに取り込むことに成功しています。 ただし、CMDB アドミニストレーターは、検出されたデータを、グループのアサインなどの検出不可能な情報で補完することが不可欠です。

グループは、CI に関連するインシデントを管理し、必要な変更を促進するために重要です。 正確なグループデータにより、これらのプロセスがスムーズに実行されます。

このラボでは、Cloud Dimensions が CSDM モデルの一部を実装し、ダイナミック CI グループを活用して、選択した CI クラスに対するグループのアサインの更新を改善します。

このラボで達成する目標は、次のとおりです。

- CI クラスマネージャーを使用してグループのアサインを管理する
- CMDB グループを作成する
- ダイナミック CI グループを作成する
- ダイナミック CI グループを技術管理オファリングに関連付ける
- サービスオファリングから基礎となる CI にグループデータを同期する

このラボで取り上げる領域に焦点を当てた CSDM

# 盤データを表示する

- 1.  **\[Configuration (構成)\] > \[Servers (サーバー)\] > \[Windows\]** に移動します。

- 1.  **SYD** または **CD** で始まるすべてのサーバーを検索します。

- 1.  リストをカスタマイズし、**\[OS Version (OS バージョン)\]** 列の後に **\[Support group (サポートグループ)\]**、**\[Change Group (変更グループ)\]**、および **\[Managed by Group (管理担当者グループ)\]** 列を表示します。

**注：** _Cloud Dimensions_ は一部の _Configuration Item (CI)_ のサポートグループを実装していますが、新しい _CI_ が継続的に追加され、手動で更新する必要があるため、サポートグループを維持することが困難です。 この課題に対処するために、_Cloud Dimensions_ はダイナミッ

ク _CI_ グループとサービスオファリングを活用し、継続的なメンテナンスを簡素化することを計画しています。

_\[Support group (_サポートグループ_)\]_、_\[Change Group (_変更グループ_)\]_、および _\[Managed by groups (_管理担当者_)\]_ グループは、手動で入力する必要がある検出不可能なフィールドです。これらのフィールドは、_Incident Management (_インシデント管理_)_や _Change Management (_変更管理_)_ などのプロセスにおいて重要な役割を果たします。具体的には、_Support Group_ がインシデントアサイン先グループを決定し、_Change Group_ は変更アサイン先グループに対応します。 ダイナミック _CI_ グループを実装することで、_Cloud Dimensions_ は、これらのプロセス全体にわたる手作業を削減し、データ精度を向上させることができます。

# CI クラスマネージャーから盤データを管理する

ダイナミック CI グループを実装する前に、Cloud Dimensions は CI クラスマネージャーの活用を検討し、特定の CI クラスに対して \[Managed By Group (管理担当者グループ)\] フィールドに値を設定することを計画しています。

- 1.  **\[User Administration (ユーザー管理)\] > \[Groups (グループ)\]** に移動します。

- 1.  **\[New (新規)\]** を選択します。
    2.  **\[Name (名前)\]** フィールドに「**CD-Managed By Group (CD-管理担当者グループ)**」と入力します。

- 1.  レコードを保存します。

- 1.  **\[Group Members (グループメンバー)\]** 関連リストを選択します。

- 1.  **\[Edit (編集)\]** を選択します。

- 1.  「**System Administrator (システムアドミニストレーター)**」を検索して選択し、**\[Group Members List (グループメンバーリスト)\]** ペインに追加します。
    2.  **\[Save (保存)\]** を選択します。

**注**： グループを _CI_ またはサービスオファリングの _\[Managed By Group (_管理担当者グループ_)\]_ フィールドに関連付けることで、責任者へのデータマネージャーのタスクのアサインを効率化できます。

- 1.  フォームを再ロードし、**\[Groups Members (グループメンバー)\]** 関連リストの下に **\[System Administrator (システムアドミニストレーター)\]** が表示されることを確認します。

- 1.  **\[Configuration (構成)\] > \[CI Class Manager (CI クラスマネージャー)\]** に移動します。

- 1.  **\[Hierarchy (階層)\]** を選択します。

- 1.  「**Windows Server (Windows サーバー)**」クラスを検索して選択します。

### \[Basic Info (本情報)\] タブの \[Managed By Group (管理担当者グループ)\] フィールドに

「**CD-Managed By Group (CD-管理担当者グループ)**」と入力します。

**注：** すべての _Windows Server_ の _\[Managed By Group (_管理担当者グループ_)\]_ フィールドは、_CI_ クラスマネージャーを使用して構成できます。 よりきめ細かな制御とメンテナンスの容易化のために、このラボの後半で説明するサービスオファリングとダイナミック _CI_ グループを活用できます。

- 1.  レコードを保存します。

- 1.  **\[System Definition (システム定義)\] > \[Scheduled Jobs (スケジュール済みジョブ)\]** に移動します。

- 1.  「**CSDM Data Sync (CSDM データ同期)**」スケジュール済みジョブを検索して開きます。

- 1.  **\[Execute Now (今すぐ実行)\]** を選択します。

**注：**スケジュール済みジョブは、_CI_ クラスマネージャーで設定された _\[Managed By Group (_管理担当者グループ_)\]_ フィールドの値を、当該クラス内のすべての _CI_ に同期します。

- 1.  **\[Configuration (構成)\] > \[Servers (サーバー)\] > \[Windows\]** に移動します。

- 1.  **SYD** で始まるすべてのサーバーを検索し、**\[Managed By Group (管理担当者グループ)\]** 列に

**\[CD-Managed By Group (CD-管理担当者グループ)\]** と表示されていることを確認します。

**注：** すべての _Windows Server_ で、_\[Managed By Group (_管理担当者グループ_)\]_ フィールドが「_CD-Managed By Group (CD-_管理担当者グループ_)_」を参照するようになりました。 この構成は _CI_ クラスマネージャーで設定され、当該 _CI_ クラス全体に適用されます。 よりきめ細かく柔軟なアプローチを取るには、技術管理サービスオファリングとダイナミック _CI_ グループを組み合わせて使用し、_\[Managed By Group (_管理担当者グループ_)\]_ を構成できます。

# 技術管理サービスオファリングから盤データを管理する

Cloud Dimensions は、Configuration Management Database (構成管理データベース) (CMDB) 内の一部の Configuration Item (CI) に対してサポートグループを構成しています。ただし、新しい CI が継続的に追加され、手動で更新する必要があるため、これらのグループを維持することは困難です。この問題に対処するために、Cloud Dimensions は、CMDB グループおよび技術管理サービスオファリングと組み合わせて、ダイナミック CI グループを活用することを検討しています。

CMDB グループは、IT 資産とサービスの管理、追跡、メンテナンスを効率化するために構成された CI の集合です。 ダイナミック CI グループは、事前定義された基準に基づいて CI を自動的にグループに含めることで、これらのグループを維持するために必要な手作業を削減し、常にグループを最新の状態に保つことができます。

## CMDB グループを構成する

- 1.  **\[Configuration (構成)\]** \> **\[CMDB Groups (CMDB グループ)\]** に移動します。

- 1.  **\[New (新規)\]** を選択します。

### \[Group Name (グループ名)\] に「CD-Sydney Win Servers CMDB Group (CD-Sydney Win

**サーバー CMDB グループ)**」と入力します。

- 1.  レコードを保存します。

### \[CMDB Group Contains Encoded Queries (CMDB グループはエンコードクエリを含む)\] タブで、\[New (新規)\] を選択します。

- 1.  以下のとおり、記載されている順序でクエリを設定します。

- - - Class (クラス)： **Server \[cmdb_ci_server\] (サーバー \[cmdb_ci_server\])**

- - - Conditions (条件)：

- - - - **Name |starts with | syd OR Name | starts with | cd (名前 | 次の値で始まる | syd OR 名前 | 次の値で始まる | cd)**

- 1.  **\[Submit (送信)\]** を選択します。

### \[Show All CI (すべての CI を表示)\] を選択します。

**注：** クエリに一致するすべてのサーバーのリストが表示されます。

## ダイナミック CI グループを作成する

ServiceNow のダイナミック CI グループは、事前定義された基準に基づいて CI を自動的にグループに含めることで、これらのグループを維持するために必要な手作業を大幅に削減します。 CMDB グループを参照し、基礎となる CI の内、どれを管理対象とするかを決定します。 さらに、ダイナミック CI グループは ServiceNow のサービスタイプとして分類され、ダイナミック CI グループ \[cmdb_ci_query_based_service\] テーブルに保存されます。

1.  **\[Configuration (構成)\] > \[Dynamic CI Groups (ダイナミック CI グループ)\]** に移動します。

1.  **\[New (新規)\]** を選択します。

1.  以下の情報に従ってフォームを構成します。

### Name (名前)： CD-Sydney Win Servers Dynamic CI Group (CD-Sydney Win サーバーダイナミック CI グループ)

- - CMDB Group (CMDB グループ)： **CD-Sydney Win Servers CMDB Group (CD-Sydney Win**

### サーバー CMDB グループ)

1.  **\[Submit (送信)\]** を選択します。

## 技術管理サービスオファリングを更新する

サービスオファリング内で定義されたグループは、関連付けられたダイナミック CI グループに含まれる基礎となる CI と自動的に同期されます。

\[Support group (サポートグループ)\]、\[Change Group (変更グループ)\]、および \[Managed by groups (管理担当者)\] は検出不可能なフィールドであり、Incident Management や Change Management などのプロセスをサポートするために、CI レコードに手動で入力する必要があります。

具体的には、\[Support group (サポートグループ)\] は \[Incident Assignment Groups (インシデントアサイン先グループ)\] フィールドに、\[Change Group (変更グループ)\] は \[Change Assignment Group (変更アサイン先グループ)\] フィールドにマップされます。

Cloud Dimensions は、技術管理サービスオファリングをダイナミック CI グループと組み合わせて使用することで、これらのグループの管理を自動化し、簡素化することを目指しています。これにより、関連データを一貫して正確に維持できます。

1.  **\[Service Portfolio Management (サービスポートフォリオ管理)\] > \[Service Builder (サービスビルダー)\]** に移動します。

### \[My services (自分のサービス)\] で、\[CD-Technology Management Service (CD-技術管理サービス)\]

を選択して開きます。

1.  **\[Manage Offerings (オファリングの管理)\]** タブを選択します。

### \[CD-Technology Management Service Offering (CD-技術管理サービスオファリング)\] を選択して開きます。

1.  **\[Operations (操作)\]** タブを選択します。

1.  一番下までスクロールし、**\[Application services | contain (アプリケーションサービス | 含む)\]**フィールドに「**CD-Sydney Win Servers Dynamic CI Group (CD-Sydney Win サーバーダイナミック CI グループ)**」と入力します。

1.  **\[Team (チーム)\]** タブを選択します。

1.  このオファリングは、前のラボでサポートおよび変更グループを使用して既に構成済みであることを確認します。

1.  **\[Save & Close (保存して閉じる)\]** を選択します。

1.  **\[Review and Submit (レビューと送信)\]** タブを選択します。

1.  **\[Submit (送信)\]** を選択します。

### \[Return to my dashboard (自分のダッシュボードに戻る)\] を選択します。

**グループの盤データを礎となる CI に同期する**

ServiceNow にはスケジュール済みジョブが用意されており、このジョブを実行すると、サービスオファリングに関連付けられたすべてのグループデータが、ダイナミック CI グループで参照される基礎となる CIに同期されます。

1.  **\[System Definition (システム定義)\]** \> **\[Scheduled Jobs (スケジュール済みジョブ)\]** に移動します。

1.  「**CSDM Data Sync (CSDM データ同期)**」を検索して開きます。

1.  **\[Execute Now (今すぐ実行)\]** を選択します。

**注：** スケジュール済みジョブは、サービスオファリングの _\[Support group (_サポートグ

ループ_)\]_、_\[Change Group (_変更グループ_)\] (_アサイン先グループ_)_、および _\[Managed by Group (_管理担当者グループ_)\]_ を、ダイナミック _CI_ グループ内の基礎となる _CI_ に同期します。これにより、これらの検出不可能な属性を効率的に管理できます。

# 成果

ダイナミック CI グループを活用すると、いくつかの重要なメリットがあります。 サービスオファリングに関連付けることで、基礎となる CI 全体にわたって、基盤グループデータのメンテナンスを簡素化できます。 さらに、変更フォームでダイナミック CI グループを選択すると、ServiceNow が自動的にグループを展開し、\[Affected CIs (影響を受ける CI)\] リストに値を入力して、適切な変更のアサイン先グループを適用します。 これにより、トリアージに要する時間が短縮され、変更要求が誤ってルーティングされるリスクが最小限に抑えられます。

## グループ属性の更新を確認する

1.  **\[Configuration (構成)\] > \[Servers (サーバー)\] > \[Windows\]** に移動します。

1.  Sydney の場所にある、名前が **SYD** で始まるサーバーをすべて検索します。

1.  すべてのサーバーで、**\[Support group (サポートグループ)\]**、**\[Change Group (変更グループ)\]**、および **\[Managed By Group (管理担当者グループ)\]** のグループ値が更新されて表示されていることを確認します。

**注：**_CI_ クラスマネージャーで設定された _\[Managed By Group (_管理担当者グループ_)\]_ がサービスオファリングで構成された値と異なる場合、サービスオファリング側の優先度が高いため、サービスオファリングの値で上書きされます。

## Change Management (変更管理)

ダイナミック CI グループにまとめられた CI は、いくつかの点で Change Management にメリットをもたらします。

- - 変更要求フォームの構成アイテムとしてダイナミック CI グループを選択すると、メンバー CI が自動的に展開され、\[Affected CIs (影響を受ける CI)\] 関連リストに表示されます。
    - \[Affected CIs (影響を受ける CI)\] セクションの CI のリストは調整でき、変更の影響を受けない CI を削除できます。
    - \[Affected CIs (影響を受けるCI)\] の最終リストに基づいて、システムは影響を受けるサービスを導き出すことができます。

1.  **\[Change (変更)\] > \[Create New (新規作成)\]** に移動します。

1.  **\[Models (モデル)\]** タブで **\[Normal (標準)\]** タイルを選択します。

### \[Configuration item (構成アイテム)\] フィールドから、\[CD-Sydney Win Servers Dynamic CI Group (CD-Sydney Win サーバーダイナミック CI グループ)\] を選択します。

**注：**このダイナミック _CI_ グループは、このラボの前半で作成済みです。このグループには、名前が _SYD_ または _CD_ で始まるすべてのサーバーが含まれます。_CD_ で始まるサーバーは、 _CD-Service Instance/Application Service (CD-_サービスインスタンス_/_アプリケーションサービス_)_ の下流 _CI_ であることを思い出してください。

1.  レコードを保存します。

1.  **\[Assignment group (アサイン先グループ)\]** に、技術管理サービスオファリングで構成された

**\[CD-Change Group (CD-変更グループ)\]** が自動的に入力されていることを確認します。

**注：** 変更フォームの _\[Assignment group (_アサイン先グループ_)\]_ には、技術管理サービスオファリングで構成された変更グループが自動的に入力されます。 この自動アサインにより、変更要求が適切なグループに動的にルーティングされ、変更プロセスが簡素化されます。

1.  グループの展開が開始されたことを示す情報メッセージが表示されていることを確認します。

1.  ヘッダーを右クリックし、**\[Reload form (フォームのリロード)\]** を選択します。

1.  **\[Affected CIs (影響を受ける CI)\]** タブに、ダイナミック CI グループ内のすべての CI が表示されていることを確認します。

1.  **\[SYD50-DC1-WIN12\]** の左側にあるチェックボックスをオンにします。
2.  **\[Actions on selected rows (選択した行のアクション)\]** 選択リストから、**\[Delete (削除)\]** を選択します。

1.  **\[Confirmation (確認)\]** ウィンドウでもう一度 **\[Delete (削除)\]** を選択し、リストから CI を削除します。

**注：** 変更レコードからダイナミック _CI_ グループを選択すると、グループ内のすべての _CI_ を可視化でき、変更グループがそれらの _CI_ をまとめて変更管理できるようになります。また、変更要求に不要な _CI_ は必要に応じて柔軟に削除できます。

1.  ヘッダーから、右クリックして **\[Refresh Impacted Services (影響を受けたサービスのリフレッシュ)\]**

を選択します。

1.  ヘッダーを右クリックし、**\[Reload form (フォームのリロード)\]** を選択します。

1.  **\[Impacted Services/CIs (影響するサービス/CI)\]** タブを選択し、変更グループが変更要求の影響を受けるサービスをすべて把握できるようになっていることを確認します。

**追加のトレーニング：**_Change Management_ と _CSDM_ に関する追加のプレゼンテーションについては、以下のビデオをご覧ください。

- - Change Management での CSDM の活用方法

## 課題：

学習したスキルを使用して、以下のタスクを実行します。

- 以下の情報に従って、新しい **Windows Server (Windows サーバー)** を手動で作成します。
    - Name (名前)： **SYD51-DC1-WIN12**
    - Operating System (オペレーティングシステム)： **Windows 2012 R2 Standard**
    - OS Version (OS バージョン)： **6.3.9600**

**注：** _\[Support group (_サポートグループ_)\]_、_\[Change Group (_変更グループ_)\]_、_\[Managed By Group (_管理担当者グループ_)\]_ の各フィールドには、現在のところ値は入力されていません。

- **\[System Definition (システム定義)\] > \[Scheduled Jobs (スケジュール済みジョブ)\]** に移動し、

### \[Update Query Based Services (クエリベースのサービスを更新する)\] レコードを検索して開き、

実行します。 (このジョブは、クエリ基準を満たす新しい CI を 1 回の実行につき最大 100 件まで CMDB グループに追加し、10 分ごとに実行されます)。

- **\[System Definition (システム定義)\] > \[Scheduled Jobs (スケジュール済みジョブ)\]** に移動し、 **\[CSDM Data Sync (CSDM データ同期)**\] レコードを検索して開き、実行します。(このジョブは、技術管理オファリングの \[Support group (サポートグループ)\]、\[Change Group (変更グループ)\]、 \[Managed By Group (管理担当者グループ)\] の値を、基礎となる CI に毎日同期します。)

- 手動で作成したレコードに、サービスオファリングで構成されたすべてのグループが含まれていることを確認します。

**注：** この例では、_\[Scheduled Jobs (_スケジュール済みジョブ_)\]_ を手動で実行しました。ただし、これらのジョブは定義されたスケジュールに従って自動的に実行されるため、基礎となる _CI_ 含むグループをシームレスに管理できます。

まとめると、ServiceNow のダイナミック CI グループは、Common Service Data Model (CSDM) の有効性を高める上で重要な役割を果たします。ダイナミック CI グループは、効率的なIT サービスの管理と運用に不可欠な、正確で一貫性があり、適切に整理された CI データの維持に役立ちます。 CI のグループ化と分類を自動化することで、ダイナミック CI グループは可視性の向上、運用効率の改善、業界のベストプラクティスとの整合性向上に貢献します。

この図は、オファリングで構成された \[Managed by group (管理担当者グループ)\] が、同じ CI クラスに対して CI クラスマネージャーで構成された \[Managed by group (管理担当者グループ)\] よりも優先されることを示しています。

**ラボ完了**

**お疲れさまでした！ このラボはこれで完了です。**
# デジタルポートフォリオ管理

**ラボ 4.01** 30 分

**ラボの目標**

Digital Portfolio Management (デジタルポートフォリオ管理) (DPM) は、オーナーがライフサイクル全体を通じて、Portfolio (ポートフォリオ)、Service (サービス)、Offering (オファリング)、および Product (製品) を包括的に把握し、一元的に管理できるようにする統合ワークスペースです。

DPM と Common Service Data Model (共通サービスデータモデル) (CSDM) は、連携するように設計されています。

CSDM に従ってモデル化されたサービスにより、DPM は明確なエンドツーエンドの可視化を提供できます。

- Service Portfolio (サービスポートフォリオ) → Taxonomy Node (分類ノード) → Service (サービス) → Offering (オファリング) → Infrastructure (インフラストラクチャ)

これにより意思決定が改善され、インシデント、要求、および変更に関するトレーサビリティが確保されます。

このラボで達成する目標は、次のとおりです。

- 基盤データを追加する
- Service Portfolio および Taxonomy Node を構成する
- Service Portfolio¥Taxonomy Node を Service に関連付ける
- Digital Portfolio Management Workspace (デジタルポートフォリオ管理ワークスペース) を確認する

- DPM KPI グループと KPI グループマッピングを構成する
- カスタム KPI グループと KPI グループマッピングを作成する

Service Portfolio の管理

# 基盤データを追加する

このセクションでは、グループを作成し、必要なロールをアサインし、ユーザーを追加して、Digital Portfolio Management (DPM) アプリケーション、モジュール、およびワークスペースへのアクセス権を付与します。 このユーザーアカウントは、システムアドミニストレーターアカウントと比較する目的でのみ使用されます。

- 1.  **\[User Administration (ユーザー管理)\] > \[Users (ユーザー)\]** に移動します。

- 1.  **\[New (新規)\]** を選択します。

- 1.  指定された情報に従って、新しいユーザーを作成します。

- - - User ID (ユーザー ID)： **CD.DPM Solution Owner (CD.DPM ソリューションオーナー)**

- - - First name (名)： **CD**

- - - Last name (姓)： **DPM Solution Owner (DPM ソリューションオーナー)**

- 1.  **\[Submit (送信)\]** を選択します。

- 1.  **\[User Administration (ユーザー管理)\] > \[Groups (グループ)\]** に移動します。

- 1.  **\[New (新規)\]** を選択します。

### \[Name (名前)\] フィールドに「CD-DPM Solution Owner Group (CD-DPM ソリューションオーナーグループ)」と入力します。

- 1.  レコードを保存します。

- 1.  **\[Group Members (グループメンバー)\]** 関連リストで、**\[Edit (編集)\]** を選択します。

### \[CD DPM Solution Owner (CD DPM ソリューションオーナー)\] と \[Abel Tuter\] を \[Group Members List (グループメンバーリスト)\] に追加します。

- 1.  **\[Save (保存)\]** を選択します。

- 1.  **\[Roles (ロール)\]** 関連リストで、**\[Edit (編集)\]** を選択します。

- 1.  **sn_dpm.dpm_manager** ロールと **portfolio_editor** ロールをグループに追加します。

- 1.  **\[Save (保存)\]** を選択します。

- 1.  フォームを更新して、新しいグループ、ロール、およびグループメンバーを表示します。

# Service Portfolio および Taxonomy Node を構成する

ServiceNow では、Service Portfolio と Taxonomy Node は、組織内のサービスを整理、管理、分類するために使用される主要な機能です。

ServiceNow の Service Portfolio は、サービスプロバイダーがライフサイクル全体を通じて管理するすべてのサービスを構造化して表したものです。戦略と設計から運用、廃止に至るまで、サービスを追跡し管理する上で役立ちます。

Taxonomy Node は、Service Portfolio 内のサービスを整理するために使用される階層的な分類要素です。共通の特性に基づいてサービスをグループ化するためのフォルダーまたはカテゴリとして捉えてください。

- 1.  **\[Service Portfolio Management (サービスポートフォリオ管理)\] > \[Service Portfolios (サービスポートフォリオ)\]** に移動します。
    2.  **\[New (新規)\]** を選択します。

- 1.  **\[Name (名前)\]** フィールドに「**CD-Service Portfolio (CD-サービスポートフォリオ)**」と入力します。

### \[Service portfolio owner (サービスポートフォリオオーナー)\] フィールドに「CD DPM Solution Owner (CD DPM ソリューションオーナー)」と入力します。

- 1.  **\[Submit (送信)\]** を選択します。

- 1.  **\[Service Portfolio Management (サービスポートフォリオ管理)\] > \[Taxonomy Nodes (分類ノード)\]** に移動します。
    2.  **\[New (新規)\]** を選択します。

- 1.  **\[Name (名前)\]** フィールドに「**CD-Taxonomy Node (CD-分類ノード)**」と入力します。

### \[Service portfolio (サービスポートフォリオ)\] フィールドに「CD-Service Portfolio (CD-サービスポートフォリオ)」と入力します。

- 1.  **\[Owned by (オーナー)\]** フィールドに「**CD DPM Solution Owner (CD DPM ソリューションオーナー)**」と入力します。
    2.  **\[Submit (送信)\]** を選択します。

1.  **Service Portfolio¥Taxonomy Node を Service に関連付ける**

ServiceNow の Service Builder (サービスビルダー) は、Service Portfolio や Taxonomy Node への適切なアサインを含め、Service と Offering の作成と構成を簡素化するために設計された、使いやすいツールです。

- 1.  **\[Service Portfolio Management (サービスポートフォリオ管理)\] > \[Service Builder (サービスビルダー)\]** に移動します。

### \[CD-Business Service (CD-ビジネスサービス)\] を開きます。

- 1.  **\[Details (詳細)\]** タブの **\[Service portfolio (サービスポートフォリオ)\]** に、以下のように入力します。

- - - Portfolio (ポートフォリオ)： **CD-Service Portfolio (CD-サービスポートフォリオ)**

- - - Node (ノード)： **CD-Taxonomy Node (CD-分類ノード)**

- 1.  **\[Review and Submit (レビューと送信)\]** タブを選択します。

- 1.  **\[Submit (送信)\]** を選択します。

### \[Return to my dashboard (自分のダッシュボードに戻る)\] を選択します。

- 1.  **\[CD-Technology Management Service (CD-技術管理サービス)\]** を開きます。

- 1.  **\[Details (詳細)\]** タブの **\[Service portfolio (サービスポートフォリオ)\]** に、以下のように入力します。

- - - Portfolio (ポートフォリオ)： **CD-Service Portfolio (CD-サービスポートフォリオ)**

- - - Node (ノード)： **CD-Taxonomy Node (CD-分類ノード)**

- 1.  **\[Review and Submit (レビューと送信)\]** タブを選択します。

- 1.  **\[Submit (送信)\]** を選択します。

- 1.  **\[Return to my dashboard (自分のダッシュボードに戻る)\]** を選択します。

# Digital Portfolio Management Workspace (デジタルポートフォリオ管理ワークスペース) を確認する

ServiceNow の Digital Portfolio Management (DPM) ワークスペースは、組織がビジネスサービスやテクニカルサービスをデジタル製品として管理できるように設計された専用インターフェイスです。 製品マネージャー、サービスオーナー、およびステークホルダーが、観念化から廃止までのライフサイクル全体にわたってサービスを戦略的に管理できるよう、一元化されたロールベースのワークスペースを提供します。

### \[Digital Portfolio Management Workspace (デジタルポートフォリオ管理ワークスペース)\] に移動します。

- 1.  **ホーム**アイコンを選択します。

**注：**システムアドミニストレーターとしてログインしているため、複数の _Service_ および _Offering_のオーナーであり、_DPM_ ロールを含むフルアクセス権を持っています。そのため、自分にアサインされているすべての _Service_ および _Offering_ を表示できます。

- 1.  **ホーム**アイコンの下にある**個人ポートフォリオ**アイコンを選択します。

**注：** _DPM_ ロールのいずれかを持つユーザーは誰でも、管理対象の _Business Application (_ビジネスアプリケーション_)_、_Service_、_Offering_ からなる個人用ポートフォリオを作成できます。

- 1.  **個人ポートフォリオ**アイコンの下にある**エンタープライズポートフォリオ**アイコンを選択します。

### \[Portfolio (ポートフォリオ)\] 選択リストから、\[CD-Service Portfolio (CD-サービスポートフォリオ)\] を選択します。

- 1.  **\[Lifecycle stages (ライフサイクルステージ)\]** フィルターから **\[All (すべて)\]** を選択します。

- 1.  Taxonomy node、Service、Offering など、ポートフォリオで利用可能なさまざまな要素を展開します。

- 1.  各ノードを選択し、**\[No performance metrics (パフォーマンスメトリクスなし)\]** というメッセージが表示されることを確認します。

**注：** この時点では、この _Service portfolio_ に _KPI_ が構成されていないため、_\[No performance metrics (_パフォーマンスメトリクスなし_)\]_ というメッセージが表示されます。

- 1.  **リスト**アイコンを選択します。

- 1.  各ノードを選択し、**\[Owned by me (自分が所有)\]** と **\[All (すべて)\]** のそれぞれに表示されるレコードを確認します。

**注：** _\[Owned by me (_自分が所有_)\]_ ノードのいずれかを選択すると、_\[Owned by (_オーナー_)\]_

フィールドで定義されている、自分が所有しているすべての _Service_、_Offering_、_Business application_、および _Application service_ が表示されます。 それ以外のすべての _Service_、 _Offering_、_Business application_ は、適切な _DPM_ ロールを持つユーザーであれば誰でも _\[All (_すべて_)\]_ ノードに表示されます。この時点では、システムアドミニストレーターは _Service Builder_で作成した _Service_ と _Offering_ のオーナーですが、_Abel Tuter_ は先に作成した _Business application_ と _Application service_ のオーナーです。

- 1.  **\[CD DPM Solution Owner (CD DPM ソリューションオーナー)\]** ユーザーの代理操作を行い、 **\[Digital Portfolio Management Workspace (デジタルポートフォリオ管理ワークスペース)\]** に移動し、各アイコンを確認します。あわせて、このユーザーのデフォルトのビューとアクセス権

を**システムアドミニストレーター**と比較して確認します。

- 1.  **\[Abel Tuter\]** ユーザーの代理操作を行い、**\[Digital Portfolio Management Workspace (デジタルポートフォリオ管理ワークスペース)\]** に移動し、各アイコンを確認します。あわせて、このユーザーのデフォルトのビューとアクセス権を**システムアドミニストレーター**および **CD DPM Solution**

**Owner** と比較して確認します。

**注：** _Abel Tuter_ は、先に _CD-Business Application (CD-_ビジネスアプリケーション_)_ と

_CD-Service Instance/Application Service (CD-_サービスインスタンス_/_アプリケーションサービス_)_ のオーナーとして構成されています。

- 1.  代理操作を終了し、次のセクションに進みます。

# DPM KPI グループと KPI グループマッピングを構成する

ServiceNow の Digital Portfolio Management (DPM) では、KPI グループと KPI グループマッピングを使用して、さまざまなタイプの Service、Offering、および Portfolio アイテムにわたって Key Performance Indicator (重要業績評価指標) (KPI) を整理、追跡、および適用します。 これにより、構造化された再利用可能でスケーラブルな方法で、サービスの健全性とパフォーマンスを測定し、レポートすることができます。

KPI グループは、論理的に関連するKPI を事前定義してまとめたもので、Service または Offering の特定の側面を評価するために使用されます。

KPI グループマッピングは、KPI グループを特定のタイプのService、Offering、または Taxonomy nodeに関連付けます。 これにより、どの KPI をどのサービスに自動的に適用するかを ServiceNow に指示できます。

- 1.  **\[Digital Portfolio Management (デジタルポートフォリオ管理)\] > \[KPI Groups (KPI グループ)\] > \[KPI Groups (KPI グループ)\]** に移動します。
    2.  **\[Performance snapshot (パフォーマンススナップショット)\]** レコードを検索して開きます。

**注：** この _KPI_ グループには _4_ つの _KPI_ が含まれており、_Service Portfolio_ タイプです。つまり、 _Service Portfolio_ の下の各子要素 _(Taxonomy_、_Service_、_Offering)_ にこれらの _KPI_ が継承されます。

- 1.  Cloud Dimensions の Service Portfolio をこの KPI グループに追加するには、**\[KPI Group Mappings (KPI グループマッピング)\]** 関連リストを選択します。
    2.  **\[New (新規)\]** を選択します。

### \[Service portfolio (サービスポートフォリオ)\] フィールドに \[CD-Service Portfolio (CD-サービスポートフォリオ)\] を追加します。

- 1.  **\[Submit (送信)\]** を選択します。

- 1.  **\[System Definition (システム定義)\] > \[Scheduled Jobs (スケジュール済みジョブ)\]** に移動します。

- 1.  **\[DPM: Daily Data Collection (DPM：日次データ収集)\]** ジョブを検索して開きます。

- 1.  フォーム上部にあるリンクの **\[here (こちら)\]** を選択し、フォームを編集します。

- 1.  前日から本日までのデータを収集するために、**\[Relative end (終了日 (相対))\]** の値を **0** に変更します。

**注：** この変更は、今日実施した作業が _KPI_ に確実に反映されるようにするため、トレーニング目的でのみ行っています。

- 1.  レコードを保存します。

- 1.  リンクの **\[here (こちら)\]** をもう一度選択してフォームを編集し、**\[Execute Now (今すぐ実行)\]** を選択してデータ収集を開始します。

### \[Digital Portfolio Management Workspace (デジタルポートフォリオ管理ワークスペース)\] に移動します。

- 1.  **エンタープライズポートフォリオ**アイコンを選択します。

### \[Portfolio (ポートフォリオ)\] 選択リストから、\[CD-Service Portfolio (CD-サービスポートフォリオ)\] を選択します。

- 1.  **\[Lifecycle stages (ライフサイクルステージ)\]** フィルターから **\[All (すべて)\]** を選択します。

- 1.  Taxonomy node、Service、Offering など、ポートフォリオで利用可能なさまざまな要素を展開します。
    2.  各ノードを選択し、4 つの KPI を含む **\[Performance snapshot (パフォーマンススナップショット)\]** KPI グループが表示されることを確認します。

**注：** _\[CD-Technology Management Service Offering (CD-_技術管理サービスオファリング_)\]_が選択されている場合、前のラボで作成されたインシデントが _\[Open incident (_オープンインシデント_)\]_ の下に表示されます。

- 1.  **\[CD-Technology Management Service Offering (CD-技術管理サービスオファリング)\]** ノードを選択した後、右上の **\[View details (詳細を表示)\]** ボタンを選択します。

- 1.  **\[Run (実行)\]** タブを選択し、**CD-Service Instance/Application Service** への依存関係を含む同じ **\[Performance snapshot KPIs (パフォーマンススナップショット KPI)\]** が表示されることを確認します。

# カスタム KPI グループと KPI グループマッピングを作成する

- 1.  **\[Digital Portfolio Management (デジタルポートフォリオ管理)\] > \[KPI Groups (KPI グループ)\]** \>

**\[KPI Groups (KPI グループ)\]** に移動します。

- 1.  **\[New (新規)\]** を選択します。

- 1.  **\[Name (名前)\]** フィールドに「**CD-KPI Group (CD-KPI グループ)**」と入力します。

### \[Type (タイプ)\] を \[Service portfolios (サービスポートフォリオ)\] に変更します。

**注：** _\[Type (_タイプ_)\]_ フィールドは、_KPI_ を計算するレベルを決定するため、重要です。 たとえば、_\[Service (_サービス_)\]_ が選択されている場合、_KPI_ データは _Service portfolio_ や _Taxonomy_

のレベルではなく、_Service_ と _Offering_ についてのみ計算されます。

- 1.  \[Order (オーダー)\] を **200** に更新します。

- 1.  レコードを保存します。

- 1.  Cloud Dimensions の Service Portfolio をこの KPI グループに追加するには、**\[KPI Group Mappings (KPI グループマッピング)\]** 関連リストを選択します。
    2.  **\[New (新規)\]** を選択します。

### \[Service portfolio (サービスポートフォリオ)\] フィールドに \[CD-Service Portfolio (CD-サービスポートフォリオ)\] を追加します。

- 1.  **\[Submit (送信)\]** を選択します。
    2.  このグループに KPI を追加するには、**\[KPIs\]** 関連リストを選択します。

- 1.  **\[New (新規)\]** を選択します。

- 1.  **\[KPI\]** フィールドから、**\[DPM: Number of new incidents (DPM：新規インシデントの数)\]** を検索して選択します。
    2.  **\[Label (ラベル)\]** フィールドを **\[New Incidents (新規インシデント)\]** に更新します。

- 1.  KPI に構成できる **\[Chart type (グラフのタイプ)\]** と **\[Time range (時間範囲)\]** のさまざまなオプションを確認します。
    2.  **\[Submit (送信)\]** を選択します。

## 課題：

指定された情報に従って、**\[CD-KPI Group (CD-KPI グループ)\]** の 2 番目の KPI を構成します。

### KPI： DPM: Number of new changes (DPM：新規変更の数)

- - - Label (ラベル)： **New Changes (新規変更)**

- - - Order (オーダー)： **200**

- - - Chart type (グラフのタイプ)： **Time Series (時系列)： Line (線グラフ)**

### \[DPM: Daily Data Collection (DPM：日次データ収集)\] ジョブを実行します。

- - - **\[Digital Portfolio Management Workspace (デジタルポートフォリオ管理ワークスペース)\]** から、**\[CD-Technology Management Service Offering (CD-技術管理サービスオファリング)\]** レコードの詳細を表示し、**\[Run (実行)\]** タブで、前のラボで作成した新しいインシデントを含め、新しい CD-KPI グループとそのメトリクスが表示されていることを確認します。

**注：** 新しい _KPI_ グループを表示するには、フォームの更新が必要になる場合があります。

### \[Digital Portfolio Management Workspace (デジタルポートフォリオ管理ワークスペース)\] から、\[CD-Business Service Offering (CD-ビジネスサービスオファリング)\] レコードの詳細を表示し、\[Run (実行)\] タブで、前のラボで作成した新しい変更を含め、新しい CD-KPI グループとそのメトリクスが表示されていることを確認します。

- - - **\[Digital Portfolio Management Workspace (デジタルポートフォリオ管理ワークスペース)\]** から、**\[CD-Service Portfolio (CD-サービスポートフォリオ)\]** レコードの詳細を表示し、**\[Overview (概要)\]** タブで、Service portfolio ビューにロールアップされて表示されている新しいインシデントと変更を含め、新しい **CD-KPI グループ**とそのメトリクスが表示されていることを確認します。

まとめると、CSDM ガイドラインに従うことで、DPM はより強力かつ正確になり、ビジネスに整合したものになります。その結果、組織はデジタルサービスを、適切に構造化された製品ポートフォリオのように管理できるようになります。

**ラボ完了**

**お疲れさまでした！ このラボはこれで完了です。**
# Integrate CSM with SPM

**Lab 5.01** 30m

# Lab objectives

The ServiceNow® Customer Service Management (CSM) product enables you to provide the service and support that your external customers need. For example, your customers can communicate and receive support through the web, email, chat, telephone, and social media.

Integrating ServiceNow Customer Service Management (CSM) with Service Portfolio Management (SPM), in alignment with the Common Service Data Model (CSDM), creates major strategic and operational value by ensuring that customer-facing service delivery is accurately tied to the underlying services your organization offers, maintains, and evolves. CSDM provides the standard framework and data model to support this alignment, enabling consistent, reliable service mapping and reporting across the enterprise.

In this lab, you achieve the following objectives:

- Use CSM Guided Setup for Integration between CSM with SPM
- Configure the Service Offering form
- Configure the Product Models form
- Configure the Account form
- Personalize Sold Product form
- Personalize Case form
- View Realized Outcomes

Service Consumption Domain

# A. CSM Guided Setup for Integration between CSM with SPM

Customer Service Management provides an integration with the Service Portfolio Management (SPM) application. This integration gives customer service managers, customer service agents, and service owners visibility into sold products and their service offerings.

1.  Navigate **Customer Service > Administration > Guided Setup.**

1.  If any alerts display, remove them.

1.  Select **Get Started**.
2.  Scroll down, and under the **Integration with Service Portfolio Management (SPM**) section, select **Get Started**.

**Note**_: There are two tasks required. The first task to Activate Customer Service with Service Portfolio Management (SPM) store application has been previously completed and setup on your instance._

1.  To the right of the first task, select **Mark as Complete**.

1.  For the **Configure Form Views** task, select each of the configuration requirements to gain insight into the requirements to complete this task.

**NOTE**_: In the next section you will complete these configurations._

## Configure the Service Offering Form

In this section you will add the Subscribed by Customers (Sold Product -> Service

offering) related list to provide service owners visibility into which customers have subscribed to which service offerings.

1.  Navigate to **CSDM > Sell and Consume > Business Service Offering**.

1.  Search for and open the **CD-Business Service Offering** record.

1.  From the **Additional actions** menu, select **Configure > Related Lists**.

1.  Select **Edit this view** to make updates.

1.  Search for and move **Sold Product -> Service Offering** from the **Available** to the **Selected** pane to gain visibility of the customers who are subscribed to this offering to assist with impact analysis.
2.  Search for and move **Task -> Service Offering** from the **Available** to the **Selected** pane to gain visibility of incidents opened against the offering.

**Note:** _If two Service Offering related lists display, add the one that appears first in the list._

1.  Select **Save**.

1.  If any alerts display, select **Dismiss All**.

1.  Verify two new related lists called **Subscribed by Customers** and **Tasks** are visible.

**NOTE**_: Any CSM sold product, customer account, product model and incident that is associated with a Business Service Offering will now be visible from the new related lists._

## Configure Product Models Form

In this section you will add the Service Offerings (Offering -> Model ID) related list on the Product Model/Service Model forms to enable customer service managers to associate service offerings to product models.

1.  Navigate to **Customer Service > Products > Product Models**.

1.  Search for and open **CD-Product Model**.

**NOTE**_: A CD-CSM Customer Account, CD-Model Category, and CD-Product Model record were previously configured on your instance. The steps performed would be required for each product model where an offering would be associated._

1.  From the **Additional actions** menu, select **Configure > Related Lists**.

1.  Search for and add **Offering->Model ID** from the **Available** to **Selected** pane.

1.  Select **Save**.

1.  Verify a new **Offerings** related list now displays.

**NOTE**_: Currently the Offering tab only provides the option to create new offerings associated with a product model versus selecting an existing offering. In the next steps you will add the Edit option to the related list._

1.  Under the **Offerings** tab, to the right of the **Name** column, select the **Column option** menu and select **Configure > List Control**.

1.  Deselect the **Omit edit button** checkbox.

1.  Select the **Enable Edit** button.

**NOTE**_: This transaction may take over a minute to complete. Be patient._

1.  After the transaction completes, select **Update**.

1.  Under the **Offerings** tab, verify the **Edit** button is now available.

1.  Select the **Edit** button.
2.  Search for **CD-Business Service Offering** and move it from the **Collection** to **Offerings List**

pane.

1.  Select **Save**.

**NOTE**_: Now a business service offering can be associated with an existing product model._

## Account Form

In this section you will add the Service Offering column to the Sold Products related list to enable customer service agents or managers to view service offerings associated to the sold product for an account or consumer.

1.  Navigate to **Customer Service > Customer > Accounts**.

1.  Open the **CD-CSM Customer Account** record.

1.  Under the **Sold Products** related list, select the **Personalize List** option.

1.  Search for and add **Service Offering** to the **Selected** pane.

1.  Select **OK**.

**NOTE:** _From the account form, for each sold product, the associated offering can now be visible._

## Sold Product Form

In this section you will add the Service Offering field to the Sold Product form to enable customer service managers to associate a service offering to a sold product for an account or consumer.

1.  Navigate to **Customer Service > Products > Sold Products**.

1.  Select **New**.

1.  Right-click the header and choose **Configure > Form Layout**.

1.  From the pop-up, select **Not Now**.

1.  Select **Edit this section**.

1.  Search for and add **Service Offering** from the **Available** pane to the **Select** pane under

### Parent Sold Product.

1.  Select **Save**.

**NOTE**_: Now a Sold Product can reference a Business Service offering._

1.  Configure the form using the information provided:

- - Name: **CD-Sold Product**
    - Product: **CD-Product Model**
    - Service Offering: **CD-Business Service Offering**

- - Account: **CD-CSM Customer Account**

1.  Select **Submit**

**NOTE**_: Now a Sold Product can reference a Business Service offering._

## Case Form

In this section you will add the Service Offering field for the Sold Product to the Case form. This enables customer service agents dealing with customer issues to see the service offering associated to sold product for which a case was opened.

1.  Navigate to **Customer Service > Cases > Create New**.

1.  Personalize the form and under **Install Base**, add **Sold Product** and **Sold Product.Service Offering**.

**Note**_: Sold Product.Service Offering can be found after expanding the Sold Product reference field within the editor._

**Note**_: It is up to the customer and implementer to determine if Service Offering should be added to the case form. It is being added only to showcase the link between sold product and the sold product’s service offering._

1.  Complete the form using the provide information:

- - Sold Product: **CD-Sold Product**
    - Contact: **CD-Contact FN CD-Contact LN**
    - Account: **CD-CSM Customer Account**
    - Product: **CD-Product Model**
    - Service offering: **CD-Business Service Offerings**

**NOTE**_: Entering the Sold Product, auto populates the other fields except for contact._

1.  Save the record.

1.  Select **Submit** to create the customer case.

# B. Escalate Case to an Incident

1.  From the case, select the **Additional actions** menu and choose **Create Incident**.

1.  From the new incident record, verify the contact came across automatically and that the work notes contain a reference to the case number.
2.  From the **Customer Cases** related list, verify the case the incident was created from is referenced.
3.  In the **Service Offering** field, enter **CD-Business Service Offering**.

1.  In the **Short Description**, enter **This incident was created from a case record**.

1.  Save the record.

# Realized Outcomes

Configuring CSM with SPM within the guidance of CSDM bring about several key outcomes.

### Incident

1.  From the new incident record to the right of the **Service Offering** field, select the **Preview this record** icon.

1.  Select **Open Record**.
2.  Select the **Subscribed by Customers** related list to view the customer(s) impacted by this offering.
3.  Select the **Tasks** related list to view the new incident associated with the business service offering.

**Note** _the Subscribed by Customers and tasks related lists are populated and provide valuable insights into customer impacted by the incident and previous cases._

1.  Under the **Tasks** related list, select the referenced incident record.
2.  From the Incident record, under the **Customer Cases** related list, confirm you have visibility to the case record associated to the offering.

### Customer Account

1.  Navigate to **Customer Service > Customer > Accounts.**
2.  Open the **CD-CSM Customer Account** record.

1.  Select the **Sold Products** related list and verify that the subscribed sold product and its associated business service offering are visible.

In summary, by following CSDM guidelines, integrating ServiceNow Customer Service Management (CSM) with Service Portfolio Management (SPM) creates major strategic and operational value by ensuring that customer-facing service delivery is accurately tied to the underlying services your organization offers, maintains, and evolves.

# Lab Complete

**Congratulations! You have completed this lab.**
