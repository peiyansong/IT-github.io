<!DOCTYPE html><html>
<head>
<meta charset="utf-8">
<title>我的个人简历</title>
<link rel="stylesheet" href="https://cdn.staticfile.org/twitter-bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://cdn.staticfile.org/jquery/2.1.1/jquery.min.js"></script>
<script src="https://cdn.staticfile.org/twitter-bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="https://cdn.staticfile.org/echarts/4.3.0/echarts.min.js"></script>
</head>
<body >
<div class="jumbotron text-center" style="margin-bottom:0" id="grad1"> 
<img src="D:\网页\img\1.jpg" width="200px" height="200px" />
<h3>大壮</h3>
<p style="font-size: 15px;">2020年升入xxx学院，<br/>学习软件技术，对编程有浓厚的兴趣，
在老师的指导，<br/>和自己的课下练习，渐渐对编程有了更深入的了解。<br/>在课余时间，
我喜欢唱歌、跑步和打乒乓球。<br/>喜好结交志同道合的朋友，一起分享学习的生活的经验。<br/>
有良好的团队意识，学习时认真负责。            </p>
</div>
<nav class="navbar navbar-inverse">
    <!-- <设置导航栏颜色 -->
<div class="container-fluid">
<div class="navbar-header">
<button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
<span class="icon-bar"></span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
</button>
<!-- <a class="navbar-brand" href="#">专业技能</a> -->
</div>
<div id="relation">
<table  class="table table-striped">
<tbody>
<tr align="center">
<td><a href="#email"><button type="button" class="btn btn-primary btn-lg">
<span class="glyphicon glyphicon-envelope"></span>
</button></a></td>
<td> <a href="#email"><button type="button" class="btn btn-primary btn-lg">
<span class=" glyphicon glyphicon-earphone"></span>
</button></a></td>
<td><a href="#" target="_blank"><button type="button" class="btn btn-primary btn-lg">
<span class=" glyphicon glyphicon-user"></span>
</button></a></td>
</tr>
</tbody>
</table>
</div>
<div class="collapse navbar-collapse" id="myNavbar">
<ul class="nav nav-pills nav-justified">
<li><a href="#main">专业技能</a></li>
<li><a href="#project">个人实践</a></li>
<li><a href="#myCarousel">作品展示</a></li>
<li><a href="#education">教育经历</a></li>     
</ul>
</div>
</div>
</nav>
<!-- 为ECharts准备一个具备大小（宽高）的Dom -->
<div id="main" style="width:
50%;height:400px;left: 25%;"></div>
<script type="text/javascript">
// 基于准备好的dom，初始化echarts实例
var myChart = echarts.init(document.getElementById('main'));
// 指定图表的配置项和数据
var option = {
title: {
text: '专业技能平均分'
},
tooltip: {},
legend: {
data:['分数'],
},
xAxis: {
data: ["C语言","高数","计算机应用基础","计算机网络技术","大学英语","体育"],axisLabel: {
// inside: true, 隐藏x轴内容
// 改变x轴字体颜色
//     textStyle: {
//         color: '#8B4500'
//     }
},
},
yAxis: {},
series: [{
name: '分数',
type: 'bar', 
//改变图表颜色
color:['#8EE5EE'],
data: [85, 95, 82, 90, 80, 80]
}],
};
// 使用刚指定的配置项和数据显示图表。
myChart.setOption(option);
</script>
<ul class="list-unstyled" align="center">
<li>Java基础:<br/>
我入门时首先学的就是C语言做基础，然后再到Java，<br/>
在学习过程中老师细致的教学为我们打下了牢固的java基础。              </li>
<li>数据库:<br/>
数据库是我们大一第二学期开的课，配合Java一起学习的科目，</li>
<li>C语言：<br/>
在学C语言之前我有良好计算机语言基础，所学习C语言时也是十分顺利的掌握了课本里的内容。</li>
<li>动态网页设计<br/>
网页开发是我最喜爱的科目之一，HTML和CSS的学习给我启发深刻。</li>
</ul>
<div class="container" align="center">
<div class="row">
<div class="col-sm-4">
<h3 class="text-info" id="project">
<a href="#uuu">个人实践</a></h3>
<ul class="nav nav-pills nav-stacked">
<li class="active"><a href="#uu">在学校担任计算机协会社长</a></li>
<li><a href="#ye">担任班级学委</a></li>
<li><a href="#yan">参加全国大学生TMT行业赛事——蓝桥杯</a></li>
</ul>
<hr class="hidden-sm hidden-md hidden-lg">
</div>
<div class="col-sm-8" align="left">
 <h3 class="text-info" id="uuu">个人实践</h3>
<h2 id="uu">在学校担任计算机协会社长</h2>
<p>这个社团是我在大一第一学期的时候就参加的，也是我最想参加的社团，因为我对计算机超级热爱，我想在这个社团里去锻炼我，让我去见识更多关于计算机的知识。我在这里也学到了许多很实用且有趣的东西。
以及导航、朋友圈等功能一体的汽车平台。该项目用户的使用方法如下：        <p>1.学会了用python去做一些小的数据分析</p>
<p>2.在这里我彻底明白了自己今后的发展方向。</p>
<p>3。通过和同学参加的活动让自己变得更加自信。</p>
<p>4.提高了自己的码代码的速度。</p>
</p>
<br>
<h2 id="ye">担任班级学委</h2>
<h5>自我收获</h5>
<p>在担任学委期间，可以说让我成长了不少，同时也学到了许多东西。学习委员是一个充满挑战的职务、身为学习委员让我也感受到了压力，但同时也是一种动力，首先自己的学习不能落下，并要有所作为，这样才能更好的服务同学，其次也要调理好同学和老师之间的关系，对于老师和同学之间的矛盾及时劝阻和疏通。最后，也得搞好自身的学习成绩。我觉得自己收获挺多，也有所感悟：<p>1.我觉得自己本身工作成功开展得谢谢我的老师和同学，他们给予我好多的鼓励在我失落徘徊的时候，他们总会给我开导帮我树立自信。</p>
<p>2.我得谢谢我家二狗，嘿嘿嘿那肯定是个狗啊，我们彼此忠诚相互依偎，谢谢贠二狗给我数不尽的帮助，和大佬对我的支持嘿嘿嘿。</p>
<p> 3.当然我的同桌也不能落下，他虽然一副不在意的样子，看起来啥也不在乎，可是通过你一次次的的真心话，我知道其实你也其实挺好的啊 ，谢谢你的忠言，同桌！</p>
<br>
<h2 id="yan">参加全国大学生TMT行业赛事——蓝桥杯</h2>
<h5>参赛经历</h5>
<p>蓝桥杯是我们最近才参加完的比赛。该比赛是由我们的杨老师带队我们全学院学校学生参加的情况下展开的，在我们杨老师的指导下，自己的努力下，我也成的拿到了省三的奖励。
<p>该比赛让我体会到了团队合作和团队分工明确的重要性，每个人做好属于自己的一份任务，环环相扣才能保质保量的完成项目。</p>
</div></div>
</div>
<div id="myCarousel" class="carousel slide" style="border: solid; border-color: cornflowerblue;">
<!-- 轮播（Carousel）指标 -->
<ol class="carousel-indicators">
<li data-target="#myCarousel" data-slide-to="0" class="active"></li>
<li data-target="#myCarousel" data-slide-to="1"></li>
<li data-target="#myCarousel" data-slide-to="2"></li>
<li data-target="#myCarousel" data-slide-to="3"></li>
</ol>
<!-- 图片轮播（Carousel）项目-->
<div class="carousel-inner" align="center" >
<div class="item active">
<img src="D:\网页\img\1.jpg" style="width: 80%;height: 800px; border: solid 5px; border-color: lightslategray;" alt="First slide">
</div>
<div class="item">
<img src="D:\网页\img\3.jpg" style="width: 80%;height: 800px; border: solid 5px; border-color: lightslategray;" alt="Second slide">
</div>
<div class="item">
<img src="D:\网页\img\4.jpg" style="width: 80%;height: 800px; border: solid 5px; border-color: lightslategray;" alt="Second slide">
</div>
<div class="item">
<img src="D:\网页\img\6.png" style="width: 80%;height: 800px; border: solid 5px; border-color: darkgray;" alt="Third slide">
</div>
</div>
<!-- （Carousel）导航按钮 -->
<a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
<span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
<span class="sr-only">Previous</span>
</a>
<a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
<span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
<span class="sr-only">Next</span>
</a></div>
<div style="width: 100%; height: 220px; " >
<table class="table">
<caption style="text-align: center;"><h3 id="education" style="color: black;">教育经历</h3></caption>
<tbody style="text-align: center;">
<tr>
<td>2008.9.-2014.7</td>
<td>就读于xx小学</td>
</tr>
<tr>
<td>2014.9-2017.7 </td>
<td> 就读于xx初中</td>
</tr>
<tr>
<td>2017.9-2020.7 </td>
<td> 就读于xx高级中学</td>
</tr>
<tr>
<td>2020.9-至今 </td>
<td> 就读于xxx学院</td>
</tr>
</tbody></table></div>
<div class="jumbotron text-center" style="margin-bottom:0" >
<p id="email" align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

</div>
</body></html> 
————————————————
版权声明：本文为CSDN博主「九硕」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/weixin_52847491/article/details/118866352
