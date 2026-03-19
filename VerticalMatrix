function VerticalMatrix(str){
    const words = str.split(' ');
    const maxLength = Math.max(...words.map(w=> w.length));
    const matrix = []
    
    for (let i = 0; i < maxLength; i++ ){
        const row = []
        for (let j = 0 ; j < words.length; j++){
            row.push(words[j][i] ?? " ");
        }
        matrix.push(row);
    }
    
    return matrix
}

console.log(VerticalMatrix('hello bobobob'));
