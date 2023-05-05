Download Link: https://assignmentchef.com/product/solved-ece253-homework-5
<br>
<ol>

 <li>A sampler of sampling frequency 1 kHz is taking samples of a sine-wave input signal at different frequencies.</li>

</ol>

Consider input signal frequencies of 250 Hz, 333 Hz, 667 Hz, 750 Hz, 1250 Hz and 1333 Hz. For each input frequency:

<ul>

 <li>Plot 50 samples of the sampled signal.</li>

 <li>From that plot, find the frequency of the reconstructed signal.</li>

</ul>

Hint: You may use whatever plotting package to draw this picutre, e.g. Excel/Libreoffice, Python, Matlab.

<ol start="2">

 <li>An audio ADC has a sampling frequency of 44.1 kHz. It is clocked by a clock source with 1 <em>µ</em>s of RMS jitter. It is fed with a 15 kHz sine wave at 1 V amplitude, which exactly fills its dynamic range.

  <ul>

   <li>What is the period of each sample?</li>

   <li>What is the magnitude of the RMS voltage noise that results from that jitter?</li>

   <li>What is the effective number of bits of the converter, assuming this is the dominant noise source?</li>

  </ul></li>

 <li>An audio signal, sampled at 50 kHz is processed using a 128-point FFT for frequency identification.

  <ul>

   <li>What is the frequency spacing between FFT bins?</li>

   <li>What is the highest frequency this system can identify?</li>

   <li>If the sampling frequency is increased, and the number of FFT bins remains constant, what happens to the bin spacing?</li>

  </ul></li>

</ol>

Applying a peak-fitting algorithm to the results allows the FFT algorithm to identify frequency differences as small as 1/5th the bin spacing.

<ul>

 <li>What is the largest sampling frequency that can be used with a 128-point FFT that would allow 440 Hz and 461 Hz to be clearly distinguished?</li>

</ul>

1