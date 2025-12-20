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
In this section, we demonstrate that our model can generate different expressions given the same reference speech, and dialog history, but varying speaker description. 

---
## Varying Dialog History
In this section, we demonstrate that our model can generate different expressions given the same reference speech, and speaker description, but varying situation embodied through dialog history. 

<table>
  <thead>
    <tr>
      <th>Reference Speech</th>
      <th>Speaker Description</th>
      <th>Dialog</th>
      <th>Audio</th>
    </tr>
  </thead>
  <tbody>
    <!-- Group 1 -->
    <tr>
      <td rowspan="3">s
        <audio controls src="wavs/diff_situation/spk_1_ref_speech.wav"></audio>
      </td>
      <td rowspan="3">
        The speaker is a male adult introvert. The speaker's relationship with the dialog partner is close.
      </td>
      <td>
        <div style="white-space: pre-line;">
            <strong>DIALOG HISTORY:</strong><br>
            [SPK0]: She's dead.<br>
            [SPK1]: She's not dead.<br>
            [SPK0]: She's dead, and I hit her, and I killed her, and she's dead.<br><br>

            <strong>NEXT UTTERANCE:</strong><br>
            [SPK1]: She's not dead. She's acting dead. This is just... Listen, Adam, this is just a scene.
        </div>
      </td>
      <td>
        <audio controls src="wavs/diff_situation/spk1_a.wav"></audio>
      </td>
    </tr>
    <tr>
      <td>
        <div style="white-space: pre-line;">
            <strong>DIALOG HISTORY:</strong><br>
            [SPK0]: You'll see.<br>
            [SPK1]: How could they do that?<br>
            [SPK0]: They can't. It's impossible, but they'll figure a way.<br><br>

            <strong>NEXT UTTERANCE:</strong><br>
            [SPK0]: I've been in this company for ten years, and I've seen things you wouldn't believe.
        </div>
      </td>
      <td>
        <audio controls src="wavs/diff_situation/spk1_b.wav"></audio>
      </td>
    </tr>
    <tr>
      <td>
        <div style="white-space: pre-line;">
            <strong>DIALOG HISTORY:</strong><br>
            [SPK0]: You froze the account.<br>
            [SPK1]: I had to get your attention, Mark.<br>
            [SPK0]: Do you realize that you jeopardized the entire company? Do you realize that your actions could have permanently destroyed everything I've been working on? We have been working on- Without money, the site can't function. Okay, let me tell you the difference between Facebook and everybody else.<br><br>

            <strong>NEXT UTTERANCE:</strong><br>
            [SPK0]: We don't crash ever. If the servers are down for even a day, our entire reputation is irreversibly destroyed.
        </div>
      </td>
      <td>
        <audio controls src="wavs/diff_situation/spk1_c.wav"></audio>
      </td>
    </tr>

    <!-- Group 2 -->
    <tr>
      <td rowspan="3">
        <audio controls src="wavs/diff_situation/ref_02.wav"></audio>
      </td>
      <td rowspan="3">
        An energetic young female speaker with expressive prosody.
      </td>
      <td>
        Dialog example 4 (same ref & speaker)
      </td>
      <td>
        <audio controls src="wavs/diff_situation/out_02_1.wav"></audio>
      </td>
    </tr>
    <tr>
      <td>
        Dialog example 5 (same ref & speaker)
      </td>
      <td>
        <audio controls src="wavs/diff_situation/out_02_2.wav"></audio>
      </td>
    </tr>
    <tr>
      <td>
        Dialog example 6 (same ref & speaker)
      </td>
      <td>
        <audio controls src="wavs/diff_situation/out_02_3.wav"></audio>
      </td>
    </tr>
  </tbody>
</table>


---