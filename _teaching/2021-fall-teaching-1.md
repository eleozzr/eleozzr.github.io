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
1. [**本科生课程**](#1)  
    1.1 [数学分析习题课-课件](#1.1)  
    1.2 [数学分析习题课-作业](#1.2)  
    
### 1.1 数学分析习题课-课件 [(top)](#table-of-contents) <a name="1.1"></a>

该课程采用南开大学数学科学学院，由刘春根 朱少红 李军 丁龙云主编的《数学分析》[下载](https://www.baidu.com/)


### 1.2 数学分析习题课-作业情况  [(top)](#table-of-contents) <a name="1.2"></a>

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
     
|周数   |日期       |星期   |作业 |备注 |
|:------|:----------|:------|:----|:----|
|第1周  |2021-09-06 |星期一 |   ********************  |     |
|第1周  |2021-09-10 |星期五 |     |     |
|第2周  |2021-09-13 |星期一 |     |     |
|第2周  |2021-09-17 |星期五 |     |     |
|第3周  |2021-09-20 |星期一 |     |     |
|第3周  |2021-09-24 |星期五 |     |     |
|第4周  |2021-09-27 |星期一 |     |     |
|第4周  |2021-10-01 |星期五 |     |     |
|第5周  |2021-10-04 |星期一 |     |     |
|第5周  |2021-10-08 |星期五 |     |     |
|第6周  |2021-10-11 |星期一 |     |     |
|第6周  |2021-10-15 |星期五 |     |     |
|第7周  |2021-10-18 |星期一 |     |     |
|第7周  |2021-10-22 |星期五 |     |     |
|第8周  |2021-10-25 |星期一 |     |     |
|第8周  |2021-10-29 |星期五 |     |     |
|第9周  |2021-11-01 |星期一 |     |     |
|第9周  |2021-11-05 |星期五 |     |     |
|第10周 |2021-11-08 |星期一 |     |     |
|第10周 |2021-11-12 |星期五 |     |     |
|第11周 |2021-11-15 |星期一 |     |     |
|第11周 |2021-11-19 |星期五 |     |     |
|第12周 |2021-11-22 |星期一 |     |     |
|第12周 |2021-11-26 |星期五 |     |     |
|第13周 |2021-11-29 |星期一 |     |     |
|第13周 |2021-12-03 |星期五 |     |     |
|第14周 |2021-12-06 |星期一 |     |     |
|第14周 |2021-12-10 |星期五 |     |     |
|第15周 |2021-12-13 |星期一 |     |     |
|第15周 |2021-12-17 |星期五 |     |     |
|第16周 |2021-12-20 |星期一 |     |     |
|第16周 |2021-12-24 |星期五 |     |     |
|第17周 |2021-12-27 |星期一 |     |     |
|第17周 |2021-12-31 |星期五 |     |     |

