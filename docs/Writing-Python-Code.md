# Writing Python Code in Dis-Code

Here, you will learn how to run python code in the Dis-Code app.

## Writing it.

To code python on Dis-Code, do you see a black Textarea next to the message area. That is actually the area where you write code(_It has even syntax highlighting!!_)Now let's test it out shall we?

ok let's make a simple program where the program will ask a number and display the result.
For that we can write something like this

```python
number = input("Enter a number please")
print(number)
```
After that click the run button under the code area.
you will get an alert which has a textbox. which where you would enter the input data. like the below image.

![Test-Input](.\images\test-input.png)

After you entered that you should get an alert like this.

![Success-Banner](.\images\Success.png)

Then check the developer console to see the output

> Quick Side Bar: To access the Dev-Console you either press Ctrl+Shift+j or go to More Tools -> Developer Console on chrome.

The output should be Like this.

![Output on Dev-Console](.\images\Output.png)

so that's pretty much it.

> Extra: You have the entire standard library with you in this. so you can use from random to requests in the script.

## How this works??

Now you maybe wondering. _HOW THE HECK IS THIS WORKING IN THE BROWSER!!_
well the answer comes in a thing called [Pyodide](https://pyodide.org/en/stable/).
It's a JS library of which will run python code using WASM(which is Web Assembly BTW.)

from it's page it says that,

>Pyodide is a Python distribution for the browser and Node.js based on WebAssembly.

so there you have it folks!

so now Have a good day hacking, Thanks for reading!

~ Author: [Sas2k](https://github.com/Sas2k)