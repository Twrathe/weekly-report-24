<script>export default { name :'homePage',}</script>
<script setup>

</script>

<template>
    <div class="div_fixedPicture">
        <img src="./image/头像4.jpg" alt="">
    </div>
    <div class="top">
        <h1><i>Fan's Photo Album</i></h1>
        <p>Start from 04/2024</p>
    </div>
    <div class="Navigation">
        <h1>NAVIGATION</h1>
        <h4>导航</h4>
        <table >
            <tr>
            <td> <a href="#the_foreword">简介</a></td>
            <td> <a href="#photo_show">作品集</a></td>
            <td> <a href="#">1</a></td>
            <td> <a href="#connectToPhotographer">联系我</a></td>
            </tr>
        </table>
    </div>
    <div class="theForeword" id="the_foreword">
        <h1>THE FOREWORD</h1>
        <h4>简介</h4>

        <!-- 这边是文本--开端  -->
        <div class="div_theForword_1">
            <h3>啥时候开始了解摄影？</h3>
            <p>
                我觉得我的摄影启蒙应该是动物世界？（误）&nbsp;
                小时候真的非常喜欢看动物世界，时常幻想自己是一个野生动物摄影师。这个幻想也一直被埋藏在我的心中。对于影像的兴趣也直接促使我在大学拿起来相机，来捕捉我眼中的光影世界。
            </p>
            <h3>
                现在水平咋样？ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                <span style="text-align: right;"><del>依托答辩</del></span>
            </h3>
            <p>
                刚起步啦，拍到过自己满意的照片，也有非常多非常多的废片。
                <p>想拍风光，也想拍人像，还想拍人文。</p>
                <p>会点构图，但不多。会点打光，但不多。会点调色，但不多。</p>
                <p>正在学习调色和PS(奋斗ing)</p>
                <p>也好想找美女拍人像，也好想出去旅游扫街拍风景。</p>
            </p>
           
            <h3>
                未来期望！！
            </h3>
            <p>
                当一个摄影民工，赚点钱换个更好的相机，买一大堆一大堆镜头，提高自己的艺术审美，确定自己的摄影风格，为成为摄影大师而学习。
            </p>
        </div>

        <!-- 这边是我的一些自拍 -->
        <div class="div_theForword_2"> 
            <img src="./image/mySelf2.jpg" alt=""> 
            <p>常用ID：Safelanding 、 Fanzone 、 Stan
               <br>
               <br>
               目前就读于 小汤河职业技术学校 大一小东西
            </p>
            
                
        </div> 
    </div>
    <div class="div_photoShow" id="photo_show">
        <h1>THE PHOTO ALBUM</h1>
        <h4>作品集</h4>
        <div>
            <p>日出金梦</p>
            <img src="./image/风景照 (2).jpg" alt="">
            
        </div>
    </div><!-- 这边想做成一个滚动播放的 碍于还没学JS 就先放一个照片在这里啦  -->
    <p style="text-align: center;">这边想做成一个滚动播放的 学会了就加上了</p>
    <div class="div_connectToPhotographer" id="connectToPhotographer"> 
        <h1>connect to photographer</h1>
        <h4>联系我</h4>
        <table>
            <tr>
                <td>qq: 2215464269</td>
                
            </tr>
            <tr>
                <td>wx: wxid_wovfwydsv40x22</td>
            </tr>
            <tr>
                <td>email: 19839852169@163.com</td>
            </tr>
            <tr>
                <td>github: Safelanding</td>
            </tr>
            
        </table>

    </div>

</template>

<style>
   .div_fixedPicture{
        img {
            position: fixed;
            right: 10px;
            bottom: 50px;
            height: 150px;
            width: 150px;
            border-radius: 5px;
        }
    }
    .top h1 {
        text-align: center;
        color: rgb(7, 221, 221);
        background-color: #ff8223;
        border-radius: 50px;
        margin: 0px;
        font-size: 100px;
        text-shadow: 5px 5px 1px rgb(11, 106, 207);
    }
    .top p {
        margin-top: 10px;
        text-align: right;
        font-size: 20px;
        font-family:'Times New Roman', Times, serif;
        text-shadow: 3px 3px 1px rgb(165, 183, 202);
        /* font-size-adjust: initial ; */
        /* background-color: #f3af49;
        margin-left: 100px;
        text-shadow: white;
        border: 200px; */
    }
    .Navigation h1 {
        display: block;
         font-size: 60px;
         text-align: center;
         color: #e0e1e5;
         line-height: 100%;
         font-weight: bold;
    }
    .Navigation h4 {
        margin-top: -80px;
        text-align: center;
        font-size: 50px;
    }
    .Navigation table {
        margin: 0 auto;
        /* border: 1px solid blue; */
        border: none;
        font-size: 30px;
        margin-top: -50px;
        width: 800px;
        text-align: center;
        font-style: normal;
        td {
           border: none; 
           width: 25%;
           height: 100px;
           text-align: center;
            /* border: 1px solid black */
        }
        a {
            
           text-decoration: none; /* 消除下划线 */
           color: inherit; /* 继承父元素的文字颜色 */
        }
    }
    .theForeword h1 {
        display: block;
         font-size: 60px;
         text-align: center;
         color: #e0e1e5;
         line-height: 100%;
         font-weight: bold;
    }
    .theForeword h4 {
        margin-top: -80px;
        text-align: center;
        font-size: 50px;
    }
    .div_theForword_1{
        display: inline-block ;
        border-radius: 5px;
        /* position:fixed; */
        /* position: static; */
        width: 45%;
        height: 650px;
        margin-left: 15%;
        margin-right: 1%;
        background-color:#ff8223;
        vertical-align: top;
        text-indent: 2em;
        font-size: 20px;
        padding-left: 1em;
        color: white;
        letter-spacing: 1px;
        /* opacity: 50%; */
        h3 {
            text-indent: 0em;
        }
        p {
            
            /* font-family: SimSun, serif; */
            line-height: 1.5em; /* 使用宋体字体，如果系统中没有宋体字体则使用备用字体 */
        }
    }
    .div_theForword_1 img{
        position: fixed;
    }
    .div_theForword_2{
        display: inline-block;
        border-radius: 5px;
        width: 20%;
        height: 650px;
        position: relative; 
        margin-right: 14%;
        margin-left: 0%;
        background-color: rgba(140, 0, 0, 0.9);
        vertical-align: top;
        justify-content: center;
        text-align: center;
        img {
            position: absolute;
            top: 38%;
            left: 50%;
            transform: translate(-50%, -50%); 
            max-width: 90%; /* 图片最大宽度为容器宽度 */
            max-height: 90%; /* 图片最大高度为容器高度 */

            } 
        p {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.5); /* 文字背景色，可根据需要修改 */
            color: white; /* 文字颜色，可根据需要修改 */
            padding: 10px;
            box-sizing: border-box;
            }
            
    }
/* 行内元素无法设置高度和宽度 */
    /* .div_theForword_1 span{
        display:block;
        background-color: #100701;
        width: 50px;
        height: 50px;
        position: static;
    }   */
    .div_photoShow div{
        width: 1000px;
        height: 1000px;
        border-radius: 69% 31% 70% 30% / 45% 21% 79% 55% ;
        background-color: #ff6f00;
        margin-left: 20%;
        margin-right: 20%;
        img {
            position:relative;
            top: 20%;
            left: 15%;
            max-width: 70%;
            max-height: 70%;
            border-radius: 50px;
        }
        p {
            position: relative;
            top: 10%;
            text-align: center;
            width: 100%;
            margin-top: 0;
            margin-bottom: 0;
            font-size: 30px;
        }
    }
    .div_photoShow h1{
         display: block;
         font-size: 60px;
         text-align: center;
         color: #e0e1e5;
         line-height: 100%;
         font-weight: bold;

    }
    .div_photoShow h4{
        margin-top: -80px;
        text-align: center;
        font-size: 50px;
    }
    .div_connectToPhotographer h1{
        display: block;
        font-size: 60px;
        text-align: center;
        color: #e0e1e5;
        line-height: 100%;
        font-weight: bold;

    }
    .div_connectToPhotographer h4{
        margin-top: -80px;
        text-align: center;
        font-size: 50px;
    }
    .div_connectToPhotographer table{
        background-color: #3b291a;
        border: #e0e1e5;
        color: #e0e1e5;
        position: relative;
        left: 10%;
        width: 80%;
        border-collapse:separate;
        td {
            text-align:left;
            text-indent: 500px;
            font-size: 20px;
            border-color: #e0e1e5;
        }
    }
</style>