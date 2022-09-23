# Login2xplore_Employee_Form

## Form for Employee - Employee ID(primary key),Employee Name, Basic Salary, HRA, DA, Deductions

### Provides easy navigation to the employee form:

Has following buttons on the employee form page.

1.The first row is of ‘Control’ buttons.

2.The second row is of ‘Navigation’ buttons: [New] [Save] [Edit] [Change] [Reset] [First] [Prev] [Next] [Last]

![Screenshot (55)](https://user-images.githubusercontent.com/112549956/191912020-ed256270-5d47-4280-9cd6-640601469244.png)


### Whenever the navigation buttons are enabled (except for when [Save] and [Change] are enabled) the behavior of navigation will be as follows:

1.Clicking on [First] will display first record and will enable [Next] and [Last] and disable [Prev] and [First]

2.Clicking on [Last] should be opposite to the above step.

3.Clicking on [Prev] will display the previous record and should enable all four navigation buttons. If it's the first record should disable [First] and [Prev].

4.Clicking on [Next] will behave just the reverse of the above step.

![Screenshot (56)](https://user-images.githubusercontent.com/112549956/191912598-2e2601d1-32c3-437e-a26a-83dce2f8341c.png)


### If [Save] and [Change] are enabled the navigation buttons must all be disabled.

1.On page load, displays last record and on [Reset] click current record is displayed(all form fields disabled)

2.Clicking on [New] will enable all form fields and move the cursor to the first field i.e. empID. It will also enable [Save] and [Reset] buttons.

3.Clicking on [Reset] will go back to step-1.

4.Clicking on [Save] will save the new record after all validations and go back to step-1.

5.Click on [Edit] will enable all form fields except empID and move the cursor to empName for editing.

6.Clicking on [Reset] will go back to step-1.

7.Clicking on [Change] will update the current record after all validations and go back to step-

![Screenshot (55)](https://user-images.githubusercontent.com/112549956/191912734-4b1ca74e-40b2-4ff6-94bc-39ce2ac7b6f2.png)
