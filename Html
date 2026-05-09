<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>BUSINESS ADS - Plateforme d'affiliation</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/qrcodejs@1.0.0/qrcode.min.js"></script>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Inter', sans-serif; background: linear-gradient(135deg, #0a0e27 0%, #1a1f3a 100%); min-height: 100vh; color: #fff; }
        body.light-mode { background: linear-gradient(135deg, #f5f7fa 0%, #e9eef5 100%); color: #1e2a5e; }
        body.light-mode .top-nav, body.light-mode .navbar, body.light-mode .services-nav { background: rgba(255,255,255,0.95); border-bottom-color: rgba(0,0,0,0.1); }
        body.light-mode .top-nav-links a, body.light-mode .nav-links a { color: #1e2a5e; }
        body.light-mode .balance-card, body.light-mode .stat-card, body.light-mode .section, body.light-mode .form-card, body.light-mode .auth-card { background: rgba(0,0,0,0.05); border-color: rgba(0,0,0,0.1); }
        .theme-toggle { cursor: pointer; background: rgba(255,255,255,0.2); padding: 0.3rem 0.8rem; border-radius: 50px; font-size: 0.8rem; display: flex; align-items: center; gap: 0.5rem; }
        .toast-notification { position: fixed; bottom: 80px; right: 20px; background: #2c3e66; padding: 0.8rem 1.2rem; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.3); z-index: 1100; display: flex; align-items: center; gap: 0.8rem; border-left: 4px solid #4ecdc4; animation: slideIn 0.3s ease; max-width: 300px; }
        .toast-notification.success { border-left-color: #00d25b; background: #1a3a2a; color: white; }
        .toast-notification.error { border-left-color: #ff4757; background: #3a1a1a; color: white; }
        @keyframes slideIn { from { transform: translateX(100%); opacity: 0; } to { transform: translateX(0); opacity: 1; } }
        .top-nav, .navbar, .services-nav { background: rgba(10,14,39,0.98); backdrop-filter: blur(10px); padding: 0.5rem 2rem; display: flex; justify-content: space-between; align-items: center; border-bottom: 1px solid rgba(255,255,255,0.1); flex-wrap: wrap; gap: 1rem; }
        .brand-logo .main { font-size: 1.3rem; font-weight: 800; background: linear-gradient(135deg, #ff6b6b, #4ecdc4); -webkit-background-clip: text; background-clip: text; color: transparent; }
        .services-nav { background: rgba(26,31,58,0.9); padding: 0.5rem 2rem; display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap; }
        .services-nav a { color: #ccc; text-decoration: none; font-weight: 500; font-size: 0.9rem; cursor: pointer; border-bottom: 2px solid transparent; transition: 0.2s; }
        .services-nav a:hover { color: #4ecdc4; border-bottom-color: #4ecdc4; }
        .navbar { background: rgba(10,14,39,0.98); padding: 0.6rem 1rem; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 100; flex-wrap: wrap; gap: 0.5rem; }
        .nav-links { display: flex; gap: 0.5rem; align-items: center; flex-wrap: wrap; }
        .nav-links a { color: #fff; text-decoration: none; padding: 0.5rem 1rem; border-radius: 10px; cursor: pointer; font-size: 0.85rem; display: inline-flex; align-items: center; gap: 0.3rem; transition: 0.2s; background: rgba(78,205,196,0.1); }
        .nav-links a:hover { background: rgba(78,205,196,0.3); color: #4ecdc4; }
        .user-info { display: flex; align-items: center; gap: 0.8rem; background: rgba(255,255,255,0.08); padding: 0.3rem 0.8rem; border-radius: 50px; }
        .balance { color: #4ecdc4; font-weight: bold; font-size: 0.9rem; }
        .logout-btn { background: rgba(255,71,87,0.2); color: #ff4757; padding: 0.2rem 0.6rem; border-radius: 50px; cursor: pointer; }
        .container { max-width: 1200px; margin: 0 auto; padding: 1rem; }
        .page { display: none; animation: fadeIn 0.3s ease; }
        .page.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        .balances-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1.5rem; margin-bottom: 2rem; }
        .balance-card, .stat-card { background: rgba(255,255,255,0.05); border-radius: 24px; padding: 1.5rem; border: 1px solid rgba(255,255,255,0.1); transition: transform 0.2s; }
        .balance-card:hover, .stat-card:hover { transform: translateY(-5px); }
        .balance-card .amount, .stat-card .value { font-size: 1.6rem; font-weight: bold; background: linear-gradient(135deg, #ff6b6b, #4ecdc4); -webkit-background-clip: text; background-clip: text; color: transparent; }
        .stats-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 1rem; margin-bottom: 1.5rem; }
        .section { background: rgba(255,255,255,0.05); border-radius: 20px; padding: 1.2rem; margin-bottom: 1.5rem; }
        .section-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 1rem; flex-wrap: wrap; gap: 0.5rem; }
        .btn-primary { background: linear-gradient(135deg, #ff6b6b, #4ecdc4); color: white; padding: 0.5rem 1rem; border-radius: 12px; border: none; cursor: pointer; font-weight: 600; transition: opacity 0.2s; }
        .btn-primary:hover { opacity: 0.9; }
        .btn-wave { background: #3b82f6; color: white; width: 100%; padding: 0.7rem; border-radius: 12px; border: none; cursor: pointer; }
        .form-card { background: rgba(255,255,255,0.05); border-radius: 20px; padding: 1.5rem; max-width: 500px; margin: 0 auto; }
        .form-group { margin-bottom: 1rem; }
        .form-group label { display: block; margin-bottom: 0.5rem; color: #ccc; font-size: 0.85rem; }
        .form-group input, .form-group select, .form-group textarea { width: 100%; padding: 0.8rem; background: rgba(0,0,0,0.3); border: 1px solid rgba(255,255,255,0.2); border-radius: 12px; color: #fff; }
        .btn-block { width: 100%; }
        .badge-success { background: rgba(0,210,91,0.2); color: #00d25b; padding: 0.2rem 0.6rem; border-radius: 20px; font-size: 0.7rem; }
        .badge-pending { background: rgba(255,193,7,0.2); color: #ffc107; padding: 0.2rem 0.6rem; border-radius: 20px; font-size: 0.7rem; }
        .badge-auto { background: rgba(78,205,196,0.3); color: #4ecdc4; padding: 0.2rem 0.5rem; border-radius: 20px; font-size: 0.7rem; }
        .alert-error { background: rgba(255,71,87,0.2); border: 1px solid #ff4757; color: #ff4757; padding: 0.8rem; border-radius: 12px; margin-bottom: 1rem; }
        .alert-success { background: rgba(0,210,91,0.2); border: 1px solid #00d25b; color: #00d25b; padding: 0.8rem; border-radius: 12px; margin-bottom: 1rem; }
        .empty-state { text-align: center; padding: 2rem; color: #888; }
        .auth-container { max-width: 450px; margin: 0 auto; padding: 1rem; }
        .auth-card { background: rgba(255,255,255,0.05); border-radius: 24px; padding: 1.5rem; }
        .virtual-card { background: linear-gradient(135deg, #1e2a5e, #0f172a); border-radius: 16px; padding: 1.2rem; border: 1px solid rgba(255,215,0,0.3); margin-bottom: 1rem; }
        .card-number { font-family: monospace; font-size: 1.1rem; background: rgba(0,0,0,0.3); display: inline-block; padding: 0.3rem 0.8rem; border-radius: 10px; margin: 0.5rem 0; }
        .link-copy { display: flex; gap: 0.5rem; align-items: center; flex-wrap: wrap; }
        .link-copy input { flex: 1; padding: 0.5rem; background: rgba(0,0,0,0.3); border-radius: 8px; color: #fff; border: 1px solid rgba(255,255,255,0.2); }
        .btn-copy { background: rgba(78,205,196,0.2); border: none; padding: 0.5rem 0.8rem; border-radius: 8px; cursor: pointer; color: #4ecdc4; transition: 0.2s; }
        .payment-methods { display: flex; gap: 1rem; margin-bottom: 1rem; flex-wrap: wrap; }
        .payment-card { flex: 1; background: rgba(255,255,255,0.05); border-radius: 12px; padding: 0.8rem; text-align: center; cursor: pointer; border: 1px solid transparent; transition: 0.2s; }
        .payment-card.selected { border: 2px solid #3b82f6; background: rgba(59,130,246,0.1); }
        .preset-buttons { display: flex; gap: 0.5rem; margin-bottom: 1rem; flex-wrap: wrap; }
        .preset-btn { background: rgba(255,255,255,0.1); padding: 0.4rem 0.8rem; border-radius: 8px; cursor: pointer; border: none; color: white; font-size: 0.8rem; }
        table { width: 100%; border-collapse: collapse; }
        th, td { padding: 0.8rem; text-align: left; border-bottom: 1px solid rgba(255,255,255,0.05); font-size: 0.85rem; }
        th { color: #aaa; }
        .modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.9); z-index: 1000; justify-content: center; align-items: center; }
        .modal-content { background: #1a1f3a; border-radius: 24px; padding: 1.5rem; max-width: 500px; width: 90%; max-height: 80vh; overflow-y: auto; }
        .btn-close { background: none; border: none; color: #fff; font-size: 1.5rem; cursor: pointer; float: right; }
        .info-row { display: flex; justify-content: space-between; padding: 0.5rem 0; border-bottom: 1px dashed rgba(255,255,255,0.1); }
        .confirmation-box { background: rgba(0,0,0,0.3); border-radius: 16px; padding: 1.2rem; margin: 1rem 0; }
        .whatsapp-float { position: fixed; bottom: 20px; right: 20px; background-color: #25D366; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; box-shadow: 0 4px 10px rgba(0,0,0,0.3); z-index: 1000; text-decoration: none; color: white; }
        .whatsapp-float:hover { transform: scale(1.05); }
        .invoice-qr { text-align: center; margin: 1rem 0; }
        .invoice-qr canvas { background: white; padding: 8px; border-radius: 12px; }
        .invoice-id { font-family: monospace; background: rgba(0,0,0,0.2); padding: 0.3rem 0.6rem; border-radius: 8px; font-size: 0.7rem; }
        canvas { max-height: 300px; background: rgba(255,255,255,0.05); border-radius: 16px; padding: 1rem; }
        @media (max-width: 768px) { .navbar { flex-direction: column; } .nav-links { justify-content: center; } .stats-grid { grid-template-columns: 1fr; } }
    </style>
</head>
<body>

<div class="top-nav" id="topNavPublic">
    <div class="brand-logo"><div class="main">BUSINESS ADS</div><div class="slogan">BOOSTEZ VOTRE BUSINESS, ATTEIGNEZ PLUS LOIN</div></div>
    <div class="top-nav-links">
        <a onclick="showPublicPage('home')">Accueil</a>
        <a id="topLoginBtn" onclick="showAuthPage()">Connexion</a>
        <span id="topUserInfo" style="display:none;"><span id="topUsername"></span><a onclick="logout()" style="margin-left:1rem;">Déconnexion</a></span>
        <div class="theme-toggle" onclick="toggleTheme()"><i class="fas fa-moon"></i> <span id="themeText">Mode clair</span></div>
    </div>
</div>

<div class="services-nav" id="servicesNav" style="display: none;">
    <a onclick="showService('formations')"><i class="fas fa-graduation-cap"></i> Formations</a>
    <a onclick="showService('ebook')"><i class="fas fa-book"></i> Ebook</a>
    <a onclick="showService('support')"><i class="fas fa-headset"></i> Support</a>
    <a onclick="showService('statistics')"><i class="fas fa-chart-line"></i> Stats avancées</a>
</div>

<nav class="navbar" id="navbar" style="display: none;">
    <div class="navbar-brand"><div class="main">BUSINESS ADS</div></div>
    <div class="nav-links">
        <a onclick="showPage('dashboard')"><i class="fas fa-home"></i> Dashboard</a>
        <a onclick="showPage('card')"><i class="fas fa-credit-card"></i> Ma Carte</a>
        <a onclick="showPage('transfer')"><i class="fas fa-exchange-alt"></i> Transfert</a>
        <a onclick="showPage('deposit')"><i class="fas fa-wallet"></i> Dépôt</a>
        <a onclick="showPage('withdraw')"><i class="fas fa-money-bill-wave"></i> Retrait</a>
        <a onclick="showPage('links')"><i class="fas fa-link"></i> Liens</a>
        <a onclick="showPage('admin')" id="adminNavLink" style="display:none;"><i class="fas fa-chart-simple"></i> Admin</a>
        <div class="user-info"><span id="navUsername"></span><span class="balance" id="navBalance">0 FCFA</span><span class="logout-btn" onclick="logout()"><i class="fas fa-sign-out-alt"></i> Déco</span></div>
    </div>
</nav>

<div class="container">
    <!-- Page connexion -->
    <div id="authPage" class="page active">
        <div class="auth-container">
            <div class="auth-card">
                <div class="auth-header"><h1>📢 BUSINESS ADS</h1><p>Cartes Virtuelles & Affiliation</p></div>
                <div id="authError" class="alert-error" style="display: none;"></div>
                <div id="authSuccess" class="alert-success" style="display: none;"></div>
                <form id="loginForm" onsubmit="login(event)">
                    <div class="form-group"><label>Email</label><input type="email" id="loginEmail" required></div>
                    <div class="form-group"><label>Mot de passe</label><input type="password" id="loginPassword" required></div>
                    <button type="submit" class="btn-primary btn-block">Se connecter</button>
                </form>
                <div style="text-align: center; margin: 1rem;">ou</div>
                <form id="registerForm" onsubmit="register(event)">
                    <div class="form-group"><label>Nom d'utilisateur</label><input type="text" id="regUsername" required></div>
                    <div class="form-group"><label>Email</label><input type="email" id="regEmail" required></div>
                    <div class="form-group"><label>Mot de passe</label><input type="password" id="regPassword" required></div>
                    <div class="form-group"><label>Numéro Wave</label><input type="tel" id="regWaveNumber" placeholder="Ex: 87379715" required></div>
                    <div class="form-group"><label>Code Parrain (optionnel)</label><input type="text" id="regSponsorCode" placeholder="Code de parrainage"></div>
                    <button type="submit" class="btn-primary btn-block">S'inscrire</button>
                </form>
            </div>
        </div>
    </div>

    <!-- Dashboard -->
    <div id="dashboardPage" class="page">
        <div class="balances-grid">
            <div class="balance-card"><h3>💰 Solde Principal</h3><div class="amount" id="dashboardBalance">0 FCFA</div><small>Disponible pour retrait</small></div>
            <div class="balance-card"><h3>📊 Total Retraits</h3><div class="amount" id="totalWithdrawnDashboard">0 FCFA</div><small>Cumul des retraits validés</small></div>
        </div>
        <div class="stats-grid">
            <div class="stat-card"><h3>🖱️ Clics totaux</h3><div class="value" id="dashboardClicks">0</div></div>
            <div class="stat-card"><h3>👥 Filleuls N1</h3><div class="value" id="referralCountDashboard">0</div></div>
            <div class="stat-card"><h3>💰 Gains parrainage</h3><div class="value" id="referralEarnings">0 FCFA</div></div>
            <div class="stat-card"><h3>📈 Gains totaux</h3><div class="value" id="dashboardEarnings">0 FCFA</div></div>
            <div class="stat-card"><h3>🔗 Liens actifs</h3><div class="value" id="activeLinksCount">0</div></div>
        </div>
        <div class="section"><div class="section-header"><h2>📊 Évolution des gains (7 derniers jours)</h2></div><canvas id="earningsChart"></canvas></div>
        <div id="adminUsersSection" style="display: none;" class="section">
            <div class="section-header"><h2>👥 Tous les utilisateurs inscrits</h2></div>
            <table id="allUsersTable"><thead><tr><th>Nom</th><th>Email</th><th>Solde</th><th>Code parrainage</th><th>Filleuls</th></tr></thead><tbody><tr><td colspan="5" class="empty-state">Chargement...</td></tr></tbody></table>
        </div>
        <div id="adminCreateUserPanel" style="display: none;" class="section">
            <div class="section-header"><h2>📝 Créer un compte</h2></div>
            <div class="stats-grid"><input type="text" id="adminCreateUsername" placeholder="Nom"><input type="email" id="adminCreateEmail" placeholder="Email"><input type="text" id="adminCreatePassword" placeholder="Mot de passe (auto)"><input type="text" id="adminCreateWave" placeholder="Wave"><button class="btn-primary" onclick="adminCreateUser()">Créer</button><div id="adminCreateResult"></div></div>
        </div>
    </div>

    <!-- Carte Virtuelle -->
    <div id="cardPage" class="page"><h1>💳 Ma Carte Virtuelle</h1><div class="stats-grid"><div class="stat-card"><h3>💰 Solde</h3><div class="value" id="cardBalance">0 FCFA</div></div></div><div class="form-card"><div class="virtual-card"><div class="card-number" id="cardNumberDisplay"></div><div class="info-row"><span>Titulaire</span><span id="cardHolderName"></span></div><div class="info-row"><span>Code carte</span><span id="cardCodeDisplay"></span></div></div><button class="btn-copy" onclick="copyCardCode()">Copier le code</button></div><div class="section"><h2>📥 Transferts reçus</h2><table id="receivedTransfersTable"><thead><tr><th>Date</th><th>De</th><th>Montant</th></tr></thead><tbody><tr><td colspan="3" class="empty-state">Aucun transfert</td></tr></tbody></table></div></div>

    <!-- Transfert -->
    <div id="transferPage" class="page"><h1>🔄 Transférer</h1><div class="stats-grid"><div class="stat-card"><h3>💰 Votre solde</h3><div class="value" id="transferBalance">0 FCFA</div></div></div><div class="form-card"><form id="transferForm"><div class="form-group"><label>🔑 Code carte destinataire</label><input type="text" id="recipientCardCode" required placeholder="Ex: BAD-ABCD-1234"></div><div class="form-group"><label>💰 Montant (FCFA)</label><input type="number" id="transferAmount" min="1000" required></div><button type="submit" class="btn-primary btn-block">Transférer</button></form></div><div class="section"><h2>📤 Transferts envoyés</h2><table id="sentTransfersTable"><thead><tr><th>Date</th><th>À</th><th>Montant</th></tr></thead><tbody><tr><td colspan="3" class="empty-state">Aucun transfert</td></tr></tbody></table></div></div>

    <!-- Dépôt -->
    <div id="depositPage" class="page"><h1>📥 Déposer de l'argent</h1><div class="stats-grid"><div class="stat-card"><h3>💰 Solde actuel</h3><div class="value" id="depositBalance">0 FCFA</div></div></div><div class="form-card"><div class="payment-methods"><div class="payment-card wave selected" onclick="selectDepositMethod('wave')"><i class="fas fa-mobile-alt"></i><h3>Wave Money</h3><small>Compte: 87379715</small></div><div class="payment-card soleaspay" onclick="selectDepositMethod('soleaspay')"><i class="fas fa-qrcode"></i><h3>SoleasPay</h3><small>QR code</small></div></div><div id="soleaspayQrArea" style="display:none; text-align:center;"><img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://soleaspay.com/m/HRPMSRBXXC" width="120"><p><small>Scannez pour payer</small></p></div><div class="form-group"><label>Montant (FCFA)</label><input type="number" id="depositAmount" min="5000" placeholder="Minimum 5 000"></div><div class="preset-buttons"><button class="preset-btn" onclick="setDepositAmount(5000)">5 000</button><button class="preset-btn" onclick="setDepositAmount(10000)">10 000</button><button class="preset-btn" onclick="setDepositAmount(25000)">25 000</button></div><button class="btn-wave" onclick="initiateDeposit()">💳 Payer et obtenir mon code</button><p style="font-size:0.7rem; text-align:center;">📱 Envoyez au numéro Wave: <strong>87379715</strong> ou scannez SoleasPay</p><div id="adminDepositPanel" style="display:none; margin-top:1rem;"><hr><p>🔧 
