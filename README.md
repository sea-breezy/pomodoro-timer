# Pomodoro timer 
A simple, neumorphic timer app to help you boost your productivity. Working is cycles of 25min work 5min break and after 3 cycles of work you get a longer 15min break. If you don't want to wait for the cicles to complete, you can skip to the next part.
Click for [Demo](https://pomodoro-app1.netlify.app/).
<br><br>
<div align="center">
<img src='./public/Pomodoro Timer Screenshot.png' width=300px>
</div>

<br>

<h2> Main Learning Points</h2>

- Practised Tailwind CSS
- Used neumorphic styling
- Used useRef hook
- Used setInterval & clearInterval
- The main problem we faced was with clearInterval onClick. It took a lot of digging into google forums but the issue we had was the pause button kept on resetting so useRef seemed to do the trick. 'useRef is basically useState but React won't render component when ref changes nor ref value will change when render happens'. 
Solution found in https://www.reddit.com/r/reactjs/comments/y1aorm/clear_interval_is_not_working_on_onclick/

<h2> Stretch Goals</h2>

- Allow the user to select number of work cycles and change length of breaks
- Write tests

<h2> Built with</h2>

- Next.js
- Tailwind CSS

<h2> Installation</h2>

1.  `git clone https://github.com/socweekendprojects/pomodoro-timer.git`

2. <code>npm i & npm run dev</code>


