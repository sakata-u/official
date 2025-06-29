<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>坂田和真 | Personal Website</title>

    <style>
        /* 基本的なスタイル */
        body {
            font-family: sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4; /* 全体の背景色 */
            color: #333;
        }

        .container {
            width: 80%; /* デスクトップでの表示幅 */
            max-width: 1200px; /* 最大幅 */
            margin: 0 auto;
            padding: 20px 0;
        }

        header {
            background-color: transparent; /* ヘッダーの背景色を透明に */
            color: #333; /* ヘッダーのテキスト色をbodyと同じに調整 */
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 5px 0 0;
            font-size: 1.1em;
        }

        section {
            background-color: transparent; /* セクションの背景色を透明に */
            margin-bottom: 20px;
            padding: 30px;
            border-radius: 8px;
            box-shadow: none; /* セクションの影をなくす */
        }

        h2 {
            color: #007bff;
            border-bottom: 2px solid #eee;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            margin-bottom: 10px;
        }

        ul li a {
            color: #007bff;
            text-decoration: none;
        }

        ul li a:hover {
            text-decoration: underline;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }

        /* --- ここからがスマホ対応の重要な部分です --- */

        /* メディアクエリ: 画面幅が768px以下の場合に適用されるスタイル */
        @media (max-width: 768px) {
            .container {
                width: 95%; /* スマホでは幅を広げる */
                padding: 10px 0; /* パディングを調整 */
            }

            header h1 {
                font-size: 2em; /* スマホではフォントサイズを小さく */
            }

            header p {
                font-size: 1em; /* スマホではフォントサイズを小さく */
            }

            section {
                padding: 20px; /* スマホではパディングを小さく */
            }

            h2 {
                font-size: 1.5em; /* スマホではセクションタイトルを小さく */
            }
        }

        /* さらに小さい画面（例: 480px以下）にも対応する場合 */
        @media (max-width: 480px) {
            header h1 {
                font-size: 1.8em;
            }

            header p {
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>Kazuma Sakata</h1>
            <p>Web Developer / Designer</p>
        </div>
    </header>

    <main class="container">
        <section class="profile">
            <h2>About Me</h2>
            <p>
                例こんにちは、坂田和真です。東京を拠点に活動するWebデベロッパーです。
                ユーザーフレンドリーで視覚的に魅力的なウェブサイトやアプリケーションを構築することに情熱を注いでいます。
                特にJavaScript、React、Node.jsを使った開発を専門としており、常に新しい技術やベストプラクティスを学ぶことに意欲的です。
                休日は、新しいプログラミング言語を試したり、都内のカフェ巡りを楽しんでいます。
            </p>
        </section>

        <section class="works">
            <h2>Works / Portfolio</h2>
            <ul>
                <li><a href="https://example.com/project-a" target="_blank">Eコマースサイト</a> - レスポンシブデザインに対応したオンラインストア構築プロジェクトです。</li>
                <li><a href="https://github.com/kazuma-sakata/personal-blog" target="_blank">パーソナルブログエンジン</a> - Markdownサポートと軽量CMSを備えたカスタムビルドのブログエンジンです。Node.jsとExpressで開発しました。</li>
                <li><a href="https://example.com/mobile-app-concept" target="_blank">コンセプトモバイルアプリ：Tokyo Food Guide</a> - 東京の飲食店を案内するモバイルアプリケーションのUI/UXデザインとプロトタイプです。Figmaでデザインしました。</li>
            </ul>
        </section>

        <section class="contact">
            <h2>Contact</h2>
            <p>ご連絡は以下のリンクからお願いします。</p>
            <ul>
                <li><a href="https://github.com/your-github-username" target="_blank">GitHub</a></li>
                <li><a href="https://twitter.com/your-twitter-username" target="_blank">Twitter</a></li>
                <li><a href="mailto:your.email@example.com">Email</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 坂田和真. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
