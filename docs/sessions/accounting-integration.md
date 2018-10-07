# Aim
By the end of this session, you should be able to export accounting information so that it can be imported into QuickBooks or a similar accounting package.

# Objectives
Specific objectives:

* Understand how to configure Financial Accounts, Financial Types, and the Relations between them
* Understand how to manage and export Accounting Batches
* Understand a safe process for initial imports of Accounting Batches into accounting packages like QuickBooks

# Learning Points
You should aim to cover:

* What Financial Account Type, Account Code, and Account Type Code are used for and how they relate to your Chart of Accounts
* What the point of Financial Types is, and how to Assign Financial Accounts to them
* Creating, Editing, Closing and Exporting Accounting Batches
* Typical issues when first importing batches into QuickBooks and similar packages

# Session Plan
The session should last 60 minutes.

## Basic Concepts (10 minutes)
Review the basic ideas of double entry accounting:

* Organizations have a Chart of Accounts in their bookkeeping system, with different accounts classed as Assets, Liabilities, Revenue, Expenses, and so on.
* A donation creates a balancing entry in both revenue account and an asset account like Payment Processor account (or Cash and Cheques for Deposit).
* A pay later transaction creates an entry in both revenue account and accounts receivable (assuming accrual accounting).
* A payment for a pay later transaction creates an entry that reduces accounts receivable and increases an asset account like a Bank Account.

Present how financial types can hide this complexity from staff who are not trained in bookkeeping or accounting:

* The lifecycle of a particular kind of revenue almost always deals with a predetermined set of accounts. 
* Andrew Perry of Community Builders proposed that we use this to simplify use of the system by investing more effort in initial configuration of 'financial types' that bundle related financial accounts together.
* We still need to configure the financial account associated with online payment processors separately from the rest of the financial accounts in a financial type.

Outline how financial batches are used:

* Batching transactions is a best practice for handling financial transactions. 
* Batching provides a convenient way to ensure audit-ability, and corresponds to to actions like depositing a set of cheques.
* Explain the process of closing batches, reconciling them, and then exporting them. Note that closed batches can be re-opened and adjusted, but exported batches cannot be changed. Additional change transactions can be created to adjust errors in an exported batch. 

## Configuration of Financial Accounts and Financial Types (10 minutes)

* Demonstrate how to export a Chart of Accounts from QuickBooks and view it in a low-level editor. Point out Account Code, Account Name, and Account Type.
* Show how to view the list of existing financial accounts at Administer > CiviContribute > Financial Accounts. Suggest benefits of editing existing accounts of the correct type over creating from scratch.
* Demonstrate how to edit a financial accounts and explain the importance of the accuracy of the Account Code, Account Name, and Account Type fields. Then show how to create one.
* Show how to view the list of existing Financial Types at Administer > CiviContribute > Financial Types. Point out related financial accounts for each.
* Demonstrate how to edit a financial type. Show how to change an existing relationship with a financial account and how to create a new one.

## Managing and Exporting Financial Batches (10 minutes)

* Show how to create a batch directly from data entry of offline contributions. Explain the purpose and importance of the number of items and total amount for the batch. Briefly illustrate entering offline memberships.
* Show how the batches appear in the Open batches. Close them.
* Show how one can edit a transaction, eg from $10 to $100. Reopen the transaction, include the changed entries, and close it again.
* Show how to export a batch as either .csv or .iif. Show how to re-export the same batch in case the file was lost or corrupted.
* Illustrate importing the .iif file into QuickBooks.

## Exercise (30 minutes)
