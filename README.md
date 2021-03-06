
 鉴于上述情况，研究者认为，此次网络试调查问卷的有效问卷标准如下：  
 （1）问卷回答时长在10~60分钟之间（包含端点值）；  
 （2）排除医务人员被试；  
 （3）排除学生被试。  
   

## 请根据上述要求，完成以下问题：
**（1）**
计算有效问卷率；

__（2）__
选择合适的指标，说明效问卷的回答时长及其分布。

__（3）__
新生成两个变量，一为*province*（省份），一为*city*（省会城市或地级市，），此部分信息均在*ip*一列中可以找到。统计各省份、各城市有多少被试参与调查。

+ 注：当然，*ip*显示云南丽江，不一定被试为丽江市区（城市户口），也可能是丽江农村（农村户口）。所以这里的城市，只宜理解为行政管辖上的归属地所属，而不能体现城乡差别。

+ 提示：建议使用*Hadley*的*stringr*及*lubridate*这两个包进行字段处理和时间处理的相关操作。
  
        
 # 四、统计操作（20分）
   （一）仍以第三大题（一）的rs2015数据为练习数据，分专业统计各专业的人数、最低分、最高分、中位数、均值、第一和第三四分位数，以及标准差（注意所有统计量均为分专业前提下操纵）。写出命令和并附上结果。
   
   （二）加拿大某大学研究者研究了大一新生的体重增长情况。他们从住在校园内部的大一新生和住在校外的大一新生中各随机抽取了10名学生，调查了他们的入学之后体重增减情况, 如下所列（单位: kg）:
   
|**校外(out)** | 2.0|2.3|1.1|-2.0|-1.9|5.6|2.6|1.1|5.6|8.2 | 
| :-: | :-: | :-: | :-: |:-: |:-: |:-: |:-: |:-: |:-: |:-: |
| **校外(out)** | **1.6**|**3.1**|**-2.8**|**0.0**|**0.2**|**2.9**|**-0.9**|**3.8**|**0.7**|**-0.1**|
  
   正数表示体重增加，负数表示体重减少。完成以下任务，写出命令和并附上结果。  
   （1）将此数据输入R，命名为testscore。  
   （2）估计校内住宿新生和校外住宿新生的平均体重增减量之差(校内－校外)的98%双侧置信区间，假定所有条件满足。基于这一区间，研究者有无足够信心认为校内住宿新生与校外住宿新生的平均体重增减量有无区别？  
   （3）若研究者想判定，平均而言校内住宿新生比校外住宿新生更容易“长胖”，应当使用什么样的置信区间？如果用R实现？  
   （4）若使用显著性检验法判定校内住宿新生比校外住宿新生更容易“长胖”，应当使用什么方法和R命令实现？ 
 # 五、综合应用（10分） 
文件ReadingList.xlsx是2016级南开大学应用心理学学术硕士的某课程文献阅读清单。该班级共10人，每人阅读6篇文献，并由老师随机指定2篇文献进行15分钟的课堂报告。随机指定文献的过程相当于是进行两次随机分层抽样，以学生名字（student）为层（strata），共10层，每层内各6个元素（文献名）；每次从每一层中抽取1
篇文献作为报告文献。注意第一次抽取后，应将该文献剔除后再进行第二次分层随机抽样。    

试用R实现上述过程。请写出你的命令，并用#的方式，分行注明每条命令的功能（注：你可能会用到sampling包，其使用说明请自行查阅帮助文档）。
   
 # 六、开放性问题（10分，不少于500字）
此题请用电脑打字，最后请说明电脑统计的字数（不计空格）。

结合自身的专业背景，谈一谈你对大数据技术对本专业研究的应用前景，以及R在其中可扮演的角色。并由此谈一谈你对本专业数据处理类课程设置、教学内容、教学方式的建议。
