---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "About Me"
date: 2015
published: true
labels:
  - Education
  - Goals
summary: "My team developed a robotic mouse that won first place in the 2015 UH Micromouse competition."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Aloha everyone! My name is Levi, I'm a super senior who recently decided to double major in MIS to compliment my Marketing degree.

I started my college career at UH firmly believeing that Marketing was the area for me. Recently, I've felt that I want more than just Marketing, and MIS became that more. I found that MIS can fulfill my want to problem solve and get creative. Plus, after doing a little market research I found their are hybrid jobs that utilize both Marketing and MIS skills, such as a Marketing Technologist. 

I'm excited to my path where ever MIS takes me and to hopefully meet all of you! If I can give one piece of advice from being in college for so long (and its been quite a long time) it would be trust the process, theres no standard for when you need to graduate everyone is at their own pace. 

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
