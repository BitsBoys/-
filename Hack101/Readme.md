使用样例：
python login.py -u "http://127.0.0.1/08d20761c3/login" \
  -U username2.txt -P password2.txt \
  -C "Your Own Cookie" \
  -H "Host IP Address " \
  -R "Your Own Referer" 

-u或者--URL指定需要暴破的地址；
-U或者--Username指定暴破用户名使用的字典；
-P或者--Password指定暴破密码使用的字典；
-C或者--Cookie指定使用的Cookie参数；
-H和-R后续学习补充。

补充说明一下：
本脚本产生自在学习Hacker101网站的第Petshop Pro题为了获取第二个Flag需要登录的场景中，适用于该题目的学习和研究，不建议用作其他用途。
在Hacker101中的第Petshop Pro题中，使用错误用户名登录返回的“Invalid username”和使用错误密码登录返回的“Invalid password”的字符串长度一样长，因此不能通过返回页面的长度确定参数。
