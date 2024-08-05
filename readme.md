1. What are the variable naming conventions in JavaScript?

Ans. 1.Varibles are case sencitive (myName not equal to myname)

     2.Variables can be single character,multiple character,alphanumeric.

     3.Camel Casing => best prectice(isLoggedIn)

     4.Only two symbols can beused "$","_".

     5.Cannot start with a number.

     6.Cannot use keywords as variables .
     
     7.Variable name cannot have spaces.

2. Create a greeting alert (use => prompt, message, alert)

Ans. let name=prompt("Your name:")

    let message=prompt("Message to be printed")

    alert(`${message} ${name}`)

3. Write some code so that the values of the below variables switch around .
Let a = 5, let b = 8. Switch the value so that a holds the value 8 and the variable b holds the value 5.

Ans. let a = 5

     let b = 8

     let c = b

     b=a

     a=c

     console.log(a)

     console.log(b)

4. ![ScreenShot](./SS-JS%20assinment%2002.png)