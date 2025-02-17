# 9675_cmdline_pmt_app

this repository is for commandline payments application.
## Requirements: Create design (class diagram and schema design) and write working code for a command-line payment application that supports the following use cases.

### Filter Transaction History: Allow users to filter their transaction history by date range, transaction type, or status (completed, pending, refunded).
>**FilterTransactions** [user_id] [start_date] [end_date] [transaction_type] [status]

### Enable users to automatically split payments (e.g., dinner bill, shared rent) between multiple people. It calculates each person's share and handles the transfer automatically.
>**SplitPayment** [user_id] [amount] [split_method] [other_user_ids]

### Create a shared wallet where multiple users can pool funds together for a common purpose, such as a group vacation or event.
>**CreateSharedWallet** [user_ids] [wallet_name]

### Allow admins to block or unblock users
>**Blockaccount** [user id]
>**Unblockaccount** [user id]
