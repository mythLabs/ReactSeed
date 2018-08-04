  React Seed Application   ![alt text](https://travis-ci.org/mythLabs/ReactSeed.svg?branch=React-seed-with-Travis)<br />

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

  #Travis Ci pipe line and Surge deployment
     
     #surge.sh <br /> ![surge.sh](https://surge.sh/) <br />
     npm install --global surge <br />
      Easy deployment for front-end developers <br />
      run #npm run build && surge, it will ask for email/password to create account.

      Step 1. <br />
      #Travis.yml is added for entry level configuration (already added to solution)

      Step 2. <br />
      On local CMD run #surge token, and copy the token.

      Step 3. <br /> ![travis-ci.org](https://travis-ci.org/) <br />
      Login to travisci and add environment variables SURGE_LOGIN,SURGE_TOKEN<br />
      Where SURGE_LOGIN is the email you used when you set Surge up, and  SURGE_TOKEN is the token you copied from the output of surge token

      [view env sample](https://drive.google.com/open?id=1_e-Ds-GqHepSgZxltaUKBQ6_87oEH6uM)

      Step 4. <br />
      On travis find reporitory and enable CD/CI by flicking switch <br />

      Step 5.<br />
      Create commit, push to git and see it getting deployed.<br />

      ![Travis shot 1](https://drive.google.com/open?id=1h8qnqtagvxSMJBQ7op52xTma_-OMXNuN)

      ![Travis shot 1](https://drive.google.com/open?id=1JZLmzSFg9mIky7G-OrVD4DdXJY4-xXVq)

      ![Travis shot 1](https://drive.google.com/open?id=1QYn_cCIi3pWoVjn7HXCU5VKIdYWigqdo)

      ![surge shot](https://drive.google.com/open?id=11q_Y0p1IUhF_cN5igTO8ObQeSUQA2wU8)





      #FYI,
      current configuration starts the automated process when comitted to 'React-seed-with-Travis' branch and deployed to mythLabs.surge.sh. Change as per your requirement.



      