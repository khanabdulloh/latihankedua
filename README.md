<?xml version="1.0" encoding="UTF-8" ?>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gbl' xmlns:data='http://www.google.com/2005/gbl' xmlns:expr='http://www.google.com/2005/gbl'>
<head>
  <meta charset='utf-8'/>
  <meta content='width=device-width, initial-scale=1.0' name='viewport'/>
  <b:include data='blog' name='all-head-content'/>
  <title><data:blog.pageTitle/></title>
  <b:skin><![CDATA[
    body{margin:0;}
  ]]></b:skin>
  <link href='https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700&amp;family=Playfair+Display:wght@600;700&amp;display=swap' rel='stylesheet'/>
  <link href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css' rel='stylesheet'/>
  <style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
  --pri:#1a56db;--pri-d:#1e429f;--pri-l:#ebf0ff;
  --txt:#111827;--muted:#6b7280;
  --bg:#fff;--bg2:#f8fafc;--bg3:#f1f5f9;
  --bdr:#e5e7eb;--r:12px;--rs:8px;--rl:20px;
  --sh:0 1px 3px rgba(0,0,0,.08),0 1px 2px rgba(0,0,0,.04);
  --sh2:0 10px 25px rgba(0,0,0,.12);
}
body{font-family:'Plus Jakarta Sans',sans-serif;color:var(--txt);background:var(--bg);line-height:1.6;font-size:15px}
a{text-decoration:none;color:inherit}
img{max-width:100%}
.topbar{background:var(--pri-d);color:rgba(255,255,255,.9);font-size:12.5px;padding:7px 0}
.topbar-in{max-width:1200px;margin:0 auto;padding:0 20px;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:6px}
.topbar a{color:rgba(255,255,255,.85)}
.topbar a:hover{color:#fff}
.tb-l,.tb-r{display:flex;gap:16px;align-items:center}
.topbar i{margin-right:5px;font-size:11px}
.site-hdr{background:var(--bg);border-bottom:1px solid var(--bdr);position:sticky;top:0;z-index:1000;box-shadow:0 2px 8px rgba(0,0,0,.06)}
.hdr-in{max-width:1200px;margin:0 auto;padding:0 20px;display:flex;align-items:center;justify-content:space-between;height:72px;gap:20px}
.logo-wrap{display:flex;align-items:center;gap:14px;flex-shrink:0}
.logo-ic{width:48px;height:48px;background:linear-gradient(135deg,var(--pri),var(--pri-d));border-radius:12px;display:flex;align-items:center;justify-content:center;color:#fff;font-size:22px;flex-shrink:0}
.logo-name{font-family:'Playfair Display',serif;font-size:17px;font-weight:700;color:var(--pri-d);line-height:1.2}
.logo-sub{font-size:11px;color:var(--muted);font-weight:400}
.main-nav{display:flex;align-items:center;gap:4px}
.main-nav a{padding:8px 14px;border-radius:var(--rs);font-size:14px;font-weight:500;color:var(--txt);transition:all .2s;white-space:nowrap}
.main-nav a:hover{background:var(--pri-l);color:var(--pri)}
.nav-cta{background:var(--pri)!important;color:#fff!important;padding:8px 18px!important;border-radius:8px!important}
.nav-cta:hover{background:var(--pri-d)!important}
.hamburger{display:none;background:none;border:none;font-size:22px;cursor:pointer;color:var(--txt);padding:4px}
.hero{background:linear-gradient(135deg,#1e3a8a,#1a56db 50%,#2563eb);color:#fff;padding:80px 20px;text-align:center;position:relative;overflow:hidden}
.hero-in{max-width:780px;margin:0 auto;position:relative}
.hero-badge{display:inline-flex;align-items:center;gap:6px;background:rgba(255,255,255,.15);border:1px solid rgba(255,255,255,.25);border-radius:100px;padding:5px 14px;font-size:12.5px;font-weight:500;margin-bottom:20px}
.hero h1{font-family:'Playfair Display',serif;font-size:clamp(28px,5vw,48px);font-weight:700;line-height:1.2;margin-bottom:16px}
.hero p{font-size:clamp(14px,2vw,17px);opacity:.88;margin-bottom:32px;max-width:560px;margin-left:auto;margin-right:auto}
.hero-btns{display:flex;gap:12px;justify-content:center;flex-wrap:wrap}
.btn-pri{background:#fff;color:var(--pri);padding:12px 26px;border-radius:10px;font-weight:600;font-size:14px;transition:all .2s;display:inline-flex;align-items:center;gap:8px}
.btn-pri:hover{transform:translateY(-2px);box-shadow:0 8px 20px rgba(0,0,0,.2)}
.btn-out{background:transparent;color:#fff;border:1.5px solid rgba(255,255,255,.5);padding:12px 26px;border-radius:10px;font-weight:500;font-size:14px;transition:all .2s;display:inline-flex;align-items:center;gap:8px}
.btn-out:hover{background:rgba(255,255,255,.1);border-color:#fff}
.stats{background:#fff;border-bottom:1px solid var(--bdr)}
.stats-in{max-width:1200px;margin:0 auto;display:grid;grid-template-columns:repeat(4,1fr)}
.stat-it{padding:24px 20px;text-align:center;border-right:1px solid var(--bdr)}
.stat-it:last-child{border-right:none}
.stat-n{font-size:28px;font-weight:700;color:var(--pri);line-height:1}
.stat-l{font-size:12px;color:var(--muted);margin-top:4px}
.section{padding:64px 20px}
.section-alt{background:var(--bg2)}
.container{max-width:1200px;margin:0 auto}
.sec-hdr{text-align:center;margin-bottom:44px}
.sec-tag{display:inline-block;background:var(--pri-l);color:var(--pri);font-size:12px;font-weight:600;padding:4px 12px;border-radius:100px;margin-bottom:10px;letter-spacing:.5px;text-transform:uppercase}
.sec-title{font-family:'Playfair Display',serif;font-size:clamp(22px,3.5vw,32px);font-weight:700;color:var(--txt);margin-bottom:10px}
.sec-desc{color:var(--muted);font-size:15px;max-width:540px;margin:0 auto}
.cards-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:20px}
.card{background:#fff;border:1px solid var(--bdr);border-radius:var(--r);overflow:hidden;box-shadow:var(--sh);transition:all .25s}
.card:hover{box-shadow:var(--sh2);transform:translateY(-3px)}
.card-img{aspect-ratio:16/9;background:var(--bg3);overflow:hidden;display:flex;align-items:center;justify-content:center}
.card-img img{width:100%;height:100%;object-fit:cover;transition:transform .3s}
.card:hover .card-img img{transform:scale(1.04)}
.card-body{padding:20px}
.card-meta{display:flex;align-items:center;gap:10px;font-size:12px;color:var(--muted);margin-bottom:10px}
.card-tag{background:var(--pri-l);color:var(--pri);padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600}
.card-title{font-weight:600;font-size:15px;margin-bottom:8px;line-height:1.4}
.card-title a:hover{color:var(--pri)}
.card-desc{font-size:13.5px;color:var(--muted);line-height:1.6}
.card-foot{padding:14px 20px;border-top:1px solid var(--bdr);display:flex;justify-content:space-between;align-items:center}
.read-more{font-size:13px;font-weight:600;color:var(--pri);display:flex;align-items:center;gap:5px}
.read-more:hover{gap:8px}
.ann-list{display:flex;flex-direction:column;gap:12px}
.ann-item{background:#fff;border:1px solid var(--bdr);border-radius:var(--rs);padding:16px 20px;display:flex;gap:16px;align-items:flex-start;box-shadow:var(--sh);transition:all .2s}
.ann-item:hover{border-color:var(--pri);box-shadow:0 4px 12px rgba(26,86,219,.1)}
.ann-date{background:var(--pri-l);color:var(--pri);border-radius:var(--rs);padding:8px 12px;text-align:center;min-width:52px;flex-shrink:0;font-weight:600}
.ann-day{font-size:20px;line-height:1}
.ann-mon{font-size:11px}
.ann-content h4{font-size:14px;font-weight:600;margin-bottom:4px}
.ann-content p{font-size:13px;color:var(--muted)}
.ann-badge{font-size:10.5px;font-weight:600;padding:2px 8px;border-radius:100px;display:inline-block;margin-bottom:4px}
.b-red{background:#fef2f2;color:#dc2626}
.b-blue{background:#eff6ff;color:#2563eb}
.b-grn{background:#f0fdf4;color:#16a34a}
.qlink{display:flex;align-items:center;gap:10px;padding:10px 12px;border:1px solid var(--bdr);border-radius:var(--rs);font-size:13.5px;font-weight:500;transition:all .2s;color:var(--txt);margin-bottom:8px}
.qlink:hover{border-color:var(--pri);color:var(--pri)}
.qlink-ic{width:30px;height:30px;border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:13px;flex-shrink:0}
.cal-wrap{background:#fff;border:1px solid var(--bdr);border-radius:var(--rl);overflow:hidden;box-shadow:var(--sh)}
.cal-hdr{background:linear-gradient(135deg,var(--pri-d),var(--pri));color:#fff;padding:24px 28px;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:16px}
.cal-hdr h3{font-family:'Playfair Display',serif;font-size:20px}
.cal-nav-wrap{display:flex;gap:8px;align-items:center}
.cal-btn{background:rgba(255,255,255,.2);border:1px solid rgba(255,255,255,.3);color:#fff;width:34px;height:34px;border-radius:8px;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:14px;transition:background .2s}
.cal-btn:hover{background:rgba(255,255,255,.3)}
.cal-yr{font-size:15px;font-weight:600;padding:0 8px}
.cal-body{padding:24px 28px}
.month-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:20px;margin-bottom:28px}
.month-card{border:1px solid var(--bdr);border-radius:var(--rs);overflow:hidden}
.month-head{background:var(--bg3);padding:8px 12px;font-size:13px;font-weight:600;color:var(--pri-d);text-align:center}
.mini-cal{width:100%;padding:6px;border-collapse:collapse}
.mini-cal th{font-size:10.5px;color:var(--muted);padding:4px 2px;text-align:center;font-weight:500}
.mini-cal td{font-size:11.5px;text-align:center;padding:3px 2px;border-radius:4px}
.mini-cal td.hol{background:#fef2f2;color:#dc2626;font-weight:600}
.mini-cal td.ujn{background:#faf5ff;color:#7c3aed;font-weight:600}
.mini-cal td.evt{background:#eff6ff;color:#2563eb;font-weight:600}
.mini-cal td.lsm{background:#f0fdf4;color:#16a34a;font-weight:600}
.mini-cal td.tdy{background:var(--pri);color:#fff!important;font-weight:700;border-radius:50%}
.mini-cal td.sun{color:#dc2626}
.mini-cal td.emp{color:#d1d5db}
.cal-legend{display:flex;gap:16px;flex-wrap:wrap;padding-top:20px;border-top:1px solid var(--bdr)}
.leg-it{display:flex;align-items:center;gap:6px;font-size:12.5px;color:var(--muted)}
.leg-dot{width:12px;height:12px;border-radius:3px;flex-shrink:0}
.d-hol{background:#fef2f2;border:1.5px solid #dc2626}
.d-ujn{background:#faf5ff;border:1.5px solid #7c3aed}
.d-evt{background:#eff6ff;border:1.5px solid #2563eb}
.d-lsm{background:#f0fdf4;border:1.5px solid #16a34a}
.cal-ev-list{margin-top:24px}
.cal-ev-list h4{font-size:14px;font-weight:600;margin-bottom:14px;color:var(--txt)}
.cal-ev-it{display:flex;gap:12px;align-items:center;padding:10px 0;border-bottom:1px solid var(--bdr);font-size:13px;flex-wrap:wrap}
.cal-ev-it:last-child{border-bottom:none}
.cal-ev-dt{font-weight:600;color:var(--pri);min-width:120px;font-size:12px}
.cal-ev-nm{color:var(--txt);flex:1}
.cal-ev-tp{font-size:10px;font-weight:600;padding:2px 7px;border-radius:3px;white-space:nowrap}
.fas-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(160px,1fr));gap:16px}
.fas-card{background:#fff;border:1px solid var(--bdr);border-radius:var(--r);padding:24px 16px;text-align:center;box-shadow:var(--sh);transition:all .25s}
.fas-card:hover{border-color:var(--pri);box-shadow:0 8px 20px rgba(26,86,219,.1);transform:translateY(-2px)}
.fas-ic{width:52px;height:52px;background:var(--pri-l);border-radius:14px;display:flex;align-items:center;justify-content:center;font-size:22px;color:var(--pri);margin:0 auto 12px}
.fas-card h4{font-size:13.5px;font-weight:600;margin-bottom:4px}
.fas-card p{font-size:11.5px;color:var(--muted)}
.eks-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:16px}
.eks-card{background:#fff;border:1px solid var(--bdr);border-radius:var(--r);padding:20px;box-shadow:var(--sh);display:flex;gap:14px;align-items:center;transition:all .2s}
.eks-card:hover{border-color:var(--pri)}
.eks-ic{width:44px;height:44px;flex-shrink:0;border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:22px}
.eks-card h4{font-size:13.5px;font-weight:600;margin-bottom:3px}
.eks-card p{font-size:11.5px;color:var(--muted)}
.guru-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(180px,1fr));gap:20px}
.guru-card{background:#fff;border:1px solid var(--bdr);border-radius:var(--r);padding:24px 16px;text-align:center;box-shadow:var(--sh);transition:all .25s}
.guru-card:hover{box-shadow:var(--sh2);transform:translateY(-3px)}
.guru-av{width:80px;height:80px;border-radius:50%;margin:0 auto 14px;border:3px solid var(--pri-l);overflow:hidden;display:flex;align-items:center;justify-content:center;font-size:24px;font-weight:700}
.guru-card h4{font-size:14px;font-weight:600;margin-bottom:4px}
.guru-mapel{font-size:12px;color:var(--pri);font-weight:500}
.guru-jabatan{font-size:11.5px;color:var(--muted);margin-top:2px}
.kontak-grid{display:grid;grid-template-columns:1fr 1fr;gap:32px;align-items:start}
.kontak-it{display:flex;gap:14px;align-items:flex-start;margin-bottom:18px}
.kontak-ic{width:40px;height:40px;flex-shrink:0;background:var(--pri-l);color:var(--pri);border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:16px}
.kontak-it h5{font-size:12px;color:var(--muted);margin-bottom:2px}
.kontak-it p{font-size:14px;font-weight:500}
.map-box{border-radius:var(--r);overflow:hidden;border:1px solid var(--bdr);height:300px;background:var(--bg3);display:flex;align-items:center;justify-content:center;color:var(--muted);font-size:14px;text-align:center}
.soc-btn{width:36px;height:36px;border-radius:8px;background:var(--pri-l);display:flex;align-items:center;justify-content:center;color:var(--pri);font-size:15px;transition:all .2s}
.soc-btn:hover{background:var(--pri);color:#fff}
.content-wrap{max-width:1200px;margin:0 auto;padding:48px 20px;display:grid;grid-template-columns:1fr 320px;gap:32px;align-items:start}
.sw{background:#fff;border:1px solid var(--bdr);border-radius:var(--r);padding:22px;margin-bottom:20px;box-shadow:var(--sh)}
.sw h3{font-size:15px;font-weight:600;margin-bottom:16px;padding-bottom:12px;border-bottom:1px solid var(--bdr)}
.srch-box{display:flex;gap:8px}
.srch-box input{flex:1;padding:9px 14px;border:1px solid var(--bdr);border-radius:var(--rs);font-size:13.5px;font-family:inherit;outline:none}
.srch-box input:focus{border-color:var(--pri)}
.srch-box button{background:var(--pri);color:#fff;border:none;border-radius:var(--rs);padding:9px 14px;cursor:pointer;font-size:14px}
.cat-list{list-style:none}
.cat-list li{padding:8px 0;border-bottom:1px solid var(--bdr);display:flex;justify-content:space-between;align-items:center;font-size:13.5px}
.cat-list li:last-child{border-bottom:none}
.cat-list a:hover{color:var(--pri)}
.cat-ct{background:var(--bg3);color:var(--muted);font-size:11px;font-weight:600;padding:2px 7px;border-radius:100px}
.pop-post{display:flex;gap:12px;padding:10px 0;border-bottom:1px solid var(--bdr)}
.pop-post:last-child{border-bottom:none}
.pop-thumb{width:60px;height:54px;border-radius:6px;background:var(--bg3);overflow:hidden;flex-shrink:0}
.pop-thumb img{width:100%;height:100%;object-fit:cover}
.pop-info h5{font-size:12.5px;font-weight:600;line-height:1.4;margin-bottom:4px}
.pop-info span{font-size:11px;color:var(--muted)}
.post-page{max-width:760px;margin:0 auto;padding:48px 20px}
.post-cat{display:inline-block;background:var(--pri-l);color:var(--pri);font-size:12px;font-weight:600;padding:3px 10px;border-radius:4px;margin-bottom:12px}
.post-title{font-family:'Playfair Display',serif;font-size:clamp(24px,4vw,36px);font-weight:700;line-height:1.25;margin-bottom:16px}
.post-meta{display:flex;gap:16px;align-items:center;flex-wrap:wrap;color:var(--muted);font-size:13px;margin-bottom:24px}
.post-av{width:32px;height:32px;border-radius:50%;background:var(--pri-l);display:inline-flex;align-items:center;justify-content:center;color:var(--pri);font-size:13px;font-weight:600}
.post-img{border-radius:var(--r);overflow:hidden;margin-bottom:32px}
.post-img img{width:100%;height:auto}
.post-body{font-size:16px;line-height:1.8;color:#1f2937}
.post-body h2,.post-body h3{font-family:'Playfair Display',serif;margin:28px 0 12px}
.post-body p{margin-bottom:18px}
.post-body ul,.post-body ol{padding-left:24px;margin-bottom:18px}
.post-body li{margin-bottom:6px}
.post-body blockquote{border-left:3px solid var(--pri);padding:12px 20px;margin:24px 0;background:var(--pri-l);border-radius:0 var(--rs) var(--rs) 0;font-style:italic;color:var(--pri-d)}
.site-ftr{background:#0f172a;color:rgba(255,255,255,.75);padding:60px 20px 0}
.ftr-grid{max-width:1200px;margin:0 auto;display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:40px;padding-bottom:48px}
.ftr-soc{display:flex;gap:10px;margin-top:20px}
.ftr-soc-btn{width:36px;height:36px;border-radius:8px;background:rgba(255,255,255,.1);display:flex;align-items:center;justify-content:center;color:rgba(255,255,255,.7);font-size:15px;transition:all .2s}
.ftr-soc-btn:hover{background:var(--pri);color:#fff}
.ftr-col h4{color:#fff;font-size:14px;font-weight:600;margin-bottom:18px}
.ftr-links{list-style:none}
.ftr-links li{margin-bottom:10px}
.ftr-links a{font-size:13.5px;transition:color .2s}
.ftr-links a:hover{color:#fff}
.ftr-bot{max-width:1200px;margin:0 auto;padding:20px 0;border-top:1px solid rgba(255,255,255,.08);display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:10px;font-size:12.5px}
.mob-nav{display:none;position:fixed;top:0;left:0;right:0;bottom:0;background:#fff;z-index:2000;padding:20px;flex-direction:column;overflow-y:auto}
.mob-nav.open{display:flex}
.mob-nav-hdr{display:flex;justify-content:space-between;align-items:center;margin-bottom:32px}
.close-nav{background:none;border:none;font-size:24px;cursor:pointer;color:var(--txt)}
.mob-links{display:flex;flex-direction:column;gap:4px}
.mob-links a{padding:13px 16px;border-radius:var(--rs);font-size:15px;font-weight:500;color:var(--txt);transition:background .2s}
.mob-links a:hover{background:var(--bg2)}
#sc-top{position:fixed;bottom:24px;right:24px;background:var(--pri);color:#fff;width:42px;height:42px;border-radius:10px;border:none;cursor:pointer;display:none;align-items:center;justify-content:center;font-size:16px;box-shadow:0 4px 12px rgba(26,86,219,.4);transition:all .2s;z-index:500}
#sc-top.show{display:flex}
#sc-top:hover{transform:translateY(-2px)}
.blog-pager{padding:32px 20px;max-width:760px;margin:0 auto;display:flex;justify-content:space-between;gap:12px}
.blog-pager a{padding:10px 20px;border-radius:var(--rs);background:#fff;border:1px solid var(--bdr);font-size:13.5px;font-weight:500;color:var(--txt);display:flex;align-items:center;gap:8px;box-shadow:var(--sh);transition:all .2s}
.blog-pager a:hover{border-color:var(--pri);color:var(--pri)}
.comments{max-width:760px;margin:0 auto;padding:0 20px 48px}
@media(max-width:1024px){
  .ftr-grid{grid-template-columns:1fr 1fr}
  .kontak-grid{grid-template-columns:1fr}
  .content-wrap{grid-template-columns:1fr}
}
@media(max-width:768px){
  .stats-in{grid-template-columns:repeat(2,1fr)}
  .main-nav{display:none}
  .hamburger{display:flex;align-items:center}
  .ftr-grid{grid-template-columns:1fr}
  .month-grid{grid-template-columns:1fr 1fr}
  .tb-r{display:none}
  .hero{padding:56px 20px}
  .ann-pg{grid-template-columns:1fr}
}
@media(max-width:500px){
  .month-grid{grid-template-columns:1fr}
  .fas-grid{grid-template-columns:repeat(2,1fr)}
  .guru-grid{grid-template-columns:repeat(2,1fr)}
}
  </style>
</head>
<body>

<div class='topbar'>
  <div class='topbar-in'>
    <div class='tb-l'>
      <span><i class='fa fa-map-marker-alt'/>Jl. Contoh No. 1, Kota Anda</span>
      <span><i class='fa fa-clock'/>Senin-Sabtu: 07.00-15.00 WIB</span>
    </div>
    <div class='tb-r'>
      <a href='tel:+62812345678'><i class='fa fa-phone'/>+62 812-345-678</a>
      <a href='mailto:info@sekolah.sch.id'><i class='fa fa-envelope'/>info@sekolah.sch.id</a>
    </div>
  </div>
</div>

<header class='site-hdr'>
  <div class='hdr-in'>
    <div class='logo-wrap'>
      <div class='logo-ic'><i class='fa fa-graduation-cap'/></div>
      <div>
        <div class='logo-name'><data:blog.title/></div>
        <div class='logo-sub'>Terakreditasi A - Sejak 1970</div>
      </div>
    </div>
    <nav class='main-nav'>
      <a href='/'>Beranda</a>
      <a href='/p/profil.html'>Profil</a>
      <a href='/p/akademik.html'>Akademik</a>
      <a href='/p/ekstrakurikuler.html'>Ekskul</a>
      <a href='/p/fasilitas.html'>Fasilitas</a>
      <a href='/'>Berita</a>
      <a class='nav-cta' href='/p/kontak.html'>Hubungi Kami</a>
    </nav>
    <button class='hamburger' id='hamburger'><i class='fa fa-bars'/></button>
  </div>
</header>

<div class='mob-nav' id='mob-nav'>
  <div class='mob-nav-hdr'>
    <div class='logo-wrap'>
      <div class='logo-ic' style='width:40px;height:40px;font-size:18px;'><i class='fa fa-graduation-cap'/></div>
      <div><div class='logo-name'><data:blog.title/></div></div>
    </div>
    <button class='close-nav' id='close-nav'>&#x2715;</button>
  </div>
  <div class='mob-links'>
    <a href='/'>Beranda</a>
    <a href='/p/profil.html'>Profil Sekolah</a>
    <a href='/p/akademik.html'>Akademik</a>
    <a href='/p/ekstrakurikuler.html'>Ekstrakurikuler</a>
    <a href='/p/fasilitas.html'>Fasilitas</a>
    <a href='/'>Berita</a>
    <a href='#kalender'>Kalender Pendidikan</a>
    <a href='/p/kontak.html'>Kontak</a>
  </div>
</div>

<b:section class='main' id='main' maxwidgets='1' showaddelement='no'>
<b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='1'>
<b:widget-settings/>
<b:includable id='main' var='top'>

<b:if cond='data:blog.pageType == &quot;index&quot;'>

<section class='hero'>
  <div class='hero-in'>
    <div class='hero-badge'><i class='fa fa-star' style='font-size:11px;color:#fbbf24;'/> Sekolah Unggulan Terpercaya</div>
    <h1>Membangun Generasi Cerdas &amp; Berkarakter Mulia</h1>
    <p>Kami berkomitmen memberikan pendidikan berkualitas tinggi yang memadukan ilmu pengetahuan, teknologi, dan nilai-nilai karakter bangsa.</p>
    <div class='hero-btns'>
      <a class='btn-pri' href='/p/profil.html'><i class='fa fa-book-open'/> Profil Sekolah</a>
      <a class='btn-out' href='/p/kontak.html'><i class='fa fa-paper-plane'/> Daftar Sekarang</a>
    </div>
  </div>
</section>

<div class='stats'>
  <div class='stats-in'>
    <div class='stat-it'><div class='stat-n'>1.240+</div><div class='stat-l'>Siswa Aktif</div></div>
    <div class='stat-it'><div class='stat-n'>86</div><div class='stat-l'>Tenaga Pendidik</div></div>
    <div class='stat-it'><div class='stat-n'>98%</div><div class='stat-l'>Tingkat Kelulusan</div></div>
    <div class='stat-it'><div class='stat-n'>54 Thn</div><div class='stat-l'>Pengalaman Kami</div></div>
  </div>
</div>

<section class='section'>
  <div class='container'>
    <div class='sec-hdr'>
      <div class='sec-tag'>Terkini</div>
      <div class='sec-title'>Berita &amp; Informasi</div>
      <div class='sec-desc'>Ikuti perkembangan terbaru kegiatan dan prestasi sekolah kami.</div>
    </div>
    <div class='cards-grid'>
      <b:loop values='data:posts' var='post'>
      <div class='card'>
        <div class='card-img'>
          <b:if cond='data:post.featuredImage'>
            <img alt='' expr:src='data:post.featuredImage'/>
          <b:else/>
            <i class='fa fa-newspaper' style='font-size:36px;color:#93c5fd;'/>
          </b:if>
        </div>
        <div class='card-body'>
          <div class='card-meta'>
            <b:if cond='data:post.labels'><span class='card-tag'><data:post.labels.first.name/></span></b:if>
            <span><data:post.date.long/></span>
          </div>
          <div class='card-title'><a expr:href='data:post.url'><data:post.title/></a></div>
          <div class='card-desc'><data:post.snippet/></div>
        </div>
        <div class='card-foot'>
          <span style='font-size:12px;color:var(--muted);'><i class='fa fa-user' style='margin-right:5px;'/><data:post.author.name/></span>
          <a class='read-more' expr:href='data:post.url'>Baca <i class='fa fa-arrow-right'/></a>
        </div>
      </div>
      </b:loop>
    </div>
  </div>
</section>

<section class='section section-alt'>
  <div class='container'>
    <div style='display:grid;grid-template-columns:1fr 320px;gap:40px;' class='ann-pg'>
      <div>
        <div class='sec-tag'>Terbaru</div>
        <div class='sec-title' style='text-align:left;margin-bottom:24px;'>Pengumuman</div>
        <div class='ann-list'>
          <div class='ann-item'>
            <div class='ann-date'><div class='ann-day'>15</div><div class='ann-mon'>Mei</div></div>
            <div class='ann-content'><span class='ann-badge b-red'>Penting</span><h4>Jadwal Ujian Akhir Semester Genap 2024/2025</h4><p>Ujian Akhir Semester Genap dilaksanakan 15-22 Mei 2025.</p></div>
          </div>
          <div class='ann-item'>
            <div class='ann-date'><div class='ann-day'>08</div><div class='ann-mon'>Mei</div></div>
            <div class='ann-content'><span class='ann-badge b-blue'>Informasi</span><h4>PPDB Online Tahun Ajaran 2025/2026 Dibuka</h4><p>Pendaftaran PPDB TA 2025/2026 dibuka online mulai 8 Mei 2025.</p></div>
          </div>
          <div class='ann-item'>
            <div class='ann-date'><div class='ann-day'>02</div><div class='ann-mon'>Mei</div></div>
            <div class='ann-content'><span class='ann-badge b-grn'>Kegiatan</span><h4>Peringatan Hari Pendidikan Nasional</h4><p>Upacara Hardiknas dilaksanakan pada 2 Mei 2025 pukul 07.00 WIB.</p></div>
          </div>
          <div class='ann-item'>
            <div class='ann-date'><div class='ann-day'>18</div><div class='ann-mon'>Apr</div></div>
            <div class='ann-content'><span class='ann-badge b-blue'>Informasi</span><h4>Libur Wafat Isa Al Masih</h4><p>18 April 2025 ditetapkan sebagai hari libur nasional.</p></div>
          </div>
        </div>
      </div>
      <div>
        <div style='background:#fff;border:1px solid var(--bdr);border-radius:var(--r);padding:22px;box-shadow:var(--sh);'>
          <h3 style='font-size:15px;font-weight:600;margin-bottom:16px;padding-bottom:12px;border-bottom:1px solid var(--bdr);'><i class='fa fa-link' style='margin-right:8px;color:var(--pri);'/>Tautan Cepat</h3>
          <a class='qlink' href='/p/ppdb.html'><div class='qlink-ic' style='background:var(--pri-l);color:var(--pri);'><i class='fa fa-user-plus'/></div>Daftar PPDB Online</a>
          <a class='qlink' href='/p/jadwal.html'><div class='qlink-ic' style='background:#f0fdf4;color:#16a34a;'><i class='fa fa-calendar'/></div>Jadwal Pelajaran</a>
          <a class='qlink' href='/p/nilai.html'><div class='qlink-ic' style='background:#faf5ff;color:#7c3aed;'><i class='fa fa-chart-bar'/></div>Cek Nilai Siswa</a>
          <a class='qlink' href='/p/ekskul.html'><div class='qlink-ic' style='background:#fff7ed;color:#ea580c;'><i class='fa fa-trophy'/></div>Kegiatan Ekskul</a>
          <a class='qlink' href='/p/perpus.html'><div class='qlink-ic' style='background:#fef2f2;color:#dc2626;'><i class='fa fa-book'/></div>E-Perpustakaan</a>
        </div>
      </div>
    </div>
  </div>
</section>

<section class='section' id='kalender'>
  <div class='container'>
    <div class='sec-hdr'>
      <div class='sec-tag'>Agenda</div>
      <div class='sec-title'>Kalender Pendidikan Indonesia</div>
      <div class='sec-desc'>Kalender akademik, hari libur nasional, dan agenda kegiatan sekolah.</div>
    </div>
    <div class='cal-wrap'>
      <div class='cal-hdr'>
        <div>
          <h3 id='cal-title'>Kalender Pendidikan 2024/2025</h3>
          <div style='font-size:13px;opacity:.8;margin-top:4px;'>Tahun Ajaran Aktif</div>
        </div>
        <div class='cal-nav-wrap'>
          <button class='cal-btn' id='prev-yr'><i class='fa fa-chevron-left'/></button>
          <span class='cal-yr' id='yr-disp'>2024/2025</span>
          <button class='cal-btn' id='next-yr'><i class='fa fa-chevron-right'/></button>
        </div>
      </div>
      <div class='cal-body'>
        <div class='month-grid' id='month-grid'></div>
        <div class='cal-legend'>
          <div class='leg-it'><div class='leg-dot d-hol'/>Libur Nasional / Hari Besar</div>
          <div class='leg-it'><div class='leg-dot d-ujn'/>Ujian / Asesmen</div>
          <div class='leg-it'><div class='leg-dot d-evt'/>Kegiatan Sekolah</div>
          <div class='leg-it'><div class='leg-dot d-lsm'/>Libur Semester</div>
        </div>
        <div class='cal-ev-list'>
          <h4><i class='fa fa-calendar-check' style='color:var(--pri);margin-right:8px;'/>Agenda Penting Tahun Ajaran <span id='agenda-yr'>2024/2025</span></h4>
          <div id='ev-list'></div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class='section section-alt'>
  <div class='container'>
    <div class='sec-hdr'>
      <div class='sec-tag'>Fasilitas</div>
      <div class='sec-title'>Sarana &amp; Prasarana Unggulan</div>
      <div class='sec-desc'>Fasilitas modern untuk mendukung proses belajar mengajar yang optimal.</div>
    </div>
    <div class='fas-grid'>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-laptop-code'/></div><h4>Lab Komputer</h4><p>40 unit terbaru</p></div>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-flask'/></div><h4>Lab IPA</h4><p>Alat lengkap</p></div>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-book'/></div><h4>Perpustakaan</h4><p>10.000+ koleksi</p></div>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-running'/></div><h4>Lapangan Olahraga</h4><p>Multi-fungsi</p></div>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-mosque'/></div><h4>Mushola</h4><p>Kap. 200 orang</p></div>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-utensils'/></div><h4>Kantin Sehat</h4><p>Higienis &amp; bergizi</p></div>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-wifi'/></div><h4>WiFi Gratis</h4><p>Seluruh area</p></div>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-bus'/></div><h4>Antar Jemput</h4><p>Area terjangkau</p></div>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-theater-masks'/></div><h4>Aula Serbaguna</h4><p>Kap. 500 orang</p></div>
      <div class='fas-card'><div class='fas-ic'><i class='fa fa-medkit'/></div><h4>UKS</h4><p>Tenaga medis</p></div>
    </div>
  </div>
</section>

<section class='section'>
  <div class='container'>
    <div class='sec-hdr'>
      <div class='sec-tag'>Pengembangan Diri</div>
      <div class='sec-title'>Ekstrakurikuler</div>
      <div class='sec-desc'>Berbagai kegiatan untuk mengembangkan bakat dan minat siswa.</div>
    </div>
    <div class='eks-grid'>
      <div class='eks-card'><div class='eks-ic' style='background:#eff6ff;'>&#x26BD;</div><div><h4>Sepak Bola</h4><p>Selasa &amp; Kamis</p></div></div>
      <div class='eks-card'><div class='eks-ic' style='background:#f0fdf4;'>&#x1F3AD;</div><div><h4>Teater</h4><p>Senin &amp; Rabu</p></div></div>
      <div class='eks-card'><div class='eks-ic' style='background:#faf5ff;'>&#x1F3B5;</div><div><h4>Paduan Suara</h4><p>Jumat</p></div></div>
      <div class='eks-card'><div class='eks-ic' style='background:#fef2f2;'>&#x1F94B;</div><div><h4>Pencak Silat</h4><p>Sabtu</p></div></div>
      <div class='eks-card'><div class='eks-ic' style='background:#fff7ed;'>&#x1F3A8;</div><div><h4>Seni Lukis</h4><p>Rabu</p></div></div>
      <div class='eks-card'><div class='eks-ic' style='background:#f0fdf4;'>&#x265F;</div><div><h4>Catur</h4><p>Kamis</p></div></div>
      <div class='eks-card'><div class='eks-ic' style='background:#eff6ff;'>&#x1F916;</div><div><h4>Robotik</h4><p>Selasa</p></div></div>
      <div class='eks-card'><div class='eks-ic' style='background:#faf5ff;'>&#x1F4F0;</div><div><h4>Jurnalistik</h4><p>Senin</p></div></div>
    </div>
  </div>
</section>

<section class='section section-alt'>
  <div class='container'>
    <div class='sec-hdr'>
      <div class='sec-tag'>Tim Kami</div>
      <div class='sec-title'>Tenaga Pendidik Profesional</div>
      <div class='sec-desc'>Guru-guru berpengalaman dan berdedikasi untuk kemajuan siswa.</div>
    </div>
    <div class='guru-grid'>
      <div class='guru-card'><div class='guru-av' style='background:linear-gradient(135deg,#dbeafe,#bfdbfe);color:#1d4ed8;'>AS</div><h4>Ahmad Suherman, S.Pd.</h4><div class='guru-mapel'>Matematika</div><div class='guru-jabatan'>Wakasek Kurikulum</div></div>
      <div class='guru-card'><div class='guru-av' style='background:linear-gradient(135deg,#dcfce7,#bbf7d0);color:#15803d;'>SR</div><h4>Siti Rahmawati, M.Pd.</h4><div class='guru-mapel'>Bahasa Indonesia</div><div class='guru-jabatan'>Kepala Sekolah</div></div>
      <div class='guru-card'><div class='guru-av' style='background:linear-gradient(135deg,#fae8ff,#e9d5ff);color:#7e22ce;'>DP</div><h4>Dian Pratama, S.Si.</h4><div class='guru-mapel'>IPA / Fisika</div><div class='guru-jabatan'>Guru Senior</div></div>
      <div class='guru-card'><div class='guru-av' style='background:linear-gradient(135deg,#fef3c7,#fde68a);color:#b45309;'>RN</div><h4>Rina Nuraini, S.Kom.</h4><div class='guru-mapel'>Informatika</div><div class='guru-jabatan'>Koordinator Lab TI</div></div>
      <div class='guru-card'><div class='guru-av' style='background:linear-gradient(135deg,#fee2e2,#fecaca);color:#b91c1c;'>BW</div><h4>Budi Wijaya, S.Pd.</h4><div class='guru-mapel'>PJOK</div><div class='guru-jabatan'>Wali Kelas IX A</div></div>
      <div class='guru-card'><div class='guru-av' style='background:linear-gradient(135deg,#e0f2fe,#bae6fd);color:#0369a1;'>LH</div><h4>Linda Handayani, M.A.</h4><div class='guru-mapel'>Bahasa Inggris</div><div class='guru-jabatan'>Wali Kelas VIII B</div></div>
    </div>
  </div>
</section>

<section class='section'>
  <div class='container'>
    <div class='sec-hdr'>
      <div class='sec-tag'>Hubungi Kami</div>
      <div class='sec-title'>Informasi Kontak</div>
    </div>
    <div class='kontak-grid'>
      <div>
        <div class='kontak-it'><div class='kontak-ic'><i class='fa fa-map-marker-alt'/></div><div><h5>Alamat</h5><p>Jl. Pendidikan No. 1, Kecamatan Anda, Kota Anda 12345</p></div></div>
        <div class='kontak-it'><div class='kontak-ic'><i class='fa fa-phone'/></div><div><h5>Telepon</h5><p>(022) 1234-5678 / +62 812-345-6789</p></div></div>
        <div class='kontak-it'><div class='kontak-ic'><i class='fa fa-envelope'/></div><div><h5>Email</h5><p>info@sekolah.sch.id</p></div></div>
        <div class='kontak-it'><div class='kontak-ic'><i class='fa fa-clock'/></div><div><h5>Jam Layanan</h5><p>Senin - Sabtu: 07.00 - 15.00 WIB</p></div></div>
        <div style='display:flex;gap:10px;margin-top:8px;'>
          <a class='soc-btn' href='#'><i class='fab fa-facebook-f'/></a>
          <a class='soc-btn' href='#'><i class='fab fa-instagram'/></a>
          <a class='soc-btn' href='#'><i class='fab fa-youtube'/></a>
          <a class='soc-btn' href='#'><i class='fab fa-twitter'/></a>
        </div>
      </div>
      <div class='map-box'>
        <div>
          <i class='fa fa-map-marked-alt' style='font-size:36px;color:#93c5fd;display:block;margin-bottom:12px;'/>
          <p>Ganti dengan embed Google Maps sekolah Anda</p>
          <a href='https://maps.google.com' style='color:var(--pri);font-size:13px;font-weight:600;margin-top:8px;display:inline-block;' target='_blank'>Lihat di Google Maps</a>
        </div>
      </div>
    </div>
  </div>
</section>

<b:else/>

<div class='content-wrap'>
  <div>
    <b:loop values='data:posts' var='post'>
    <article class='post-page'>
      <b:if cond='data:post.labels'><span class='post-cat'><data:post.labels.first.name/></span></b:if>
      <h1 class='post-title'><data:post.title/></h1>
      <div class='post-meta'>
        <span class='post-av'>A</span>
        <span><data:post.author.name/></span>
        <span>&#xB7;</span>
        <span><data:post.date.long/></span>
      </div>
      <b:if cond='data:post.featuredImage'>
        <div class='post-img'><img alt='' expr:src='data:post.featuredImage'/></div>
      </b:if>
      <div class='post-body'><data:post.body/></div>
    </article>
    <b:include data='post' name='comments'/>
    </b:loop>
    <div class='blog-pager'>
      <b:if cond='data:newerPageUrl'><a expr:href='data:newerPageUrl'><i class='fa fa-arrow-left'/> Lebih Baru</a></b:if>
      <b:if cond='data:olderPageUrl'><a expr:href='data:olderPageUrl'>Lebih Lama <i class='fa fa-arrow-right'/></a></b:if>
    </div>
  </div>
  <aside>
    <div class='sw'>
      <h3>Cari Artikel</h3>
      <div class='srch-box'>
        <input placeholder='Cari...' type='text'/>
        <button><i class='fa fa-search'/></button>
      </div>
    </div>
    <div class='sw'>
      <h3>Kategori</h3>
      <ul class='cat-list'>
        <li><a href='/search/label/Berita'>Berita</a><span class='cat-ct'>12</span></li>
        <li><a href='/search/label/Akademik'>Akademik</a><span class='cat-ct'>8</span></li>
        <li><a href='/search/label/Prestasi'>Prestasi</a><span class='cat-ct'>15</span></li>
        <li><a href='/search/label/Pengumuman'>Pengumuman</a><span class='cat-ct'>20</span></li>
        <li><a href='/search/label/Kegiatan'>Kegiatan</a><span class='cat-ct'>9</span></li>
      </ul>
    </div>
    <div class='sw'>
      <h3>Artikel Populer</h3>
      <div class='pop-post'><div class='pop-thumb' style='background:linear-gradient(135deg,#dbeafe,#bfdbfe);'/><div class='pop-info'><h5>Tips Belajar Efektif Menghadapi Ujian</h5><span>2 Mei 2025</span></div></div>
      <div class='pop-post'><div class='pop-thumb' style='background:linear-gradient(135deg,#dcfce7,#bbf7d0);'/><div class='pop-info'><h5>Siswa Raih Juara Olimpiade Sains Nasional</h5><span>28 Apr 2025</span></div></div>
      <div class='pop-post'><div class='pop-thumb' style='background:linear-gradient(135deg,#fae8ff,#e9d5ff);'/><div class='pop-info'><h5>Program Adiwiyata: Sekolah Peduli Lingkungan</h5><span>20 Apr 2025</span></div></div>
    </div>
  </aside>
</div>

</b:if>

</b:includable>
<b:includable id='comments' var='post'>
  <div class='comments'>
    <b:if cond='data:post.allowComments'>
      <b:include name='comment-form'/>
    </b:if>
  </div>
</b:includable>
</b:widget>
</b:section>

<footer class='site-ftr'>
  <div class='ftr-grid'>
    <div>
      <div class='logo-wrap'>
        <div class='logo-ic'><i class='fa fa-graduation-cap'/></div>
        <div>
          <div class='logo-name' style='color:#fff;'><data:blog.title/></div>
          <div class='logo-sub' style='color:rgba(255,255,255,.5);'>Terakreditasi A - Sejak 1970</div>
        </div>
      </div>
      <p style='font-size:13.5px;line-height:1.7;margin-top:16px;'>Sekolah kami berkomitmen mencetak generasi penerus bangsa yang cerdas, berkarakter, dan siap menghadapi tantangan global.</p>
      <div class='ftr-soc'>
        <a class='ftr-soc-btn' href='#'><i class='fab fa-facebook-f'/></a>
        <a class='ftr-soc-btn' href='#'><i class='fab fa-instagram'/></a>
        <a class='ftr-soc-btn' href='#'><i class='fab fa-youtube'/></a>
        <a class='ftr-soc-btn' href='#'><i class='fab fa-twitter'/></a>
        <a class='ftr-soc-btn' href='#'><i class='fab fa-tiktok'/></a>
      </div>
    </div>
    <div>
      <h4>Navigasi</h4>
      <ul class='ftr-links'>
        <li><a href='/'>Beranda</a></li>
        <li><a href='/p/profil.html'>Profil Sekolah</a></li>
        <li><a href='/p/visi-misi.html'>Visi &amp; Misi</a></li>
        <li><a href='/p/sejarah.html'>Sejarah</a></li>
        <li><a href='/p/struktur.html'>Struktur Organisasi</a></li>
      </ul>
    </div>
    <div>
      <h4>Akademik</h4>
      <ul class='ftr-links'>
        <li><a href='/p/kurikulum.html'>Kurikulum</a></li>
        <li><a href='/p/jadwal.html'>Jadwal Pelajaran</a></li>
        <li><a href='/p/ppdb.html'>PPDB Online</a></li>
        <li><a href='/p/ekstrakurikuler.html'>Ekstrakurikuler</a></li>
        <li><a href='/p/prestasi.html'>Prestasi Siswa</a></li>
      </ul>
    </div>
    <div>
      <h4>Informasi</h4>
      <ul class='ftr-links'>
        <li><a href='/'>Berita Terbaru</a></li>
        <li><a href='/p/pengumuman.html'>Pengumuman</a></li>
        <li><a href='#kalender'>Kalender Pendidikan</a></li>
        <li><a href='/p/galeri.html'>Galeri Foto</a></li>
        <li><a href='/p/kontak.html'>Kontak Kami</a></li>
      </ul>
    </div>
  </div>
  <div class='ftr-bot'>
    <span>&#169; <span id='yr-ftr'/>&#160;<data:blog.title/>. Hak Cipta Dilindungi.</span>
    <span>Untuk kemajuan pendidikan Indonesia &#183; <a href='/p/kebijakan-privasi.html'>Kebijakan Privasi</a></span>
  </div>
</footer>

<button id='sc-top'><i class='fa fa-arrow-up'/></button>

<script type='text/javascript'>
//<![CDATA[
(function(){
  // Mobile Nav
  var hbg=document.getElementById('hamburger');
  var mnav=document.getElementById('mob-nav');
  var cnav=document.getElementById('close-nav');
  if(hbg)hbg.addEventListener('click',function(){mnav.classList.add('open');document.body.style.overflow='hidden';});
  if(cnav)cnav.addEventListener('click',function(){mnav.classList.remove('open');document.body.style.overflow='';});

  // Scroll Top
  var sct=document.getElementById('sc-top');
  if(sct){
    window.addEventListener('scroll',function(){sct.classList.toggle('show',window.scrollY>400);});
    sct.addEventListener('click',function(){window.scrollTo({top:0,behavior:'smooth'});});
  }

  // Footer Year
  var yf=document.getElementById('yr-ftr');
  if(yf)yf.textContent=new Date().getFullYear();

  // Kalender
  var mg=document.getElementById('month-grid');
  if(!mg)return;

  var KD={
    '2024/2025':{
      hol:[[2024,0,1],[2024,1,8],[2024,1,9],[2024,1,10],[2024,1,11],[2024,1,12],[2024,2,11],[2024,3,9],[2024,3,10],[2024,3,11],[2024,3,12],[2024,3,13],[2024,3,14],[2024,3,15],[2024,4,1],[2024,4,23],[2024,5,1],[2024,5,17],[2024,7,17],[2024,8,16],[2024,9,28],[2024,11,25],[2024,11,26],[2025,0,1],[2025,0,27],[2025,0,28],[2025,1,3],[2025,1,4],[2025,1,5],[2025,1,6],[2025,1,7],[2025,2,29],[2025,2,30],[2025,2,31],[2025,3,1],[2025,3,2],[2025,3,3],[2025,3,4],[2025,3,5],[2025,3,6],[2025,3,7],[2025,3,18],[2025,3,20],[2025,3,21],[2025,4,1],[2025,4,2],[2025,4,12],[2025,4,13],[2025,4,29],[2025,5,1],[2025,5,6],[2025,5,9]],
      ujn:[[2024,9,14],[2024,9,15],[2024,9,16],[2024,9,17],[2024,9,18],[2024,11,2],[2024,11,3],[2024,11,4],[2024,11,5],[2024,11,6],[2024,11,7],[2024,11,8],[2024,11,9],[2024,11,10],[2024,11,11],[2024,11,12],[2024,11,13],[2025,2,3],[2025,2,4],[2025,2,5],[2025,2,6],[2025,2,7],[2025,2,8],[2025,4,15],[2025,4,16],[2025,4,17],[2025,4,18],[2025,4,19],[2025,4,20],[2025,4,21],[2025,4,22]],
      evt:[[2024,6,15],[2024,6,22],[2024,7,1],[2024,7,17],[2024,9,28],[2024,10,10],[2024,10,25],[2024,11,22],[2025,1,10],[2025,2,17],[2025,3,21],[2025,4,2],[2025,4,28],[2025,5,2],[2025,5,20]],
      lsm:[[2024,6,1],[2024,6,2],[2024,6,3],[2024,6,4],[2024,6,5],[2024,6,6],[2024,6,7],[2024,6,8],[2024,6,9],[2024,6,10],[2024,6,11],[2024,6,12],[2024,6,13],[2024,6,14],[2024,11,23],[2024,11,24],[2024,11,27],[2024,11,28],[2024,11,29],[2024,11,30],[2025,5,27],[2025,5,28],[2025,5,29],[2025,5,30],[2025,6,1],[2025,6,2],[2025,6,3],[2025,6,4],[2025,6,5],[2025,6,6],[2025,6,7],[2025,6,8],[2025,6,9],[2025,6,10],[2025,6,11],[2025,6,12]]
    },
    '2025/2026':{
      hol:[[2025,7,17],[2025,8,5],[2025,9,29],[2025,11,25],[2025,11,26],[2026,0,1],[2026,1,17],[2026,1,18],[2026,2,21],[2026,2,22],[2026,2,23],[2026,2,24],[2026,2,25],[2026,2,26],[2026,2,27],[2026,2,28],[2026,2,29],[2026,2,30],[2026,2,31],[2026,3,1],[2026,3,2],[2026,3,3],[2026,3,10],[2026,3,14],[2026,3,20],[2026,4,1],[2026,4,7],[2026,4,14],[2026,4,21],[2026,4,25]],
      ujn:[[2025,9,13],[2025,9,14],[2025,9,15],[2025,9,16],[2025,9,17],[2025,11,1],[2025,11,2],[2025,11,3],[2025,11,4],[2025,11,5],[2025,11,6],[2025,11,7],[2025,11,8],[2025,11,9],[2025,11,10],[2025,11,11],[2025,11,12],[2026,2,9],[2026,2,10],[2026,2,11],[2026,2,12],[2026,2,13],[2026,2,14],[2026,4,11],[2026,4,12],[2026,4,13],[2026,4,14],[2026,4,15],[2026,4,16],[2026,4,17],[2026,4,18]],
      evt:[[2025,6,14],[2025,7,1],[2025,7,17],[2025,9,28],[2025,10,28],[2025,11,22],[2026,1,2],[2026,2,17],[2026,3,21],[2026,4,2],[2026,4,28]],
      lsm:[[2025,5,27],[2025,5,28],[2025,5,29],[2025,5,30],[2025,6,1],[2025,6,2],[2025,6,3],[2025,6,4],[2025,6,5],[2025,6,6],[2025,6,7],[2025,6,8],[2025,6,9],[2025,6,10],[2025,6,11],[2025,6,12],[2025,6,13],[2025,11,22],[2025,11,23],[2025,11,24],[2025,11,27],[2025,11,28],[2025,11,29],[2025,11,30]]
    }
  };

  var AD={
    '2024/2025':[
      {d:'15 Jul 2024',n:'Awal Tahun Pelajaran 2024/2025',t:'evt'},
      {d:'17 Agu 2024',n:'Hari Kemerdekaan RI ke-79',t:'hol'},
      {d:'14-18 Okt 2024',n:'Asesmen Tengah Semester Ganjil',t:'ujn'},
      {d:'28 Okt 2024',n:'Peringatan Hari Sumpah Pemuda',t:'evt'},
      {d:'2-13 Des 2024',n:'Asesmen Sumatif Akhir Semester Ganjil',t:'ujn'},
      {d:'23 Des-1 Jan 2025',n:'Libur Semester Ganjil, Natal dan Tahun Baru',t:'lsm'},
      {d:'1 Jan 2025',n:'Tahun Baru 2025',t:'hol'},
      {d:'27-28 Jan 2025',n:'Tahun Baru Imlek 2576',t:'hol'},
      {d:'3-7 Feb 2025',n:'Isra Miraj Nabi Muhammad SAW',t:'hol'},
      {d:'3-8 Mar 2025',n:'Asesmen Tengah Semester Genap',t:'ujn'},
      {d:'29 Mar-7 Apr 2025',n:'Libur Ramadhan dan Idul Fitri 1446 H',t:'hol'},
      {d:'18 Apr 2025',n:'Wafat Isa Al Masih',t:'hol'},
      {d:'2 Mei 2025',n:'Peringatan Hari Pendidikan Nasional',t:'evt'},
      {d:'15-22 Mei 2025',n:'Asesmen Sumatif Akhir Semester Genap',t:'ujn'},
      {d:'27 Jun-12 Jul 2025',n:'Libur Kenaikan Kelas dan Akhir Tahun',t:'lsm'}
    ],
    '2025/2026':[
      {d:'14 Jul 2025',n:'Awal Tahun Pelajaran 2025/2026',t:'evt'},
      {d:'17 Agu 2025',n:'Hari Kemerdekaan RI ke-80',t:'hol'},
      {d:'13-17 Okt 2025',n:'Asesmen Tengah Semester Ganjil',t:'ujn'},
      {d:'28 Okt 2025',n:'Peringatan Hari Sumpah Pemuda',t:'evt'},
      {d:'1-12 Des 2025',n:'Asesmen Sumatif Akhir Semester Ganjil',t:'ujn'},
      {d:'22 Des 2025-1 Jan 2026',n:'Libur Semester Ganjil, Natal dan Tahun Baru',t:'lsm'},
      {d:'1 Jan 2026',n:'Tahun Baru 2026',t:'hol'},
      {d:'17-18 Feb 2026',n:'Tahun Baru Imlek 2577',t:'hol'},
      {d:'9-14 Mar 2026',n:'Asesmen Tengah Semester Genap',t:'ujn'},
      {d:'21 Mar-3 Apr 2026',n:'Libur Ramadhan dan Idul Fitri 1447 H',t:'hol'},
      {d:'10 Apr 2026',n:'Wafat Isa Al Masih',t:'hol'},
      {d:'2 Mei 2026',n:'Peringatan Hari Pendidikan Nasional',t:'evt'},
      {d:'11-18 Mei 2026',n:'Asesmen Sumatif Akhir Semester Genap',t:'ujn'},
      {d:'Jun 2026',n:'Libur Kenaikan Kelas dan Akhir Tahun',t:'lsm'}
    ]
  };

  var tList=['2024/2025','2025/2026'];
  var curT='2024/2025';
  var mN=['Januari','Februari','Maret','April','Mei','Juni','Juli','Agustus','September','Oktober','November','Desember'];
  var dN=['Min','Sen','Sel','Rab','Kam','Jum','Sab'];

  function dk(y,m,d){return y+'-'+m+'-'+d;}

  function buildCal(t){
    var D=KD[t]||{};
    var hS=new Set((D.hol||[]).map(function(x){return dk(x[0],x[1],x[2]);}));
    var uS=new Set((D.ujn||[]).map(function(x){return dk(x[0],x[1],x[2]);}));
    var eS=new Set((D.evt||[]).map(function(x){return dk(x[0],x[1],x[2]);}));
    var lS=new Set((D.lsm||[]).map(function(x){return dk(x[0],x[1],x[2]);}));
    var td=new Date();
    var sy=parseInt(t.split('/')[0]);
    var months=[];
    var i;
    for(i=6;i<12;i++)months.push({y:sy,m:i});
    for(i=0;i<7;i++)months.push({y:sy+1,m:i});
    mg.innerHTML='';
    months.forEach(function(mi){
      var y=mi.y,m=mi.m;
      var mc=document.createElement('div');
      mc.className='month-card';
      var fd=new Date(y,m,1).getDay();
      var dim=new Date(y,m+1,0).getDate();
      var rows='';
      var day=1;
      for(var r=0;r<6;r++){
        rows+='<tr>';
        for(var c=0;c<7;c++){
          if((r===0&&c<fd)||day>dim){
            rows+='<td class="emp">&#160;</td>';
          }else{
            var k=dk(y,m,day);
            var cl='';
            var isT=(y===td.getFullYear()&&m===td.getMonth()&&day===td.getDate());
            if(isT)cl='tdy';
            else if(hS.has(k))cl='hol';
            else if(uS.has(k))cl='ujn';
            else if(eS.has(k))cl='evt';
            else if(lS.has(k))cl='lsm';
            else if(c===0)cl='sun';
            rows+='<td class="'+cl+'">'+day+'</td>';
            day++;
          }
        }
        rows+='</tr>';
        if(day>dim)break;
      }
      mc.innerHTML='<div class="month-head">'+mN[m]+' '+y+'</div>'+
        '<table class="mini-cal"><thead><tr>'+
        dN.map(function(d,idx){return '<th'+(idx===0?' style="color:#dc2626;"':'')+'>'+d+'</th>';}).join('')+
        '</tr></thead><tbody>'+rows+'</tbody></table>';
      mg.appendChild(mc);
    });

    var el=document.getElementById('ev-list');
    if(el){
      var ag=AD[t]||[];
      el.innerHTML=ag.map(function(ev){
        var bg=ev.t==='hol'?'background:#fef2f2;color:#dc2626;':
                ev.t==='ujn'?'background:#faf5ff;color:#7c3aed;':
                ev.t==='lsm'?'background:#f0fdf4;color:#16a34a;':
                'background:#eff6ff;color:#2563eb;';
        var lb=ev.t==='hol'?'Libur':ev.t==='ujn'?'Ujian':ev.t==='lsm'?'Libur Sem.':'Kegiatan';
        return '<div class="cal-ev-it"><div class="cal-ev-dt">'+ev.d+'</div><div class="cal-ev-nm">'+ev.n+'</div><span class="cal-ev-tp" style="'+bg+'">'+lb+'</span></div>';
      }).join('');
    }
    var ct=document.getElementById('cal-title');
    if(ct)ct.textContent='Kalender Pendidikan '+t;
    var yd=document.getElementById('yr-disp');
    if(yd)yd.textContent=t;
    var ay=document.getElementById('agenda-yr');
    if(ay)ay.textContent=t;
  }

  buildCal(curT);

  var pBtn=document.getElementById('prev-yr');
  var nBtn=document.getElementById('next-yr');
  if(pBtn)pBtn.addEventListener('click',function(){
    var i=tList.indexOf(curT);
    if(i>0){curT=tList[i-1];buildCal(curT);}
  });
  if(nBtn)nBtn.addEventListener('click',function(){
    var i=tList.indexOf(curT);
    if(i<tList.length-1){curT=tList[i+1];buildCal(curT);}
  });
})();
//]]>
</script>

</body>
</html>
