# Timer

Hello everybody! 👋 </br>
✨ Welcome to the Timer Project! This project is a simple yet functional timer application developed using HTML, CSS, and JavaScript. It allows users to set a specific time duration, start the countdown, pause it, and reset the timer. The interface is designed to be intuitive and user-friendly, making it easy for anyone to use the timer effectively.

## 👀 Overview

### 📷 Screenshot

![screencapture-tucecifci-github-io-Timer-2024-06-14-10_33_14](https://github.com/tucecifci/Timer/assets/151346784/d65a84e7-d173-4fe0-8f56-edfb70262f8f)
![screencapture-tucecifci-github-io-Timer-2024-06-14-10_38_45](https://github.com/tucecifci/Timer/assets/151346784/5610e41e-94ae-4e6c-9eb2-0bfbd63f2311)


### 🔗 Links

- https://tucecifci.github.io/Timer/

## My process

### 💡 Built with

- HTML: Structures the application’s layout.
- CSS: Styles the interface, ensuring it is aesthetically pleasing and responsive.
- JavaScript: Powers the timer functionality, including starting, pausing, and resetting the timer.

  
### 🧠 What I learned

- Event Handling: Improved skills in using JavaScript to handle user interactions through event listeners.
- DOM Manipulation: Gained experience in updating the DOM dynamically to reflect the timer's state.
- CSS Styling: Enhanced ability to create responsive and visually appealing designs using CSS.
- JavaScript Logic: Deepened understanding of timing functions and state management in JavaScript.
  
```javascript
  tartStopBtn.addEventListener("click", function () {
  if (timerStatus === "stopped") {
    timerInterval = window.setInterval(stopWatch, 1000);
    document.getElementById(
      "startStopBtn"
    ).innerHTML = `<i class="fa-solid fa-pause" id="pause"></i>`;
    timerStatus = "started";
  } else {
    window.clearInterval(timerInterval);
    document.getElementById(
      "startStopBtn"
    ).innerHTML = `<i class="fa-solid fa-play" id="play"></i>`;
    timerStatus = "stopped";
  }
});
```

### 👩🏼‍💻 Features

- Set Timer: Users can input a specific duration for the timer.
- Start/Pause Timer: Users can start and pause the countdown as needed.
- Reset Timer: Users can reset the timer to its initial state.
- Visual Countdown: A dynamic visual display shows the remaining time.
- Responsive Design: The timer adjusts to different screen sizes for mobile and desktop use.


### 🤔 How to Use

1.Set the Timer:
- Input the desired time duration in the provided field.
2. Start the Timer:
- Click the "Start" button to begin the countdown.
3. Pause the Timer:
- Click the "Pause" button to halt the countdown temporarily.
4. Reset the Timer:
- Click the "Reset" button to revert the timer to the initially set duration.

### 🤌🏻 Useful resources

- https://www.youtube.com/watch?v=5fb2aPlgoys
- https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model

## 🏳️‍🌈 Author

- Tuğçe Çifci - [@tucecifci](https://github.com/tucecifci)
- Frontend Mentor - [@tucecifci](https://www.frontendmentor.io/profile/tucecifci)
