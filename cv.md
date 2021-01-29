Sergey Bazylevich
Tel: +375297218164, E-mail: cbilling36@gmail.com
The priority is to study a full stack developer and learn English. I can work and study very hard. No experience in commercial development.
HTML - basic, CSS - basic, JS - basic, Salesforce Aura - basic, Apex - basic
```javascript
window.onload = function () {
    function clock() {
        var date = new Date(),
            day = date.getDate(),
            weekDay = date.getDay(),
            weekDayArr = ["ВОСКРЕСЕНИЕ", "ПОНЕДЕЛЬНИК", "ВТОРНИК", "СРЕДА", "ЧЕТВЕРГ", "ПЯТНИЦА", "СУББОТА"],
            month = date.getMonth(),
            monthArr = ["01", "02", "03", "04", "05", "06", "07", "08", "09", "10", "11", "12"],
            year = date.getFullYear(),
            hour = date.getHours(),
            min = date.getMinutes(),
            sec = date.getSeconds();

        if (day < 10) day = "0" + day;
        if (hour < 10) hour = "0" + hour;
        if (min < 10) min = "0" + min;
        if (sec < 10) sec = "0" + sec;

        document.getElementById("date").innerHTML = day + "." + monthArr[month] + "." + year;
        document.getElementById("day").innerHTML = weekDayArr[weekDay];
        document.getElementById("hour").innerHTML = hour;
        document.getElementById("minute").innerHTML = min;
        document.getElementById("second").innerHTML = sec;
    }

    var timer;
    ```
Junior Front-end Developer on courser https://github.com/uspehcoursbrest/BazylevichDiplomaProject
Belarusion State Agrarian Technical University - Ingineer-Energy, Education center Uspeh Front-end Development courses
A2 - no practice
