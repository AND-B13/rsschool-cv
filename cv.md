# Budovskey Andrey Gennadievich<br>Junior Frontend Developer

### Contact information:
* **Phone:** [+7-967-006-07-21](tel:+7-967-006-07-21)
* **E-mail:** [andrey13budovskey@gmail.com](mailto:andrey13budovskey@gmail.com)
* **Telegram:** [@AND_B13](https://t.me/AND_B13)
* **Discord:** [AND_B13](https://discord.com/309433350681133057)

### Briefly About Myself:
I became engrossed Frontend development with this field a year ago when I began my journey in it. I had no knowledge of development at all prior to that point, and I had no idea what the code that has been the subject of widespread discussion since 2020 actually looked like.

Over the past year, I've gotten better at HTML, CSS, JavaScript, and VueJS, and I now feel confident creating websites and applications. Still, I'm learning a lot, and I plan to keep expanding my knowledge through online courses and independent study.

As a front-end developer, my ability to think creatively and persistently through problems is one of my strongest traits. I genuinely like breaking down complex situations and developing novel solutions.

Even though I don't have much work experience, I've worked on several commercial and educational projects over this time, which has given me a wealth of information and experience. Realizing my full potential as a web interface development professional is my main goal.

I feel confident in stating that my determination to learn and my fortitude are my greatest assets.

### Skills and Proficiency:
* *HTML5, CSS3, SCSS, SASS*
* *Bootstrap(4,5)*
* *Gulp(4), Webpack(5)*
* *VueJS(2,3)*
* *Git, GitHub, GitLab*
* *VS Code*
* *Figma, Adobe Photoshop*
* *Tilda*

### Code example:
**Shortest Word:** 
*Simple, given a string of words, return the length of the shortest word(s).*
*String will never be empty and you do not need to account for different data types.*

```
function findShort(s) {
    return s.split(' ').reduce((one, two) => {
        if (typeof one === 'number') {
            return Math.min(one, two.length);
        } else {
            return Math.min(one.length, two.length);
        }
    })
}
```
