console.log("Hello React");

function Human() {
   this.firstname = "default";
   this.lastname = "default";
   this.getFullname = function(){
         return this.firstname + " " + this.lastname;
   }
}

var person1 = new Human();
console.log(person1);