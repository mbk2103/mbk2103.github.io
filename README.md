# mbk2103.github.io
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kişisel Web Sayfası</title>
    <style>
        body {
            font-family: Verdana, sans-serif;
            color: #333;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007acc;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #eee;
            padding: 1em 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #007acc;
        }
        section {
            padding: 2em;
            margin: 2em auto;
            max-width: 800px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #007acc;
            color: white;
        }
        h2 {
            color: #007acc;
        }
        .project {
            border-top: 1px solid #eee;
            padding-top: 1em;
            margin-top: 1em;
        }
        .contact-info {
            margin-top: 2em;
        }
        .contact-info a {
            color: #007acc;
            text-decoration: none;
        }
        .media-container {
            margin-top: 2em;
        }
        .media-container iframe,
        .media-container .medium-preview {
            width: 100%;
            margin: 1em 0;
        }
        .medium-preview {
            border: 1px solid #ddd;
            padding: 1em;
        }
        .medium-preview h3 {
            margin: 0;
            font-size: 1.2em;
            color: #007acc;
        }
        .medium-preview p {
            font-size: 0.9em;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Burak'ın Kişisel Web Sayfası</h1>
    </header>
    <nav>
        <a href="#hakkimda">Hakkımda</a>
        <a href="#egitim">Eğitim</a>
        <a href="#is-deneyimi">İş Deneyimi</a>
        <a href="#projeler">Projeler</a>
        <a href="#iletisim">İletişim</a>
    </nav>
    <section id="hakkimda">
        <h2>Hakkımda</h2>
        <p>Kendimi sürekli geliştirmeye ve öğrenmeye her zaman açık bir birey olarak tanıtabilirim. Yenilikleri keşfetmek benim için büyük bir zevktir. Bu nedenle seyahat etmek, tiyatro izlemek, piyano çalmayı öğrenmek ve yemek yapmak gibi aktivitelerden büyük keyif alıyorum. Ayrıca, gelişen teknolojiye olan merakım ve ilgim de hiç azalmıyor. Verinin hayatımızdaki önemini anlıyorum ve bu bağlamda yapay zeka, makine öğrenimi ve bilgisayarlı görü alanlarında kendimi sürekli olarak geliştiriyorum. Edindiğim bilgileri ise YouTube ve Medium hesaplarımda paylaşarak bilgi paylaşımına katkıda bulunmaya çalışıyorum.</p>
    </section>
    <section id="egitim">
        <h2>Eğitim</h2>
        <p>Burası eğitim bilgilerinizi içerecek.</p>
    </section>
    <section id="is-deneyimi">
        <h2>İş Deneyimi</h2>
        <p>Burası iş deneyimi bilgilerinizi içerecek.</p>
    </section>
    <section id="projeler">
        <h2>Projeler</h2>
        <div class="project">
            <h3>Proje 1</h3>
            <p>Proje 1 açıklaması.</p>
        </div>
        <div class="project">
            <h3>Proje 2</h3>
            <p>Proje 2 açıklaması.</p>
        </div>
        <div class="project">
            <h3>Proje 3</h3>
            <p>Proje 3 açıklaması.</p>
        </div>
    </section>
    <section id="iletisim">
        <h2>İletişim</h2>
        <div class="contact-info">
            <p>E-posta: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
            <p>Linktree: <a href="https://linktr.ee/mtburakk" target="_blank">https://linktr.ee/mtburakk</a></p>
            <p>Sosyal Medya:</p>
            <ul>
                <li><a href="https://linkedin.com" target="_blank">LinkedIn</a></li>
                <li><a href="https://github.com" target="_blank">GitHub</a></li>
                <li><a href="https://medium.com" target="_blank">Medium</a></li>
            </ul>
        </div>
        <div class="media-container">
            <h2>Videolar ve Makaleler</h2>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/videoid1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/videoid2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <div class="medium-preview">
                <h3>Medium Makalesi 1</h3>
                <p>Medium makalesi 1'in kısa açıklaması. <a href="https://medium.com/article-link-1" target="_blank">Devamını oku</a></p>
            </div>
            <div class="medium-preview">
                <h3>Medium Makalesi 2</h3>
                <p>Medium makalesi 2'nin kısa açıklaması. <a href="https://medium.com/article-link-2" target="_blank">Devamını oku</a></p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Burak. Tüm hakları saklıdır.</p>
    </footer>
</body>
</html>
