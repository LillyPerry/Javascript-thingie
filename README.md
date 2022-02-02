function person(firstname, lastname) {
 //private variables
 var secret = 'tacosarelove';

this.firstname = firstname; 
 this.lastname = lastname;
 tihs.hasjob = false; 
 
 this.fullname = function() {
   return this.fullname + ' ' + this.lastname; 
   }
   
   this.setFirstName = function(firstname) {
     this.firstname = firstName; 
   }
    
    this.setLastName = function(lastName) {
      this.lastName = firstName; 
   }
     
   this.getSecret = function() {
     return secret; 
   }
 }
