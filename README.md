
1. Build a Cricket Team Building
<
Previous
Next >
App using React
Create an app to simulate a mini-cricket league tournament. Allow users to form their
teams from a list of players. Users should be able to add a new player if they can't find
a suitable one from the list.
Also, they should be able to change a player's role (Batsman, Bowler, Wicket Keeper)
and delete players from the list. Any modifications to the list should be reflected in the
user's team.
A valid team includes 2 batsmen, 2 bowlers, and 1 Wicket Keeper.
The app should display error messages if the team composition doesn't meet these
requirements:
1. 'You do not have the required number of batsmen in your team'
2. 'You do not have the required number of bowlers in your team'
3. 'You do not have the required number of wicketkeepers in your team'
You need to complete the following files:
1. src/Main/Player.js
2. src/Main/Team.js
Important Notes:

Important Notes:
1. Click on the Explorer button on the VS Code Side toolbar to access the project
directory.
2. You do not need to install any third-party library like Axios. It is already installed
in the project.
3. Do not change the function names and method types provided for you in the
Reports.js, just fill them with the correct implementation. These will be imported
and used for your evaluation.
4. Implementation-related specifics are added directly as comments in the
workspace.
5. Ensure that the structure and datatype of the components are followed as
specified in the comments to ensure that the code is evaluated correctly.
6. There is no need to write code to style this application. This is already written.
Testing & Submitting your code:
Step 1: Click on the WeCP Projects Button as shown below and click to Start react
server to start the react server.

2.

2. Build a Sales Dashboard2
<
Previous
Next >
application using React
Project Description:
You are asked to build a Sales Dashboard application using React. In this
application a sale data entity consists of three fields; saleTotal, buyerName
and creditCard. You will find the data in sales.json file in the public folder.
The application requires four dashboard reports. Implement relevant
calculations in src/Main/Reports.js and use them in src/Main/Dashboard.jsx
file.
<
1. Total Sale Report: Implement calculateTotalSales in
src/Main/Reports.js. You must return the sum of all sales.
2. Total Cash Sale Report: Implement calculateTotalCashSale function in
src/Main/Reports.js. You must return the sum of all sales where
creditCard attribute is false.
3. Total Credit Card Sale Report: Implement calculateTotalCreditSale
function in src/Main/Reports.js. You must return the sum of all sales
where creditCard attribute is true.

4. Buyer With Most Sale: Implement calculateBuyerWithMostSale
function in src/Main/Reports.js. You must return the buyer with the
most saleTotal. Thus, if Loron Chaun is the person with the most
purchased items, return Loron Chaun and sum of the purchases he
made. Return format must be {"buyerName": "Loron Chaun",
"saleTotal": 34000}. The sales.json may or may not contain above
names and figures. The above example is just to demonstrate the
expected data format.
Your task is to complete the function defined in the file below:
1. src/Main/Reports.js
2. src/Main/Dashboard.jsx
Notes:
1. It is given that each report has a different implementation, but each
function will require the sale data. Use getSalesData function in
src/Main/Reports.js to fetch sales data. getSalesData function is
already implemented for you.
2. Do not change file names, class names , method declarations.
Tasting 0 Cuknitting your
can you help me to do steps by steps writing the code explain me instead gice me complete codeonce
# react17
2
![image](https://github.com/user-attachments/assets/673f230b-0602-484d-9d51-82d5761b44b2)

..
![image](https://github.com/user-attachments/assets/1518b4b8-45a5-4413-ae8c-799f2ee09ae3)
1
![image](https://github.com/user-attachments/assets/ca410390-cd8f-43a7-9a21-e9461ff19335)
...
![image](https://github.com/user-attachments/assets/0e8483f3-4cd4-4666-b8ff-27a1338f7ce8)
