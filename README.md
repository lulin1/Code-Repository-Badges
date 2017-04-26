# Code-Repository-Badges
代码徽章中文版入门讲解。

幻灯片1
Code Repository Badges 
路琳 2017  4月


幻灯片2
Why ?
幻灯片3
Code Repository Badges
代码的勋章 -- 高质量代码的认证
可以把它想象成牛仔裤上的标牌和名牌商品上的商标。
幻灯片4
哪些项目在使用代码徽章？

React :

Vue:

......
freeCodeCamp:
幻灯片5
	What ?
幻灯片6














幻灯片7


Including a badge from "Inch-CI" .

从 "Inch-CI" 中获得一个徽章可以证明文档在你的项目中是具有较高优先级的 ，项目结构良好。

幻灯片8
What is Inch CI?

在项目的 README 中提供了 徽章，向人们表明记录代码是一件很酷的事情。
旨在提高开源文档的可视性。


What is this "Inch"?


Inch 是一个Ruby的文档测量工具，用来帮助人们编写和管理代码。这是一个命令行工具，根据文档的完成度给出相应的分数。


幻灯片9
What is the goal?

在项目的 README 文件中加上徽章，将会有益于该项目（因为人们看到了该项目的文档有被很好的管理），也有益于社区发展（提高了文档的可视性）。

Which languages are supported?

Currently Inch supports Elixir, JavaScript, and Ruby.

幻灯片10


Node Security Project  Live Check
Node Security Project (**NSP*) 

NodeSecurity 是由 Node Security Project 提供的一个免费服务，旨在检查项目中的依赖项是否有安全漏洞。
这个徽章是个很好的方式 来向使用你的应用程序/网站的人确保代码是经过安全检查的。

幻灯片11



Continuous Integration (CI)即持续集成，是一个软件开发过程，只要提交代码，CI自动测试，编译，优化，上线。即所有的开发工作被集成到一个预定义的时间内，或者说自动测试和构建事件和由此产生的工作。

将一堆工具链合到一起，旨在开发过程中尽早的识别出错误。




幻灯片12
Continuous Integration


Travis CI  帮助我们解决自己在运行CI时的麻烦和繁琐的工作，使我们可以集中注意力在项目上。  
Travis CI是一个对Github上所有开源项目免费的的持续集成平台。
使用一个名为.travis.yml的文件，在代码发生变化时能够触发自动构建。


幻灯片13
Key Advantages of Travis-CI:

不用安装任何东西(Travis是基于web的 ... Not a heavy Java Application you have to host yourself)
 对托管在Github上的开源项目免费。
很好的集成了GitHub (without any developer effort!)


幻灯片14



CodeClimate 是一个代码质量估分工具，他根据项目代码的一系列因素，（eg：复杂性/简洁性、可读性、可维护性、重复度和每个文件的代码行数）来对项目进行测量并给出相应的分数。
最高分数是 4.0


幻灯片15


"Any fool can write code that a computer can understand. 
Good programmers write code that humans can understand." 
-- Martin Fowler

goodparts 是一个JS  “linter”，是用来检查代码风格/错误的小工具，使JavaScript只包括 "The Good Parts" 

幻灯片16
Key Advantages of using goodparts :
Readability - 使用较少的JS语法，可以直接获得他所做的核心工作，不必浪费时间去了解它的具体写作方式。
Portability - 具有很好的移植性，包括老式浏览器及设备。
Beginner-friendlyness - 使用了较少的JS功能，降低了新手的学习成本。

幻灯片17


点击徽章会跳转到Gitter 里本项目所在的公共聊天区域，将下面代码粘贴到项目的README.md文件里：

 [![Join the chat at https://gitter.im/{ORG-or-USERNAME}/{REPO-NAME}]
(https://badges.gitter.im/Join%20Chat.svg)]
(https://gitter.im/dwyl/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


如果想让其他人参与到自己开发的项目中来，可以通过该徽章进行提示：

 [![contributions welcome]
(https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)]
(https://github.com/dwyl/esta/issues)
幻灯片18
	How ?
幻灯片19
Security


1. Sign Up for the Service
Sign up at: https://nodesecurity.io/signup
You will receive an email asking you to verify the email address you used to sign up. Click on "Verify Account"：





幻灯片20
Security


2. Create your "Organisation" (if you don't already have one)

Once you have verified your account with NSP create an "organization" so you can keep track of a group of Node.js based projects.

If you are using NSP for personal projects just name your "org" the same as your GitHub username.








幻灯片21
Security


3. Create a GitHub Integration for your Project
Click on the button to create a GitHub Integration:








You will be re-directed to a GitHub "Auth" (Login) Page.
Login and authorize Node Security Project to access your account. Remember to grant authorization for the org where you project is (if applicable):
Then click on the Authorize Application button at the bottom of the page: 








幻灯片22
Security


3. Create a GitHub Integration for your Project
Once you do this you will be re-directed back to https://nodesecurity.io/orgs/dwyl/github/  where you will need to select the Org again .
You will then be presented with a list of projects.
In our case we are enabling NSP Live checking for our hapi-auth-jwt2 project:



Once you click the Submit button you're done! You should see the following message:








幻灯片23
Security


3. Create a GitHub Integration for your Project
And if you scroll down you will see that the project checkbox is checked.

Going back to your "Projects" page you will see:





So you know it's working ! 




幻灯片24
Security


4. Show the badge on your Project
Click on the project link and then on the badge:
Copy the Markdown code shown which includes the unique token for your project. and paste it into the README.md of your project. e.g: NSP Status













幻灯片25
Security


Note :
 just having a 3rd party service telling you there aren't any know vulnerabilities does not guarantee that your app is "secure"! You still need to write good code that escapes all input and follows "best practice"! But the nsp badge & service is a useful early warning system.







幻灯片26
Continuous Integration

To get started with Travis CI: #   https://travis-ci.org/
1. 使用GitHub账号登录Travis CI，点击确定GitHub访问权限。
2. 到GitHub主页选择使Travis CI可以访问的GitHub的代码库。
3. 在选择的代码库中添加一个.travis.yml 文件，push到git中，这时会触发一个Travis CI build。  

 什么是.travis.yml ？

幻灯片27
Continuous Integration

.travis.yml 文件用来告诉Travis CI要做什么。
项目使用的编程语言
运行时的版本
构建前要执行哪些命令或脚本



.travis.yml

幻灯片28
Continuous Integration


To get started with Travis CI: #
 4. 检查 build status ，查看生成是否通过或失败。





幻灯片29
CodeClimate 














幻灯片30
CodeClimate 








幻灯片31
CodeClimate 






幻灯片32
Documentation 

Visit:  http://inch-ci.org/learn_more  and paste your GitHub username (or organisation name) and repository name into the form then click Evaluate.


幻灯片33
Documentation 


Then you can copy the badge directly from the resulting page. e.g:







幻灯片34
JavaScript the goodparts (code style/linting)  

First install the NPM Package in your Node.js/JS project :

   $ npm install goodparts --save-dev
Then add the following script to your package.json :


{
  "lint": "node_modules/.bin/goodparts path/to/files/for/linting"
}
幻灯片35
JavaScript the goodparts (code style/linting)  

Now when you run the command:


   $ npm run lint


幻灯片36
goodparts - Autofix  

使用 --fix 可以自动修复一大部分的errors :

   $  node_modules/.bin/goodparts /path/to/dir --fix
Example: (fixing the linting "errors" from the example above)





Note:  --fix  只修复缺少分号的问题，但不能删除额外的（未使用的）被定义的变量。


