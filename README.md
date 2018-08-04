  React Seed Application
       A React Seed project with Sass preprocessing, Flow Integration, commit-preprocessing, Travis ci pipleling and surge integration out-of-the-box.


  Travis pipeline,steps in React-seed-with-Travis branch 


  #yarn install <br />
      -Install all dependencies

  #yarn start <br />
      -Start application in development mode

  #yarn build <br />
      -Generate solution build for release

   
  #yarn global add serve <br />
      -A local Http server to rapidly run the build files

  #serve -s build <br />
      -Start the local dev server and open the file in build folder

  #yarn add husky lint-staged prettier <br />
      -Formatting Code Automatically when before code commit.Commit pre-processing added scripts in package.json

  #saas precompiler <br />
      -Creaitng Saas file, these will be compiles to css and used. they are already added to git ignore.Compile process is automated.

  #integration of flow <br />
      -A static type checker.<br />
       run ~npm run flow (or yarn flow)

  #react-router-dom installed <br />
     
  #Environment file <br />
    .env - Common file used in both staging and development <br />
    .env.development- file used only in development mode <br />
    .evv.production- file used only in production <br />

  #added enzyme <br />
     -Assertion library

  #source map explorer <br />
    -Source map explorer analyzes JavaScript bundles using the source maps <br />
    npm run build <br />
    npm run analyze <br />