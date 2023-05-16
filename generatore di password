Generatore di password

 function generaPassword(lunghezza) {
    var caratteri = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789";
    var password = "";
    for (var i = 0; i < lunghezza; i++) {
      var carattereCasuale = caratteri.charAt(Math.random() * caratteri.length);
      password += carattereCasuale;
    }
    return password;
  }
  
  var lunghezzaPassword = prompt("inserisci la lunghezza della password che vuoi ottenere");
  var passwordGenerata = generaPassword(lunghezzaPassword);
  alert(`La password di ${lunghezzaPassword} caratteri è stata generata ` + passwordGenerata);
