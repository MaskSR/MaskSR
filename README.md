# MaskSR: Masked language model for speech restoration

This is the demonstration page of the paper "MaskSR: Masked language model for speech restoration" with some selected samples generated with the proposed method.

## Abstract

Speech restoration aims at restoring high quality speech in the presence of a diverse set of distortions. Although several deep learning paradigms have been studied for this task,
the power of the recently emerging language models has not been fully explored. In this paper, we propose MaskSR, a masked language model capable of restoring full-band 44.1 kHz speech
jointly considering noise, reverb, clipping, and low bandwidth. MaskSR works with discrete acoustic tokens extracted using a pre-trained neural codec. During training, MaskSR is
optimized to predict randomly masked tokens extracted from the high quality target speech, conditioned on the corrupted speech with various distortions. During inference, MaskSR
reconstructs the target speech tokens with efficient iterative sampling. Extensive experiments show that MaskSR obtains competitive results on both the full-band speech restoration task
and also on sub-tasks compared with a wide range of models.


