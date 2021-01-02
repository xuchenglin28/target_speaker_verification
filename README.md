# target Speaker Verification (tSV) / ts-vector

This repository includes the data, codes and models for tSV, where the test utterance could be a single- or multi-talker speech. The tSV includes a speaker attention module, a speaker representation module and a PLDA classifier. The front-end speaker attention module aims to extract the target speaker's voice from either a single- or multi-talker speech. The speaker representation module obtains speaker embeddings for both enrolment and test utterances. The front-end speaker attention module and the back-end speaker representation module are joinly optimized. Finally, the PLDA classifier makes a decision to accept or reject by comparing the speaker embeddings of enrolment and test utterances.

If you would like to learn the front-end processing about speech separation and speaker extraction, please visit our previous works:

Frequency-domain Speech Separation: https://github.com/xuchenglin28/speech_separation

Frequency-domain Speaker Extraction: https://github.com/xuchenglin28/speaker_extraction

Time-domain Speaker Extraction (SpEx): https://github.com/xuchenglin28/SpEx

# Data Configuration

## WSJ0-2mix-extr

Training/development/test (2-talker): egs/WSJ0-2mix-extr/data/[tr,cv,tt]/[mix.scp, aux.scp, ref.scp]

Training/development/test (2-talker+1-talker): egs/WSJ0-2mix-extr/data/[tr,cv,tt]/[mix_clean.scp, aux_clean.scp, ref_clean.scp]

SV evaluation set (enrol): egs/WSJ0-2mix-extr/data/enrol/[mix.scp, aux.scp]

SV evaluation set (1-talker test): egs/WSJ0-2mix-extr/data/trials_1talker/[mix.scp, aux.scp, trials]

SV evaluation set (2-talker test): egs/WSJ0-2mix-extr/data/trials_2talker/[mix.scp, aux.scp, trials]


## Libri2Mix

The data folder structure is similar, could be find in details at egs/Libri2Mix/data

# Code

# Released Models

code and model will be released when the paper is accepted.
