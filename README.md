# Text_Completion_for_Persian

## Overview
In this project, the goal is to develop a language model to understand the context of a sentence in Persian. Using the trained language model, the most probable characters for completing the current word should be determined. The language model can be either character-based or word-based, or even a combination of both. For instance, you may first want to train your desired language model, narrow down the word domain, and then select the most likely word based on the character-based language model.

Input:
"دیروز که داشتم به دانشگاه میرفتم که کل."

Output:
"دیروز که داشتم به دانشگاه میرفتم که کلاس."

Input:
"دیوان شمس از مو"

Output:
"دیوان شمس از مولانا"

Input:
"به نام خ."

Output:
"به نام خدا"

The above examples are provided for better understanding, and our main domain coverage is news texts that are accessible.
