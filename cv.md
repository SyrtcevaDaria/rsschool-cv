## My CV project
### Syrtceva Daria<br>
Junior Frontend Developer<br>
![My photo](/assets/images/photo.jpg)<br><br>
**Contact information**:
* [github](https://github.com/SyrtcevaDaria)
* [telegram](https://t.me/Syrtceva)
* [vk](https://vk.com/syrtse)<br><br>

**Brief Self-Introduction:**<br>
My main goal is to understand what I really want to do. I recently discovered frontend development for myself, I like it, so I want to develop further in this direction. I am diligent and hardworking, so everything should work out for me.

**Education:**<br>
* Higher education
  * I am studying in the third year at the St. Petersburg State Electrotechnical University in the direction of software engineering, sometimes it is difficult, but in general I like it.
* Аdditional education
  * ![crt](/assets/images/crt.jpg)<br>I passed the stage 0 in the [rolling scopes school](https://rs.school/)
  * I also took a basic course in [python](https://edu.sirius.online/#/course/374) and [c++](https://edu.sirius.online/#/course/800)

**Skills:**<br>
* Knowledge of the basics of programming languages such as java script, python, c++
* Ability to work with git and github
* Knowledge of css and html, as well as css preprocessors

**Some examples of my work:**<br>
* [snake game](https://rolling-scopes-school.github.io/syrtcevadaria-JSFEPRESCHOOL2023Q2/random-game/)
* [image galery](https://rolling-scopes-school.github.io/syrtcevadaria-JSFEPRESCHOOL2023Q2/image-galery/)
* [audio player](https://rolling-scopes-school.github.io/syrtcevadaria-JSFEPRESCHOOL2023Q2/audio-player/)
* [library](https://rolling-scopes-school.github.io/syrtcevadaria-JSFEPRESCHOOL2023Q2/library/)

**Code Examples:**<br>
[Link to kata](https://www.codewars.com/kata/59752e1f064d1261cb0000ec)<br>
The solution to this task is presented below:
```javascript
var whatTimeIsIt = function(angle) {
  let hour = Math.floor(angle/30);
  let ansHour = hour;
  if (hour===0){
     ansHour = 12;
  }
  ansHour = ansHour.toString();
  ansHour = ansHour.length < 2 ? '0' + ansHour : ansHour;
  let minut = angle-hour*30;
  let ansMin = Math.floor(minut/0.5);
  ansMin = ansMin.toString();
  ansMin = ansMin.length < 2 ? '0' + ansMin : ansMin;
  return ansHour+":"+ansMin;
}
