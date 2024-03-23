# AygazGenAIBootcamp-PromptEngineering-Galeri-WebSitesi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Galeri ve Şarkı Önerileri</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Önerilen Şarkılar */
        .song-list {
            list-style-type: none;
            padding: 0;
        }
        .song-list li {
            margin-bottom: 10px;
        }

        /* Kahve Çeşitleri */
        .coffee-list {
            list-style-type: none;
            padding: 0;
        }
        .coffee-list li {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand" href="#">Portfolio Galeri</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#portfolio">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#songs">Şarkı Önerileri</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#coffees">Kahve Çeşitleri</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section id="portfolio">
            <h2>Portfolio</h2>
            <!-- Portfolio galeri içeriği buraya gelecek -->
        </section>

        <section id="songs">
            <h2>Şarkı Önerileri</h2>
            <ul class="song-list">
                <li><strong>Şarkı Adı 1:</strong> Sanatçı 1</li>
                <li><strong>Şarkı Adı 2:</strong> Sanatçı 2</li>
                <li><strong>Şarkı Adı 3:</strong> Sanatçı 3</li>
                <!-- Daha fazla şarkı ekleyebilirsiniz -->
            </ul>
        </section>

        <aside id="coffees">
            <h2>Kahve Çeşitleri</h2>
            <ul class="coffee-list">
                <li><strong>Kahve Çeşidi 1:</strong> Açıklama 1</li>
                <li><strong>Kahve Çeşidi 2:</strong> Açıklama 2</li>
                <li><strong>Kahve Çeşidi 3:</strong> Açıklama 3</li>
                <!-- Daha fazla kahve çeşidi ekleyebilirsiniz -->
            </ul>
        </aside>
    </main>

    <footer>
        <p>&copy; 2024 Portfolio Galeri</p>
    </footer>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
