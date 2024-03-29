---
title: "数学分析I习题课/Mathematical AnalysisI"
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
    1.4 [其它习题询问](#1.4)  
    1.5 [经典反例](#1.5)  
    1.6 [月考试题](#1.6)  
    
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
   <td style="text-align:left;"> 练习2.1的1;习题2(A)的1,2,3,6 </td>
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
   <td style="text-align:left;" rowspan="2">练习2.2:题1，题3的(3)(6);<br /> 练习2.3:题2的(3)(4),题3的(2); <br/>习题2(A):6、7、9;</td>
   <td style="text-align:left;">  2021-10-19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第6周 </td>
   <td style="text-align:left;"> 2021-10-11 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">  2021-10-19 习题课上交作业</td>
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
   <td style="text-align:left;">练习2.4: 题1的(2)(6)(7),题2的(2);<br/>练习2.5: 题(1)的(2)(4)(6);<br /> 练习2.6: 题2;<br/>习题2(A): 16,17,18,27;</td>
   <td style="text-align:left;">  2021-10-26 习题课上交作业</td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第7周 </td>
   <td style="text-align:left;"> 2021-10-22 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> 第一次月考时间<span style="color:red;">晚上18:30-20:10</span>:第1,2章; <a href="https://stat.nankai.edu.cn/bksjy/list.htm"> [具体安排]</a> </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第8周 </td>
   <td style="text-align:left;"> 2021-10-25 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">练习2.7: 题1的(2),题5的(5)-(8); <br/> 练习3.1: 题1的(2),题3的(1)(3)(5);<br/>练习3.2:题2;<br/> 练习3.3: 题1的(4),题2的(1)(3)(5)(7)(9)</td>
   <td style="text-align:left;"> 2021-11-02 习题课上交作业 </td>
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
   <td style="text-align:left;">练习3.4: 题1,题3; <br/> 练习3(A): 题6,题7;<br/>练习4.1: 题2,题6-8;<br/> 练习4.2: 题1,题2.</td>
   <td style="text-align:left;"> 2021-11-09 习题课上交作业 </td>
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
   <td style="text-align:left;">练习4.2: 题3(8),题4(4);题9 <br/> 练习4.2: 题2,题3(2),题5(2),题6(2);<br/>练习4.4: 题4(2);<br/> 练习4(A):题5,题6,题7.</td>
   <td style="text-align:left;"> 2021-11-16 习题课上交作业</td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第10周 </td>
   <td style="text-align:left;"> 2021-11-12 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> 第二次月考时间<span style="color:red;">晚上18:30-20:10</span>:第3,4章; <a href="https://stat.nankai.edu.cn/bksjy/list.htm"> [具体安排]</a>  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第11周 </td>
   <td style="text-align:left;"> 2021-11-15 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;">练习5.1: 题2,题3,题4(3),题5,题7,题8,题10;<br/>练习5.2: 题2,题3(1);<br/>习题5(A): 题2,题5，题6</td>
   <td style="text-align:left;"> 2021-11-23 习题课上交作业</td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第11周 </td>
   <td style="text-align:left;"> 2021-11-19 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第12周 </td>
   <td style="text-align:left;"> 2021-11-22 </td>
   <td style="text-align:left;"> 星期一 </td>
   <td style="text-align:left;"> 练习5.2: 题4，题5; <br/> 练习5.3: 题1,题2,题3(3); <br/> 练习5.4:题1的偶数题</td>
   <td style="text-align:left;"> 2021-11-30 习题课上交作业</td> 
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
   <td style="text-align:left;"> 练习5.5: 题1(4), 题2(5), 题3(5),题5<br/> 习题5A:题27,28,29,30  <br/> 练习7.1: 题3(6)<br/> 练习7.2:题1的5,10,15,20,25,30</td>
   <td style="text-align:left;"> 2021-12-07 习题课上交作业</td> 
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
   <td style="text-align:left;"> 练习7.3:题1的5,10,15,17,23;<br/>练习7.4:题1的10,11;<br/> 练习7.5:题1的9,10; 题2的3;<br/> 习题7A:题2的3,5; 题6的3，题7的1; 题9的5,10</td>
   <td style="text-align:left;">  2021-12-14 习题课上交作业</td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第14周 </td>
   <td style="text-align:left;"> 2021-12-09 </td>
   <td style="text-align:left;"> 星期四 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> 预计第三次月考时间 （晚上）:第5,7章 <a href="https://math.nankai.edu.cn/2021/1130/c5536a418206/page.htm"> [具体安排]</a> </td>
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
   <td style="text-align:left;"> 练习6.1:题2,题3,题4;</br> 练习6.2:题1,题2,题3,题4,题5;</br>练习6(A): 题1,题2(2)</td>
   <td style="text-align:left;">2021-12-21 习题课上交作业  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 第15周 </td>
   <td style="text-align:left;"> 2021-12-17 </td>
   <td style="text-align:left;"> 星期五 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
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
</tbody>
</table>

**Note:** 期末考试按照教务系统安排，内容是第1-7章，即本学期所有上课内容

### 1.4 其它习题询问 [(top)](#table-of-contents) <a name="1.4"></a>

如果大家课外时间有其它习题可以通过下面链接或者二维码进行提交:

   1. [数学分析I习题课其它习题] (https://www.wjx.cn/vj/Oh5iulx.aspx),<a href="https://www.wjx.cn/vj/Oh5iulx.aspx"> https://www.wjx.cn/vj/Oh5iulx.aspx </a>
   2. 调查问卷二维码

![习题课调查问卷二维码](/images/shxuefenxi_question.png)

### 1.5 经典反例 [(top)](#table-of-contents) <a name="1.5"></a>
   1. 若 $f(x)$ 在 $\mathbb{R}$ 连续，若 $\forall t\in \mathbb{R}$,有 $\lim\limits_{x\rightarrow+\infty} f(n+t)=A$, 问是否可以证明得到 $\lim\limits_{x\rightarrow+\infty}f(x)=A$. 反例如下:
 $$f(x)=\left\{\begin{array}{ll}m(x-m),&x\in[m,m+1/m]\\m(m+2/m-x),&x\in(m+1/m,m+2/m]\\0,&other\\\end{array}\right. (m\in\mathbb{N}^* ~and ~m\ge 2)$$

<details>
<summary>
   反例图像产生代码以及代码:
 </summary>
<!-- rnb-text-begin -->

<pre class="r"><code>
f=function(x){
  m=as.integer(x)
  if(x>=m & x<=m+1/m){
    return(m*(x-m))
  }else if(x>=m+1/m & x<=m+2/m){
    return (m*(m+2/m-x))
  }else{
    return(0)
  }
}
x=seq(from=1,to=1000,length=500000)
y=sapply(x,function(x0) f(x0))
df=data.frame(x=x,y=y)
ggplot(df[1:10000,])+geom_line(aes(x=x,y=y))+
  scale_x_continuous(breaks = c(1:20))+
  cowplot::theme_cowplot() </code></pre>

</details>

![反例图片](/images/shxuefenxi1_example.png)

### 1.6 考试试题 [(top)](#table-of-contents) <a name="1.6"></a>

    > 下面链接包括以前月考以及2020年数学分析I考试试题
    
[https://www.jianguoyun.com/p/Db_2Xi0Q_9fcCRidtaIE ( Access Password:ahOSTY )](https://www.jianguoyun.com/p/Db_2Xi0Q_9fcCRidtaIE)
