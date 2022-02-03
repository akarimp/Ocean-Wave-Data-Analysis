.. YA LATIF

Ocean Wave Data Analysis
========================

Ocean Wave Data Analysis: Introduction to Time Series Analysis, Signal Processing, and Wave Prediction

figure:: figures/Figure_Book_Coastal.jpg

Order at Amazon: https://www.amazon.com/dp/0692109978

In this book, readers learn about:

* Linear wave theory
* Time-series of ocean\coastal wave
* Wave data analysis in time domain (zero-crossing method)
* Wave data analysis in frequency domain (spectral analysis method)
* Window functions and digital filtering
* Analysis of water pressure and wave orbital velocity
* Wavenumber, wavelength, directional wave spectrum, wind sea, and swell waves
* Non-dimensional wave variables
* Wind and bathymetry data
* Water wave spectrums
* Parametric wave models
* Parametric hurricane models
* SWAN wave modelMATLAB and Python Codes are provided throughout the book to calculate different wave properties 

Contents
--------

1 Introduction to Wave Theory	1
    | 1.1 Linear wave theory	1
    | 1.2 Basic relations	2
    | 1.3 Wave characteristics based on water depth	3
    | 1.4 Dispersion relation	3
    | 1.5 Wave phase velocity (Celerity)	4
    | 1.6 Group wave velocity	5
    | 1.7 Water particle motion under the wave	5
    | 1.8 Water pressure under the wave	6
    | 1.9 Wave energy and power	7
    | 1.10 Wave radiation stress (momentum flux)	8
    | 1.11 Higher order wave theory	9
    | 1.12 Stokes waves	10
    | 1.13 Cnoidal waves	12
    | 1.14 Solitary waves	12

2 Introduction to Time Series: Data Acquisition and Preparation	13
    | 2.1 Sampling frequency	13
    | 2.2 Data sampling in burst and continuous modes	15
    | 2.3 Sampling duration	15
    | 2.4 Data quality control	17
    | 2.4.1 de-spiking	17
    | 2.4.2 Unacceptable data removal	18
    | 2.4.3 Missing data	18
    | 2.5 de-trending data	18

3 Introduction to Time Domain Data Analysis: Zero-Crossing Method	21
    | 3.1 Random sea	21
    | 3.2 Zero-crossing method	22
    | 3.3 Wave properties from zero-crossing method	24

4 Introduction to frequency domain data analysis: spectral analysis method	29
    | 4.1 Relationships between time and frequency domains	29
    | 4.2 Fourier analysis	31
    | 4.3 Power spectral density	35
    | 4.4 Periodogram method	38
    | 4.5 Frequency ordering	40
    | 4.6 Power spectral density calculation code	41
    | 4.7 Calculating a power spectral density using MATLAB/Octave and Python/SciPy functions	48
    | 4.8 Calculating wave properties from a spectral analysis method	49
    | 4.9 Wave properties calculation code	50
    | 4.10 Peak wave frequency from weighted integral of wave power spectrum	52
    | 4.11 MATLAB, GNU Octave and Python	54

5 Window Functions, Digital Filters and Data Smoothing	57
    | 5.1 Window function	57
    | 5.2 Digital filters	59
    | 5.2.1 Low-pass filter	61
    | 5.2.2 High-pass filter	63
    | 5.2.3 Band-pass filter	65
    | 5.2.4 Band-reject filter	67
    | 5.2.5 Low-pass filter code	69
    | 5.2.6 High-pass filter code	75
    | 5.3 Filter application in the time domain	77
    | 5.4 Filter application in the frequency domain	78
    | 5.5 Filtering a power spectral density	81
    | 5.6 Data smoothing	82
    | 5.7 Smoothing a power spectral density (periodogram)	84
    | 5.8 Calculating a power spectral density using MATLAB/Octave and Python/SciPy functions	85
    | 5.9 Code for smoothing a power spectral density using convolution	90

6 Pressure Data Analysis	93
    | 6.1 Pressure data correction to account for dynamic pressure attenuation in depth	93
    | 6.2 Obtaining water surface elevation from measured pressure data in the time domain	97
    | 6.3 Obtaining a power spectral density of the water surface elevation from measured pressure data in the frequency domain	99
    | 6.4 Lower limit for a pressure response factor	100
    | 6.5 Theoretical method to define an acceptable minimum value for a pressure response factor	102
    | 6.6 Practical methods to define an acceptable minimum value for a pressure response factor	106
    | 6.6.1 Practical method to define fmaxpcorr and Kpmin in the time domain	106
    | 6.6.2 Practical methods to define fmaxpcorr and Kpmin in the frequency domain	107
    | 6.6.3 Some guidelines on defining a constant fcH, an adaptive fmaxpcorr, and an adaptive Kpmin in the frequency domain	109
    | 6.6.4 Step by step procedure to obtain a water surface elevation power spectral density from measured pressure data in the frequency domain	112
    | 6.7 Accuracy of using a pressure response factor to convert pressure data to water surface elevation	115
    | 6.8 Wave spectrum diagnostic tail	117

7 Velocity Data Analysis	123
    | 7.1 Wave orbital and mean velocity (current velocity)	124
    | 7.2 Obtaining water surface elevation from measured velocity data in the time domain	127
    | 7.3 Obtaining a power spectral density of the water surface elevation from measured velocity data in the frequency domain	129
    | 7.4 Lower limit for an orbital velocity conversion factor	130
    | 7.5 Theoretical method to define an acceptable minimum value for an orbital velocity conversion factor	132
    | 7.6 Practical methods to define an acceptable minimum value for an orbital velocity conversion factor	136
    | 7.6.1 Practical method to define fmaxuvcorr and Kuvmin in the time domain	137
    | 7.6.2 Practical methods to define fmaxuvcorr and Kuvmin in the frequency domain	137
    | 7.6.3 Some guidelines on defining a constant fcH, an adaptive fmaxuvcorr, and an adaptive Kuvmin in the frequency domain	139
    | 7.6.4 Step by step procedure to obtain a water surface elevation power spectral density from measured velocity data in the frequency domain	142
    | 7.7 Accuracy of using an orbital velocity conversion factor to convert velocity data to water surface elevation	145
    | 7.8 Wave spectrum diagnostic tail	146

8 Calculating Secondary Wave Properties	151
    | 8.1 Calculating wavenumber and wavelength	151
    | 8.2 Relationship between wave properties in the time and frequency domains	157
    | 8.3 Calculating wave properties from the linear wave theory	158
    | 8.4 Wave height and wave period distributions	160
    | 8.5 Directional wave spectra	163
    | 8.6 Generating a time series from a power spectral density	170
    | 8.7 Wind Sea and swell waves partitioning	172

9 Wave Modeling and Prediction	177
    | 9.1 Non-dimensional variables	177
    | 9.2 Geographic coordinate system	179
    | 9.3 Wind data	181
    | 9.3.1 Wind gust factor (wind velocity averaging)	182
    | 9.3.2 Wind velocity profile	185
    | 9.3.3 Wind direction averaging	188
    | 9.4 Sustained wind	188
    | 9.5 Wind fetch	190
    | 9.6 Bathymetry data	192
    | 9.7 Water wave power spectra	193
    | 9.7.1 Bretschneider (1959) spectrum in deep water	195
    | 9.7.2 Pierson and Moskowitz (1964) spectrum in fully developed deep water	195
    | 9.7.3 JONSWAP (1973) spectrum in deep water	196
    | 9.7.4 Donelan (1985) spectrum for deep water	197
    | 9.7.5 TMA (1985) spectrum in depth-limited water	198
    | 9.7.6 Generating wave power spectra numerically	200
    | 9.8 Parametric wave models	201
    | 9.8.1 Fetch-limited wave growth, duration-limited wave growth and equivalent wind fetch	202
    | 9.8.2 Fully developed condition	203
    | 9.8.3 Asymptotic limit	204
    | 9.8.4 Mean water depth along a wind fetch	204
    | 9.8.5 Steps to calculate wave properties using parametric models	205
    | 9.9 Parametric wave model equations	208
    | 9.9.1 SMB parametric wave model in deep water	208
    | 9.9.2 Wilson (1965) parametric wave model in deep water	210
    | 9.9.3 JONSWAP (1973) parametric wave model in deep water	211
    | 9.9.4 Shore Protection Manual, SPM, (1984), parametric wave model in deep water	213
    | 9.9.5 Kahma and Calkoen (1992) parametric wave model in deep water	214
    | 9.9.6 Hwang and Wang (2004) parametric wave model in deep water	214
    | 9.9.7 Coastal Engineering Manual, CEM (2015), parametric wave model in deep water	215
    | 9.9.8 Shore Protection Manual, SPM, (1984), parametric wave model in depth-limited water	217
    | 9.9.9 Young and Verhagen (1996a) parametric wave model in depth-limited water	219
    | 9.9.10 Karimpour et al. (2017) parametric wave model in depth-limited water	220
    | 9.10 Parametric hurricane models	224
    | 9.10.1 Hurricane wind velocity and pressure models	224
    | 9.10.2 Hurricane historical data	226
    | 9.10.3 Hurricane maximum wind velocity	226
    | 9.10.4 Hurricane wind velocity adjustment for height and duration	226
    | 9.10.5 Hurricane wind velocity inflow angle	227
    | 9.10.6 Hurricane wind velocity adjustment for hurricane forward motion	228
    | 9.11 SWAN wave model	230
    | 9.11.1 Preparing a computational grid for SWAN	231
    | 9.11.2 Preparing depth data for SWAN	233
    | 9.11.3 Preparing water level data for SWAN	235
    | 9.11.4 Preparing wind data for SWAN	236
    | 9.11.5 Preparing a command input file for SWAN	238
    | 9.11.6 Start SWAN simulation	244
    | 9.12 Goodness of fit	245

Notation	249

References	265

Index	287

License
-------

CC BY-NC-SA 4.0 License

Ocean Wave Data Analysis: Introduction to Time Series Analysis, Signal Processing, and Wave Prediction

Copyright (c) 2022 Arash Karimpour

All rights reserved

Ocean Wave Data Analysis: Introduction to Time Series Analysis, Signal Processing, and Wave Prediction
© 2018 by Arash Karimpour is licensed under CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/)
