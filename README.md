# my-startup
## Notes
My CS260 startup project and notes

Change from dev environment

Change from GitHub

Change from VS Code

When I got to the merge issues part of the assignment, I couldn't figure out how to get the two versions to merge until I used VS Code. I think this was useful for me to figure out what way is easiest for me to find solutions to common problems. I am excited to keep using GitHub since it is really fascinating to me how the branches can communicate with each other. I will try to commit often so I can keep good track of my work in GitHub

In HTML don't forget your closing tags! Also, W3Schools has really good info for using HTML, so if you get stuck, try visiting their website.

###### Midterm Notes
- div = division
- Point to another DNS, use CNAME (to IP = A)
- Load fonts using @import (link)
- Promise async other code will execute unless await specified
- JSON key always in double quotes, undefined is not valid
- class uses .class
- id uses #id
- in regex / opens and closes (usually ends with /i)
- no equal sign on function declaration unless anonymous
- Pals Before Marriage
- Map does a thing to each val of array and maps to that new val
- textContent sets child text
- subdomain before domain name followed by period
- flex columns up->down
- flex rows left-> right
- js object must have colon
- chmod +x deploy.sh makes script executable
- ssh shells to remote
- sudo executes as root user

###### Final Notes
- Cookies allow server to store on client
- Fetch can be used in front end and back end
- HTTP headers (Authorization, Accept, Content-Type, Cookie, Host, Origin, Access-Control-Allow-Origin, Content-Length, Cache-Control, User-Agent)
- JSX does not include CSS
- Express middleware: Must match the method, then match url, regular expressions
- Daemon: Starts when computer rebooted, PM2, executes independent of user, can fork other processes
- Passwords hashed to improve security
- Routes to components have URL in them (path=)
- WebSocket allows peer to peer instead
- Port 80 is reserved for HTTP, 20 = FTP, 22 = SSH, 25 = SMTP, 53 = DNS, 110 = POP3, 123 = NTP, 161= SNMP, 194 = IRC, 443 = HTTPS
- Back end only responds if something is sent to it in WS
- Reg ex are case sensitive (unless ?i)
- HTTP status codes: 100 = continue, 200 = success, 300 range = caching or redirects, 400 range = error codes, 500 range = service issues
- npm install adds dependency to json file, adds source code to node-modules, locks version (does not add template code)
- USE is global does not depend on HTTP request

###### Simon HTML-
- Learned how to use HTML structures
- Don't forget to save, commit, and push all changes made in VScode
- Re-deploy every time changes are made so web page is updated
- Link to Simon : https://simon.porbeaglesharks.click

- Link to simon github: https://github.com/hhellwig/simon.git

###### Simon CSS-
- Learned how to style using css
- Learned that VSCode will let you select color using a color scale!
- Aligning items is hard!

###### Simon JS-
- Learned how to create local login (use for startup)
- Learned how to make buttons "reactive (can use for match cards)
- Learned how to get score table to update (use for high scores on startup)
- JavaScript can get really complicated...I think I'll probably need a lot of help implementing it in my startup

###### Simon Service-
- Learned how to actually use POST method in application
- Learned how to use service storage versus local storage (implement to keep high scores in startup)
- Service is not too bad when you take the time to understand...start early so you can take your time!
- It can actually be less complicated than local storage, especially for scoreboards

###### Simon DB-
- DO NOT forget to install mongodb FIRST
- If the server isn't working try restarting it from ssh again
- Use similar js for saving scores in startup
- Sometimes you just need to refresh (git status, server, production, etc)
- Learned how I will use a my database to save scores for my game

###### Simon Login/Authentication-
- I learned what a cookie actually is and why websites use them!
- Can use similar implementation for my startup, but might need some tweaks on the styling
- There is a very specific balance between security and ease of use
- Don't forget to install bcrypt and cookie-parser and uuid
- Hashing is how we compare passwords without revealing passwords

###### Simon WS
- Websocket it used for storing, sending, and receiving messages. It can connect simultaneously instead of waiting for both users to access the server
- Implement ws to create a chat for my startup
- Communicate using send() for messages
- Refer to WS debug page ad chat page if stuck!
- Add a div for the messages to be sent to

###### Simon React
- Run npm install create-react-app on directory first!
- Running npm build gives you the production deployment-ready version to deploy
- Change .js to .jsx
- React just takes your current elements and turns them into components
- Create child components to simplifiy jsx files
- Learned that react takes what you have and makes it into a single "file" application for simplifying

My web server: http://13.59.191.43

My domain name: https://porbeaglesharks.click

## Mad Match

###### Mad Match link: https://startup.porbeaglesharks.click

###### Startup Design -
Images here -
[Note Jan 27, 2023.pdf](https://github.com/hhellwig/startup/files/10524195/Note.Jan.27.2023.pdf)


The simplest games are often the most exciting, and who doesn't love a good matching game! Matching games increase memory skills and have the added benefit of being great fun! In this application, users can log in, play the matching game, and share their time scores with other players! Users can race to beat the fastest times and have their score posted on the leaderboard! Each week will include new match packs with fun new images to match and play with. Users can recommend new match packs to their friends and suggest new match pack themes to the creator! Don't miss out on the match of a lifetime with Mad Match!

###### Features -
- Secure login
- User info saved
- Chatting with other users
- Playing the game
- Giving app feedback
- Competing for the high score!
- Fun!

###### Mad Match Notes -
- I learned that for some reason even though I am using two different css sheets, my program couldn't recognize the difference between them, which is why all of the items in login.css are referred to by id names instead of element names
- Learned that the best resource for learning bootstrap is either bootstrap website or stack overflow
- Testing using the web debugger can help determine if viewer will work on different devices
- Don't get frustrated! Sometimes it's just an easy fix! Comment out a line and test to see if it changes anything
- If it's not working, try wrapping it in another div ;)
- Class and Id's can be really important for distinguishing items! Use them and use names that make sense!

###### Mad Match JS -
- If you can think to do it, it has probably already been done. If you can find code that does what you want and you understand how to implement it, then don't be afraid to add it and make it your own. Don't struggle to solve a problem that already has a solution.
- Don't go too fast. If you type quickly you are liable to make mistakes like typos that are hard to find. Better to go slow and make sure you have it right the first time than to search you code for a single missed letter. (Also make sure that the IDE doesn't autocorrect to something you didn't mean)
- Spread out your work
- Break a problem down to smaller tasks
- Don't forget the () after functions, unless you are passing it as a parameter
- Functions must be called somehow---button press, window.onload, etc.

###### Mad Match Service -
- I learned a lot about security in login for different web applications
  - Passwords are often hashed for secure storage
  - Database can be used to store user information
  - Maybe eventually I can include user scores in that info
- Websocket allows for multiple users to chat all at the same time
- You cannot use the secure log in from VS Live, so use the debugger instead by pressing F5
- Don't forget to download the node packages you need before running!
- Keep it simple, complicating databases and service will only confuse you and your users
- Note: think about getting rid of the "Are you sure" message...not sure if it really contributes to the interface
