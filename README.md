# Blogplace
Blog site
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>협업 블로그 | 함께 만드는 이야기</title>
    
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_ADSENSE_PUBLISHER_ID"
         crossorigin="anonymous"></script>
    
    <style>
        body { font-family: 'Malgun Gothic', sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #333; color: white; padding: 1em 0; text-align: center; }
        header a { color: white; text-decoration: none; margin: 0 15px; }
        .container { width: 90%; max-width: 1200px; margin: 20px auto; display: flex; flex-wrap: wrap; }
        .main-content { flex: 3; min-width: 60%; padding-right: 20px; }
        .sidebar { flex: 1; min-width: 300px; background-color: white; padding: 15px; border-radius: 5px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); }
        .blog-post { background-color: white; padding: 20px; margin-bottom: 20px; border-radius: 5px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); }
        .post-meta { font-size: 0.9em; color: #666; margin-bottom: 10px; }
        .post-meta strong { font-weight: bold; }
        .ads-slot { background-color: #fff8e1; border: 1px solid #ffecb3; padding: 10px; margin-bottom: 20px; text-align: center; }
        footer { background-color: #333; color: white; text-align: center; padding: 1em 0; margin-top: 20px; }
        
        /* 작성자 별로 스타일링을 다르게 하려면 이 부분에 CSS 추가 */
        .author-name { font-style: italic; color: #007bff; }
    </style>
</head>
<body>

    <header>
        <h1>[attachment_0](attachment) 협업 블로그</h1>
        <nav>
            <a href="#">홈</a>
            <a href="#">글 작성 (로그인 필요)</a> <a href="#">작성자 목록</a>
            <a href="#">문의</a>
        </nav>
    </header>

    <div class="container">
        
        <div class="main-content">
            
            <div class="blog-post">
                <h2>첫 번째 협업 게시글 제목</h2>
                <p class="post-meta">
                    작성자: <span class="author-name">김 작성자</span> | 
                    날짜: 2025년 9월 28일
                </p>
                <p>
                    이곳은 첫 번째 게시글의 내용입니다. 여러 작성자가 자유롭게 로그인하여 글을 작성하고 수정할 수 있는 시스템이 백엔드에서 구현되어야 합니다.
                </p>
                <a href="#">더 읽기...</a>
            </div>

            <div class="ads-slot">
                <p>여기에 **인-아티클 광고** 코드를 삽입하세요.</p>
                </div>

            <div class="blog-post">
                <h2>두 번째 작성자의 최신 글</h2>
                <p class="post-meta">
                    작성자: <span class="author-name">이 공동저자</span> | 
                    날짜: 2025년 9월 27일
                </p>
                <p>
                    새로운 작성자의 글이 자동으로 메인 페이지에 표시되도록 시스템을 설계해야 합니다. 각 작성자의 이름은 고유하게 표시됩니다.
                </p>
                <a href="#">더 읽기...</a>
            </div>
            
        </div>

        <aside class="sidebar">
            <h3>최신 작성자</h3>
            <ul>
                <li>김 작성자</li>
                <li>이 공동저자</li>
                <li>박 기여자</li>
            </ul>
            
            <div class="ads-slot">
                <p>여기에 **디스플레이 광고** 코드를 삽입하세요.</p>
                </div>
        </aside>
    </div>

    <footer>
        <p>&copy; 2025 협업 블로그. 모든 권리 보유.</p>
    </footer>

</body>
</html>
