HEAD
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.4.2/css/all.css" integrity="sha384-/rXc/GQVaYpyDdyxK+ecHPVYJSN9bmVFBvjA/9eOB+pb3F2w2N6fc5qB9Ew5yIns" crossorigin="anonymous">

<style type="text/css">

@charset "UTF-8";

@import url('https://fonts.googleapis.com/css?family=KoHo ');

@font-face
{
font-family: はれのそら明朝;
src: url('https://cdn.leafscape.be/Harenosora/harenosora_web.woff2')
     format("woff2");
}
/*-------------------------------------------------
このフォントはIPAフォントライセンスv1.0の下で提供されています。
http://ipafont.ipa.go.jp/ipa_font_license_v1.html
オリジナルのフォントは以下から取得できます。
http://fontopo.com/?p=377
http://ipafont.ipa.go.jp/
-------------------------------------------------*/

@media screen and (max-width: 480px) {

    body{
            padding: 50px 0 0;
    }

    .top {
        top: 0;
        left:0;
        display: flex;
        position: fixed;
        padding: 0;
        margin: 0;
    }

    .menu {
        display: table;
        table-layout: fixed;
    }

    .menu li {
        display: table-cell;
        vertical-align: middle;
    }

    .main{
        margin:10px 20px 0;
    }
}

@media screen and (min-width: 481px) {
    .wrp {
        max-width: 800px;
        overflow: hidden;
    }

    .top{
        width: 150px;
        float: left;
        margin: 50px 15px 0 20px;
    }

    .main{
        margin: 50px 20px 0 200px;
    }

    .menu li {
        display: inline;
    }

}

body {
    background: #e9e9e9;
    color: #333;
    font-size: 12px;
    font-family: 'KoHo', 'STHeitiSC-Light', 'Microsoft YaHei', gulim, メイリオ, sans-serif;
    line-height: 180%;
    letter-spacing: 2px; 
}

a {
    color: #88bbd6;
    text-decoration: none;
}

a:hover, active {
    position: relative;
    top: 0;
}

h1 {
    font-size: 14px;
    border-bottom: 1px solid #69c5c5;
    display: inline-block;
    padding: 5px;
    margin: 0 0 10px;
    font-weight: 200;
}

h2 {
    font-size: 14px;
    border-bottom: 1px solid #69c5c5;
    display: inline-block;
    padding: 5px 20px 5px 5px;
    margin: 0 0 10px;
    font-weight: 200;
    text-transform: uppercase;
}

h3 {
    font-size: 12px;
    border: 1px solid #cdcdcd;
    background: #cdcdcd;
    display: inline-block;
    padding: 0 5px;
    margin: 10px 0;
    font-weight: 200;
    text-transform: uppercase;
}

hr {
    border-top: solid 1px #cdcdcd;
    border-left: none;
    border-bottom: none;
}

b {
    font-weight: 200;
    background: #c1e4e9;
}

textarea {
    height: 50px;
    width: 50%;
    font-size: 12px;
    font-family:  'KoHo', 'STHeitiSC-Light', 'Microsoft YaHei', gulim, メイリオ, sans-serif;
    line-height: 180%;
    letter-spacing: 2px;
    color: #333;
    background: #cdcdcd;
    border: solid 1px #cdcdcd;
        -webkit-appearance: none;
    border-radius: 0;
    box-shadow: none;
    margin: 3px 0;
    padding: 3px;
}

.wrp {
    margin:0 auto;
    padding: 0;
}

.top {
    z-index: 99;
}

.menu {
    background: #69c5c5;
    text-align: center;
    width: 100%;
    padding: 0;
    margin: 0;
}

.menu li a {
    color: #e9e9e9;
    display: block;
    text-decoration: none;
    padding: 10px 0;
    text-transform: uppercase;
}

.menu li a:hover, active {
    background: #69c5c5;
    display: block;
    padding: 10px 0;
}

.main {
    text-align: center;
}

.title {
    position: relative;
    width: 80%;
    margin: 20px auto;
}

.title p {
    font-family: はれのそら明朝, 'Merriweather Sans', 'STHeitiSC-Light', 'Microsoft YaHei', gulim, メイリオ, sans-serif;
    font-size: 20px;
    font-weight: 200;
    color: #e9e9e9;
    position: absolute;
    top: 70%;
    left: 50%;
        -ms-transform: translate(-50%, -50%);
        -webkit-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    margin: 0;
    padding: 0;
}

.title img {
    width: 100%;
    margin: 0;
}

.box {
    color: #aaa;
    margin: 10px;
    border: solid 1px #cdcdcd;
    padding: 8px;
}

.right {
    text-align: right;
}

.left {
    text-align: left;
}

</style>
<style type="text/css">
button.original-evaluation-btn {
    appearance: none;
    -webkit-appearance: none;
    display: inline-block;
	*display: inline; /*for IE*/
	*zoom: 1; /*for IE*/
	margin: 2px;
	color: #696969;
	padding: 2px 4px;
	margin-left: 2px;
	margin-right: 2px;
	border: 1px solid #e6e6fa;
	background-color: #f0f8ff;
	-moz-border-radius: 3px;
    -webkit-border-radius: 3px;
    border-radius: 3px;
    font-size: 14px;
}
button.original-evaluation-btn:hover {
    color: #ff7f50;
    background-color: #f1f2f3;
}
button.original-evaluation-btn span {
    color: #f45b5b;
}

</style>

<style type="text/css">
<!--
/* 吹き出し */
/* 全体のスタイル */
.kaiwa {
    margin-bottom: 5px;
}
/* 左画像 */
.kaiwa-img-left {
    margin: 0;
    float: left;
    width: 60px;
    height: 60px;
    margin-right: -70px;
}
/* 右画像 */
.kaiwa-img-right {
    margin: 0;
    float: right;
    width: 60px;
    height: 60px;
    margin-left: -70px;
}
.kaiwa figure img {
    width: 100%;
    height: 100%;
    border: 1px solid #aaa;
    border-radius: 50%;
    margin: 0;
}
/* 左からの吹き出しテキスト */
.kaiwa-text-right {
    position: relative;
    margin-left: 80px;
    padding: 10px;
    border-radius: 10px;
    margin-right: 12%;
    float: left;
}
/* 右からの吹き出しテキスト */
.kaiwa-text-left {
    position: relative;
    margin-right: 80px;
    padding: 10px;
    border-radius: 10px;
    margin-left: 12%;
    float: right;
}
p.kaiwa-text {
    margin: 0 0 20px;
    padding-top: 0 !important;
}
p.kaiwa-text:last-child {
    margin-bottom: 0;
}
/* 左の三角形を作る */
.kaiwa-text-right:before {
    position: absolute;
    content: "";
    border: 10px solid transparent;
    top: 1px; 
    left: -19px;
    -ms-transform: rotate(35deg);
    -webkit-transform: rotate(35deg);
    transform: rotate(35deg);
}
.kaiwa-text-right:after {
    position: absolute;
    content: "";
    border: 10px solid transparent;
    top: 1px; 
    left: -12px;
    -ms-transform: rotate(35deg);
    -webkit-transform: rotate(35deg);
    transform: rotate(35deg);
}
/* 右の三角形を作る */
.kaiwa-text-left:before {
    position: absolute;
    content: "";
    border: 10px solid transparent;
    top: 1px; 
    right: -19px;
    border: 8px solid transparent;
    -ms-transform: rotate(-35deg);
    -webkit-transform: rotate(-35deg);
    transform: rotate(-35deg);
}
.kaiwa-text-left:after {
    position: absolute;
    content: "";
    border: 10px solid transparent;
    top: 1px; 
    right: -10px;
    border: 8px solid transparent;
    -ms-transform: rotate(-35deg);
    -webkit-transform: rotate(-35deg);
    transform: rotate(-35deg);
}
/* 回り込み解除 */
.kaiwa:after,.kaiwa:before {
    clear: both;
    content: "";
    display: block;
}
/* 名前 */
.kaiwa-name-right {
    position: relative;
    margin-left: 80px;
    font-size: 10px;
    text-align: left;
    font-weight: bold;
}
.kaiwa-name-left {
    position: relative;
    margin-right: 80px;
    font-size: 10px;
    text-align: right;
    font-weight: bold;
}
-->
</style>


上部表示テキスト
<center><h2>#note_title#</h2>
<p style="opacity:0.9">小ネタとか会話集とかのネタ置き場
いいねが多かったら何かしらの作品にするかもしれない</p>
<hr>
</center>


ノート部分 
<h3>#date#</h3> #title#<br>
#body#<br>
#iine#
<hr>


下部表示テキスト
<center class="backBtn-grid">##prev(←prev)## | ##next(next→)##</center>




