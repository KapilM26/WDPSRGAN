# Wasserstein Dilation Patch Super Resolution Generative Adverserial Network

A PyTorch ( specifically PyTorch Lightning) implementation of WDPSRGAN.

## This Repo is a very much a work in progress

## TODO:
- [x] Change output layer of Discriminator.
- [x] Change training labels for Discriminator
- [ ] Implement Wasserstein loss function for Discriminator (Critic).
- [ ] Implement weight clipping for critic.
- [ ] Change training step to update critic more times per iteration (5x more than generator).
- [ ] Use RMSProp instead of Adam.
- [ ] Train model
- [ ] Verify results
- [ ] Repeat with multiple iterations for good results (Note down results in every iteration.
- [ ] Create requirements.txt