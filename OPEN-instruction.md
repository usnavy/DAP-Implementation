# Implementing DAP Code on OPEN

## DAP Code
The Google Tag Management (GTM) code below should only be used for OPEN sites. In some cases a site is hosted in the OPEN enviroment but uses a differnt (GTM) code. To ensure you are using the correct code refer to the [GTM table](https://github.com/usnavy/DAP-Implementation/blob/master/GTM-table.md) to see if your web site falls under another code implementation. 

```javascript
<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-54DBGZP');</script>
<!-- End Google Tag Manager -->

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src=https://www.googletagmanager.com/ns.html?id=GTM-54DBGZP height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->
```

### NOTE about Google Tag Manager
If your Command wants to manage a GTM workspace, please request access to the U.S. Navy's GTM account. 

## Using SharePoint Designer
*If you do not have SharePoint Designer, please reach out to your webmaster lead, who can insert the scripts using an enhanced text editor.*
  
  1. Ensure you are signed in to the author side on Internet Explorer. Then click the SharePoint Designer icon on your desktop to open the application.
  
  2. Next, open your main domain site.
  
  Note: If you have subdomains, the **"Page Layouts"** that you will be editing is all under your domain site:
  
  ![alt text](https://github.com/Photomate78/DAP-Implementation/blob/master/images/image-1.PNG "Logo Title Text 1")
  
  
  3. In order to determine your page layout, please follow steps a. through d., otherwise skip to step 4.
     
     a. Click **"Site Actions"** on the Ribbon bar
     
      ![alt text](https://github.com/Photomate78/DAP-Implementation/blob/master/images/image-2.PNG "Logo Title Text 2")
     
     b. Click **"View All Site Content"** on the drop-down menu
     
      ![alt text](https://github.com/Photomate78/DAP-Implementation/blob/master/images/image-3.PNG "Logo Title Text 3")
     
     c. Under **"Document Libraries,"** click **"Pages"**
     
     ![alt text](https://github.com/Photomate78/DAP-Implementation/blob/master/images/image-4.PNG "Logo Title Text 4")
     
     d. On this screen, you will see the list of all of your pages, and on the far right is a column named **"Page Layouts"** that will let you know what **"Page Layout"** your pages are using.
     
     ![alt text](https://github.com/Photomate78/DAP-Implementation/blob/master/images/image-5.PNG "Logo Title Text 5")
  
  4. On the left side navigation menu, under **"Site Objects,"** click **"Page Layouts."** Once you click on link, a window will open to the right. Please click on the page layout you want to add the code to.
  
  ![alt text](https://github.com/Photomate78/DAP-Implementation/blob/master/images/image-6.PNG "Logo Title Text 6")
  
  5. When you click on the page layouts link, a new window will open. Under the customization section, please click the hyperlink that says **"Edit File."** Then, a dialogue box will open - click **"Yes"** to check out the file. 
  
  ![alt text](https://github.com/Photomate78/DAP-Implementation/blob/master/images/image-7.PNG "Logo Title Text 7")
  
  6. When you open the file, you will see views for "Design," "Split," and "Code." This is similar to other web design programs, such as Adobe Dreamweaver. In the **"Code View,"** insert the **"Google Tag Manager"** script after the C# SharePoint language at the very top, so it as high on the page as possible. 
  
  ![alt text](https://github.com/Photomate78/DAP-Implementation/blob/master/images/image-8.PNG "Logo Title Text 8")
  
  7. In the same page layout, find the first "article body" div class and insert the **"No Script" Google Tag Manager** in this area.
  
  ![alt text](https://github.com/Photomate78/DAP-Implementation/blob/master/images/image-7.PNG "Logo Title Text 9")
  
  8. Once complete, go to the top of the file, where you see the **tab** and right click to **"Save As."** and then click again and click **"Close"** to shut down the file. 
  
  9. After the file has closed, click back on **"Page Layouts,"** in the left side navigation menu, and make sure that you **"Check In"** the file or changes will not be published. Click **"OK"** in the dialogue box. 
  
 10. When the scripts have been successfully implemented, let the DAP POC know. The DAP POC will ensure that the tag is firing and reporting statistics.  
  
