# historyStore
Work as a wrapper to Browser/Phone back functionality.  Works only on HTML5 Browser. Uses html5 history/state api[pop,push]. 

Example: 
 -->> Url of page is http://www.example.com.
 
 --> call this line in javascript 
 
      historyStoreObj.push(function(){console.log("Back to homepage");},"page1");
      
 -->> Url of page becomes http://www.example.com/page1
 
 
--> User click back or run history.go(-1)


--> Url of page becomes http://www.example.com and console will output "Back to homepage" 


