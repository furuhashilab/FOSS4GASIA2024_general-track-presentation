# Localization of FOSS4G Tools and Building an Open Knowledge Platform in Japanese University Education
日本の大学教育におけるFOSS4Gツールの多言語化とオープンナレッジ・プラットフォームの構築

## GDAL
* QGISマニュアルの翻訳
* po fileを使用したGDAL翻訳

## Youth
* SDGsの翻訳
* JOSMのバリデーション

## Abstract
Furuhashi Lab has been working on OSM mapping and Mapathon as YouthMappers AGU under the theme of "Participatory Mapping and Social Contribution". Here is a look back at our specific activities in 2024. Three months from March to June, we participated in the OSM Validation training of UN MAPS. We achieved the promotion of all 12 students in our lab to intermediate OSM Mappers. Based on the knowledge learned, we also created a graphic recording about JOSM Validation and published it on GitHub. In April, we participated in "International Humanitarian Mapathon 2024" and competed with universities and organizations from more than 5 countries including USC and UCLA. In June, we held Wheelmap's Mapathon to learn how we can use maps to contribute to society. We are also working on the translation of "Open Mapping towards Sustainable Development Goals" as part of our year-round activities to promote the activities of YouthMappers. We are also planning to participate in other Mapathons and Hakkathons in the future.

Throughout our year-long activities, we have been faced with the challenge that there is a large gap in understanding depending on the amount of knowledge and language level of individuals. As newcomers to the geospatial information industry, we had little prerequisite knowledge and were unfamiliar with tools such as the QGIS manual, GDAL, and JOSM, which are commonplace for advanced mappers. The most difficult thing for us Japanese was that the manuals for understanding these tools were mostly in English, and we found ourselves in a situation where we could not understand them even if we read them because of their many technical terms. It was not easy to keep the manuals close at hand and look at the actual screens and operate them at the same time.

For this reason, this presentation will introduce the usefulness of translation and visualization for problems such as unfamiliarity with computer operation, inability to understand manuals due to lack of knowledge in the field, and resistance to learning in a language other than one's native tongue. In particular, we recognize that overcoming language barriers is of paramount importance. As examples, we will discuss the translation of the QGIS manual and GDAL, and the creation of a graticule for the JOSM Validation Training. We will then publish those deliverables on GitHub to create an open knowledge platform.

First of all, in the rapidly evolving field of geospatial technology, access to comprehensive and understandable documentation is crucial for both new and experienced users. However, language barriers often limit access to valuable resources. To bridge this gap, students from the Furuhashi Lab at Aoyama Gakuin University's "Applied Spatial Information Science III" course are working to localize technical documents for FOSS4G (Free and Open Source Software for Geospatial) tools such as QGIS and GDAL. These tools are widely used for geospatial data manipulation, analysis, and visualization, but much of their documentation is predominantly available in English. By translating these documents into Japanese, we aim to increase accessibility for Japanese-speaking users and contribute to a deeper understanding of geospatial technologies.

Our approach in the course begins with understanding the functionalities of QGIS and GDAL, followed by practical exercises to familiarize participants with basic operations. This practical experience forms the foundation for translating technical documents, helping participants effectively understand the content. We use tools such as Transifex for collaborative translation efforts, ensuring consistency and accuracy across documents. However, the current complexity of registering an account on Transifex poses a challenge. To address this, we have created a Markdown-based "QGIS Documentation Japanese Translation Manual" within a GitHub repository, where students document the steps and share insights, including potential pitfalls. This helps in facilitating collaborative information sharing.

The content of the guide follows the format outlined by the Japan Translation Federation (JTF)’s “Translation Guidelines,” which is essential for the success of translation projects involving open data. By building an open knowledge platform using GitHub, both users and instructors can better understand the tendencies that beginners may encounter with these tools. The FAQ and other resources on this platform allow participants to easily create, edit, and publish markdown documents, helping them mentally simulate the actual working environment. Furthermore, gaining this experience helps foster a culture of open knowledge sharing within the academic community, where students can exchange the skills needed to effectively manage digital documentation.

Regarding GDAL, we focus on translating .po files within GitHub.

This project demonstrates that localization and open knowledge platforms can bridge the gap between technology and language, serving as a gateway to fostering geospatial literacy. We aim to share this project at the FOSS4G International Conference, contributing to the geospatial community and promoting more accessible geospatial information literacy.
Second, Furuhashi Lab continues to input data into OpenStreetMap for emergency rescue efforts and as a contribution to areas without maps.

Creating and providing accurate maps requires not only proper instruction but also mastery of the editing tools used. In addition, using JOSM is an efficient way to input and validate huge amounts of data in OSM without errors.

JOSM (Java OpenStreetMap Editor) is an advanced OSM desktop editor, written in Java, that only works on Windows and Mac. And the printed manual is difficult for beginners to understand, and they often have trouble even getting the tool to work in the first place.

On the other hand, Visual information has the advantage of overcoming language barriers and differences due to prerequisite knowledge and can convey information intuitively. Furuhashi Lab uses graphic recording method as a means to achieve this.

Twelve students from Furuhashi Lab participated in the "OSM Data Validation Training Proposal" sponsored by UN Mappers over a three-month period from March to June. However, students who were not used to working with computers had a hard time just installing the system, and most of the students who participated actually faced problems. The graphic recording was created in such a situation. The graphic recording created in this situation did not capture the essence of the lecture, so we had to redo it. Afterwards, the video was reviewed and newly redrawn, which is now available to the whole world on GitHub.

Using the example of the graphic recording at JOSM Validation, I will introduce the usefulness of visualization in Japanese university education.

## 和訳
古橋研究室は「参加型地図と社会貢献」をテーマに、YouthMappersAGUとしてOSMのマッピングやマッパソンに取り組んでいます。2024年の活動を振り返って具体的な活動について紹介します。3月から6月の3カ月間、UN MAPSのOSM Validation Traningに参加しました。研究室に所属する12名の学生全員のOSMの中級マッパー昇格を達成しました。また、学んだ知識をもとにJOSM Validationについてのグラレコを作成してGitHubに公開しています。また、4月には、International Humanitarian Mapathon 2024に参加し、USCやUCLAなど世界5カ国の大学・団体と競い合いました。6月にはWheelmapのMapathonを開催して、地図を用いてどのように社会に貢献できるか日々学んでいます。そして、通年の作業として"Open Mapping towards Sustainable Development Goals" の和訳作業を行い、YouthMappersの活動を広める活動をしています。この後もMapathonへの参加やHakkathonの開催を企画しています。

1年間の活動を通して、個人の知識量や言語レベルによって理解の差が大きくなってしまうことが課題となっていました。地理空間情報の業界に飛び込んできたばかりの私たちは、前提知識が少なく、QGISやGDAL、JOSMといった上級者のマッパーにとっては当たり前のツールにも不慣れでした。日本人の私たちが最も苦労したことが、それらのツールを理解するためのマニュアルがほとんど英語であり、さらに専門用語が多いため読んでも分からない状態に陥ってしまったことでした。マニュアルを手元に置きつつ、実際の画面を見て同時に操作することも、簡単ではありませんでした。

そのため、この発表では、パソコン操作に不慣れである、その道の知識がなくマニュアルが理解できない、母語以外の言語で学習することには抵抗がある、といったトラブルに対し、翻訳やビジュアライゼーションが有用であるという紹介をします。特に言語の壁を越えることは最重要であると認識しています。例として、QGISマニュアル・GDALの翻訳とJOSM Validation Traningのグラレコ作成を取り上げます。そして、それらの成果物をGitHubに公開することで、オープンナレッジプラットフォームの構築を目指します。

はじめに、急速に進化する地理空間技術の分野では、新規ユーザーと経験豊富なユーザーの両方にとって、包括的で理解しやすいドキュメントへのアクセスが重要です。しかし、言語の壁が貴重なリソースへのアクセスを制限することが多々あります。このギャップを埋めるため、青山学院大学の「応用空間情報学Ⅲ（Applied Spatial Information Science III）」講座では、Furuhashi Labの学生が主体となり、QGISやGDALなどのFOSS4G（Free and Open Source Software for Geospatial）ツールの技術文書を日本語化しようと試みています。これらのツールは地理空間データの操作、分析、可視化に広く使用されていますが、その多くのドキュメントは主に英語で提供されています。これを日本語に翻訳することで、日本語話者のユーザーのアクセスを増やし、地理空間技術の理解を深めることに貢献できると考えています。

講座でのアプローチは、まずQGISとGDALの機能を理解し、その後、参加者が基本的な操作に慣れるための実践的な演習を行います。この実践的な経験は技術文書の翻訳の基盤となり、参加者がコンテンツを効果的に理解するのを助けます。私たちはTransifexなどのツールを使用して協力翻訳を行います。この翻訳ツールを使うことで、文書の一貫性と正確性を確保しています。しかし、現状Transifexのアカウント登録方法が複雑なことが問題として挙げられます。そこで、実際に生徒が手を動かしてつまずいた箇所をGitHubに立てたリポジトリ内にMarkdown記法で、「QGIS Documentation 日本語翻訳作業マニュアル」として、注意事項など盛り込み、作業の情報共有を図っています。

ガイド内容は、の「翻訳ガイドライン」に則った形式で手順を追います。オーブンデータの翻訳において、翻訳プロジェクトの成功に不可欠です。
このようなGitHubを利用したオープンナレッジプラットフォームを構築することで、ツール初心者が陥りやすい傾向をユーザー側も指導者側も把握できるようになります。このプラットフォームのFAQなどを一読すれば、参加者がマークダウン形式のドキュメントを作成、編集、公開し、実際の作業環境を頭でシミュレートしやすくなります。さらにこの経験を積むことは、デジタルドキュメントを効果的に管理するために必要なスキルを学生間で提供し合う、学術コミュニティ内でオープンナレッジシェアリングの文化を育みます。

また、GDALに関しては、GitHub内のpoファイルを翻訳しています。

このプロジェクトは、多言語化とオープンナレッジプラットフォームが、技術と言語のギャップを埋め、より安易な地理空間情報リテラシー醸成への入り口としての機能をつくることにつながります。FOSS4G国際会議にて、このプロジェクトを共有し、地理空間コミュニティへの貢献を目標にしています。

次に、古橋研究室では、緊急時の救助活動や地図のない地域への貢献として、OpenStreetMapへのデータの入力を続けています。

正確な地図を作成し提供するためには適切なインストラクションだけではなく、使用する編集ツールを使いこなすことも必要です。そして、OSMで膨大なデータをミスなく入力・検証するには、JOSMを使うことが効率的です。

JOSM (Java OpenStreetMap Editor)は、上級者向けのOSMのデスクトップエディターであり、Javaで書かれているので、WindowsとMacでしか作動しません。そして、活字のマニュアルは初心者にとっては難解で、そもそものツールを動作させることさえ上手くいかない場合が多いのが現状です。

一方で、視覚的な情報は言語の壁や前提知識の有無による差を乗り越えて、情報を直感的に伝達できるというメリットがあります。その手段として古橋研究室ではグラレコを用いています。

古橋研究室の学生12名は、3月から6月の約3カ月間に渡って、UN Mappers主催の「OSM Data Validation Training Proposal」に参加しました。しかし、パソコン作業に不慣れな学生はインストールをするだけでも一苦労であり、実際に参加した学生のほとんどがトラブルに直面しました。JOSM Validationのレクチャーもリアルタイム且つ英語で行われたため、参加頻度やリスニング能力によって、学生の理解度に差が出てしまいました。その状態で作成したグラレコは、本質を突いたものにならなかったのでやり直しとなりました。その後、動画を見直して新しく描き直したものが、GitHubで全世界に公開されています。

JOSM Validationのグラレコを例にして、日本の大学教育におけるビジュアライゼーションの有用性について紹介します。


## description

### QGIS translation manual

The "QGIS Documentation Japanese Translation Manual 2024" is an in-depth guide created by the Furuhashi Lab to support students and participants in translating QGIS Desktop user guides into Japanese using Transifex. QGIS, a widely used open-source GIS software, often has documentation primarily available in English, creating a language barrier for Japanese users. This manual addresses these challenges by providing step-by-step instructions on how to use Transifex, a translation management platform commonly adopted by open-source projects.

The manual begins by explaining the importance of QGIS's internationalization efforts (i18n) and why Japanese translations are crucial for expanding accessibility. It details the account registration process on Transifex, highlighting potential pitfalls and solutions, such as using GitHub to bypass certain registration restrictions. Additionally, the guide includes best practices for project participation and managing translation workflows to ensure high-quality outputs.

A key feature of the guide is its emphasis on collaboration through GitHub. By leveraging GitHub, participants can document their work, share insights, and address common issues encountered during translation. The GitHub repository serves as an open knowledge platform, encouraging participants to engage in discussions, post FAQs, and create markdown documents that simulate real-world collaboration. This environment helps both beginners and experienced users alike to enhance their skills, providing a hands-on learning experience that goes beyond traditional classroom instruction.

The manual also follows the Japan Translation Federation (JTF)’s “Translation Guidelines,” ensuring that the translation efforts meet professional standards, particularly when dealing with open data. It breaks down the specific steps involved in translating QGIS documentation, including how to navigate po files within GitHub, a critical component for managing translations in GDAL. The guide also provides troubleshooting tips and common solutions, helping users maintain consistency and accuracy across all translated materials.

Furthermore, the manual explores the use of Sphinx, a documentation generation tool, which helps in publishing the translated documents while maintaining their original structure and quality. The Sphinx internationalization features are particularly highlighted, demonstrating how translated content can be managed effectively within a professional framework.

Overall, this project aims to bridge the language gap in geospatial technology by creating a comprehensive resource that supports the Japanese translation of essential QGIS documentation. By fostering an open knowledge-sharing culture, the initiative empowers students and participants to contribute meaningfully to the broader geospatial community. The project’s ultimate goal is to present these efforts at the FOSS4G International Conference, showcasing the impact of localization and collaborative learning on enhancing geospatial literacy for Japanese-speaking users.

For a complete guide and more details, please visit the page [here](https://github.com/furuhashilab/foss4gi18nJP/wiki/QGIS-Documentation-%E6%97%A5%E6%9C%AC%E8%AA%9E%E7%BF%BB%E8%A8%B3%E4%BD%9C%E6%A5%AD%E3%83%9E%E3%83%8B%E3%83%A5%E3%82%A2%E3%83%AB-2024).

### GDAL translation

GDAL (Geospatial Data Abstraction Library) is a versatile library and command-line tool used for converting and manipulating raster and vector data. It supports a wide range of geospatial data formats and is essential for data conversion, processing, and analysis in various GIS applications. The translation rules for GDAL documentation are aligned with those established for QGIS, ensuring consistency across these geospatial tools. GDAL translations are managed using po files on GitHub, facilitating collaborative updates and refinements. This approach allows contributors to work together efficiently, ensuring the documentation remains accurate and relevant.

By managing translations on GitHub, the GDAL community leverages version control, making it easier to track changes, address errors, and maintain high standards of quality across all translated content. This process enhances accessibility for Japanese-speaking users, promoting broader use of GDAL in academic, professional, and research environments. The GitHub repository serves as an open platform for sharing translation progress, encouraging community engagement, and providing a centralized location for all translation-related activities. This collaborative effort ensures that GDAL's powerful features are accessible to a wider audience, contributing to the overall growth and understanding of geospatial technology in different languages.

---

### The Usefulness of Visualization in University Education - Using the JOSM Validation Hackathon as an Example

Furuhashi Lab uses Graphic recording as a visualization method to reliably communicate information in a way that is easy for anyone to understand. Graphic recording is “a method of summarizing the content of a meeting or presentation using graphics such as pictures and figures ([OPTAGE for Business, 2023](https://optage.co.jp/business/contents/article/20231115.html)"). Since the main points and conclusions are visualized, it has the advantage of being easier to understand and more memorable than text-only information and is useful for stimulating discussion and reviewing. Above all, since the information is recorded in pictures rather than text, anyone in the world can intuitively understand the content. At the Furuhashi Laboratory, we actively use the system to summarize the content of weekly classes and to keep a record of individual work. One experience in which Graphic Recording was particularly helpful in understanding the content was the “UN Mappers Validation JOSM Follow-up Hackathon” initiative in June.

Furuhashi Lab. participated in the “OSM Data Validation Training Proposal” organized by UN Mappers from March. Every Wednesday at 22:00 (JLT), we received lectures on OSM Validation via Zoom. 12 students attended the lectures for 2 months from March to May, but none of them could attend all of them and understand the contents. The reason was that the lectures were given in English and the content was for advanced students.

After all lectures were finished, in June, we held a “UN Mappers Validation JOSM Follow-up Hackathon” to summarize the lectures in our lab, with the goal of summarizing how to use JOSM for validation purposes in graphic recording, and publishing the completed graphic recording on Git Hub. The goal was to publish the completed graphic recording on Git Hub. The 12 students were divided into 4 teams: Installation, JOSM Basic Operation, Validation Basics, and Validation Application. The materials used for reference were the UN Mappers online lecture archive videos and the JOSM Validation document stored in the [UN Maps Learning Hub](https://mappers.un.org/learning/).

First, in the installation section, we summarized the JOSM operation check and the linkage with Tasking Manager. The completed graphic recording is [here](https://github.com/furuhashilab/V-F_UN-Validation/issues/5). Next, in the JOSM Basic Operations section, we focused on the basic operations of JOSM, how to use the Building Plugin, and how to modify the shape of buildings (right-angled and snapped nodes) to create graphic recording. The completed graphic recording is [here](https://github.com/furuhashilab/Drone_UN-Validation/blob/main/README.md). In the Validation Basics section, we summarized the JOSM validator tool (validation) and the TODO plugin. The completed graphic recording is [here](https://github.com/furuhashilab/Design-UN-validation/issues/1). Finally, in the Validation application section, we summarized two methods: how to use Osmose and how to validate with JOSM using the Overpass layer. The completed graphic recording is [here](https://github.com/furuhashilab/Youth_JOSM-Validation).

There was an obstacle in making the graphic recording public. The resolution of the first graphic recording was low, and except for the JOSM Basic Operations section, the graphic recordings of the three teams were not fully understandable because they were just copies of the lectures. For the students whose native language is Japanese, this may have been due to the fact that the lecture was given in English. Therefore, the lectures were redrawn, and the corrected versions are now available to the world (the aforementioned URL is also the corrected graphic recording version).

Although the students rarely reviewed lectures other than the items for which they were responsible, they were able to gain some understanding of how to do JOSM Validation by looking at a series of graphic recordings created by each team. As a result, all 12 students passed the JOSM Validation verification test provided by UN Maps. This result, which could not have been achieved by lectures in English alone, was made possible by the fact that graphic recording helped the students learn by extracting and organizing the necessary information.

This experience shows that graphic recording is a useful visualization tool in Japanese university education for understanding content explained in languages other than Japanese and in fields outside one's own expertise.

## Poster
[FOSS4G_Shiori,Aki_presentation_v2.pdf](https://github.com/user-attachments/files/18098593/FOSS4G_Shiori.Aki_presentation_v2.pdf)
