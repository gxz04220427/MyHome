# A second-hand housing sale site 

##Intro

该项目所设计的系统为基于Web的城市房屋出租出售系统的设计与实现，网站的浏览者
通过注册，登录可以有浏览房屋信息，发布出售出租信息和发布求购求租信息的功能。

底层的架构是我们经常使用的 struts2 MVC 架构。

##Model

Model 层使用了 **Hibernate** 做数据持久化处理。

##UI

页面是基于 **Bootstrap** 的前端框架。

##JavaMail

调用了 **JavaMail** 的接口，实现了注册时的邮箱验证功能。

##Service

本系统实现的功能包括用户注册、用户登陆、房屋查找、求助信息查找、房屋介绍、房屋发布，还包括后台管理员，为管理员提供了
房屋管理、求助信息管理、用户管理、管理员管理等。由于房屋的特殊性，和同城的便利性，本系统不提供线上的沟通聊天功能，为
了确保用户的信息的安全，只能通过线下的手机或当面沟通交流。通过面对面的沟通也能更好地了解房屋的信息。

1. 用户注册：为了实现房屋卖家与卖家的沟通性，为方便用户的使用，必须先注册自己的信息。不注册登陆用户只能进行网站的浏览。

2. 用户登录：对于已经注册的用户只有在登录后才能发布房子的信息和求助的信息。

3. 房屋查找：针对用户的要求，精准的筛选为用户提供房屋信息。

4. 房屋介绍：对于出租出售的房屋进行图片展示和相关的文字介绍。

5. 求助信息查找：按要求浏览同城的所有求房源的信息。

6. 房屋发布：发布自己的房子，需要录入房子的信息，图片介绍，和自己的信息。

7. 个人中心：编辑个人资料，管理发布的信息。

8. 房屋管理：管理员对网站中房屋发布信息经行浏览和删除。

9. 用户管理：管理员对所已经注册了的用户的信息进行浏览、删除。

10. 求助信息管理：管理员对发布的求助信息经行浏览，删除。

11. 管理员管理：管理员可以再添加其他的管理员。

##IDE

系统采用IDEA开发，后台由Navicat for mysql提供数据支持。



