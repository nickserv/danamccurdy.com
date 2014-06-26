---
layout: page
title: "Teaching & Consulting"
published: true
---

Ever since I first heard the Beatles' "I Am the Walrus" as a teenager, I've been fascinated by the art and science of music technology, and how it contributes to the process of creative music making. 

A few years later, I started teaching others how to use this technology for their own creative expression, and I haven't stopped since. My goal has always been to empower people to create their music as effectively, economically, and independently as possible, using whatever tools are currently available. 
 
Over the years, I have taught countless individuals, usually in their home studios, as well as hundreds of classes in various New York and New Jersey schools. As a consultant, I provide whatever technical support and coaching my clients may need to work effectively and complete their projects, from software and hardware installation and trouble-shooting, to MIDI production, engineering, editing, and mixing.
 
## Subjects I teach (with some overlap)
- sound synthesis
- sampling
- home recording
- MIDI
- computer-based music production
- Propellerhead Reason
- Native Instruments Komplete
- ProTools (as an Avid-certified instructor)
 
## Schools I've taught at
- New School University (NYC)
- Harvestworks/Studio PASS (NYC)
- Mannes School of Music (NYC)
- High Tech High School (N. Bergen, NJ)
- Ramapo College (Mawhwah, NJ)
- Vassar College (Poughkeepsie, NY)
- Institute of Audio Research (NYC)
 
## Some of my notable students and clients
<dl class="dl-horizontal">
  {% for person in site.data.students_and_clients %}
    <dt>
      {% if person.link %}
        <a href="{{ person.link }}">{{ person.name }}</a>
      {% else %}
        {{ person.name }}
      {% endif %}
    </dt>
    <dd>{{ person.description }}</dd>
  {% endfor %}
</dl>