# Bankist

Simplified version of bankist app

There are two accounts with login/pin.
Login are two first letter from first and last name.

1. dd/1111
2. jd/2222

UI will pop up after someone is logged in.

Transfer can be done to only existing accounts. If you switch account without refreshing the page it can be seen on other accounts.
Also current amount can be seen.

Loan request can be done only if you have deposit which is 10% of loan which you would like to receive.

Closing account is only possible if u input proper credentials.

Every account(object) has it's own interest rate.

Sort button sorts in ascending order. Second click turns it back to previous state. And so on and so forth.

Every used has his locale(language package) set individually. Changes can be seen when switching accounts in currency and date tabs.

Timers were added. For example loan is not granted immediately, only after 3s. 
Inactivity timer. User is logged out if timer reaches 0. There are 2 activities: Loan and transfer.
