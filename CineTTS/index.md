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
In this section, we demonstrate that our model can generate different speech styles given the same reference voice, and dialog history, but varying speaker description. 

---
## Varying Dialog History
In this section, we demonstrate that our model can generate different speech styles given the same reference voice, and speaker description, but **<u>varying situation</u>**. 

**Reference Speech:**  
<audio controls src="wavs/diff_situation/spk_1_ref_speech.wav"></audio>

**Speaker Description:**  
The speaker is a male adult introvert. The speaker's relationship with the dialog partner is close.


<table style="width:100%; table-layout: fixed;">
  <colgroup>
    <col style="width:40%">
    <col style="width:30%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>

  <thead>
    <tr>
      <th>Dialog History</th>
      <th>Next Utterance</th>
      <th>Predicted Style</th>
      <th>Audio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        [SPK0]: She's dead.<br>
        [SPK1]: She's not dead.<br>
        [SPK0]: She's dead, and I hit her, and I killed her, and she's dead.
      </td>
      <td>
        [SPK1]: She's not dead. She's acting dead. This is just... Listen, Adam, this is just a scene.
      </td>
      <td>
        expressive,<br>
        moderate speed,<br>
        high pitch
      </td>
      <td>
        <audio controls src="wavs/diff_situation/spk1_a.wav"></audio>
      </td>
    </tr>
    <tr>
      <td>
        [SPK0]: You'll see.<br>
        [SPK1]: How could they do that?<br>
        [SPK0]: They can't. It's impossible, but they'll figure a way.
      </td>
      <td>
        [SPK0]: I've been in this company for ten years, and I've seen things you wouldn't believe.
      </td>
      <td>
        slightly expressive,<br>
        moderate speed,<br>
        moderate pitch
      </td>
      <td>
        <audio controls src="wavs/diff_situation/spk1_b.wav"></audio>
      </td>
    </tr>
    <tr>
      <td>
        [SPK0]: You froze the account.<br>
        [SPK1]: I had to get your attention, Mark.<br>
        [SPK0]: Do you realize that you jeopardized the entire company? Do you realize that your actions could have permanently destroyed everything I've been working on? We have been working on- Without money, the site can't function. Okay, let me tell you the difference between Facebook and everybody else.            
      </td>
      <td>
        [SPK0]: We don't crash ever. If the servers are down for even a day, our entire reputation is irreversibly destroyed.
      </td>
      <td>
        slightly expressive,<br>
        fast speed,<br>
        high pitch
      </td>
      <td>
        <audio controls src="wavs/diff_situation/spk1_c.wav"></audio>
      </td>
    </tr>
  </tbody>
</table>


---