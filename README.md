# About The project.
This project is a web-based application that reads RSS feeds. It uses [Jasmine](http://jasmine.github.io/) for testing.

#
##  Testing  scenario
Inside the jasmine  ```feedreader.js```  i have written script that tested the app functionality and ensure that everything working well without bugs or errors.

#
## Run.
First you need to clone the app in to your local machine.

Open ```index.html``` in your browser.

# About Testing script.
It's include Suites which is a group of related specs, each suite test and expect certain scenario in the application.

## Example.

```
    it('Check  hidden by default', () => {
            const body = document.querySelector('body');
            expect(body.classList.contains('menu-hidden')).toBeTruthy();
    });
```
This function ensures the menu element is hidden by default.

And so on and so fourth with each case in the app.