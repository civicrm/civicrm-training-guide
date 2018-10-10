# Contibute

---
##Aim

By the end of the session, you should be able to manage contribution and contribution pages.

---
##Objectives

Become familiar with basic financial concepts in CiviCRM (including payment processors), be comfortable creating and working with online contribution pages, and be comfortable carrying out back end contribution administration and reporting.

---
##Learning points

Things to learn

* Basic CiviContribute concepts (contributions, financial types, custom data)
* Relationship of CiviContribute to other parts of CiviCRM (e.g. contacts, memberships and events)
* Contribution pages
* Payment processors
* Campaign widgets
* Premiums
* Personal campaign pages
* Sales tax and invoicing
* Back end contribution admin (including the contribution dashboard, creating and editing contributions, and bulk entry of offline contributions)

---
##Session Plan

This session should take 60 minutes. Explain that we'll cover the basics and that you can go into more depth using the book if you want to.

### Basic concepts (10)

Explain that contributions are the basic financial building block of CiviCRM, and that any financial transaction in CiviCRM (whether a donation, membership fee, etc.) is accompanied by a contribution.

Contributions are similar to other CiviCRM entities like contacts.  Ask learners if they can think about how they might be similar.

A final list of qualities of contributions should contain:

* CiviCRM comes with out of the box contribution types
* you can add more types of contribution (these can relate to accounting codes)
* you can attach custom data to contributions (ask them to think of some examples)
* contributions are always attached to a contact
* sometimes attached to other entities like participants and memberships
* Contributions are of a given type which define related financial types (for accounting integration)
* Contributions can be exported as a spreadsheet, and also in accounting package formats


### Contribution pages (10)

Explain that contribution pages:

* are out of the box
* allow people to donate money to you via your website
* have some useful features like
     * Profiles
     * Recurring payments
     * Campaign widgets
     * Premiums
     * Personal campaign pages
     * Pledges

Show a few examples of real world contribution pages. It's probably helpful to show people some that have been themed, and some that haven't been themed.  https://www.eff.org/ and http://leukaemialymphomaresearch.org.uk/ have some good examples of themed pages.  CiviCRM has a good example of not themed pages.

### Contribution page exercises (25)

Before starting the exercises, it is a good idea to show people what contribution page administration looks like by showing them the manage contribution pages screen.

Points to make clear include:

* you can set up as many as you like
* configuration happens via the tabs at the top of the screen.

You should also explain to them techniques for testing (which include logging out or going into private browsing / incognito mode to test) and what happens if you don't log out for testing.

When recapping the exercises, it might be worth noting the different ways that you can create contributions records in the backend (including the menu, the contributions page, the contact actions button).

### Payment processors (5)

Explain that if you want to take transactions on your site you'll need to integrate with a payment processor.  Points to make

* There are two types of payment processor
  * on your website (SSL required, smoother workflow)
  * on the payment processors website (easier and cheaper)
* All payment processors have different pricing schedules
* You can see the out of the box integrations on the payment processors page.
* Other payment processors are available via extensions

### Sales Tax and Invoicing (5)
* Show people the sales tax and invoicing settings pages (administer>CiviContribute>CiviContribute component settings)
* Discuss the page settings (what do you call sales tax, due date and display settings)
* Then show them how to create the sales tax Account (administer>CiviContribute>Financial accounts), make sure Financial Account Type is set to Liability. Select Enabled and Is Tax and specify the Tax Rate.
* After you create the Financial Account, assign it to the specific Financial Type (adminster > CiviContribute > Financial Types). Find the Financial Type this sales tax applies to, and click on Accounts. Click on Assign Account.
* Once a sales tax Financial Account has been added, you will see it listed with the other Financial Accounts for that specific Financial Type.

### Personal campaign pages (5)
* Can be configured from the contribution page admin screens
* allow you to set up justgiving style pages attached to a contribution page
