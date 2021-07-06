# Machine Learning Experiments
## Ray Tune
### Outline
- Study about **Ray Tune** API Implementation.
- Experiment with simplified loss function.
- Simple Baseline Code Implementation with **Class API**.
### Install Packages
- Miniconda Environment Installation (cpu-only)
  ```
  pip3 install torch torchvision torchaudio
  pip install ray[tune], ray[default]
  pip install jupyter, seaborn
  pip install bayesian-optimization
  pip install HEBO
  ```
### Description
  1. ray_tune_experiment : Experiment I
  2. ray_tune_with_es : Experiment II (with Early Stopping, Modules)
  3. ray_tune_with_class [*in progress*] : Experiment III (with **Class API** baseline)
  4. ray_tune_pytorch : PyTorch Implementation