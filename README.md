<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tiêu đề bài viết - My Blog</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&family=Playfair+Display:wght@400;500;700&family=Fira+Code&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Libre Baskerville', serif;
            line-height: 1.7;
            max-width: 760px;
            margin: 0 auto;
            padding: 2rem;
            color: #2d2d2d;
            background-color: #fffce8;
            font-size: 14px;
        }

        .book-container {
            background-color: #fffce8;
            margin: 0 auto;
            max-width: 650px;
        }

        /* Back link */
        .back-link {
            display: inline-block;
            margin-bottom: 2rem;
            color: #268bd2;
            text-decoration: none;
            font-size: 0.9rem;
            border-bottom: 1px solid rgba(107, 91, 53, 0.3);
            transition: all 0.2s;
        }

        .back-link:hover {
            color: #4a3f24;
            border-bottom-color: rgba(74, 63, 36, 0.7);
        }

        header {
            margin-bottom: 3rem;
            padding-bottom: 1.5rem;
            border-bottom: 2px solid #d3c6a6;
            text-align: center;
        }

        header h1 {
            margin-bottom: 1rem;
            font-family: 'Playfair Display', serif;
            font-weight: 700;
            font-size: 2rem;
            color: #483c32;
            line-height: 1.3;
        }

        .header-ornament {
            display: block;
            margin: 1rem auto;
            font-size: 1.5rem;
            color: #927e5a;
        }

        .post-meta {
            font-size: 0.9rem;
            color: #927e5a;
            font-style: italic;
            text-align: center;
        }

        main {
            padding: 1rem 0;
        }

        article {
            margin-bottom: 3rem;
        }

        article p:first-of-type::first-letter {
            font-size: 3.5em;
            font-family: 'Playfair Display', serif;
            font-weight: 700;
            float: left;
            line-height: 0.8;
            margin-right: 0.4rem;
            color: #483c32;
        }

        h2 {
            text-align: center;
            font-family: 'Playfair Display', serif;
            font-size: 1.5rem;
            margin-top: 3rem;
            margin-bottom: 2rem;
            color: #483c32;
        }

        h2::before, h2::after {
            content: "❦";
            color: #927e5a;
            font-size: 1.2rem;
            margin: 0 0.8rem;
        }

        h3 {
            font-family: 'Playfair Display', serif;
            font-size: 1.2rem;
            margin-top: 2rem;
            margin-bottom: 1rem;
            color: #483c32;
        }

        p {
            margin: 1.5rem 0;
            line-height: 1.8;
            text-align: justify;
        }

        .separator {
            text-align: center;
            margin: 2rem auto;
            font-size: 1.5rem;
            color: #927e5a;
        }

        pre {
            border-radius: 0;
            margin: 2rem 0;
            padding: 1.5rem;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            background: #4b474a;
            border: 1px solid #483c32;
            overflow-x: auto;
        }

        code {
            font-family: 'Fira Code', monospace;
            font-size: 0.95rem;
            line-height: 1.6;
            color: #f8f8f2;
        }

        :not(pre) > code {
            background: #ebe5d8;
            padding: 0.2rem 0.4rem;
            border-radius: 0;
            font-size: 0.9em;
            color: #2d2d2d;
            border: 1px solid #d3c6a6;
        }

        a {
            color: #268bd2;
            text-decoration: none;
            transition: color 0.2s ease;
            border-bottom: 1px solid rgba(107, 91, 53, 0.3);
        }

        a:hover {
            color: #4a3f24;
            border-bottom-color: rgba(74, 63, 36, 0.7);
        }

        blockquote {
            margin: 2rem 0;
            padding: 1rem 1.5rem;
            border-left: 3px solid #927e5a;
            background: #fffef5;
            font-style: italic;
            color: #483c32;
        }

        ul, ol {
            margin: 1.5rem 0;
            padding-left: 2rem;
        }

        li {
            margin: 0.5rem 0;
            line-height: 1.8;
        }

        img {
            max-width: 100%;
            height: auto;
            margin: 2rem auto;
            display: block;
            border: 1px solid #d3c6a6;
        }

        footer {
            margin-top: 4rem;
            padding-top: 2rem;
            border-top: 2px solid #d3c6a6;
            text-align: center;
            font-size: 0.9rem;
            color: #927e5a;
        }

        .footer-ornament {
            margin: 1rem auto;
            font-size: 1.2rem;
            color: #927e5a;
        }

        @media (max-width: 768px) {
            body {
                padding: 1rem;
                font-size: 15px;
            }

            header h1 {
                font-size: 1.6rem;
            }

            pre {
                padding: 1rem;
                font-size: 0.85rem;
            }
        }
    </style>
</head>
<body>
    <div class="book-container">
        <a href="../index.html" class="back-link">← Về trang chủ</a>

        <header>
            <h1>Tiêu đề bài viết của bạn</h1>
            <span class="header-ornament">❦</span>
            <div class="post-meta">20 Tháng 1, 2026 • 5 phút đọc</div>
        </header>

        <main>
            <article>
                <p>
                    Đây là đoạn mở đầu của bài viết với chữ cái đầu tiên được làm đẹp (drop cap). 
                    Bạn có thể viết giới thiệu về chủ đề mà bạn muốn chia sẻ trong bài viết này.
                </p>

                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod 
                    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, 
                    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                </p>

                <h2>Phần 1: Giới thiệu</h2>

                <p>
                    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore 
                    eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, 
                    sunt in culpa qui officia deserunt mollit anim id est laborum.
                </p>

                <h3>Mục con 1.1</h3>

                <p>
                    Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium 
                    doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore 
                    veritatis et quasi architecto beatae vitae dicta sunt explicabo.
                </p>

                <p>Ví dụ về list:</p>
                <ul>
                    <li>Điểm thứ nhất quan trọng</li>
                    <li>Điểm thứ hai cần lưu ý</li>
                    <li>Điểm thứ ba để tham khảo</li>
                </ul>

                <div class="separator">✦</div>

                <h2>Phần 2: Code và ví dụ</h2>

                <p>
                    Bạn có thể thêm inline code như <code>function example()</code> hoặc code blocks:
                </p>

                <pre><code>def greet(name):
    """Hàm chào mừng đơn giản"""
    return f"Xin chào, {name}!"

# Sử dụng hàm
message = greet("Thế giới")
print(message)</code></pre>

                <p>
                    At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis 
                    praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias 
                    excepturi sint occaecati cupiditate non provident.
                </p>

                <blockquote>
                    "Đây là một quote nổi bật hoặc điểm quan trọng mà bạn muốn nhấn mạnh 
                    trong bài viết của mình."
                </blockquote>

                <h2>Kết luận</h2>

                <p>
                    Đây là phần kết luận của bài viết. Bạn có thể tổng kết lại những điểm chính 
                    hoặc đưa ra những suy nghĩ cuối cùng về chủ đề đã thảo luận.
                </p>

                <p>
                    Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, 
                    sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
                </p>
            </article>
        </main>

        <footer>
            <div class="footer-ornament">❦</div>
            <p>© 2026 My Blog • Made with ♥</p>
            <p><a href="../index.html">Về trang chủ</a></p>
        </footer>
    </div>
</body>
</html>