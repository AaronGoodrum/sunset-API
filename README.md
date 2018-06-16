# Add firebase to ionic

  export Firebase config info
    app > firebase_config.ts

  install firebase, add a angular fire (warpper) to be use for ionic.
    npm i install firebase angularfire2 --save

  update app.module.ts for import, and firebase config
    AngularFireModule

  updating Login and Register to save and login/save data
    login.ts , login.html
    register.html, register.ts

  firebase Authentication
    app > import from angularfire2/auth

  Need to build a user provider, to help with login, register...
    provider/user/user.ts
      may help with adding user to a database and user look up.