---
title: "数学分析习题课/Mathematical Analysis"
collection: teaching
type: "Undergraduate Course"
permalink: /teaching/2021-fall-teaching-1
venue: "Nankai University, School of Statistics and Data Science"
date: 2021-09-01
location: "Tianjin, China"
---

该课程主要面对数学/统计等相关专业的本科生


<a name="table-of-contents"></a>
1. [**数学分析I**](#1)  
    1.1 [数学分析I教材](#1.1)  
    1.2 [数学分析I课表](#1.2)   
    1.3 [数学分析习题课-作业](#1.3)  
    
### 1.1 数学分析I教材 [(top)](#table-of-contents) <a name="1.1"></a>

该课程采用南开大学数学科学学院刘春根 朱少红 李军 丁龙云老师主编的《数学分析》[https://item.jd.com/10022132503675.html](https://item.jd.com/10022132503675.html)

![教材名称](/images/shuxuefenxi_pic1.png)


### 1.2 数学分析I课表 [(top)](#table-of-contents) <a name="1.2"></a>

![数学分析I课表](/images/mycourse1.png)


### 1.3 数学分析习题课-作业情况  [(top)](#table-of-contents) <a name="1.3"></a>

<details>
<summary>
  展示生成表格的R代码
 </summary>
 
<!-- rnb-text-begin -->

<pre class="r"><code>x1=rep(paste0(&quot;第&quot;,1:17,&quot;周&quot;),each=2)
date1=seq(as.Date(&quot;2021/09/06&quot;), as.Date(&quot;2021/12/27&quot;), &quot;weeks&quot;)
date2=seq(as.Date(&quot;2021/09/10&quot;), as.Date(&quot;2021/12/31&quot;), &quot;weeks&quot;)
date_new=c(date1,date2)
date_new[seq(1,length(date_new),by=2)]=date1
date_new[seq(2,length(date_new),by=2)]=date2
weeks=rep(c(&quot;星期一&quot;,&quot;星期五&quot;),times=17)
df0=data.frame(`周数`=x1,`日期`=date_new,`星期`=weeks,`作业`=rep(&quot;&quot;,length=34),`备注`=rep(&quot;&quot;,length=34))
knitr::kable(df0, format=&quot;markdown&quot;)</code></pre>

</details>
<br>

<table>
 <thead>
  <tr>
   <th style="text-align:left;"> 周数 </th>
   <th style="text-align:left;"> 日期 </th>
   <th style="text-align:left;"> 星期 </th>
   <th style="text-align:left;"> 作业 </th>
   <th style="text-align:left;"> 备注 </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> 第1周 </td>
   <td style="text-align:left;"> 2021-09-06 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;"> - </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第1周 </td>
   <td style="text-align:left;"> 2021-09-10 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;"> - </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第2周 </td>
   <td style="text-align:left;"> 2021-09-13 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;"> - </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第2周 </td>
   <td style="text-align:left;"> 2021-09-17 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;" rowspan="2">练习1.1的4、5、6、7；<br /> 习题1(A)的2、4、7、8、11、14  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第3周 </td>
   <td style="text-align:left;"> 2021-09-20 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;"> 中秋放假,调整09/18/2021(周六)上课</td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第3周 </td>
   <td style="text-align:left;"> 2021-09-24 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第4周 </td>
   <td style="text-align:left;"> 2021-09-27 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第4周 </td>
   <td style="text-align:left;"> 2021-10-01 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第5周 </td>
   <td style="text-align:left;"> 2021-10-04 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第5周 </td>
   <td style="text-align:left;"> 2021-10-08 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第6周 </td>
   <td style="text-align:left;"> 2021-10-11 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第6周 </td>
   <td style="text-align:left;"> 2021-10-15 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第7周 </td>
   <td style="text-align:left;"> 2021-10-18 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第7周 </td>
   <td style="text-align:left;"> 2021-10-22 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> 预计第一次月考时间（晚上）:第1,2章  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第8周 </td>
   <td style="text-align:left;"> 2021-10-25 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第8周 </td>
   <td style="text-align:left;"> 2021-10-29 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第9周 </td>
   <td style="text-align:left;"> 2021-11-01 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第9周 </td>
   <td style="text-align:left;"> 2021-11-05 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第10周 </td>
   <td style="text-align:left;"> 2021-11-08 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第10周 </td>
   <td style="text-align:left;"> 2021-11-12 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第11周 </td>
   <td style="text-align:left;"> 2021-11-15 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第11周 </td>
   <td style="text-align:left;"> 2021-11-19 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第12周 </td>
   <td style="text-align:left;"> 2021-11-22 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> 预计第二次月考时间（晚上）:第3,4章 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第12周 </td>
   <td style="text-align:left;"> 2021-11-26 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第13周 </td>
   <td style="text-align:left;"> 2021-11-29 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第13周 </td>
   <td style="text-align:left;"> 2021-12-03 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第14周 </td>
   <td style="text-align:left;"> 2021-12-06 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第14周 </td>
   <td style="text-align:left;"> 2021-12-10 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第15周 </td>
   <td style="text-align:left;"> 2021-12-13 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第15周 </td>
   <td style="text-align:left;"> 2021-12-17 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> 预计第三次月考时间 （晚上）:第5,7章 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第16周 </td>
   <td style="text-align:left;"> 2021-12-20 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第16周 </td>
   <td style="text-align:left;"> 2021-12-24 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第17周 </td>
   <td style="text-align:left;"> 2021-12-27 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第17周 </td>
   <td style="text-align:left;"> 2021-12-31 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
</tbody>
</table>

**Note:** 期末考试按照教务系统安排，内容是第1-7章，即本学期所有上课内容

