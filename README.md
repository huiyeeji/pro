function unique(arr){
    var newArr = [];
    for(var i = 0; i < arr.length; i++){
        if(newArr.indexOf(arr[i]) == -1){
            newArr.push(arr[i])
        }
    }
    return newArr;
}       

var arr = [1,2,2,3,4,4,5,1,3];
var newArr = unique(arr);
console.log(newArr);
