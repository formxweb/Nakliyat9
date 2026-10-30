
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#ffffff">
<meta name="description" content="Cesur Nakliyat İzmir - Evden eve nakliyat, asansörlü taşımacılık, ambalajlama ve şehirler arası nakliyat.">
<title>Cesur Nakliyat | İzmir Evden Eve Nakliyat</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700;800&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>
:root {
  --ink:#14202d;
  --muted:#687581;
  --blue:#174f8c;
  --line:#e6ebef;
  --bg:#ffffff;
  --soft:#f5f8fa;
}
* { box-sizing:border-box; }
html { scroll-behavior:smooth; }
body {
  margin:0;
  background:var(--bg);
  color:var(--ink);
  font-family:"DM Sans",sans-serif;
}
a { text-decoration:none; color:inherit; }
button,input,select,textarea { font:inherit; }
button { cursor:pointer; }
.container {
  width:min(1200px,calc(100% - 40px));
  margin:auto;
}
header {
  position:absolute;
  top:0;left:0;right:0;
  z-index:20;
  border-bottom:1px solid rgba(255,255,255,.22);
}
.nav {
  height:86px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:24px;
}
.logo {
  display:flex;
  align-items:center;
  gap:12px;
  color:white;
  font-weight:800;
  font-size:23px;
  letter-spacing:-1px;
}
.logo-mark {
  width:43px;height:43px;
  display:grid;place-items:center;
  background:white;
  color:var(--blue);
  border-radius:11px;
  font-weight:800;
  font-size:24px;
}
.logo small {
  display:block;
  font-size:10px;
  letter-spacing:3px;
  font-weight:600;
  margin-top:1px;
}
nav {
  display:flex;
  gap:30px;
  align-items:center;
}
nav a {
  font-size:13px;
  font-weight:700;
  color:white;
}
.nav-cta {
  padding:13px 19px;
  border-radius:5px;
  background:white;
  color:var(--ink);
  font-size:13px;
  font-weight:800;
}
.menu-toggle {
  display:none;
  color:white;
  background:transparent;
  border:0;
  font-size:28px;
}
.hero {
  position:relative;
  min-height:740px;
  height:100svh;
  max-height:1050px;
  display:flex;
  align-items:center;
  overflow:hidden;
  background:#1c2e3d;
  color:white;
}
.hero-video {
  position:absolute;
  inset:0;
  width:100%;
  height:100%;
  object-fit:cover;
  z-index:0;
}
.hero:before {
  content:"";
  position:absolute;
  inset:0;
  background:linear-gradient(90deg,rgba(5,17,29,.85),rgba(5,17,29,.38) 70%),
             linear-gradient(0deg,rgba(5,17,29,.48),transparent 50%);
  z-index:1;
}
.hero-content {
  position:relative;
  z-index:2;
  padding-top:100px;
}
.eyebrow {
  font-size:12px;
  letter-spacing:3px;
  text-transform:uppercase;
  font-weight:800;
}
.hero .eyebrow {
  display:flex;
  align-items:center;
  gap:13px;
  color:#e5effb;
}
.hero .eyebrow:before {
  content:"";
  width:35px;height:2px;
  background:#fff;
}
h1,h2,h3,p { margin-top:0; }
h1,h2,h3 { font-family:Manrope,sans-serif; }
h1 {
  font-size:clamp(48px,7.5vw,104px);
  letter-spacing:-5px;
  line-height:1.06;
  max-width:900px;
  margin:28px 0;
  font-weight:800;
}
.hero p {
  max-width:590px;
  color:#e1e8ed;
  font-size:18px;
  line-height:1.9;
}
.hero-buttons {
  display:flex;
  flex-wrap:wrap;
  gap:12px;
  margin-top:36px;
}
.btn {
  display:inline-flex;
  align-items:center;
  justify-content:center;
  min-height:54px;
  padding:0 24px;
  font-size:13px;
  font-weight:800;
  border-radius:5px;
  transition:.25s;
}
.btn:hover { transform:translateY(-3px); }
.btn-white { background:white;color:#152333; }
.btn-outline { border:1px solid #ffffff80;color:white; }
.btn-blue { background:var(--blue);color:white; }
.hero-bottom {
  position:absolute;
  bottom:35px;
  left:0;right:0;
  z-index:2;
}
.hero-bottom .container {
  display:flex;
  justify-content:space-between;
  color:#e8edf1;
  font-size:12px;
  letter-spacing:1px;
}
section { padding:105px 0; }
.section-label {
  font-size:11px;
  color:var(--blue);
  letter-spacing:3px;
  font-weight:800;
  text-transform:uppercase;
  margin-bottom:18px;
}
.section-title {
  font-size:clamp(32px,4vw,57px);
  line-height:1.16;
  letter-spacing:-2px;
  margin-bottom:22px;
  font-weight:800;
}
.section-text {
  font-size:16px;
  line-height:2;
  color:var(--muted);
}
.intro-grid {
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:90px;
  align-items:center;
}
.intro-image {
  position:relative;
  height:510px;
  overflow:hidden;
  border-radius:7px;
  background:var(--soft);
}
.intro-image img {
  width:100%;
  height:100%;
  object-fit:cover;
}
.image-tag {
  position:absolute;
  bottom:22px;
  left:22px;
  padding:14px 20px;
  background:white;
  font-weight:800;
  font-size:13px;
  border-radius:4px;
}
.stats {
  display:grid;
  grid-template-columns:repeat(3,1fr);
  margin-top:35px;
  gap:18px;
  border-top:1px solid var(--line);
  padding-top:25px;
}
.stat strong {
  display:block;
  font-size:22px;
  color:var(--ink);
}
.stat span {
  display:block;
  color:var(--muted);
  font-size:12px;
  margin-top:6px;
}
.soft { background:var(--soft); }
.section-head {
  display:flex;
  justify-content:space-between;
  gap:35px;
  align-items:end;
  margin-bottom:40px;
}
.section-head .section-text { max-width:420px; }
.services {
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:18px;
}
.service {
  padding:34px 28px;
  background:white;
  border:1px solid var(--line);
  border-radius:7px;
  transition:.25s;
}
.service:hover {
  transform:translateY(-5px);
  box-shadow:0 15px 40px #162a4010;
}
.service .num {
  color:#8da6bd;
  font-size:12px;
  font-weight:800;
  margin-bottom:50px;
}
.service h3 {
  font-size:21px;
  letter-spacing:-.7px;
}
.service p {
  color:var(--muted);
  line-height:1.9;
  font-size:14px;
  margin-bottom:0;
}
.gallery-wrap { overflow:hidden; }
.gallery-top {
  display:flex;
  justify-content:space-between;
  align-items:end;
  margin-bottom:36px;
}
.gallery-controls { display:flex;gap:8px; }
.arrow {
  width:48px;height:48px;
  border:1px solid var(--line);
  border-radius:50%;
  background:white;
  font-size:22px;
  color:var(--ink);
}
.gallery-track {
  display:flex;
  gap:20px;
  overflow-x:auto;
  scroll-snap-type:x mandatory;
  scrollbar-width:none;
  padding-bottom:15px;
}
.gallery-track::-webkit-scrollbar { display:none; }
.gallery-item {
  flex:0 0 365px;
  scroll-snap-align:start;
}
.gallery-item img {
  display:block;
  width:100%;
  height:400px;
  object-fit:cover;
  background:#eef1f3;
  border-radius:6px;
}
.gallery-item h3 {
  margin:20px 0 6px;
  font-size:18px;
}
.gallery-item p {
  color:var(--muted);
  font-size:13px;
}
.process {
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:22px;
  margin-top:45px;
}
.step {
  border-top:2px solid #cad5de;
  padding-top:23px;
}
.step strong {
  display:block;
  font-size:13px;
  color:var(--blue);
  margin-bottom:38px;
}
.step h3 { font-size:19px; }
.step p {
  color:var(--muted);
  font-size:14px;
  line-height:1.9;
}
.cta-section {
  background:#142a40;
  color:white;
}
.cta-grid {
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:80px;
  align-items:center;
}
.cta-section .section-label { color:#adcbe6; }
.cta-section .section-text { color:#b9c7d3; }
.contact-box {
  background:white;
  padding:35px;
  color:var(--ink);
  border-radius:8px;
}
.contact-box h3 { font-size:23px; }
.contact-box p {
  color:var(--muted);
  font-size:13px;
  line-height:1.8;
}
.field { margin-top:13px; }
.field input,.field select,.field textarea {
  width:100%;
  border:1px solid #dce4ea;
  background:#f9fbfc;
  padding:15px;
  border-radius:4px;
  outline:none;
  font-size:14px;
}
.field textarea { resize:vertical;min-height:90px; }
.contact-box button {
  width:100%;
  margin-top:16px;
  border:0;
}
.contact-info {
  display:grid;
  gap:16px;
  margin-top:35px;
  color:white;
}
.contact-info a { font-weight:700; }
footer {
  background:#0d1d2d;
  color:#c5d0d9;
  padding:40px 0;
}
.footer-inner {
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:20px;
  font-size:13px;
}
footer a { color:white; }
.whatsapp-float {
  position:fixed;
  bottom:22px;
  right:22px;
  z-index:30;
  background:#25d366;
  color:white;
  padding:15px 20px;
  border-radius:50px;
  box-shadow:0 8px 28px #0003;
  font-weight:800;
  font-size:13px;
}
@media(max-width:900px) {
  .intro-grid,.cta-grid { grid-template-columns:1fr;gap:35px; }
  .services { grid-template-columns:repeat(2,1fr); }
  .process { grid-template-columns:repeat(2,1fr); }
  .intro-image { height:420px; }
  .section-head { display:block; }
}
@media(max-width:650px) {
  .container { width:calc(100% - 34px); }
  .nav { height:72px; }
  .logo { font-size:19px; }
  .logo-mark { width:37px;height:37px; }
  .menu-toggle { display:block; }
  nav {
    display:none;
    position:absolute;
    top:72px;left:0;right:0;
    background:#142a40;
    padding:25px;
    flex-direction:column;
    align-items:flex-start;
  }
  nav.open { display:flex; }
  .nav-cta { display:none; }
  .hero { min-height:650px;max-height:none; }
  h1 { letter-spacing:-2.5px;font-size:clamp(43px,11vw,65px); }
  .hero p { font-size:15px;line-height:1.8; }
  .hero-bottom { bottom:22px; }
  .hero-bottom .container { font-size:10px; }
  section { padding:70px 0; }
  .section-title { letter-spacing:-1.3px; }
  .intro-image { height:340px; }
  .services,.process { grid-template-columns:1fr; }
  .service .num { margin-bottom:25px; }
  .gallery-item { flex-basis:82vw; }
  .gallery-item img { height:330px; }
  .contact-box { padding:23px; }
  .footer-inner { flex-direction:column;align-items:flex-start; }
  .stats { gap:8px; }
  .stat strong { font-size:17px; }
}
@media(prefers-reduced-motion:reduce) {
  html { scroll-behavior:auto; }
  .btn,.service { transition:none; }
}
</style>
</head>

<body>

<header>
  <div class="container nav">
    <a href="#" class="logo">
      <span class="logo-mark">C</span>
      <span>CESUR <small>NAKLİYAT</small></span>
    </a>

    <nav id="nav">
      <a href="#hakkimizda">Hakkımızda</a>
      <a href="#hizmetler">Hizmetlerimiz</a>
      <a href="#calismalar">Çalışmalarımız</a>
      <a href="#surec">Taşıma Süreci</a>
      <a href="#iletisim">İletişim</a>
    </nav>

    <a class="nav-cta" href="tel:05510493159">HEMEN ARA ↗</a>
    <button class="menu-toggle" id="menuToggle" aria-label="Menüyü aç" aria-expanded="false">☰</button>
  </div>
</header>

<main>

<section class="hero" id="anasayfa">
  <video class="hero-video" autoplay muted loop playsinline preload="metadata" poster="medya-1.jpg">
    <source src="nakliyat.mp4" type="video/mp4">
  </video>

  <div class="container hero-content">
    <div class="eyebrow">İZMİR · PROFESYONEL TAŞIMACILIK</div>

    <h1>Yeni bir adres.<br>Aynı güven.</h1>

    <p>
      Hayatınızın yeni başlangıcına güvenle eşlik ediyoruz.
      İzmir'den Türkiye'nin dört bir yanına, her eşyaya
      özen gösteren profesyonel taşımacılık.
    </p>

    <div class="hero-buttons">
      <a class="btn btn-white" href="#iletisim">ÜCRETSİZ TEKLİF AL ↗</a>
      <a class="btn btn-outline" href="#calismalar">ÇALIŞMALARIMIZI KEŞFEDİN</a>
    </div>
  </div>

  <div class="hero-bottom">
    <div class="container">
      <span>CESUR NAKLİYAT / İZMİR</span>
      <span>AŞAĞI KAYDIR ↓</span>
    </div>
  </div>
</section>

<section id="hakkimizda">
  <div class="container intro-grid">
    <div>
      <div class="section-label">BİZ KİMİZ?</div>
      <h2 class="section-title">Sadece eşya değil,<br>güven taşıyoruz.</h2>
      <p class="section-text">
        Taşınmak, hayatınızdaki önemli değişimlerden biridir.
        Cesur Nakliyat olarak bu süreci sizin için daha düzenli,
        güvenli ve zahmetsiz hale getirmeyi hedefliyoruz.
      </p>
      <p class="section-text">
        Evden eve nakliyat, asansörlü taşımacılık,
        ambalajlama ve şehirler arası taşımacılık
        hizmetlerimizle her aşamada yanınızdayız.
      </p>
      <div class="stats">
        <div class="stat"><strong>01</strong><span>Planlı taşıma</span></div>
        <div class="stat"><strong>02</strong><span>Özenli paketleme</span></div>
        <div class="stat"><strong>03</strong><span>Güvenli teslimat</span></div>
      </div>
    </div>

    <div class="intro-image">
      <img src="medya-1.jpg" alt="Cesur Nakliyat taşımacılık çalışması" loading="lazy">
      <div class="image-tag">İZMİR'DEN TÜRKİYE'YE</div>
    </div>
  </div>
</section>

<section class="soft" id="hizmetler">
  <div class="container">
    <div class="section-head">
      <div>
        <div class="section-label">HİZMETLERİMİZ</div>
        <h2 class="section-title">Her taşınma için<br>doğru çözüm.</h2>
      </div>
      <p class="section-text">
        Eşyalarınızın taşınma sürecini ihtiyaçlarınıza
        uygun şekilde planlıyor ve yönetiyoruz.
      </p>
    </div>

    <div class="services">
      <article class="service">
        <div class="num">01 / HİZMET</div>
        <h3>Evden Eve Nakliyat</h3>
        <p>Ev eşyalarınızın hazırlanmasından yeni adresinize taşınmasına kadar planlı nakliye hizmeti.</p>
      </article>
      <article class="service">
        <div class="num">02 / HİZMET</div>
        <h3>Asansörlü Taşımacılık</h3>
        <p>Uygun binalarda dış cephe asansörüyle daha kontrollü eşya taşıma çözümleri.</p>
      </article>
      <article class="service">
        <div class="num">03 / HİZMET</div>
        <h3>Şehirler Arası Nakliyat</h3>
        <p>İzmir çıkışlı şehirler arası taşınmalar için planlama ve nakliye desteği.</p>
      </article>
      <article class="service">
        <div class="num">04 / HİZMET</div>
        <h3>Ambalajlama</h3>
        <p>Mobilya ve diğer eşyaların taşınmaya uygun malzemelerle hazırlanması.</p>
      </article>
      <article class="service">
        <div class="num">05 / HİZMET</div>
        <h3>Ofis Taşımacılığı</h3>
        <p>İş yerlerinin ihtiyaçlarına göre düzenli ve koordineli taşıma hizmeti.</p>
      </article>
      <article class="service">
        <div class="num">06 / HİZMET</div>
        <h3>Taşınma Planlaması</h3>
        <p>Eşya miktarı, kat durumu ve mesafe dikkate alınarak taşıma organizasyonu.</p>
      </article>
    </div>
  </div>
</section>

<section class="gallery-wrap" id="calismalar">
  <div class="container">
    <div class="gallery-top">
      <div>
        <div class="section-label">SAHADAN KARELER</div>
        <h2 class="section-title">İşimiz konuşsun.</h2>
      </div>
      <div class="gallery-controls">
        <button class="arrow" id="prev" aria-label="Önceki fotoğraf">←</button>
        <button class="arrow" id="next" aria-label="Sonraki fotoğraf">→</button>
      </div>
    </div>

    <div class="gallery-track" id="gallery">
      <article class="gallery-item">
        <img src="medya-1.jpg" alt="İzmir nakliyat aracı" loading="lazy">
        <h3>İzmir'de taşımacılık</h3>
        <p>Cesur Nakliyat çalışma alanından</p>
      </article>
      <article class="gallery-item">
        <img src="medya-3.jpg" alt="Eşya paketleme çalışması" loading="lazy">
        <h3>Özenli ambalajlama</h3>
        <p>Taşınma öncesi eşya hazırlığı</p>
      </article>
      <article class="gallery-item">
        <img src="medya-4.jpg" alt="Asansörlü nakliyat" loading="lazy">
        <h3>Asansörlü taşımacılık</h3>
        <p>Yüksek katlara taşıma çözümleri</p>
      </article>
      <article class="gallery-item">
        <img src="medya-5.jpg" alt="Nakliyat araçları" loading="lazy">
        <h3>Yollarda Cesur Nakliyat</h3>
        <p>Taşıma organizasyonlarımızdan kareler</p>
      </article>
      <article class="gallery-item">
        <img src="medya-6.jpg" alt="Cesur Nakliyat çalışması" loading="lazy">
        <h3>Profesyonel yaklaşım</h3>
        <p>Her aşamada özenli çalışma</p>
      </article>
      <article class="gallery-item">
        <img src="medya-7.jpg" alt="Taşımacılık operasyonu" loading="lazy">
        <h3>Yeni adreslere doğru</h3>
        <p>Taşınma sürecinden görüntüler</p>
      </article>
    </div>
  </div>
</section>

<section class="soft" id="surec">
  <div class="container">
    <div class="section-label">NASIL ÇALIŞIYORUZ?</div>
    <h2 class="section-title">Dört adımda<br>yeni adresinizde.</h2>

    <div class="process">
      <div class="step">
        <strong>01</strong>
        <h3>İletişim</h3>
        <p>Taşınma adresinizi, eşya durumunuzu ve ihtiyaçlarınızı öğreniyoruz.</p>
      </div>
      <div class="step">
        <strong>02</strong>
        <h3>Planlama</h3>
        <p>Taşıma günü, araç ve gerekli ekipman için organizasyon yapıyoruz.</p>
      </div>
      <div class="step">
        <strong>03</strong>
        <h3>Taşıma</h3>
        <p>Eşyalarınızın hazırlanması, yüklenmesi ve nakliyesi gerçekleştiriliyor.</p>
      </div>
      <div class="step">
        <strong>04</strong>
        <h3>Teslimat</h3>
        <p>Eşyalarınız yeni adresinize ulaştırılarak taşıma süreci tamamlanıyor.</p>
      </div>
    </div>
  </div>
</section>

<section class="cta-section" id="iletisim">
  <div class="container cta-grid">
    <div>
      <div class="section-label">BİZE ULAŞIN</div>
      <h2 class="section-title">Yeni adresinize<br>birlikte gidelim.</h2>
      <p class="section-text">
        Taşınma planınızı bizimle paylaşın.
        Size uygun nakliye seçeneklerini değerlendirelim.
      </p>
      <div class="contact-info">
        <a href="tel:05510493159">☎ 0551 049 31 59</a>
        <a href="tel:05548602885">☎ 0554 860 28 85</a>
        <a href="https://www.instagram.com/cesurnakliyatizmir/" target="_blank" rel="noopener noreferrer">Instagram: @cesurnakliyatizmir ↗</a>
      </div>
    </div>

    <div class="contact-box">
      <h3>Ücretsiz teklif isteyin.</h3>
      <p>Bilgilerinizi girin, WhatsApp üzerinden bize ulaşın.</p>

      <form id="quoteForm">
        <div class="field">
          <input id="name" type="text" placeholder="Adınız Soyadınız" required>
        </div>
        <div class="field">
          <input id="phone" type="tel" placeholder="Telefon Numaranız" required>
        </div>
        <div class="field">
          <input id="from" type="text" placeholder="Nereden taşınıyorsunuz?" required>
        </div>
        <div class="field">
          <input id="to" type="text" placeholder="Nereye taşınıyorsunuz?" required>
        </div>
        <div class="field">
          <select id="service" required>
            <option value="">Hizmet seçiniz</option>
            <option>Evden eve nakliyat</option>
            <option>Asansörlü nakliyat</option>
            <option>Şehirler arası nakliyat</option>
            <option>Ofis taşımacılığı</option>
            <option>Diğer</option>
          </select>
        </div>
        <div class="field">
          <textarea id="note" placeholder="Ek bilgi (isteğe bağlı)"></textarea>
        </div>
        <button class="btn btn-blue" type="submit">WHATSAPP İLE TEKLİF AL ↗</button>
      </form>
    </div>
  </div>
</section>

</main>

<footer>
  <div class="container footer-inner">
    <div>© <span id="year"></span> CESUR NAKLİYAT. Tüm hakları saklıdır.</div>
    <div>İzmir · Türkiye</div>
    <a href="#anasayfa">YUKARI ÇIK ↑</a>
  </div>
</footer>

<a class="whatsapp-float"
   href="https://wa.me/905510493159?text=Merhaba%2C%20nakliyat%20hizmeti%20hakk%C4%B1nda%20bilgi%20almak%20istiyorum."
   target="_blank" rel="noopener noreferrer">
  WhatsApp ↗
</a>

<script>
const menuToggle = document.getElementById("menuToggle");
const nav = document.getElementById("nav");

menuToggle.addEventListener("click", () => {
  const isOpen = nav.classList.toggle("open");
  menuToggle.setAttribute("aria-expanded", String(isOpen));
});

document.querySelectorAll("nav a").forEach(link => {
  link.addEventListener("click", () => {
    nav.classList.remove("open");
    menuToggle.setAttribute("aria-expanded", "false");
  });
});

const gallery = document.getElementById("gallery");

document.getElementById("next").addEventListener("click", () => {
  gallery.scrollBy({left:385,behavior:"smooth"});
});

document.getElementById("prev").addEventListener("click", () => {
  gallery.scrollBy({left:-385,behavior:"smooth"});
});

document.getElementById("year").textContent = new Date().getFullYear();

document.getElementById("quoteForm").addEventListener("submit", function(e) {
  e.preventDefault();

  const name = document.getElementById("name").value.trim();
  const phone = document.getElementById("phone").value.trim();
  const from = document.getElementById("from").value.trim();
  const to = document.getElementById("to").value.trim();
  const service = document.getElementById("service").value;
  const note = document.getElementById("note").value.trim();

  const message =
    "Merhaba, Cesur Nakliyat'tan teklif almak istiyorum.\n\n" +
    "Ad Soyad: " + name + "\n" +
    "Telefon: " + phone + "\n" +
    "Nereden: " + from + "\n" +
    "Nereye: " + to + "\n" +
    "Hizmet: " + service + "\n" +
    "Ek Bilgi: " + (note || "Belirtilmedi");

  window.open(
    "https://wa.me/905510493159?text=" + encodeURIComponent(message),
    "_blank",
    "noopener,noreferrer"
  );
});
</script>

</body>
</html>
