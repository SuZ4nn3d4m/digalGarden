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