```HTML検定解答```

```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="utf-8">
<title>HAPPINESS FITNESS CLUB</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>
<header>
	<h1><img src="images/logo.png" width="203" height="70" alt="ハピネスフィットネスクラブ"></h1>
	<nav>
		<ul>
			<li><a href="info.html"><img src="images/nav1.png" width="173" height="50" alt="施設のご案内"></a></li>
			<li><a href="fee.html"><img src="images/nav2.png" width="173" height="50" alt="料金プラン"></a></li>
			<li><a href="opinion.html"><img src="images/nav3.png" width="173" height="50" alt="ご意見・ご要望"></a></li>
		</ul>
	</nav>
</header>
<div id="contents">
	<div id="main">
		<p id="graphic"><img src="images/graphic.jpg" width="570" height="300" alt="ハピネスフィットネスクラブでは さまざまなプログラムをご用意しております。"></p>
		<section>
			<h2>今月のお知らせ</h2>
			<p>入会された方に、ミネラルウォーターをプレゼントいたします。<br>運動中の水分補給にお使いください。</p>
		</section>
	</div>
	<div id="sub">
		<aside>
			<ul>
				<li><a href="info.html"><img src="images/bnr_info.png" width="200" height="80" alt="施設のご案内"></a></li>
				<li><a href="opinion.html"><img src="images/bnr_opinion.png" width="200" height="50" alt="ご意見・ご要望"></a></li>
			</ul>
		</aside>
	</div>
</div>
<footer>
	<p><small>Copyright 2014 HAPPINESS FITNESS CLUB All rights reserved.</small></p>
</footer>
</body>
</html>
```

```html
<!-- info.html -->
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="utf-8">
<title>施設のご案内 - HAPPINESS FITNESS CLUB</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>
<header>
	<h1><a href="index.html"><img src="images/logo.png" width="203" height="70" alt="ハピネスフィットネスクラブ"></a></h1>
	<nav>
		<ul>
			<li><a href="info.html"><img src="images/nav1.png" width="173" height="50" alt="施設のご案内"></a></li>
			<li><a href="fee.html"><img src="images/nav2.png" width="173" height="50" alt="料金プラン"></a></li>
			<li><a href="opinion.html"><img src="images/nav3.png" width="173" height="50" alt="ご意見・ご要望"></a></li>
		</ul>
	</nav>
</header>
<div id="contents">
	<div id="main">
		<article>
			<h1>施設のご案内</h1>
			<p><img src="images/pic.jpg" width="200" height="200" alt="" class="float_right">当施設は、スタジオやプールのほか、100台ものマシンを所有するフィットネスクラブです。</p>
			<p>マシンはフィットネスに合わせた様々な設備が揃い、各専門分野のインストラクターが常に指導できるよう常駐しています。<br>
			肩こりや腰痛の改善、ダイエット、体力づくりなど、様々な目的に合わせて専門のインストラクターから的確なアドバイスが受けられる体制を整えています。</p>
			<p>スタジオプログラムは多彩なプログラムをご用意し、随時開催しています。定員さえ超えなければ、いくつでもご自由にご参加いただけます。</p>
			<p>大浴場は、ジェットバス、シャワー、サウナ、水風呂を完備し、マッサージルームでは運動後の疲れや痛みを残さないよう資格をもったスタッフがマッサージをいたします。</p>
			<p>ご興味のある方は、ぜひ無料見学にお越しください。</p>
		</article>
	</div>
	<div id="sub">
		<aside>
			<ul>
				<li><a href="info.html"><img src="images/bnr_info.png" width="200" height="80" alt="施設のご案内"></a></li>
				<li><a href="opinion.html"><img src="images/bnr_opinion.png" width="200" height="50" alt="ご意見・ご要望"></a></li>
			</ul>
		</aside>
	</div>
</div>
<footer>
	<p><small>Copyright 2014 HAPPINESS FITNESS CLUB All rights reserved.</small></p>
</footer>
</body>
</html>
```

```html
<!-- fee.html -->
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="utf-8">
<title>料金プラン - HAPPINESS FITNESS CLUB</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>
<header>
	<h1><a href="index.html"><img src="images/logo.png" width="203" height="70" alt="ハピネスフィットネスクラブ"></a></h1>
	<nav>
		<ul>
			<li><a href="info.html"><img src="images/nav1.png" width="173" height="50" alt="施設のご案内"></a></li>
			<li><a href="fee.html"><img src="images/nav2.png" width="173" height="50" alt="料金プラン"></a></li>
			<li><a href="opinion.html"><img src="images/nav3.png" width="173" height="50" alt="ご意見・ご要望"></a></li>
		</ul>
	</nav>
</header>
<div id="contents">
	<div id="main">
		<article>
			<h1>料金プラン</h1>
			<table>
				<caption><strong>ご利用料金</strong><p>ご利用する時間帯、料金をご確認いただき、ご希望に合った会員プランをお選びください。また、入会金、年会費等は一切かかりませんので、お気軽にご入会ください。</p></caption>
				<tr>
					<th scope="col">会員プラン</th>
					<th scope="col">利用時間</th>
					<th scope="col" class="price">金額</th>
				</tr>
				<tr>
					<td>正会員A(全施設利用)</td>
					<td rowspan="2">10:00-23:00</td>
					<td class="price">9,625円/月</td>
				</tr>
				<tr>
					<td>正会員B(プールのみ利用)</td>
					<td class="price">3,980円/月</td>
				</tr>
				<tr>
					<td>デイ会員</td>
					<td>10:00-18:00</td>
					<td class="price">6,890円/月</td>
				</tr>
				<tr>
					<td>ナイト会員</td>
					<td>18:00-23:00</td>
					<td class="price">7,950円/月</td>
				</tr>
				<tr>
					<td>都度会員</td>
					<td>10:00-23:00</td>
					<td class="price">ご利用1回ごとに<br>2,030円</td>
				</tr>
			</table>
		</article>
	</div>
	<div id="sub">
		<aside>
			<ul>
				<li><a href="info.html"><img src="images/bnr_info.png" width="200" height="80" alt="施設のご案内"></a></li>
				<li><a href="opinion.html"><img src="images/bnr_opinion.png" width="200" height="50" alt="ご意見・ご要望"></a></li>
			</ul>
		</aside>
	</div>
</div>
<footer>
	<p><small>Copyright 2014 HAPPINESS FITNESS CLUB All rights reserved.</small></p>
</footer>
</body>
</html>
```
```html
<!-- opinion.html -->
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="utf-8">
<title>ご意見・ご要望 - HAPPINESS FITNESS CLUB</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>
<header>
	<h1><a href="index.html"><img src="images/logo.png" width="203" height="70" alt="ハピネスフィットネスクラブ"></a></h1>
	<nav>
		<ul>
			<li><a href="info.html"><img src="images/nav1.png" width="173" height="50" alt="施設のご案内"></a></li>
			<li><a href="fee.html"><img src="images/nav2.png" width="173" height="50" alt="料金プラン"></a></li>
			<li><a href="opinion.html"><img src="images/nav3.png" width="173" height="50" alt="ご意見・ご要望"></a></li>
		</ul>
	</nav>
</header>
<div id="contents">
	<div id="main">
		<article>
			<h1>ご意見・ご要望</h1>
			<p>サービス改善のため、皆様のお声をお聞かせください。<br>
			会員の方はもちろん、ご入会を検討している方のご意見・ご要望もお待ちしております。</p>
			<form action="#">
				<p><label>お名前<br>
				<input type="text" name="name" class="textfield"></label></p>
				<p><label>ご意見・ご要望<br>
				<textarea name="comment"></textarea></label></p>
				<p><input type="submit" value="確認する"></p>
			</form>
		</article>
	</div>
	<div id="sub">
		<aside>
			<ul>
				<li><a href="info.html"><img src="images/bnr_info.png" width="200" height="80" alt="施設のご案内"></a></li>
				<li><a href="opinion.html"><img src="images/bnr_opinion.png" width="200" height="50" alt="ご意見・ご要望"></a></li>
			</ul>
		</aside>
	</div>
</div>
<footer>
	<p><small>Copyright 2014 HAPPINESS FITNESS CLUB All rights reserved.</small></p>
</footer>
</body>
</html>
```


```css
<!-- style.css -->
@charset "utf-8";

/* 基本レイアウト ここから↓ */
@import url(common.css);
header {
	width: 800px;
	height: 70px;
	margin: 20px auto 40px auto;
	position: relative;
}
header h1 {
	margin : 0;
	position: absolute;
}
nav {
	position: absolute;
	right: 0;
}
nav ul {
	list-style-type: none;
	overflow: hidden;
}
nav ul li {
	float: left;
}
nav ul li a:hover {
	opacity: 0.7;
}
footer p {
	margin-bottom: 0;
	padding: 14px 0 14px 0;
	background-image: url(../images/bg_footer.png);
	background-repeat: repeat-x;
	text-align: center;
}
footer small {
	font-size: 100%;
}
#main h1 {
	margin: 0 0 20px 0;
	padding: 8px 0 3px 40px;
	background-image: url(../images/h1.png);
	background-repeat: no-repeat;
	font-size: 162%;
}
/* 基本レイアウト ここまで↑ */

/* 「施設のご案内」ページ ここから↓ */
img.float_right {
	margin-bottom: 20px;
	margin-left: 20px;
	float: right;
}
/* 「施設のご案内」ページ ここまで↑ */

/* 「料金プラン」ページ ここから↓ */
table {
	width: 568px;
	margin-bottom: 20px;
	border-collapse: collapse;
}
table caption {
	text-align: left;
}
table th, table td {
	width: 190px;
	padding: 10px;
	border: 1px solid #7aa7a2;
	text-align: center;
}
table th {
	background-color: #cce8e4;
}
table .price {
	width: 125px;
}
table td.price {
	text-align: right;
}
/* 「料金プラン」ページ ここまで↑ */

/* 「ご意見・ご要望」ページ ここから↓ */
form {
	margin-top: 30px;
}
input.textfield, textarea {
	border: 1px solid #d1ccb4;
}
input.textfield {
	width: 250px;
}
textarea {
	width: 500px;
	height: 170px;
	overflow-y: scroll;
}
/* 「ご意見・ご要望」ページ ここまで↑ */
```