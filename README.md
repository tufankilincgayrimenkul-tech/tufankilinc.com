<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tufan Kılınç | Gayrimenkul Danışmanı</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:Georgia,serif;color:#e8e0d0;background:#0a0a0a;line-height:1.6;overflow-x:hidden}
a{text-decoration:none;color:inherit}

:root{
  --gold:#c9a84c;
  --gold-light:#e8c97a;
  --gold-dim:#6a5520;
  --dark:#0a0a0a;
  --dark2:#111;
  --dark3:#181818;
  --dark4:#202020;
  --text:#e8e0d0;
  --muted:#888070;
  --border:rgba(201,168,76,0.18);
  --border2:rgba(201,168,76,0.38);
}

/* NAV */
nav{position:fixed;top:0;left:0;right:0;z-index:999;background:rgba(10,10,10,0.96);border-bottom:1px solid var(--border);padding:1.1rem 3rem;display:flex;justify-content:space-between;align-items:center}
.nav-logo{font-size:1.1rem;font-weight:400;letter-spacing:0.14em;text-transform:uppercase;color:#fff}
.nav-logo span{color:var(--gold)}
.nav-links{display:flex;gap:2.5rem;align-items:center}
.nav-links a{font-size:0.72rem;letter-spacing:0.15em;text-transform:uppercase;color:var(--muted);transition:color 0.25s;font-family:Arial,sans-serif}
.nav-links a:hover{color:var(--gold)}
.nav-cta{border:1px solid var(--gold);color:var(--gold)!important;padding:0.5rem 1.3rem;transition:all 0.25s!important}
.nav-cta:hover{background:var(--gold);color:#0a0a0a!important}

/* HERO */
.hero{min-height:100vh;display:flex;align-items:center;background:#0a0a0a;padding:0 3rem}
.hero-inner{max-width:1200px;margin:0 auto;width:100%;display:grid;grid-template-columns:1fr 380px;gap:5rem;align-items:center;padding-top:5rem}
.eyebrow{display:flex;align-items:center;gap:1rem;margin-bottom:2rem}
.eline{width:36px;height:1px;background:var(--gold)}
.etxt{font-family:Arial,sans-serif;font-size:0.68rem;letter-spacing:0.22em;text-transform:uppercase;color:var(--gold)}
.hero h1{font-size:4rem;font-weight:400;line-height:1.12;margin-bottom:1.5rem;color:#fff;font-style:italic}
.hero h1 b{font-style:normal;color:var(--gold);font-weight:400}
.hero p{font-family:Arial,sans-serif;font-size:0.88rem;color:var(--muted);max-width:420px;margin-bottom:2.5rem;line-height:1.9}
.btns{display:flex;gap:1rem;flex-wrap:wrap}
.btn-g{background:var(--gold);color:#0a0a0a;padding:0.85rem 1.9rem;font-family:Arial,sans-serif;font-size:0.72rem;font-weight:700;letter-spacing:0.15em;text-transform:uppercase;transition:background 0.25s;display:inline-flex;align-items:center;gap:0.5rem;cursor:pointer;border:none}
.btn-g:hover{background:var(--gold-light)}
.btn-o{border:1px solid var(--border2);color:var(--text);padding:0.85rem 1.9rem;font-family:Arial,sans-serif;font-size:0.72rem;letter-spacing:0.15em;text-transform:uppercase;transition:all 0.25s;display:inline-flex;align-items:center;gap:0.5rem}
.btn-o:hover{border-color:var(--gold);color:var(--gold)}

/* HERO CARD */
.hcard{background:var(--dark3);border:1px solid var(--border)}
.hcard-top{background:var(--dark4);padding:2rem;border-bottom:1px solid var(--border);text-align:center}
.av{width:76px;height:76px;border-radius:50%;border:1px solid var(--gold);margin:0 auto 1rem;display:flex;align-items:center;justify-content:center;font-size:1.5rem;color:var(--gold);background:var(--dark)}
.hcard h3{font-size:1.25rem;font-weight:400;color:#fff;letter-spacing:0.06em}
.hcard .sub{font-family:Arial,sans-serif;font-size:0.68rem;letter-spacing:0.18em;text-transform:uppercase;color:var(--gold);margin-top:0.4rem}
.hcard-body{padding:1.25rem 1.75rem}
.hrow{display:flex;justify-content:space-between;align-items:center;padding:0.75rem 0;border-bottom:1px solid rgba(255,255,255,0.05)}
.hrow:last-child{border-bottom:none}
.hlabel{font-family:Arial,sans-serif;font-size:0.68rem;letter-spacing:0.12em;text-transform:uppercase;color:var(--muted)}
.hval{font-size:1.15rem;color:var(--gold);font-weight:400}
.hcard-foot{padding:1.25rem 1.75rem;border-top:1px solid var(--border)}

/* SECTIONS */
section{padding:6rem 3rem}
.si{max-width:1200px;margin:0 auto}
.stitle{font-size:2.75rem;font-weight:400;color:#fff;margin-bottom:1rem;font-style:italic}
.ssub{font-family:Arial,sans-serif;font-size:0.85rem;color:var(--muted);max-width:500px;line-height:1.9}
.divdr{width:56px;height:1px;background:var(--gold);margin:1.5rem 0 3rem}

/* HİZMETLER */
.hizmetler{background:var(--dark2)}
.hgrid{display:grid;grid-template-columns:repeat(3,1fr);border:1px solid var(--border);margin-top:3rem}
.hcard2{padding:2.25rem 1.75rem;border-right:1px solid var(--border);border-bottom:1px solid var(--border);transition:background 0.25s}
.hcard2:hover{background:var(--dark3)}
.hcard2:nth-child(3n){border-right:none}
.hcard2:nth-child(4),.hcard2:nth-child(5),.hcard2:nth-child(6){border-bottom:none}
.hnum{font-size:2.5rem;color:rgba(201,168,76,0.12);line-height:1;margin-bottom:1.25rem}
.hcard2 h3{font-family:Arial,sans-serif;font-size:0.75rem;letter-spacing:0.13em;text-transform:uppercase;color:#fff;margin-bottom:0.6rem;font-weight:600}
.hcard2 p{font-family:Arial,sans-serif;font-size:0.8rem;color:var(--muted);line-height:1.8}

/* HAKKIMDA */
.hakkimda{background:var(--dark)}
.hgrid2{display:grid;grid-template-columns:1fr 1fr;gap:5rem;align-items:start;margin-top:3rem}
.htext p{font-family:Arial,sans-serif;font-size:0.875rem;color:var(--muted);margin-bottom:1.1rem;line-height:1.9}
.htext p strong{color:var(--text);font-weight:600}
.highlights{display:flex;flex-direction:column}
.hl{display:flex;gap:1.25rem;align-items:flex-start;padding:1.25rem 0;border-bottom:1px solid var(--border)}
.hl:first-child{border-top:1px solid var(--border)}
.hlnum{font-size:1.75rem;color:var(--gold);min-width:52px;font-weight:400;line-height:1}
.hl h4{font-family:Arial,sans-serif;font-size:0.72rem;letter-spacing:0.12em;text-transform:uppercase;color:#fff;margin-bottom:0.35rem;font-weight:600}
.hl p{font-family:Arial,sans-serif;font-size:0.78rem;color:var(--muted)}

/* NEDEN */
.neden{background:var(--dark2)}
.ngrid{display:grid;grid-template-columns:repeat(4,1fr);border:1px solid var(--border);margin-top:3rem}
.nitem{padding:3rem 1.5rem;text-align:center;border-right:1px solid var(--border)}
.nitem:last-child{border-right:none}
.nnum{font-size:3rem;font-weight:400;color:var(--gold);display:block;line-height:1;margin-bottom:0.6rem}
.nitem p{font-family:Arial,sans-serif;font-size:0.72rem;letter-spacing:0.1em;text-transform:uppercase;color:var(--muted)}

/* İLETİŞİM */
.iletisim{background:var(--dark)}
.igrid{display:grid;grid-template-columns:1fr 1fr;gap:5rem;align-items:start;margin-top:3rem}
.crows{display:flex;flex-direction:column}
.crow{padding:1.25rem 0;border-bottom:1px solid var(--border)}
.crow:first-child{border-top:1px solid var(--border)}
.clabel{font-family:Arial,sans-serif;font-size:0.68rem;letter-spacing:0.16em;text-transform:uppercase;color:var(--gold);margin-bottom:0.3rem}
.cval{font-family:Arial,sans-serif;font-size:0.95rem;color:#fff;font-weight:300}
.wabtn{background:var(--gold);color:#0a0a0a;padding:1.1rem 1.75rem;font-family:Arial,sans-serif;font-size:0.72rem;font-weight:700;letter-spacing:0.15em;text-transform:uppercase;display:flex;align-items:center;gap:0.75rem;margin-top:1.75rem;transition:background 0.25s;cursor:pointer;border:none;width:100%;justify-content:center}
.wabtn:hover{background:var(--gold-light)}
.cright{display:flex;flex-direction:column;gap:2rem}
.quote{border-left:2px solid var(--gold);padding-left:1.5rem}
.quote p{font-size:1.5rem;font-weight:400;color:#fff;line-height:1.55;font-style:italic}
.quote cite{font-family:Arial,sans-serif;font-size:0.68rem;letter-spacing:0.12em;text-transform:uppercase;color:var(--gold);margin-top:0.9rem;display:block;font-style:normal}
.bolgebox{background:var(--dark3);border:1px solid var(--border);padding:1.5rem}
.bolgebox h4{font-family:Arial,sans-serif;font-size:0.68rem;letter-spacing:0.16em;text-transform:uppercase;color:var(--gold);margin-bottom:1rem;font-weight:600}
.blist{display:flex;flex-wrap:wrap;gap:0.5rem}
.bolge{font-family:Arial,sans-serif;font-size:0.68rem;letter-spacing:0.08em;border:1px solid var(--border);padding:0.3rem 0.7rem;color:var(--muted);text-transform:uppercase}

/* FOOTER */
footer{background:#050505;border-top:1px solid var(--border);padding:2.5rem 3rem;display:flex;justify-content:space-between;align-items:center}
.flogo{font-size:1rem;letter-spacing:0.14em;text-transform:uppercase;color:#fff}
.flogo span{color:var(--gold)}
footer p{font-family:Arial,sans-serif;font-size:0.68rem;letter-spacing:0.1em;color:var(--muted);text-transform:uppercase}

/* WhatsApp FAB */
.wafab{position:fixed;bottom:2rem;right:2rem;width:52px;height:52px;background:#25D366;display:flex;align-items:center;justify-content:center;z-index:500;transition:transform 0.25s;cursor:pointer;border-radius:50%}
.wafab:hover{transform:scale(1.1)}
.wafab svg{width:26px;height:26px;fill:#fff}

@media(max-width:800px){
  nav{padding:1rem 1.25rem}
  .nav-links{display:none}
  .hero{padding:0 1.25rem}
  .hero-inner{grid-template-columns:1fr;padding-top:5rem;gap:2rem}
  .hero h1{font-size:2.6rem}
  .hcard{display:none}
  section{padding:4rem 1.25rem}
  .hgrid{grid-template-columns:1fr}
  .hcard2{border-right:none}
  .hcard2:nth-child(n){border-bottom:1px solid var(--border)}
  .hcard2:last-child{border-bottom:none}
  .hgrid2,.igrid{grid-template-columns:1fr;gap:2.5rem}
  .ngrid{grid-template-columns:repeat(2,1fr)}
  .nitem:nth-child(2){border-right:none}
  .nitem:nth-child(3),.nitem:nth-child(4){border-top:1px solid var(--border)}
  footer{flex-direction:column;gap:0.75rem;text-align:center;padding:2rem 1.25rem}
}
</style>
</head>
<body>

<nav>
  <div class="nav-logo">Tufan <span>Kılınç</span></div>
  <div class="nav-links">
    <a href="#hizmetler">Hizmetler</a>
    <a href="#hakkimda">Hakkımda</a>
    <a href="#iletisim">İletişim</a>
    <a href="https://wa.me/905000000000" class="nav-cta">WhatsApp</a>
  </div>
</nav>

<!-- HERO -->
<section class="hero" id="anasayfa">
  <div class="hero-inner">
    <div>
      <div class="eyebrow"><div class="eline"></div><span class="etxt">Mersin · Gayrimenkul Danışmanı</span></div>
      <h1>Prestijli<br>Mülklerde<br><b>Güvenilir</b><br>Rehberiniz</h1>
      <p>Mersin'in en seçkin konutları ve ticari mülklerinde uzman danışmanlık. Her adımda şeffaf, hızlı ve güvenilir.</p>
      <div class="btns">
        <a href="#hizmetler" class="btn-g">Hizmetleri Keşfet</a>
        <a href="https://wa.me/905000000000" class="btn-o">WhatsApp</a>
      </div>
    </div>
    <div class="hcard">
      <div class="hcard-top">
        <div class="av">TK</div>
        <h3>Tufan Kılınç</h3>
        <p class="sub">Lisanslı Gayrimenkul Danışmanı</p>
      </div>
      <div class="hcard-body">
        <div class="hrow"><span class="hlabel">Deneyim</span><span class="hval">10+ Yıl</span></div>
        <div class="hrow"><span class="hlabel">Tamamlanan İşlem</span><span class="hval">200+</span></div>
        <div class="hrow"><span class="hlabel">Memnuniyet</span><span class="hval">%97</span></div>
        <div class="hrow"><span class="hlabel">Bölge</span><span class="hval">Mersin</span></div>
      </div>
      <div class="hcard-foot">
        <a href="https://wa.me/905000000000" class="btn-g" style="width:100%;justify-content:center;font-size:0.7rem">Hemen Ulaşın</a>
      </div>
    </div>
  </div>
</section>

<!-- HİZMETLER -->
<section class="hizmetler" id="hizmetler">
  <div class="si">
    <div class="eyebrow"><div class="eline"></div><span class="etxt">Hizmetlerim</span></div>
    <h2 class="stitle">Nasıl Yardımcı Olabilirim?</h2>
    <div class="divdr"></div>
    <div class="hgrid">
      <div class="hcard2"><div class="hnum">01</div><h3>Konut Alım & Satımı</h3><p>Mersin'de daire, villa ve müstakil ev alım satım süreçlerini hızlı ve güvenli yönetiyorum.</p></div>
      <div class="hcard2"><div class="hnum">02</div><h3>Ticari Gayrimenkul</h3><p>Ofis, dükkan, depo ve fabrika gibi ticari mülklerin alım satım ve kiralanmasında uzman destek.</p></div>
      <div class="hcard2"><div class="hnum">03</div><h3>Kiralama Hizmetleri</h3><p>Uzun veya kısa dönemli kiralama işlemlerinde güvenilir eşleştirme ve sözleşme desteği.</p></div>
      <div class="hcard2"><div class="hnum">04</div><h3>Yatırım Danışmanlığı</h3><p>Mersin gayrimenkul piyasasını yakından takip ederek en karlı yatırım fırsatlarını sunuyorum.</p></div>
      <div class="hcard2"><div class="hnum">05</div><h3>Tapu & Hukuki Destek</h3><p>Tapu devri, ipotek ve hukuki süreçlerde uzman ekibimizle tam destek sağlıyorum.</p></div>
      <div class="hcard2"><div class="hnum">06</div><h3>Ücretsiz Değerleme</h3><p>Mülkünüzün güncel piyasa değerini ücretsiz olarak analiz edip detaylı raporluyorum.</p></div>
    </div>
  </div>
</section>

<!-- HAKKIMDA -->
<section class="hakkimda" id="hakkimda">
  <div class="si">
    <div class="eyebrow"><div class="eline"></div><span class="etxt">Hakkımda</span></div>
    <h2 class="stitle">Tufan Kılınç</h2>
    <div class="divdr"></div>
    <div class="hgrid2">
      <div class="htext">
        <p>Mersin'de <strong>10 yılı aşkın süredir</strong> gayrimenkul sektöründe hizmet vermekteyim. Müşterilerimin hayallerini gerçeğe dönüştürmek için her zaman yanlarında oluyor, dürüst ve şeffaf bir danışmanlık anlayışıyla çalışıyorum.</p>
        <p>Konut, ticari ve yatırım amaçlı gayrimenkul alanlarında <strong>derin bir bilgi birikimine</strong> sahibim. Her müşterinin ihtiyacını dinler, ona özel çözümler üretirim.</p>
        <p>Mersin'in tüm ilçelerinde — özellikle Mezitli, Yenişehir, Toroslar ve Akdeniz'de — güncel piyasa bilgisiyle en doğru rehberliği sunuyorum.</p>
        <a href="https://wa.me/905000000000" class="btn-g" style="margin-top:2rem;display:inline-flex">Tanışalım</a>
      </div>
      <div class="highlights">
        <div class="hl"><div class="hlnum">01</div><div><h4>Lisanslı Danışman</h4><p>SPK onaylı lisans ile faaliyet gösteriyorum</p></div></div>
        <div class="hl"><div class="hlnum">02</div><div><h4>Mersin Uzmanı</h4><p>10+ yıldır yalnızca Mersin pazarına odaklanıyorum</p></div></div>
        <div class="hl"><div class="hlnum">03</div><div><h4>Güven & Şeffaflık</h4><p>Her adımda müşterimle açık iletişim kuruyorum</p></div></div>
        <div class="hl"><div class="hlnum">04</div><div><h4>Hızlı Geri Dönüş</h4><p>WhatsApp üzerinden anında yanıt veriyorum</p></div></div>
      </div>
    </div>
  </div>
</section>

<!-- NEDEN BEN -->
<section class="neden">
  <div class="si">
    <div class="eyebrow"><div class="eline"></div><span class="etxt">Rakamlarla</span></div>
    <h2 class="stitle">Neden Tufan Kılınç?</h2>
    <div class="divdr"></div>
    <div class="ngrid">
      <div class="nitem"><span class="nnum">200+</span><p>Başarılı gayrimenkul işlemi</p></div>
      <div class="nitem"><span class="nnum">10+</span><p>Yıllık sektör deneyimi</p></div>
      <div class="nitem"><span class="nnum">%97</span><p>Müşteri memnuniyet oranı</p></div>
      <div class="nitem" style="border-right:none"><span class="nnum">24s</span><p>WhatsApp geri dönüş garantisi</p></div>
    </div>
  </div>
</section>

<!-- İLETİŞİM -->
<section class="iletisim" id="iletisim">
  <div class="si">
    <div class="eyebrow"><div class="eline"></div><span class="etxt">İletişim</span></div>
    <h2 class="stitle">Hemen Ulaşın</h2>
    <div class="divdr"></div>
    <div class="igrid">
      <div>
        <div class="crows">
          <div class="crow"><div class="clabel">Telefon / WhatsApp</div><div class="cval">+90 500 000 00 00</div></div>
          <div class="crow"><div class="clabel">E-posta</div><div class="cval">tufan@example.com</div></div>
          <div class="crow"><div class="clabel">Konum</div><div class="cval">Mersin, Türkiye</div></div>
        </div>
        <a href="https://wa.me/905000000000" class="wabtn">
          <svg viewBox="0 0 24 24" fill="currentColor" width="20" height="20"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413Z"/></svg>
          WhatsApp'tan Mesaj Gönder
        </a>
      </div>
      <div class="cright">
        <div class="quote">
          <p>"Hayalinizdeki mülkü bulmak için değil, doğru mülkü bulmak için buradayım."</p>
          <cite>— Tufan Kılınç</cite>
        </div>
        <div class="bolgebox">
          <h4>Hizmet Bölgelerim</h4>
          <div class="blist">
            <span class="bolge">Mezitli</span>
            <span class="bolge">Yenişehir</span>
            <span class="bolge">Toroslar</span>
            <span class="bolge">Akdeniz</span>
            <span class="bolge">Silifke</span>
            <span class="bolge">Tarsus</span>
            <span class="bolge">Erdemli</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="flogo">Tufan <span>Kılınç</span></div>
  <p>© 2025 · Mersin Gayrimenkul Danışmanı</p>
</footer>

<!-- WhatsApp FAB -->
<a href="https://wa.me/905000000000" class="wafab" title="WhatsApp">
  <svg viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413Z"/></svg>
</a>

</body>
</html>
