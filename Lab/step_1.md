# How to set up a Private, Remote and Virtual npm Registry

![](image/screenshot1.png)

The simplest way to manage and organize your Node dependencies is with an [npm repository](https://www.jfrog.com/confluence/display/JFROG/npm+Registry). You need reliable, secure, consistent and efficient access to your dependencies that are shared across your team, in a central location. Including a place to set up multiple registries, that work transparently with the npm client.

With the  JFrog Artifactory, you can set up a [free local, remote and virtual npm registry](https://www.jfrog.com/confluence/display/JFROG/Repository+Management) in minutes. This lab  will take you through the step to do that.

## Getting started
Here’s what you’ll need:

   * [npm client installed](https://docs.npmjs.com/getting-started)
   * [JFrog self-hosted subscription or JFrog cloud subscription](https://jfrog.com/start-free/#hosted)
   * [JFrog CLI installed](https://jfrog.com/getcli/)


## Getting started with the Lab environment

Here’s what is provided as part of the lab environment:

1. In the environment provided, an SSH session to the Linux virtual machine and lab guide will get loaded in your browser tab. 
   
   ![](../images/vmandguidelinux.png)

2. To get the lab environment details, you can select the **Environment Details** tab. Additionally, the credentials will also be sent to your email address provided during registration.

   ![](../images/envdetailslinux.png)
   
3. You can also open the Lab Guide on a separate full window by selecting the **Split Window** button on the bottom right corner.

   ![](../images/splitwindowlinux.png)

4. You can **start(1)** or **stop(2)** the Virtual Machine from the **Resources** tab.

   ![](../images/resourcestablinux.png)

5. There is also a **Validation** tab where you will be able to validate and verify if the task as part of the instructions has been completed successfully.
   
   
## Task: Log in to JFrog Portal

1. Let us start by logging into the JFrog Portal. Copy the below link and open in a new tab in your browser.

   <inject key="Fqdn" enableCopy="true" />


1. In the page that loads up, enter the following username, password and click on **Sign in**. 

   * Username: <inject key="JFrog Portal Username"></inject>

   * Password: <inject key="JFrog Portal Password"></inject>

   ![](image/screenshot2.webp)

1. Now, you will be redirected to the JFrog Portal. On the Welcome Popup Window that opens up, click on **Get Started** button.

1. In the REST ADMIN PASSWORD page, update the password as `Password1234!!` in the popup window

   ```
   Password1234!!
   ```
  > Note : It is mandatory to update the password with the above value itself to ensure the validation is possible.

Now, you can move on to the next page.
