// $Id: README.txt,v 1.1.2.1 2010/12/30 07:58:00 jmfederico Exp $

UC NAB Transact

1. Introduction
2. Installation
3. NAB Transact Bank Response Codes

================================================================================

1. Introduction

UC NAB Transact is a payment gateway module for Ubercart that currently allows
you to process credit card payments on your site using NAB Transact's XML API
payment service. In order to use this module, you must have an account with NAB
Transact and confirm that you are enabled for XML API use.

================================================================================

2. Installation

To use this module, use the following steps:

  1. Upload this module to your site and enable it.
  2. Browse to the Payment gateways settings form and enter your account
     information for NAB Transact.
  3. Browse to the Payment methods form and make sure your credit card settings
     have been configured properly and NAB Transact is set as the default credit
     card gateway.
  4. Run a few test transactions through an order view page to get a feel for
     the module.
  5. Try it through checkout to make sure it processes there as well.
  6. When you're read you to go, change the transaction mode in the gateway
     settings to Live.

================================================================================

3. NAB Transact Bank Response Codes

  3.1 Approved

    00	Approved
    08	Approved
    11	Approved (not used)
    16	Approved (not used)

  3.1 Declined

    1	Refer to Card Issuer
    2	Refer to Issuer’s Special Conditions
    3	Invalid Merchant
    4	Pick Up Card
    5	Do Not Honour
    6	Error
    7	Pick Up Card, Special Conditions
    9	Request in Progress
    10	Partial Amount Approved
    12	Invalid Transaction
    13	Invalid Amount
    14	Invalid Card Number
    15	No Such Issuer
    17	Customer Cancellation
    18	Customer Dispute
    19	Re-enter Transaction
    20	Invalid Response
    21	No Action Taken
    22	Suspected Malfunction
    23	Unacceptable Transaction Fee
    24	File Update not Supported by Receiver
    25	Unable to Locate Record on File
    26	Duplicate File Update Record
    27	File Update Field Edit Error
    28	File Update File Locked Out
    29	File Update not Successful
    30	Format Error
    31	Bank not Supported by Switch
    32	Completed Partially
    33	Expired Card—Pick Up
    34	Suspected Fraud—Pick Up
    35	Contact Acquirer—Pick Up
    36	Restricted Card—Pick Up
    37	Call Acquirer Security—Pick Up
    38	Allowable PIN Tries Exceeded
    39	No CREDIT Account
    40	Requested Function not Supported
    41	Lost Card—Pick Up
    42	No Universal Amount
    43	Stolen Card—Pick Up
    44	No Investment Account
    51	Insufficient Funds
    52	No Cheque Account
    53	No Savings Account
    54	Expired Card
    55	Incorrect PIN
    56	No Card Record
    57	Trans. not Permitted to Cardholder
    58	Transaction not Permitted to Terminal
    59	Suspected Fraud
    60	Card Acceptor Contact Acquirer
    61	Exceeds Withdrawal Amount Limits
    62	Restricted Card
    63	Security Violation
    64	Original Amount Incorrect
    65	Exceeds Withdrawal Frequency Limit
    66	Card Acceptor Call Acquirer Security
    67	Hard Capture—Pick Up Card at ATM
    68	Response Received Too Late
    75	Allowable PIN Tries Exceeded
    86	ATM Malfunction
    87	No Envelope Inserted
    88	Unable to Dispense
    89	Administration Error
    90	Cut-off in Progress
    91	Issuer or Switch is Inoperative
    92	Financial Institution not Found
    93	Trans Cannot be Completed
    94	Duplicate Transmission
    95	Reconcile Error
    96	System Malfunction
    97	Reconciliation Totals Reset
    98	MAC Error
    99	Reserved for National Use