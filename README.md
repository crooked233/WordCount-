项目简介及其相关用法：
  该项目用于实现文本计数以及对代码对应行数的统计，能正确统计导入的纯英文txt文本中的字符数，单词数，句子数和代码空行数、注释数、有效行数。
  命令模式： wc.exe [参数] [文件名]  例如：wc.exe -c pra.txt 用于统计名为pra的文本中的字符数量，改换参数，-w，统计该文本中的单词数，-s，统计该文本中的句子数，-code，统计代码中的有效行数、空行数和注释行数。
  
  
  
 项目使用程序：Python 3.5 64bt
  
  
 例程运行及其相关结果：
 pra.txt：
 Intervening in regional affairs, meddling in other countries' internal affairs, inciting a "color revolution" and 
even subverting the legitimate political power of other countries are the real source of regional chaos and wars, 
Wei Fenghe, State Councilor and Minister of National Defense said at the opening ceremony of the 9th Beijing 
Xiangshan Forum on Monday morning. 

Wei stated in his keynote speech that wanton interference is unpopular and only mutual respect will lead the world 
to live in harmony.   

All countries, big or small, strong or weak, rich or poor, are equal members of the international community and 
have the right to choose their own development path, said Wei.  Wei also said that China advocates that all 
countries in the world respect each other and treat each other equally, not to bully the small, oppress the weak, 
or have precedence over others.  

Wei emphasized that China does not attach any political conditions to its exchanges with other countries or require 
other countries to choose sides, and does not interfere in the internal affairs of other countries or impose its 
will on others.
运行结果：
wc.exe -c pra.txt    文章含有的字符数为：935个
wc.exe -w pra.txt    文章含有的单词数为：182个
wc.exe -s pra.txt    文章中含有的句子数为：19句

 代码行数测试：
 pra.txt：
 asdhukashdk
#
asdhalsj   #sdan


jaiashda

运行结果：
wc.exe -code pra.txt  代码行数为：3行
                      空行数为：2行
                      注释行为：2行
