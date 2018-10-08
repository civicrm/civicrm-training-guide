# Duplicates

## Aim

By the end of this session, you should understand how to reduce and manage duplicate contacts

## Objectives

Specific objectives:

- Understand how to configure the Find and Merge Duplicate Contacts settings
- Understand how to run regular duplicate contact checks and how to merge duplicate contacts

## Learning points

You should aim to cover the following points in this session

- What duplicates are and how CiviCRM identifies them
- How to manually configure the Find and Merge Duplicate Contacts settings

Extra points that it would be good to go into, if there is time include:

- Merging contacts from search results - that you can merge 2 contacts directly from the contact search results action menu

## Session plan

This session should last 45 minutes with the exercises and 30 minutes without.

#### Basic concepts (10 minutes)

With the group talk about what duplicates are and ask the group why they may occur (e.g. from imported data, public form data, added by staff, misspellings).
Show the group the Find and Merge Duplicate Contacts page and at this stage explain the difference between the Supervised, Unsupervised and General rule types.

Unsupervised rules are used when new contacts are created through online registration forms including event, membership, contribution, and profile pages (and when you create a contact through CiviCRM's programming API).
Unsupervised rules place a priority on avoiding false matches and apply relatively rigid criteria. It is therefore possible to sometimes miss real duplicates.

Supervised rules are used to check for duplicates when contacts are added or edited via the CiviCRM user interface and a human has to decide if the match is accurate.
Supervised rules have a loose definition of matches so you can catch as many possible duplicates as possible.

Demonstrate to the group how a Supervised rule is used when you try to save a duplicate organisation and what your options are.

Explain to the group that when you import data you can choose which of the available rules you would like to use.

#### Configuring Rules (10 minutes)

Go back to the Find and Merge Duplicate Contacts page and edit the Organization Unsupervised rule.
Go through in detail the concepts of;

- Adding fields (add some more fields)
- The meaning of weight and weight threshold
- How length will effect the matching result. A good example is 'On a First Name field check with a length of 2 Jo and Joanne would be matched'.

Add a new rule that will identify individuals who have the same Postal Code and Birth Date.

#### Merging Contacts (10 minutes)

Run the Organization Unsupervised rule and explain the whole process of contact merging.
Not forgetting;

- To explain the implications of running a Batch dedupe
- What dedupe exceptions are
- The difference between the duplicate and the original on the merge screen
- What actually happens when you merge the contacts

#### Exercise 1 (15 minutes)

You can now ask the learners to complete Exercise 1. This will take around 10 minutes but it is then worth taking some time to review their answers in detail.

### More useful tools for Duplicates

Explain that the Wiki / CiviCRM book contains more detail on duplicate management. See the Deduping and Merging section.
