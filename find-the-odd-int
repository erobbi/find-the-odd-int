function findOdd(A) {
  let unique = A.filter( (e,i) => A.indexOf(e) === i );
  for ( let i = 0; i < unique.length; i++ ) {
    if ( A.filter( e => e === unique[i]).length % 2 === 1 ) {
      return unique[i]
    }
  }
}
