# AKG K712
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -3.2dB
GraphicEQ: 21 0.0; 23 0.3; 25 -0.0; 28 -0.5; 31 -0.8; 34 -1.1; 37 -1.4; 41 -1.6; 45 -1.9; 49 -2.1; 54 -2.3; 60 -2.6; 66 -2.9; 72 -3.2; 79 -3.5; 87 -3.9; 96 -4.2; 106 -4.5; 116 -4.7; 128 -4.8; 141 -5.0; 155 -5.3; 170 -5.6; 187 -5.9; 206 -6.2; 227 -6.4; 249 -6.4; 274 -6.3; 302 -6.1; 332 -5.9; 365 -5.6; 402 -5.5; 442 -5.3; 486 -5.0; 535 -4.6; 588 -3.9; 647 -3.3; 712 -2.8; 783 -2.1; 861 -1.4; 947 -0.6; 1042 0.6; 1146 1.9; 1261 2.9; 1387 2.3; 1526 1.1; 1678 -0.2; 1846 -1.1; 2031 -2.3; 2234 -3.1; 2457 -1.3; 2703 1.6; 2973 2.7; 3270 1.8; 3597 0.9; 3957 -0.5; 4353 -1.9; 4788 -2.7; 5267 -5.2; 5793 -6.3; 6373 -3.7; 7010 -3.8; 7711 -3.9; 8482 -0.3; 9330 0.0; 10263 0.0; 11289 -1.7; 12418 -4.2; 13660 -1.2; 15026 -0.5; 16529 -5.4; 18182 -9.2; 20000 -8.1
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`AKG K712 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-31**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `AKG K712 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-2.0dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 347 Hz   | 0.25 | -7.2 dB  |
| Peaking | 1997 Hz  | 0.5  | 10.1 dB  |
| Peaking | 2111 Hz  | 2.02 | -10.4 dB |
| Peaking | 5549 Hz  | 1.48 | -8.6 dB  |
| Peaking | 18837 Hz | 1.27 | -10.3 dB |
| Peaking | 17 Hz    | 2.07 | 1.3 dB   |
| Peaking | 1238 Hz  | 8.13 | 1.4 dB   |
| Peaking | 10328 Hz | 3.28 | 2.2 dB   |
| Peaking | 12243 Hz | 3.65 | -4.0 dB  |
| Peaking | 14615 Hz | 4.6  | 3.2 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_over-ear_2018/AKG%20K712/AKG%20K712.png)