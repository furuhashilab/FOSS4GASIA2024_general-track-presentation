# FOSS4GASIA2024_generalspeaking
# 日本の大学教育におけるFOSS4Gツールの多言語化とオープンナレッジフォームの構築

## GDAL
* QGISマニュアルの翻訳
* po fileを使用したGDAL翻訳

## Youth
* SDGsの翻訳
* JOSMのバリデーション

## Abstract
Title: Localization of FOSS4G Tools and Building an Open Knowledge Platform in Japanese University Education

Furuhashi Lab has been working on OSM mapping and Mapathon as YouthMappersAGU under the theme of "Participatory Mapping and Social Contribution". Here is a look back at our specific activities in 2024. Three months from March to June, we participated in the OSM Validation Traning of UN MAPS. We achieved the promotion of all 12 students in our lab to intermediate OSM Mappers. Based on the knowledge learned, we also created a graphic recording about JOSM Validation and published it on GitHub. In April, we participated in "International Humanitarian Mapathon 2024" and competed with universities and organizations from more than 5 countries including USC and UCLA. In June, we held Wheelmap's Mapathon to learn how we can use maps to contribute to society. We are also working on the translation of "Open Mapping towards Sustainable Development Goals" as part of our year-round activities to promote the activities of YouthMappers. We are also planning to participate in other Mapathons and Hakkathons in the future.

Throughout our year-long activities, we have been faced with the challenge that there is a large gap in understanding depending on the amount of knowledge and language level of individuals. As newcomers to the geospatial information industry, we had little prerequisite knowledge and were unfamiliar with tools such as the QGIS manual, GDAL, and JOSM, which are commonplace for advanced mappers. The most difficult thing for us Japanese was that the manuals for understanding these tools were mostly in English, and we found ourselves in a situation where we could not understand them even if we read them because of their many technical terms. It was not easy to keep the manuals close at hand and look at the actual screens and operate them at the same time.

For this reason, this presentation will introduce the usefulness of translation and visualization for problems such as unfamiliarity with computer operation, inability to understand manuals due to lack of knowledge in the field, and resistance to learning in a language other than one's native tongue. In particular, we recognize that overcoming language barriers is of paramount importance. As examples, we will discuss the translation of the QGIS manual and GDAL, and the creation of a graticule for the JOSM Validation Training. We will then publish those deliverables on GitHub to create an open knowledge platform.

In the rapidly evolving field of geospatial technology, access to comprehensive and understandable documentation is crucial for both new and experienced users. However, language barriers often limit access to valuable resources. To bridge this gap, students from the Furuhashi Lab at Aoyama Gakuin University's "Applied Spatial Information Science III" course are working to localize technical documents for FOSS4G (Free and Open Source Software for Geospatial) tools such as QGIS and GDAL. These tools are widely used for geospatial data manipulation, analysis, and visualization, but much of their documentation is predominantly available in English. By translating these documents into Japanese, we aim to increase accessibility for Japanese-speaking users and contribute to a deeper understanding of geospatial technologies.

Our approach in the course begins with understanding the functionalities of QGIS and GDAL, followed by practical exercises to familiarize participants with basic operations. This practical experience forms the foundation for translating technical documents, helping participants effectively understand the content. We use tools such as Transifex for collaborative translation efforts, ensuring consistency and accuracy across documents. However, the current complexity of registering an account on Transifex poses a challenge. To address this, we have created a Markdown-based "QGIS Documentation Japanese Translation Manual" within a GitHub repository, where students document the steps and share insights, including potential pitfalls. This helps in facilitating collaborative information sharing.

The guide content follows the format of JTF’s “Translation Guidelines,” which is essential for the success of translation projects involving open data. By building an open knowledge platform using GitHub, both users and instructors can better understand the tendencies that beginners may encounter with these tools. The FAQ and other resources on this platform allow participants to easily create, edit, and publish markdown documents, helping them mentally simulate the actual working environment. Furthermore, gaining this experience helps foster a culture of open knowledge sharing within the academic community, where students can exchange the skills needed to effectively manage digital documentation.

We also explore the capabilities of Sphinx, a documentation generation tool, to publish our translated materials. By leveraging Sphinx's internationalization features, we ensure that our translations maintain the quality and structure of the original documents.

This project demonstrates that localization and open knowledge platforms can bridge the gap between technology and language, serving as a gateway to fostering geospatial literacy. We aim to share this project at the FOSS4G International Conference, contributing to the geospatial community and promoting more accessible geospatial information literacy.

Furuhashi Lab continues to input data into OpenStreetMap for emergency rescue efforts and as a contribution to areas without maps.

Creating and providing accurate maps requires not only proper instruction but also mastery of the editing tools used. In addition, using JOSM is an efficient way to input and validate huge amounts of data in OSM without errors.

JOSM (Java OpenStreetMap Editor) is an advanced OSM desktop editor, written in Java, that only works on Windows and Mac. And the printed manual is difficult for beginners to understand, and they often have trouble even getting the tool to work in the first place.

On the other hand, Visual information has the advantage of overcoming language barriers and differences due to prerequisite knowledge and can convey information intuitively. Furuhashi Lab uses the graphic recording as a means to achieve this.

Twelve students from Furuhashi Lab participated in the "OSM Data Validation Training Proposal" sponsored by UN Mappers over a three-month period from March to June. However, students who were not used to working with computers had a hard time just installing the system, and most of the students who participated actually faced problems. The graphic recording was created in such a situation. The graphic recording created in this situation did not capture the essence of the lecture, so we had to redo it. Afterwards, the video was reviewed and newly redrawn, which is now available to the whole world on GitHub.

Using the example of the graphic recording at JOSM Validation, I will introduce the usefulness of visualization in Japanese university education.

## 和訳
タイトル: 日本の大学教育におけるFOSS4Gツールの多言語化とオープンナレッジプラットフォームの構築

急速に進化する地理空間技術の分野では、新規ユーザーと経験豊富なユーザーの両方にとって、包括的で理解しやすいドキュメントへのアクセスが重要です。しかし、言語の壁が貴重なリソースへのアクセスを制限することが多々あります。このギャップを埋めるため、青山学院大学の「応用空間情報学Ⅲ（Applied Spatial Information Science III）」講座では、Furuhashi Labの学生が主体となり、QGISやGDALなどのFOSS4G（Free and Open Source Software for Geospatial）ツールの技術文書を日本語化しようと試みています。これらのツールは地理空間データの操作、分析、可視化に広く使用されていますが、その多くのドキュメントは主に英語で提供されています。これを日本語に翻訳することで、日本語話者のユーザーのアクセスを増やし、地理空間技術の理解を深めることに貢献できると考えています。

講座でのアプローチは、まずQGISとGDALの機能を理解し、その後、参加者が基本的な操作に慣れるための実践的な演習を行います。この実践的な経験は技術文書の翻訳の基盤となり、参加者がコンテンツを効果的に理解するのを助けます。私たちはTransifexなどのツールを使用して協力翻訳を行います。この翻訳ツールを使うことで、文書の一貫性と正確性を確保しています。しかし、現状Transifexのアカウント登録方法が複雑なことが問題として挙げられます。そこで、実際に生徒が手を動かしてつまずいた箇所をGitHubに立てたリポジトリ内にMarkdown記法で、「QGIS Documentation 日本語翻訳作業マニュアル」として、注意事項など盛り込み、作業の情報共有を図っています。

ガイド内容は、JTFの「翻訳ガイドライン」に則った形式で手順を追います。オーブンデータの翻訳において、翻訳プロジェクトの成功に不可欠です。
このようなGitHubを利用したオープンナレッジプラットフォームを構築することで、ツール初心者が陥りやすい傾向をユーザー側も指導者側も把握できるようになります。このプラットフォームのFAQなどを一読すれば、参加者がマークダウン形式のドキュメントを作成、編集、公開し、実際の作業環境を頭でシミュレートしやすくなります。さらにこの経験を積むことは、デジタルドキュメントを効果的に管理するために必要なスキルを学生間で提供し合う、学術コミュニティ内でオープンナレッジシェアリングの文化を育みます。

また、翻訳した資料を公開するために、ドキュメント生成ツールであるSphinxの機能も探ります。Sphinxの国際化機能を活用することで、翻訳が元の文書の品質と構造を維持できるようにします。

このプロジェクトは、多言語化とオープンナレッジプラットフォームが、技術と言語のギャップを埋め、より安易な地理空間情報リテラシー醸成への入り口としての機能をつくることにつながります。FOSS4G国際会議にて、このプロジェクトを共有し、地理空間コミュニティへの貢献を目標にしています。


古橋研究室では、緊急時の救助活動や地図のない地域への貢献として、OpenStreetMapへのデータの入力を続けています。

正確な地図を作成し提供するためには適切なインストラクションだけではなく、使用する編集ツールを使いこなすことも必要です。そして、OSMで膨大なデータをミスなく入力・検証するには、JOSMを使うことが効率的です。

JOSM (Java OpenStreetMap Editor)は、上級者向けのOSMのデスクトップエディターであり、Javaで書かれているので、WindowsとMacでしか作動しません。そして、活字のマニュアルは初心者にとっては難解で、そもそものツールを動作させることさえ上手くいかない場合が多いのが現状です。

一方で、視覚的な情報は言語の壁や前提知識の有無による差を乗り越えて、情報を直感的に伝達できるというメリットがあります。その手段として古橋研究室ではグラレコを用いています。

古橋研究室の学生12名は、3月から6月の約3カ月間に渡って、UN Mappers主催の「OSM Data Validation Training Proposal」に参加しました。しかし、パソコン作業に不慣れな学生はインストールをするだけでも一苦労であり、実際に参加した学生のほとんどがトラブルに直面しました。JOSM Validationのレクチャーもリアルタイム且つ英語で行われたため、参加頻度やリスニング能力によって、学生の理解度に差が出てしまいました。その状態で作成したグラレコは、本質を突いたものにならなかったのでやり直しとなりました。その後、動画を見直して新しく描き直したものが、GitHubで全世界に公開されています。

JOSM Validationのグラレコを例にして、日本の大学教育におけるビジュアライゼーションの有用性について紹介します。
