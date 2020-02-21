# Angular FireDash
Featherweight administrative dashboard starter project using **Angular 9**, **Firestore** and **Material Design**.  

Live Demo: https://www.angular-firedash.netlify.com

![](https://firebasestorage.googleapis.com/v0/b/angular-material-firestarter.appspot.com/o/demo.PNG?alt=media&token=2a379f4d-e73d-40dc-ac39-00d8792a49af)

## Getting started

* Check out the [live demo][demo].
* Read through [the documentation][docs].
* Review the [wiki] for links to tutorials, articles and sample projects.
* Become a [Contributor][contributing]!
* Join the [Slack Team][slack]!


## Need help?

### Slack Channel


Please use [StackOverflow][stackoverflow] for help requests and how-to questions.

Please open GitHub issues for bugs and enhancements only, not general help requests.
Please search previous issues (and Google and StackOverflow) before creating a new issue.

## Want to contribute?

If you want to contribute through code or documentation, the [Contributing
guide is the best place to start][contributing]. If you have questions, feel free
to ask.


## Dependencies

We try not to reinvent the wheel, so Active Admin is built with other open source projects:

Tool / Version        | Description
--------------------- | -----------
NodeJS                | Ruby -> HTML, just like that.
NPM                   | Powerful, extensible user authentication
Angular CLI           | A Rails form builder plugin with semantically rich and accessible markup
AngularFire v5.5      | Simplifies controllers with pre-built RESTful controller actions
Material Design       | Elegant pagination for any sort of collection

## Features
- [x] Angular 9
- [x] Google Firebase / Firestore / Cloud Functions
- [x] Material Design + Flex Layout
- [x] Google Charts

- What does this project do?
- Why is this project useful?
- How do I get started?
- Where can I get more help, if I need it?

## Usage
1. Clone from Git and install dependencies
        git clone https://github.com/max-geller/angular-9-material-firestarter-firedash.git firestarter
        cd firestarter
        npm install

2. Create a project at https://firebase.google.com/ and grab your web config.  

3. Add the config to your Angular environment in 'src/environments/' and update the environment.prod.ts and environment.ts files.

        export const environment = {
          production: false,
          firebase: {
            apiKey: 'APIKEY',
            authDomain: 'DEV-APP.firebaseapp.com',
            databaseURL: 'https://DEV-APP.firebaseio.com',
            projectId: 'DEV-APP',
            storageBucket: 'DEV-APP.appspot.com',
            messagingSenderId: '...',
            appId: '...',
          }
        };
4. Serve project and navigate to localhost:4200
        ng serve -o



## To Do
- [ ] 'User Registration' Workflow
- [ ] 'Reset Password' Workflow
- [ ] 'Email Verification' Workflow
- [ ] Implement AuthGuard
- [ ] Dynamic Notification/Icon Badge Service
- [ ] Messaging Service
- [ ] SMS Push Notifications


[demo]: http://angular-firedash.netlify.com
[docs]: http://activeadmin.info/0-installation.html
[wiki]: https://github.com/max-geller/Angular-Firedash/wiki
[stackoverflow]: http://stackoverflow.com/questions/tagged/angular-firedash
[slack]: https://angularfiredash.slack.com
[contributing]: CONTRIBUTING.md
