# Stock Market Simulator


How to use the program?

The program starts off by asking the user to enter their name. Then, the program displays a welcome message to the user as well as a table of 
stock names and values. Just when the program runs, the user is prompted to enter the number of companies they want to invest in out of the 6. 
This input should be a single digit between 1 and 6 inclusive. Next, the program asks the user to enter the digits of the companies they want 
to invest in (each company recieves its own digit designation, which will be explained in the terminal window itself). These inputs should also 
be single digits between 1 and 6 inclusive. The user will then also enter the number of shares they want to buy at each company. Validations in 
this case will depend on how many stocks are available at each company, which will be shown on the stocks table in the terminal window. The 
program then asks the user if they wish to simulate Quarter 1. The user needs to enter 0 to continue (entering a different value or number of 
values will cause the program to print an error message and exit). The program then displays what happened during quarter 1 and also displays 
any relevant headline that is pertinent to allow the user to make informed investment decisions for the next quarter. Again, the user will need 
to enter 0 to continue. The Standard Draw window will simulate this entire process in an appealing way simultaneously. For quarter changes, there 
is an animation with pop-out text. For portfolio changes, an appealing table is shown.  

Next, the program outputs any overall stock value changes that occured over quarter 1 and shows how this reflects on the user's portoflio value
and assets value. All this will be shown both on the terminal window and the Standard Draw window. The stocks table (showing stock names and value) 
and the portoflio table (displaying the user's portfolio) will also be shown again at this point, both on the terminal window and the Standard 
Draw window. After this, the program asks the user to enter 0 to mark the beginning of quarter 2 (again, entering a different value or number 
of values will cause the program to print an error message and exit). The animation will be shown on the Standard Draw screen. The program then 
asks the user if they want to invest more in their exisiting companies. If the user wishes to invest more in their existing companies, they enter 
the number and the digits of the companies they want to buy more of, after which they also enter the number of shares they want to buy at each 
company. If the user doesn't wish to do so, they just need to enter 0. Appropriate validations are set in place for these numerical inputs. Then, 
the program asks the user if they want to sell shares that they own. If the user wishes to sell some or all of their shares, they enter the number 
and the digits of the companies they want to sell shares of, after which the user also enters the numer of shares they want to sell. If the user 
doesn't wish to do so, they just need to enter 0. Appropriate validations are set in place for these numerical inputs. The program then asks the 
user if they want to invest in any new companies. The user enters the number and digit designations of the new companies they want to invest in, 
after which the user also enters the number of shares they want to buy at each company. If the user doesn't wish to do so, they just need to enter 
0. Appropriate validations are set in place for these numerical inputs. The program also validates that the user doesn't enter the digit of a 
company they have already invested in. These three actions essentially update the user's portfolio, and thus their portfolio value and cash held.  

This entire process repeats from simulating quarter 2 to the end of quarter 4, after which the program displays the final portfolio value, cash 
held, and total assets value of the user. If the user's assets value is greater than or equal to the initial asset value of $1000, the user wins 
the game. Otherwise, the user loses the game. The result of the game will also be shown as a pop-out animation on the Standard Draw screen. The 
program then ends by asking if the user wishes to sort each company's return to them in descending order. The user needs to enter 1 if they wish 
to see the order and 0 if they don't. Appropriate validations are set in place for this input. The program uses merge sort and recursion to 
accomplish such an efficient sorting. The program then ends. 



Additional comments about the final program:

I have managed to fulfill all the compulsory requirements for the project. Among the optional components, I have included graphics, recursion, 
interactve input from the user, and input from files (for the company logos on Standard Draw). I thought that use of the mouse and sound/audio
wasn't absolutely necessary for my project and that my project looks great with the components it currently has, contrary to what I had thought 
and planned. Furthermore, I initially had planned to include two different classes in my project: one for stock information and one for investor
(user) information. However, I dropped the class for the investor information because I thought that it was making my program unnecessarily complex
and because this game has only one user (investor).    
