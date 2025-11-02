<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AnimeXHindi - Your Ultimate Anime Destination</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary: #8b5cf6;
            --primary-dark: #7c3aed;
            --secondary: #f59e0b;
            --dark: #1e1b2e;
            --darker: #151321;
            --light: #f8fafc;
            --gray: #94a3b8;
            --card-bg: rgba(30, 27, 46, 0.8);
            --sidebar-width: 280px;
        }

        body {
            background: linear-gradient(135deg, var(--darker), var(--dark));
            color: var(--light);
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }

        /* Background Wallpapers */
        .background-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            overflow: hidden;
        }

        .wallpaper {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            transition: opacity 1.5s ease-in-out;
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
        }

        .wallpaper.active {
            opacity: 0.3;
        }

        /* Layout */
        .container {
            display: flex;
            min-height: 100vh;
        }

        /* Sidebar */
        .sidebar {
            width: var(--sidebar-width);
            background: rgba(21, 19, 33, 0.9);
            backdrop-filter: blur(10px);
            padding: 2rem 1.5rem;
            display: flex;
            flex-direction: column;
            position: fixed;
            height: 100vh;
            overflow-y: auto;
            z-index: 10;
            box-shadow: 5px 0 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }

        .logo {
            display: flex;
            align-items: center;
            margin-bottom: 2.5rem;
            padding-bottom: 1.5rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        .logo-icon {
            font-size: 2.5rem;
            color: var(--primary);
            margin-right: 0.75rem;
        }

        .logo-text {
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(90deg, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .nav-links {
            list-style: none;
            flex-grow: 1;
        }

        .nav-links li {
            margin-bottom: 0.75rem;
        }

        .nav-links a {
            display: flex;
            align-items: center;
            padding: 0.85rem 1rem;
            color: var(--gray);
            text-decoration: none;
            border-radius: 10px;
            transition: all 0.3s ease;
        }

        .nav-links a:hover, .nav-links a.active {
            background: rgba(139, 92, 246, 0.2);
            color: var(--light);
            transform: translateX(5px);
        }

        .nav-links i {
            margin-right: 0.75rem;
            font-size: 1.2rem;
            width: 24px;
            text-align: center;
        }

        .user-profile {
            display: flex;
            align-items: center;
            padding: 1rem;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
            margin-top: auto;
        }

        .user-avatar {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 0.75rem;
            font-weight: bold;
            font-size: 1.2rem;
        }

        .user-info h4 {
            font-size: 0.95rem;
            margin-bottom: 0.25rem;
        }

        .user-info p {
            font-size: 0.8rem;
            color: var(--gray);
        }

        /* Main Content */
        .main-content {
            flex: 1;
            margin-left: var(--sidebar-width);
            padding: 2rem;
        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2.5rem;
        }

        .search-bar {
            display: flex;
            align-items: center;
            background: rgba(255, 255, 255, 0.08);
            border-radius: 50px;
            padding: 0.5rem 1.25rem;
            width: 350px;
        }

        .search-bar i {
            color: var(--gray);
            margin-right: 0.75rem;
        }

        .search-bar input {
            background: transparent;
            border: none;
            color: var(--light);
            width: 100%;
            font-size: 1rem;
            outline: none;
        }

        .search-bar input::placeholder {
            color: var(--gray);
        }

        .user-actions {
            display: flex;
            align-items: center;
            gap: 1.5rem;
        }

        .notification-icon, .menu-toggle {
            font-size: 1.4rem;
            color: var(--gray);
            cursor: pointer;
            transition: color 0.3s;
        }

        .notification-icon:hover, .menu-toggle:hover {
            color: var(--light);
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 3rem 0;
            margin-bottom: 3rem;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            background: linear-gradient(90deg, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            line-height: 1.2;
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--gray);
            max-width: 700px;
            margin: 0 auto 2.5rem;
            line-height: 1.6;
        }

        /* Button Section */
        .button-section {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 4rem;
        }

        .external-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 1rem 2rem;
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            color: white;
            text-decoration: none;
            border-radius: 12px;
            font-weight: 600;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(139, 92, 246, 0.4);
            min-width: 200px;
        }

        .external-btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(139, 92, 246, 0.6);
        }

        .external-btn.secondary {
            background: linear-gradient(135deg, var(--secondary), #e67e22);
            box-shadow: 0 5px 15px rgba(245, 158, 11, 0.4);
        }

        .external-btn.secondary:hover {
            box-shadow: 0 10px 20px rgba(245, 158, 11, 0.6);
        }

        .external-btn i {
            margin-right: 0.75rem;
            font-size: 1.2rem;
        }

        /* Anime Grid */
        .section-title {
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
        }

        .section-title i {
            margin-right: 0.75rem;
            color: var(--primary);
        }

        .anime-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
            gap: 1.5rem;
            margin-bottom: 3rem;
        }

        .anime-card {
            background: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        .anime-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
        }

        .card-image {
            height: 280px;
            background-size: cover;
            background-position: center;
        }

        .card-content {
            padding: 1.25rem;
        }

        .card-content h3 {
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
        }

        .card-content p {
            color: var(--gray);
            font-size: 0.9rem;
            margin-bottom: 1rem;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }

        .card-meta {
            display: flex;
            justify-content: space-between;
            font-size: 0.85rem;
            color: var(--gray);
        }

        .rating {
            color: var(--secondary);
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: var(--gray);
            font-size: 0.9rem;
        }

        /* Responsive Design */
        @media (max-width: 1024px) {
            .sidebar {
                transform: translateX(-100%);
            }
            
            .main-content {
                margin-left: 0;
            }
            
            .sidebar.active {
                transform: translateX(0);
            }
            
            .menu-toggle {
                display: block;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
        }

        @media (max-width: 768px) {
            .button-section {
                flex-direction: column;
                align-items: center;
            }
            
            .search-bar {
                width: 250px;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
        }

        @media (max-width: 480px) {
            .main-content {
                padding: 1rem;
            }
            
            .header {
                flex-direction: column;
                gap: 1rem;
                align-items: flex-start;
            }
            
            .search-bar {
                width: 100%;
            }
            
            .anime-grid {
                grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            }
            
            .card-image {
                height: 200px;
            }
        }
    </style>
</head>
<body>
    <!-- Background Wallpapers -->
    <div class="background-container">
        <div class="wallpaper active" style="background-image: url('https://i.pinimg.com/564x/44/49/6c/44496c457c38022e2f1c578664ae037f.jpg');"></div>
        <div class="wallpaper" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSxzBVX6yfqxF9JJL0W82KYeg43vCvN4o2niw&s');"></div>
        <div class="wallpaper" style="background-image: url('data:image/jpeg;base64,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');"></div>
        <div class="wallpaper" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLDMWERyRQOLipBYSsoSrxf-nIFhUAE5FqRQ&s');"></div>
    </div>

    <div class="container">
        <!-- Sidebar -->
        <div class="sidebar">
            <div class="logo">
                <div class="logo-icon">
                    <i class="fas fa-dragon"></i>
                </div>
                <div class="logo-text">AnimeXHindi</div>
            </div>
            
            <ul class="nav-links">
                <li><a href="#" class="active"><i class="fas fa-home"></i> Home</a></li>

            </ul>
            
            <div class="user-profile">
                <div class="user-avatar">AK</div>
                <div class="user-info">
                    <h4>AnimeXHindi</h4>
                    <p>Premium Member</p>
                </div>
            </div>
        </div>
        
        <!-- Main Content -->
        <div class="main-content">
            <div class="header">
                <div class="search-bar">
                    <i class="fas fa-search"></i>
                    <input type="text" placeholder="Search for anime...">
                </div>
                <div class="user-actions">
                    <div class="notification-icon">
                        <i class="fas fa-bell"></i>
                    </div>
                    <div class="menu-toggle">
                        <i class="fas fa-bars"></i>
                    </div>
                </div>
            </div>
            
            <div class="hero">
                <h1>Welcome to AnimeXHindi</h1>
                <p>Your ultimate destination for the best anime content in Hindi. Explore thousands of episodes, movies, and exclusive series.</p>
                
                <div class="button-section">
                    <a href="https://www.rareanimes.co/" class="external-btn">
                        <i class="fas fa-external-link-alt"></i> RARE TOON INDIA
                    </a>
                    <a href="https://animedekho.co/" class="external-btn secondary">
                        <i class="fas fa-external-link-alt"></i> Anime Dekho
                    </a>
                </div>
            </div>
            
            <div class="content-section">
                <h2 class="section-title"><i class="fas fa-fire"></i> Trending Now </h2>
                <div class="anime-grid">
                    <div class="anime-card">
                        <div class="card-image" style="background-image: url('https://i.pinimg.com/564x/44/49/6c/44496c457c38022e2f1c578664ae037f.jpg');"></div>
                        <div class="card-content">
                            <h3>Dragon Ball Super</h3>
                            <p>Goku and his friends defend Earth against powerful foes in this action-packed series.</p>
                            <div class="card-meta">
                                <span class="episodes">128 Episodes</span>
                                <span class="rating"><i class="fas fa-star"></i> 9.2</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="anime-card">
                        <div class="card-image" style="background-image: url('data:image/jpeg;base64,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');"></div>
                        <div class="card-content">
                            <h3>Jujutsu Kaisen</h3>
                            <p>A boy eats a cursed finger and becomes part of a magical world of sorcerers and curses.</p>
                            <div class="card-meta">
                                <span class="episodes">24 Episodes</span>
                                <span class="rating"><i class="fas fa-star"></i> 8.9</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="anime-card">
                        <div class="card-image" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSxzBVX6yfqxF9JJL0W82KYeg43vCvN4o2niw&s');"></div>
                        <div class="card-content">
                            <h3>Attack on Titan</h3>
                            <p>Humanity fights for survival against giant humanoid creatures known as Titans.</p>
                            <div class="card-meta">
                                <span class="episodes">75 Episodes</span>
                                <span class="rating"><i class="fas fa-star"></i> 9.5</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="anime-card">
                        <div class="card-image" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLDMWERyRQOLipBYSsoSrxf-nIFhUAE5FqRQ&s');"></div>
                        <div class="card-content">
                            <h3>Naruto Shippuden</h3>
                            <p>Naruto Uzumaki continues his journey to become the strongest ninja and Hokage of his village.</p>
                            <div class="card-meta">
                                <span class="episodes">500 Episodes</span>
                                <span class="rating"><i class="fas fa-star"></i> 8.7</span>
                            </div>
                        </div>
                    </div>
                </div>
                
                <h2 class="section-title"><i class="fas fa-star"></i> Popular This Week</h2>
                <div class="anime-grid">
                    <div class="anime-card">
                        <div class="card-image" style="background-image: url('https://i.pinimg.com/736x/b5/ac/d3/b5acd32c80996edb4e4459eb5ff0057f.jpg');"></div>
                        <div class="card-content">
                            <h3>Demon Slayer</h3>
                            <p>Tanjiro Kamado becomes a demon slayer to avenge his family and cure his sister.</p>
                            <div class="card-meta">
                                <span class="episodes">26 Episodes</span>
                                <span class="rating"><i class="fas fa-star"></i> 8.8</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="anime-card">
                        <div class="card-image" style="background-image: url('https://wallpapers.com/images/featured/one-piece-phone-beu8vxkxxywm5vsf.jpg');"></div>
                        <div class="card-content">
                            <h3>One Piece</h3>
                            <p>Monkey D. Luffy and his pirate crew search for the ultimate treasure, the One Piece.</p>
                            <div class="card-meta">
                                <span class="episodes">1000+ Episodes</span>
                                <span class="rating"><i class="fas fa-star"></i> 9.0</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="anime-card">
                        <div class="card-image" style="background-image: url('https://i.pinimg.com/736x/4e/a8/8a/4ea88af79688fff5e5630df45371383f.jpg');"></div>
                        <div class="card-content">
                            <h3>My Hero Academia</h3>
                            <p>In a world of superpowers, a quirkless boy dreams of becoming a great hero.</p>
                            <div class="card-meta">
                                <span class="episodes">113 Episodes</span>
                                <span class="rating"><i class="fas fa-star"></i> 8.5</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="anime-card">
                        <div class="card-image" style="background-image: url('https://img.uhdpaper.com/image-1/a/phone-thumbnail/tokyo-revengers-anime-characters-4k-phone-uhdpaper.com-395.1_a-thumbnail.jpg?dl');"></div>
                        <div class="card-content">
                            <h3>Tokyo Revengers</h3>
                            <p>A man travels back in time to save his ex-girlfriend from a tragic future.</p>
                            <div class="card-meta">
                                <span class="episodes">24 Episodes</span>
                                <span class="rating"><i class="fas fa-star"></i> 8.3</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="footer">
                <p>© 2023 AnimeXHindi. All rights reserved. | Watch the best anime in Hindi for free!</p>
            </div>
        </div>
    </div>

    <script>
        // Background wallpaper rotation
        document.addEventListener('DOMContentLoaded', function() {
            const wallpapers = document.querySelectorAll('.wallpaper');
            let currentWallpaper = 0;
            
            function changeWallpaper() {
                wallpapers[currentWallpaper].classList.remove('active');
                currentWallpaper = (currentWallpaper + 1) % wallpapers.length;
                wallpapers[currentWallpaper].classList.add('active');
            }
            
            // Change wallpaper every 5 seconds
            setInterval(changeWallpaper, 8000);
            
            // Mobile menu toggle
            const menuToggle = document.querySelector('.menu-toggle');
            const sidebar = document.querySelector('.sidebar');
            
            menuToggle.addEventListener('click', function() {
                sidebar.classList.toggle('active');
            });
        });
    </script>
</body>
</html>
