# InfoDesc
This repo contains course projects related announcements and deadlines. I suggest you to subscribe for notifications here (click "Watch" button next to "Star" button).

Do not hesitate to open Github issues in case of administrative questions right here (in this repository). For question related to specific details of your team's projects, open issues at your team's repositories. I try my best to respond to them ASAP. Also, if you feel you need in person project support, email me so we assign a meeting this week. 

# Info
## Poster session info
The poster session will be held on Wednesday (19.12) in Liivi 2 (room 405) at 10:15.

To print your posters free of charge, send them to meedia@ut.ee by Tuesday morning the latest so that they can give them printed by Wednesday 9:30 AM. 

Also, put “[MachineTranslation2018]" into the subject of the email.

At the same time, upload them to GitHub to the project report repo!

Then you can pick them here http://goo.gl/1lNE3 (Lossi 3-141a, Tartu) (the door where it is written "Print on demand").

Please note, that 10:15 is the time when all the posters already should be on the walls! 

So please come earlier (before 10:00) to have some time to prepare.

## Preparing the poster
You can start making your posters. The target audience is other course participants.  

Some guidelines are here:
https://docs.google.com/document/d/1QECbT_mwCRGqlUkdMfig7SDV8K5vYumcKizl3mYLZpM/edit?usp=sharing

## Final report - Hard deadline: 10.12.2018 23.59
Hi everyone!

It is time to write your final reports. They are more like summaries of what you have done.

I prepared detailed guide of what should be included. The report should be in .md format. Please, follow the provided structure and keep it concise.

Report template link: https://classroom.github.com/g/a0sKhdFE

## Error analysis - Deadline extended. New deadline: 03.12.2018 23.59

## Error analysis - Deadline 02.12.2018 23.59
Your next task is comparative error analysis. You should have an input sentence in Estonian (`est`), two machine translations of this sentence (one is done by the baseline - `eng_base`, one by your big system - `eng_our`), and one reference in English (`eng_ref`). Take the same `est` and `eng_ref` sentences you used in practicum 4.

Now for each set of 4 sentences (`est, eng_base, eng_our, eng_ref`) compare eng_base to `eng_our` and to `eng_ref`. Make a conclusion which sentence (`eng_our` or `eng_ref`) is a better translation and provide a short justification of your choice. 

Format your output similar to how you did in practicum 4. Also, count how many times you prefer one system over another (e.g. baseline_score: 35/60; our_system_score: 25/60).

The baseline model is deployed on our neurotolge website: http://neurotolge.ee/# . Choose English as an output language. The choice of style is up to you (see which one is more similar to reference and use it; it won't make much difference in our case). So use this website to obtain baseline translations for comparison.

The deadline is Sunday 02.12.2018 23.59. 

#### Expected result: error analysis report
--- 
## Big experiment - Deadline 26.11.2018 23.59
...
2) Each corpus is split into train, dev and test sets. You can think of these sets as about in-domain sets and you should use them during your model training (training set for training, dev set for early stopping, test set for final evaluation). You should use this dev set for early stopping, and test set to report final BLUE. 
3) In addition, you should report a BLUE score on the "out-of-domain" dev set from the practicum 2.
4) I will share details about manual analysis later when we are done with this.

#### Expected result: translated out-domain set from practicum 2 and translated test set from shared data folder. BLEU scores for them. Paths to experiments on rocket.  
Note: if you have a trained system by the deadline and translated one of these required sets, but not another one, please add translation of the 2nd one and explicitly specify it in report. You can do it till 02.12.2018 23.59. We will not penalize you.

However, if you did not have a trained system and translated none of the sets, please also finish your experiments, but specify that you are doing late submission.
