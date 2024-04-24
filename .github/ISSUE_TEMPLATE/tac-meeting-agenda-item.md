---
name: TAC Meeting Agenda Item
about: Propose an agenda item to discuss at an upcoming TAC meeting
title: AGENDA TOPIC
labels: ''
assignees: Naomi-Wash

---

The TAC welcomes topics of interest to the community and our hosted projects. Plese set the issue title above to the agenda topic and fill out the following details to have this added to a future TAC meeting agenda. 

Note that you must be available to lead this discussion during a TAC meeting. You can find TAC meeting information and how to join on the community calendar: https://pqca.org/calendar/

 - type: textarea
    id: details
    attributes:
      label: Please share any additional details on this topic
 - type: textarea
    id: details
    attributes:
      label: Detail what actions or feedback you would like from the TAC
 - type: dropdown
    id: time needed
    attributes:
      label: How much time do you need for this topic?
      options:
        - 10 minutes or less
        - 30 minutes
    Validations:
         required: true
