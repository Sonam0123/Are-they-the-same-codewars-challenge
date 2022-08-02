# are-they-the-same-codewars-challenge

<h2>My solution</h2>
<br>


  for(i = 0; i < array1.length; i++){
    for(j = 0; j < array2.length; j++){
      const squares = array2.map(e => Math.sqrt(e));
      if(squares.includes(Math.sqrt(array1[i]))){
        return true
    }else{
      return false
      }
    }
  }

