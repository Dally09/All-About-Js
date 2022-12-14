# All-About-Js
Js is one of the core technologies of the World Wide Web, alongside HTML and CSS. 

# Chapter1
i)Using;
    <script>
    function myFunction() {
        document.getElementById.style.display = "block";
    }
    </script>

    or

    <script>
    function myFunction() {
        var x = document.getElementById("myLinks");
        if (x.style.display === "block") {
        x.style.display = "none";
        } else {
        x.style.display = "block";
        }
    }
    </script>

    -shows hidden html components.

ii)Using buttons to call scripts;
    <button type="button" onclick="myFunction()">

iii)Calling external scripts;
    <script src="myScript.js"></script>

    or

    <script src="https://www.w3schools.com/js/myScript.js"></script>

    or

    <script src="/js/myScript.js"></script>

    -Speeds up load page and its also easy to read and maintain.

iv)Scripts can "display" data in different ways:

    -Writing into an HTML element, using innerHTML.
    eg.
        <script>
            document.getElementById("demo").innerHTML = 5 + 6;
        </script>

    -Writing into the HTML output using document.write().
    eg.
        <script>
            document.write(5 + 6);
        </script>

        or

        <button type="button" onclick="document.write(5 + 6)">Try it</button>

    -Writing into an alert box, using window.alert().
    eg.
        <script>
            window.alert(5 + 6);
        </script>

        or

        <script>
            alert(5 + 6);
        </script>

    -Writing into the browser console, using console.log().
    eg.
        <script>
            console.log(5 + 6);
        </script>

v) We can use js to print things on the web although it does not have any print object or print methods.
    .ie
        <button onclick="window.print()">Print this page</button>
        
# Chapter2
1) Js Statements.
    -A JavaScript program is a list of programming statements (JavaScript code).
    -This statement tells the browser to write "Hello Dolly." inside an HTML element with id="demo":
        eg. 
            <script>
                document.getElementById("demo").innerHTML = "Hello Dolly.";
            </script>
    i) Js Keywords
    -var        :Declares a variable
    -let	    :Declares a block variable
    -const	    :Declares a block constant
    -if	        :Marks a block of statements to be executed on a condition
    -switch	    :Marks a block of statements to be executed in different cases
    -for	    :Marks a block of statements to be executed in a loop
    -function	:Declares a function
    -return	    :Exits a function
    -try	    :Implements error handling to a block of statements