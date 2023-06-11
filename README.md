# I hacked everything in school from middle school to high school....

***This is a summary article, not an in-depth analysis.***

```If I edit something, i'll be a best student or i'll be the evil and equal really exist ?```

## Middle school.

Going back in time when I was a middle school kid when I was still practicing playing bangbang game on zinhme with a little knowledge of hacking.

On a beautiful day, my friend invited me to the library to read a book, I saw in the library there is a computer for students and teachers to use public about once or twice I used the computer, I checked the history and saw the teacher. Go to the website to enter grades for students as well as send messages to students who have not studied (to be honest at that time, I was very cayyyyyyyy because I often received messages that I did not my homework T_T)

I know the website is [XXX] and the teacher accidentally saved his account and password on the web

With the account shown as (name of the teacher who taught me)

And the password is hidden as *********

![](https://github.com/VHAE04/Mylife_hacking/blob/main/images/passhide.PNG?raw=true)

And with a little F12 knowledge, I opened the command panel and changed type="password" to type="text" to read the password and be able to access my teacher account.

![](https://github.com/VHAE04/Mylife_hacking/blob/main/images/passshow.PNG?raw=true)

But the special thing is that the teacher's account has less privileges than the school or administrator's account 

![](https://github.com/VHAE04/Mylife_hacking/blob/main/images/teacher.PNG?raw=true)

but by accessing my teacher account I got more clues about the other accounts as well as admin accounts, I was going to try all the related passwords as well as easy passwords to hack into those accounts (I later learned it was bruteforce technique) somehow I have hacked 2 admin accounts by the above technique and here are the features and admin accounts. well and i can accessing admin account (the tool I created to bruteforce code in autoit language was also the first language I learned)

![](https://github.com/VHAE04/Mylife_hacking/blob/main/images/admin.PNG?raw=true)

Here I have full rights to edit the scores of sending mass messages to parents student teacher, private information and more.......

After that, I emailed my teacher about her account being exposed and I was suddenly invited to the principal's room to have a drink and was reminded of the hacking behavior by in the middle of the lesson ._. although I'm trying to make schools safer.

ps If you often read newspapers, you will see this: [https://zingnews.vn/loi-khai-9x-nhan-1700-tin-con-ong-ba-hoc-ngu-nhu-bo-post685735.html](https://zingnews.vn/loi-khai-9x-nhan-1700-tin-con-ong-ba-hoc-ngu-nhu-bo-post685735.html)


## High school.

At the beginning of 11th grade I knew my school managed grades through an app XXX and when everyone was initially given an account  is the phone number and the password was a string of 6 random numbers. first in my head thought of bruteforce technique through the app's api right at my homeroom's phone number and continued to attack the app's api to get all the information of all the teachers as well as the most privileged principal.

![](https://github.com/VHAE04/Mylife_hacking/blob/main/images/app.jpg?raw=true)

![](https://github.com/VHAE04/Mylife_hacking/blob/main/images/data_api_app.PNG?raw=true)

I also learned about web site vulnerabilities and played some ctf.

My school website is created on nukeviet platform and this is also the first time I create a poc about the zero-day xss stored vulnerability about nukeviet and exploit 
it to take control of my school website video tool here : [video](https://www.youtube.com/watch?v=ActzTLmODA4) (because the article is quite long, i'll make another posts that analyzes this zero-day vulnerability).

ps : you can go to [thptvietnambalan-hanoi.edu.vn](http://thptvietnambalan-hanoi.edu.vn) scroll down to the bottom and press ctrl+a to see secret at the bottom of the web

![](https://github.com/VHAE04/Mylife_hacking/blob/main/images/secret.PNG?raw=true)



....Will write more ....

ye come back when just the other day i got my github account back T_T
    
![]()

Continuing this series I will continue to talk about how I hack the school camera.

My school uses 2 network services vnpt and viettel.

Usually when learning Informatics news I tried to scan other networks but failed because the computer department used a separate network solution, vnpt after a while. I redrawn my school's network diagram

![]()

Because of security, the network solution is only linked to the management, accounting, and security departments

....and was surprised when my school just opened a library room and have computers connected to that network

![]()

Here comes the new game begins

I scan all services and machines in the network range and found some computers with smb vulnerability (ms17) and I hacked into it.

The first machine I was able to attack was the security room's machine because it was too old,on this machine I have quite a lot of information because it contains wifi password information, server, and is accessing the total camera, from that way I downloaded the camera decoder from this machine and tried to connect back to the computer. from the information in the txt file in the machine using rdp

About the camera I accessed the camera at the school gate

![]()

With the computer in the finance department I have too much information including exam questions, answers to payroll ..........

![]()


## Go to university

while curious about admissions i hacked the admissions page and reported it to the school ._.

![]()

You can see the old version here, visit and view the page source

http://web.archive.org/web/20230216134634/https://ts.hust.edu.vn/

and then I failed college ;D

....more in future






