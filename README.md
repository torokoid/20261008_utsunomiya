# 20261008_utsunomiya

<html lang="ja" data-loaded="false" data-scrolled="false" data-spmenu="closed">
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
p {
color: #fffafa;
font-size: 1.5em;
}


.red {color:#ff0000;}
.grey {color:#ffffff; background:#999999;}
.snow {color:#fffafa;}
.yellow {color:#ff0000; background:#ffff00;}
.blue {color:#0000ff;}
.white {color:#ffffff;}
.waku {border:2px dotted #99cc66;
line-height: 200%;
padding: 10px;}


main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}


/* 点滅 */
.blinking{
-webkit-animation:blink 1.5s ease-in-out infinite alternate;
-moz-animation:blink 1.5s ease-in-out infinite alternate;
animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@-moz-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/

/*背景を表示させる部分*/
body::before {
content:"";
display:block;
position:fixed;
top:0;
left:0;
z-index:-1;
width:100%;
height:100vh;
background:url(https://torokoid.github.io/20261008_utsunomiya/20261008_00022.jpeg) center/cover no-repeat;
-webkit-background-size:cover;/*Android4*/
}

a.p:hover {
position: relative;
text-decoration: none;
}
a.p span {
display: none;
position: relative;
top: -0.5em;
left: 2em;
}
a.p:hover span {
border: none;
display: block;
width: 800px;
}


@media screen and (min-width: 540px),
screen and (orientation: landscape) {
p.note { display: none; }
}


    
.media-container {
  width: 100%;
  max-width: 900px;
  margin: 0 auto;
}

.responsive-media {
  width: 100%;
  display: block;
}

.youtube-wrapper {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%; /* 16:9比率 */
  height: 0;
}

.youtube-wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
}





/* オープニング画面の初期状態 */
#splash {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background-color: #1a1a1a; /* 背景色（黒やブランドカラーなど） */
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 9999; /* 最前面に表示 */
  opacity: 1;
  visibility: visible;
  transition: opacity 0.8s ease, visibility 0.8s ease; /* 0.8秒かけてふわっと消える */
}

/* 読み込み完了後に付与するクラス（非表示状態） */
#splash.loaded {
  opacity: 0;
  visibility: hidden;
}

/* メインコンテンツ（最初は少し隠しておくと自然です） */
#container {
  opacity: 1;
}



</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>

<!-- オープニング（スプラッシュ画面） -->
<div id="splash">
  <div class="splash-content">
    <h1 class="splash-logo">HPに今風の動きを取り入れてみた</h1>
  </div>
</div>

<!-- メインコンテンツ -->
<div id="container">
  <h1>メインのホームページ画像</h1>
  <p>https://torokoid.github.io/20261008_utsunomiya/20261008_00022.jpeg</p>
</div>



<!--
    <p><a href="https://peyng.github.io/restart/">前回までの記録</a>><a><span class="grey">今回2026,05,28</span></a></p>
-->


<p class="note">
モバイル端末をお使いの場合は、画面を横向きにすると
背景画像の横方向がご覧頂けます。
</p>


<!--ここ上は、ほぼそのまま使います！-->


<!--QRコードの挿入例-->
<p align="left"> <img src="QR_2026Oct08.png" alt="アクセス用QRコード" width="100">QR for Access</p>
<p align="right"><marquee direction="left" scrollamount="20" width="30%">(^_^)/~PeYoung</marquee></p>

<!--流れ文字の挿入例-->
<h1><span class="yellow"><marquee behavior="left">!!! 2026/10/08、街中のスーパー銭湯「ゆ」から、カンセキのお花売り場とや夕焼け空まで !!!</marquee></span></h1>




<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<!--ここから下が、本体部分-->


<div class="media-container">

<h2><span class="yellow">2026Oct07、宇都宮4号線沿いのスーパー銭湯「ゆ」で肩こりをほぐします</span></h2>
<a href="20261008_00001.jpeg" target="_blank"><img src="20261008_00001.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">水曜平日のお昼は空いてます</span></h2>
<a href="20261008_00002.jpeg" target="_blank"><img src="20261008_00002.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">特製カレーをいただいて、食後にコーラも飲みました</span></h2>
<a href="20261008_00003.jpeg" target="_blank"><img src="20261008_00003.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00004.jpeg" target="_blank"><img src="20261008_00004.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">温泉から出たら、雲ひとつない秋の青空</span></h2>
<a href="20261008_00005.jpeg" target="_blank"><img src="20261008_00005.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">ホームセンター、カンセキに寄ります</span></h2>
<a href="20261008_00006.jpeg" target="_blank"><img src="20261008_00006.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">屋外お花売り場に夕陽が当たって、草花がニッコリ輝きました</span></h2>
<a href="20261008_00007.jpeg" target="_blank"><img src="20261008_00007.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00008.jpeg" target="_blank"><img src="20261008_00008.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00009.jpeg" target="_blank"><img src="20261008_00009.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00010.jpeg" target="_blank"><img src="20261008_00010.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00011.jpeg" target="_blank"><img src="20261008_00011.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00012.jpeg" target="_blank"><img src="20261008_00012.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00013.jpeg" target="_blank"><img src="20261008_00013.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00014.jpeg" target="_blank"><img src="20261008_00014.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00015.jpeg" target="_blank"><img src="20261008_00015.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00016.jpeg" target="_blank"><img src="20261008_00016.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00017.jpeg" target="_blank"><img src="20261008_00017.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00018.jpeg" target="_blank"><img src="20261008_00018.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00019.jpeg" target="_blank"><img src="20261008_00019.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00020.jpeg" target="_blank"><img src="20261008_00020.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00021.jpeg" target="_blank"><img src="20261008_00021.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00022.jpeg" target="_blank"><img src="20261008_00022.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00023.jpeg" target="_blank"><img src="20261008_00023.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00024.jpeg" target="_blank"><img src="20261008_00024.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00025.jpeg" target="_blank"><img src="20261008_00025.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00026.jpeg" target="_blank"><img src="20261008_00026.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00027.jpeg" target="_blank"><img src="20261008_00027.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00028.jpeg" target="_blank"><img src="20261008_00028.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00029.jpeg" target="_blank"><img src="20261008_00029.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261008_00030.jpeg" target="_blank"><img src="20261008_00030.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">西の空に夕陽が沈みます</span></h2>
<a href="20261008_00031.jpeg" target="_blank"><img src="20261008_00031.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">河内総合運動公園の丘とプール棟のお空も秋晴れ</span></h2>
<a href="20261008_00032.jpeg" target="_blank"><img src="20261008_00032.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">晩御飯はお魚とデザート</span></h2>
<a href="20261008_00033.jpeg" target="_blank"><img src="20261008_00033.jpeg" alt="サンプル画像" class="responsive-media"></a>



<h2><span class="yellow">JAしおのや、道の駅、うわだいらパーキングまでの移動経路はこんな感じ</span></h2>
<a href="20261008_00001.png" target="_blank"><img src="20261008_00001.png" alt="サンプル画像" class="responsive-media"></a>


<h2><span class="yellow">移動中の走行動画</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Kvle0K0ejWk?si=_CvtyDMxLNUBtBXs&autoplay=1&mute=1&loop=1&playlist=Kvle0K0ejWk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>






<br><br>

<!--
<h2><span class="yellow">以下、動画を11本</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/80OBLXk1o4s?si=Cdq4k5bPYmH2FsTb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
-->


<br><br><!--
<h2><span class="yellow">今回は、写真少なめでした！</span></h2>
-->

<!--
<h2><span class="yellow">今回の撮影範囲は、おおむね赤枠のエリア</span></h2>
<a href="20260228_059.PNG" target="_blank"><img src="20260228_059.PNG" alt="サンプル画像" class="responsive-media"></a>
<br><br>

<h2><span class="yellow">再掲ですが一点おまけ動画、メタバース上で公開された、まいてゃさん作のオリジナルソング「サンダーオンザゴーストロード」<br>2026年2月24日の新作です</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZtwhS51Oj2s?si=E6fP69LLlqTOz5Tb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>






<br>
<h2><span class="yellow">日没後に雷が鳴って雨の夜になったので星空は無し<br>星空アプリでいつもみている方向の画像撮りました<br>カノープスだけ図示</span></h2>
<a href="20260220_041.png" target="_blank"><img src="20260220_041.png" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">写真は星空全体で見ると、だいたいこの部分</span></h2>
<a href="20260219_037.png" target="_blank"><img src="20260219_037.png" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">今回はカノープスの写真は無し</span></h2>
-->




<br><br><br><!--
<h2><span class="yellow">月齢の説明リンク貼ります</span></h2>
<h2><a href="https://starwalk.space/ja/moon-calendar" target="_blank"><span class="snow">月齢カレンダー・リンク</span></a></h2><br><br>


<h2><span class="yellow">さそり座の説明リンク貼ります</span></h2>
<h2><a href="https://www.study-style.com/seiza/Sco.html" target="_blank"><span class="snow">さそり座・リンク</span></a></h2><br><br>

<h2><span class="yellow">カシオペヤ、説明リンク貼ります</span></h2>
<h2><a href="https://kids.yahoo.co.jp/zukan/astro/autumn/0004.html" target="_blank"><span class="snow">カシオペヤ・リンク</span></a></h2>

<h2><span class="yellow">アンドロメダ座、説明リンク貼りますね</span></h2>
    <h2><a href="https://www.shinko-keirin.co.jp/expo2025/constellation/andromeda/" target="_blank"><span class="snow">アンドロメダ座とは</span></a></h2>

<h2><span class="yellow">ペルセウス座、説明リンク貼りますね</span></h2>
    <h2><a href="https://www.dainippon-tosho.co.jp/star/2007/09/peruseusu.html" target="_blank"><span class="snow">ペルセウス座とは</span></a></h2>

<h2><span class="yellow">おひつじ座、説明リンク貼りますね</span></h2>
    <h2><a href="https://www.dainippon-tosho.co.jp/star/2014/12/ohitujiza.html" target="_blank"><span class="snow">おひつじ座とは</span></a></h2>

<h2><span class="yellow">ぎょしゃ座、説明リンク貼りますね</span></h2>
    <h2><a href="https://www.dainippon-tosho.co.jp/star/2026/01/gyosyaza.html" target="_blank"><span class="snow">ぎょしゃ座とは</span></a></h2>

<h2><span class="yellow">いっかくじゅう座、説明リンク貼りますね</span></h2>
    <h2><a href="https://www.astroarts.co.jp/article/hl/a/13376_mook-mon" target="_blank"><span class="snow">いっかくじゅう座とは</span></a></h2>

<h2><span class="yellow">おおいぬ座、説明リンク貼りますね</span></h2>
    <h2><a href="https://www.astroarts.co.jp/article/hl/a/13373_mook-cma" target="_blank"><span class="snow">おおいぬ座とは</span></a></h2>

<h2><span class="yellow">冬の大三角形、説明リンク貼りますね</span></h2>
    <h2><a href="https://www.kenko-tokina.co.jp/special/celestial/201601_sorawomiyou.html" target="_blank"><span class="snow">冬の大三角形とは</span></a></h2>

<h2><span class="yellow">すばる、説明リンクします</span></h2>
    <h2><a href="https://www.kahaku.go.jp/exhibitions/vm/resource/tenmon/space/nebula/nebula02.html" target="_blank"><span class="snow">すばるとは</span></a></h2>

<h2><span class="yellow">おうし座、説明リンクします</span></h2>
    <h2><a href="https://www.kyoiku-shuppan.co.jp/docs/pages/rika/guide/astro/ousiza.html" target="_blank"><span class="snow">おうし座とは</span></a></h2>

<h2><span class="yellow">ふたご座、説明リンクします</span></h2>
    <h2><a href="https://www.kyoiku-shuppan.co.jp/docs/pages/rika/guide/astro/hutagoza.html" target="_blank"><span class="snow">ふたご座とは</span></a></h2>

<h2><span class="yellow">こいぬ座、説明リンクします</span></h2>
    <h2><a href="https://www.kyoiku-shuppan.co.jp/docs/pages/rika/guide/astro/koinuza.html" target="_blank"><span class="snow">こいぬ座とは</span></a></h2>

<h2><span class="yellow">カノープス、再度説明リンクします</span></h2>
    <h2><a href="https://www.astroarts.co.jp/special/2025canopus/index-j.shtml" target="_blank"><span class="snow">カノープスとは</span></a></h2>
-->

    
<!--
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/51tmW4PV-Xw?si=v7PtzTJ3WaY8o6uJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>

<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/MvsoLLa-XHQ?si=-zvqXbodBPV2nEFE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>

<h2><span class="yellow">Short movies</span></h2>
https://youtube.com/shorts/773yijDWNEM?feature=share<br>
https://youtube.com/shorts/fXWujjVeAQo?feature=share<br>
https://youtube.com/shorts/43kwtgxybM8?feature=share<br>
https://youtube.com/shorts/jKhX0RtXWAk?feature=share<br>
https://youtube.com/shorts/Fqw8KGuUPtA?feature=share<br>
https://youtube.com/shorts/ieJlzaTlpn0?feature=share<br>
https://youtube.com/shorts/z8YXZQyPVMA?feature=share<br>
https://youtube.com/shorts/1MxKGMEFFR4?feature=share<br>
-->

<br><br><br><br><br><br><br><br><br>

<br><br>

<h2><span class="yellow">今日のBGMは、Soothing Music + Bamboo Water Sounds 🌿 Deep Relaxation for Calm Sleep and Inner Peace Tonight *47</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZVait79WDOg?si=qlOUcrXLc6jFRpKx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>

<!--
<h2><span class="yellow">おまけ(再掲)、メタバース内で解説された、遠野物語</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/ngocglcJSdw?si=4-3NAM7-NH6FAQGL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
-->
<!--
<h2><span class="yellow">さらにもう1曲、The Good, the Bad and the Ugly - The Danish National Symphony Orchestra (Live)</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/enuOArEfqGo?si=XPNuIaDbLYRTPL2e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>


<br><br><br><br>

<h2><span class="yellow">以下、しばらく据え置きます</span></h2>

<br><br>

<h2><span class="yellow">今日の1曲は再掲ですが、Sinead O'Connor - Nothing Compares 2 U (Live)</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/NAOKzvL8dgk?si=QPHFN3aQAECEKtE-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>


<h2><span class="yellow">こちらがオリジナル、Prince - Nothing Compares 2 U (Live At Paisley Park, 1999)</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/1NarDEEhOsM?si=879m1krkyyWdnJtg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>


<h2><span class="yellow">さらにもう一曲プリンスといえばこれ、Prince - Purple Rain (Live At Paisley Park, 1999)<br>プログレッシブロックなので好みが分かれるところですが・・・</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/ryT-ltTDCko?si=HhEEKCeje68xjVeJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
-->

<!--
<h2><span class="yellow">最後の一曲は、Toshl 365日の紙飛行機(AKB48さんカバー)</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/gTSIQIWvb0A?si=10YFot0Zc02i0sq5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
-->

<br><br><br>
<h2><span class="yellow">2026Oct08、街中のスーパー銭湯「ゆ」から、カンセキのお花売り場とや夕焼け空まででした<br>Thank you for reading this far.</span></h2>
<!--
<br><br><br><br><br>
<h2><span class="yellow">
<a href="https://torokoid.github.io/Mashiko_himawari_3/" target="_blank">クリックでメニューページに戻ります</a>
</span></h2>
-->

<br><br><br>

<!-- hitwebcounter Code START -->
<a href="https://www.hitwebcounter.com" target="_blank">
<p>you are <img src="https://hitwebcounter.com/counter/counter.php?page=21345151&style=0018&nbdigits=5&type=page&initCount=0" title="Counter Widget" Alt="Visit counter For Websites"   border="0" />visitor<br>The numbers are cumulative for the Bangkok ＆ Utsunomiya series websites launched since 2025 August 1st.</p></a>   



<style>
.responsive-media {
    opacity: 1 !important;
    filter: brightness(100%) !important;
}
</style>


<br><br><br><br><br><br><br><br><br>





<br><br>

<br><br><br><br><br><br>

<!--本体はここまで-->
    </div>

<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
<p>Copyright 2026/10/08 PeYoung</p>
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>



window.addEventListener('load', function() {
  const splash = document.querySelector('#splash');
  
  // 0.5秒（500ミリ秒）ほど待ってからフェードアウトを開始する
  setTimeout(function() {
    splash.classList.add('loaded');
  }, 500);
});





    </body>
    
</html>
