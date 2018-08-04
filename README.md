  React Seed Application
       A React Seed project with Sass preprocessing, Flow Integration, commit-preprocessing, Travis ci pipleling and surge integration out-of-the-box.


  Travis pipeline,steps in React-seed-with-Travis branch 


  #yarn install 
      Install all dependencies

  #yarn start
      Start application in development mode

  #yarn build
      Generate solution build for release

   
  #yarn global add serve
      A local Http server to rapidly run the build files

  #serve -s build
      Start the local dev server and open the file in build folder

  #yarn add husky lint-staged prettier
      Formatting Code Automatically when before code commit.Commit pre-processing added scripts in package.json

  #saas precompiler
      Creaitng Saas file, these will be compiles to css and used. they are already added to git ignore.Compile process is automated.

  #integration of flow
      A static type checker.
       run ~npm run flow (or yarn flow)

  #react-router-dom installed
     
  #Environment file
    .env - Common file used in both staging and development
    .env.development- file used only in development mode
    .evv.production- file used only in production

  #added enzyme
     Assertion library

  #source map explorer
    Source map explorer analyzes JavaScript bundles using the source maps
    npm run build
    npm run analyze