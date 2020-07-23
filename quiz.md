## Quiz Speech Emotion Recognition (SER)


1. If we have a signal with a length of 32kHz, then framming will be done along into 40ms frame. If the overlap is half the length of the sample frame, then the number of samples in each frame and the length of the overlap is ...
   - [ ] 1280 samples and 200 overlap samples
   - [ ] 200 samples and 1280 overlap samples
   - [ ] 1280 samples and 640 overlap samples
   - [ ] 640 samples and 1280 overlap samples

2. Which one the statement below is NOT TRUE about emotions model concept?
   - [ ] The disadvantages for the dimensional representation is not intuitive enough and special training may be needed to label each emotion
   - [ ] In the dimensional approach, emotions are not independent of each other
   - [ ] In the discrete approach, emotions are independent of each other
   - [ ] Discreate emotions model can be able to define some of the complex emotional states observed in daily communication

3. The goal to process windowing on the frame is...
   - [ ] to sharpen the signal ends to zero at the beginning and end of each frame
   - [ ] Filter the frame into mel in the frequency domain
   - [ ] Convert the energy band to spectogram in frequency domain
   - [ ] None of above


4. Steps of MFCC:
    a. Take the logarithm of all filterbank energies.
    b. For each frame calculate the periodogram estimate of the power spectrum.
    c. Apply the mel filterbank to the power spectra, sum the energy in each filter.
    d. Frame the signal into short frames.
    e. Take the DCT of the log filterbank energies.

    The correct sequence when extracting voice features using MFCC is..
   - [ ] (a,b,c,d,e)
   - [ ] (a,c,b,d,e)
   - [ ] (d,c,b,a,e)
   - [ ] (d,b,c,a,e)


5. According to studies, human perception of sound frequency is not linear. So each note in the actual frequency was measured subjectively using a scale called "mel". Which of the following is a characteristic of the mel scale?
   - [ ] Mel scale is linear above 100Hz and logarithmic below 100 Hz
   - [ ] Mel scale is linear below 1KHz and logarithmic above 1KHz
   - [ ] Mel scale is logarithmic below 1Khz and linear above 1KHz
   - [ ] Mel scale is linear below 100Hz and logarithmic above 100 Hz