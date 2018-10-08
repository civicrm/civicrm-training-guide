# Organising data

## Aim

Understand how data is organised within CiviCRM, and how to get data in and out of CiviCRM

## Objectives

Specific objectives:

- Learn about the core data structures that can be used in CivICRM
- Understand how to extend these data structures with types and custom data
- Understand how to import data to and export data from CiviCRM

## Learning points

You should aim to cover the following points in this session:

- core data

    - contacts and 'out-of-the-box' contact types
    - relationships
    - groups and tags
    - activities
- record types (e.g. activity types, contact types, membership types)
- custom data

    - custom data sets
    - location of custom data (entities and types)
    - custom data field types
- Importing
- Exporting

## Session plan

This session lasts 1 hour when accompanied by exercises.

Explain that we'll be building on what we learnt in the first session about

- contacts
- activities
- relationships
- tags and groups

That we are going to go into more detail on

- groups and tags
- relationships
- types
- custom data

### Groups vs. tags (10)

People tend to get quite hung up on the difference between groups and tags, and everyone has their own way of using them. Ask if there are any examples from the audience. It is worthwhile giving a few pointers here. Here are some suggestions:

- There is quite a lot of overlap between tags and groups
- There are some things that groups can do that tags can't, and visa versa (see handout for details)
- You'll learn from experience when to use one and not the other.
- You can reasonably easily change from a group to a tag and visa versa (select all contacts with a tag, and add them to a group)

Take questions from the learners on their use cases.

### Relationships (5)

Get people to brainstorm some different relationship types that are possible between contacts and write these on a board. Where appropriate, write the two different words for the relationship. You should end up with something like

- parent/child
- friend
- employer/employee
- subsidiary

Once they are on the board, ask people to think about what contact types go with different relationship types so you end up with something like

- individual <-- parent/child --> individual
- individual <-- friend --> individual
- individual <-- employer/employee --> individual
- organisation <-- subsidiary --> organisation

Explain that you can add extra relationship types to represent different relations in your organisation.

### Custom data (10)

Ask people what they would do if they wanted to store some extra information about a contact in CiviCRM, for example some extra information about potential funding organisations, like:

- the funders interests
- the amount of funding that the funder normally gives
- when the funding deadlines are

*Probably a good idea to explain the following by drawing some diagrams*...

Explain that this would be a good time to use custom data. Some points to get across:

- nearly all of the records in CiviCRM (e.g. contacts, activities, relationships, groups, etc.) can be extended with custom data fields.
- If you want to only add data to a certain type of object, you can do so. For example if you only wanted to add funding information to 'funders', you can make a new type of organisation called 'funder' and add the fields there. (Probably a good idea to explain this via drawing on a board.)
- remember that custom data is only one way to model data in CiviCRM. Often the right approach but consider other approaches as well (groups, tags, and other built in entities)

*Probably a good idea to explain the following by going through the user interface...*

Explain that there are two steps to adding custom data.

1.  Choose the object that you want to add the custom data to, and add a custom data set to that object (or specific type of object)
2.  Add custom data fields to that set

Explain that each field has a type. Help learners understand the the different types of custom data fields that exist by asking them what field types they would use for the data above.

### Organising data exercises (20)

At this point, learners should do the organising data exercises.

5 minutes before the end of this session, ask someone who has completed the exercise if they would like to demonstrate their custom data set in use. If no one is willing to do so, then ask if you can demonsrate it for them and ask them questions about why they chose certain fields.

### Importing and exporting (10)

Importing is fiddly so don't let the class loose on importing data. Instead, show them an example of importing some data, using emails as a unique identifier.

Explain to them about matching existing contacts and the different actions that can be taken when a duplicate is matched, e.g. skip, update, fill.
