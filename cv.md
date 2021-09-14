# Yan Tamashchuk

## Junior/Trainee Frontend Developer

## Contact information:

**Phone:** _+380954551130_

**E-mail:** *yantamashchuk@gmail.com*

**[LinkedIn](https://www.linkedin.com/in/yan-tamashchuk-2aa8a5220/)**

## **Briefly About Myself:**

My goal: to start a career in IT as a front-end developer.
Priorities: studying new technologies of js to create a product.
I approach the study of this area with enthusiasm and am ready to give all my strength and time to improve in this direction.
![mount](mount.png)

## **Skills and Proficiency:**

- HTML, CSS Basics
- JavaScript
- Git, GitHub
- VS Code
- Photoshop
- Webpack, vs code extensions, npm
- elementary react

## **Code example:**

    function formatDuration(seconds) {
        const year = Math.floor(seconds / (365 * 24 * 60 * 60))
        const day = Math.floor(seconds / (3600 * 24) % 365)
        const hour = Math.floor(seconds % (3600 * 24) / 3600)
        const minute = Math.floor(seconds % 3600 / 60)
        const second = Math.floor(seconds % 60)

        const years = year > 1 ? ' years, ' : ' year, '
        const days = day > 1 ? ' days, ' : ' day, '
        const hours = hour > 1 ? ' hours, ' : ' hour, '
        const minutes = minute > 1 ? ' minutes, ' : ' minute, '
        const secondPlural = second > 1 ? ' seconds, ' : ' second, '

        let string = ''

        if (seconds === 0) return 'now'
        if (year > 0) string += `${year + years}`
        if (day > 0) string += `${day + days}`
        if (hour > 0) string += `${hour + hours}`
        if (minute > 0) string += `${minute + minutes}`
        if (second > 0) string += `${second + secondPlural}`

        string = string
            .trim()
            .slice(0, -1)
            .replace(/,(?!.*,)/, ', and')


        return string.substring(0, string.lastIndexOf(","))
        +
        string.substring(string.lastIndexOf(",") + 1)
    }

## **Courses:**

- learnjavascript.ru
- RS Schools Course «JavaScript/Front-end. Stage 1»
- js marathone
- react marathone
- html, css marathone

## **Languages:**

**English**
А2

