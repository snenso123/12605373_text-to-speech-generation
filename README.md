# 12605373_text-to-speech-generation

### Project Description
The presented project addresses the challenge of generating natural-sounding and emphasized speech from a given text, in particular, the creation of a pleasant and easy to follow narrator voice for reading longer texts e.g. books, papers, etc. aloud. Therefore the already trained text-to-speech-model [Fish Audio Drama 3](https://fish.audio/de/drama-3/)[^1][^3] is used and further adapted to the given problem by fine-tuning the model parameters with **LoRA**[^5] on a single speaker subset of the [HUI-Audio-Corpus-German dataset](https://opendata.iisys.de/dataset/hui-audio-corpus-german/)[^4]. The project meets the requirements for project type **Bring your own method**. 

### Dataset
For fine-tuning the model with LoRA the HUI-Audio-Corpus-German dataset is used. It is assembled from voices of multiple speakers and contains normalized and noise-suppressed audio data with a high sample rate and corresponding transcripts. For the training process only one speaker subset is used.

### Work Schedule
| Task | Time |
| :--- | :--- |
| dataset collection and adaption | 2h |
| network design | 3h |
| metrics implementation | 3h |
| network fine-tuning | 10h (without computation time) |
| inference pipeline | 2h |
| validation and testing | 5h |
| report | 5h |
| presentation | 3h |
| **Total** | **33h** |

### References
[^1]: Fish-Speech: Leveraging Large Language Models for Advanced Multilingual Text-to-Speech Synthesis (DOI:10.48550/arXiv.2411.01156)  
[^2]: Fish Audio S2 Technical Report (DOI:10.48550/arXiv.2603.08823)  
[^3]: Fish Audio Drama 3 Technical Report (DOI: 10.48550/arXiv.2610.18010)  
[^4]: HUI-Audio-Corpus-German: A high quality TTS dataset (DOI: 10.48550/arXiv.2106.06309)  
[^5]: LoRA: Low-Rank Adaptation of Large Language Models (DOI: 10.48550/arXiv.2106.09685)  



