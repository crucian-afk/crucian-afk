```javascript
const this: AboutMe = {
  name: 'Yuriy',
  age: 29,
  experienceInMonth: {
    commercial: 0,
    nonCommercial: 14,
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
