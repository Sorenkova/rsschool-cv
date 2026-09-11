# Yauheniya Sarankova

### Contact Information
* **Telegram:** [@sorenkova](https://t.me/sorenkova)
* **Email:** [sorenkova@gmail.com](mailto:sorenkova@gmail.com)
* **GitHub:** [github.com/sorenkova](https://github.com/sorenkova)
* **LinkedIn:** [linkedin.com/in/sorenkova](https://linkedin.com/in/sorenkova)
* **Discord:** [@sorenkova](https://discord.com/users/sorenkova)

### Brief Self-Introduction
Motivated Junior Frontend Developer transitioning from a background in linguistics and education. I am passionate about creating clean, accessible, and user-friendly web interfaces. My 5-year experience as an online English tutor has improved my ability to explain complex topics, manage remote workflows, and collaborate effectively. I am eager to apply my analytical skills and dedication to learning in a professional development environment.

### Skills
* **Languages:** HTML5, CSS3, JavaScript (Basics)
* **Tools:** Git, GitHub, VS Code
* **Methodologies:** Responsive Web Design

### Code Example 
Here is a snippet from my custom Pet Sitter Countdown Timer. It calculates the remaining time and formats the output:
```javascript
const arrivalDate = new Date('2026-08-20T09:00:00').getTime();

function updateCountdown() {
    const now = new Date().getTime();
    const distance = arrivalDate - now;

    const timerElement = document.getElementById('timer');

    if (distance < 0) {
        timerElement.innerHTML = '<div class="timer-box" style="grid-column: span 4;"><span class="timer-num" style="color: #B91C1C;">Ваша работа выполнена! 🎉</span></div>';
        return;
    }

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    timerElement.innerHTML = `
        <div class="timer-box"><span class="timer-num">${days}</span><span class="timer-label">дней</span></div>
        <div class="timer-box"><span class="timer-num">${String(hours).padStart(2, '0')}</span><span class="timer-label">часов</span></div>
        <div class="timer-box"><span class="timer-num">${String(minutes).padStart(2, '0')}</span><span class="timer-label">минут</span></div>
        <div class="timer-box"><span class="timer-num">${String(seconds).padStart(2, '0')}</span><span class="timer-label">секунд</span></div>
    `;
}

updateCountdown();
setInterval(updateCountdown, 1000);
```
### Work Experience
**English Language Instructor (Online)** | *2021 – 2026*

* Designed and delivered personalized curricula for 50+ students.
* Managed remote classroom environments and technical platforms.
* Developed strong self-discipline and remote communication skills.

### Education
* **Linguist & Translator (English/German)** | Minsk Innovation University, 2018 – 2023
* **RS School Course:** "Full-Stack JavaScript 2026 Q3" (In progress)

### English Language
* **Level:** C1 (Advanced)
* **Practice:** 5 years of professional teaching experience, constant communication with native speakers, and regular practice of specialized pedagogical methodology.