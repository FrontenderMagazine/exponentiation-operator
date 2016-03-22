The exponentiation operator (`**`) is an ECMAScript proposal by Rick Waldron. It
is at stage 4 (finished) and part of[ECMAScript 2016][1].

 
`**` is an infix operator for exponentiation:

    x ** y
    

is produces the same result as

    Math.pow(x, y)
    

Examples:

    let squared = 3 ** 2; // 9
        
        let num = 3;
        num **= 2;
        console.log(num); // 9
    

Further reading:

*   [Exponentiation Operator][2] (Rick Waldron)

 [1]: http://www.2ality.com/2016/01/ecmascript-2016.html
 [2]: https://github.com/rwaldron/exponentiation-operator