# Communications

## Aim

Learn about the various ways you can use CiviCRM to communicate with contacts.

## Objectives

- Have an overview of the different tools that you can use for communication in CiviCRM, and the requirements of each (e.g. any necessary system configuration or third party providers).
- Understand how to create and send personalised mass mailings, and how to track the effectiveness of these mailings.
- Understand CiviCRM's email templating system.
- Be able to carry out two way communication via SMS.
- Understand how to create scheduled mailings based on events or memberships

## Learning points

todo

## Session plan

This session aims to take 60 minutes. It includes some front of the class demonstrations (that can be carried out using the CiviCRM that was used to run the training course). Since this session is about sending live email, it is probably worth 1) ensuring that live email can be sent from the environment that you are using, and 2) reinforcing the fact with students' that live email will be sent.

### Overview (5)

Outline the three big parts of CiviCRM that we'll be looking at during this session. We'll start with CiviMail and with a bit of luck we'll have time to cover Scheduled reminders and

- CiviMail
- Scheduled reminders
- SMS

Mention that there are also other parts of CiviCRM where email gets sent, e.g. confiirmation receipts, the send email action but they are simple and we won't be talking much about them.

#### Email system configuration

- Setting up email is a **system administrator task**
- Configuring mail server - something you will want to get a pro to do or use a third party service.

### Mass mailing / CiviMail

aka. sending newsletters, etc. It makes sense to split this in two into

1.  mailing list management (covered in some exercises) and
2.  creating and sending newsletters

#### Mailing list management (5)

There are two key points to get across here

**1) Groups are the main tool for mailing list management**. These can be *smart* groups (e.g. meet up attendees)

Ask the class for examples of smart groups that would make sense as mailing lists. Make sure the final list contains

- members
- people that have attended an event
- people that have contributed more than a certain amount

Show them the manage groups page where you can create and edit groups: /civicrm/group

Show them that some but not all groups are mailing lists (so if you are wondering why your group is not showing up, it is probably because it is not a mailing list.

**2) CiviCRM allows people to control their own subscription to groups**

Show people the following page: /civicrm/mailing/subscribe and how this relates to /civicrm/group

Explain options for unsubscribe

- links in each email
- their contact dashboard

#### Creating newsletters (15)

Demonstrate how to create a mailing by walking through the CiviMail wizard on civicrm.org and creating a mailing to the people that have registered to attend this training and to the trainers.

A few key points to make sure that you get across

- Mailings start with groups (might help to create a group and add the students to that group first)
- Mailings can exclude previous mailings
- Mailings use **templates, headers and footers**
- Mailings use **tokens**
- Mailings should be **tested**
- Mailings can be scheduled
- Mailings *need* opt out and unsubscribe (what is the difference?)

Make sure that you include in the email

- external links for tracking
- an image that they will have to download images to see
- a token that is replaced by their name
- a checksum link to a profile form

    The link detail is http://www.organisation.org/civicrm/profile/edit?reset=1&gid=N&id={contact.contact\_id}&{contact.checksum} where *N* is the ID of the profile form you want them to edit.
    The special link lasts for 7 days from the day you send the mailing (in Drupal / Joomla sites).

#### Tokens and checksums

Talk about out of the box tokens and the fact that you can create custom tokens.

Explain what checksums are and get people to think about when they would be useful. Make sure the final list includes:

-   - non-logged-in users updating details in a profile form
    - going to contribution / membership pages with details pre-filled

Discuss with the group how useful this feature is in terms of being to keep contact data up to date.

Once your email is complete, send the mail. Have people open the email and click on the links so that you can show them tracking info.

### Scheduled reminders (5)

Scheduled reminders very useful. Can be based on events, memberships, activities.

Get people to come up with times at which you might want to use scheduled reminders:

Make sure that the final list includes

- before and after events with reminders / solicitations for feedback
- as people approach the end of their memberships (membership renewals)
- as reminder for staff to carry out activities (e.g. the day before they are due)

### Individual emails into and out of CiviCRM (5)

Show the other simple way that email can be sent from CiviCRM. Explain the different between that and CiviMail (no tracking, only a few contacts).

Auto-filing email conversations in CiviCRM with bcc.

### Communication exercises (10)

Get people to carry out the scheduled reminders exercises.

### SMS (5)

Sending an SMS is similar to sending an email apart from two things (get the class to think about what these might be

- no formatting
- replying is quite easy for SMS

To work with SMS, you need an SMS provider. CiviCRM currently supports clickatell.
