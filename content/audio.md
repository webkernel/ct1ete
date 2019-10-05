---
title: "Audio Files (recorded by CT1ETE)"
date: 2019-10-05T16:45:16+01:00
draft: false
menu: "main"
---

<center>**Morse Runner 50 wpm training**</center>

<figure {{ with .Get "class" }}class="{{ . }}"{{ end }}>
<audio controls preload="{{ .Get "preload" | default "metadata" }}">
{{ with .Get "src" }}<source src="/audio/MorseRunner50.wav" type="audio/mpeg">{{ end }}
{{ with .Get "caption" }}<figcaption>{{ . }}</figcaption>{{ end }}
</audio>
</figure>

<center>**40m SSB recording (Elad FDM-S1 Receiver)**</center>

<figure {{ with .Get "class" }}class="{{ . }}"{{ end }}>
<audio controls preload="{{ .Get "preload" | default "metadata" }}">
{{ with .Get "src" }}<source src="/audio/7MHz_Ham.wav" type="audio/mpeg">{{ end }}
{{ with .Get "caption" }}<figcaption>{{ . }}</figcaption>{{ end }}
</audio>
</figure>

<figure {{ with .Get "class" }}class="{{ . }}"{{ end }}>
<audio controls preload="{{ .Get "preload" | default "metadata" }}">
{{ with .Get "src" }}<source src="/audio/7MHz_Ham2.wav" type="audio/mpeg">{{ end }}
{{ with .Get "caption" }}<figcaption>{{ . }}</figcaption>{{ end }}
</audio>
</figure>

<center>**30m CW recording (Elad FDM-S1 Receiver)**</center>

<figure {{ with .Get "class" }}class="{{ . }}"{{ end }}>
<audio controls preload="{{ .Get "preload" | default "metadata" }}">
{{ with .Get "src" }}<source src="/audio/10MHz_Ham.wav" type="audio/mpeg">{{ end }}
{{ with .Get "caption" }}<figcaption>{{ . }}</figcaption>{{ end }}
</audio>
</figure>
