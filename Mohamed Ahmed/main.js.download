let promp = prompt("What is Your Name ?");
document.getElementById("name").innerHTML= `Hello ${promp}`
function age(){
    var d1 = document.getElementById("data").value;
    var m1 = document.getElementById("month").value;
    var y1 = document.getElementById("year").value;

    var data = new Date() ;
    var d2 = data.getDate();
    var m2 = 1 + data.getMonth();
    var y2 = data.getFullYear();
    var month = [31, 28, 31, 30, 31, 30, 31, 30, 31, 30]

    if(d1 > d2){
        d2 = d2 + month[ m2 + 2];
        m2 = m2 - 1;
    }
    if(m1 > m2){
        m2 = m2 + 12;
        y2 = y2 - 1;
    }
    var d = d2 - d1;
    var m = m2 - m1;
    var y = y2 - y1;
    document.getElementById("age").innerHTML = ` your age is ${y} years ${m} months ${d} days`;
}