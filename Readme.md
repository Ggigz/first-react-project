# Important thing to note when setting up the webpack

# depedences to install 
 npm install --save webpack
 npm install --save-dev webpack
 npm install --save-dev webpack-dev-server
 npm install --save-dev babel-loader
 npm install --save-dev babel-preset-es2015
 npm install --save-dev babel-preset-react
 npm install --save-dev babel-preset-stage-2

#expected errors
 -error cannot find module 'babel-core'
 -Solution `npm install --save-dev babel-core babel-loader@7`
 -N.B,`babel-loader@7` will change the `babel-loader` version to version7 