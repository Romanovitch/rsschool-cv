# Romanovitch Konstantin

## Contact Info
*Phone number* : +375336252769<br>
*E-mail* : rokos.job@gmail.com<br>
*LinkedIn profile* : [Konstantin Romanovitch](https://www.linkedin.com/in/konstantin-romanovitch-1b21a198/)<br>
*github* : [Romanovitch](https://github.com/Romanovitch/)<br>

## Summary
Novice frontend-developer with technical education.<br>
I read an article about SEO. It has awakened great interest in the topic of how to create and how work websites. <br>
I got acquainted with SEO, Software Testing and how to create websites. <br>
I like to create. It influenced my vision for the future.<br>
I have decided to change the direction of my professional activity and realize myself in the IT industry.<br>
Dedication, perseverance and good self-education skills help me move towards this goal.

## Technical Skills
* <strong>Programming languages and technologies :</strong> 
    Javascript, HTML/Pug, CSS/SCSS, PHP(a little bit), Adaptive/Responsive Markup<br>
* <strong>Programming practices :</strong>
    Agile, Kanban, Scrum<br>
* <strong>Framework and Libraries :</strong>
    bootstrap<br>
* <strong>Tools :</strong>
    WebStorm, VSCode, Photoshop, Zeplin, PSDetch, GIT, Gulp, SQL DB (Access, MySQL), Open Server<br>
* <strong>Software Testing tools :</strong>
    Android Studio, Charles proxy, Postman<br>
* <strong>Other skills :</strong>
    advanced user in: Windows, AutoCAD, Excel<br>

## Code example
```javascript
function howManyNodes(typeOfNode) {
    return Array.from(document.childNodes)
        .filter(iNode => Array.from(iNode.childNodes).length !== 0)
        .reduce(function reducer(sum, iNode) { 
        return Array.from(iNode.childNodes).reduce(reducer, sum) 
            + (iNode.nodeType === typeOfNode ? 1 : 0);
    }, 0);
}
```
