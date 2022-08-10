---
title: France vid
date: 2022-08-10T20:52:09.298Z
description: Holiday in France
---
```
import React from "react"
import DogVideo from "../assets/france_vid.mp4"

export default function Home() {
  return (
    <video controls>
      <source src={DogVideo} type="video/mp4" />
    </video>
  );
}
```