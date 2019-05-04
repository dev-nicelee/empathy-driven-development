
```
 ___        __       ___              __   __          ___         
|__   |\/| |__)  /\   |  |__| \ /    |  \ |__) | \  / |__  |\ |    
|___  |  | |    /~~\  |  |  |  |     |__/ |  \ |  \/  |___ | \|    
                                                                   
 __   ___       ___       __   __         ___      ___             
|  \ |__  \  / |__  |    /  \ |__)  |\/| |__  |\ |  |              
|__/ |___  \/  |___ |___ \__/ |     |  | |___ | \|  |              

```

# Empathy Driven Development
https://github.com/marcysutton/empathy-driven-development

## By Marcy Sutton / @marcysutton
Head of Learning, Gatsby




## Outdoor Trip Planner App
The master branch of this repository is intentionally broken for accessibility. For fixes, check out the [fixes](https://github.com/marcysutton/empathy-driven-development/tree/fixes) branch.

### Components
- Collapsible sidebar menu
- Form
- Carousel
- Modal dialog
- Card flip

### How to run the app

Clone the directory and install dependencies:
```
git clone https://github.com/marcysutton/empathy-driven-development && cd empathy-driven-development
npm install
```

Then you can run Gatsby in development or production mode:
```
gatsby develop
```
or:
```
gatsby build && gatsby serve
```
#### Run tests

Run Cypress tests on the command line:
```
npm run test
```





### Who are you designing/building for?

- PEOPLE, who are diverse creatures.
- 15% of the population has some kind of disability. http://www.who.int/disabilities/world_report/2011/report/en/
- Don’t leave people behind.







### Don't reinvent the wheel

- ARIA Authoring Practices https://www.w3.org/TR/wai-aria-practices-1.1/
- Accessibility: the Beginners Guide https://www.deque.com/accessibility-beginners-guide/
- Deque University https://dequeuniversity.com
- Egghead.io A11y course https://egghead.io/courses/start-building-accessible-web-applications-today
- Udacity Course https://www.udacity.com/course/web-accessibility--ud891
- Notes on Client-Rendered Accessibility https://www.smashingmagazine.com/2015/05/client-rendered-accessibility/
- Accessibility Tips in Single Page Applications https://www.deque.com/blog/accessibility-tips-in-single-page-applications/
- aXe Accessibility Testing Tools https://deque.com/axe
- Writing automated tests for accessibility https://www.24a11y.com/2017/writing-automated-tests-accessibility/


 



### Test with real people

- Manual testing: content quality, contrast edge cases, error validation messaging, event handling & interactions
- More on manual testing: https://www.smashingmagazine.com/2018/09/importance-manual-accessibility-testing/
- Usability testing with people with disabilities https://access-works.com




### In this app

- cypress-axe https://www.npmjs.com/package/cypress-axe
- axe-core https://www.npmjs.com/package/axe-core
- Inert polyfill https://github.com/WICG/inert
- What Input https://github.com/ten1seven/what-input
- Focus Trap React https://github.com/davidtheclark/focus-trap-react