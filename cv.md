# Evgeniy Negura
## Contancts:
   + **E-mail:** evgenijnegura@gmail.com
   + **Phone:** +375336075799
  
***** 

  
## Summary
I want to gain as much knowledge as possible, to acquire skills in writing laconic algorithms. The frontend hobby has arisen recently. *My purpose is to deeply learn JavaScript and find a job as a frontend developer.* Further deeper immersion in development. Right now I am design developer of packaging materials in my current job. I have extensive experience in communicating with customers and approving organizations - useful skills when applying for a company, I believe this will help to become a teamlead in the future. **I am ready to study a lot, my desire to be in demand as a developer is very great.**


## Skills
+ **In studing:** HTML, CSS, SCSS, JavaScript, BEM, Git.
+ **Mastered:** VSCode, Figma, Adobe Photoshop, Adobe Illustrator, Adobe Indesign, CorelDraw etc.

## Code example:
```sh
  const loadText = document.querySelector('.loading-text');  
  const bg = document.querySelector('.bg');  
  let load = 0;
  let int = setInterval(blurring, 30);
  function blurring() {
     load++;
      if (load > 99) {
          clearInterval(int);
      }
      loadText.innerText = `${load}%`;
      loadText.style.opacity = scale(load, 0, 100, 1, 0);
      bg.style.filter = `blur(${scale(load, 0, 100, 30, 0)}px)`;
  }
  const scale = (num, in_min, in_max, out_min, out_max) => {
      return (num - in_min) * (out_max - out_min) / (in_max - in_min) + out_min;
  };
```

## Education
- Secondary special education. 
- Online course “JavaScript 2021 - Complete Zero-to-Pro Guide”. (Udemy, Vladilen Minin).
- Online marathon “7 days HTML, CSS & JS”

## English level

My English Level is Pre-intermediate A1.
