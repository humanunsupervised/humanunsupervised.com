# humanunsupervised.com
Machine learning Jupyter notebooks, tutorials, and code for articles and posts on humanunsupervised.com

### How to style converted Jupyter notebooks
 When converting Jupyter notebooks to HTML, make sure to include the following code snippet just under the first style tag in the head of the HTML documewnt.

 ```
/* 
    NOTE: For every new notebook you convert to HTML, add these style tags
*/
#notebook { padding-top:0px !important; } /* eliminate top gray */
.container { width:100% !important; } /* eliminate side gray */
.end_space { min-height:0px !important; } /* eliminate bottom gray */

#notebook-container { 
    -webkit-box-shadow: 0px 0px 0px 0px rgba(0, 0, 0, 0) !important;
    box-shadow: 0px 0px 0px 0px rgba(0, 0, 0, 0) !important;
}
  ```


#### Github Pages

This site is hosted by Github pages. So all HTML can be accessed at https://humanunsupervised.github.io/humanunsupervised.com

