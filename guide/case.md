# Case management

## Aim

By the end of this session, you should understand how to set-up CiviCase and when it can be used

## Objectives

Specific objectives:

- Understand the principles behind CiviCase and under what circumstances it can be used
- Understand how to configure the CiviCase settings
- Understand the CiviCase interface

## Learning points

You should aim to cover the following points in this session

- What a case is
- How to add a new case type
- How to add new cases and to manage a case

Extra points that it would be good to go into, if there is time include:

- Case reports

## Session plan

This session should last 30 minutes and there are no exercises.
You should also have a sample case XML file ready to show the learners. This could be one of the sample files that come installed with CiviCRM.

#### Basic concepts (15 minutes)

Give the group a basic understanding as to what a case is. That;

- A collection of activities make up a single case
- A set workflow can be applied to a case (a workflow being a number of set sequenced activities called a Timeline)
- It is often used where various staff members (or external agencies) need to be involved in a single case

Ask the group to give example case types and discuss these. A good simple example is a medical one - 'open case', 'see doctor', ' approved for physiotherapy', 'attend physiotherapy sessions', 'close case'.
Or a Housing case type.

Go to the Case dashboard and look at each of the screen elements.

You should then create a new case of type Housing Support, show the status and look at the activities that appear in the timeline.
It is important to make it clear that the timeline doesn't have to be fixed and then you can add other activities to the case.
Explain the Case Roles and highlight how the existing contact relationships and case resources also appear on the case screen.
Case resources are available to all cases of a given case type.

Search for some cases and show the learners how you can use find activities to look for specific case activities (e.g. Search for open case activities only).

#### Adding a new case type / Case configuration (15 minutes)

Explain that setting up a new case type requires careful consideration.
Learners should be made aware that adding a new case type is different to the rest of the configuration jobs covered on the course.
New case types require the uploading of an XML file and you also need to add the exact same name to the Case Type list found in the administration console.

You should show the learners a sample XML file and look at each section in detail;

- The available activity types including the maximum number of instances (e.g. open case should have a maximum instance of 1)
- If you are adding a Timeline the activities which are included and the time between each activity (called the offset)
- Who will be involved (the case roles). These relationships will also have to be added to the available Administration / Relationship Types list

The activities, relationships and the case type names used in the XML need to match exactly with ones that exist in the CiviCRM system.

### More useful tools for Case Management

Explain that the Wiki / CiviCRM book contains more detail on case management. See the CiviCase section.
