# MATLAB code for Fourier series handling (with FFT)

The **MATLAB** FFT/IFFT functions are good but not so easy to use for real periodic signal:
* the ordering of the frequency vector is confusing due to the negative frequencies (spectrums are symmetric)
* the coefficients are not scaled as in a Fourier series due to the definition of the DFT

The provided **MATLAB** functions offer different functionalities around **Fourier series**:
* get time and frequency vector
* wrappers around the MATLAB **FFT/IFFT** functions that scale periodic signals as Fourier series coefficients
* generate spectrum of **PWM periodic signal** (with finite or infinite slew rate) directly in the frequency domain

<p float="middle">
    <img src="readme_img/example_simple.png" width="400">
    <img src="readme_img/example_pwm.png" width="400">
</p>

Look at the examples [test_example_simple.m](test_example_simple.m) and [test_example_pwm.m](test_example_pwm.m).

## Compatibility

* Tested with MATLAB R2018b.
* No toolboxes are required.
* Compatibility with GNU Octave not tested but probably easy to achieve.

## Author

**Thomas Guillod** - [GitHub Profile](https://github.com/otvam)

## License

This project is licensed under the **BSD License**, see [LICENSE.md](LICENSE.md).
