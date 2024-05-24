# beta-rhythm-analysis
In this work, an 8th-order band-pass Butterworth IIR filter with cutoff frequencies of 14 and 30 Hz was used to extract the alpha rhythm from the EEG.
Screenshot from the Filter Designer and Analysis Tool:

![image](https://github.com/pr0tos/beta-rhythm-analysis/assets/137896055/2db45ced-0ce0-47b7-8a34-3d57b8da6a25)

The main window of programm:

![image](https://github.com/pr0tos/beta-rhythm-analysis/assets/137896055/e24e3a8a-c020-4beb-a552-9218ecc6c654)

A band-pass filter (8th-order Butterworth filter) was developed to isolate the β-rhythm. From the PSD plot of the filtered signal, it can be seen that the signal predominantly contains frequencies in the range of 14 to 40 Hz, corresponding to the EEG β-rhythm. A feature was added to allow the selection of different methods for calculating the PSD. Autocorrelation function (ACF) plots of the signals before and after filtering were constructed. The ACF plot after filtering decays fairly quickly, which may indicate weakly pronounced periodicities of the β-rhythm.








