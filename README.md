# Modified IEEEtran.bst BibTeX style with file links, doi links, and url

The **MATLAB** FFT/IFFT functions are good but not so easy to use for real periodic signal:
* the ordering of the frequency vector is confusing due to the negative frequencies (spectrums are symmetric)
* the coefficients are not scaled as in a Fourier series due to the definition of the DFT

The provided **MATLAB** functions offer different functionalities around **Fourier series**:
* get time and frequency vector
* wrappers around the MATLAB **FFT/IFFT** functions that scale periodic signals as Fourier series coefficients
* generate spectrum of **PWM periodic signal** (with finite or infinite slew rate) directly in the frequency domain

<p float="middle">
    <img src="screenshot.png" width="600">
</p>

Look at the examples [thesis.pdf](thesis.pdf).

## Compatibility

* Tested with bibtex (MiKTeX 2.9 and TeX Live 2017)
* Tested with pdflatex (MiKTeX 2.9 and TeX Live 2017)
* Tested with lualatex (MiKTeX 2.9 and TeX Live 2017)

## Author

**Thomas Guillod** - [GitHub Profile](https://github.com/otvam)

## License

This project is licensed under the **LaTeX Project Public License**, see [LICENSE.md](LICENSE.md).
