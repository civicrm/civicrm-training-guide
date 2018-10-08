# Profiles

## Aim

By the end of this session, you should understand how to use Profiles.

## Objectives

Specific objectives:

- Understand how to configure and create user defined profiles
- Understand how profiles are used by CiviCRM

## Learning points

You should aim to cover the following points in this session

- What profiles are and how they are created/edited
- Look at some example profiles in use
- Learners should create their own profiles and consider how their own organisation would use profiles

Extra points that it would be good to go into, if there is time include:

- Batch updating of contacts using a profile. **Note:** Batch update can only be performed on one type of contact at a time (Individual or Organisation) and on less than 100 contacts
- Embedding profiles into ANY web page using HTML form snippets (note: these forms don't work with Recaptcha enabled)
- Profiles and Access Control

## Session plan

This session should last 60 minutes. Without the exercises, you should be able to complete it in 30 minutes.

Demonstrate to the learners how profiles work and then ask the learners to complete the exercises

#### Basic concepts (15 minutes)

Explain to the the group that profiles are a collection of fields that are used to gather or display information.
Profiles are either user defined or reserved by the system and each one can be used multiple times.

Explain that they are used to collect new/edit existing data and are used to expose data.
As a group discuss who might use profiles (e.g. staff, volunteers, directory users, logged in site users, members, site visitors completing a form, event participants).

Go through the following data collection / existing data uses

- Such as new contacts - show the learners the reserved / new Individual profile create form
- Explain why the system uses reserved profiles and that you can still edit some elements of some reserved profiles
- Used to register site users and edit existing Drupal user account details - explain what this means
- Used for standalone data collection forms. Explain who might use these e.g. Volunteers adding form data
- Used for the batch updating of multiple contacts
- Used within Contribution and Event Registration forms

Go through the following exposing data uses

- Like a Searchable directory
- To show alternative search result views

#### Creating Profiles (15 minutes)

Create a new sample Profile and spend some time discussing with the group the meaning of all the Advanced options.
Mention the importance of using Recaptcha on public forms and how Account creation only works with Drupal/Joomla sites.
Explain that some options only matter when you are using the site to collect data and some only when you are exposing data.

Add some fields to the new profile asking the group for ideas . Explain to the learners that you cannot combine unsupported record types in a profile i.e. You cannot include both individual and organisational data fields in one profile.
After you have added some fields quickly look at the profile Preview.

Then discuss and change the setting of the visibility of each field to 'Public Pages'. This will make available a simple searchable directory for the profile.
If you are using a Drupal site you can demonstrate the new profile's directory by accessing the following URL;
<http://www.myorganization.org/civicrm/profile?reset=1&gid=N>

#### Exercises (30 minutes)

Then ask the learners to complete as many exercises as they can. They should be encouraged to explore and if useful questions are asked maybe relay the answer to the whole group.
Review the exercise answers as a group.

### More useful tools for Profiles

Explain that the Wiki / CiviCRM book contains a lot of detail and usage scenarios.
