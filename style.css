/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #ff6b35;
    --secondary-color: #f7931e;
    --dark-bg: #0a0e27;
    --darker-bg: #050813;
    --light-text: #ffffff;
    --gray-text: #a8b2d1;
    --accent-blue: #00d4ff;
    --accent-purple: #8b5cf6;
    --gradient-1: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --gradient-2: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    --gradient-3: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    --gradient-4: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
}

body {
    font-family: 'Poppins', sans-serif;
    background: var(--dark-bg);
    color: var(--light-text);
    overflow-x: hidden;
    line-height: 1.6;
}

.container {
    max-width: 1400px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Navigation */
.navbar {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(10, 14, 39, 0.95);
    backdrop-filter: blur(10px);
    z-index: 1000;
    padding: 15px 0;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    transition: all 0.3s ease;
}

.navbar .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    display: flex;
    align-items: center;
    gap: 10px;
    font-size: 24px;
    font-weight: 800;
    color: var(--light-text);
}

.logo i {
    color: var(--primary-color);
    font-size: 28px;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 40px;
}

.nav-links a {
    color: var(--light-text);
    text-decoration: none;
    font-weight: 500;
    transition: all 0.3s ease;
    position: relative;
}

.nav-links a::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 0;
    height: 2px;
    background: var(--gradient-3);
    transition: width 0.3s ease;
}

.nav-links a:hover::after {
    width: 100%;
}

.nav-links a:hover {
    color: var(--accent-blue);
}

.book-btn {
    background: var(--gradient-3);
    color: white;
    border: none;
    padding: 12px 28px;
    border-radius: 50px;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.3s ease;
    font-size: 15px;
}

.book-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 30px rgba(0, 212, 255, 0.4);
}

.hamburger {
    display: none;
    flex-direction: column;
    gap: 5px;
    cursor: pointer;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background: white;
    border-radius: 5px;
    transition: all 0.3s ease;
}

/* Hero Section */
.hero {
    min-height: 100vh;
    height: auto;
    background: linear-gradient(135deg, rgba(10, 14, 39, 0.9), rgba(102, 126, 234, 0.4)),
                url('https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?w=1600&h=900&fit=crop') center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    position: relative;
    overflow: hidden;
    padding: 120px 20px 80px;
}

.hero-overlay {
    position: absolute;
    inset: 0;
    background: radial-gradient(circle at 50% 50%, rgba(102, 126, 234, 0.2), transparent 70%);
}

.hero-content {
    position: relative;
    z-index: 2;
    max-width: 900px;
    padding: 0 20px;
}

.hero-title {
    font-size: clamp(36px, 8vw, 72px);
    font-weight: 800;
    margin-bottom: 20px;
    animation: fadeInUp 1s ease;
    line-height: 1.2;
}

.gradient-text {
    background: var(--gradient-3);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.hero-subtitle {
    font-size: clamp(18px, 4vw, 28px);
    color: var(--gray-text);
    margin-bottom: 15px;
    animation: fadeInUp 1s ease 0.2s backwards;
    line-height: 1.4;
}

.hero-description {
    font-size: clamp(14px, 2.5vw, 18px);
    color: var(--gray-text);
    margin-bottom: 40px;
    line-height: 1.8;
    animation: fadeInUp 1s ease 0.4s backwards;
}

.hero-buttons {
    display: flex;
    gap: 20px;
    justify-content: center;
    animation: fadeInUp 1s ease 0.6s backwards;
    flex-wrap: wrap;
}

.cta-btn {
    padding: 16px 35px;
    border: none;
    border-radius: 50px;
    font-size: 15px;
    font-weight: 600;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 10px;
    transition: all 0.3s ease;
}

.cta-btn.primary {
    background: var(--gradient-4);
    color: white;
}

.cta-btn.secondary {
    background: transparent;
    border: 2px solid white;
    color: white;
}

.cta-btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 15px 40px rgba(255, 107, 53, 0.4);
}

.scroll-indicator {
    position: absolute;
    bottom: 30px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    color: var(--gray-text);
    animation: bounce 2s infinite;
}

@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes bounce {
    0%, 100% { transform: translate(-50%, 0); }
    50% { transform: translate(-50%, 10px); }
}

/* Section Styles */
section {
    padding: 80px 0;
}

.section-header {
    text-align: center;
    margin-bottom: 60px;
}

.section-tag {
    display: inline-block;
    background: var(--gradient-3);
    color: white;
    padding: 8px 20px;
    border-radius: 50px;
    font-size: 13px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin-bottom: 15px;
}

.section-header h2 {
    font-size: clamp(32px, 6vw, 48px);
    font-weight: 800;
    margin-bottom: 15px;
    background: var(--gradient-4);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.section-header p {
    font-size: clamp(14px, 2.5vw, 18px);
    color: var(--gray-text);
}

/* About Section */
.about {
    background: var(--darker-bg);
}

.about-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: center;
}

.about-text h3 {
    font-size: clamp(24px, 4vw, 36px);
    margin-bottom: 20px;
    color: var(--light-text);
}

.about-text p {
    color: var(--gray-text);
    margin-bottom: 20px;
    font-size: clamp(14px, 2vw, 16px);
    line-height: 1.8;
}

.about-features {
    margin-top: 40px;
    display: flex;
    flex-direction: column;
    gap: 25px;
}

.feature-item {
    display: flex;
    gap: 20px;
    padding: 20px;
    background: rgba(255, 255, 255, 0.03);
    border-radius: 15px;
    border: 1px solid rgba(255, 255, 255, 0.1);
    transition: all 0.3s ease;
}

.feature-item:hover {
    background: rgba(255, 255, 255, 0.05);
    transform: translateX(10px);
}

.feature-item i {
    font-size: 32px;
    color: var(--primary-color);
    flex-shrink: 0;
}

.feature-item h4 {
    font-size: clamp(16px, 2.5vw, 20px);
    margin-bottom: 5px;
}

.feature-item p {
    font-size: clamp(12px, 1.8vw, 14px);
    margin: 0;
}

.about-image {
    border-radius: 20px;
    overflow: hidden;
    box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
}

.about-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
}

.about-image:hover img {
    transform: scale(1.1);
}

/* Cars Section */
.cars-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
}

.car-card {
    background: rgba(255, 255, 255, 0.03);
    border-radius: 20px;
    overflow: hidden;
    border: 1px solid rgba(255, 255, 255, 0.1);
    transition: all 0.4s ease;
}

.car-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 60px rgba(102, 126, 234, 0.3);
    border-color: var(--accent-blue);
}

.car-image {
    position: relative;
    height: 220px;
    overflow: hidden;
}

.car-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
}

.car-card:hover .car-image img {
    transform: scale(1.15);
}

.car-badge {
    position: absolute;
    top: 15px;
    right: 15px;
    background: var(--gradient-4);
    color: white;
    padding: 6px 16px;
    border-radius: 50px;
    font-size: 11px;
    font-weight: 600;
    text-transform: uppercase;
}

.car-badge.exclusive {
    background: var(--gradient-1);
}

.car-info {
    padding: 25px;
}

.car-info h3 {
    font-size: clamp(20px, 3vw, 28px);
    margin-bottom: 10px;
    color: var(--light-text);
}

.car-desc {
    color: var(--gray-text);
    margin-bottom: 20px;
    font-size: clamp(12px, 1.8vw, 14px);
}

.car-specs {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    margin-bottom: 25px;
}

.car-specs span {
    display: flex;
    align-items: center;
    gap: 6px;
    font-size: clamp(11px, 1.5vw, 13px);
    color: var(--gray-text);
    background: rgba(255, 255, 255, 0.05);
    padding: 6px 12px;
    border-radius: 50px;
}

.car-specs i {
    color: var(--accent-blue);
}

.car-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 20px;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
    gap: 15px;
    flex-wrap: wrap;
}

.price {
    display: flex;
    flex-direction: column;
}

.price-label {
    font-size: 11px;
    color: var(--gray-text);
    text-transform: uppercase;
}

.price-value {
    font-size: clamp(24px, 4vw, 32px);
    font-weight: 800;
    background: var(--gradient-3);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.view-btn {
    background: var(--gradient-3);
    color: white;
    border: none;
    padding: 12px 24px;
    border-radius: 50px;
    font-weight: 600;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 10px;
    transition: all 0.3s ease;
    font-size: 14px;
}

.view-btn:hover {
    transform: translateX(5px);
    box-shadow: 0 10px 30px rgba(0, 212, 255, 0.4);
}

/* Services Section */
.services {
    background: var(--darker-bg);
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 25px;
}

.service-card {
    background: rgba(255, 255, 255, 0.03);
    padding: 35px 25px;
    border-radius: 20px;
    border: 1px solid rgba(255, 255, 255, 0.1);
    text-align: center;
    transition: all 0.4s ease;
}

.service-card:hover {
    background: rgba(255, 255, 255, 0.05);
    transform: translateY(-10px);
    border-color: var(--accent-blue);
}

.service-icon {
    width: 70px;
    height: 70px;
    margin: 0 auto 20px;
    background: var(--gradient-3);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 32px;
    transition: all 0.3s ease;
}

.service-card:hover .service-icon {
    transform: rotateY(360deg);
}

.service-card h3 {
    font-size: clamp(18px, 2.5vw, 24px);
    margin-bottom: 15px;
    color: var(--light-text);
}

.service-card p {
    color: var(--gray-text);
    line-height: 1.8;
    font-size: clamp(13px, 1.8vw, 15px);
}

/* Contact Section */
.contact-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
}

.contact-info {
    display: grid;
    gap: 20px;
}

.info-card {
    background: rgba(255, 255, 255, 0.03);
    padding: 25px;
    border-radius: 15px;
    border: 1px solid rgba(255, 255, 255, 0.1);
    transition: all 0.3s ease;
}

.info-card:hover {
    background: rgba(255, 255, 255, 0.05);
    transform: translateX(10px);
}

.info-card i {
    font-size: 28px;
    color: var(--primary-color);
    margin-bottom: 15px;
}

.info-card h3 {
    font-size: clamp(16px, 2.5vw, 20px);
    margin-bottom: 10px;
}

.info-card p {
    color: var(--gray-text);
    line-height: 1.8;
    font-size: clamp(13px, 1.8vw, 15px);
}

.whatsapp-btn {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    background: #25d366;
    color: white;
    padding: 10px 20px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: 600;
    margin-top: 10px;
    transition: all 0.3s ease;
    font-size: 14px;
}

.whatsapp-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 30px rgba(37, 211, 102, 0.4);
}

.contact-form {
    background: rgba(255, 255, 255, 0.03);
    padding: 35px;
    border-radius: 20px;
    border: 1px solid rgba(255, 255, 255, 0.1);
}

.contact-form h3 {
    font-size: clamp(20px, 3vw, 28px);
    margin-bottom: 25px;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 14px;
    margin-bottom: 18px;
    background: rgba(255, 255, 255, 0.05);
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 10px;
    color: white;
    font-family: 'Poppins', sans-serif;
    font-size: 15px;
    transition: all 0.3s ease;
}

.contact-form input:focus,
.contact-form textarea:focus {
    outline: none;
    border-color: var(--accent-blue);
    background: rgba(255, 255, 255, 0.08);
}

.contact-form input::placeholder,
.contact-form textarea::placeholder {
    color: rgba(168, 178, 209, 0.6);
}

.submit-btn {
    width: 100%;
    background: var(--gradient-4);
    color: white;
    border: none;
    padding: 15px;
    border-radius: 50px;
    font-size: 15px;
    font-weight: 600;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    transition: all 0.3s ease;
}

.submit-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 15px 40px rgba(250, 112, 154, 0.4);
}

/* Modal */
.modal {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.9);
    z-index: 2000;
    align-items: center;
    justify-content: center;
    padding: 20px;
}

.modal-content {
    background: var(--dark-bg);
    padding: 40px 30px;
    border-radius: 20px;
    max-width: 600px;
    width: 100%;
    max-height: 90vh;
    overflow-y: auto;
    position: relative;
    border: 1px solid rgba(255, 255, 255, 0.1);
}

.close-modal {
    position: absolute;
    top: 15px;
    right: 20px;
    font-size: 32px;
    cursor: pointer;
    color: var(--gray-text);
    transition: all 0.3s ease;
}

.close-modal:hover {
    color: var(--primary-color);
    transform: rotate(90deg);
}

.modal-content h2 {
    font-size: clamp(24px, 4vw, 36px);
    margin-bottom: 10px;
    background: var(--gradient-3);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.modal-subtitle {
    color: var(--gray-text);
    margin-bottom: 30px;
    font-size: clamp(13px, 1.8vw, 15px);
}

.form-group {
    margin-bottom: 22px;
}

.form-group label {
    display: block;
    margin-bottom: 8px;
    font-weight: 600;
    color: var(--light-text);
    font-size: clamp(13px, 1.8vw, 15px);
}

.form-group input,
.form-group select,
.form-group textarea {
    width: 100%;
    padding: 14px;
    background: rgba(255, 255, 255, 0.05);
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 10px;
    color: white;
    font-family: 'Poppins', sans-serif;
    font-size: 15px;
    transition: all 0.3s ease;
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--accent-blue);
    background: rgba(255, 255, 255, 0.08);
}

.form-group select {
    cursor: pointer;
}

.form-group input::placeholder,
.form-group textarea::placeholder {
    color: rgba(168, 178, 209, 0.6);
}

/* Footer */
.footer {
    background: var(--darker-bg);
    padding: 50px 0 20px;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
}

.footer-content {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr;
    gap: 50px;
    margin-bottom: 35px;
}

.footer-logo {
    display: flex;
    align-items: center;
    gap: 10px;
    font-size: clamp(22px, 3vw, 28px);
    font-weight: 800;
    margin-bottom: 15px;
}

.footer-logo i {
    color: var(--primary-color);
    font-size: clamp(26px, 3.5vw, 32px);
}

.footer-section p {
    color: var(--gray-text);
    margin-bottom: 20px;
    font-size: clamp(13px, 1.8vw, 15px);
}

.social-links {
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
}

.social-links a {
    width: 40px;
    height: 40px;
    background: rgba(255, 255, 255, 0.05);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    transition: all 0.3s ease;
}

.social-links a:hover {
    background: var(--gradient-3);
    transform: translateY(-3px);
}

.footer-section h4 {
    font-size: clamp(16px, 2.5vw, 20px);
    margin-bottom: 18px;
}

.footer-section ul {
    list-style: none;
}

.footer-section ul li {
    margin-bottom: 10px;
}

.footer-section ul li a {
    color: var(--gray-text);
    text-decoration: none;
    transition: all 0.3s ease;
    font-size: clamp(13px, 1.8vw, 15px);
}

.footer-section ul li a:hover {
    color: var(--accent-blue);
    padding-left: 5px;
}

.footer-section ul li i {
    color: var(--primary-color);
    margin-right: 10px;
}

.footer-bottom {
    text-align: center;
    padding-top: 25px;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
    color: var(--gray-text);
    font-size: clamp(12px, 1.8vw, 14px);
}

.footer-bottom i {
    color: #e74c3c;
}

/* Responsive Design */

/* Tablet Landscape and Small Laptops */
@media (max-width: 1024px) {
    .container {
        padding: 0 30px;
    }
    
    .about-content,
    .contact-content {
        grid-template-columns: 1fr;
        gap: 40px;
    }
    
    .footer-content {
        grid-template-columns: 1fr 1fr;
        gap: 40px;
    }
    
    .cars-grid {
        grid-template-columns: repeat(2, 1fr);
    }
    
    .services-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

/* Tablet Portrait */
@media (max-width: 768px) {
    .container {
        padding: 0 20px;
    }
    
    section {
        padding: 60px 0;
    }
    
    /* Navigation */
    .nav-links {
        display: none;
    }
    
    .book-btn {
        padding: 10px 20px;
        font-size: 14px;
    }
    
    .hamburger {
        display: flex;
    }
    
    /* Hero */
    .hero {
        padding: 100px 20px 60px;
    }
    
    .hero-buttons {
        flex-direction: column;
        width: 100%;
    }
    
    .cta-btn {
        width: 100%;
        justify-content: center;
        padding: 14px 30px;
    }
    
    .scroll-indicator {
        display: none;
    }
    
    /* Section Headers */
    .section-header {
        margin-bottom: 40px;
    }
    
    /* Cars Grid */
    .cars-grid {
        grid-template-columns: 1fr;
        gap: 25px;
    }
    
    .car-image {
        height: 200px;
    }
    
    /* Services Grid */
    .services-grid {
        grid-template-columns: 1fr;
        gap: 20px;
    }
    
    /* Contact */
    .contact-content {
        gap: 30px;
    }
    
    .contact-form {
        padding: 25px 20px;
    }
    
    /* Modal */
    .modal-content {
        padding: 30px 20px;
        max-width: 100%;
    }
    
    /* Footer */
    .footer {
        padding: 40px 0 20px;
    }
    
    .footer-content {
        grid-template-columns: 1fr;
        gap: 30px;
    }
}

/* Mobile Devices */
@media (max-width: 480px) {
    .container {
        padding: 0 15px;
    }
    
    section {
        padding: 50px 0;
    }
    
    /* Navigation */
    .navbar {
        padding: 12px 0;
    }
    
    .logo {
        font-size: 20px;
    }
    
    .logo i {
        font-size: 24px;
    }
    
    .book-btn {
        padding: 8px 16px;
        font-size: 13px;
    }
    
    /* Hero */
    .hero {
        padding: 90px 15px 50px;
    }
    
    .hero-buttons {
        gap: 12px;
    }
    
    .cta-btn {
        padding: 12px 25px;
        font-size: 14px;
    }
    
    /* About Section */
    .about-features {
        margin-top: 30px;
        gap: 20px;
    }
    
    .feature-item {
        padding: 15px;
        gap: 15px;
    }
    
    .feature-item i {
        font-size: 26px;
    }
    
    /* Cars */
    .car-info {
        padding: 20px;
    }
    
    .car-specs {
        gap: 8px;
    }
    
    .car-specs span {
        padding: 5px 10px;
    }
    
    .car-footer {
        flex-direction: column;
        align-items: flex-start;
        gap: 15px;
    }
    
    .view-btn {
        width: 100%;
        justify-content: center;
    }
    
    /* Services */
    .service-card {
        padding: 25px 20px;
    }
    
    .service-icon {
        width: 60px;
        height: 60px;
        font-size: 28px;
    }
    
    /* Contact */
    .info-card {
        padding: 20px;
    }
    
    .contact-form {
        padding: 20px 15px;
    }
    
    .contact-form input,
    .contact-form textarea,
    .form-group input,
    .form-group select,
    .form-group textarea {
        padding: 12px;
        font-size: 14px;
    }
    
    /* Modal */
    .modal {
        padding: 10px;
    }
    
    .modal-content {
        padding: 25px 15px;
    }
    
    .close-modal {
        font-size: 28px;
        top: 10px;
        right: 15px;
    }
    
    /* Footer */
    .social-links a {
        width: 36px;
        height: 36px;
        font-size: 14px;
    }
}

/* Extra Small Devices */
@media (max-width: 360px) {
    .container {
        padding: 0 12px;
    }
    
    .hero {
        padding: 80px 12px 40px;
    }
    
    .cta-btn {
        padding: 10px 20px;
        font-size: 13px;
    }
    
    .car-info {
        padding: 15px;
    }
    
    .service-card {
        padding: 20px 15px;
    }
}

