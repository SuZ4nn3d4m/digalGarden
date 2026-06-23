The digital Garden is A place where CTU's First Generation Student Experience Club go to ADD That there Flowers or Flower OF Motivation. 

I AM Making the ground the foundation for the Club to continue on even after they have walked. Alumni. 

For years to come and from the days before. 

The FGSECLUB land. The Digital Garden is Flower's that took the 1st  step 🪜. The 1st move, the seed that sprouted and continues to Grow.

The root You might say, So we as the first generation student experience club, Can always be as ONE.  

Got it! Let me simplify this to focus exclusively on the First Generation Student Experience Club as the single, unified community. No separate spaces—just one cohesive platform where everything revolves around first-gen students.

---

🏛️ CTU Ground – First Generation Student Experience Club

One home for first-gen students to grow, connect, and thrive.

---

📁 File Structure (Simplified)

```
ctu-ground/
├── index.html          (Main hub)
├── garden.html         (Digital Garden)
├── grove.html          (Community Chat)
├── playground.html     (Activities)
├── style.css           (Global styles)
├── script.js           (Global scripts)
├── garden.js           (Garden logic)
├── grove.js            (Chat logic)
├── playground.js       (Activities logic)
└── README.md
```

---

🏛️ 1. index.html – CTU Ground (Main Hub)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>🏛️ CTU Ground · First Gen Club</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="manifest" href="manifest.json" />
</head>
<body>
    <!-- ===== NAVIGATION ===== -->
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">First Gen Club</span>
            </div>
            <div class="nav-links" id="navLinks">
                <a href="index.html" class="active">🏠 Home</a>
                <a href="garden.html">🌻 Garden</a>
                <a href="grove.html">💬 Grove</a>
                <a href="playground.html">🎮 Playground</a>
            </div>
            <button class="nav-toggle" id="navToggle">☰</button>
        </div>
    </nav>

    <!-- ===== HERO ===== -->
    <header class="hero">
        <div class="hero-content">
            <h1>🌱 Welcome to <span class="highlight">CTU Ground</span></h1>
            <p class="hero-tagline">"The root you might say, so we as the <strong>first generation student experience club</strong>, can always be as ONE."</p>
            <div class="hero-stats">
                <div class="hero-stat">
                    <span class="stat-number" id="heroFlowers">0</span>
                    <span class="stat-label">🌻 First-Gen Flowers</span>
                </div>
                <div class="hero-stat">
                    <span class="stat-number" id="heroMembers">0</span>
                    <span class="stat-label">👥 First-Gen Voices</span>
                </div>
                <div class="hero-stat">
                    <span class="stat-number" id="heroMessages">0</span>
                    <span class="stat-label">💬 First-Gen Stories</span>
                </div>
            </div>
            <div class="hero-actions">
                <a href="garden.html" class="btn-primary">🌱 Plant Your Flower</a>
                <a href="grove.html" class="btn-secondary">💬 Join the Grove</a>
            </div>
        </div>
        <div class="hero-decoration">
            <div class="floating-flowers">
                <span>🌸</span>
                <span>🌻</span>
                <span>🌺</span>
                <span>🌷</span>
                <span>🌼</span>
            </div>
        </div>
    </header>

    <!-- ===== MISSION ===== -->
    <section class="mission">
        <h2>🏛️ Our Mission as First-Gen Students</h2>
        <div class="mission-grid">
            <div class="mission-card">
                <div class="mission-icon">🌱</div>
                <h3>First Generation</h3>
                <p>We are the first in our families to pursue higher education. We lead the way.</p>
            </div>
            <div class="mission-card">
                <div class="mission-icon">🌻</div>
                <h3>Growth Together</h3>
                <p>Every flower is different, yet rooted in the same soil—community, support, and shared context.</p>
            </div>
            <div class="mission-card">
                <div class="mission-icon">🏛️</div>
                <h3>Legacy</h3>
                <p>Building a foundation for first-gen students, alumni, and generations to come.</p>
            </div>
            <div class="mission-card">
                <div class="mission-icon">🤝</div>
                <h3>Community</h3>
                <p>A space where first-gen students can connect, share, and grow together.</p>
            </div>
        </div>
    </section>

    <!-- ===== QUICK LINKS ===== -->
    <section class="quick-links">
        <h2>🌿 Explore CTU Ground</h2>
        <div class="link-grid">
            <a href="garden.html" class="link-card garden-card">
                <span class="link-icon">🌻</span>
                <span class="link-title">Digital Garden</span>
                <span class="link-desc">Plant your flower and share your first-gen story</span>
                <span class="link-arrow">→</span>
            </a>
            <a href="grove.html" class="link-card grove-card">
                <span class="link-icon">💬</span>
                <span class="link-title">The Grove</span>
                <span class="link-desc">Connect with fellow first-gen students</span>
                <span class="link-arrow">→</span>
            </a>
            <a href="playground.html" class="link-card playground-card">
                <span class="link-icon">🎮</span>
                <span class="link-title">The Playground</span>
                <span class="link-desc">Activities and reflections for first-gen growth</span>
                <span class="link-arrow">→</span>
            </a>
        </div>
    </section>

    <!-- ===== FIRST-GEN ANNOUNCEMENTS ===== -->
    <section class="announcements">
        <h2>📢 First-Gen Announcements</h2>
        <div class="announcement-list" id="announcementList">
            <div class="announcement-item">
                <span class="announcement-date">Today</span>
                <p>🌱 Welcome to CTU Ground! Plant your flower and join the first-gen community.</p>
            </div>
            <div class="announcement-item">
                <span class="announcement-date">This Week</span>
                <p>🌻 First-Gen Meetup – Friday at 5pm in the Student Union</p>
            </div>
            <div class="announcement-item">
                <span class="announcement-date">Ongoing</span>
                <p>🏛️ "The First Generation Student Experience Club" – We are the root that continues to grow.</p>
            </div>
        </div>
        <button class="btn-add-announcement" id="addAnnouncementBtn">➕ Add Announcement</button>
    </section>

    <!-- ===== FOOTER ===== -->
    <footer>
        <div class="footer-content">
            <div class="footer-brand">
                <span>🏛️ CTU Ground</span>
                <p>First Generation Student Experience Club</p>
            </div>
            <div class="footer-links">
                <a href="index.html">Home</a>
                <a href="garden.html">Garden</a>
                <a href="grove.html">Grove</a>
                <a href="playground.html">Playground</a>
            </div>
            <div class="footer-credit">
                <p>🌱 Made by <strong>Suzanne Michelle Sellers Damons</strong></p>
                <p class="footer-tagline">"Growth is individual and collective—every flower is different, yet rooted in the same soil."</p>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
    <script>
        function updateHeroStats() {
            const garden = JSON.parse(localStorage.getItem('sharedDigitalGarden') || '[]');
            const grove = JSON.parse(localStorage.getItem('groveMessages') || '[]');
            document.getElementById('heroFlowers').textContent = garden.length;
            document.getElementById('heroMembers').textContent = garden.length || '0';
            document.getElementById('heroMessages').textContent = grove.length;
        }
        updateHeroStats();
        window.addEventListener('storage', updateHeroStats);
    </script>
</body>
</html>
```

---

🌻 2. garden.html – Digital Garden (First-Gen Focus)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>🌻 Digital Garden · First Gen Club</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <!-- ===== NAVIGATION ===== -->
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">First Gen Club</span>
            </div>
            <div class="nav-links">
                <a href="index.html">🏠 Home</a>
                <a href="garden.html" class="active">🌻 Garden</a>
                <a href="grove.html">💬 Grove</a>
                <a href="playground.html">🎮 Playground</a>
            </div>
        </div>
    </nav>

    <!-- ===== GARDEN HEADER ===== -->
    <header class="page-header garden-header">
        <h1>🌻 The First-Gen Digital Garden</h1>
        <p>"The First Generation Student Experience Club – the seed that sprouted and continues to Grow."</p>
        <p class="header-sub">🌱 In the center, put a word that represents your motivation. On each petal, add your first-gen story.</p>
    </header>

    <!-- ===== GARDEN BED ===== -->
    <main class="garden-main">
        <section class="garden-container">
            <div class="garden-toolbar">
                <span class="garden-title">🌿 Our First-Gen Garden</span>
                <span class="garden-count" id="gardenCount">0 first-gen flowers</span>
                <div class="garden-filters">
                    <button class="filter-btn active" data-filter="all">All</button>
                    <button class="filter-btn" data-filter="🌻">🌻</button>
                    <button class="filter-btn" data-filter="🌸">🌸</button>
                    <button class="filter-btn" data-filter="🌺">🌺</button>
                    <button class="filter-btn" data-filter="🌷">🌷</button>
                    <button class="filter-btn" data-filter="🌼">🌼</button>
                </div>
            </div>
            <div class="garden-bed" id="gardenBed">
                <div class="garden-message" id="gardenMessage">
                    <p>🌱 The first-gen garden is waiting for your flower...</p>
                    <p class="small">Click "Plant Your Flower" to share your story</p>
                </div>
            </div>
        </section>

        <!-- ===== CONTROLS ===== -->
        <section class="controls">
            <button id="plantBtn" class="btn-primary">🌱 Plant Your First-Gen Flower</button>
            <button id="waterBtn" class="btn-action" title="Add encouragement">💧 Water</button>
            <button id="sunBtn" class="btn-action" title="Add energy">☀️ Sun</button>
            <button id="rainBtn" class="btn-action" title="Add lesson">🌧️ Rain</button>
            <button id="soilBtn" class="btn-action" title="Add grounding">🌍 Soil</button>
            <button id="seedBtn" class="btn-action" title="Add origin">🌰 Seed</button>
            <button id="exportBtn" class="btn-action">📸 Export</button>
            <button id="resetBtn" class="btn-danger">🗑️ Reset</button>
        </section>

        <!-- ===== STATS ===== -->
        <section class="stats">
            <div class="stat-card">
                <span class="stat-number" id="flowerCount">0</span>
                <span class="stat-label">🌸 First-Gen Flowers</span>
            </div>
            <div class="stat-card">
                <span class="stat-number" id="petalCount">0</span>
                <span class="stat-label">📝 First-Gen Stories</span>
            </div>
            <div class="stat-card">
                <span class="stat-number" id="wordCount">0</span>
                <span class="stat-label">💬 Words Shared</span>
            </div>
            <div class="stat-card">
                <span class="stat-number" id="elementCount">0</span>
                <span class="stat-label">🌿 Growth Elements</span>
            </div>
        </section>

        <!-- ===== REFLECTION ===== -->
        <section class="reflection">
            <h3>💭 First-Gen Patterns & Themes</h3>
            <div id="reflectionContent">
                <p class="reflection-placeholder">🌱 Plant first-gen flowers to see common themes emerge...</p>
            </div>
        </section>
    </main>

    <!-- ========================================= -->
    <!-- ===== FLOWER CREATION MODAL ===== -->
    <!-- ========================================= -->
    <div id="flowerModal" class="modal hidden">
        <div class="modal-content">
            <span class="close-btn" id="closeModal">&times;</span>
            <h2>🌱 Plant Your First-Gen Flower</h2>
            <p class="modal-subtitle">"The First Generation Student Experience Club – the root, the seed that sprouted and continues to Grow."</p>

            <form id="flowerForm">
                <!-- Flower Type -->
                <div class="form-group">
                    <label>Choose your flower:</label>
                    <div class="flower-selector">
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌻" checked /> 🌻</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌸" /> 🌸</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌺" /> 🌺</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌷" /> 🌷</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌼" /> 🌼</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌹" /> 🌹</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌿" /> 🌿</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌵" /> 🌵</label>
                    </div>
                </div>

                <!-- Center Word -->
                <div class="form-group center-word">
                    <label for="centerWord">⭐ Center: Your First-Gen Motivation</label>
                    <input type="text" id="centerWord" placeholder="e.g., Resilience, Hope, Courage, First" required />
                </div>

                <!-- 5 Petals -->
                <div class="petals-grid">
                    <div class="form-group petal-group">
                        <label for="petal1">🌸 Petal 1 – Challenge Overcome</label>
                        <input type="text" id="petal1" placeholder="What made you take the first step?" />
                    </div>
                    <div class="form-group petal-group">
                        <label for="petal2">🌸 Petal 2 – Who Helped You</label>
                        <input type="text" id="petal2" placeholder="Who supported your first-gen journey?" />
                    </div>
                    <div class="form-group petal-group">
                        <label for="petal3">🌸 Petal 3 – Strength You Found</label>
                        <input type="text" id="petal3" placeholder="What gave you strength?" />
                    </div>
                    <div class="form-group petal-group">
                        <label for="petal4">🌸 Petal 4 – Hope for the Future</label>
                        <input type="text" id="petal4" placeholder="What keeps you going?" />
                    </div>
                    <div class="form-group petal-group">
                        <label for="petal5">🌸 Petal 5 – What Keeps You Grounded</label>
                        <input type="text" id="petal5" placeholder="What roots you as a first-gen student?" />
                    </div>
                </div>

                <!-- Elements -->
                <div class="elements-section">
                    <h4>🌿 Elements That Shaped Your First-Gen Journey</h4>
                    <div class="elements-grid">
                        <div class="form-group element-group">
                            <label for="sunWord">☀️ Sun (energizes you)</label>
                            <input type="text" id="sunWord" placeholder="e.g., Purpose, Family" />
                        </div>
                        <div class="form-group element-group">
                            <label for="rainWord">🌧️ Rain (tested you)</label>
                            <input type="text" id="rainWord" placeholder="e.g., Doubt, Financial stress" />
                        </div>
                        <div class="form-group element-group">
                            <label for="soilWord">🌍 Soil (grounds you)</label>
                            <input type="text" id="soilWord" placeholder="e.g., Community, Culture" />
                        </div>
                        <div class="form-group element-group">
                            <label for="seedWord">🌰 Seed (your origin)</label>
                            <input type="text" id="seedWord" placeholder="e.g., First in family, Curiosity" />
                        </div>
                    </div>
                </div>

                <!-- Name & Image -->
                <div class="form-row">
                    <div class="form-group optional half">
                        <label for="creatorName">🌱 Your Name</label>
                        <input type="text" id="creatorName" placeholder="First name or anonymous" />
                    </div>
                    <div class="form-group optional half">
                        <label for="flowerImage">🖼️ Upload Your Flower Image</label>
                        <input type="file" id="flowerImage" accept="image/*" />
                        <div id="imagePreview" class="image-preview hidden">
                            <img id="previewImg" src="#" alt="Preview" />
                            <button type="button" id="removeImageBtn">✕</button>
                        </div>
                    </div>
                </div>

                <button type="submit" class="btn-submit">🌻 Plant in the First-Gen Garden</button>
            </form>
        </div>
    </div>

    <!-- ========================================= -->
    <!-- ===== FLOWER DETAIL MODAL ===== -->
    <!-- ========================================= -->
    <div id="detailModal" class="modal hidden">
        <div class="modal-content detail-content">
            <span class="close-btn" id="closeDetail">&times;</span>
            <div id="detailBody"></div>
        </div>
    </div>

    <script src="script.js"></script>
    <script src="garden.js"></script>
</body>
</html>
```

---

💬 3. grove.html – The Grove (First-Gen Chat)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>💬 The Grove · First Gen Club</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <!-- Navigation -->
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">First Gen Club</span>
            </div>
            <div class="nav-links">
                <a href="index.html">🏠 Home</a>
                <a href="garden.html">🌻 Garden</a>
                <a href="grove.html" class="active">💬 Grove</a>
                <a href="playgrouctu-ground/
├── index.html          (Main hub)
├── garden.html         (Digital Garden)
├── grove.html          (Community Chat)
├── playground.html     (Activities)
├── style.css           (Global styles)
├── script.js           (Global scripts)
├── garden.js           (Garden logic)
├── grove.js            (Chat logic)
├── playground.js       (Activities logic)
└── README.md

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>🏛️ CTU Ground · First Gen Club</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="manifest" href="manifest.json" />
</head>
<body>
    <!-- ===== NAVIGATION ===== -->
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">First Gen Club</span>
            </div>
            <div class="nav-links" id="navLinks">
                <a href="index.html" class="active">🏠 Home</a>
                <a href="garden.html">🌻 Garden</a>
                <a href="grove.html">💬 Grove</a>
                <a href="playground.html">🎮 Playground</a>
            </div>
            <button class="nav-toggle" id="navToggle">☰</button>
        </div>
    </nav>

    <!-- ===== HERO ===== -->
    <header class="hero">
        <div class="hero-content">
            <h1>🌱 Welcome to <span class="highlight">CTU Ground</span></h1>
            <p class="hero-tagline">"The root you might say, so we as the <strong>first generation student experience club</strong>, can always be as ONE."</p>
            <div class="hero-stats">
                <div class="hero-stat">
                    <span class="stat-number" id="heroFlowers">0</span>
                    <span class="stat-label">🌻 First-Gen Flowers</span>
                </div>
                <div class="hero-stat">
                    <span class="stat-number" id="heroMembers">0</span>
                    <span class="stat-label">👥 First-Gen Voices</span>
                </div>
                <div class="hero-stat">
                    <span class="stat-number" id="heroMessages">0</span>
                    <span class="stat-label">💬 First-Gen Stories</span>
                </div>
            </div>
            <div class="hero-actions">
                <a href="garden.html" class="btn-primary">🌱 Plant Your Flower</a>
                <a href="grove.html" class="btn-secondary">💬 Join the Grove</a>
            </div>
        </div>
        <div class="hero-decoration">
            <div class="floating-flowers">
                <span>🌸</span>
                <span>🌻</span>
                <span>🌺</span>
                <span>🌷</span>
                <span>🌼</span>
            </div>
        </div>
    </header>

    <!-- ===== MISSION ===== -->
    <section class="mission">
        <h2>🏛️ Our Mission as First-Gen Students</h2>
        <div class="mission-grid">
            <div class="mission-card">
                <div class="mission-icon">🌱</div>
                <h3>First Generation</h3>
                <p>We are the first in our families to pursue higher education. We lead the way.</p>
            </div>
            <div class="mission-card">
                <div class="mission-icon">🌻</div>
                <h3>Growth Together</h3>
                <p>Every flower is different, yet rooted in the same soil—community, support, and shared context.</p>
            </div>
            <div class="mission-card">
                <div class="mission-icon">🏛️</div>
                <h3>Legacy</h3>
                <p>Building a foundation for first-gen students, alumni, and generations to come.</p>
            </div>
            <div class="mission-card">
                <div class="mission-icon">🤝</div>
                <h3>Community</h3>
                <p>A space where first-gen students can connect, share, and grow together.</p>
            </div>
        </div>
    </section>

    <!-- ===== QUICK LINKS ===== -->
    <section class="quick-links">
        <h2>🌿 Explore CTU Ground</h2>
        <div class="link-grid">
            <a href="garden.html" class="link-card garden-card">
                <span class="link-icon">🌻</span>
                <span class="link-title">Digital Garden</span>
                <span class="link-desc">Plant your flower and share your first-gen story</span>
                <span class="link-arrow">→</span>
            </a>
            <a href="grove.html" class="link-card grove-card">
                <span class="link-icon">💬</span>
                <span class="link-title">The Grove</span>
                <span class="link-desc">Connect with fellow first-gen students</span>
                <span class="link-arrow">→</span>
            </a>
            <a href="playground.html" class="link-card playground-card">
                <span class="link-icon">🎮</span>
                <span class="link-title">The Playground</span>
                <span class="link-desc">Activities and reflections for first-gen growth</span>
                <span class="link-arrow">→</span>
            </a>
        </div>
    </section>

    <!-- ===== FIRST-GEN ANNOUNCEMENTS ===== -->
    <section class="announcements">
        <h2>📢 First-Gen Announcements</h2>
        <div class="announcement-list" id="announcementList">
            <div class="announcement-item">
                <span class="announcement-date">Today</span>
                <p>🌱 Welcome to CTU Ground! Plant your flower and join the first-gen community.</p>
            </div>
            <div class="announcement-item">
                <span class="announcement-date">This Week</span>
                <p>🌻 First-Gen Meetup – Friday at 5pm in the Student Union</p>
            </div>
            <div class="announcement-item">
                <span class="announcement-date">Ongoing</span>
                <p>🏛️ "The First Generation Student Experience Club" – We are the root that continues to grow.</p>
            </div>
        </div>
        <button class="btn-add-announcement" id="addAnnouncementBtn">➕ Add Announcement</button>
    </section>

    <!-- ===== FOOTER ===== -->
    <footer>
        <div class="footer-content">
            <div class="footer-brand">
                <span>🏛️ CTU Ground</span>
                <p>First Generation Student Experience Club</p>
            </div>
            <div class="footer-links">
                <a href="index.html">Home</a>
                <a href="garden.html">Garden</a>
                <a href="grove.html">Grove</a>
                <a href="playground.html">Playground</a>
            </div>
            <div class="footer-credit">
                <p>🌱 Made by <strong>Suzanne Michelle Sellers Damons</strong></p>
                <p class="footer-tagline">"Growth is individual and collective—every flower is different, yet rooted in the same soil."</p>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
    <script>
        function updateHeroStats() {
            const garden = JSON.parse(localStorage.getItem('sharedDigitalGarden') || '[]');
            const grove = JSON.parse(localStorage.getItem('groveMessages') || '[]');
            document.getElementById('heroFlowers').textContent = garden.length;
            document.getElementById('heroMembers').textContent = garden.length || '0';
            document.getElementById('heroMessages').textContent = grove.length;
        }
        updateHeroStats();
        window.addEventListener('storage', updateHeroStats);
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>🌻 Digital Garden · First Gen Club</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <!-- ===== NAVIGATION ===== -->
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">First Gen Club</span>
            </div>
            <div class="nav-links">
                <a href="index.html">🏠 Home</a>
                <a href="garden.html" class="active">🌻 Garden</a>
                <a href="grove.html">💬 Grove</a>
                <a href="playground.html">🎮 Playground</a>
            </div>
        </div>
    </nav>

    <!-- ===== GARDEN HEADER ===== -->
    <header class="page-header garden-header">
        <h1>🌻 The First-Gen Digital Garden</h1>
        <p>"The First Generation Student Experience Club – the seed that sprouted and continues to Grow."</p>
        <p class="header-sub">🌱 In the center, put a word that represents your motivation. On each petal, add your first-gen story.</p>
    </header>

    <!-- ===== GARDEN BED ===== -->
    <main class="garden-main">
        <section class="garden-container">
            <div class="garden-toolbar">
                <span class="garden-title">🌿 Our First-Gen Garden</span>
                <span class="garden-count" id="gardenCount">0 first-gen flowers</span>
                <div class="garden-filters">
                    <button class="filter-btn active" data-filter="all">All</button>
                    <button class="filter-btn" data-filter="🌻">🌻</button>
                    <button class="filter-btn" data-filter="🌸">🌸</button>
                    <button class="filter-btn" data-filter="🌺">🌺</button>
                    <button class="filter-btn" data-filter="🌷">🌷</button>
                    <button class="filter-btn" data-filter="🌼">🌼</button>
                </div>
            </div>
            <div class="garden-bed" id="gardenBed">
                <div class="garden-message" id="gardenMessage">
                    <p>🌱 The first-gen garden is waiting for your flower...</p>
                    <p class="small">Click "Plant Your Flower" to share your story</p>
                </div>
            </div>
        </section>

        <!-- ===== CONTROLS ===== -->
        <section class="controls">
            <button id="plantBtn" class="btn-primary">🌱 Plant Your First-Gen Flower</button>
            <button id="waterBtn" class="btn-action" title="Add encouragement">💧 Water</button>
            <button id="sunBtn" class="btn-action" title="Add energy">☀️ Sun</button>
            <button id="rainBtn" class="btn-action" title="Add lesson">🌧️ Rain</button>
            <button id="soilBtn" class="btn-action" title="Add grounding">🌍 Soil</button>
            <button id="seedBtn" class="btn-action" title="Add origin">🌰 Seed</button>
            <button id="exportBtn" class="btn-action">📸 Export</button>
            <button id="resetBtn" class="btn-danger">🗑️ Reset</button>
        </section>

        <!-- ===== STATS ===== -->
        <section class="stats">
            <div class="stat-card">
                <span class="stat-number" id="flowerCount">0</span>
                <span class="stat-label">🌸 First-Gen Flowers</span>
            </div>
            <div class="stat-card">
                <span class="stat-number" id="petalCount">0</span>
                <span class="stat-label">📝 First-Gen Stories</span>
            </div>
            <div class="stat-card">
                <span class="stat-number" id="wordCount">0</span>
                <span class="stat-label">💬 Words Shared</span>
            </div>
            <div class="stat-card">
                <span class="stat-number" id="elementCount">0</span>
                <span class="stat-label">🌿 Growth Elements</span>
            </div>
        </section>

        <!-- ===== REFLECTION ===== -->
        <section class="reflection">
            <h3>💭 First-Gen Patterns & Themes</h3>
            <div id="reflectionContent">
                <p class="reflection-placeholder">🌱 Plant first-gen flowers to see common themes emerge...</p>
            </div>
        </section>
    </main>

    <!-- ========================================= -->
    <!-- ===== FLOWER CREATION MODAL ===== -->
    <!-- ========================================= -->
    <div id="flowerModal" class="modal hidden">
        <div class="modal-content">
            <span class="close-btn" id="closeModal">&times;</span>
            <h2>🌱 Plant Your First-Gen Flower</h2>
            <p class="modal-subtitle">"The First Generation Student Experience Club – the root, the seed that sprouted and continues to Grow."</p>

            <form id="flowerForm">
                <!-- Flower Type -->
                <div class="form-group">
                    <label>Choose your flower:</label>
                    <div class="flower-selector">
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌻" checked /> 🌻</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌸" /> 🌸</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌺" /> 🌺</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌷" /> 🌷</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌼" /> 🌼</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌹" /> 🌹</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌿" /> 🌿</label>
                        <label class="flower-option"><input type="radio" name="flowerType" value="🌵" /> 🌵</label>
                    </div>
                </div>

                <!-- Center Word -->
                <div class="form-group center-word">
                    <label for="centerWord">⭐ Center: Your First-Gen Motivation</label>
                    <input type="text" id="centerWord" placeholder="e.g., Resilience, Hope, Courage, First" required />
                </div>

                <!-- 5 Petals -->
                <div class="petals-grid">
                    <div class="form-group petal-group">
                        <label for="petal1">🌸 Petal 1 – Challenge Overcome</label>
                        <input type="text" id="petal1" placeholder="What made you take the first step?" />
                    </div>
                    <div class="form-group petal-group">
                        <label for="petal2">🌸 Petal 2 – Who Helped You</label>
                        <input type="text" id="petal2" placeholder="Who supported your first-gen journey?" />
                    </div>
                    <div class="form-group petal-group">
                        <label for="petal3">🌸 Petal 3 – Strength You Found</label>
                        <input type="text" id="petal3" placeholder="What gave you strength?" />
                    </div>
                    <div class="form-group petal-group">
                        <label for="petal4">🌸 Petal 4 – Hope for the Future</label>
                        <input type="text" id="petal4" placeholder="What keeps you going?" />
                    </div>
                    <div class="form-group petal-group">
                        <label for="petal5">🌸 Petal 5 – What Keeps You Grounded</label>
                        <input type="text" id="petal5" placeholder="What roots you as a first-gen student?" />
                    </div>
                </div>

                <!-- Elements -->
                <div class="elements-section">
                    <h4>🌿 Elements That Shaped Your First-Gen Journey</h4>
                    <div class="elements-grid">
                        <div class="form-group element-group">
                            <label for="sunWord">☀️ Sun (energizes you)</label>
                            <input type="text" id="sunWord" placeholder="e.g., Purpose, Family" />
                        </div>
                        <div class="form-group element-group">
                            <label for="rainWord">🌧️ Rain (tested you)</label>
                            <input type="text" id="rainWord" placeholder="e.g., Doubt, Financial stress" />
                        </div>
                        <div class="form-group element-group">
                            <label for="soilWord">🌍 Soil (grounds you)</label>
                            <input type="text" id="soilWord" placeholder="e.g., Community, Culture" />
                        </div>
                        <div class="form-group element-group">
                            <label for="seedWord">🌰 Seed (your origin)</label>
                            <input type="text" id="seedWord" placeholder="e.g., First in family, Curiosity" />
                        </div>
                    </div>
                </div>

                <!-- Name & Image -->
                <div class="form-row">
                    <div class="form-group optional half">
                        <label for="creatorName">🌱 Your Name</label>
                        <input type="text" id="creatorName" placeholder="First name or anonymous" />
                    </div>
                    <div class="form-group optional half">
                        <label for="flowerImage">🖼️ Upload Your Flower Image</label>
                        <input type="file" id="flowerImage" accept="image/*" />
                        <div id="imagePreview" class="image-preview hidden">
                            <img id="previewImg" src="#" alt="Preview" />
                            <button type="button" id="removeImageBtn">✕</button>
                        </div>
                    </div>
                </div>

                <button type="submit" class="btn-submit">🌻 Plant in the First-Gen Garden</button>
            </form>
        </div>
    </div>

    <!-- ========================================= -->
    <!-- ===== FLOWER DETAIL MODAL ===== -->
    <!-- ========================================= -->
    <div id="detailModal" class="modal hidden">
        <div class="modal-content detail-content">
            <span class="close-btn" id="closeDetail">&times;</span>
            <div id="detailBody"></div>
        </div>
    </div>

    <script src="script.js"></script>
    <script src="garden.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>💬 The Grove · First Gen Club</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <!-- Navigation -->
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">First Gen Club</span>
            </div>
            <div class="nav-links">
                <a href="index.html">🏠 Home</a>
                <a href="garden.html">🌻 Garden</a>
                <a href="grove.html" class="active">💬 Grove</a>
                <a href="playground.html">🎮 Playground</a>
            </div>
        </div>
    </nav>

    <!-- Page Header -->
    <header class="page-header grove-header">
        <h1>💬 The First-Gen Grove</h1>
        <p>A safe space for first-gen students to connect, share, and support each other.</p>
        <p class="header-sub">🌱 "The First Generation Student Experience Club – always as ONE."</p>
    </header>

    <!-- Chat Main -->
    <main class="grove-main">
        <div class="grove-container">
            <!-- Chat Rooms -->
            <aside class="grove-sidebar">
                <h3>🌿 First-Gen Spaces</h3>
                <ul class="room-list">
                    <li class="room-item active" data-room="general">💬 General Chat</li>
                    <li class="room-item" data-room="support">🤝 First-Gen Support</li>
                    <li class="room-item" data-room="resources">📚 First-Gen Resources</li>
                    <li class="room-item" data-room="events">🎉 First-Gen Events</li>
                    <li class="room-item" data-room="stories">📖 First-Gen Stories</li>
                </ul>
                <button class="btn-add-room" id="addRoomBtn">➕ New Room</button>
            </aside>

            <!-- Chat Area -->
            <section class="grove-chat">
                <div class="chat-header">
                    <span class="chat-room-name" id="chatRoomName">💬 General Chat</span>
                    <span class="chat-member-count" id="chatMemberCount">0 first-gen voices</span>
                </div>
                <div class="chat-messages" id="chatMessages">
                    <div class="chat-welcome">
                        <p>🌱 Welcome to the First-Gen Grove!</p>
                        <p class="small">Share your thoughts, ask questions, and connect with the first-gen community.</p>
                        <p class="small">🏛️ "The root you might say, so we as the first generation student experience club, can always be as ONE."</p>
                    </div>
                </div>
                <div class="chat-input-area">
                    <input type="text" id="chatInput" placeholder="Share your first-gen story..." />
                    <button id="chatSendBtn">📤 Send</button>
                    <button id="chatEmojiBtn">😊</button>
                </div>
            </section>
        </div>
    </main>

    <script src="script.js"></script>
    <script src="grove.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>🎮 Playground · First Gen Club</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <!-- Navigation -->
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">First Gen Club</span>
            </div>
            <div class="nav-links">
                <a href="index.html">🏠 Home</a>
                <a href="garden.html">🌻 Garden</a>
                <a href="grove.html">💬 Grove</a>
                <a href="playground.html" class="active">🎮 Playground</a>
            </div>
        </div>
    </nav>

    <!-- Page Header -->
    <header class="page-header playground-header">
        <h1>🎮 The First-Gen Playground</h1>
        <p>Fun activities to reflect, connect, and grow as first-generation students.</p>
    </header>

    <!-- Activities -->
    <main class="playground-main">
        <!-- Activity 1: Word Cloud -->
        <section class="activity-card" id="wordCloudActivity">
            <div class="activity-header">
                <span class="activity-icon">☁️</span>
                <h2>First-Gen Word Cloud</h2>
                <p>Add words that represent your first-gen journey – watch the cloud grow!</p>
            </div>
            <div class="activity-body">
                <div class="word-cloud" id="wordCloud">
                    <span class="cloud-word" style="font-size: 2.5rem;">Resilience</span>
                    <span class="cloud-word" style="font-size: 1.8rem;">Courage</span>
                    <span class="cloud-word" style="font-size: 2.2rem;">Hope</span>
                    <span class="cloud-word" style="font-size: 1.5rem;">Strength</span>
                    <span class="cloud-word" style="font-size: 1.9rem;">Believe</span>
                    <span class="cloud-word" style="font-size: 1.3rem;">FirstGen</span>
                    <span class="cloud-word" style="font-size: 2.0rem;">Pioneer</span>
                </div>
                <div class="activity-input">
                    <input type="text" id="cloudWordInput" placeholder="Add your first-gen word..." />
                    <button id="cloudAddBtn">➕ Add</button>
                </div>
            </div>
        </section>

        <!-- Activity 2: Gratitude Jar -->
        <section class="activity-card" id="gratitudeActivity">
            <div class="activity-header">
                <span class="activity-icon">🫙</span>
                <h2>First-Gen Gratitude Jar</h2>
                <p>What are you grateful for as a first-gen student?</p>
            </div>
            <div class="activity-body">
                <div class="gratitude-jar" id="gratitudeJar">
                    <div class="jar-items" id="jarItems">
                        <span class="jar-item">🌱 Being the first in my family</span>
                        <span class="jar-item">🌸 Supportive first-gen friends</span>
                        <span class="jar-item">🌻 My family's sacrifice</span>
                    </div>
                    <div class="jar-label">🫙 First-Gen Gratitude Jar</div>
                </div>
                <div class="activity-input">
                    <input type="text" id="gratitudeInput" placeholder="What are you grateful for?" />
                    <button id="gratitudeAddBtn">➕ Add</button>
                </div>
            </div>
        </section>

        <!-- Activity 3: Affirmations -->
        <section class="activity-card" id="affirmationActivity">
            <div class="activity-header">
                <span class="activity-icon">✨</span>
                <h2>First-Gen Affirmations</h2>
                <p>Start your day with a first-gen affirmation.</p>
            </div>
            <div class="activity-body">
                <div class="affirmation-display" id="affirmationDisplay">
                    <p class="affirmation-text">"I am the first, and I am capable of achieving my dreams."</p>
                    <button id="newAffirmationBtn">✨ New Affirmation</button>
                </div>
                <div class="activity-input">
                    <input type="text" id="affirmationInput" placeholder="Write your own first-gen affirmation..." />
                    <button id="affirmationAddBtn">➕ Add</button>
                </div>
            </div>
        </section>

        <!-- Activity 4: First-Gen Challenges -->
        <section class="activity-card" id="challengeActivity">
            <div class="activity-header">
                <span class="activity-icon">🏆</span>
                <h2>First-Gen Weekly Challenges</h2>
                <p>Complete challenges and earn badges!</p>
            </div>
            <div class="activity-body">
                <div class="challenge-display" id="challengeDisplay">
                    <div class="challenge-card">
                        <span class="challenge-icon">🌱</span>
                        <h3>This Week's First-Gen Challenge</h3>
                        <p>Reach out to a fellow first-gen student you haven't met yet.</p>
                        <button class="challenge-complete-btn" id="completeChallengeBtn">✅ Mark Complete</button>
                    </div>
                    <div class="badge-display" id="badgeDisplay">
                        <span class="badge">🌟 First-Gen Starter</span>
                        <span class="badge">🌱 First-Gen Grower</span>
                        <span class="badge">🏆 First-Gen Champion</span>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <script src="script.js"></script>
    <script src="playground.js"></script>
</body>
</html>

/* ============================================
   CTU GROUND - First Gen Club Styles
   ============================================ */

* { margin: 0; padding: 0; box-sizing: border-box; }

:root {
    --primary: #4a3520;
    --primary-light: #6b503a;
    --secondary: #b0947a;
    --background: #f7f0e6;
    --card-bg: #fffcf7;
    --text: #3f2c1b;
    --text-light: #7a6553;
    --shadow: 0 8px 30px rgba(0,0,0,0.08);
    --radius: 20px;
    --transition: all 0.3s ease;
}

body {
    font-family: 'Segoe UI', system-ui, sans-serif;
    background: var(--background);
    color: var(--text);
    min-height: 100vh;
}

/* ----- NAVIGATION ----- */
.main-nav {
    background: rgba(255, 252, 248, 0.92);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid #ece0d2;
    padding: 0 2rem;
    position: sticky;
    top: 0;
    z-index: 100;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0.8rem 0;
}

.nav-brand {
    display: flex;
    align-items: center;
    gap: 8px;
    font-size: 1.3rem;
    font-weight: 700;
    color: var(--primary);
}

.brand-icon { font-size: 1.6rem; }
.brand-sub { font-size: 0.7rem; color: var(--text-light); font-weight: 400; }

.nav-links {
    display: flex;
    gap: 8px;
}

.nav-links a {
    text-decoration: none;
    color: var(--text-light);
    padding: 8px 16px;
    border-radius: 30px;
    font-weight: 600;
    font-size: 0.9rem;
    transition: var(--transition);
}

.nav-links a:hover,
.nav-links a.active {
    background: var(--primary);
    color: white;
}

.nav-toggle { display: none; background: none; border: none; font-size: 1.5rem; cursor: pointer; }

/* ----- HERO ----- */
.hero {
    max-width: 1200px;
    margin: 2rem auto;
    padding: 3rem 2rem;
    background: linear-gradient(135deg, #f5ede4, #e8ddce);
    border-radius: 60px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
    overflow: hidden;
}

.hero-content { flex: 1; z-index: 2; }
.hero h1 { font-size: 3.5rem; color: var(--primary); margin-bottom: 0.5rem; }
.highlight { background: linear-gradient(135deg, #6b503a, #b0947a); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
.hero-tagline { font-size: 1.2rem; color: var(--text-light); font-style: italic; max-width: 600px; }
.hero-stats { display: flex; gap: 2rem; margin: 1.5rem 0; }
.hero-stat { text-align: center; }
.hero-stat .stat-number { display: block; font-size: 2.5rem; font-weight: 800; color: var(--primary); }
.hero-stat .stat-label { font-size: 0.8rem; color: var(--text-light); }
.hero-actions { display: flex; gap: 1rem; flex-wrap: wrap; }

.btn-primary, .btn-secondary {
    padding: 12px 32px;
    border-radius: 60px;
    text-decoration: none;
    font-weight: 700;
    transition: var(--transition);
    border: none;
    cursor: pointer;
    font-size: 1rem;
}

.btn-primary { background: var(--primary); color: white; }
.btn-primary:hover { background: #2f1f12; transform: translateY(-2px); }
.btn-secondary { background: white; color: var(--primary); border: 2px solid var(--primary); }
.btn-secondary:hover { background: var(--primary); color: white; }

.hero-decoration { flex: 0 0 200px; text-align: center; }
.floating-flowers { font-size: 3rem; animation: float 4s infinite alternate ease-in-out; }

@keyframes float {
    0% { transform: translateY(0px) rotate(-5deg); }
    100% { transform: translateY(-20px) rotate(5deg); }
}

/* ----- MISSION & QUICK LINKS ----- */
.mission, .quick-links, .announcements {
    max-width: 1200px;
    margin: 2rem auto;
    padding: 0 2rem;
}

.mission h2, .quick-links h2, .announcements h2 {
    font-size: 2rem;
    color: var(--primary);
    margin-bottom: 1.5rem;
}

.mission-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1.5rem;
}

.mission-card {
    background: var(--card-bg);
    padding: 1.5rem;
    border-radius: var(--radius);
    text-align: center;
    box-shadow: var(--shadow);
    border: 1px solid #ece0d2;
    transition: var(--transition);
}

.mission-card:hover { transform: translateY(-5px); box-shadow: 0 12px 40px rgba(0,0,0,0.12); }
.mission-icon { font-size: 2.5rem; display: block; margin-bottom: 0.5rem; }
.mission-card h3 { font-size: 1.1rem; margin-bottom: 0.5rem; }
.mission-card p { font-size: 0.9rem; color: var(--text-light); }

.link-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.5rem;
}

.link-card {
    background: var(--card-bg);
    padding: 1.5rem;
    border-radius: var(--radius);
    text-decoration: none;
    color: var(--text);
    box-shadow: var(--shadow);
    border: 1px solid #ece0d2;
    transition: var(--transition);
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

.link-card:hover { transform: translateY(-5px); box-shadow: 0 12px 40px rgba(0,0,0,0.12); }
.link-icon { font-size: 3rem; margin-bottom: 0.5rem; }
.link-title { font-size: 1.2rem; font-weight: 700; }
.link-desc { font-size: 0.85rem; color: var(--text-light); margin: 0.3rem 0; }
.link-arrow { font-size: 1.5rem; margin-top: 0.5rem; }

.garden-card { border-left: 5px solid #f5a623; }
.grove-card { border-left: 5px solid #4a90d9; }
.playground-card { border-left: 5px solid #e74c3c; }

/* ----- ANNOUNCEMENTS ----- */
.announcement-list {
    background: var(--card-bg);
    border-radius: var(--radius);
    padding: 1rem;
    box-shadow: var(--shadow);
}

.announcement-item {
    padding: 0.8rem 0;
    border-bottom: 1px solid #ece0d2;
    display: flex;
    gap: 1rem;
    align-items: flex-start;
}

.announcement-item:last-child { border-bottom: none; }
.announcement-date { font-weight: 700; color: var(--secondary); font-size: 0.8rem; white-space: nowrap; }
.announcement-item p { font-size: 0.95rem; }
.btn-add-announcement { margin-top: 1rem; padding: 8px 20px; background: var(--secondary); color: white; border: none; border-radius: 30px; cursor: pointer; font-weight: 600; transition: var(--transition); }
.btn-add-announcement:hover { background: var(--primary-light); }

/* ----- PAGE HEADERS ----- */
.page-header {
    max-width: 1200px;
    margin: 1.5rem auto;
    padding: 2rem;
    text-align: center;
    background: var(--card-bg);
    border-radius: 40px;
    box-shadow: var(--shadow);
    border: 1px solid #ece0d2;
}

.page-header h1 { font-size: 2.5rem; color: var(--primary); }
.page-header p { color: var(--text-light); font-size: 1.1rem; }
.header-sub { font-size: 0.9rem !important; font-style: italic; margin-top: 6px; }

/* ----- GARDEN ----- */
.garden-main { max-width: 1200px; margin: 0 auto; padding: 0 2rem 2rem; }
.garden-container {
    background: #dccfc0;
    background-image: radial-gradient(circle at 20% 30%, #cbb9a6 3px, transparent 3px), radial-gradient(circle at 70% 80%, #cbb9a6 2px, transparent 3px);
    background-size: 60px 60px, 90px 90px;
    border-radius: 40px;
    border: 6px solid #b3987e;
    box-shadow: inset 0 -12px 0 #9a7f66;
    overflow: hidden;
}

.garden-toolbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 20px;
    background: rgba(62, 44, 29, 0.7);
    backdrop-filter: blur(4px);
    color: #f5ede4;
    flex-wrap: wrap;
    gap: 8px;
}

.garden-filters { display: flex; gap: 4px; }
.filter-btn {
    background: rgba(255,255,255,0.15);
    border: none;
    padding: 4px 12px;
    border-radius: 20px;
    color: #f5ede4;
    cursor: pointer;
    font-size: 0.8rem;
    transition: var(--transition);
}
.filter-btn:hover, .filter-btn.active { background: rgba(255,255,255,0.3); }

.garden-bed {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-end;
    gap: 20px 25px;
    min-height: 350px;
    padding: 25px 20px 20px;
}

/* ----- FLOWER CARDS ----- */
.flower-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    cursor: pointer;
    transition: transform 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
    animation: float 5s infinite alternate ease-in-out;
    padding: 6px 12px 8px;
    border-radius: 30px;
    background: rgba(255, 248, 240, 0.25);
    backdrop-filter: blur(2px);
    min-width: 70px;
}

.flower-card:hover { transform: scale(1.12) translateY(-10px); z-index: 10; background: rgba(255, 248, 240, 0.5); }
.flower-card .flower-emoji { font-size: 3.2rem; line-height: 1.1; }
.flower-card .flower-center-word {
    font-size: 0.65rem;
    background: rgba(62, 44, 29, 0.8);
    color: #f5ede4;
    padding: 2px 12px;
    border-radius: 30px;
    font-weight: 700;
    max-width: 80px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    margin-top: -4px;
}
.flower-card .flower-petal-count {
    font-size: 0.5rem;
    color: #5a4432;
    background: rgba(255, 248, 240, 0.85);
    padding: 0 10px;
    border-radius: 20px;
}

/* ----- CONTROLS ----- */
.controls {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 8px;
    margin: 16px 0;
}

.btn-action, .btn-danger {
    padding: 10px 18px;
    border-radius: 60px;
    font-size: 0.85rem;
    font-weight: 700;
    border: 2px solid #b0947a;
    cursor: pointer;
    transition: var(--transition);
    box-shadow: 0 4px 0 #8f745c;
}

.btn-action:active, .btn-danger:active { transform: translateY(4px); box-shadow: none; }
.btn-action { background: #f1e8dd; color: #3f2d1d; }
.btn-action:hover { background: #e4d6c6; }
.btn-danger { background: #e8d5c4; color: #6b3f2a; border-color: #b08872; }
.btn-danger:hover { background: #dcc4b0; }

/* ----- STATS ----- */
.stats {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
    gap: 12px;
    margin: 12px 0 20px;
}

.stat-card {
    background: var(--card-bg);
    padding: 12px 10px;
    border-radius: 30px;
    text-align: center;
    border: 1px solid #dccfc0;
}

.stat-number { display: block; font-size: 2rem; font-weight: 800; color: var(--primary); }
.stat-label { font-size: 0.7rem; color: var(--text-light); }

/* ----- REFLECTION ----- */
.reflection {
    background: #f3ebe2;
    border-radius: 40px;
    padding: 1.2rem 1.8rem;
    border-left: 6px solid #b49274;
}

.reflection h3 { color: #4f3824; font-size: 1.2rem; margin-bottom: 6px; }

/* ----- MODAL ----- */
.modal {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(30, 20, 12, 0.7);
    backdrop-filter: blur(10px);
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 1000;
    padding: 20px;
}

.modal.hidden { display: none; }
.modal-content {
    background: var(--card-bg);
    border-radius: 40px;
    padding: 2rem;
    max-width: 650px;
    width: 100%;
    max-height: 90vh;
    overflow-y: auto;
    position: relative;
    box-shadow: 0 40px 80px rgba(0,0,0,0.3);
}

.close-btn {
    position: sticky;
    float: right;
    top: 0;
    font-size: 2rem;
    cursor: pointer;
    color: var(--text-light);
    background: var(--card-bg);
    padding: 0 8px;
    border-radius: 30px;
    z-index: 10;
}

.close-btn:hover { color: var(--primary); transform: rotate(90deg); }

/* ----- FORM ----- */
.form-group { margin-bottom: 1rem; }
.form-group label { display: block; font-weight: 600; color: #5a4432; margin-bottom: 4px; font-size: 0.9rem; }
.form-group input[type="text"], .form-group input[type="file"] {
    width: 100%;
    padding: 10px 16px;
    border: 2px solid #d6c6b6;
    border-radius: 30px;
    font-size: 0.95rem;
    background: #fffcf8;
    transition: 0.2s;
}
.form-group input:focus { outline: none; border-color: #b0947a; box-shadow: 0 0 0 4px rgba(176, 148, 122, 0.15); }

.flower-selector {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(50px, 1fr));
    gap: 6px;
}
.flower-option {
    display: flex;
    align-items: center;
    justify-content: center;
    background: #f5ede4;
    padding: 6px;
    border-radius: 30px;
    border: 2px solid transparent;
    cursor: pointer;
    font-size: 1.5rem;
}
.flower-option:has(input:checked) { border-color: #b0947a; background: #e8dccc; }
.flower-option input { display: none; }

.petals-grid, .elements-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
}

.form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }

.btn-submit {
    width: 100%;
    padding: 14px;
    background: var(--primary);
    color: white;
    border: none;
    border-radius: 60px;
    font-size: 1.1rem;
    font-weight: 700;
    cursor: pointer;
    transition: var(--transition);
}
.btn-submit:hover { background: #2f1f12; }

/* ----- CHAT ----- */
.grove-main { max-width: 1200px; margin: 0 auto; padding: 0 2rem 2rem; }
.grove-container { display: flex; gap: 1.5rem; min-height: 500px; }

.grove-sidebar {
    flex: 0 0 200px;
    background: var(--card-bg);
    border-radius: var(--radius);
    padding: 1rem;
    box-shadow: var(--shadow);
}
.grove-sidebar h3 { margin-bottom: 0.5rem; color: var(--primary); }

.room-list { list-style: none; padding: 0; }
.room-item {
    padding: 8px 12px;
    border-radius: 30px;
    cursor: pointer;
    transition: var(--transition);
    font-size: 0.9rem;
}
.room-item:hover { background: #f0e8df; }
.room-item.active { background: var(--primary); color: white; }

.grove-chat {
    flex: 1;
    background: var(--card-bg);
    border-radius: var(--radius);
    box-shadow: var(--shadow);
    display: flex;
    flex-direction: column;
}
.chat-header {
    padding: 12px 20px;
    border-bottom: 1px solid #ece0d2;
    display: flex;
    justify-content: space-between;
}
.chat-messages {
    flex: 1;
    padding: 1rem;
    overflow-y: auto;
    max-height: 400px;
}
.chat-message {
    padding: 8px 14px;
    margin: 4px 0;
    border-radius: 20px;
    background: #f5ede4;
    max-width: 80%;
}
.chat-message.self { background: var(--primary); color: white; margin-left: auto; }
.chat-message .msg-name { font-weight: 700; font-size: 0.8rem; }
.chat-message .msg-time { font-size: 0.6rem; opacity: 0.6; margin-left: 8px; }

.chat-input-area {
    display: flex;
    gap: 8px;
    padding: 12px;
    border-top: 1px solid #ece0d2;
}
.chat-input-area input { flex: 1; padding: 10px 16px; border: 2px solid #d6c6b6; border-radius: 30px; }
.chat-input-area button {
    padding: 10px 20px;
    border: none;
    border-radius: 30px;
    background: var(--primary);
    color: white;
    font-weight: 700;
    cursor: pointer;
}
.chat-input-area button:hover { background: #2f1f12; }

/* ----- PLAYGROUND ----- */
.playground-main {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem 2rem;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.5rem;
}

.activity-card {
    background: var(--card-bg);
    border-radius: var(--radius);
    box-shadow: var(--shadow);
    padding: 1.5rem;
    border: 1px solid #ece0d2;
}

.activity-header { text-align: center; margin-bottom: 1rem; }
.activity-icon { font-size: 2.5rem; display: block; }
.activity-header h2 { font-size: 1.3rem; color: var(--primary); }
.activity-header p { font-size: 0.85rem; color: var(--text-light); }

.activity-body { text-align: center; }
.activity-input { display: flex; gap: 8px; margin-top: 1rem; justify-content: center; }
.activity-input input { padding: 8px 16px; border: 2px solid #d6c6b6; border-radius: 30px; flex: 1; max-width: 300px; }
.activity-input button { padding: 8px 20px; border: none; border-radius: 30px; background: var(--primary); color: white; font-weight: 700; cursor: pointer; }

.word-cloud { display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 8px; min-height: 120px; padding: 1rem; }
.cloud-word { font-weight: 700; color: var(--primary); }

.gratitude-jar {
    border: 3px dashed var(--secondary);
    border-radius: 20px;
    padding: 1rem;
    min-height: 120px;
    position: relative;
}
.jar-items { display: flex; flex-wrap: wrap; gap: 6px; justify-content: center; }
.jar-item { background: #f5ede4; padding: 4px 12px; border-radius: 20px; font-size: 0.85rem; }
.jar-label { text-align: center; margin-top: 8px; font-weight: 700; color: var(--text-light); }

.affirmation-text { font-size: 1.5rem; font-style: italic; color: var(--primary); padding: 1rem; }

.challenge-card {
    background: #f5ede4;
    border-radius: 20px;
    padding: 1.5rem;
}
.challenge-icon { font-size: 2.5rem; display: block; }
.challenge-card h3 { font-size: 1.1rem; }
.badge-display { display: flex; gap: 8px; justify-content: center; margin-top: 1rem; flex-wrap: wrap; }
.badge {
    background: var(--primary);
    color: white;
    padding: 4px 16px;
    border-radius: 30px;
    font-size: 0.8rem;
    font-weight: 600;
}

/* ----- FOOTER ----- */
footer {
    background: var(--primary);
    color: #f5ede4;
    padding: 2rem;
    margin-top: 2rem;
}

.footer-content {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 1rem;
}

.footer-brand span { font-size: 1.3rem; font-weight: 700; }
.footer-brand p { font-size: 0.85rem; opacity: 0.7; }
.footer-links { display: flex; gap: 1rem; }
.footer-links a { color: #f5ede4; text-decoration: none; opacity: 0.7; transition: var(--transition); }
.footer-links a:hover { opacity: 1; }
.footer-credit { text-align: right; font-size: 0.8rem; opacity: 0.7; }
.footer-tagline { font-style: italic; }

/* ----- RESPONSIVE ----- */
@media (max-width: 768px) {
    .nav-links { display: none; }
    .nav-links.open { display: flex; flex-direction: column; position: absolute; top: 100%; left: 0; right: 0; background: var(--card-bg); padding: 1rem; box-shadow: var(--shadow); }
    .nav-toggle { display: block; }
    
    .hero { flex-direction: column; text-align: center; padding: 2rem 1rem; }
    .hero h1 { font-size: 2.5rem; }
    .hero-stats { justify-content: center; }
    .hero-actions { justify-content: center; }
    .hero-decoration { display: none; }
    
    .grove-container { flex-direction: column; }
    .grove-sidebar { flex: auto; }
    
    .playground-main { grid-template-columns: 1fr; }
    .petals-grid, .elements-grid, .form-row { grid-template-columns: 1fr; }
    .stats { grid-template-columns: 1fr 1fr; }
}

@media (max-width: 480px) {
    .hero h1 { font-size: 2rem; }
    .page-header h1 { font-size: 1.8rem; }
    .controls button { font-size: 0.7rem; padding: 6px 12px; }
    .flower-card .flower-emoji { font-size: 2.4rem; }
}

Feature Purpose
🌻 Garden Each flower tells a first-gen student's story
💬 Grove Safe space for first-gen students to connect
🎮 Playground Activities to reflect on the first-gen journey
🏛️ Mission Celebrating first-generation identity
📊 Stats Tracking the growing first-gen community

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>🏛️ CTU Ground · First Gen Club</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="manifest" href="manifest.json" />
    <meta name="theme-color" content="#4a3520" />
    <meta name="description" content="CTU Ground – First Generation Student Experience Club" />
</head>
<body>
    <!-- ===== NAVIGATION ===== -->
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">First Gen Club</span>
            </div>
            <div class="nav-links" id="navLinks">
                <a href="index.html" class="active">🏠 Home</a>
                <a href="garden.html">🌻 Garden</a>
                <a href="grove.html">💬 Grove</a>
                <a href="playground.html">🎮 Playground</a>
                <a href="profile.html" id="profileLink">👤 Profile</a>
            </div>
            <div class="nav-auth">
                <span id="userDisplay" class="user-display"></span>
                <button id="logoutBtn" class="btn-logout" style="display:none;">🚪 Logout</button>
                <button id="loginBtn" class="btn-login">🔑 Login</button>
                <button class="nav-toggle" id="navToggle">☰</button>
            </div>
        </div>
    </nav>

    <!-- ===== LOGIN MODAL ===== -->
    <div id="loginModal" class="modal hidden">
        <div class="modal-content auth-modal">
            <span class="close-btn" id="closeLogin">&times;</span>
            <h2>🔑 Welcome First-Gen Student</h2>
            <div id="authTabs" class="auth-tabs">
                <button class="auth-tab active" data-tab="login">Login</button>
                <button class="auth-tab" data-tab="register">Register</button>
            </div>
            
            <!-- Login Form -->
            <form id="loginForm" class="auth-form">
                <div class="form-group">
                    <label for="loginEmail">📧 Email</label>
                    <input type="email" id="loginEmail" placeholder="your@email.com" required />
                </div>
                <div class="form-group">
                    <label for="loginPassword">🔒 Password</label>
                    <input type="password" id="loginPassword" placeholder="Enter password" required />
                </div>
                <button type="submit" class="btn-submit">🔑 Login</button>
                <p class="auth-switch">Don't have an account? <a href="#" id="switchToRegister">Register here</a></p>
            </form>

            <!-- Register Form -->
            <form id="registerForm" class="auth-form hidden">
                <div class="form-group">
                    <label for="registerName">🌱 Your Name</label>
                    <input type="text" id="registerName" placeholder="First name" required />
                </div>
                <div class="form-group">
                    <label for="registerEmail">📧 Email</label>
                    <input type="email" id="registerEmail" placeholder="your@email.com" required />
                </div>
                <div class="form-group">
                    <label for="registerPassword">🔒 Password (min 6 chars)</label>
                    <input type="password" id="registerPassword" placeholder="Create password" required minlength="6" />
                </div>
                <div class="form-group">
                    <label for="registerYear">🎓 Year</label>
                    <select id="registerYear">
                        <option value="Freshman">Freshman</option>
                        <option value="Sophomore">Sophomore</option>
                        <option value="Junior">Junior</option>
                        <option value="Senior">Senior</option>
                        <option value="Alumni">Alumni</option>
                    </select>
                </div>
                <div class="form-group checkbox">
                    <input type="checkbox" id="registerFirstGen" checked />
                    <label for="registerFirstGen">✅ I am a first-generation student</label>
                </div>
                <button type="submit" class="btn-submit">🌱 Join the Club</button>
                <p class="auth-switch">Already a member? <a href="#" id="switchToLogin">Login here</a></p>
            </form>
        </div>
    </div>

    <!-- ===== HERO ===== -->
    <header class="hero">
        <div class="hero-content">
            <h1>🌱 Welcome to <span class="highlight">CTU Ground</span></h1>
            <p class="hero-tagline">"The root you might say, so we as the <strong>first generation student experience club</strong>, can always be as ONE."</p>
            <div class="hero-stats">
                <div class="hero-stat">
                    <span class="stat-number" id="heroFlowers">0</span>
                    <span class="stat-label">🌻 First-Gen Flowers</span>
                </div>
                <div class="hero-stat">
                    <span class="stat-number" id="heroMembers">0</span>
                    <span class="stat-label">👥 First-Gen Voices</span>
                </div>
                <div class="hero-stat">
                    <span class="stat-number" id="heroMessages">0</span>
                    <span class="stat-label">💬 First-Gen Stories</span>
                </div>
            </div>
            <div class="hero-actions">
                <a href="garden.html" class="btn-primary">🌱 Plant Your Flower</a>
                <a href="grove.html" class="btn-secondary">💬 Join the Grove</a>
            </div>
        </div>
        <div class="hero-decoration">
            <div class="floating-flowers">
                <span>🌸</span>
                <span>🌻</span>
                <span>🌺</span>
                <span>🌷</span>
                <span>🌼</span>
            </div>
        </div>
    </header>

    <!-- ===== THEME SELECTOR ===== -->
    <section class="theme-selector">
        <h3>🎨 Choose Your Theme</h3>
        <div class="theme-buttons">
            <button class="theme-btn" data-theme="default" style="background:#4a3520;">🌿 Default</button>
            <button class="theme-btn" data-theme="sunset" style="background:#e76f51;">🌅 Sunset</button>
            <button class="theme-btn" data-theme="ocean" style="background:#2a9d8f;">🌊 Ocean</button>
            <button class="theme-btn" data-theme="spring" style="background:#2ecc71;">🌸 Spring</button>
            <button class="theme-btn" data-theme="midnight" style="background:#1a1a2e;">🌙 Midnight</button>
        </div>
    </section>

    <!-- ===== MISSION ===== -->
    <section class="mission">
        <h2>🏛️ Our Mission as First-Gen Students</h2>
        <div class="mission-grid">
            <div class="mission-card">
                <div class="mission-icon">🌱</div>
                <h3>First Generation</h3>
                <p>We are the first in our families to pursue higher education. We lead the way.</p>
            </div>
            <div class="mission-card">
                <div class="mission-icon">🌻</div>
                <h3>Growth Together</h3>
                <p>Every flower is different, yet rooted in the same soil—community, support, and shared context.</p>
            </div>
            <div class="mission-card">
                <div class="mission-icon">🏛️</div>
                <h3>Legacy</h3>
                <p>Building a foundation for first-gen students, alumni, and generations to come.</p>
            </div>
            <div class="mission-card">
                <div class="mission-icon">🤝</div>
                <h3>Community</h3>
                <p>A space where first-gen students can connect, share, and grow together.</p>
            </div>
        </div>
    </section>

    <!-- ===== QUICK LINKS ===== -->
    <section class="quick-links">
        <h2>🌿 Explore CTU Ground</h2>
        <div class="link-grid">
            <a href="garden.html" class="link-card garden-card">
                <span class="link-icon">🌻</span>
                <span class="link-title">Digital Garden</span>
                <span class="link-desc">Plant your flower and share your first-gen story</span>
                <span class="link-arrow">→</span>
            </a>
            <a href="grove.html" class="link-card grove-card">
                <span class="link-icon">💬</span>
                <span class="link-title">The Grove</span>
                <span class="link-desc">Connect with fellow first-gen students</span>
                <span class="link-arrow">→</span>
            </a>
            <a href="playground.html" class="link-card playground-card">
                <span class="link-icon">🎮</span>
                <span class="link-title">The Playground</span>
                <span class="link-desc">Activities and reflections for first-gen growth</span>
                <span class="link-arrow">→</span>
            </a>
        </div>
    </section>

    <!-- ===== ANNOUNCEMENTS ===== -->
    <section class="announcements">
        <h2>📢 First-Gen Announcements</h2>
        <div class="announcement-list" id="announcementList">
            <div class="announcement-item">
                <span class="announcement-date">Today</span>
                <p>🌱 Welcome to CTU Ground! Plant your flower and join the first-gen community.</p>
            </div>
            <div class="announcement-item">
                <span class="announcement-date">This Week</span>
                <p>🌻 First-Gen Meetup – Friday at 5pm in the Student Union</p>
            </div>
            <div class="announcement-item">
                <span class="announcement-date">Ongoing</span>
                <p>🏛️ "The First Generation Student Experience Club" – We are the root that continues to grow.</p>
            </div>
        </div>
        <button class="btn-add-announcement" id="addAnnouncementBtn">➕ Add Announcement</button>
    </section>

    <!-- ===== FOOTER ===== -->
    <footer>
        <div class="footer-content">
            <div class="footer-brand">
                <span>🏛️ CTU Ground</span>
                <p>First Generation Student Experience Club</p>
            </div>
            <div class="footer-links">
                <a href="index.html">Home</a>
                <a href="garden.html">Garden</a>
                <a href="grove.html">Grove</a>
                <a href="playground.html">Playground</a>
            </div>
            <div class="footer-credit">
                <p>🌱 Made by <strong>Suzanne Michelle Sellers Damons</strong></p>
                <p class="footer-tagline">"Growth is individual and collective—every flower is different, yet rooted in the same soil."</p>
            </div>
        </div>
    </footer>

    <script src="auth.js"></script>
    <script src="script.js"></script>
    <script>
        function updateHeroStats() {
            const garden = JSON.parse(localStorage.getItem('sharedDigitalGarden') || '[]');
            const grove = JSON.parse(localStorage.getItem('groveMessages') || '[]');
            document.getElementById('heroFlowers').textContent = garden.length;
            document.getElementById('heroMembers').textContent = garden.length || '0';
            document.getElementById('heroMessages').textContent = grove.length;
        }
        updateHeroStats();
        window.addEventListener('storage', updateHeroStats);
        
        // Register Service Worker for PWA
        if ('serviceWorker' in navigator) {
            navigator.serviceWorker.register('/sw.js')
                .then(() => console.log('📱 PWA Service Worker registered'))
                .catch(() => console.log('📱 PWA registration failed'));
        }
    </script>
</body>
</html>

/* ============================================
   CTU GROUND - Authentication System
   ============================================ */

// ----- STATE -----
let currentUser = null;

// ----- DOM REFS -----
const loginModal = document.getElementById('loginModal');
const loginBtn = document.getElementById('loginBtn');
const logoutBtn = document.getElementById('logoutBtn');
const closeLogin = document.getElementById('closeLogin');
const userDisplay = document.getElementById('userDisplay');

const loginForm = document.getElementById('loginForm');
const registerForm = document.getElementById('registerForm');
const loginTab = document.querySelector('[data-tab="login"]');
const registerTab = document.querySelector('[data-tab="register"]');
const switchToRegister = document.getElementById('switchToRegister');
const switchToLogin = document.getElementById('switchToLogin');

// ----- INIT -----
function initAuth() {
    // Check localStorage for session
    const saved = localStorage.getItem('ctuUser');
    if (saved) {
        try {
            currentUser = JSON.parse(saved);
            updateUI();
        } catch (e) {
            localStorage.removeItem('ctuUser');
        }
    }
}

// ----- UPDATE UI -----
function updateUI() {
    if (currentUser) {
        userDisplay.textContent = `🌱 ${currentUser.name}`;
        userDisplay.style.display = 'inline';
        loginBtn.style.display = 'none';
        logoutBtn.style.display = 'inline';
        document.getElementById('profileLink').style.display = 'inline';
        
        // Update all pages with user info
        document.querySelectorAll('.user-name-display').forEach(el => {
            el.textContent = currentUser.name;
        });
    } else {
        userDisplay.style.display = 'none';
        loginBtn.style.display = 'inline';
        logoutBtn.style.display = 'none';
        document.getElementById('profileLink').style.display = 'none';
    }
}

// ----- LOGIN -----
loginBtn?.addEventListener('click', () => loginModal.classList.remove('hidden'));

closeLogin?.addEventListener('click', () => loginModal.classList.add('hidden'));

window.addEventListener('click', (e) => {
    if (e.target === loginModal) loginModal.classList.add('hidden');
});

// Switch between login/register
loginTab?.addEventListener('click', function() {
    loginTab.classList.add('active');
    registerTab.classList.remove('active');
    loginForm.classList.remove('hidden');
    registerForm.classList.add('hidden');
});

registerTab?.addEventListener('click', function() {
    registerTab.classList.add('active');
    loginTab.classList.remove('active');
    registerForm.classList.remove('hidden');
    loginForm.classList.add('hidden');
});

switchToRegister?.addEventListener('click', (e) => {
    e.preventDefault();
    registerTab.click();
});

switchToLogin?.addEventListener('click', (e) => {
    e.preventDefault();
    loginTab.click();
});

// ----- LOGIN FORM -----
loginForm?.addEventListener('submit', function(e) {
    e.preventDefault();
    
    const email = document.getElementById('loginEmail').value.trim();
    const password = document.getElementById('loginPassword').value.trim();
    
    // Get users from localStorage
    const users = JSON.parse(localStorage.getItem('ctuUsers') || '[]');
    const user = users.find(u => u.email === email && u.password === password);
    
    if (user) {
        currentUser = {
            id: user.id,
            name: user.name,
            email: user.email,
            year: user.year,
            firstGen: user.firstGen
        };
        localStorage.setItem('ctuUser', JSON.stringify(currentUser));
        updateUI();
        loginModal.classList.add('hidden');
        loginForm.reset();
        showNotification('🌸 Welcome back, ' + user.name + '!', 'success');
        
        // Update hero stats
        if (window.updateHeroStats) window.updateHeroStats();
    } else {
        showNotification('❌ Invalid email or password. Please try again.', 'error');
    }
});

// ----- REGISTER FORM -----
registerForm?.addEventListener('submit', function(e) {
    e.preventDefault();
    
    const name = document.getElementById('registerName').value.trim();
    const email = document.getElementById('registerEmail').value.trim();
    const password = document.getElementById('registerPassword').value.trim();
    const year = document.getElementById('registerYear').value;
    const firstGen = document.getElementById('registerFirstGen').checked;
    
    if (!name || !email || !password) {
        showNotification('❌ Please fill in all fields.', 'error');
        return;
    }
    
    if (password.length < 6) {
        showNotification('❌ Password must be at least 6 characters.', 'error');
        return;
    }
    
    // Get existing users
    const users = JSON.parse(localStorage.getItem('ctuUsers') || '[]');
    
    // Check if email already exists
    if (users.find(u => u.email === email)) {
        showNotification('❌ This email is already registered.', 'error');
        return;
    }
    
    // Create new user
    const newUser = {
        id: Date.now(),
        name: name,
        email: email,
        password: password,
        year: year,
        firstGen: firstGen,
        joined: new Date().toISOString(),
        flowers: 0,
        messages: 0
    };
    
    users.push(newUser);
    localStorage.setItem('ctuUsers', JSON.stringify(users));
    
    // Auto-login
    currentUser = {
        id: newUser.id,
        name: newUser.name,
        email: newUser.email,
        year: newUser.year,
        firstGen: newUser.firstGen
    };
    localStorage.setItem('ctuUser', JSON.stringify(currentUser));
    updateUI();
    registerForm.reset();
    loginModal.classList.add('hidden');
    
    showNotification('🌱 Welcome to the First Gen Club, ' + name + '!', 'success');
    
    // Update hero stats
    if (window.updateHeroStats) window.updateHeroStats();
});

// ----- LOGOUT -----
logoutBtn?.addEventListener('click', function() {
    if (confirm('🚪 Are you sure you want to logout?')) {
        localStorage.removeItem('ctuUser');
        currentUser = null;
        updateUI();
        showNotification('👋 Goodbye! See you soon.', 'info');
    }
});

// ----- NOTIFICATION SYSTEM -----
function showNotification(message, type = 'info') {
    const existing = document.querySelector('.notification');
    if (existing) existing.remove();
    
    const notif = document.createElement('div');
    notif.className = `notification ${type}`;
    notif.textContent = message;
    document.body.appendChild(notif);
    
    setTimeout(() => {
        notif.style.opacity = '0';
        setTimeout(() => notif.remove(), 300);
    }, 3000);
}

// ----- EXPORT FOR OTHER PAGES -----
window.showNotification = showNotification;
window.getCurrentUser = () => currentUser;

// ----- INIT -----
initAuth();

/* Add these to the existing style.css */

/* ----- NOTIFICATIONS ----- */
.notification {
    position: fixed;
    bottom: 30px;
    left: 50%;
    transform: translateX(-50%);
    padding: 14px 28px;
    border-radius: 60px;
    font-weight: 600;
    z-index: 9999;
    box-shadow: 0 10px 40px rgba(0,0,0,0.2);
    animation: slideUp 0.4s ease;
    max-width: 90%;
}

.notification.success { background: #2ecc71; color: white; }
.notification.error { background: #e74c3c; color: white; }
.notification.info { background: #3498db; color: white; }

@keyframes slideUp {
    from { opacity: 0; transform: translateX(-50%) translateY(20px); }
    to { opacity: 1; transform: translateX(-50%) translateY(0); }
}

/* ----- AUTH ----- */
.auth-modal { max-width: 450px; }
.auth-tabs { display: flex; gap: 0; margin-bottom: 1.5rem; border-radius: 30px; overflow: hidden; border: 2px solid var(--primary); }
.auth-tab {
    flex: 1;
    padding: 10px;
    background: var(--card-bg);
    border: none;
    cursor: pointer;
    font-weight: 600;
    color: var(--text-light);
    transition: var(--transition);
}
.auth-tab.active { background: var(--primary); color: white; }
.auth-tab:hover:not(.active) { background: #f0e8df; }

.auth-form.hidden { display: none; }
.auth-switch { text-align: center; margin-top: 1rem; font-size: 0.9rem; color: var(--text-light); }
.auth-switch a { color: var(--primary); font-weight: 600; cursor: pointer; }

.checkbox { display: flex; align-items: center; gap: 8px; }
.checkbox input { width: auto !important; }

.nav-auth { display: flex; align-items: center; gap: 10px; }
.user-display { font-weight: 600; color: var(--primary); font-size: 0.9rem; }
.btn-login, .btn-logout {
    padding: 6px 16px;
    border-radius: 30px;
    border: none;
    font-weight: 600;
    cursor: pointer;
    transition: var(--transition);
}
.btn-login { background: var(--primary); color: white; }
.btn-login:hover { background: #2f1f12; }
.btn-logout { background: #e8d5c4; color: #6b3f2a; }
.btn-logout:hover { background: #dcc4b0; }

/* ----- THEME SELECTOR ----- */
.theme-selector {
    max-width: 1200px;
    margin: 1.5rem auto;
    padding: 1rem 2rem;
    text-align: center;
    background: var(--card-bg);
    border-radius: 40px;
    box-shadow: var(--shadow);
    border: 1px solid #ece0d2;
}

.theme-selector h3 { margin-bottom: 0.5rem; color: var(--primary); }
.theme-buttons { display: flex; gap: 10px; justify-content: center; flex-wrap: wrap; }
.theme-btn {
    padding: 8px 20px;
    border-radius: 30px;
    border: 3px solid transparent;
    cursor: pointer;
    font-weight: 600;
    color: white;
    transition: var(--transition);
}
.theme-btn:hover { transform: scale(1.05); }
.theme-btn.active { border-color: #f5a623; box-shadow: 0 0 0 3px rgba(245, 166, 35, 0.3); }

/* ----- THEMES ----- */
body.theme-sunset { --primary: #e76f51; --primary-light: #f4a261; --secondary: #e9c46a; --background: #fef0e6; }
body.theme-ocean { --primary: #2a9d8f; --primary-light: #4ecdc4; --secondary: #264653; --background: #e8f4f0; }
body.theme-spring { --primary: #2ecc71; --primary-light: #58d68d; --secondary: #f1c40f; --background: #f0f8f0; }
body.theme-midnight { --primary: #1a1a2e; --primary-light: #16213e; --secondary: #0f3460; --background: #1a1a2e; color: #e8e8e8; }
body.theme-midnight .mission-card, 
body.theme-midnight .activity-card,
body.theme-midnight .stat-card,
body.theme-midnight .announcement-list,
body.theme-midnight .garden-container,
body.theme-midnight .modal-content,
body.theme-midnight .page-header,
body.theme-midnight .reflection,
body.theme-midnight .theme-selector,
body.theme-midnight .link-card,
body.theme-midnight .grove-sidebar,
body.theme-midnight .grove-chat { background: #2a2a4a; color: #e8e8e8; border-color: #3a3a5a; }
body.theme-midnight .stat-label,
body.theme-midnight .mission-card p,
body.theme-midnight .link-desc,
body.theme-midnight .reflection-placeholder,
body.theme-midnight .modal-subtitle { color: #aaa; }

/* ----- PROFILE PAGE ----- */
.profile-main { max-width: 800px; margin: 0 auto; padding: 0 2rem 2rem; }
.profile-card {
    background: var(--card-bg);
    border-radius: 40px;
    padding: 2rem;
    box-shadow: var(--shadow);
    border: 1px solid #ece0d2;
    text-align: center;
}

.profile-avatar {
    font-size: 5rem;
    margin-bottom: 0.5rem;
    animation: float 4s infinite alternate ease-in-out;
}

.profile-name { font-size: 2rem; color: var(--primary); }
.profile-badge { display: inline-block; padding: 4px 16px; background: var(--primary); color: white; border-radius: 30px; font-size: 0.8rem; margin: 8px 0; }

.profile-stats-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
    margin: 1.5rem 0;
}

.profile-stat {
    background: #f5ede4;
    padding: 1rem;
    border-radius: 20px;
}
.profile-stat .stat-number { font-size: 2rem; font-weight: 800; color: var(--primary); }
.profile-stat .stat-label { font-size: 0.8rem; color: var(--text-light); }

.profile-edit-btn {
    padding: 10px 30px;
    background: var(--primary);
    color: white;
    border: none;
    border-radius: 60px;
    font-weight: 700;
    cursor: pointer;
    transition: var(--transition);
}
.profile-edit-btn:hover { background: #2f1f12; }

/* ----- RESPONSIVE ADDITIONS ----- */
@media (max-width: 768px) {
    .nav-auth { gap: 6px; }
    .user-display { font-size: 0.7rem; }
    .profile-stats-grid { grid-template-columns: 1fr 1fr; }
    .theme-selector { padding: 1rem; }
    .theme-buttons { gap: 6px; }
    .theme-btn { font-size: 0.7rem; padding: 4px 12px; }
}

{
    "name": "CTU Ground - First Gen Club",
    "short_name": "CTU Ground",
    "description": "First Generation Student Experience Club",
    "start_url": "/",
    "display": "standalone",
    "background_color": "#f7f0e6",
    "theme_color": "#4a3520",
    "icons": [
        {
            "src": "icon-192.png",
            "sizes": "192x192",
            "type": "image/png"
        },
        {
            "src": "icon-512.png",
            "sizes": "512x512",
            "type": "image/png"
        }
    ],
    "categories": ["education", "social", "community"],
    "screenshots": [
        {
            "src": "screenshot-1.png",
            "sizes": "1080x1920",
            "type": "image/png"
        }
    ]
}

// CTU Ground - Service Worker
const CACHE_NAME = 'ctu-ground-v1';
const ASSETS = [
    '/',
    '/index.html',
    '/garden.html',
    '/grove.html',
    '/playground.html',
    '/profile.html',
    '/style.css',
    '/script.js',
    '/auth.js',
    '/garden.js',
    '/grove.js',
    '/playground.js',
    '/manifest.json'
];

self.addEventListener('install', (e) => {
    e.waitUntil(
        caches.open(CACHE_NAME)
            .then(cache => cache.addAll(ASSETS))
            .then(() => self.skipWaiting())
    );
});

self.addEventListener('activate', (e) => {
    e.waitUntil(
        caches.keys().then(keys => {
            return Promise.all(
                keys.filter(key => key !== CACHE_NAME)
                    .map(key => caches.delete(key))
            );
        }).then(() => self.clients.claim())
    );
});

self.addEventListener('fetch', (e) => {
    e.respondWith(
        caches.match(e.request)
            .then(response => response || fetch(e.request))
    );
});

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>👤 Profile · CTU Ground</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">First Gen Club</span>
            </div>
            <div class="nav-links">
                <a href="index.html">🏠 Home</a>
                <a href="garden.html">🌻 Garden</a>
                <a href="grove.html">💬 Grove</a>
                <a href="playground.html">🎮 Playground</a>
                <a href="profile.html" class="active">👤 Profile</a>
            </div>
            <div class="nav-auth">
                <span id="userDisplay" class="user-display"></span>
                <button id="logoutBtn" class="btn-logout">🚪 Logout</button>
            </div>
        </div>
    </nav>

    <main class="profile-main">
        <div class="profile-card" id="profileCard">
            <div class="profile-avatar" id="profileAvatar">🌱</div>
            <h2 class="profile-name" id="profileName">First-Gen Student</h2>
            <span class="profile-badge" id="profileBadge">🎓 First Generation</span>
            <p id="profileEmail" style="color:var(--text-light);">email@example.com</p>
            
            <div class="profile-stats-grid">
                <div class="profile-stat">
                    <span class="stat-number" id="profileFlowers">0</span>
                    <span class="stat-label">🌸 Flowers Planted</span>
                </div>
                <div class="profile-stat">
                    <span class="stat-number" id="profileMessages">0</span>
                    <span class="stat-label">💬 Messages</span>
                </div>
                <div class="profile-stat">
                    <span class="stat-number" id="profileDays">0</span>
                    <span class="stat-label">📅 Days in Club</span>
                </div>
            </div>
            
            <button class="profile-edit-btn" id="editProfileBtn">✏️ Edit Profile</button>
        </div>
    </main>

    <footer>
        <div class="footer-content">
            <div class="footer-brand">
                <span>🏛️ CTU Ground</span>
                <p>First Generation Student Experience Club</p>
            </div>
            <div class="footer-credit">
                <p>🌱 Made by <strong>Suzanne Michelle Sellers Damons</strong></p>
            </div>
        </div>
    </footer>

    <script src="auth.js"></script>
    <script>
        // Load profile data
        function loadProfile() {
            const user = getCurrentUser();
            if (!user) {
                window.location.href = 'index.html';
                return;
            }
            
            document.getElementById('profileName').textContent = user.name;
            document.getElementById('profileEmail').textContent = user.email;
            document.getElementById('profileBadge').textContent = user.firstGen ? '🎓 First Generation' : '🎓 Student';
            
            // Stats
            const garden = JSON.parse(localStorage.getItem('sharedDigitalGarden') || '[]');
            const flowers = garden.filter(f => f.creatorName === user.name || f.creatorName === user.email).length;
            document.getElementById('profileFlowers').textContent = flowers;
            
            const grove = JSON.parse(localStorage.getItem('groveMessages') || '[]');
            const messages = grove.filter(m => m.sender === user.name || m.sender === user.email).length;
            document.getElementById('profileMessages').textContent = messages;
            
            const days = Math.floor((Date.now() - new Date(user.joined || Date.now())) / 86400000);
            document.getElementById('profileDays').textContent = days || 1;
            
            // Avatar based on flower
            const emojis = ['🌱', '🌸', '🌻', '🌺', '🌷', '🌼', '🌹', '🌿'];
            document.getElementById('profileAvatar').textContent = emojis[Math.floor(Math.random() * emojis.length)];
        }
        
        // Edit profile
        document.getElementById('editProfileBtn').addEventListener('click', function() {
            const newName = prompt('✏️ Update your name:', document.getElementById('profileName').textContent);
            if (newName && newName.trim()) {
                const user = getCurrentUser();
                user.name = newName.trim();
                localStorage.setItem('ctuUser', JSON.stringify(user));
                
                // Update in users list
                const users = JSON.parse(localStorage.getItem('ctuUsers') || '[]');
                const idx = users.findIndex(u => u.id === user.id);
                if (idx !== -1) {
                    users[idx].name = user.name;
                    localStorage.setItem('ctuUsers', JSON.stringify(users));
                }
                
                loadProfile();
                showNotification('✅ Profile updated!', 'success');
            }
        });
        
        // Logout
        document.getElementById('logoutBtn').addEventListener('click', function() {
            if (confirm('🚪 Logout?')) {
                localStorage.removeItem('ctuUser');
                window.location.href = 'index.html';
            }
        });
        
        loadProfile();
    </script>
</body>
</html>

// ----- EMAIL NOTIFICATIONS -----
function sendEmailNotification(type, data) {
    // This uses a free email service (formspree.io or similar)
    // Sign up at https://formspree.io/ and get your endpoint
    
    const endpoint = 'https://formspree.io/f/YOUR_FORM_ID'; // Replace with your formspree ID
    
    const payload = {
        type: type,
        data: data,
        timestamp: new Date().toISOString()
    };
    
    fetch(endpoint, {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify(payload)
    }).catch(err => console.log('Email notification skipped:', err));
}

// Call when new flower is planted
function notifyNewFlower(flower) {
    const user = getCurrentUser();
    if (user) {
        sendEmailNotification('new_flower', {
            user: user.name,
            email: user.email,
            flower: flower.centerWord,
            petals: flower.petals.length
        });
    }
}

// Call when new message is sent
function notifyNewMessage(message) {
    const user = getCurrentUser();
    if (user) {
        sendEmailNotification('new_message', {
            user: user.name,
            email: user.email,
            message: message
        });
    }
}

// Call when new member joins
function notifyNewMember(user) {
    sendEmailNotification('new_member', {
        name: user.name,
        email: user.email,
        year: user.year,
        firstGen: user.firstGen
    });
}

ctu-ground/
├── index.html              (Main hub)
├── garden.html             (Digital Garden)
├── grove.html              (Community Chat)
├── playground.html         (Activities)
├── profile.html            (User profile)
├── admin.html              (Admin dashboard)
├── style.css               (Global styles)
├── script.js               (Global scripts)
├── auth.js                 (Authentication)
├── garden.js               (Garden logic)
├── grove.js                (Chat logic)
├── playground.js           (Activities logic)
├── firebase.js             (Firebase config)
├── sw.js                   (Service Worker)
├── manifest.json           (PWA manifest)
├── firebase-messaging-sw.js (Push notifications)
└── README.md

/* ============================================
   CTU GROUND - Firebase Configuration
   ============================================ */

// Replace with your Firebase config from Firebase Console
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT.firebaseapp.com",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_PROJECT.appspot.com",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID",
    databaseURL: "https://YOUR_PROJECT.firebaseio.com"
};

// Initialize Firebase
firebase.initializeApp(firebaseConfig);

// Services
const auth = firebase.auth();
const db = firebase.firestore();
const storage = firebase.storage();
const messaging = firebase.messaging();

// Enable offline persistence
db.enablePersistence()
    .catch(err => console.warn('Firestore persistence:', err));

// ----- AUTH STATE -----
let currentUser = null;

auth.onAuthStateChanged(user => {
    if (user) {
        currentUser = user;
        // Load user profile from Firestore
        db.collection('users').doc(user.uid).get()
            .then(doc => {
                if (doc.exists) {
                    const userData = doc.data();
                    userData.uid = user.uid;
                    localStorage.setItem('ctuUser', JSON.stringify(userData));
                    updateUI(userData);
                }
            });
    } else {
        currentUser = null;
        localStorage.removeItem('ctuUser');
        updateUI(null);
    }
});

// ----- FUNCTIONS -----
function getCurrentUser() {
    return currentUser;
}

function updateUI(user) {
    // Update UI elements across pages
    document.querySelectorAll('.user-display').forEach(el => {
        el.textContent = user ? `🌱 ${user.name}` : '';
    });
    document.querySelectorAll('.login-btn, .logout-btn').forEach(el => {
        el.style.display = user ? 'none' : 'inline';
    });
}

// Export for other files
window.getCurrentUser = getCurrentUser;
window.firebase = firebase;
window.db = db;
window.auth = auth;
window.storage = storage;
window.messaging = messaging;

/* ============================================
   CTU GROUND - Firebase Authentication
   ============================================ */

// ----- REGISTER -----
async function registerUser(email, password, name, year, firstGen) {
    try {
        const userCredential = await auth.createUserWithEmailAndPassword(email, password);
        const user = userCredential.user;
        
        // Save user data to Firestore
        await db.collection('users').doc(user.uid).set({
            name: name,
            email: email,
            year: year,
            firstGen: firstGen || true,
            joined: firebase.firestore.FieldValue.serverTimestamp(),
            flowers: 0,
            messages: 0,
            badge: '🌱 First-Gen Starter',
            notifications: true
        });
        
        // Send welcome notification
        sendNotificationToUser(user.uid, {
            title: '🌱 Welcome to CTU Ground!',
            body: `Welcome ${name}! Plant your first flower and join the community.`,
            icon: '🌻'
        });
        
        // Store in localStorage for offline
        localStorage.setItem('ctuUser', JSON.stringify({ name, email, year, firstGen, uid: user.uid }));
        
        return { success: true, user };
    } catch (error) {
        return { success: false, error: error.message };
    }
}

// ----- LOGIN -----
async function loginUser(email, password) {
    try {
        const userCredential = await auth.signInWithEmailAndPassword(email, password);
        return { success: true, user: userCredential.user };
    } catch (error) {
        return { success: false, error: error.message };
    }
}

// ----- LOGOUT -----
async function logoutUser() {
    try {
        await auth.signOut();
        localStorage.removeItem('ctuUser');
        return { success: true };
    } catch (error) {
        return { success: false, error: error.message };
    }
}

// ----- RESET PASSWORD -----
async function resetPassword(email) {
    try {
        await auth.sendPasswordResetEmail(email);
        return { success: true };
    } catch (error) {
        return { success: false, error: error.message };
    }
}

// ----- UPDATE PROFILE -----
async function updateUserProfile(uid, data) {
    try {
        await db.collection('users').doc(uid).update(data);
        return { success: true };
    } catch (error) {
        return { success: false, error: error.message };
    }
}

// ----- GET USER DATA -----
async function getUserData(uid) {
    try {
        const doc = await db.collection('users').doc(uid).get();
        if (doc.exists) {
            return { success: true, data: doc.data() };
        }
        return { success: false, error: 'User not found' };
    } catch (error) {
        return { success: false, error: error.message };
    }
}

// ----- GET ALL USERS (Admin) -----
async function getAllUsers() {
    try {
        const snapshot = await db.collection('users').get();
        const users = [];
        snapshot.forEach(doc => {
            users.push({ id: doc.id, ...doc.data() });
        });
        return { success: true, users };
    } catch (error) {
        return { success: false, error: error.message };
    }
}

// Export
window.registerUser = registerUser;
window.loginUser = loginUser;
window.logoutUser = logoutUser;
window.resetPassword = resetPassword;
window.updateUserProfile = updateUserProfile;
window.getUserData = getUserData;
window.getAllUsers = getAllUsers;

/* ============================================
   CTU GROUND - Push Notification Service Worker
   ============================================ */

importScripts('https://www.gstatic.com/firebasejs/9.x.x/firebase-app-compat.js');
importScripts('https://www.gstatic.com/firebasejs/9.x.x/firebase-messaging-compat.js');

firebase.initializeApp({
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT.firebaseapp.com",
    projectId: "YOUR_PROJECT_ID",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID"
});

const messaging = firebase.messaging();

// Handle background messages
messaging.onBackgroundMessage((payload) => {
    const notificationTitle = payload.notification.title;
    const notificationOptions = {
        body: payload.notification.body,
        icon: '/icon-192.png',
        badge: '/icon-192.png',
        data: payload.data,
        requireInteraction: true
    };

    self.registration.showNotification(notificationTitle, notificationOptions);
});

// Handle notification click
self.addEventListener('notificationclick', (event) => {
    event.notification.close();

    const url = event.notification.data?.url || '/';
    event.waitUntil(
        clients.matchAll({ type: 'window' }).then((clientList) => {
            for (const client of clientList) {
                if (client.url === url && 'focus' in client) {
                    return client.focus();
                }
            }
            if (clients.openWindow) {
                return clients.openWindow(url);
            }
        })
    );
});

/* ============================================
   CTU GROUND - Notification System
   ============================================ */

// ----- REQUEST PERMISSION -----
async function requestNotificationPermission() {
    if (!('Notification' in window)) {
        console.log('❌ This browser does not support notifications');
        return false;
    }
    
    if (Notification.permission === 'granted') {
        return true;
    }
    
    if (Notification.permission === 'denied') {
        console.log('❌ Notifications denied');
        return false;
    }
    
    const permission = await Notification.requestPermission();
    return permission === 'granted';
}

// ----- SEND PUSH NOTIFICATION -----
async function sendPushNotification(token, title, body, data = {}) {
    if (!token) return;
    
    const message = {
        token: token,
        notification: {
            title: title,
            body: body,
            icon: '/icon-192.png',
            badge: '/icon-192.png',
            click_action: 'https://ctuground.com'
        },
        data: data
    };
    
    try {
        // Send via Firebase Cloud Messaging
        const response = await fetch('https://fcm.googleapis.com/v1/projects/YOUR_PROJECT/messages:send', {
            method: 'POST',
            headers: {
                'Authorization': 'Bearer YOUR_ACCESS_TOKEN',
                'Content-Type': 'application/json'
            },
            body: JSON.stringify({ message })
        });
        return await response.json();
    } catch (error) {
        console.error('Push notification error:', error);
        return null;
    }
}

// ----- SEND TO SPECIFIC USER -----
async function sendNotificationToUser(uid, notification) {
    try {
        // Get user's FCM token from Firestore
        const doc = await db.collection('users').doc(uid).get();
        if (!doc.exists) return;
        
        const userData = doc.data();
        const token = userData.fcmToken;
        if (!token) return;
        
        await sendPushNotification(token, notification.title, notification.body, notification.data);
    } catch (error) {
        console.error('Send notification error:', error);
    }
}

// ----- SEND TO ALL USERS (Admin) -----
async function sendNotificationToAll(title, body, data = {}) {
    try {
        const snapshot = await db.collection('users').get();
        const tokens = [];
        snapshot.forEach(doc => {
            const token = doc.data().fcmToken;
            if (token) tokens.push(token);
        });
        
        // Send in batches
        const batchSize = 500;
        for (let i = 0; i < tokens.length; i += batchSize) {
            const batch = tokens.slice(i, i + batchSize);
            // Send batch via Firebase Cloud Messaging
            console.log(`📨 Sending to batch ${i / batchSize + 1}: ${batch.length} users`);
        }
    } catch (error) {
        console.error('Send to all error:', error);
    }
}

// ----- REGISTER FCM TOKEN -----
async function registerFCMToken() {
    if (!('serviceWorker' in navigator)) return;
    
    try {
        const registration = await navigator.serviceWorker.register('/firebase-messaging-sw.js');
        const token = await messaging.getToken({
            vapidKey: 'YOUR_VAPID_KEY',
            serviceWorkerRegistration: registration
        });
        
        if (token) {
            // Save token to Firestore
            const user = getCurrentUser();
            if (user && user.uid) {
                await db.collection('users').doc(user.uid).update({
                    fcmToken: token
                });
            }
            console.log('✅ FCM Token registered:', token);
            return token;
        }
    } catch (error) {
        console.error('FCM registration error:', error);
    }
    return null;
}

// ----- NOTIFICATION TRIGGERS -----
// When a new flower is planted
function notifyNewFlower(flower) {
    const user = getCurrentUser();
    if (!user) return;
    
    // Notify all users except planter
    const notification = {
        title: `🌻 New Flower Planted!`,
        body: `${user.name} planted a ${flower.centerWord} flower in the garden.`,
        data: { url: '/garden.html', flowerId: flower.id }
    };
    
    sendNotificationToAll(notification.title, notification.body, notification.data);
}

// When a new message is sent
function notifyNewMessage(message, room) {
    const user = getCurrentUser();
    if (!user) return;
    
    const notification = {
        title: `💬 New Message in ${room}`,
        body: `${user.name}: ${message.substring(0, 50)}${message.length > 50 ? '...' : ''}`,
        data: { url: '/grove.html' }
    };
    
    sendNotificationToAll(notification.title, notification.body, notification.data);
}

// When a new member joins
function notifyNewMember(userData) {
    const notification = {
        title: `🌱 Welcome to CTU Ground!`,
        body: `Please welcome ${userData.name}, our new first-gen student!`,
        data: { url: '/index.html' }
    };
    
    sendNotificationToAll(notification.title, notification.body, notification.data);
}

// Export
window.requestNotificationPermission = requestNotificationPermission;
window.registerFCMToken = registerFCMToken;
window.notifyNewFlower = notifyNewFlower;
window.notifyNewMessage = notifyNewMessage;
window.notifyNewMember = notifyNewMember;
window.sendNotificationToAll = sendNotificationToAll;

// Initialize on load
document.addEventListener('DOMContentLoaded', async () => {
    const user = getCurrentUser();
    if (user && user.uid) {
        await registerFCMToken();
        const permission = await requestNotificationPermission();
        if (!permission) {
            console.log('🔕 Notifications not enabled');
        }
    }
});

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>🏛️ Admin · CTU Ground</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <nav class="main-nav">
        <div class="nav-container">
            <div class="nav-brand">
                <span class="brand-icon">🏛️</span>
                <span class="brand-text">CTU Ground</span>
                <span class="brand-sub">Admin</span>
            </div>
            <div class="nav-links">
                <a href="index.html">🏠 Home</a>
                <a href="garden.html">🌻 Garden</a>
                <a href="grove.html">💬 Grove</a>
                <a href="playground.html">🎮 Playground</a>
                <a href="admin.html" class="active">⚙️ Admin</a>
            </div>
            <button id="logoutBtn" class="btn-logout">🚪 Logout</button>
        </div>
    </nav>

    <main class="admin-main">
        <h1>⚙️ Admin Dashboard</h1>
        
        <!-- Stats -->
        <section class="admin-stats">
            <div class="stat-card">
                <span class="stat-number" id="adminUsers">0</span>
                <span class="stat-label">👥 Total Members</span>
            </div>
            <div class="stat-card">
                <span class="stat-number" id="adminFlowers">0</span>
                <span class="stat-label">🌻 Total Flowers</span>
            </div>
            <div class="stat-card">
                <span class="stat-number" id="adminMessages">0</span>
                <span class="stat-label">💬 Total Messages</span>
            </div>
            <div class="stat-card">
                <span class="stat-number" id="adminPetals">0</span>
                <span class="stat-label">📝 Total Petals</span>
            </div>
        </section>

        <!-- Admin Actions -->
        <section class="admin-actions">
            <h2>🔧 Admin Actions</h2>
            <div class="action-grid">
                <div class="action-card">
                    <h3>📢 Send Announcement</h3>
                    <input type="text" id="adminAnnouncement" placeholder="Announcement text..." />
                    <button id="sendAnnouncementBtn">📤 Send to All</button>
                </div>
                <div class="action-card">
                    <h3>🔔 Push Notification</h3>
                    <input type="text" id="notifTitle" placeholder="Title" />
                    <input type="text" id="notifBody" placeholder="Message body" />
                    <button id="sendPushBtn">📨 Send Push</button>
                </div>
                <div class="action-card">
                    <h3>🌱 Garden Management</h3>
                    <button id="adminResetGarden">🗑️ Reset Garden</button>
                    <button id="adminExportGarden">📸 Export Garden Data</button>
                </div>
                <div class="action-card">
                    <h3>👥 Member Management</h3>
                    <button id="adminViewMembers">👥 View All Members</button>
                    <button id="adminExportMembers">📄 Export Members</button>
                </div>
            </div>
        </section>

        <!-- Member List -->
        <section class="admin-members">
            <h2>👥 Members</h2>
            <div id="memberList" class="member-list">
                <p>Loading members...</p>
            </div>
        </section>
    </main>

    <script src="firebase.js"></script>
    <script src="auth.js"></script>
    <script>
        // Load admin data
        async function loadAdminData() {
            // Check if user is admin
            const user = getCurrentUser();
            if (!user || user.email !== 'admin@ctuground.com') {
                window.location.href = 'index.html';
                return;
            }

            // Load stats
            const users = await getAllUsers();
            const garden = JSON.parse(localStorage.getItem('sharedDigitalGarden') || '[]');
            const grove = JSON.parse(localStorage.getItem('groveMessages') || '[]');
            
            document.getElementById('adminUsers').textContent = users.users?.length || 0;
            document.getElementById('adminFlowers').textContent = garden.length;
            document.getElementById('adminMessages').textContent = grove.length;
            document.getElementById('adminPetals').textContent = garden.reduce((sum, f) => sum + f.petals.length, 0);
            
            // Load member list
            renderMembers(users.users || []);
        }

        function renderMembers(users) {
            const container = document.getElementById('memberList');
            if (users.length === 0) {
                container.innerHTML = '<p>No members yet.</p>';
                return;
            }
            
            container.innerHTML = users.map(user => `
                <div class="member-item">
                    <span class="member-name">🌱 ${user.name}</span>
                    <span class="member-email">${user.email}</span>
                    <span class="member-year">${user.year || 'Student'}</span>
                    <span class="member-badge">${user.firstGen ? '🎓 First-Gen' : '🎓 Student'}</span>
                    <button class="member-remove" data-uid="${user.id}">✕</button>
                </div>
            `).join('');
        }

        // Send announcement
        document.getElementById('sendAnnouncementBtn').addEventListener('click', async () => {
            const text = document.getElementById('adminAnnouncement').value.trim();
            if (!text) return;
            
            // Save to announcements
            const list = document.getElementById('announcementList');
            const item = document.createElement('div');
            item.className = 'announcement-item';
            item.innerHTML = `
                <span class="announcement-date">Admin</span>
                <p>${text}</p>
            `;
            list?.prepend(item);
            
            // Send push notification
            await sendNotificationToAll('📢 Announcement', text);
            document.getElementById('adminAnnouncement').value = '';
            showNotification('✅ Announcement sent!', 'success');
        });

        // Send push notification
        document.getElementById('sendPushBtn').addEventListener('click', async () => {
            const title = document.getElementById('notifTitle').value.trim();
            const body = document.getElementById('notifBody').value.trim();
            if (!title || !body) return;
            
            await sendNotificationToAll(title, body);
            document.getElementById('notifTitle').value = '';
            document.getElementById('notifBody').value = '';
            showNotification('✅ Push notification sent!', 'success');
        });

        // Reset garden
        document.getElementById('adminResetGarden').addEventListener('click', () => {
            if (confirm('⚠️ Reset the entire garden? This cannot be undone!')) {
                localStorage.setItem('sharedDigitalGarden', '[]');
                showNotification('✅ Garden reset!', 'success');
                location.reload();
            }
        });

        // Export garden
        document.getElementById('adminExportGarden').addEventListener('click', () => {
            const garden = JSON.parse(localStorage.getItem('sharedDigitalGarden') || '[]');
            const blob = new Blob([JSON.stringify(garden, null, 2)], { type: 'application/json' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = `garden-export-${Date.now()}.json`;
            a.click();
            URL.revokeObjectURL(url);
        });

        // View members
        document.getElementById('adminViewMembers').addEventListener('click', () => {
            document.querySelector('.admin-members').scrollIntoView({ behavior: 'smooth' });
        });

        // Export members
        document.getElementById('adminExportMembers').addEventListener('click', async () => {
            const users = await getAllUsers();
            const blob = new Blob([JSON.stringify(users.users, null, 2)], { type: 'application/json' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = `members-export-${Date.now()}.json`;
            a.click();
            URL.revokeObjectURL(url);
        });

        // Initialize
        loadAdminData();
    </script>
</body>
</html>

/* ----- MORE THEMES ----- */
body.theme-lavender { --primary: #6c3483; --primary-light: #8e44ad; --secondary: #d7bde2; --background: #f4ecf7; }
body.theme-forest { --primary: #1e8449; --primary-light: #27ae60; --secondary: #a9dfbf; --background: #eafaf1; }
body.theme-gold { --primary: #b7950b; --primary-light: #d4ac0d; --secondary: #f9e79f; --background: #fef9e7; }
body.theme-coral { --primary: #cd6155; --primary-light: #e74c3c; --secondary: #f5b7b1; --background: #fdedec; }
body.theme-mint { --primary: #1abc9c; --primary-light: #48c9b0; --secondary: #a3e4d7; --background: #eafaf1; }

/* Theme buttons for new themes */
.theme-btn[data-theme="lavender"] { background: #6c3483; }
.theme-btn[data-theme="forest"] { background: #1e8449; }
.theme-btn[data-theme="gold"] { background: #b7950b; }
.theme-btn[data-theme="coral"] { background: #cd6155; }
.theme-btn[data-theme="mint"] { background: #1abc9c; }

<button class="theme-btn" data-theme="lavender" style="background:#6c3483;">💜 Lavender</button>
<button class="theme-btn" data-theme="forest" style="background:#1e8449;">🌲 Forest</button>
<button class="theme-btn" data-theme="gold" style="background:#b7950b;">✨ Gold</button>
<button class="theme-btn" data-theme="coral" style="background:#cd6155;">🪸 Coral</button>
<button class="theme-btn" data-theme="mint" style="background:#1abc9c;">🌿 Mint</button>

rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /users/{userId} {
      allow read, write: if request.auth != null && request.auth.uid == userId;
      allow read: if request.auth != null;
    }
    match /flowers/{flowerId} {
      allow read, write: if request.auth != null;
    }
    match /messages/{messageId} {
      allow read, write: if request.auth != null;
    }
  }
}

git add .
git commit -m "🚀 CTU Ground with Firebase & Push Notifications"
git push origin main

npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy

