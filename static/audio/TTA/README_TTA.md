## Thank you for your reviewing!
Hints to the TTA demo
- A headphone is usually better than speaker
- AudioSet (AS) vs. AudioCaps (AC) finetuning
  - Although finetuning on AC improves the FAD a lot, as is explained in Sec.5.1 in the paper, we think the AS version of SpecMaskGIT is good as well.
- HiFiGAN vs. BigVSAN
  - Although SpecVQGAN is the bottleneck in our current framework, BigVSAN tends to offer a better low-frequency response, making the audio sound richer.
- Text promts shows that without trainiong with audio-text paired data, SpecMaskGIT can still distinguish between similar prompts.