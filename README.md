# Noisy Signal Filter

## Project Description
The Noisy Signal Filter project involves the development of an advanced filter using statistical methods and machine learning techniques to enhance the quality of noisy signals. This project includes generating a sinusoidal signal, introducing Gaussian noise, designing a Butterworth low-pass filter, applying the filter, and visualizing the results.

## Project Steps

### 1. Setup and Generate the Noisy Signal
- Generated a sinusoidal signal with a frequency of 1 Hz and amplitude of 1.
- Introduced Gaussian noise with zero mean and a standard deviation of 0.5 to simulate real-world noisy signals.

### 2. Design a Low-pass Filter
- Utilized a Butterworth low-pass filter to target and mitigate high-frequency noise.
- Chose appropriate filter parameters such as cutoff frequency and filter order to optimize the filtering process.

### 3. Apply the Filter
- Applied the designed Butterworth low-pass filter to the noisy signal, significantly improving signal clarity.

### 4. Plot Results
- Plotted the original, noisy, and filtered signals to visually demonstrate the effectiveness of the filtering process.
- Analyzed the performance of the filter in terms of noise reduction and signal preservation.

## Usage

### Requirements
- Python 3.x
- NumPy
- Matplotlib
- SciPy

### How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/noisy-signal-filter.git
2. Navigate to the project directory:
   ```bash
  cd noisy-signal-filter
3. Run the Jupyter Notebook
  ```bash
  jupyter notebook NoisySignalFilter.ipynb
## Results
The project successfully reduces noise and enhances signal clarity using the Butterworth low-pass filter. The visualization of the original, noisy, and filtered signals demonstrates the effectiveness of the filtering process.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
