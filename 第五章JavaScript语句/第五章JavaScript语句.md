#第五章   JavaScript语句
###5.1  分支语句
5.1.1  if语句
    var a = 10;
      //小括号里一定要是turn
      if(a<20){
          alert('yes');
      }

5.1.2  else语句

    if(a<10){
          alert('yes');
      }else{
          alert('no');
      }

5.1.3 if...else if语句

    
      if(a<60){
          alert('及格');
        }else if(a>=60 && a<75){
            alert('c');
        }else if (a>=75 && a<85){
            alert('b')
        }else if(a>=85 && a<=100){
            alert('a')
        }else{
            alert('缺考');
        }
    
5.1.4   switch语句
switch小括号中一般情况是一个变量名,这个变量可能会有不同的取值,所有的case都是"或"的关系,case后面的值会与变量值作比对,满足后就执行case后面代码.不写break就会将所有的比对进行一遍.
      var a = 10;
        //将判断的内容写在括号里
        switch(a){
            case 值1:
            //执行代码
            break;
            case 值2:
            //执行代码
            break;
            case 值3:
            //执行代码
            break;
            case 值n:
            //执行代码
            break;
            default:
            //执行代码

###循环语句

5.2.1 while循环
while语句是一种前测试语句(先判断以下在执行)，循环的目的是为了反复执行语句或代码块,只要表达式为ture就继续循环，一旦为假的时候,循环退出.

5.2.2 do....while循环
 do....while语句是一中后测试语句,就是在循环体中得代码执行之后,才开始判断条件.也就是说,在表达是判断之前,循环体内的代码至少会被执行一次.
       var a = 0;
       do{
          alert('你好')
           a++;
       }while(a<5);

5.2.3 for循环
for语句是一种前侧语句，一般情况下,有三个基础表达式语句,每一个要用分号隔开.
             //初始化  判断  更新
      for( var x = 0; x<y; x++){
            //执行循环体
            alert(x);
        }
      //顺序为：初始化-->  判断-->  执行循环体-->  更新-->
     
##练习
需求：
 1.做一个1+2+3+4+5+6+7+8+9+10的和

作业：
    
    