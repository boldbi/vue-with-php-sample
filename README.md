# BoldBI Embedding Vue with PHP Sample

This project was created using Vue with PHP. The Vue sample acts as the front-end, and the PHP sample acts as the back-end application. This application aims to demonstrate how to render the dashboard available on your Bold BI server.

## Dashboard view

   ![Dashboard view](https://github.com/boldbi/vue-with-php-sample/assets/129487075/717ec161-f4d2-4dca-9fc9-91f6feef7d39)

## Prerequisites

 * [PHP](https://windows.php.net/download/)
 * [Node.js](https://nodejs.org/en/)
 * [Visual Studio Code](https://code.visualstudio.com/download)
 > **NOTE:** Node.js v16.14 to v18.18 are supported.

#### Supported browsers
  
 * Google Chrome, Microsoft Edge, and Mozilla Firefox.

## Configuration

 * Please ensure that you have enabled embed authentication on the `embed settings` page. If it is not currently enabled, please refer to the following image or detailed [instructions](https://help.boldbi.com/site-administration/embed-settings/#get-embed-secret-code) to enable it.

    ![Embed Settings](https://github.com/boldbi/aspnet-core-sample/assets/91586758/b3a81978-9eb4-42b2-92bb-d1e2735ab007)

 * To download the `embedConfig.json` file, please follow this [link](https://help.boldbi.com/site-administration/embed-settings/#get-embed-configuration-file) for reference. Additionally, you can refer to the following image for visual guidance.

    ![Embed Settings Download](https://github.com/boldbi/aspnet-core-sample/assets/91586758/d27d4cfc-6a3e-4c34-975e-f5f22dea6172)
    ![EmbedConfig Properties](https://github.com/boldbi/aspnet-core-sample/assets/91586758/d6ce925a-0d4c-45d2-817e-24d6d59e0d63)

 * Copy the downloaded `embedConfig.json` file and paste it into the designated [location](https://github.com/boldbi/vue-with-php-sample/tree/master/PHP) within the application. Please ensure that you have placed it in the application as shown in the following image.

   ![EmbedConfig image](https://github.com/boldbi/vue-with-php-sample/assets/129487075/057ebe6b-ec0a-49bc-af8e-9121b86f1f34)

## Run a PHP Sample
 
 * Open the PHP sample in visual studio code or any respective IDE.
 
 * Ensure whether embedConfig file is located in following location, `/PHP/embedConfig.json` and run the PHP application using the respective IDE or using visual studio code.

## Run a Sample Using Command Line Interface 
    
  * Open the command line interface and navigate to the specified file [location](https://github.com/boldbi/vue-with-php-sample/PHP) where the project is located.

  * Run the back-end `PHP` sample using the following command `php -S localhost:8080`.
  
  * Open the command line interface and navigate to the specified file [location](https://github.com/boldbi/vue-with-php-sample/Vue) where the project is located.
   
  * To install all dependent packages, use the following command `npm install`.
 
  * Finally, run the application using the following command `npm run serve`. After the application has started, it will display a URL in the `command line interface`, typically something like (e.g., http://localhost:8081). Copy this URL and paste it into your default web browser. 

## Developer IDE

  * [Visual Studio Code](https://code.visualstudio.com/download)

## Run a Sample Using Visual Studio Code

 * Open the PHP sample in **Visual Studio Code**.
 
 * Run the PHP sample, use the below command

   ```bash
      php -S localhost:8080
   ```

 * Open the Vue sample in **Visual Studio Code**.

 * Install all dependent packages, use the below command

   ```bash
      npm install
   ```

 * Run the Vue sample, use the below command

   ```bash
      npm run serve
   ```

 * After the application has started, it will display a URL in the `command line interface`, typically something like (e.g., http://localhost:8081). Copy this URL and paste it into your default web browser.

   ![Dashboard view](https://github.com/boldbi/vue-with-php-sample/assets/129487075/abc18903-e010-492b-88d3-5272daf0e708)
   
> **NOTE:** If the API host is already in use, modify the port number according to your preference and update it in the App.vue file.

## Online demos

Look at the Bold BI Embedding sample to live demo [here](https://samples.boldbi.com/embed).

## Documentation

A complete Bold BI Embedding documentation can be found on [Bold BI Embedding Help](https://help.boldbi.com/embedded-bi/javascript-based/).
