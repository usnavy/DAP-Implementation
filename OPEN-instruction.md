# Implementing DAP Code on OPEN

## OPEN DAP Code
The Google Tag Management (GTM) code below should only be used for OPEN sites. In some cases the site is hosted in the OPEN enviroment but use a differnt (GTM) code. To ensure you are using the correct code refer to the GTM table to see if your command falls under another code implentation.   is created by the BSO your command is assigned. To see a list of the of GTM code see XXXX. In oder to use 

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


## Using SharePoint Designer
*If you do not have SharePoint Designer, please reach out to your webmaster lead, who can insert the scripts using an enhanced text editor.*
  
  1. Ensure you are signed in to the author side on Internet Explorer. Then click the SharePoint Designer icon on your desktop to open the application.
  
  2. Next, open your main domain site
  
  Note: If you have subdomains, the **Page Layouts** that you will be editing is all under your domain site
  
  ![alt text](https://github.com/usnavy/DAP-Implantation/blob/master/images/image-1.PNG "Logo Title Text 1")
  
  
  3. In order to determine your page layout, please follow steps a. through d., otherwise skip to step 4.
     
     a. Click **Site Actions** on the Ribbon bar
     
     b. Click **View All Site Content** on the drop-down menu
     
     c. Under **Document Libraries**, click **Pages**
     
     d. On this screen, you will see the list of all of your pages, and on the far right is a column named **Page Layouts** that will let you know what **Page Layout** your pages are using.
  
  4. On the left side navigation menu, under **Site Objects**,” click **Page Layouts**.” Once you click on link, a window will open to the right. Please click on the page layout you want to add the code to.
