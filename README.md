# lagged_hilbert_coherence
Lagged Hilbert coherence, phase-locking value, and amplitude coherence

## Requirements
python version: joblib, scipy, numpy, statsmodels

matlab version: econometrics toolbox, signal processing toolbox

# Python files
- lagged_coherence.py: core functions
- demo.ipynb: demonstration of the new lagged coherence algorithm
- multi_trial_demo.ipynb: demonstration of new lagged coherence algorithm with multiple trials
- sims.ipynb: tests with simulated data
- meg_sensor_data.ipynb: analysis of MEG sensor data
- lfp_data.ipynb: analysis of LFP monkey data

# Matlab files
- lagged_hilbert_coherence.m: core function
- ar_surr.m: ARMA surrogate data generation
- demo.m: demonstration of new lagged coherence algorithm
- multi_trial_demo.m: demonstration of new lagged coherence algorithm with multiple trials
- rfft.m: Fourier transform of real signal
- irfft.m: inverse Fourier transform of real signal
- hilbert.m: hilbert transform
