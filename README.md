# HZpagination.js
A jquery plugin for paginating existing lists!

QUICK INSTALATION

JQuery>Path to Jquery<
<script type="text/javascript" src="Path/to/HZpagination.js"></script>

-------------------------------------------------------------------------------

HTML STRUCTURE
>>
>>

           <ul class="paginationTable">
              <li class="tableItem"> 1 </li>
              <li class="tableItem"> 2 </li>
              <li class="tableItem"> 3 </li>
              <li class="tableItem"> 4 </li>
              <li class="tableItem"> 5 </li>
              <li class="tableItem"> 6 </li>
              <li class="tableItem"> 7 </li>
              <li class="tableItem"> 8 </li>
              <li class="tableItem"> 9 </li>
              <li class="tableItem"> 10 </li>
              <li class="tableItem"> 11 </li>
              <li class="tableItem"> 12 </li>
              <li class="tableItem"> 13 </li>
              <li class="tableItem"> 14 </li>
              <li class="tableItem"> 15 </li>
          </ul>
          
          <div id="pagination-container">
            <p class='paginacaoCursor' id="beforePagination"><</p>
            <p class='paginacaoCursor' id="afterPagination">></p>
          </div>
          

CONFIGURATION: (ON HZpagination.js FILE) 
>>
>>
     var HZperPage = 2, //number of results per page
         
         HZwrapper = 'paginationTable', //wrapper class
     
         HZlines   = 'tableItem', //items class
     
         HZpaginationId ='pagination-container', //id of pagination container
     
         HZpaginationArrowsClass = 'paginacaoCursor', //set the class of pagination arrows
     
         HZpaginationColorDefault =  '#880e4f', //default color for the pagination numbers
     
         HZpaginationColorActive = '#311b92', //color when page is clicked
     
         HZpaginationCustomClass = 'customPagination';  //custom class for styling the pagination (css)
     
-------------------------------------------------------------------------------

HOPE YOU LIKE IT!
