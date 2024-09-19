# Notes
- I installed pytorch, fairseq, and nnAudio
- I also had to install transformers and datasets (both part of hugging face)
- soundfile, libsnd (sudo apt install), librosa, ffmpeg were also necessary
- Initial test using demo code shows model is working if ".double()" appended to "resampler" function OR ".float()" is appended to "torch.from_numpy" resampler input
- Next step is to fine-tune a model for a downstream task, maybe try to reproduce MERTech experiments
- Progress: I can download huggingface datasets to ".cache/huggingface", and process MERTech dataset
- Issues: the MERTech model fails at the beginning of training
