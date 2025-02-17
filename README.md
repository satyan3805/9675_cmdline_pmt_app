# 9675_cmdline_pmt_app

this repository is for commandline payments application.
## Requirements: Create design (class diagram and schema design) and write working code for a command-line payment application that supports the following use cases.

### This will allow users to send money to multiple recipients in a single transaction, which could be useful in scenarios like splitting bills or group donations.
>**CreateGroupTransaction** _[from_user_id] [amount_per_user] [user_phone_numbers]

### Displays the details of a group payment transaction, including the list of recipients and amounts sent.
>*ViewGroupTransaction* [transaction_id]

### Allow users to request payments from others. This can be useful for scenarios like splitting bills or collecting money for a group activity. The person who receives the request can approve or reject it.
>**RequestPayment** [from_user_id] [to_user_id] [amount]

### Allow users to set a reminder for upcoming payments or bills. For example, they can set reminders for monthly rent, loan payments, etc., so they don't forget to pay.
>**SetPaymentReminder** [user_id] [payment_amount] [due_date]
