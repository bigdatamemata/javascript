# javascript
- para definir métodos en una clase es con prototype.
- la definición de la clase es con function:
  function Player(n,s,r){
    this.name =n;
    this.score = s;
    this.rank = r;
  }
  
  Player.prototype.logInfo = function(){
  console.log("I am:", this name);
  
  
  
