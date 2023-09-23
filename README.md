# Shopify GitHub integration for themes

> The Shopify GitHub integration lets you connect a GitHub account or organization with a Shopify login. This connection helps you to make and track changes to online store theme code. It also helps you to collaborate with other developers and share progress in real time.

1. Refer to the link below to install Shopify CLI 3.0 and all other dependencies for Shopify GitHub integration.
https://shopify.dev/docs/themes/tools/cli/install

    *Once you have installed the Shopify CLI 3.0 and all other dependencies. Create a local directory in your system.*
   

3. Go to the local directory and change the path to **"cmd"** and hit enter.

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/1.png">

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/2.png">

  
    The command prompt window opens on hitting enter

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/3.png">
  

4. Enter the command `shopify version` to confirm Shopify CLI installation.

5. Enter the following commands for authentication.
  ```
  shopify theme info
  shopify theme dev --store=bellavita1.myshopify.com
  ```


6. Enter any of the following commands to pull the Shopify theme code to the local directory.
  ```
  shopify theme pull
  shopify theme pull --store=bellavita1.myshopify.com
  shopify theme pull --store=bellavita1.myshopify.com --theme=122274054190
  ```

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/4.png">


  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/5.png">


  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/6.png">


7. Now, log into your GitHub account and create a new ***private repository*** for the master branch.

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/7.png">

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/8.png">
  

8. Initialize the Git to the local directory and push the theme code from the local directory to the main branch of the GitHub repository using the following commands.
  ```
  git init
  git add .
  git commit -m "Initial Upload"
  git branch -M main
  git remote add origin https://github.com/simarjeet-dev/Bella-Vita-3.0-Master-Branch.git
  git push -u origin main
  ```


9. Refresh the GitHub repository and check the code directories.

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/9.png">
  

10. Give access to the code repository on the Shopify application for the integration using the following steps.

  `Go to GitHub account settings > Applications > Shopify > Configure > Repository access > Select repository > Save`

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/10.png">

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/11.png">


11. Now, go to the Shopify dashboard and connect the Shopify theme with the GitHub repository.

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/12.png">

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/13.png">

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/14.png">

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/15.png">


***The integration has been completed.***

  <img width="auto" src="https://cdn.shopify.com/s/files/1/0575/3228/5065/files/16.png">
