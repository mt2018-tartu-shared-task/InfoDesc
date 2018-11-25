# InfoDesc
This repo contains course projects related announcements and deadlines. I suggest you to subscribe for notifications here (click "Watch" button next to "Star" button).

# Info (incl. duplicates of my emails)

## Error analysis - Deadline 02.12.2018 23.59
Your next task is comparative error analysis. You should have an input sentence in Estonian (`est`), two machine translations of this sentence (one is done by the baseline - `eng_base`, one by your big system - `eng_our`), and one reference in English (`eng_ref`). Take the same `est` and `eng_ref` sentences you used in practicum 4.

Now for each set of 4 sentences (`est, eng_base, eng_our, eng_ref`) compare eng_base to eng_my and to eng_ref. Make a conclusion which sentence (eng_our or eng_ref) is a better translation and provide a short justification of your choice. 

Format your output similar to how you did in practicum 4. Also, count how many times you prefer one system over another (e.g. baseline_score: 35/60; our_system_score: 25/60).

To baseline model is deployed on our neurotolge website: http://neurotolge.ee/# . Choose English as an output language. The choice of style is up to you (see which one is more similar to reference and use it; it won't make much difference in our case). So use this website to obtain baseline translations for comparison.

The deadline is Sunday at 23:59. 

PS:
the deadline for the big experiment is tomorrow at 23:59. I expect you to push (to Github) your BLEU scores for the big models (also include a path to translated test/dev sets and experiment on the rocket). 

Do not hesitate to open Github issues, I try my best to respond to them ASAP. Also, if you feel you need in person project support, email me so we assign a meeting this week. 

#### Expected result: error analysis report
--- 
## Big experiment - Deadline 26.11.2018 23.59
...
2) Each corpus is split into train, dev and test sets. You can think of these sets as about in-domain sets and you should use them during your model training (training set for training, dev set for early stopping, test set for final evaluation). You should use this dev set for early stopping, and test set to report final BLUE. 
3) In addition, you should report a BLUE score on the "out-of-domain" dev set from the practicum 2.
4) I will share details about manual analysis later when we are done with this.

#### Expected result: translated out-domain set from practicum 2 and translated test set from shared data folder. BLEU scores for them. Paths to experiments on rocket.  
Note: if you have a trained system by the deadline and translated one of these required sets, but not another one, please add translation of 2nd one and explicitly specify it in report. You can do it till 02.12.2018 23.59. We will not penalize you.

However, if you did not have a trained system and translated none of the sets, please also finish your experiments, by specify that you are doing late submission.
Please specify that you are translated one of them before (either , and just adding translation of another one. If you translated non of sets till the deadline and doing late submition, explicitly state it.
