---
title: "Persona-Aware Conversational Text-to-Speech"
description: "authors list here"
---
## Abstract
Abstract here

---

## Audio Demo
We present some examples of speech synthesized by CineTTS, along with the ground truth and outputs from baseline models used in the user study.



---
## Varying Persona
In this section, we demonstrate that our model can generate different speech styles given the same reference voice, and dialog history, but **<u>varying speaker characteristics</u>**. 

**Reference Speech:**  
<audio controls src="wavs/diff_persona_1/ref_speech.wav"></audio>

**Dialog:**  

---
## Varying Dialog
In this section, we demonstrate that our model can generate different speech styles given the same reference voice, and speaker description, but **<u>varying situation</u>**. 

### Demo 1
**Reference Speech:**  
<audio controls src="wavs/diff_situation_1/ref_speech.wav"></audio>

**Speaker Description:**  
The speaker is a male adult introvert. The speaker's relationship with the dialog partner is close.

<table style="width:100%; table-layout: fixed;">
  <colgroup>
    <col style="width:60%">
    <col style="width:30%">
    <col style="width:10%">
  </colgroup>

  <thead>
    <tr>
      <th>Dialog</th>
      <th>Predicted Style</th>
      <th>Audio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        [SPK0]: She's dead.<br>
        [SPK1]: She's not dead.<br>
        [SPK0]: She's dead, and I hit her, and I killed her, and she's dead.<br><br>
        NEXT UTTERANCE:<br>
        [SPK1]: She's not dead. She's acting dead. This is just... Listen, Adam, this is just a scene.
      </td>
      <td>
        expressive,<br>
        moderate speed,<br>
        high pitch
      </td>
      <td>
        <audio controls src="wavs/diff_situation_1/a.wav"></audio>
      </td>
    </tr>
    <tr>
      <td>
        [SPK0]: You'll see.<br>
        [SPK1]: How could they do that?<br>
        [SPK0]: They can't. It's impossible, but they'll figure a way.<br><br>
        NEXT UTTERANCE:<br>
        [SPK0]: I've been in this company for ten years, and I've seen things you wouldn't believe.
      </td>
      <td>
        slightly expressive,<br>
        moderate speed,<br>
        moderate pitch
      </td>
      <td>
        <audio controls src="wavs/diff_situation_1/b.wav"></audio>
      </td>
    </tr>
    <tr>
      <td>
        [SPK0]: You froze the account.<br>
        [SPK1]: I had to get your attention, Mark.<br>
        [SPK0]: Do you realize that you jeopardized the entire company? Do you realize that your actions could have permanently destroyed everything I've been working on? We have been working on- Without money, the site can't function. Okay, let me tell you the difference between Facebook and everybody else.<br><br>
        NEXT UTTERANCE:<br>
        [SPK0]: We don't crash ever. If the servers are down for even a day, our entire reputation is irreversibly destroyed.
      </td>
      <td>
        slightly expressive,<br>
        fast speed,<br>
        high pitch
      </td>
      <td>
        <audio controls src="wavs/diff_situation_1/c.wav"></audio>
      </td>
    </tr>
  </tbody>
</table>

### Demo 2
**Reference Speech:**  
<audio controls src="wavs/diff_situation_2/ref_speech.wav"></audio>

**Speaker Description:**  
The speaker is a male adult whose voice is usually in the low pitch range. The speaker's relationship with the dialog partner is close.

<table style="width:100%; table-layout: fixed;">
  <colgroup>
    <col style="width:60%">
    <col style="width:30%">
    <col style="width:10%">
  </colgroup>

  <thead>
    <tr>
      <th>Dialog</th>
      <th>Predicted Style</th>
      <th>Audio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        [SPK0]: In our garden where I grew up.<br>
        [SPK0]: The view of the sea.<br>
        [SPK0]: Promise me you'll come back for me.<br><br>
        NEXT UTTERANCE:<br>
        [SPK1]: I promise I'll come back for you.
      </td>
      <td>
        monotone,<br>
        slow speed,<br>
        low pitch
      </td>
      <td>
        <audio controls src="wavs/diff_situation_2/a.wav"></audio>
      </td>
    </tr>
    <tr>
      <td>
        [SPK0]: A lot less dead than they are now.<br>
        [SPK1]: Oh, really? That's too bad.<br>
        [SPK0]: Yeah, it's too bad for you. Because they were part of your little dream team of thugs, weren't they?<br><br>
        NEXT UTTERANCE:<br>
        [SPK1]: Oh, that's right. You got me. Past tense. They were. Yeah, it's really quite a sad story, actually.
      </td>
      <td>
        slightly expressive,<br>
        moderate speed,<br>
        low pitch
      </td>
      <td>
        <audio controls src="wavs/diff_situation_2/b.wav"></audio>
      </td>
    </tr>
  </tbody>
</table>

---