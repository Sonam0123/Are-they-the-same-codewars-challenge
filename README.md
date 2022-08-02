# are-they-the-same-codewars-challenge

<h2>My solution</h2>
<br>

`function comp(array1, array2){ <br>
  for(i = 0; i < array1.length; i++){ <br>
    for(j = 0; j < array2.length; j++){ <br>
      const squares = array2.map(e => Math.sqrt(e)); <br>
      if(squares.includes(Math.sqrt(array1[i]))){ <br>
        return true <br>
    }else{ <br>
      return false <br>
    }
  }
}
}`

