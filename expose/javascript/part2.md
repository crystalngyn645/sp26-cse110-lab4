# Part 2

1. Line 12 will print **3** beacuse `i` was decalred with `var`. Therefore, it will be accessible outside the loop. 
2. Line 13 will print **150**. Since `discountedPrice` was declared with `var`, it is still accessible outside the loop. 
3. Line 14 will print **150**. Since `finalPrice` was declared with `var` it is function scoped. 
4.  The function would return **[50, 100, 150]**. Each price was discounted by 50% (0.5). 
5.  There would be an error at line 12. Since `i` was decalred with `let` inside the loop it cannot be accessed outside the loop. 
6.  There would be an error at line 13. Since `discountedPrice` was decalred with `let` inside the loop, it cannot be accessed outside the loop. 
7.  There would be an error at lien 14. Since `finalPrice` was declared with `let` inside the loop, it cannot be accessed outside the loop. 
8.  The function would return **[50,100, 150]**. 
9.  There will be an error at line 11 because `i` was decalred with `let` inside the loop. 
10. Line 12 will pritn **3** because `length` was decalred outisde teh loop. 
11. The function will return **[50, 100, 150]** 
12. A: student.name <br>
    B: student[ "Grad Year"] <br>
    C: student.greeting() <br>
    D: student["Favorite Teacher"].name <br>
    E: student.courseLoad[0] <br>

13. A: '32'<br>
    '+' with a string results in a strign concatenation <br>
    B: 1<br>
    '-' converts 3 toan int <br>
    C: 3<br>
    null is equivalent to '0' <br>
    D: 3null<br>
    '+' is used for a string concatenation<br>
    E: 4<br>
    true is eqiovalent to 1 <br>
    F: 0<br>
    both false and null converts to 0<br>
    G: 3undefined<br>
    '+' was used for string concatenation<br>
    G: Nan<br>
    undefined converts to NaN<br>

14. A: true<br>
    2 converts to an int <br>
    B: false<br>
    since both are strings, they are compared alphabetically<br>
    C: true<br>
    '==' allows type conversions<br>
    D: false<br>
    '===' compares both value and type <br>
    E: false<br>
    true converts to 1. and 1 is not equivalent to 2
    F: true<br>
    Boolean(2) is true and both sides are booleans <br>

15. The difference between **==** and **===** is that **==** compares values after conversion. In contrast, **===** comapres value and type without conversion. 
    
16. ``` js
    for (let property in statistics) 
    {
        if ( property.startsWith("r") || statistics[ property ] % 2 === 1) 
        {
            console.log(statistics[property]);
        }
    }


17. The result would be **[2, 4, 6]**. This function would call `doSomething` as it loops thorugh **[1,2,3]**. And for each value, it would be multiplied by 2. 
    
18. ```js 
    setInterval(() => 
    {
        let temp = new Date();

        let time = temp.toLocaleTimeString();

        console.log(time);
    }, 1000);

19. The output is: 1, 4, 3, 2