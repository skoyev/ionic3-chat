# ionic3-chat

Developed Ionic 3 Chat Mobile Application which has 3 tabs:

- Home - with your latest conversations
- About page - application details, about product
- Contacts - Your contact for communication.

The online demo link is below:

[DEMO](https://stackblitz.com/edit/ionic3-chat-rvon8t)

 ## Running

 In order ot run application - follow the next steps:

 * Clone this repository: `https://github.com/skoyev/ionic3-chat`.
 * Run `npm install` from the project root.
 * If you do not install the ionic CLI (`npm install -g ionic`)
 * Run `ionic serve` in a terminal from the project root.

 ## App Preview

 The application DEMO screenshot:

 <img src="https://github.com/skoyev/ionic3-chat/blob/master/assets/chat.gif" alt="Preview">

 ## File Structure

 Application file structure:
 
 ```
 .
 ├── LICENSE
 ├── README.md
 ├── config.xml
 ├── ionic.config.json
 ├── package.json
 ├── resources
 ├── src
 │   ├── index.html
 │   ├── app
 │   │   ├── app.component.ts
 │   │   ├── app.html
 │   │   ├── app.module.ts
 │   │   ├── app.scss
 │   │   └── main.ts
 │   ├── assets
 │   │   └── mock
 │   │       └── msg-list.json                 * mock json
 │   │   └── icon
 │   │       └── favicon.ico
 │   │   └── to-user.jpg
 │   │   └── user.jpg
 │   ├── components/emoji-picker               * emoji-picker component
 │   │   └── emoji-picker.html
 │   │   └── emoji-picker.module.ts
 │   │   └── emoji-picker.scss
 │   │   └── emoji-picker.ts
 │   ├── providers
 │   │   └── chat-service.ts                  * chat-service
 │   │   └── emoji.ts                         * emoji-provider
 │   ├── pipes
 │   │   └── relative-time.ts                 * relative time pipes
 │   ├── pages
 │   │   ├── home
 │   │   │   ├── home.html        
 │   │   │   ├── home.scss         
 │   │   │   └── home.ts           
 │   │   ├── chat                             * chat page
 │   │   │   ├── chat.html                    * chat template
 │   │   │   ├── chat.scss                    * chat stylesheet
 │   │   │   ├── chat.ts                      * chat code
 │   │   │   └── chat.module.ts               * chat module
 │   │   └── tabs
 │   │       ├── tabs.html
 │   │       └── tabs.ts
 │   ├── service-worker.js
 │   └── theme
 │       └── variables.scss
 ├── tsconfig.json
 └── tslint.json
 ```

 ## Environment
 ```
cli packages:

    @ionic/cli-utils  : 1.12.0
    ionic (Ionic CLI) : 3.13.1

global packages:

    Cordova CLI : 7.0.1

local packages:

    @ionic/app-scripts : 2.1.4
    Cordova Platforms  : android 6.0.0 browser 4.1.0 ios 4.1.1
    Ionic Framework    : ionic-angular 3.7.1

System:

    ios-deploy : 1.9.1
    ios-sim    : 6.0.0
    Node       : v6.9.2
    npm        : 5.4.2
    OS         : macOS Sierra
    Xcode      : Xcode 9.0 Build version 9A235
