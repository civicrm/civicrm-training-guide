# Contribute

## Aim

## Objectives

Become familiar with basic financial concepts in CivICRM (including payment processors), be comfortable creating and working with online contribution pages, and be comfortable carrying out back end contribution administration and reporting.

## Learning points

Things to learn

- Basic CiviContribute concepts (contributions, types, custom data)
- Relationship of CiviContribute to other parts of CiviCRM (e.g. member and events)
- Contribution pages
- Payment processors
- Campaign widgets
- Premiums
- Personal campaign pages
- Back end contribution admin (including the contribution dashboard, creating and editing contributions, and bulk entry of offline contributions)

## Session plan

This session should take 60 minutes. Explain that we'll cover the basics and that you can go into more depth in the book if you want to.

### Basic concepts (10)

Explain that contributions are a the basic financial building block of CiviCRM, and that any financial transaction in CiviCRM (wether a donation, membership fee, etc.) is accompanied by a tranasction.

A final list of qualities of contributions should contain

- comes with out of the box contribution types
- you add more types of contribution (these can relate to accounting codes)
- you can attach custom data to contributions (ask them to think of some examples)
- always attached to contacts
- sometimes attached to other entities like participants and memberships
- link to financial types which define related financial types (for accounting integration)

### Contribution pages (10)

Show a few examples of real world contribution pages. It's probably helpful to show people some that have been themed, and some that haven't been themed. <https://www.eff.org/> and <http://leukaemialymphomaresearch.org.uk/> have some good examples of themed pages. CiviCRM has a good example of not themed pages.

Explain that contribution pages

- are out of the box
- allow people to donate money to do via your website
- have some cool features like

    - Recurring payments
    - Campaign widgets
    - Premiums
    - Personal campaign pages
    - Pledges

Ask if people how they would put extra fields on a contribution page

### Contribution page exercises (30)

Before starting the exercises, it is a good idea to show people what contribution page administration looks like by showing them the manage contribution pages screen.

Points to make clear include:

- you can set up as many as you like
- configuration happens via the tabs at the top of the screen.

You should also explain to them techniques for testing (which include logging out or going into private browsing / incognito mode to test) and what happens if you don't log out for testing).

When recapping the exercises, it might be worth noting the different ways that you can create contributions records in the backend (including the menu, the contributions page, the contact actions button).

### Payment processors (5)

Explain that if you want to take transactions on your site you'll need to integrate with a payment processor. Points to make

- There are two types of payment processor

    - on your website (SSL required, smoother workflow)
    - on the payment processors website (easier and cheaper)
- All payment processors have different pricing schedule
- You can see the out of the box integrations on the payment processors page.
- Other payment processors are available via extensions

### Personal campaign pages (5)

- Can be configured from the contribution page admin screens
- allow you to set up first/just giving style pages
