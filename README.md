# Bugsloutions
# here is some solution for some bugs that may appear 
# 1- owl.hash.js (Reading Arabic form hashed in firefox browser)
 At line 88 in owl carousal hash plugin there is an issue in arabic hashed url in 
 FIREFOX Browser becouse of it read the arabic as unicode so it can't navigate so the 
 solution for that problem can solved by function decodeURI();

# 2- solution for drupal 7 publish button module
 When you use a view with two modules like ( publish button and weight selector ) you 
 will find some mysteries problem that only one of them will work so the solution is  
 to rewrite one of them in the views->field->choose one the field->choose Rewrite results
 type the html code like <div class="btn form-submit customPublishBtn">[status]</div> and 
 from the class or the id you can rerander the result with javascript 


# feel free to contact me 
# email: hanysayed.a@gmail.com 
# linkedIn : https://www.linkedin.com/in/h4hany


