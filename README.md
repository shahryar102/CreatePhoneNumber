# CreatePhoneNumber
function createPhoneNumber(numbers){
  phone='' 
  for(i=0;i<numbers.length;i++){
    phone+=numbers[i]
  }
  output=`(${phone.slice(0,3)}) ${phone.slice(3,6)}-${phone.slice(6,10)}`
  console.log(output)
  return output  
}
createPhoneNumber([5,7,1,8,2,6,9,5,0,7])
