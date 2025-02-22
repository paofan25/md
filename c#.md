### c#
![image-20250216225532907](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250216225532907.png)

![image-20250216225720086](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250216225720086.png)

有自动空行，无自动空行

写一个键即可，写一行东西按enter才行

![image-20250216225743379](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250216225743379.png)

![image-20250217124002219](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217124002219.png)

![image-20250217130222229](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217130222229.png)

![image-20250217130313944](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217130313944.png)

num

默认是double类型，加了float才告诉计算机是浮点数

![image-20250217155131282](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217155131282.png)

sbyte 1

int 4

short 2

long8

byte 1

uint 4

ushort2

ulong 8

float 4

double 8

decimal 16

bool1

char2

string打不出来

![image-20250217161556076](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217161556076.png)

myAge

myGenfer

myAttact

myOffend

yourHeight

yourWeight

![image-20250217162351668](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217162351668.png)

不可以修改

必须初始化
```
\\
\"
\'
\n
\t
```

![image-20250217170005363](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217170005363.png)

大范围转小范围，int转long

![image-20250217182341609](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217182341609.png)

![image-20250217184127010](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217184127010.png)

![image-20250217185852933](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217185852933.png)

![image-20250217194229064](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217194229064.png)

![image-20250217200341656](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217200341656.png)

![image-20250217200425535](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217200425535.png)

![image-20250217200737355](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217200737355.png)

![image-20250217200837299](C:\Users\19562\AppData\Roaming\Typora\typora-user-images\image-20250217200837299.png)

啊啊



![image-20250217201742969](./assets/image-20250217201742969.png)

![image-20250217203436838](./assets/image-20250217203436838.png)

![image-20250217205236462](./assets/image-20250217205236462.png)

![image-20250217205555886](./assets/image-20250217205555886.png)

![image-20250217210001459](./assets/image-20250217210001459.png)

0100 1100

0101 0101

0101 1101

93







560                               110 0011    

​                                      010 0001

​                                      100 0010    66

0100 0010

33



异或 ^ 相同为0，不同为1

位取反~ 0变1，1变0

![image-20250217211818730](./assets/image-20250217211818730.png)

![image-20250217213845296](./assets/image-20250217213845296.png)

![image-20250218131235874](./assets/image-20250218131235874.png)

![image-20250218132824423](./assets/image-20250218132824423.png)

![image-20250218135604784](./assets/image-20250218135604784.png)

![image-20250218140830002](./assets/image-20250218140830002.png)

![image-20250218160640714](./assets/image-20250218160640714.png)

![image-20250218162559728](./assets/image-20250218162559728.png)

```
// See https://aka.ms/new-console-template for more information

// Console.WriteLine("变量");

// #region 声明变量
// Console.WriteLine("myregion");
// int i = 1;
//
//
// #endregion

string m = "练习";
Console.WriteLine(m);


// string name = "Alice";
// int age = 19;
// bool sex = true;//女
// float tall = 191.5f;
// float weight = 30.5f;
// string place = "闵行区";
// Console.WriteLine(name+" "+age+sex+tall+weight+place);

// int math = 80;
// int yuwen = 78;
// int english = 98;
// Console.WriteLine("小明的数学是"+math+"分");
// Console.WriteLine("小明的语文是"+yuwen+"分");
// Console.WriteLine("小明的英语是"+english+"分");
// Console.Write("我是小明\n我今年18\n我的爱好是制作游戏\n我要好好学习，天天向上");
// Console.WriteLine();
// Console.Write(@"我是小明
// 我今年18
// 我的爱好是制作游戏
// 我要好好学习，天天向上");

// char name1 = 'i';
// char name2 = '8';
// char name3 = '=';
// float name4 = name1;
// float name5 = name2;
// float name6 = name3;
// Console.Write(name4);
// Console.WriteLine();
// Console.Write(name5);
// Console.WriteLine();
// Console.Write(name6);
// Console.WriteLine();
//括号转换，parse,convert,toString
// 括号强转：数值整形之前转换，低精度转高精度
//parse:字符串转对应类型 变量类型.Prase（字符串）
//
//
// Console.WriteLine(sbyte.Parse("1"));
//
// int a = Convert.ToInt32("12");
// Console.WriteLine(a);
// abc = true.ToString()
// long l =1;
// short i =(short)l;
// Console.WriteLine(24069.ToString());

// char cd = (char)24069;
// Console.WriteLine(cd);
//
// Console.WriteLine("shuRu YuWen");
// string a = Console.ReadLine();
// long a1 = long.Parse(a);
// Console.WriteLine("Math");
// string b = Console.ReadLine();
// long b1 = long.Parse(b);
// Console.WriteLine("English");
// string c = Console.ReadLine();
// long c1 = long.Parse(c);

// Console.WriteLine("请输入一个数字");
// try
// {
//     int a = int.Parse(Console.ReadLine());
// }
// catch
// {
//     Console.WriteLine("输入错误");
// }
//
//
//
// Console.WriteLine("请输入成绩");
// try
// {
//     int a = int.Parse(Console.ReadLine());
// }
// catch
// {
//     Console.WriteLine("输入错误");
// }
// int age = 19;
// Console.WriteLine(age+10);
// int r = 5;
// Console.WriteLine(Double.Pi*(r^2));
// Console.WriteLine(2*Double.Pi*r);
// int a = 100, b = 69, c = 80;
// Console.WriteLine((a+b+c)/3);
// const float price = 285;
// const float trousers = 720;
// Console.WriteLine(price*2+trousers*3);
// Console.WriteLine((price*2+trousers*3)*0.38);

//31
//30
//42
// int a = 10, b = 20;
// int num = a++ + ++b + a++;
// Console.WriteLine(num);

// int a = 99, b = 89;
// int c = a;
// a = b;
// b = c;
// Console.WriteLine(a);
// Console.WriteLine(b);
// const int a = 24*60*60;
// const int b = 60*60;
// const int c = 60;
// const float time = 987652;
// int sec=(int)(time % c);
// int min = (int)time %b/c;
// int hour = (int)time %a/b;
//
// int day = (int)time / a;
// Console.WriteLine(day+"_"+sec+"_"+min+"_"+hour);
// const string name = "alice";
// Console.WriteLine("你好"+name);

// string name = "alice";
// int age = 33;
// string email = "alice@gmail.com";
// string address = "123 Main Street";
// int preferSalary = 100;
// Console.WriteLine("姓名{0}，年龄{1}，邮箱{2}，家庭住址{3}，期望工资{4}",name,age,email,address,preferSalary);


// Console.WriteLine("输入用户名");
// string name =  Console.ReadLine();
// Console.WriteLine("输入年龄");
// string age =  Console.ReadLine();
// Console.WriteLine("输入班级");
// string classnumber =  Console.ReadLine();
// Console.WriteLine("用户名{0}，年龄{1}，班级{2}", name, age, classnumber);
//

// int a = 20, b = 10;
// Console.WriteLine(a>b?a:b);
// string a = Console.ReadLine();
// Console.WriteLine(a=="帅哥"?a:"美女");

// Console.WriteLine("name");
// string n = Console.ReadLine();
// Console.WriteLine("c#");
// int q = int.Parse(Console.ReadLine());
// Console.WriteLine("unity");
// int y = int.Parse(Console.ReadLine());
// Console.WriteLine(q >= 90&& y >= 90?"毕业":"延毕");

// Console.WriteLine("输入一个年份");
// int q = int.Parse(Console.ReadLine());
// Console.WriteLine(q %400==0||q%4==0&&q%100!=0);

// Console.WriteLine("今天看唐老师视频花了多少分钟？");
// try
// {
//     int q = int.Parse(Console.ReadLine());
//     if (q > 60)
//     {
//       Console.WriteLine("今天看视频花了{0}分钟，看来你离成功又进了一步！",q);
//     }
//     else
//     {
//         Console.WriteLine("你还需要努力啊！");
//     }
// }
// catch
// {
//     Console.WriteLine("请输入正确的时间");
// }



// Console.WriteLine("你的语文成绩是多少分？");
// try
// {
//     int q = int.Parse(Console.ReadLine());
//     Console.WriteLine("你的数学成绩是多少分？");
//     int w = int.Parse(Console.ReadLine());
//     Console.WriteLine("你的英语成绩是多少分？");
//     int e = int.Parse(Console.ReadLine());
//     if (q > 70 && w > 80 && e > 90)
//     {
//         Console.WriteLine("非常棒，继续加油");
//     }
//     else if (q == 100 || w == 100 || e == 100)
//     {
//         Console.WriteLine("非常棒，继续加油");
//     }
//     else if (q > 90 && (w > 70 || e > 70))
//     {
//         Console.WriteLine("非常棒，继续加油");
//     }
// }
// catch
// {
//     Console.WriteLine("格式错误");
// }


// float testscore = 91;
// if (testscore >= 90)
// {
//     Console.WriteLine("爸爸奖励100元");
// }
// else
// {
//     Console.WriteLine("一个月不能玩游戏");
// }

// try
// {
//     Console.WriteLine("请输入一个数a");
//     int a = int.Parse(Console.ReadLine());
//     Console.WriteLine("请输入一个数b");
//     int b = int.Parse(Console.ReadLine());
//     if (a % b == 0 || b % a == 0|| a + b > 100)
//     {
//         Console.WriteLine(a);
//     }
//     else
//     {
//         Console.WriteLine(b);
//     }
// }
// catch
// {
//     Console.WriteLine("格式错误");
// }

// try
// {
//     Console.WriteLine("输入一个整数");
//     int a = int.Parse(Console.ReadLine());
//     if (a % 2 == 0)
//     {
//         Console.WriteLine("Your number is even");
//     }
//     else
//     {
//         Console.WriteLine("Your number is odd");
//     }
// }
// catch
// {
//     Console.WriteLine("格式错误");
// }


// int a =20,b=3,c=5;
// int max =0;
// if (a > b)
// {
//     max = a;
// }
// else
// {
//     max = b;
// }
//
// if (max>c)
// {
//     
// }
// else
// {
//     max = c;
// }
// Console.WriteLine(max);


// Console.WriteLine("请输入一个数字");
//
// try
// {   
//     char a = Console.ReadKey().KeyChar;
//     if (a == 0 || a == 1 || a == 2 || a == 3 || a == 4 || a == 5 || a == 6 || a == 7 || a == 8 || a == 9)
//     {
//         Console.WriteLine("您输入了一个数字");
//     }
//     else
//     {
//         Console.WriteLine("这不是一个数字");
//     }
// }
// catch
// {
//     Console.WriteLine("这不是一个数字");
// }

// Console.WriteLine("输入用户名");
// string a =Console.ReadLine();
// Console.WriteLine("输入密码");
// int b = int.Parse(Console.ReadLine());
// if (a == "admin" && b == 8888)
// {
//     Console.WriteLine("密码正确，成功登录");
// }
// else
// {
//     if(a != "admin"){
//       
//           Console.WriteLine("用户不存在");
//     }
//     else
//     {
//         Console.WriteLine("密码错误");
//     }
// }
    


// Console.WriteLine("输入年龄");
// int a = int.Parse(Console.ReadLine());
// if (a >= 18)
// {
//     Console.WriteLine("可以查看");
// }else if (a < 13)
// {
//     Console.WriteLine("不能查看");
// }else if (a >= 13 && a < 18)
// {
//     Console.WriteLine("是否继续查看（yes/no）");
//     string b = Console.ReadLine();
//     if (b == "yes")
//     {
//         Console.WriteLine("请查看");
//     }
//     else
//     {
//         Console.WriteLine("退出");
//     }
// }

// int salary = 4000;
//
// Console.WriteLine("请输入王老师课程评价");
// string answer=Console.ReadLine();
// switch (answer)
// {
//     case "很兴奋":
//         Console.WriteLine("评定为{0}级，工资为{1}","A",4000+500);
//         break;
//     case "很充实":
//         Console.WriteLine("评定为{0}级，工资为{1}","B",4000);
//         break;
//     case "还好吧":
//         Console.WriteLine("评定为{0}级，工资为{1}","C",4000-300);
//         break;
//     case "难理解":
//         Console.WriteLine("评定为{0}级，工资为{1}","D",4000-500);
//         break;
//     case "枯燥无味":
//         Console.WriteLine("评定为{0}级，工资为{1}","E",4000-800);
//         break;
//     default:
//         Console.WriteLine("格式错误");
//         break;
// }

// int money = 10;
//
// Console.WriteLine("购买型号");
// string answer=Console.ReadLine();
// switch (answer)
// {
//     case "中杯":
//         Console.WriteLine("购买成功，你还剩5元");
//         break;
//     case "大杯":
//         Console.WriteLine("购买成功，你还剩3元");
//         break;
//     case "超大杯":
//         Console.WriteLine("钱不够，请换其他型号");
//         break;
//     
//     default:
//         Console.WriteLine("格式错误");
//         break;
// }

// int i = 0;
// while (i<20)
// {
//     ++i;
//     if(i%2==0)
//     {
//         continue;
//         
//     }
//     Console.WriteLine(i);
// }


// int i = 0;
// while (i < 100)
// {
//     i++;
//     Console.WriteLine(i);
// }

// int i = 0;
// int j = 0;
// while (i < 100)
// {
//     i++;
//     j += i;
//     
// }
// Console.WriteLine(j);

// int i = 0;
// int j = 0;
// while (i < 100)
// {
//     i++;
//     if (i % 7 == 0)
//     {
//         continue;
//     }
//     j += i;
//     
// }
// Console.WriteLine(j);

// try
// {
//     Console.WriteLine("请输入一个数");
//     int num = int.Parse(Console.ReadLine());
//     int index = 2;
//     while (index < num)
//     {
//         if (num % index == 0)
//         {
//             
//             break;
//         }
//         index++;
//     }
//     if(index!=num){Console.WriteLine("不是质数");}
//     else
//     {
//         Console.WriteLine("是质数");
//     }
//
//
// }
// catch
// {
//     Console.WriteLine("格式错误");
// }

// try
// {
//     Console.WriteLine("请输入用户名和密码");
//     while (true)
//     {
//         string name = Console.ReadLine();
//         int password = Convert.ToInt32(Console.ReadLine());
//         if (name=="admin"&& password==8888)
//         {
//             Console.WriteLine("输入正确");
//             break;
//         }
//         else
//         {
//             Console.WriteLine("重新输入");
//         }
//     }
// }catch{
//     Console.WriteLine("格式错误");
// }

// try
// {
//     Console.WriteLine("输入班级人数");
//     int number = Convert.ToInt32(Console.ReadLine());
//     int i = 1;
//     int j = 0;
//     int k = 0;
//     while (i<=number)
//     {
//         Console.WriteLine("请输入第{0}个人的成绩",i);
//         int number2 = Convert.ToInt32(Console.ReadLine());
//         j += number2;
//         i++;
//     }
//
//     k = j / (i-1);
//     Console.WriteLine("平均成绩为{0}，总成绩为{1}",k,j);
// }
// catch
// {
//     Console.WriteLine("格式错误");
// }

// int sum = 0;
// int i = 0;
// while (sum<500)
// {
//     sum += i;
//     i++;
//     
// }
//
// i--;
// Console.WriteLine("加到第{0}个数字就可以使sum>500",i);

// double num =100;
//
// float i = 1f;
// while (num < 1000)
// {
//     num *= 1.2;
//     i++;
// }
//
// i--;
// Console.WriteLine("经过{0}个月，观看视频人数达到1000人",i);

// int i =1;
// int a = 1, b = 1;
// while (i < 19)
// {
//     int c = b;
//     b = b + a;
//     a = c;
//     i++;
// }
// Console.WriteLine(b);//6765

// int num = 2;
// while (num <= 100)
// {
//     int index = 2;
//     while (index < num)
//     {
//         if (num % index == 0)
//         {
//             break;
//         }
//         
//             
//
//         index++;
//     }
//
//     if (index == num)
//     {
//         Console.WriteLine(num);
//     }
//     num++;
// }

// do
// {
//     Console.WriteLine("请输入用户名和密码");
//     string n = Console.ReadLine();
//     string q=Console.ReadLine();
//     if (n == "admin" || q == "8888")
//     {
//         Console.WriteLine("密码正确");
//         break;
//     }
//     Console.WriteLine("error");
//     
// }while(true);

// do
// {
//     Console.WriteLine("请输入你的姓名");
//     string n = Console.ReadLine();
//     if (n == "q")
//     {
//         break;
//     }
// }while(true);

// for (int i = 1; i <= 100; i++)
// {
//     Console.WriteLine(i);
// }

// int sum = 0;
// for (int i = 0; i < 101; i+=2)
// {
//     sum += i;
// }
// Console.WriteLine(sum);//2550

// for (int i = 100; i < 1000; i++)
// {
//
//     if ( Math.Pow(i / 100, 3)+ Math.Pow(i / 10 % 10, 3) + Math.Pow(i % 10, 3) == i)
//     {
//         Console.WriteLine(i);
//     }
// }

// for (int i = 1; i < 10; i++)
// {
//     for (int j = 1; j <= i; j++)
//     {
//         Console.Write("{0}*{1}={2}  ",j,i,i*j);
//     }
//     Console.WriteLine();
// }



// for (int i = 1; i <= 10; i++)
// {
//     for (int j = 1; j <= 10; j++)
//     {
//         if (1 < j && j < 10 && 1 < i && i < 10)
//         {
//             Console.Write(" ");
//         }
//         else
//         {
//             Console.Write("*");
//         }
//     }
//
//     Console.WriteLine();
// }

// for (int i = 0; i < 10; i++)
// {
//     for (int j = 0; j < i; j++)
//     {
//         Console.Write("*");
//     }
//     Console.WriteLine();
// }

// for (int i = 0; i < 10; i++)
// {
//     for (int k = 0; k < 10 - i; k++)
//     {
//         Console.Write(" ");
//     }
//     for (int j = 0; j<i*2-1; j++)
//     {
//         Console.Write("*");
//     }
//     Console.WriteLine();
// }
```

```c#
 #region 知识点二 控制台其它方法
            //1.清空
            Console.Clear();

            //2.设置控制台大小
            // 窗口大小 缓冲区大小
            // 注意：
            //1.先设置窗口大小，再设置缓冲区大小
            //2.缓冲区的大小不能小于窗口的大小
            //3.窗口的大小不能大于控制台的最大尺寸
            //窗口大小
            Console.SetWindowSize(100, 50);
            //缓冲区大小 （可打印内容区域的宽高 ）
            Console.SetBufferSize(1000, 1000);

            //3.设置光标的位置
            //控制台左上角为原点0 0 右侧是X轴正方向 下方是Y轴正方向 它是一个平面二维坐标系
            //注意：
            //1.边界问题
            //2.横纵距离单位不同 1y = 2x 视觉上的
            Console.SetCursorPosition(10, 5);
            Console.WriteLine("123123");

            //4.设置颜色相关
            //文字颜色设置
            Console.ForegroundColor = ConsoleColor.Red;
            Console.WriteLine("123123123");
            Console.ForegroundColor = ConsoleColor.Green;
            //背景颜色设置
            //Console.BackgroundColor = ConsoleColor.White;
            //重置背景颜色过后 需要Clear一次 才能把整个背景颜色改变
            //Console.Clear();

            //5.光标显隐
            Console.CursorVisible = false;

            //6.关闭控制台
            Environment.Exit(0);
            #endregion
```

![image-20250218182944747](./assets/image-20250218182944747.png)

```
#region 知识点一 复习 输入输出
            //输出
            //Console.WriteLine("123123");//光标空行
            //Console.Write("123123123123");//不空行
            //输入
            //string str = Console.ReadLine();
            //如果在ReadKey(true)不会把输入的内容显示在控制台上
            //char c = Console.ReadKey(true).KeyChar;
            //Console.WriteLine(c);
            #endregion
```

![image-20250218205228227](./assets/image-20250218205228227.png)

![image-20250218205306618](./assets/image-20250218205306618.png)

![image-20250219081534697](./assets/image-20250219081534697.png)

![image-20250220091637986](./assets/image-20250220091637986.png)

![image-20250220101123540](./assets/image-20250220101123540.png)

![image-20250220120805022](./assets/image-20250220120805022.png)

![image-20250220141752730](./assets/image-20250220141752730.png)

![image-20250220160758866](./assets/image-20250220160758866.png)

![image-20250220190931360](./assets/image-20250220190931360.png)

ref一定要在外面初始化变量，内部不用

out一定要在内部修改参数，外面不用初始化

这两个功能一样，都可以在函数内部修改某值，外部也修改了。括号要写（ref 参数）或者（out 参数）

![image-20250220194618339](./assets/image-20250220194618339.png)

![image-20250220201609267](./assets/image-20250220201609267.png)

![image-20250220203358440](./assets/image-20250220203358440.png)

![image-20250220203421243](./assets/image-20250220203421243.png)

![image-20250220210559764](./assets/image-20250220210559764.png)

![image-20250221114535530](./assets/image-20250221114535530.png)

![image-20250221114716048](./assets/image-20250221114716048.png)

![image-20250221114803709](./assets/image-20250221114803709.png)

this是环境

是自己

![image-20250221122840293](./assets/image-20250221122840293.png)

代表自己

![image-20250221123921215](./assets/image-20250221123921215.png)

private 不能在外部访问，只能在内部访问

public可以在外部访问并初始化

![image-20250221132227241](./assets/image-20250221132227241.png)

![image-20250221132452585](./assets/image-20250221132452585.png)

![image-20250221132532843](./assets/image-20250221132532843.png)

![image-20250221132620207](./assets/image-20250221132620207.png)

`break` 和 `continue` 是用于控制循环结构的语句，常见于 `for` 和 `while` 循环中

值类型在函数内部更改其值后函数外面的值不变，引用类型在函数内部更改其值后函数外面的值变化

![image-20250221184919053](./assets/image-20250221184919053.png)

ref要不要加 引用类型不需要加，没有new相当于把地址copy了，两个地址指向同一个值

ref的规则，能不能有多个参数加ref，可以

![image-20250221200146216](./assets/image-20250221200146216.png)

if可以理解为任意一个

![image-20250221201801437](./assets/image-20250221201801437.png)

![image-20250221204047145](./assets/image-20250221204047145.png)

![image-20250221204121875](./assets/image-20250221204121875.png)

![image-20250221213505682](./assets/image-20250221213505682.png)

![image-20250221213643095](./assets/image-20250221213643095.png)

在while循环中实现如果0则变成红色

switch检测输入的是什么字符

![image-20250221214322622](./assets/image-20250221214322622.png)

控制不要超出范围，记得写break；

![image-20250221214550637](./assets/image-20250221214550637.png)

`break` 和 `continue` 是用于控制循环结构的语句，常见于 `for` 和 `while` 循环中

但是条件分支语句`switch`也有break；

![image-20250221214926995](./assets/image-20250221214926995.png)

