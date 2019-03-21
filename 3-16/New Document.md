# 1Date
			
			
			月份的对应关系
			1 2 3 4 5 6 7 8 9 10 11 12
			0 1 2 3 4 5 6 7 8 9  10 11
		    var a = date.getFullYear();
		    var a = date.getHours();
		    var a = date.getMinutes();
			  var a = date.getSeconds();
			 2019-3-20 14:26:23
             var date = new Date();
			年 var year = date.getFullYear(),
				月month = date.getMonth(),
				日day = date.getDate(),
				星期week = date.getDay(),
				时hour = date.getHours(),
				分minute = date.getMinutes(),
				秒second = date.getSeconds();
			var dateStr = year + "-" + (month + 1) + "-" + day + " 星期" + week 
						  + " " + hour + ":" + minute + ":" + second;
			console.log(dateStr);
##2-Math.html
		Math.floor(Math.random() *数量+ min)
任意范围的随机数
var a = Math.random(); [0,1)
      [2-13]
var b = Math.floor(a * 12) + 2 
##3-三元运算符
         var a = prompt();
 			if(a > 3){
				alert(">3");
			}else{
				alert("3>=");
		}
			a > 3 ? alert(">3") : alert("3>="); 
##4-if语句
        if(条件表达式 true){
				条件为真的时候做的事情
			}else{
				条件为假的时候做的事情
			} 
##5-逻辑运算符
逻辑运算符有三个
&& 与 且  
||	或
!	非	
    逻辑运算符 && || !
			参与逻辑运算的，都是布尔值。也就是说，只有true、false才能参与逻辑运算，得到的答案，仍然是布尔值。
			 && 都真才真 true && true ===> true 遇到false就返回,没遇到就返回最后一个值(表达式的值)
			化为布尔值为false的有: undefined null NaN "" 0 false
			 console.log(1 && 2); // 
			 || 只要有一个为真就是真 遇到true就返回,没遇到就返回最后一个值(表达式的值)
			console.log( 0>3 || 1<0);
			 ! 非true即false 非false即true
			 !! 强制性将其他类型值转换为布尔类型值
			 console.log (控制台输出内容)
      		 alert(输出内容)
			 str字符串()用引号引起的都是