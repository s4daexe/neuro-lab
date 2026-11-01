# neuro-lab
NeuroDecode

EEG-based motor imagery classification using signal processing and machine learning.

NeuroDecode is a computational neuroscience project exploring how brain activity can be decoded to distinguish between imagined left- and right-hand movements. The project uses real EEG recordings to investigate neural patterns associated with motor imagery and their applications in brain–computer interfaces (BCIs).

Project Goals

* Process and analyze real EEG recordings.
* Explore neural activity associated with motor imagery.
* Extract meaningful features from EEG signals.
* Train machine-learning models to classify imagined movements.
* Evaluate decoding performance and visualize results.

Dataset

PhysioNet EEG Motor Movement/Imagery Dataset

Publicly available EEG recordings from 109 participants performing motor execution and imagery tasks.

Dataset

Tech Stack

* Python
* MNE-Python
* NumPy
* SciPy
* Matplotlib
* scikit-learn

Roadmap

* Set up development environment
* Download initial EEG recordings
* Explore and visualize EEG signals
* Preprocess recordings and extract motor-imagery trials
* Implement feature extraction
* Train a classification model
* Evaluate decoding accuracy
* Analyze results and generate visualizations

Getting Started

git clone https://github.com/s4daexe/neuro-lab.git
cd neuro-lab
python3 -m venv .venv
source .venv/bin/activate
pip install numpy matplotlib mne
python load_eeg.py

Status

Work in progress — EEG data acquisition and exploration.

License

MIT License.
