[BEYONDTRADEWITHBADAR.html](https://github.com/user-attachments/files/29409550/BEYONDTRADEWITHBADAR.html)
# BEYONDTRADEWITHBADAR
AI SOLUTIONS | BUSINESS SETUP | AI CONTENT MARKETING &amp; WEB DESIGNING
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Beyond Trading | AI Consultant & Digital Solutions</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --black:#050505;--dark:#0A0A0A;--dark2:#0F0F0F;
  --card:#131313;--card2:#181818;
  --gold:#C9A84C;--gold2:#E0BC6A;--gold3:#F0D080;
  --gold-glow:rgba(201,168,76,0.15);--gold-dim:rgba(201,168,76,0.08);
  --gold-b:rgba(201,168,76,0.2);--gold-b2:rgba(201,168,76,0.35);
  --white:#FFFFFF;--gray:#AAAAAA;--muted:#555555;--muted2:#333333;
  --fd:'Cormorant Garamond',Georgia,serif;
  --fb:'Inter',system-ui,sans-serif;
}
html{scroll-behavior:smooth}
body{background:var(--black);color:var(--white);font-family:var(--fb);overflow-x:hidden;line-height:1.6}
::selection{background:var(--gold);color:var(--black)}
.ac-logo-text{
  width:80px;height:80px;border-radius:50%;
  border:2px solid var(--gold);
  display:flex;align-items:center;justify-content:center;
  font-family:var(--fd);font-size:1.8rem;font-weight:700;
  color:var(--gold);margin-bottom:20px;
  box-shadow:0 0 20px rgba(201,168,76,0.25);
  background:var(--gold-dim);
  letter-spacing:0.05em;
}


/* SCROLLBAR */
::-webkit-scrollbar{width:3px}
::-webkit-scrollbar-track{background:var(--black)}
::-webkit-scrollbar-thumb{background:var(--gold)}

/* PROGRESS */
#prog{position:fixed;top:0;left:0;height:2px;background:linear-gradient(90deg,var(--gold),var(--gold3),var(--gold));z-index:9999;width:0;transition:width .08s linear}

/* NAV */
nav{
  position:fixed;top:0;left:0;right:0;z-index:200;
  display:flex;align-items:center;justify-content:space-between;
  padding:20px 64px;
  background:rgba(5,5,5,0);
  transition:background .4s,padding .3s,border-color .4s;
  border-bottom:1px solid transparent;
}
nav.sc{background:rgba(5,5,5,0.95);backdrop-filter:blur(20px);padding:14px 64px;border-color:var(--gold-b)}
.nav-brand{display:flex;align-items:center;gap:12px;text-decoration:none}

.nav-brand-text{display:flex;flex-direction:column;line-height:1}
.nav-brand-main{font-family:var(--fd);font-size:1.2rem;font-weight:600;color:var(--gold);letter-spacing:0.08em}
.nav-brand-sub{font-size:0.52rem;letter-spacing:0.28em;text-transform:uppercase;color:var(--muted);margin-top:1px}
.nav-links{display:flex;gap:32px;list-style:none}
.nav-links a{color:var(--muted);text-decoration:none;font-size:0.7rem;letter-spacing:0.16em;text-transform:uppercase;transition:color .2s;position:relative;padding-bottom:4px}
.nav-links a::after{content:'';position:absolute;bottom:0;left:0;width:0;height:1px;background:var(--gold);transition:width .3s}
.nav-links a:hover,.nav-links a.act{color:var(--gold)}
.nav-links a:hover::after,.nav-links a.act::after{width:100%}
.nav-cta{padding:9px 24px;border:1px solid var(--gold);color:var(--gold);text-decoration:none;font-size:0.68rem;letter-spacing:0.14em;text-transform:uppercase;transition:all .25s;white-space:nowrap}
.nav-cta:hover{background:var(--gold);color:var(--black)}
.hbg{display:none;flex-direction:column;gap:5px;cursor:pointer;padding:4px;background:none;border:none}
.hbg span{display:block;width:22px;height:1px;background:var(--gold);transition:all .3s}

/* MOBILE MENU */
.mob-menu{display:none;position:fixed;inset:0;background:rgba(5,5,5,0.98);z-index:199;flex-direction:column;align-items:center;justify-content:center;gap:36px}
.mob-menu.open{display:flex}
.mob-menu a{color:var(--white);text-decoration:none;font-family:var(--fd);font-size:2.4rem;font-weight:300;transition:color .2s}
.mob-menu a:hover{color:var(--gold)}
.mob-x{position:absolute;top:24px;right:28px;font-size:1.4rem;cursor:pointer;color:var(--gold);background:none;border:none;font-family:var(--fb)}

/* HERO */
#hero{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:140px 40px 100px;position:relative;overflow:hidden}
.hero-noise{position:absolute;inset:0;background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.03'/%3E%3C/svg%3E");opacity:.4;pointer-events:none}
.hero-glow{position:absolute;inset:0;background:radial-gradient(ellipse 55% 45% at 50% 48%,rgba(201,168,76,0.11) 0%,transparent 65%);pointer-events:none}
.hero-glow2{position:absolute;width:600px;height:600px;border-radius:50%;background:radial-gradient(circle,rgba(201,168,76,0.05) 0%,transparent 70%);top:50%;left:50%;transform:translate(-50%,-50%);animation:pulse-glow 4s ease-in-out infinite;pointer-events:none}
@keyframes pulse-glow{0%,100%{transform:translate(-50%,-50%) scale(1);opacity:.5}50%{transform:translate(-50%,-50%) scale(1.15);opacity:1}}
.h-particles{position:absolute;inset:0;pointer-events:none}
.h-particles span{position:absolute;width:2px;height:2px;border-radius:50%;background:var(--gold);opacity:0;animation:pfloat var(--d,10s) var(--dl,0s) ease-in-out infinite}
@keyframes pfloat{0%{opacity:0;transform:translateY(20px) scale(0)}20%{opacity:.7}80%{opacity:.2}100%{opacity:0;transform:translateY(-120px) scale(.3)}}
.h-eyebrow{font-size:0.66rem;letter-spacing:0.38em;text-transform:uppercase;color:var(--gold);margin-bottom:32px;opacity:0;animation:fup .8s .2s ease forwards;position:relative}

.h-title{font-family:var(--fd);font-size:clamp(3.2rem,8vw,7rem);font-weight:300;line-height:1.02;margin-bottom:8px;opacity:0;animation:fup .9s .35s ease forwards;position:relative}
.h-title em{font-style:italic;background:linear-gradient(135deg,var(--gold),var(--gold3),var(--gold));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
.h-line{width:0;height:1px;background:linear-gradient(90deg,transparent,var(--gold),transparent);margin:20px auto;animation:lineex 1.2s .9s ease forwards;position:relative}
@keyframes lineex{to{width:100px}}
.h-sub{font-family:var(--fd);font-size:clamp(1rem,2.2vw,1.4rem);font-weight:300;color:var(--gray);letter-spacing:0.06em;margin-bottom:12px;opacity:0;animation:fup .8s .7s ease forwards;position:relative}
.h-desc{max-width:580px;color:var(--gray);font-size:0.88rem;line-height:1.9;margin:0 auto 48px;opacity:0;animation:fup .8s .85s ease forwards;position:relative}
.h-btns{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;opacity:0;animation:fup .8s 1s ease forwards;position:relative}
.h-scroll{position:absolute;bottom:36px;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;gap:8px;opacity:0;animation:fup 1s 1.4s ease forwards}
.h-scroll span{font-size:0.58rem;letter-spacing:0.26em;text-transform:uppercase;color:var(--muted)}
.h-arr{width:18px;height:18px;border-right:1px solid var(--gold);border-bottom:1px solid var(--gold);transform:rotate(45deg);animation:bounce .8s ease-in-out infinite alternate}
@keyframes bounce{from{transform:rotate(45deg) translateY(0)}to{transform:rotate(45deg) translateY(5px)}}
@keyframes fup{from{opacity:0;transform:translateY(28px)}to{opacity:1;transform:translateY(0)}}

/* BUTTONS */
.btn-g{padding:15px 40px;background:linear-gradient(135deg,var(--gold),var(--gold2));color:var(--black);text-decoration:none;font-size:0.72rem;letter-spacing:0.16em;text-transform:uppercase;font-weight:700;transition:all .3s;display:inline-block;position:relative;overflow:hidden}
.btn-g::before{content:'';position:absolute;inset:0;background:linear-gradient(135deg,var(--gold2),var(--gold3));opacity:0;transition:opacity .3s}
.btn-g:hover::before{opacity:1}
.btn-g:hover{transform:translateY(-2px);box-shadow:0 8px 30px rgba(201,168,76,0.3)}
.btn-g span{position:relative;z-index:1}
.btn-o{padding:15px 40px;border:1px solid var(--gold-b2);color:var(--gold);text-decoration:none;font-size:0.72rem;letter-spacing:0.16em;text-transform:uppercase;transition:all .3s;display:inline-block;position:relative}
.btn-o:hover{border-color:var(--gold);background:var(--gold-dim);transform:translateY(-2px)}

/* SCROLL ANIM */
[da]{opacity:0;transition:opacity .75s ease,transform .75s ease}
[da="up"]{transform:translateY(40px)}
[da="left"]{transform:translateX(-40px)}
[da="right"]{transform:translateX(40px)}
[da="scale"]{transform:scale(0.92)}
[da="fade"]{transform:none}
[da].vis{opacity:1;transform:none}

/* SECTION COMMONS */
section{padding:100px 64px}
.wrap{max-width:1100px;margin:0 auto}
.ey{font-size:0.62rem;letter-spacing:0.38em;text-transform:uppercase;color:var(--gold);margin-bottom:14px;display:block}
.st{font-family:var(--fd);font-size:clamp(2rem,5vw,3.8rem);font-weight:300;line-height:1.08;margin-bottom:16px}
.st em{font-style:italic;color:var(--gold)}
.gr{height:1px;background:linear-gradient(90deg,var(--gold),transparent);margin-bottom:40px;width:0;transition:width 1.2s ease}
.gr.vis{width:80px}
.sec-desc{max-width:620px;color:var(--gray);font-size:0.9rem;line-height:1.9;margin-bottom:0}

/* STATS */
.stats{background:var(--dark2);border-top:1px solid var(--gold-b);border-bottom:1px solid var(--gold-b);padding:48px 64px;display:flex;justify-content:center;gap:0;flex-wrap:wrap}
.stat{text-align:center;padding:0 60px;position:relative}
.stat+.stat::before{content:'';position:absolute;left:0;top:50%;transform:translateY(-50%);height:40px;width:1px;background:var(--gold-b)}
.sn{font-family:var(--fd);font-size:3rem;font-weight:600;color:var(--gold);line-height:1;display:block;background:linear-gradient(135deg,var(--gold),var(--gold3));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
.sl{font-size:0.62rem;letter-spacing:0.22em;text-transform:uppercase;color:var(--muted);margin-top:8px;display:block}

/* PROBLEM */
#problem{background:var(--dark)}
.prob-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:2px;margin-top:52px}
.prob-card{padding:48px 36px;background:var(--card);position:relative;overflow:hidden;transition:background .3s}
.prob-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--gold),var(--gold2));transform:scaleX(0);transform-origin:left;transition:transform .5s}
.prob-card:hover{background:var(--card2)}
.prob-card:hover::before{transform:scaleX(1)}
.prob-num{font-family:var(--fd);font-size:4rem;font-weight:600;color:var(--muted2);line-height:1;display:block;margin-bottom:20px;transition:color .3s}
.prob-card:hover .prob-num{color:var(--gold-b2)}
.prob-q{font-family:var(--fd);font-size:1.3rem;font-weight:400;color:var(--white);line-height:1.35;margin-bottom:14px}
.prob-a{font-size:0.82rem;color:var(--muted);line-height:1.78}

/* SERVICES */
#services{background:var(--black)}
.svc-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:20px;margin-top:52px}
.svc{padding:48px 36px;background:var(--card);border:1px solid var(--gold-b);position:relative;overflow:hidden;transition:all .4s;cursor:default}
.svc::after{content:'';position:absolute;inset:0;background:linear-gradient(135deg,var(--gold-dim) 0%,transparent 50%);opacity:0;transition:opacity .4s}
.svc:hover{border-color:var(--gold);transform:translateY(-6px);box-shadow:0 20px 60px rgba(0,0,0,0.6),0 0 40px rgba(201,168,76,0.08)}
.svc:hover::after{opacity:1}
.svc-num{font-size:0.6rem;letter-spacing:0.3em;color:var(--gold);margin-bottom:28px;display:block;position:relative}
.svc-icon{font-size:2.4rem;display:block;margin-bottom:20px;position:relative;transition:transform .3s}
.svc:hover .svc-icon{transform:scale(1.1) rotate(-5deg)}
.svc-name{font-family:var(--fd);font-size:1.5rem;font-weight:500;color:var(--white);margin-bottom:14px;position:relative;line-height:1.2}
.svc-desc{font-size:0.8rem;color:var(--muted);line-height:1.82;margin-bottom:24px;position:relative}
.svc-items{list-style:none;display:flex;flex-direction:column;gap:7px;position:relative}
.svc-items li{font-size:0.76rem;color:var(--gray);padding-left:16px;position:relative}
.svc-items li::before{content:'→';color:var(--gold);position:absolute;left:0;font-size:0.7rem}
.svc-badge{display:inline-block;margin-top:20px;font-size:0.58rem;letter-spacing:0.16em;text-transform:uppercase;padding:4px 12px;border:1px solid var(--gold-b);color:var(--gold);position:relative}

/* HOW IT WORKS */
#how{background:var(--dark2)}
.steps{display:grid;grid-template-columns:repeat(3,1fr);gap:0;margin-top:56px;position:relative}
.steps::before{content:'';position:absolute;top:52px;left:calc(16.66% + 20px);right:calc(16.66% + 20px);height:1px;background:linear-gradient(90deg,var(--gold),var(--gold-b),var(--gold));z-index:0}
.step{text-align:center;padding:0 32px;position:relative;z-index:1}
.step-num{width:52px;height:52px;border:1px solid var(--gold);border-radius:50%;display:flex;align-items:center;justify-content:center;margin:0 auto 28px;font-family:var(--fd);font-size:1.3rem;font-weight:600;color:var(--gold);background:var(--dark2);position:relative;transition:all .3s}
.step:hover .step-num{background:var(--gold);color:var(--black);box-shadow:0 0 30px rgba(201,168,76,0.4)}
.step-title{font-family:var(--fd);font-size:1.35rem;font-weight:500;color:var(--white);margin-bottom:12px}
.step-desc{font-size:0.8rem;color:var(--muted);line-height:1.78}

/* PORTFOLIO */
#work{background:var(--black)}
.work-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:52px}
.wcard{background:var(--card);border:1px solid var(--gold-b);overflow:hidden;transition:all .4s;position:relative}
.wcard:hover{border-color:var(--gold);transform:translateY(-4px);box-shadow:0 16px 48px rgba(0,0,0,0.5),0 0 30px rgba(201,168,76,0.07)}
.wcard-top{padding:20px 24px 0}
.wb-bar{display:flex;align-items:center;gap:5px;padding-bottom:14px;border-bottom:1px solid rgba(255,255,255,0.06);margin-bottom:16px}
.wdot{width:8px;height:8px;border-radius:50%}
.wdot:nth-child(1){background:#FF5F57}
.wdot:nth-child(2){background:#FFBD2E}
.wdot:nth-child(3){background:#28C840}
.wurl{flex:1;background:rgba(255,255,255,0.04);border-radius:3px;padding:3px 10px;font-size:0.62rem;color:var(--muted);margin-left:8px}
.wmock{height:120px;background:linear-gradient(135deg,#0A0A0A,#1A1406);display:flex;align-items:center;justify-content:center;font-family:var(--fd);font-size:1.1rem;color:var(--gold);letter-spacing:0.06em;border-top:1px solid var(--gold-b);margin:0 -0px;position:relative;overflow:hidden}
.wmock::before{content:'';position:absolute;inset:0;background:radial-gradient(circle at 50% 50%,rgba(201,168,76,0.06) 0%,transparent 70%)}
.wcard-body{padding:24px}
.w-type{font-size:0.6rem;letter-spacing:0.22em;text-transform:uppercase;color:var(--gold);margin-bottom:6px}
.w-name{font-family:var(--fd);font-size:1.2rem;font-weight:500;margin-bottom:8px;color:var(--white)}
.w-desc{font-size:0.76rem;color:var(--muted);line-height:1.7;margin-bottom:16px}
.w-link{display:inline-flex;align-items:center;gap:6px;color:var(--gold);text-decoration:none;font-size:0.72rem;letter-spacing:0.06em;border-bottom:1px solid var(--gold-b);padding-bottom:2px;transition:all .25s}
.w-link:hover{border-color:var(--gold);gap:10px}

/* WHY */
#why{background:var(--dark)}
.why-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:2px;margin-top:52px}
.why-card{padding:40px 28px;background:var(--card);text-align:center;transition:background .3s;border-bottom:2px solid transparent;transition:all .3s}
.why-card:hover{background:var(--card2);border-color:var(--gold)}
.why-icon{font-size:2rem;display:block;margin-bottom:18px}
.why-title{font-family:var(--fd);font-size:1.15rem;font-weight:500;color:var(--white);margin-bottom:10px}
.why-text{font-size:0.76rem;color:var(--muted);line-height:1.72}

/* PRICING */
#pricing{background:var(--black)}
.pkg-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:20px;margin-top:52px}
.pkg{padding:40px 32px;border:1px solid var(--gold-b);background:var(--card);position:relative;transition:all .35s}
.pkg:hover{transform:translateY(-4px);border-color:var(--gold-b2)}
.pkg.hot{border-color:var(--gold);background:linear-gradient(180deg,rgba(201,168,76,0.04) 0%,var(--card) 30%)}
.pkg-top-bar{position:absolute;top:0;left:0;right:0;height:2px;background:var(--gold);transform:scaleX(0);transform-origin:left;transition:transform .4s}
.pkg:hover .pkg-top-bar{transform:scaleX(1)}
.hot .pkg-top-bar{transform:scaleX(1)}
.pkg-badge{position:absolute;top:-1px;right:20px;background:var(--gold);color:var(--black);font-size:0.54rem;letter-spacing:0.18em;text-transform:uppercase;font-weight:700;padding:3px 12px}
.pkg-name{font-size:0.64rem;letter-spacing:0.26em;text-transform:uppercase;color:var(--gold);margin-bottom:10px}
.pkg-price{font-family:var(--fd);font-size:2.4rem;font-weight:600;color:var(--white);line-height:1;margin-bottom:5px}
.pkg-per{font-size:0.7rem;color:var(--muted);margin-bottom:24px}
.pkg-div{height:1px;background:var(--gold-b);margin-bottom:24px}
.pkg-list{list-style:none;display:flex;flex-direction:column;gap:9px;margin-bottom:28px}
.pkg-list li{font-size:0.79rem;color:var(--gray);padding-left:18px;position:relative}
.pkg-list li::before{content:'✓';color:var(--gold);position:absolute;left:0;font-size:0.68rem;font-weight:700}
.pkg-cta{display:block;text-align:center;padding:12px;border:1px solid var(--gold-b);color:var(--gold);text-decoration:none;font-size:0.7rem;letter-spacing:0.14em;text-transform:uppercase;transition:all .25s}
.pkg-cta:hover,.hot .pkg-cta{background:var(--gold);color:var(--black);border-color:var(--gold)}

/* CONTACT */
#contact{background:var(--dark2)}
.contact-wrap{display:grid;grid-template-columns:1fr 1fr;gap:80px;margin-top:52px;align-items:start}
.about-card{padding:40px;background:var(--card);border:1px solid var(--gold-b)}

.ac-name{font-family:var(--fd);font-size:2rem;font-weight:600;color:var(--white);margin-bottom:4px}
.ac-role{font-size:0.72rem;letter-spacing:0.12em;color:var(--gold);margin-bottom:6px;text-transform:uppercase}
.ac-company{font-size:0.76rem;color:var(--muted);margin-bottom:28px}
.ac-bio{font-size:0.84rem;color:var(--gray);line-height:1.85;margin-bottom:32px}
.contact-icons{display:flex;flex-direction:column;gap:16px}
.ci{display:flex;align-items:center;gap:16px;text-decoration:none;transition:all .25s;padding:14px 18px;border:1px solid transparent}
.ci:hover{border-color:var(--gold-b);background:var(--card2)}
.ci-icon{width:40px;height:40px;border:1px solid var(--gold-b);display:flex;align-items:center;justify-content:center;font-size:1rem;flex-shrink:0;transition:all .25s;color:var(--gold)}
.ci:hover .ci-icon{background:var(--gold);border-color:var(--gold);color:var(--black)}
.ci-label{font-size:0.6rem;letter-spacing:0.18em;text-transform:uppercase;color:var(--muted);display:block;margin-bottom:2px}
.ci-val{font-size:0.85rem;color:var(--white);transition:color .25s}
.ci:hover .ci-val{color:var(--gold)}
.cta-box{padding:40px;border:1px solid var(--gold-b);background:var(--card);display:flex;flex-direction:column;gap:24px}
.cta-eyebrow{font-size:0.6rem;letter-spacing:0.3em;text-transform:uppercase;color:var(--gold)}
.cta-title{font-family:var(--fd);font-size:2.4rem;font-weight:300;line-height:1.15;color:var(--white)}
.cta-title em{font-style:italic;color:var(--gold)}
.cta-text{font-size:0.84rem;color:var(--gray);line-height:1.86}
.cta-btns{display:flex;flex-direction:column;gap:12px}
.wa-btn{display:flex;align-items:center;justify-content:center;gap:10px;padding:14px;background:#25D366;color:white;text-decoration:none;font-size:0.74rem;letter-spacing:0.12em;text-transform:uppercase;font-weight:600;transition:opacity .25s}
.wa-btn:hover{opacity:.88}

/* FOOTER */
footer{background:var(--black);border-top:1px solid var(--gold-b);padding:28px 64px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:16px}
.f-brand{display:flex;align-items:center;gap:10px}

.f-name{font-family:var(--fd);font-size:1rem;color:var(--gold);font-weight:500}
.f-text{font-size:0.64rem;color:var(--muted)}
.f-links{display:flex;gap:24px;list-style:none}
.f-links a{font-size:0.62rem;color:var(--muted);text-decoration:none;letter-spacing:0.12em;text-transform:uppercase;transition:color .2s}
.f-links a:hover{color:var(--gold)}

/* RESPONSIVE */
@media(max-width:960px){
  nav{padding:16px 24px}
  nav.sc{padding:12px 24px}
  .nav-links,.nav-cta{display:none}
  .hbg{display:flex}
  section{padding:72px 24px}
  .stats{padding:36px 24px;gap:0}
  .stat{padding:0 32px}
  .prob-grid,.why-grid,.work-grid{grid-template-columns:1fr}.pkg-grid{grid-template-columns:1fr}.svc-grid{grid-template-columns:1fr}
  .steps{grid-template-columns:1fr;gap:40px}
  .steps::before{display:none}
  .contact-wrap{grid-template-columns:1fr;gap:32px}
  footer{padding:24px;flex-direction:column;text-align:center}
  .h-title{font-size:clamp(2.8rem,10vw,5rem)}
}
@media(max-width:640px){
  .stat+.stat::before{display:none}
  .stats{gap:32px}
}
</style>
</head>
<body>

<div id="prog"></div>

<!-- MOBILE MENU -->
<div class="mob-menu" id="mm">
  <button class="mob-x" onclick="toggleMenu()">✕</button>
  <a href="#problem" onclick="closeMob()">Problem</a>
  <a href="#services" onclick="closeMob()">Services</a>
  <a href="#work" onclick="closeMob()">Our Work</a>
  <a href="#pricing" onclick="closeMob()">Pricing</a>
  <a href="#contact" onclick="closeMob()">Contact</a>
</div>

<!-- NAV -->
<nav id="nav">
  <a href="#hero" class="nav-brand">
    <div class="nav-brand-text">
      <span class="nav-brand-main">Beyond Trading</span>
      <span class="nav-brand-sub">by ABM General Trading LLC</span>
    </div>
  </a>
  <ul class="nav-links">
    <li><a href="#problem">Problem</a></li>
    <li><a href="#services">Services</a></li>
    <li><a href="#work">Our Work</a></li>
    <li><a href="#pricing">Pricing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <a href="https://wa.me/971553815889" target="_blank" rel="noopener" class="nav-cta">WhatsApp Us</a>
  <button class="hbg" id="hbg" onclick="toggleMenu()"><span></span><span></span><span></span></button>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-noise"></div>
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>
  <div class="h-particles" id="hpart"></div>

  <span class="h-eyebrow">Beyond Trading &nbsp;·&nbsp; Dubai, UAE &nbsp;·&nbsp; AI & Digital Solutions</span>
  <h1 class="h-title">
    Your Business Is Losing Clients<br><em>Every Day You're Not Online.</em>
  </h1>
  <div class="h-line"></div>
  <p class="h-sub">We connect UAE businesses to world-class digital solutions — websites, AI automation, content marketing, and business setup in the UAE.</p>
  <p class="h-desc">Premium digital presence services for businesses that refuse to be invisible. Powered by AI. Delivered through trusted partners. Results guaranteed.</p>
  <div class="h-btns">
    <a href="#contact" class="btn-g"><span>Book Free Strategy Call</span></a>
    <a href="#services" class="btn-o">Explore Services</a>
  </div>
  <div class="h-scroll"><span>Discover</span><div class="h-arr"></div></div>
</section>

<!-- STATS -->
<div class="stats">
  <div class="stat" da="up">
    <span class="sn counter" data-t="3" data-s="+">3+</span>
    <span class="sl">Services Offered</span>
  </div>
  <div class="stat" da="up" data-dl="100">
    <span class="sn">UAE</span>
    <span class="sl">VAT Registered · ABM LLC</span>
  </div>
  <div class="stat" da="up" data-dl="200">
    <span class="sn">24/7</span>
    <span class="sl">AI-Powered Support</span>
  </div>
  <div class="stat" da="up" data-dl="300">
    <span class="sn">100%</span>
    <span class="sl">Results Focused</span>
  </div>
</div>

<!-- PROBLEM -->
<section id="problem">
  <div class="wrap">
    <span class="ey" da="fade">The Reality</span>
    <h2 class="st" da="up">Your Competitors Are<br><em>Already Ahead of You.</em></h2>
    <div class="gr" da="fade"></div>
    <div class="prob-grid">
      <div class="prob-card" da="up" data-dl="0">
        <span class="prob-num">01</span>
        <p class="prob-q">"73% of B2B buyers research online before making contact."</p>
        <p class="prob-a">If your business has no digital presence, you don't exist in their shortlist. They find your competitor instead — and they never call you.</p>
      </div>
      <div class="prob-card" da="up" data-dl="120">
        <span class="prob-num">02</span>
        <p class="prob-q">"A dead LinkedIn page loses you deals before a single conversation starts."</p>
        <p class="prob-a">European and Chinese buyers check LinkedIn before every meeting. An empty or inactive profile signals that your company isn't serious.</p>
      </div>
      <div class="prob-card" da="up" data-dl="240">
        <span class="prob-num">03</span>
        <p class="prob-q">"Manual follow-ups waste hours. AI handles it in seconds."</p>
        <p class="prob-a">Every lead that doesn't hear from you within 5 minutes is 80% less likely to convert. AI automation solves this — permanently.</p>
      </div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <div class="wrap">
    <span class="ey" da="fade">What We Connect You To</span>
    <h2 class="st" da="up">Four Solutions.<br><em>One Transformation.</em></h2>
    <div class="gr" da="fade"></div>
    <div class="svc-grid">
      <div class="svc" da="up" data-dl="0">
        <span class="svc-num">Service 01</span>
        <span class="svc-icon">🌐</span>
        <div class="svc-name">Digital Presence & Website Design</div>
        <p class="svc-desc">A professionally designed website is your most powerful 24/7 salesperson. We connect you to expert designers who deliver results.</p>
        <ul class="svc-items">
          <li>Premium 5–10 page website design</li>
          <li>Mobile-first, SEO-optimised build</li>
          <li>Conversion-focused layout & copy</li>
          <li>Fast delivery with revisions</li>
        </ul>
        <span class="svc-badge">Starting AED 2,500</span>
      </div>
      <div class="svc" da="up" data-dl="140">
        <span class="svc-num">Service 02</span>
        <span class="svc-icon">📱</span>
        <div class="svc-name">Content & Social Media Management</div>
        <p class="svc-desc">Stay visible. Stay relevant. We manage your LinkedIn and Instagram with strategically crafted content that builds authority, drives engagement, and attracts premium clients.</p>
        <ul class="svc-items">
          <li>8+ branded posts per month</li>
          <li>LinkedIn authority building</li>
          <li>Custom-designed branded visuals</li>
          <li>Monthly content calendar</li>
          <li>Engagement & scheduling</li>
        </ul>
        <span class="svc-badge">From AED 1,500/mo</span>
      </div>
      <div class="svc" da="up" data-dl="280">
        <span class="svc-num">Service 03</span>
        <span class="svc-icon">🤖</span>
        <div class="svc-name">AI Automation & Business Intelligence</div>
        <p class="svc-desc">Stop doing manually what AI can do in seconds. We deploy intelligent automation that captures leads, nurtures clients, and saves you hours every week.</p>
        <ul class="svc-items">
          <li>WhatsApp AI Chatbot (24/7 lead capture)</li>
          <li>CRM + lead follow-up automation</li>
          <li>Business process automation</li>
          <li>AI Voice Agent <em style="color:var(--gold);font-size:0.7rem">(Coming Soon)</em></li>
        </ul>
        <span class="svc-badge">Starting AED 2,000 · Custom Available</span>
      </div>
      <div class="svc" da="up" data-dl="380">
        <span class="svc-num">Service 04</span>
        <span class="svc-icon">🏢</span>
        <div class="svc-name">Business Setup & Market Entry</div>
        <p class="svc-desc">Entering the UAE market? We connect you to the right experts for a smooth, compliant, and fast company setup — so you can focus on business, not paperwork.</p>
        <ul class="svc-items">
          <li>UAE company formation & trade license</li>
          <li>Banking facilitation & account opening</li>
          <li>PRO services & visa assistance</li>
          <li>India–UAE market entry consultancy</li>
        </ul>
        <span class="svc-badge">Custom · Book a Consultation</span>
      </div>

    </div>
  </div>
</section>

<!-- HOW IT WORKS -->
<section id="how">
  <div class="wrap">
    <span class="ey" da="fade">Our Process</span>
    <h2 class="st" da="up">Simple. Fast.<br><em>Guaranteed Results.</em></h2>
    <div class="gr" da="fade"></div>
    <div class="steps">
      <div class="step" da="up" data-dl="0">
        <div class="step-num">01</div>
        <div class="step-title">Strategy Session</div>
        <p class="step-desc">We learn your business, goals, target audience, and current gaps. Free 30-minute call. Zero commitment. Maximum clarity.</p>
      </div>
      <div class="step" da="up" data-dl="150">
        <div class="step-num">02</div>
        <div class="step-title">Build & Connect</div>
        <p class="step-desc">We connect you to the right experts, manage the entire process, and ensure premium delivery — website, content, or automation.</p>
      </div>
      <div class="step" da="up" data-dl="300">
        <div class="step-num">03</div>
        <div class="step-title">Grow & Scale</div>
        <p class="step-desc">Results compound over time. You focus on closing deals. We handle the digital infrastructure that keeps your pipeline full.</p>
      </div>
    </div>
  </div>
</section>

<!-- WORK -->
<section id="work">
  <div class="wrap">
    <span class="ey" da="fade">Portfolio</span>
    <h2 class="st" da="up">Built With Purpose,<br><em>Delivered With Precision.</em></h2>
    <div class="gr" da="fade"></div>
    <div class="work-grid">
      <div class="wcard" da="up" data-dl="0">
        <div class="wcard-top">
          <div class="wb-bar">
            <div class="wdot"></div><div class="wdot"></div><div class="wdot"></div>
            <div class="wurl">🔒 abmtrade.ae</div>
          </div>
        </div>
        <div class="wmock">ABM General Trading</div>
        <div class="wcard-body">
          <p class="w-type">General Trading · Corporate Website</p>
          <p class="w-name">abmtrade.ae</p>
          <p class="w-desc">Premium black and gold corporate website for UAE-based trading company. Full company profile, services showcase, and contact integration.</p>
          <a href="https://abmtrade.ae" target="_blank" rel="noopener" class="w-link">Visit Website →</a>
        </div>
      </div>
      <div class="wcard" da="up" data-dl="120">
        <div class="wcard-top">
          <div class="wb-bar">
            <div class="wdot"></div><div class="wdot"></div><div class="wdot"></div>
            <div class="wurl">🔒 thinkbypradeep.com</div>
          </div>
        </div>
        <div class="wmock">Think by Pradeep</div>
        <div class="wcard-body">
          <p class="w-type">Real Estate · Personal Brand Website</p>
          <p class="w-name">thinkbypradeep.com</p>
          <p class="w-desc">Professional personal brand website for a real estate consultant. Services showcase, appointment booking, and lead capture integration.</p>
          <a href="https://thinkbypradeep.com" target="_blank" rel="noopener" class="w-link">Visit Website →</a>
        </div>
      </div>
      <div class="wcard" da="up" data-dl="240">
        <div class="wcard-top">
          <div class="wb-bar">
            <div class="wdot"></div><div class="wdot"></div><div class="wdot"></div>
            <div class="wurl">🔒 realtyidentify.com</div>
          </div>
        </div>
        <div class="wmock">Realty Identify</div>
        <div class="wcard-body">
          <p class="w-type">Property · Business Website</p>
          <p class="w-name">realtyidentify.com</p>
          <p class="w-desc">Clean, conversion-focused property consultancy website. Mobile-responsive design with service pages, blog, and social media integration.</p>
          <a href="https://realtyidentify.com" target="_blank" rel="noopener" class="w-link">Visit Website →</a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- WHY -->
<section id="why">
  <div class="wrap">
    <span class="ey" da="fade">Why Beyond Trading</span>
    <h2 class="st" da="up">Enterprise Results.<br><em>Without Enterprise Complexity.</em></h2>
    <div class="gr" da="fade"></div>
    <div class="why-grid">
      <div class="why-card" da="scale" data-dl="0">
        <span class="why-icon">🇦🇪</span>
        <div class="why-title">Dubai Based</div>
        <p class="why-text">Physical presence in UAE. We understand the local market, regulations, and business culture that remote agencies miss.</p>
      </div>
      <div class="why-card" da="scale" data-dl="80">
        <span class="why-icon">🤖</span>
        <div class="why-title">AI-Powered Delivery</div>
        <p class="why-text">Every service is enhanced by AI — faster delivery, smarter content, and automation that works while you sleep.</p>
      </div>
      <div class="why-card" da="scale" data-dl="160">
        <span class="why-icon">🤝</span>
        <div class="why-title">Connector Model</div>
        <p class="why-text">We connect you to the right experts for every solution — you get specialist quality without agency overhead costs.</p>
      </div>
      <div class="why-card" da="scale" data-dl="240">
        <span class="why-icon">📊</span>
        <div class="why-title">Results Focused</div>
        <p class="why-text">Every project is measured by business outcomes — more leads, better visibility, and a digital presence that converts.</p>
      </div>
    </div>
  </div>
</section>

<!-- PRICING -->
<section id="pricing">
  <div class="wrap">
    <span class="ey" da="fade">Investment</span>
    <h2 class="st" da="up">Transparent Pricing.<br><em>Every Service Covered.</em></h2>
    <div class="gr" da="fade"></div>
    <div class="pkg-grid">
      <div class="pkg" da="up" data-dl="0">
        <div class="pkg-top-bar"></div>
        <div class="pkg-name">Digital Starter</div>
        <div class="pkg-price">AED 2,500</div>
        <div class="pkg-per">One-time · Website Delivery</div>
        <div class="pkg-div"></div>
        <ul class="pkg-list">
          <li>Professional 5-page website</li>
          <li>Mobile-responsive design</li>
          <li>Contact form & Google Maps</li>
          <li>Basic SEO setup</li>
          <li>Delivered within 7–10 days</li>
        </ul>
        <a href="https://wa.me/971553815889?text=Hi%20Badar%2C%20I'm%20interested%20in%20the%20Digital%20Starter%20package" target="_blank" class="pkg-cta">Get Started</a>
      </div>
      <div class="pkg hot" da="up" data-dl="140">
        <div class="pkg-top-bar"></div>
        <div class="pkg-badge">Most Popular</div>
        <div class="pkg-name">Digital Growth</div>
        <div class="pkg-price" style="font-size:1.9rem">AED 2,500 <span style="font-size:1rem;color:var(--gray);font-family:var(--fb)">+ 1,500/mo</span></div>
        <div class="pkg-per">Website + Monthly Content Management</div>
        <div class="pkg-div"></div>
        <ul class="pkg-list">
          <li>Everything in Digital Starter</li>
          <li>8 LinkedIn/Instagram posts per month</li>
          <li>AI-generated branded visuals</li>
          <li>Monthly content calendar</li>
          <li>Performance review every 30 days</li>
          <li>Dedicated account support</li>
        </ul>
        <a href="https://wa.me/971553815889?text=Hi%20Badar%2C%20I'm%20interested%20in%20the%20Digital%20Growth%20package" target="_blank" class="pkg-cta">Get Started</a>
      </div>
      <div class="pkg" da="up" data-dl="280">
        <div class="pkg-top-bar"></div>
        <div class="pkg-name">AI Enterprise</div>
        <div class="pkg-price">Custom</div>
        <div class="pkg-per">Full Digital + AI Automation Suite</div>
        <div class="pkg-div"></div>
        <ul class="pkg-list">
          <li>Premium website design</li>
          <li>Full content management</li>
          <li>WhatsApp AI Chatbot setup</li>
          <li>CRM + lead automation</li>
          <li>Business process automation</li>
          <li>Monthly strategy sessions</li>
        </ul>
        <a href="https://wa.me/971553815889?text=Hi%20Badar%2C%20I'm%20interested%20in%20the%20AI%20Enterprise%20package" target="_blank" class="pkg-cta">Let's Talk</a>
      </div>
      <div class="pkg" da="up" data-dl="420">
        <div class="pkg-top-bar"></div>
        <div class="pkg-name">Business Setup</div>
        <div class="pkg-price">Custom</div>
        <div class="pkg-per">UAE Company Formation & Market Entry</div>
        <div class="pkg-div"></div>
        <ul class="pkg-list">
          <li>UAE company formation & trade license</li>
          <li>Banking facilitation & account opening</li>
          <li>PRO services & visa assistance</li>
          <li>India–UAE market entry consultancy</li>
          <li>End-to-end setup support</li>
        </ul>
        <a href="https://wa.me/971553815889?text=Hi%20Badar%2C%20I'm%20interested%20in%20Business%20Setup%20services" target="_blank" class="pkg-cta">Let's Talk</a>
      </div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="wrap">
    <span class="ey" da="fade">Get in Touch</span>
    <h2 class="st" da="up">Ready to Transform<br><em>Your Digital Presence?</em></h2>
    <div class="gr" da="fade"></div>
    <div class="contact-wrap">
      <div>
        <div class="about-card" da="left">
          <div class="ac-logo-text">ABM</div>
          <div class="ac-name">Badar Ahmad Khan</div>
          <div class="ac-role">AI Consultant & Managing Director</div>
          <div class="ac-company">ABM General Trading LLC · Dubai, UAE</div>
          <p class="ac-bio">Connecting UAE businesses to world-class digital solutions — websites, AI automation, and content strategies that drive real business growth. Operating through Beyond Trading, a division of ABM General Trading LLC.</p>
          <div class="contact-icons">
            <a href="tel:+971553815889" class="ci">
              <div class="ci-icon">📞</div>
              <div><span class="ci-label">Phone / WhatsApp</span><span class="ci-val">+971 55 381 5889</span></div>
            </a>
            <a href="mailto:badar@abmtrade.ae" class="ci">
              <div class="ci-icon">✉️</div>
              <div><span class="ci-label">Email</span><span class="ci-val">badar@abmtrade.ae</span></div>
            </a>
            <a href="https://www.linkedin.com/in/badar-ahmad-khan-5b497b329" target="_blank" rel="noopener" class="ci">
              <div class="ci-icon">💼</div>
              <div><span class="ci-label">LinkedIn</span><span class="ci-val">Badar Ahmad Khan</span></div>
            </a>
            <a href="https://abmtrade.ae" target="_blank" rel="noopener" class="ci">
              <div class="ci-icon">🌐</div>
              <div><span class="ci-label">Website</span><span class="ci-val">www.abmtrade.ae</span></div>
            </a>
          </div>
        </div>
      </div>
      <div class="cta-box" da="right">
        <span class="cta-eyebrow">Free 30-Minute Strategy Call</span>
        <h3 class="cta-title">Let's Build Something <em>Remarkable Together.</em></h3>
        <p class="cta-text">Whether you need a premium website, an AI-powered WhatsApp chatbot, or a complete digital transformation — we'll map out exactly what your business needs in 30 minutes. No commitment. Just clarity and a clear plan.</p>
        <div class="cta-btns">
          <a href="https://wa.me/971553815889?text=Hi%20Badar%2C%20I'd%20like%20to%20book%20a%20free%20strategy%20call" target="_blank" rel="noopener" class="wa-btn">
            💬 &nbsp;Book via WhatsApp
          </a>
          <a href="mailto:badar@abmtrade.ae?subject=Strategy Call Request — Beyond Trading" class="btn-g" style="text-align:center"><span>Send an Email</span></a>
          <a href="tel:+971553815889" class="btn-o" style="text-align:center">Call Directly: +971 55 381 5889</a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="f-brand">
    <span class="f-name">Beyond Trading · ABM General Trading LLC</span>
  </div>
  <span class="f-text">© 2026 ABM General Trading LLC · Dubai, UAE · VAT Registered · All Rights Reserved</span>
  <ul class="f-links">
    <li><a href="https://abmtrade.ae" target="_blank" rel="noopener">Website</a></li>
    <li><a href="mailto:badar@abmtrade.ae">Email</a></li>
    <li><a href="https://wa.me/971553815889" target="_blank" rel="noopener">WhatsApp</a></li>
    <li><a href="https://www.linkedin.com/in/badar-ahmad-khan-5b497b329" target="_blank" rel="noopener">LinkedIn</a></li>
  </ul>
</footer>

<script>
// PARTICLES
(function(){
  const c=document.getElementById('hpart');
  for(let i=0;i<35;i++){
    const p=document.createElement('span');
    const sz=1+Math.random()*2;
    p.style.cssText='left:'+Math.random()*100+'%;top:'+(60+Math.random()*50)+'%;--d:'+(8+Math.random()*10)+'s;--dl:'+(Math.random()*8)+'s;width:'+sz+'px;height:'+sz+'px';
    c.appendChild(p);
  }
})();

// SCROLL PROGRESS + NAV
window.addEventListener('scroll',function(){
  const s=window.scrollY,h=document.body.scrollHeight-window.innerHeight;
  document.getElementById('prog').style.width=(s/h*100)+'%';
  document.getElementById('nav').classList.toggle('sc',s>60);
  let cur='';
  ['problem','services','how','work','why','pricing','contact'].forEach(id=>{
    const el=document.getElementById(id);
    if(el&&el.getBoundingClientRect().top<=100)cur=id;
  });
  document.querySelectorAll('.nav-links a').forEach(a=>{
    a.classList.toggle('act',a.getAttribute('href')==='#'+cur);
  });
},{passive:true});

// INTERSECTION OBSERVER
const io=new IntersectionObserver(entries=>{
  entries.forEach(e=>{
    if(e.isIntersecting){
      const el=e.target,dl=parseInt(el.dataset.dl||el.getAttribute('data-dl')||0);
      setTimeout(()=>{
        el.classList.add('vis');
        if(el.classList.contains('gr'))el.style.width='80px';
        if(el.classList.contains('counter'))animCount(el);
      },dl);
      io.unobserve(el);
    }
  });
},{threshold:0.12});
document.querySelectorAll('[da]').forEach(el=>io.observe(el));

// COUNTER
function animCount(el){
  const t=parseInt(el.dataset.t||'4'),s=el.dataset.s||'',dur=1800,st=performance.now();
  (function tick(now){
    const p=Math.min((now-st)/dur,1),e=1-Math.pow(1-p,3);
    el.textContent=Math.floor(e*t)+s;
    if(p<1)requestAnimationFrame(tick);
  })(st);
}

// MOBILE MENU
function toggleMenu(){document.getElementById('mm').classList.toggle('open')}
function closeMob(){document.getElementById('mm').classList.remove('open')}
</script>
</body>
</html>
