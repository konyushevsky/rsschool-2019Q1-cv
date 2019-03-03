# Resume

1. Name and surname: Oleg, Konyushevsky.
---

2. Contacts:
    + tel.: +375333017089
    + email: olegkonyushevsky@gmail.com


---
3. Summary: Learn to write good apps. Develop. Feel happy about what I do.


---
4. Skills:
    + git
    + html/css
    + js (and node)
    + PHP (a little bit)
    + sql (a little bit)
    + с (a little bit)


---
5. Some piece of my program:
   ```
      function drawCheckMark() {
        var checkMark = document.getElementById('check_mark');
        checkMark.width = checkMark.clientWidth * window.devicePixelRatio;
        checkMark.height = checkMark.clientHeight * window.devicePixelRatio;

        var context = checkMark.getContext('2d');
        context.beginPath();

        context.lineWidth = 1.6 * window.devicePixelRatio;

        context.arc( checkMark.width / 2, checkMark.height / 2, checkMark.height / 2 - context.lineWidth / 2, (Math.PI/180) * 0, (Math.PI/180) * 360, false );

        context.moveTo(checkMark.width / 3.5, checkMark.height / 2);
        context.lineTo(checkMark.width * 0.445, checkMark.height * 0.65);
        context.lineTo(checkMark.width * 0.7, checkMark.height / 2.6);

        context.strokeStyle = '#484848';

        context.stroke();
    }
    ```


---
6. My experience is a few made sites.


---
7. Education: Higher Polish School at BIP. We studied higher mathematics, logic, programming, and statistics. I also completed a course intro to UX / UI design on cursera.


---
8. English level A2.
