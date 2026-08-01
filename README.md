## Odinbook
英語の後に日本語が続きます。

🌟 Highlights
- A clone project of Facebook. You need to create an account / login before you can access anything.
- Devise is used to securely create and login users.
- Uses Omniauth for easy sign-ups and logins.
- Images are stored using Google Cloud Storage and it's API.
- Active Storage and Mini Magick are used to process images.
- The website is hosted on Render.com (free tier). The postgres database to store user, post, and comment information is also provided from Render.com. 
- You may ask to follow other users. If they accept your request, then you will be able to view their created posts.


ℹ️ Overview
This project is the Capstone project of the Ruby on Rails course from [The Odin Project - Odinbook](https://www.theodinproject.com/lessons/ruby-on-rails-odin-book). It demonstrates the author's ability to start from zero, visualize the project, it's setup, break up everything into smaller steps and work towards completion. 
Although design/CSS is not required for the curriculum as it is a backend focused project, styling and additional layouts were added to ensure the project has a nice similar styling on multiple sized screens.


💻 Tech Stack: 
- Backend: Ruby on Rails 8
- Frontend: HTML5, CSS3, Hotwire (Turbo)
- Database: PostgreSQL
- Deployment: [Render.com](https://render.com/)
- API: OmniAuth, Google Cloud Storage

✍️ Author 
My name is Conor, I'm an aspiring web developer with a keen interest in both backend and frontend. 
You can find more about me on: 
- [My website](https://coffee-kiwi.github.io/) 
- [LinkedIn](https://www.linkedin.com/in/conor-seo-35a3b299/)


🚀 Usage
- To try out the application, please go to: [odinbook-jiuf.onrender.com](https://odinbook-jiuf.onrender.com/)
- Note that, it is hosted on the free tier. Therefore, it can take up to a minute to load the page. 
- Upon loading, an error may occur (e.g. 502). Please don't worry. 
Please reload or refresh the page a few times and it will show. 


💭 Feedback and Contributing
Please feel free to leave any comments or report any bug fixes in the [discussions section](https://github.com/coffee-kiwi/rails-odinbook/discussions).

Also, if you'd like to ask any questions or have any ideas for improvements, feel free to share them here as well!

🌟 主な特徴
- Facebookのクローンプロジェクトです。コンテンツにアクセスするには、アカウント作成またはログインが必要です。
- ユーザーの安全なアカウント作成とログイン機能の実装には、Deviseを使用しています。
- 手軽なサインアップ・ログインを実現するために、Omniauthを導入しています。
- 画像の保存には、Google Cloud StorageとそのAPIを利用しています。
- 画像処理には、Active StorageとMini Magickを使用しています。
- ウェブサイトはRender.com（無料プラン）でホストされています。ユーザー、投稿、コメントの情報を保存するPostgreSQLデータベースも、同じくRender.comで提供されています。
- 他のユーザーにフォローリクエストを送ることができます。相手がリクエストを承認すると、そのユーザーが作成した投稿を閲覧できるようになります。

ℹ️ 概要
本プロジェクトは、[The Odin Project - Odinbook](https://www.theodinproject.com/lessons/ruby-on-rails-odin-book) の Ruby on Rails コースにおける集大成（キャップ​​ストーン）プロジェクトです。ゼロからプロジェクトを構想・セットアップし、タスクを細分化して完成へと導く能力を示すものです。
バックエンドに重点を置いたプロジェクトであるため、カリキュラム上、デザインやCSSの実装は必須ではありませんでした。しかし、様々な画面サイズで適切に表示されるよう、スタイリングやレイアウトの調整を行っています。


💻 技術スタック:
- バックエンド: Ruby on Rails 8
- フロントエンド: HTML5, CSS3, Hotwire (Turbo)
- データベース: PostgreSQL
- デプロイ: [Render.com](https://render.com/)
- API: OmniAuth, Google Cloud Storage

✍️ 著者
Conor（コナー）です。バックエンドとフロントエンドの両方に強い関心を持つ、Web開発者志望です。
詳細はこちらをご覧ください:
- [個人サイト](https://coffee-kiwi.github.io/)
- [LinkedIn](https://www.linkedin.com/in/conor-seo-35a3b299/)

🚀 使用法
- アプリケーションを試すには、[odinbook-jiuf.onrender.com](https://odinbook-jiuf.onrender.com/) にアクセスしてください。
- 無料枠でホストされていることに注意してください。したがって、ページの読み込みに最大 1 分かかることがあります。
- ロード時にエラーが発生する場合があります (例: 502)。ご心配なく。
ページを数回リロードまたは更新すると表示されます。


💭 フィードバックと貢献
[ディスカッション セクション](https://github.com/coffee-kiwi/rails-odinbook/Discussions) にお気軽にコメントを残していただくか、バグ修正を報告してください。

また、ご質問や改善のアイデアがございましたら、お気軽にここで共有してください。

⚠️ 困難だった点と解決策
-初めてTurbo Streamsを使った際、必要となる数多くの小さなファイルや、それらをどのように実装・接続すればよいのかを理解するのに苦労しました。
-また、ローカル環境ではスムーズに動作していたものの、デプロイ後に予期せぬエラーが多数発生しました。大規模なプロジェクトをデプロイするのは初めてだったため、それらの対処には困難を伴いました。

✅ 解決策：
- Hotwireに関しては、ドキュメントを熟読し、理解できるまでカリキュラムの要点を繰り返し確認しながら進めました。
- デプロイに関しては、イベントログに多数のエラーが表示されましたが、一度に一つの問題に絞り、原因を理解した上でコードを修正していくことで解決しました。途中、Renderのサポートチームに連絡して質問を行う必要もありました。