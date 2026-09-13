<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ประวัติเครื่องสำอางอียิปต์โบราณ</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@500;600;700&family=Noto+Sans+Thai:wght@400;500;600;700&display=swap');

:root{
    --gold:#d9a72e;
    --gold2:#ffe39a;
    --sand:#ead29b;
    --dark:#080604;
    --dark2:#171008;
    --brown:#321c0a;
    --text:#f6e9c7;
    --muted:#c9b991;
}

*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

html{
    scroll-behavior:smooth;
}

body{
    background:
        radial-gradient(circle at 50% 0%,#4a2b0d 0%,#160d06 35%,#070504 75%);
    color:var(--text);
    font-family:"Noto Sans Thai",sans-serif;
    line-height:1.8;
}

nav{
    position:fixed;
    top:0;
    left:0;
    right:0;
    z-index:9999;

    padding:13px 6%;

    display:flex;
    align-items:center;
    justify-content:space-between;

    background:rgba(5,4,2,.95);
    border-bottom:1px solid rgba(217,167,46,.35);

    backdrop-filter:blur(10px);
}

.logo{
    color:var(--gold2);
    font-family:Cinzel,serif;
    font-size:18px;
    letter-spacing:2px;
}

nav ul{
    display:flex;
    gap:22px;
    list-style:none;
}

nav a{
    color:#f9e9bd;
    text-decoration:none;
    font-size:14px;
}

nav a:hover{
    color:var(--gold);
}

.hero{
    min-height:100vh;

    display:flex;
    align-items:center;
    justify-content:center;

    text-align:center;

    padding:130px 20px 80px;

    background:
        radial-gradient(circle at center,
        rgba(132,77,18,.55),
        rgba(8,6,4,.96) 70%);
}

.hero-inner{
    max-width:950px;
}

.egypt-eye{
    font-size:80px;
    color:var(--gold);
    text-shadow:0 0 30px rgba(217,167,46,.35);
}

.small-title{
    color:var(--gold);
    letter-spacing:5px;
    font-size:13px;
}

h1{
    margin:15px 0 25px;

    color:var(--gold2);

    font-family:Cinzel,serif;

    font-size:clamp(42px,8vw,82px);

    line-height:1.08;
}

.hero p{
    max-width:780px;
    margin:auto;

    color:#e4d4ad;

    font-size:18px;
}

.button{
    display:inline-block;

    margin:25px 6px 0;

    padding:12px 26px;

    color:#211303;

    background:
        linear-gradient(135deg,#ffe99e,#b77b19);

    border-radius:30px;

    text-decoration:none;

    font-weight:700;

    transition:.25s;
}

.button:hover{
    transform:translateY(-3px);
}

section{
    padding:90px 6%;
}

.section-title{
    text-align:center;
    margin-bottom:45px;
}

.section-title h2{
    color:var(--gold2);
    font-family:Cinzel,serif;
    font-size:clamp(30px,5vw,48px);
}

.section-title p{
    color:var(--muted);
}

.container{
    max-width:1150px;
    margin:auto;
}

.intro{
    background:
        linear-gradient(180deg,#1b1008,#0d0805);
}

.two-columns{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:25px;
}

.box{
    padding:30px;

    background:
        linear-gradient(145deg,#321d0c,#120b07);

    border:1px solid rgba(217,167,46,.25);

    border-radius:15px;

    box-shadow:0 15px 45px rgba(0,0,0,.25);
}

.box h3{
    color:var(--gold);
    margin-bottom:12px;
}

.timeline{
    max-width:950px;
    margin:auto;
}

.timeline-item{
    display:grid;
    grid-template-columns:160px 1fr;

    gap:20px;

    margin-bottom:22px;
}

.year{
    padding-top:12px;

    color:var(--gold);

    font-family:Cinzel,serif;

    font-size:20px;
}

.timeline-card{
    padding:22px;

    background:#1b1008;

    border-left:3px solid var(--gold);

    border-radius:8px;
}

.timeline-card h3{
    color:var(--gold2);
    margin-bottom:7px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:22px;
}

.card{
    overflow:hidden;

    background:
        linear-gradient(145deg,#29170a,#100a06);

    border:1px solid rgba(217,167,46,.25);

    border-radius:12px;

    transition:.25s;
}

.card:hover{
    transform:translateY(-5px);
    border-color:var(--gold);
}

.card img{
    width:100%;
    height:270px;

    display:block;

    object-fit:cover;

    background:#241409;
}

.card-content{
    padding:20px;
}

.card-content h3{
    color:var(--gold2);

    font-family:Cinzel,serif;

    margin-bottom:8px;
}

.card-content p{
    color:#cdbd9d;
    font-size:14px;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:18px;
}

.gallery-item{
    overflow:hidden;

    background:#140c07;

    border:1px solid rgba(217,167,46,.23);

    border-radius:10px;
}

.gallery-item img{
    width:100%;
    height:310px;

    object-fit:cover;

    display:block;
}

.gallery-item figcaption{
    padding:13px;

    color:#d8c7a2;

    font-size:13px;
}

.fact{
    max-width:900px;
    margin:auto;

    padding:45px;

    text-align:center;

    background:
        radial-gradient(circle,#3e240d,#100906);

    border:1px solid rgba(217,167,46,.3);

    border-radius:20px;
}

.fact-icon{
    font-size:75px;
    color:var(--gold);
}

.qr-section{
    background:
        radial-gradient(circle at center,#4b2b0d,#080504 72%);
}

.qr-card{
    max-width:650px;
    margin:auto;

    padding:35px 25px;

    text-align:center;

    color:#211304;

    background:#fff2c9;

    border-radius:20px;

    box-shadow:0 20px 70px rgba(0,0,0,.45);
}

.qr-card h3{
    color:#5c3812;

    font-family:Cinzel,serif;

    font-size:25px;
}

.website-url{
    margin-top:15px;

    padding:12px;

    width:100%;

    border:2px solid #b47c20;

    border-radius:8px;

    background:#fffaf0;

    color:#4d300e;

    font-size:13px;

    word-break:break-all;
}

#qrcode{
    width:280px;
    height:280px;

    margin:25px auto;

    padding:10px;

    display:flex;
    align-items:center;
    justify-content:center;

    background:#fff;

    border-radius:10px;
}

#qrcode canvas,
#qrcode img{
    max-width:100%;
    max-height:100%;
}

.qr-button{
    padding:11px 20px;

    margin:4px;

    border:0;

    border-radius:25px;

    background:#714812;

    color:white;

    font-weight:bold;

    cursor:pointer;
}

.qr-button:hover{
    background:#a16b1c;
}

.qr-note{
    margin-top:15px;

    padding:12px;

    background:#ffeab2;

    border-radius:8px;

    color:#68430e;

    font-size:13px;
}

.sources{
    max-width:950px;
    margin:auto;
}

.sources li{
    margin:12px 0;
}

.sources a{
    color:var(--gold2);
}

footer{
    padding:45px 20px;

    text-align:center;

    background:#050302;

    border-top:1px solid rgba(217,167,46,.2);

    color:#968664;
}

.footer-symbol{
    font-size:35px;
    color:var(--gold);
    margin-bottom:10px;
}

@media(max-width:900px){

    nav ul{
        display:none;
    }

    .two-columns{
        grid-template-columns:1fr;
    }

    .cards{
        grid-template-columns:1fr 1fr;
    }

    .gallery{
        grid-template-columns:1fr 1fr;
    }
}

@media(max-width:600px){

    section{
        padding:65px 5%;
    }

    .cards,
    .gallery{
        grid-template-columns:1fr;
    }

    .timeline-item{
        grid-template-columns:1fr;
        gap:4px;
    }

    .year{
        padding-top:0;
    }

    #qrcode{
        width:240px;
        height:240px;
    }

    .gallery-item img{
        height:320px;
    }
}
</style>
</head>


<body>


<!-- ===============================
     NAVIGATION
================================ -->

<nav>

    <div class="logo">
        𓂀 EGYPTIAN BEAUTY
    </div>

    <ul>

        <li>
            <a href="#history">
                ประวัติ
            </a>
        </li>

        <li>
            <a href="#ingredients">
                ส่วนผสม
            </a>
        </li>

        <li>
            <a href="#gallery">
                แกลเลอรี
            </a>
        </li>

        <li>
            <a href="#qr">
                QR Code
            </a>
        </li>

    </ul>

</nav>


<!-- ===============================
     HERO
================================ -->

<header class="hero">

    <div class="hero-inner">

        <div class="egypt-eye">
            𓂀
        </div>

        <div class="small-title">
            ANCIENT EGYPT • COSMETICS • BEAUTY
        </div>

        <h1>
            เครื่องสำอาง<br>
            อียิปต์โบราณ
        </h1>

        <p>
            สำรวจประวัติศาสตร์ความงามของชาวอียิปต์โบราณ
            ตั้งแต่ Kohl เครื่องสำอางสำหรับดวงตา
            แร่ธรรมชาติ ภาชนะโบราณ
            และอุปกรณ์ดูแลร่างกาย
        </p>

        <a
            class="button"
            href="#history">
            เริ่มสำรวจ
        </a>

    </div>

</header>


<!-- ===============================
     INTRODUCTION
================================ -->

<section class="intro">

    <div class="section-title">

        <h2>
            ความงามแห่งลุ่มแม่น้ำไนล์
        </h2>

        <p>
            Beauty in Ancient Egypt
        </p>

    </div>


    <div class="container two-columns">

        <div class="box">

            <h3>
                เครื่องสำอางไม่ได้มีไว้เพื่อความสวยเท่านั้น
            </h3>

            <p>
                ชาวอียิปต์โบราณใช้เครื่องสำอาง
                เพื่อเสริมรูปลักษณ์ ดูแลร่างกาย
                และในบางบริบทมีความเกี่ยวข้องกับ
                ความเชื่อและพิธีกรรม
            </p>

            <br>

            <p>
                เครื่องสำอางที่มีชื่อเสียงมากที่สุดคือ
                <strong>Kohl</strong>
                ซึ่งใช้ตกแต่งบริเวณรอบดวงตา
            </p>

        </div>


        <div class="box">

            <h3>
                ดวงตาแห่งฮอรัส
            </h3>

            <p>
                ดวงตามีความสำคัญอย่างมากในศิลปะอียิปต์
                และการวาดเส้นรอบดวงตาทำให้เกิดรูปลักษณ์
                ที่เป็นเอกลักษณ์ของความงามแบบอียิปต์
            </p>

            <br>

            <p>
                หลักฐานจากโบราณวัตถุจำนวนมาก
                แสดงให้เห็นว่ามีภาชนะสำหรับเก็บ
                เครื่องสำอางและอุปกรณ์สำหรับทา
            </p>

        </div>

    </div>

</section>


<!-- ===============================
     HISTORY
================================ -->

<section id="history">

    <div class="section-title">

        <h2>
            ประวัติศาสตร์
        </h2>

        <p>
            พัฒนาการของเครื่องสำอางในอียิปต์โบราณ
        </p>

    </div>


    <div class="timeline">


        <div class="timeline-item">

            <div class="year">
                ก่อนราชวงศ์
            </div>

            <div class="timeline-card">

                <h3>
                    จุดเริ่มต้นของการตกแต่งร่างกาย
                </h3>

                <p>
                    มีการใช้วัสดุจากธรรมชาติและแร่สีต่าง ๆ
                    เพื่อการตกแต่งร่างกายและใบหน้า
                </p>

            </div>

        </div>


        <div class="timeline-item">

            <div class="year">
                ราชอาณาจักรเก่า
            </div>

            <div class="timeline-card">

                <h3>
                    เครื่องสำอางกับชีวิตประจำวัน
                </h3>

                <p>
                    เครื่องสำอางและภาชนะต่าง ๆ
                    ปรากฏในบริบทของชีวิตและพิธีกรรม
                    รวมถึงการฝังศพ
                </p>

            </div>

        </div>


        <div class="timeline-item">

            <div class="year">
                2055–1650 BCE
            </div>

            <div class="timeline-card">

                <h3>
                    ราชอาณาจักรกลาง
                </h3>

                <p>
                    พบภาชนะเครื่องสำอางจำนวนมาก
                    ที่ทำจากหินและวัสดุหลากหลายชนิด
                </p>

            </div>

        </div>


        <div class="timeline-item">

            <div class="year">
                1550–1070 BCE
            </div>

            <div class="timeline-card">

                <h3>
                    ราชอาณาจักรใหม่
                </h3>

                <p>
                    เป็นช่วงที่มีหลักฐานเกี่ยวกับ Kohl
                    และอุปกรณ์เครื่องสำอางจำนวนมาก
                    รวมถึงหลอดและแท่งสำหรับทา
                </p>

            </div>

        </div>


    </div>

</section>


<!-- ===============================
     INGREDIENTS
================================ -->

<section id="ingredients">

    <div class="section-title">

        <h2>
            ส่วนผสมและวัสดุ
        </h2>

        <p>
            วัสดุที่พบในเครื่องสำอางและภาชนะโบราณ
        </p>

    </div>


    <div class="container cards">


        <article class="card">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_jar_MET_DP276010.jpg"
                alt="Kohl jar">

            <div class="card-content">

                <h3>
                    Kohl
                </h3>

                <p>
                    เครื่องสำอางสีเข้มสำหรับบริเวณดวงตา
                    เป็นหนึ่งในเครื่องสำอางที่พบหลักฐาน
                    ทางโบราณคดีจำนวนมาก
                </p>

            </div>

        </article>


        <article class="card">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_Jar_of_Sithathoryunet_MET_16.1.36a-b_EGDP017550_%28cropped%29.jpg"
                alt="Kohl Jar of Sithathoryunet">

            <div class="card-content">

                <h3>
                    Alabaster
                </h3>

                <p>
                    หินที่ถูกนำมาทำภาชนะเครื่องสำอาง
                    โดยเฉพาะภาชนะสำหรับเก็บ Kohl
                </p>

            </div>

        </article>


        <article class="card">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_jar_MET_DP276025.jpg"
                alt="Serpentinite Kohl jar">

            <div class="card-content">

                <h3>
                    Serpentinite
                </h3>

                <p>
                    หินสีเขียวเข้มที่พบในภาชนะเครื่องสำอาง
                    ของอียิปต์โบราณ
                </p>

            </div>

        </article>


        <article class="card">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_jar_MET_22.1.839_EGDP015879.jpg"
                alt="Obsidian Kohl jar">

            <div class="card-content">

                <h3>
                    Obsidian
                </h3>

                <p>
                    วัสดุสีดำมันวาวที่สามารถนำมาใช้
                    สร้างภาชนะและวัตถุสำหรับการดูแลร่างกาย
                </p>

            </div>

        </article>


        <article class="card">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_Jar_MET_26.8.38ab.back.jpg"
                alt="Kohl jar">

            <div class="card-content">

                <h3>
                    Diorite
                </h3>

                <p>
                    หินแข็งสีเข้มที่ถูกนำมาใช้ทำภาชนะ
                    และวัตถุที่เกี่ยวข้องกับการดูแลร่างกาย
                </p>

            </div>

        </article>


        <article class="card">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_tube_with_linen_stopper%2C_linen_-_Museo_Egizio_%28Turin%29_S_8615_04_p02.jpg"
                alt="Kohl tube">

            <div class="card-content">

                <h3>
                    Kohl Tube
                </h3>

                <p>
                    หลอดสำหรับเก็บเครื่องสำอาง
                    มีทั้งแบบทำจากไม้ หิน แก้ว
                    และวัสดุอื่น ๆ
                </p>

            </div>

        </article>


    </div>

</section>


<!-- ===============================
     GALLERY
================================ -->

<section id="gallery">

    <div class="section-title">

        <h2>
            แกลเลอรีโบราณวัตถุ
        </h2>

        <p>
            ตัวอย่างวัตถุเครื่องสำอางจากพิพิธภัณฑ์
        </p>

    </div>


    <div class="container gallery">


        <figure class="gallery-item">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_jar_MET_DP276010.jpg"
                alt="Ancient Egyptian Kohl jar">

            <figcaption>
                Kohl Jar — Ancient Egypt
            </figcaption>

        </figure>


        <figure class="gallery-item">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_Jar_of_Sithathoryunet_MET_16.1.36a-b_EGDP017550_%28cropped%29.jpg"
                alt="Kohl Jar of Sithathoryunet">

            <figcaption>
                Kohl Jar of Sithathoryunet
            </figcaption>

        </figure>


        <figure class="gallery-item">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_jar_MET_DP276025.jpg"
                alt="Serpentinite Kohl jar">

            <figcaption>
                Kohl Jar — Serpentinite
            </figcaption>

        </figure>


        <figure class="gallery-item">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_jar_MET_22.1.839_EGDP015879.jpg"
                alt="Obsidian Kohl jar">

            <figcaption>
                Kohl Jar — Obsidian
            </figcaption>

        </figure>


        <figure class="gallery-item">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_Jar_MET_26.8.38ab.back.jpg"
                alt="Kohl jar">

            <figcaption>
                Kohl Jar — New Kingdom
            </figcaption>

        </figure>


        <figure class="gallery-item">

            <img
                src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Kohl_tube_with_linen_stopper%2C_linen_-_Museo_Egizio_%28Turin%29_S_8615_04_p02.jpg"
                alt="Kohl tube">

            <figcaption>
                Kohl Tube — Museo Egizio
            </figcaption>

        </figure>


    </div>

</section>


<!-- ===============================
     FACT
================================ -->

<section>

    <div class="fact">

        <div class="fact-icon">
            𓂀
        </div>

        <h2 style="color:#ffe39a">
            ความงามที่คงอยู่มานับพันปี
        </h2>

        <br>

        <p>
            ภาชนะ Kohl และอุปกรณ์เครื่องสำอาง
            จำนวนมากยังคงหลงเหลือมาถึงปัจจุบัน
            ทำให้นักโบราณคดีสามารถศึกษาวัฒนธรรม
            เทคโนโลยี และแนวคิดเรื่องความงาม
            ของชาวอียิปต์โบราณได้
        </p>

    </div>

</section>


<!-- ===============================
     QR CODE
================================ -->

<section id="qr" class="qr-section">

    <div class="section-title">

        <h2>
            สแกนเข้าเว็บไซต์
        </h2>

        <p>
            QR Code สำหรับโทรศัพท์
        </p>

    </div>


    <div class="qr-card">

        <h3>
            𓂀 Ancient Egyptian Beauty 𓂀
        </h3>

        <p>
            สแกน QR นี้เพื่อเปิดเว็บไซต์
        </p>


        <div
            id="websiteUrl"
            class="website-url">
        </div>


        <div id="qrcode">
            กำลังสร้าง QR...
        </div>


        <button
            class="qr-button"
            onclick="downloadQR()">

            ⬇ ดาวน์โหลด QR

        </button>


        <button
            class="qr-button"
            onclick="copyWebsiteURL()">

            📋 คัดลอก URL

        </button>


        <div class="qr-note">

            📱 QR นี้ใช้ URL เว็บไซต์ GitHub Pages
            ไม่ใช้ file:// และไม่ชี้ไปยังไฟล์ในคอมพิวเตอร์

        </div>

    </div>

</section>


<!-- ===============================
     SOURCES
================================ -->

<section>

    <div class="section-title">

        <h2>
            แหล่งข้อมูล
        </h2>

        <p>
            แหล่งสำหรับศึกษาต่อ
        </p>

    </div>


    <div class="container sources">

        <ul>

            <li>
                <a
                    href="https://www.metmuseum.org/art/collection/search/544851"
                    target="_blank">
                    The Metropolitan Museum of Art — Kohl Tube
                </a>
            </li>

            <li>
                <a
                    href="https://www.metmuseum.org/art/collection/search/551055"
                    target="_blank">
                    The Metropolitan Museum of Art — Kohl Jar
                </a>
            </li>

            <li>
                <a
                    href="https://www.metmuseum.org/art/collection/search/572056"
                    target="_blank">
                    The Metropolitan Museum of Art — Kohl Tube and Stick
                </a>
            </li>

            <li>
                <a
                    href="https://commons.wikimedia.org/wiki/Category:Ancient_Egyptian_cosmetics_in_the_Metropolitan_Museum_of_Art"
                    target="_blank">
                    Wikimedia Commons — Ancient Egyptian Cosmetics
                </a>
            </li>

        </ul>

    </div>

</section>


<footer>

    <div class="footer-symbol">
        𓂀 𓋹 𓆣 𓅃
    </div>

    <p>
        Ancient Egyptian Beauty
    </p>

    <p>
        เว็บไซต์เพื่อการศึกษาเรื่องประวัติเครื่องสำอางอียิปต์โบราณ
    </p>

</footer>


<!-- ===============================
     QR LIBRARY
================================ -->

<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>


<script>

/*
===========================================================
เว็บไซต์ของคุณบน GitHub Pages
===========================================================
*/

const SITE_URL =
"https://changmobile0638948370-ui.github.io/b/";


/*
===========================================================
แสดง URL
===========================================================
*/

document.getElementById("websiteUrl").textContent =
    SITE_URL;


/*
===========================================================
สร้าง QR
===========================================================
*/

const qr =
    document.getElementById("qrcode");

qr.innerHTML = "";


new QRCode(
    qr,
    {
        text:SITE_URL,

        width:250,
        height:250,

        colorDark:"#000000",
        colorLight:"#ffffff",

        correctLevel:
            QRCode.CorrectLevel.H
    }
);


/*
===========================================================
ดาวน์โหลด QR
===========================================================
*/

function downloadQR(){

    const canvas =
        qr.querySelector("canvas");

    const image =
        qr.querySelector("img");


    if(canvas){

        const link =
            document.createElement("a");

        link.download =
            "ancient-egyptian-beauty-QR.png";

        link.href =
            canvas.toDataURL("image/png");

        link.click();

        return;
    }


    if(image){

        const link =
            document.createElement("a");

        link.download =
            "ancient-egyptian-beauty-QR.png";

        link.href =
            image.src;

        link.target =
            "_blank";

        link.click();

        return;
    }


    alert("ไม่พบ QR Code");
}


/*
===========================================================
คัดลอก URL
===========================================================
*/

function copyWebsiteURL(){

    navigator.clipboard
        .writeText(SITE_URL)
        .then(function(){

            alert(
                "คัดลอก URL แล้ว\n\n" +
                SITE_URL
            );

        })
        .catch(function(){

            alert(SITE_URL);

        });

}


/*
===========================================================
ระบบป้องกันภาพเสีย
===========================================================
*/

document.querySelectorAll("img")
.forEach(function(image){

    image.addEventListener(
        "error",
        function(){

            this.style.background =
                "linear-gradient(135deg,#2b1909,#080503)";

            this.alt =
                "ไม่สามารถโหลดภาพจากแหล่งภายนอกได้";

        }
    );

});

</script>

</body>
</html>
