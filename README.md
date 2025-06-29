<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>坂田和真 | Personal Website</title>

    <style>
        /* 基本的なスタイル（必要に応じて調整） */
        body {
            font-family: sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .container {
            width: 80%; /* デスクトップでの表示幅 */
            max-width: 1200px; /* 最大幅 */
            margin: 0 auto;
            padding: 20px 0;
        }

        header {
            background-color: #333;
            color: #fff;
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
            background-color: #fff;
            margin-bottom: 20px;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
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

            /* 必要に応じて他の要素も調整 */
        }
    </style>
    </head>
<body>
    <header>
        <div class="container">
            <h1>[坂田和真]</h1>
            <p>[あなたの肩書や簡単な説明 例: Web Developer / Designer]</p>
        </div>
    </header>

    <main class="container">
        <section class="profile">
            <h2>About Me</h2>
            <p>
                [ここに自己紹介文を記述します。どのようなことに興味があり、何をしているのかなどを自由に書いてください。]
            </p>
        </section>

        <section class="works">
            <h2>Works / Portfolio</h2>
            <ul>
                <li><a href="[作品1のリンク]" target="_blank">[作品名1]</a> - [作品の簡単な説明]</li>
                <li><a href="[作品2のリンク]" target="_blank">[作品名2]</a> - [作品の簡単な説明]</li>
                <li><a href="[作品3のリンク]" target="_blank">[作品名3]</a> - [作品の簡単な説明]</li>
            </ul>
        </section>

        <section class="contact">
            <h2>Contact</h2>
            <p>ご連絡は以下のリンクからお願いします。</p>
            <ul>
                <li><a href="https://github.com/[あなたのGitHubユーザー名]" target="_blank">GitHub</a></li>
                <li><a href="https://twitter.com/[あなたのTwitterユーザー名]" target="_blank">Twitter</a></li>
                <li><a href="mailto:[example@gmail.com]">Email</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 [坂田和真]. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
