RWD - Responsive Web Design
Semantic Tags - (Header, Section, Footer)
* -> Universal Tag For all the pages in the website
CSR - Client Side Rendering
12/2/26
1.HTML
2.CSS
3.JS
4.Bootstrap, --Tailwind
5.React
6.GitHub


1.Front-End
1.HTML
2.CSS
3.JS
4.REACT
5.Bootstrap
6.Vue js
7.Angular
8.Next js
9.PHP


Backend
1.Database
2.Java
3.Python
4.php
5.API'S
6.Node.ja
7.Express js
8.spring boot
Nuxt .js

Database
1.SQL
2,MySql
3.Postgres
4.Oracle
5.MongoDb

13/2/26
wc3-world wide web

website is the collection of web pages

how to choose 1 or 2

1.based on the usage and requirement
2.backend content changes updated date
4.based on the content
5.based on the response we get
6.based on the server config
user friendly--any one can use==ux


        cloud(aws/azure)/local server
website             server               backend
frontend            laptop(server)       backend
| | |req
------------------->
|
|
|
|
     res
<---------------------



1.static= = A website where pages are already created and the server sends the same fixed content to every user.
some set of content
1.set of webpages=5

2.dynamic = A website where pages are generated at request time using server logic and data.
content  updates accordingly you configure
1.set of webpages=3

meta data:
abc.pdf =
 size
 name

cursor

16/02/26

UTF=unicode transformation format in bits

8 bits

RWD-responsive web design.==bootstrap/tailwind//own code

sementic tags
1.<header>
2.<footer>
3.<section>

attribute  =attribute value
background-color =somecolor
margin=some px/em/rem
padding=px/em/rem
height=px/em/rem
width=px/em/rem


1.browser
2.request to server
3.js content loading.in client side or server side CSR ,SSR==react,angular
4.html content load with stylings

API.            |       webhooks
1.Application programming interface-requesting data from server and expecting response

2.webhooks.-server serves the data

17/2/26
margin/padding:10px,0px

top,-right,-bottom. -left

<ol>
<li>

1.
2.
3.
4.

<ul>
<li>

.
.
.

web storage

1.local
2.session

cookies
1.Inline 
 2. External 
3. Internal

Class = .
Id = #
tag = <tag>

18/2/26

18/2/2026
1. why we use class and why we use id
2. why do we write meta data in html
3. what is phrase titke and meta title but now meta title have been removed from the google
4.anker tag

19/2/2026

Media Queries

`@media` is a CSS at-rule that is used to apply specific styles based on the characteristics of the
device or viewport. It allows you to create responsive designs by targeting different screen sizes,
resolutions, and orientations. By using `@media`, you can define different styles for different
devices, ensuring that your website looks good and functions well across various platforms.


// to create a table in html 
<table>

<tr>

<thead>
<tbody>

<td>

form controls:

1.button
2.checkbox
3.radio buttons
4.search
5.date
6.time
7.text

20/2/26

1.align-items

flex-start
flex-end

2.justify content

space between
space around

function
1.save fn
2.update fn
3.delete fn

CRUD

create
read
update
delete

23/2/26

Cookies(4kb):1000lines

cookies are small text files stored in your browser by websites you visit.They help websites remember information about you between visits.

cookies:=user identity & authentication between browser and server

webstorage(5mb):
web storage=frontend application  state and user preferences.

1.local storage
2.session storage

Local

1.Local storage is a web storage feature that allows websites to store data in the browser with no expirationtime.
2.This means the data remains availabe even after the user closes and reopens the browser or the system is restarted.
3.It is typically used to save long-term data such as user preferences,themes,or login tokens.



session

1. session storage is also a browser-based storage method,
but it only stores data for the duration of a single browser tab session.
2. once the tab is closed, all the session storage data is automatically deleted.
3. It is useful for storing temporary data like form inputs or navigation steps that dont need to persist beyond the current session.
4.unlike local storage,session storage is not shared accross tabs-each tab has its own session.

collabrate:

Git:-
Git is the distributed version control system that helps you track changes in your code,save different versions of your project,and work with others without overwriting each others's work.It allows you to create branches,experiment safely,and easily go back to the older version whenever needed.

Git-->Tool for version control(local machine)

Git hub-->Website(by microsoft) to store and manage git repositories online,

git code commit

push=upload
pop=delete
pull=download

fundamental commands

1.git init-initialize a remote repo

2.git add-Add files to staging

3.git commit-save changes to local repo

4.git status-show file changes

5.git clone-copy a remote repo

6.git push-upload commits to remote

7.git pull--download and merge from remote

8.git branch-show branches

9.git checkout-switch branches

10.git remote -v --show connected remote repo

24/2/26

used daily in real project commands

11.git log --view commit history

12. git merge – Merge another branch

13. git fetch – Download updates without merge

14. git switch – Modern branch switching

15. git stash – Save uncommitted changes

16. git stash pop – Restore stashed work

17. git reset – Undo staged/committed changes

18. git rm – Remove a file

19. git mv – Rename/move a file

20. git diff – See the difference between versions

GIT COMMANDS TO PUSH A PROJECT:

1.git -v
2.git init
3.git status
4.git add .
5.git commit -m "first commit"
6.git status
7.git remote add origin https://github.com/SAH389/frontend.git
8.git branch -M main
9.git push -u origin main

GIT COMMANDS TO CLONE /MAKE CHANGES - PUSH AGAIN:
1.git clone (url link)
2.cd (path)...........modify
3.git status   
4.git add .
5.git commit -m "Update index.html with latest changes"
6. git push -u origin main

TO CHECK WHO COMMITED OUR PROJECT:

git log -2


Bootstrap

UTF-8
1.Unicode Transformation Format is used as 8-bit in html-5, to make our site globally readable and adaptable.

2.UTF-8 is used to encode all the characters in the world. It is used to encode all

3. Amoung 8-bits english is occupied as 1-bit.

4.Meta tags are used for SEO purpose (Search-Engine-Optimization)

5. In html-4 we have UTF as 4 bit (UTF-4) i.e can be used only for single languages.


RWD
Responsive Web Design
1.Bootstrap will adjust components based on the screen size.
2.Bootstrap is a CSS framework that helps you build responsive and modern websites quickly using pre-designed components.