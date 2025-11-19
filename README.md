## Project Title: AD 331 Experimenting with Pre-trained LLMs (GPT-2)
#### By: Amde Wubshet

### Chosen Task: 
Text Generation 

### Test Cases 
| Parameter Value | Output Snippet | Brief Observation |
|---|---|---|
| temperature=0.8 | A long time ago in a galaxy far, far away... Some thought he was going there because now he had finally found the right place... | Text is not repeating like the core implementation output |
| max_new_tokens=150 | A long time ago in a galaxy far, far away... the Dropship's guardian angel was about to encounter a corrupted soul ... | Compared to the temperature output there are less new lines |
| top_p=0.92 | A long time ago in a galaxy far, far away... a shambling mecha robot heart-leveled teacher from a hefty order in a lab (wannabe, sadist, robotics engineer, the kind of person who will change his course... | Top-p has to be pretty high. It feels like anything below .9 is bound to lead to repeats in text generation |