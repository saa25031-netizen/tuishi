<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>推し紹介サイト - 石鎚黒茶</title>
    <style>
        /* 全体のスタイル設定 */
        body {
            font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', Meiryo, sans-serif;
            background-color: #f4ece1; /* 温かみのあるお茶のようなベージュ */
            color: #3e2723; /* 深みのあるブラウンの文字色 */
            margin: 0;
            padding: 0;
            line-height: 1.8;
        }

        /* ヘッダー・メインタイトルのスタイル */
        header {
            background-color: #2e4d34; /* 石鎚黒茶の茶葉や自然をイメージした深い緑 */
            color: #ffffff;
            text-align: center;
            padding: 40px 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        h1 {
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: 2px;
        }

        /* コンテンツ全体のコンテナ */
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 0 20px;
        }

        /* 紹介文のスタイル */
        .description {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            margin-bottom: 30px;
            border-left: 6px solid #8d6e63;
        }

        .description p {
            margin: 0 0 15px 0;
            font-size: 1.1rem;
        }
        .description p:last-child {
            margin-bottom: 0;
        }

        /* 画像エリアのスタイル */
        .image-container {
            text-align: center;
            margin: 30px 0;
            background-color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            display: block;
            margin: 0 auto;
            width: 100%;
            max-height: 500px;
            object-fit: cover;
        }

        .image-caption {
            font-size: 0.9rem;
            color: #6d4c41;
            margin-top: 10px;
            font-style: italic;
        }

        /* 箇条書き（おすすめ・活用法）のスタイル */
        .recommendations {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            margin-bottom: 30px;
        }

        h2 {
            color: #2e4d34;
            border-bottom: 2px solid #2e4d34;
            padding-bottom: 8px;
            margin-top: 0;
            font-size: 1.5rem;
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 15px;
            font-size: 1.05rem;
        }

        li strong {
            color: #8d6e63;
        }

        /* ボタン・リンクエリアのスタイル */
        .button-container {
            text-align: center;
            margin-top: 40px;
            margin-bottom: 40px;
        }

        .btn {
            display: inline-block;
            background-color: #8d6e63; /* 落ち着いた茶色 */
            color: #ffffff;
            padding: 15px 30px;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 30px;
            transition: background-color 0.3s, transform 0.2s;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .btn:hover {
            background-color: #2e4d34; /* ホバー時に深い緑に変化 */
            transform: translateY(-2px);
        }

        /* フッター */
        footer {
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
            color: #6d4c41;
            border-top: 1px solid #d7ccc8;
            margin-top: 60px;
        }
    </style>
</head>
<body>

    <!-- 一番大きい見出し（ヘッダー） -->
    <header>
        <h1>石鎚黒茶</h1>
    </header>

    <div class="container">
        
        <!-- 特徴や魅力（3行以上） -->
        <section class="description">
            <p>石鎚黒茶（いしづちくろちゃ）は、愛媛県西条市で古くから作られている、日本でも大変珍しい「後発酵茶（こうはっこうちゃ）」の一種です。</p>
            <p>職人の手によって二段階の異なる発酵プロセス（カビによる発酵と乳酸菌による発酵）を経て丁寧に作られており、独特の爽やかな酸味と、まろやかで奥深い味わいが特徴です。</p>
            <p>生産者が一時激減し「幻のお茶」とも呼ばれましたが、地域の情熱的な努力によって復活を遂げ、今ではその希少性と健康価値の高さから多くの人々に愛されています。</p>
        </section>

        <!-- 画像表示エリア（大きく表示） -->
        <section class="image-container">
            <!-- 実際の画像ファイル名に合わせて src を書き換えてください -->
            <img src="ishidzuchi_kurocha.jpg" alt="石鎚黒茶のイメージ画像">
            <div class="image-caption">幻の発酵茶、石鎚黒茶</div>
        </section>

        <!-- おすすめの食べ方や活用法（箇条書き3個以上） -->
        <section class="recommendations">
            <h2>おすすめの飲み方・活用法</h2>
            <ul>
                <li><strong>定番のストレート（ホット＆アイス）：</strong> まずはそのまま淹れて、石鎚黒茶ならではの独特な甘酸っぱい風味とすっきりとした後味をじっくりとお楽しみください。冷やして飲むのも夏場におすすめです。</li>
                <li><strong>スイーツと一緒に：</strong> 甘い和菓子はもちろん、チョコレートやチーズケーキなどの洋菓子とも相性抜群です。お茶の酸味がスイーツの甘みを引き立て、口の中をさっぱりとさせてくれます。</li>
                <li><strong>お茶漬けや料理の出汁として：</strong> 石鎚黒茶の持つほのかな酸味と旨味は、お米や出汁との相性も非常に良いです。贅沢な「黒茶茶漬け」にしたり、豚肉の煮込み料理のベースに使うとさっぱりと仕上がります。</li>
            </ul>
        </section>

        <!-- 外部サイトへ飛ぶボタン（2つ） -->
        <section class="button-container">
            <a href=https://ehm-saijo-ah.esnet.ed.jp/" class="btn" target="_blank" rel="noopener noreferrer">西条農業高校</a>
            <a href=https://www.city.saijo.ehime.jp/" class="btn" target="_blank" rel="noopener noreferrer">石鎚黒茶</a>
        </section>

    </div>

    <footer>
        <p>&copy; 2026 石鎚黒茶 推し紹介ファンサイト</p>
    </footer>

</body>
</html>
