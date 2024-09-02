# Coming Soon Page
This project is a "Coming Soon" landing page designed to inform visitors that a website is currently under maintenance and will be launching soon. The page is built using HTML, CSS, and JavaScript to create an engaging and dynamic user experience.

<h2>Key Features</h2>
<h3>Countdown Timer</h3>
<h4>Launch Countdown</h4>
The page features a real-time countdown timer that shows the remaining days, hours, minutes, and seconds until the website launch. The timer is automatically updated every second, providing users with precise launch timing. 
<h4>Dynamic Reset</h4>
If the countdown reaches zero, the timer stops and displays "00" for all time units, indicating that the launch time has arrived or passed. 
<h3>Animated Elements</h3>
<h4>Rocket Animation</h4>
The page includes an animated rocket that continuously moves upward, simulating a launch sequence. This adds a playful and visually appealing element to the design. 
<h4>Interactive Button</h4>
A "Learn More" button is prominently displayed, encouraging users to interact further. The button features a subtle animation with a small triangle icon, enhancing the user experience. 
<h2>Technical Overview</h2>
<h3>HTML Structure</h3>
The HTML structure includes a main container that holds all elements, including a logo, countdown timer, and animated rocket. The countdown timer is structured with four separate `div` elements for days, hours, minutes, and seconds, each dynamically updated by JavaScript. 
<h3>CSS Styling</h3>
<h4>Background and Layout</h4>
The page uses a full-screen background image, styled with CSS to cover the entire viewport and ensure a visually consistent layout. Flexbox is used to center the content, with additional positioning for the animated rocket. 
<h4>Responsive Design</h4>
The CSS is designed to be fully responsive, with the layout and elements adjusting smoothly across different screen sizes and devices, ensuring a consistent user experience. 
<h3>JavaScript Functionality</h3>
<h4>Countdown Logic</h4>
JavaScript is used to calculate the time difference between the current date and the launch date, updating the countdown timer every second.

    let countDownDate = new Date("Oct 16, 2024 00:00:00").getTime();
    let x = setInterval(function () {
        // Countdown logic
    }, 1000);

<h4>Animation and Interactivity</h4>
JavaScript also handles the rocket animation and button interactions, ensuring that the page remains lively and engaging for users as they await the site launch. 
<h2>In Summary</h2>
This "Coming Soon" page effectively communicates the upcoming launch of a website, combining a countdown timer with engaging animations and interactive elements. The project utilizes HTML, CSS, and JavaScript to create a polished and responsive design, making it a strong template for any website's pre-launch phase.






