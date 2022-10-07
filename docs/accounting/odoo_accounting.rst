.. _odooaccounting:

The Accounting behind CPAbooks
==========================

This page summarises the way CPAbooks deals with typical accounts and transactions.

Double-entry bookkeeping
------------------------
CPAbooks automatically creates all the behind-the-scenes journal entries for each of your accounting transactions: customer invoices, point of sale order, expenses, inventory moves, etc.

CPAbooks uses the rules of double-entry bookkeeping system: all journal entries are automatically balanced (sum of debits = sum of credits).

Accrual and Cash Basis Methods
------------------------------
CPAbooks support both accrual and cash basis reporting. This allows you to report income / expense at the time transactions occur (i.e., accrual basis), or when payment is made or received (i.e., cash basis).

Multi-companies
---------------
CPAbooks allows to manage several companies within the same database. Each company has its own chart of accounts and rules. You can get consolidation reports following your consolidation rules.

Users can access several companies but always work in one company at a time.

Multi-currencies
----------------
Every transaction is recorded in the default currency of the company. For transactions occurring in another currency, CPAbooks stores both the value in the currency of the company and the value in the currency of the transaction. CPAbooks can generate currencies gains and losses after the reconciliation of the journal items.

Currency rates are updated once a day using a yahoo.com online web-service.

International Standards
-----------------------
CPAbooks accounting support more than 50 countries. The CPAbooks core accounting implement accounting standards that is common to all countries and specific modules exists per country for the specificities of the country like the chart of accounts, taxes, or bank interfaces.

In particular, CPAbooks’s core accounting engine supports:

* Anglo-Saxon Accounting (U.S., U.K.,, and other English-speaking countries including Ireland, Canada, Australia, and New Zealand) where cost of good sold are reported when products are sold/delivered.
* European accounting where expenses are accounted at the supplier bill.
* Storno accounting (Italy) where refund invoices have negative credit/debit instead of a reverting the original journal items.
* CPAbooks also have modules to comply with IFRS rules.

Accounts Receivable & Payable
-----------------------------
By default, CPAbooks uses a single account for all account receivable entries and one for all accounts payable entries. You can create separate accounts per customers/suppliers, but you don’t need to.

As transactions are associated to customers or suppliers, you get reports to perform analysis per customer/supplier such as the customer statement, revenues per customers, aged receivable/payables, …

Wide range of financial reports
-------------------------------
In CPAbooks, you can generate financial reports in real time. CPAbooks reports range from basic accounting reports to advanced management reports. CPAbooks’s reports include:

* Performance reports (such as Profit and Loss, Budget Variance)
* Position reports (such as Balance Sheet, Aged Payables, Aged Receivables)
* Cash reports (such as Bank Summary)
* Detail reports (such as Trial Balance and General Ledger)
* Management reports (such as Budgets, Executive Summary)
* CPAbooks’s report engine allows you to customize your own report based on your own formulae.

Import bank feeds automatically
-------------------------------
Bank reconciliation is a process that matches your bank statement lines, as supplied by the bank, to your accounting transactions in the general ledger. CPAbooks makes bank reconciliation easy by frequently importing bank statement lines from your bank directly into your CPAbooks account. This means you can have a daily view of your cashflow without having to log into your online banking or wait for your paper bank statements.

CPAbooks speeds up bank reconciliation by matching most of your imported bank statement lines to your accounting transactions. CPAbooks also remembers how you’ve treated other bank statement lines and provides suggested general ledger transactions.

Calculates the tax you owe your tax authority
---------------------------------------------
CPAbooks totals all your accounting transactions for your tax period and uses these totals to calculate your tax obligation. You can then check your sales tax by running CPAbooks’s Tax Report.

Inventory Valuation
-------------------
CPAbooks support both periodic (manual) and perpetual (automated) inventory valuations. The available methods are standard price, average price, LIFO (for countries allowing it) and FIFO.

Easy retained earnings
----------------------
Retained earnings is the portion of income retained by your business. CPAbooks automatically calculates your current year earnings in real time so no year-end journal or rollover is required. This is calculated by reporting the profit and loss balance to your balance sheet report automatically.
