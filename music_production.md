---
layout: page
title: Music/Production
published: true
---

From childhood on, I've always been surrounded by music and musicians, and have been  inspired to follow in their footsteps, both through creating my own music, and supporting others in doing likewise. 

From folk music (my dad was a folk singer/songwriter), to jazz, pop, experimental/electronic, and world music, my musical explorations have involved me in many diverse aspects of music creation and production, from composing and producing my own original music, to supporting other musical artists in various capacities.

## Skills and Interests
- synthesizer programming/sound design
- MIDI production
- music recording, producing, and mixing
- audio editing
- music software:
  - ProTools (Avid-certified user)
  - Digital Performer
  - Reason
  - Recycle
  - Native Instruments Komplete
  - Metasynth
- electronic music composition
- song writing
- guitar
- vocals
- keyboard
- hand drums/percussion

## Recording Credits
<table class="table table-striped">
  <tr>
    <th>Name</th>
    <th>Artist</th>
    <th>Description</th>
  </tr>
  {% for credit in site.data.recording_credits %}
    <tr>
      <td><a href="{{ credit.link }}">{{ credit.name }}</a></td>
      <td>{{ credit.artist }}</td>
      <td>{{ credit.description }}</td>
    </tr>
  {% endfor %}
</table>

## Live Performances
<table class="table table-striped">
  <tr>
    <th>Name</th>
    <th>Information</th>
    <th>Description</th>
  </tr>
  {% for performance in site.data.live_performances %}
    <tr>
      <td>
        {% if performance.link %}
          <a href="{{ performance.link }}">{{ performance.name }}</a>
        {% else %}
          {{ performance.name }}
        {% endif %}
      </td>
      <td>{{ performance.info }}</td>
      <td>{{ performance.description }}</td>
    </tr>
  {% endfor %}
</table>

## Other Production Credits 
- **Various TV & Radio Commercials:** synthesizer programming and/or recording, post-production,and mixing  
  - AMTRAK
  - Chrysler
  - Omni Magazine
  - Singer
  - Black & Decker
  - Laughing Cow
  - Thomas’ English Muffins
  - Breeders Cup

- **Miscellaneous Projects**
  - pre-production for “Saturday Night Live” (with composer Howard Shore) - synthesizer programming
  -  “source” music for TV soap opera “Another World” (with composer Mike Mandel) -  recording,   production, and mixing
  - theme music for PBS series, “Bookends” (with composer Scott Killian) - recording, co-production, and mixing
  - soundtracks for various works by video artist [Rita Myers](http://www.eai.org/artistTitles.htm?id=402), including a major Whitney Museum
installation in 1985 - recording, co-production, and mixing
  - various modern dance scores for composers Linda Fisher and Scott Killian - recording, co-production, and mixing
  - music editing for the network TV broadcast of the 1988 Summer Olympics
  - audio post-production and mixing for sports broadcasts “Best of the Beach” and the Breeders Cup.
  - "M1: The Video" - script writer and on-screen instructor: a  series of four two-hour instructional    videos on all  operational aspects of the Korg M1 Synthesizer.

## Original Music
- Songs:
- Electronic music: 