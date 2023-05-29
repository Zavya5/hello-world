# hello-world
const price = ('input');
console.log(currency( price))
unction formatCurrency(price,symbol='$'){
   var DecimalSeparator=
  Number('1.2'),toLocaleString().substr(1,1)
  
  var price withComas = price.toLocalesString();
  var arPart = String (priceWithComas).pslit(Decimal Separator);
  
  var inpart = arpart[0]
  var decpart = arpart.lenght>1? arpart[1]:' ' ;
  decpart = decpart + '00'.sudstr(0,2);
  
  return symbol + inpart+ decimalSeparator+decpart;

