# Lab4web
# Praktikum 4
```
Fahmi Abdul Muthi
311910463
TI.19.A2
```
# Langkah 1
Membuat sebuah dokumen html dengan nama file lab4_box.html kemudian tambahkan kode untuk membuat box element dengan tag ```<div>.```
![11](https://user-images.githubusercontent.com/56380765/115444291-91a34300-a23e-11eb-917c-e8f3617b2b3f.png)

Kemudian tambahkan deklarasi CSS pada ```<head>``` untuk membuat float element.
![112](https://user-images.githubusercontent.com/56380765/115444581-f199e980-a23e-11eb-9914-847bc077a3e7.png)

Mengatur clearfix element menggunakan property clear.
![113](https://user-images.githubusercontent.com/56380765/115444827-476e9180-a23f-11eb-8e80-50e5b778bd16.png)

Membuat Layout sederhana seperti gambar berikut
![layout](https://user-images.githubusercontent.com/56380765/115445334-ebf0d380-a23f-11eb-926a-af06639b97f7.jpg)

# langkah1

Membuat folder baru dengan nama lab4_layout kemudian buat file baru di dalam folder tersebut dengan nama home.html dan style.css. Lalu tambahkan kode berikut untuk membuat kerangka layout dengan semantic element.
![114](https://user-images.githubusercontent.com/56380765/115445806-8c46f800-a240-11eb-828c-12065a6bb384.png)

# langkah 2
![115](https://user-images.githubusercontent.com/56380765/115445977-bf898700-a240-11eb-8537-ee96faf222cf.png)

# langkah 3
membuat navigasi
![116](https://user-images.githubusercontent.com/56380765/115446114-ee076200-a240-11eb-9020-dc7a3f8e5c08.png)

# langkah 4
membuat hero panel
tambah element pada home.html
```<section id="hero">
    <h1>Hello World!</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
    <a href="home.html" class="btn btn-large">Learn more &raquo;</a>
</section>
```
tambahkan element pada style.css
```/* Hero Panel */
#hero {
    background-color: #e4e4e5;
    padding: 50px 20px;
    margin-bottom: 20px;
}
#hero h1 {
    margin-bottom: 20px;
    font-size: 35px;
}
#hero p {
    margin-bottom: 20px;
    font-size: 18px;
    line-height: 25px;
}
```
mengatur layout main dan sidebar

tambahkan element pada style.css
```/* main content */
#wrapper {
    margin: 0;
}
#main {
    float: left;
    width: 640px;
    padding: 20px;
}

/* sidebar area */
#sidebar {
    float: left;
    width: 260px;
    padding: 20px;
}
```
hasil nya
![117](https://user-images.githubusercontent.com/56380765/115446575-9e756600-a241-11eb-8be9-551f015a3fef.png)

# Langkah 5
membuat sidebar widget
tambahkan element pada home.html
```<aside id="sidebar">
    <div class="widget-box">
        <h3 class="title">Widget Header</h3>
        <ul>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
       </ul>
    </div>
    <div class="widget-box">
       <h3 class="title">Widget Text</h3>
       <p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt
arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer
pharetra est nunc, nec pretium nunc pretium ac.</p>
   </div>
</aside>
```
tambahkan element pada style.css
```/* widget */
.widget-box {
    border:1px solid #eee;
    margin-bottom:20px;
}
.widget-box .title {
    padding:10px 16px;
    background-color:#428bca;
    color:#fff;
}
.widget-box ul {
    list-style-type:none;
}
.widget-box li {
    border-bottom:1px solid #eee;
}
.widget-box li a {
    padding:10px 16px;
    color:#333;
    display:block;
    text-decoration:none;
}
.widget-box li:hover a {
    background-color:#eee;
}
.widget-box p {
    padding:15px;
    line-height:25px;
}
```
hasilnya
![118](https://user-images.githubusercontent.com/56380765/115447264-7c301800-a242-11eb-9aec-652951f9a34a.png)

# langkah 6
mengatur tampilan footer dengan menambahkan element pada css
```/* footer */
footer {
    clear:both;
    background-color:#1d1d1d;
    padding:20px;
    color:#eee;
}
```
![119](https://user-images.githubusercontent.com/56380765/115447518-caddb200-a242-11eb-8250-bd2c5ee363d0.png)

# langkah 7
# menambah kan element lainnya pada main content
tambahkan pada home.html
```<section id="main">
    <div class="row">
        <div class="box">
            <img src="https://dummyimage.com/120/db7d25/fff.png" alt=""
class="image-circle">
            <h3>Heading</h3>
            <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
            <a href="#" class="btn btn-default">View detail</a>
        </div>
        <div class="box">
            <img src="https://dummyimage.com/120/3e73e6/fff.png" alt=""
class="image-circle">
            <h3>Heading</h3>
            <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
            <a href="#" class="btn btn-default">View detail</a>
        </div>
        <div class="box">
            <img src="https://dummyimage.com/120/71e6d4/fff.png" alt=""
class="image-circle">
            <h3>Heading</h3>
            <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
            <a href="#" class="btn btn-default">View detail</a>
        </div>
    </div>
</section>
```
kemudian tambahkan pada css
```/* box */
.box {
    display:block;
    float:left;
    width:33.333333%;
    box-sizing:border-box;
    -moz-box-sizing:border-box;
    -webkit-box-sizing:border-box;
    padding:0 10px;
    text-align:center;
}
.box h3 {
    margin: 15px 0;
}
.box p {
    line-height: 20px;
    font-size: 14px;
    margin-bottom: 15px;
}
box img {
    border: 0;
    vertical-align: middle;
}
.image-circle {
    border-radius: 50%;
}
.row {
    margin: 0 -10px;
    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
}
.row:after, .row:before,
.entry:after, .entry:before {
    content:'';
    display:table;
}
.row:after,
.entry:after {
    clear:both;
}
```
hasilnya
![1110](https://user-images.githubusercontent.com/56380765/115448005-59523380-a243-11eb-9f67-8ab38574180a.png)

# langkah 8
# membuat content artikel
tambahkan pada home.html
```<hr class="divider" />
<article class="entry">
    <h2>First featurette heading.</h2>
    <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
</article>
<hr class="divider" />
<article class="entry">
    <h2>First featurette heading.</h2>
    <img src="https://dummyimage.com/150/7b8a70/fff.png" alt=""
class="right-img">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
</article>
```
tambahkan pada css.html
```.divider {
    border:0;
    border-top:1px solid #eeeeee;
    margin:40px 0;
}
/* entry */
   .entry {
    margin: 15px 0;
}
   .entry h2 {
    margin-bottom: 20px;
}
.entry p {
    line-height: 25px;
}
.entry img {
    float: left;
    border-radius: 5px;
    margin-right: 15px;
}
.entry .right-img {
    float: right;
}
```
hasilnya
![1111](https://user-images.githubusercontent.com/56380765/115448289-bcdc6100-a243-11eb-9bcb-13fa634b2dd0.png)

