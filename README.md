```javascript
const this: AboutMe = {
  name: 'Yuriy',  
  experienceInMonth: {
    commercial: 0,
    nonCommercial: 17,
  },
  technologies: {
    Javascript: {
      vanilla: 'advanced',
      react: 'medium',
      other: ['react-router', 'redux', 'ant-design'],
    },
    Typescript: 'beginner',
    Markup: ['HTML5', 'CSS3', 'Adaptive', 'Responsive', 'a11y', 'scss', 'gulp'],
  },  
}

type AboutMe = {
  name: string,
  age: number,
  experienceInMonth: {
    commercial: number,
    nonCommercial: number,
  },
  technologies: {
    Javascript: {
      vanilla: string,
      react: string,
      other: string[],
    },
    Typescript: string,
    Markup: string[],
  },  
}
```
