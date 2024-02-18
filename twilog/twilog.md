自動改行しないで作成しています。
HEAD内はトップと共通です。

HEAD
<style type="text/css">

@charset "UTF-8";

@import url('https://fonts.googleapis.com/css?family=Dosis');


body {
    background:linear-gradient(90deg, #ebf0f6 0%, #ebf0f6 50%, #98ccd3 50%, #98ccd3 100%);
    color: #132238;
    font-size: 15px;
    font-family: 'Dosis', 'STHeitiSC-Light', 'Microsoft YaHei', gulim, メイリオ, sans-serif;
    line-height: 200%;
    letter-spacing: 2px;
    margin: 0;
    padding: 0;
}

a {
    color: #98ccd3;
    text-decoration: none;
}

a:hover, active {
    color: #98ccd3;
    background: none;
}

h1 {
    font-weight: 200;
    margin: 5px 3px;
}

h1 p {
    display: inline-block;
    font-size: 12px;
    margin: 0 0 0 20px;
} 

h2 {
    text-align: center;
    border-bottom:3px solid #ebf0f6;
    position: relative;
    margin: 0 10px 30px;
    padding-bottom: 5px;
}
 
h2:before {
    content:"";
    display:block;
    width:50%;
    border-bottom:3px solid #98ccd3;
    position:absolute;
    bottom:0;
    margin-bottom:-3px;
}

h3 {
    color: #fff;
    margin: 20px 3px 10px;
    padding: 2px 5px;
    display: inline-block;
    background: #98ccd3;
    border: solid 1px #ebf0f6;
    box-shadow: 0px 0px 0px 2px #98ccd3;
}

b {
    background: #ebf0f6;
}

input[type],textarea {
    height: 50px;
    width: 50%;
    font-size: 12px;
    font-family: 'Dosis', 'STHeitiSC-Light', 'Microsoft YaHei', gulim, メイリオ, sans-serif;
    line-height: 200%;
    letter-spacing: 2px;
    color: #132238;
    background: #ebf0f6;
    border: solid 1px #fff;
        -webkit-appearance: none;
    border-radius: 3px;
    box-shadow: none;
    margin: 3px 0;
    padding: 3px;
}

input[type=text ]{
    height: auto;
    width: 80px;
}

input[type=submit]{
    height: auto;
    width: 40px;
    cursor: pointer;
    text-shadow: none;
    background: #364e68;
    color:#ebf0f6;
    font-weight: 200;
}


.wrp {
    margin: 50px 0 0;
    padding: 0 0 20px;
    background: #fff;
    width: 100%;
}

.top {
    color: #ebf0f6;
    margin: 50px auto 20px;
    padding: 10px;
    background: #364e68;
    border: solid 1px #ebf0f6;
    box-shadow: 0px 0px 0px 5px #364e68;
    max-width: 250px;
}

.menu {
    text-align: center;
    margin-bottom: 5px;
}

.menu a {
    color: #ebf0f6;
    margin: 0 5px;
    font-size: 13px;
    border-bottom: solid 1px #98ccd3;
}

.menu a:hover {
    color: #98ccd3;
    border: none;
}

.main {
    max-width: 500px;
    margin: 0 auto;
    padding: 30px 20px 10px;
}

.box {
    background: #ebf0f6;
    margin: 20px 0 10px;
    padding: 5px 10px;
}

.box a {
    color: #364e68;
}

.box a:hover {
    color: #98ccd3;
}

.box p {
    font-weight: 700;
    margin: -18px 0 0;
    padding: 0;
}
</style>

全体レイアウト
<div class="wrp">
<div class="main">#note#


追記画面レイアウト
<h3>#date#</h3>　#title#<br>
#text2#<br>
<br>
<br>

上部表示テキスト



ノート部分 
<h3>#title#</h3>　<br>
#body#<br>
#iine#

<br>
<br>
<h2></h2>
<br>


下部表示テキスト
</div><center class="backBtn-grid">##prev(←prev)## | ##next(next→)##</center>

