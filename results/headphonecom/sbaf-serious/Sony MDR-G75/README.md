# Sony MDR-G75
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 5.8; 45 4.9; 49 3.8; 54 2.5; 60 1.2; 66 0.1; 72 -0.8; 79 -1.7; 87 -2.4; 96 -3.0; 106 -3.4; 116 -3.8; 128 -3.9; 141 -4.0; 155 -4.0; 170 -3.9; 187 -3.6; 206 -3.3; 227 -2.9; 249 -2.5; 274 -2.1; 302 -1.3; 332 -0.8; 365 -0.2; 402 0.2; 442 -0.2; 486 -0.1; 535 0.1; 588 0.3; 647 0.4; 712 0.5; 783 0.4; 861 0.3; 947 0.1; 1042 -0.2; 1146 -0.3; 1261 -0.5; 1387 -1.2; 1526 -2.3; 1678 -3.5; 1846 -3.3; 2031 -1.4; 2234 0.7; 2457 3.2; 2703 5.2; 2973 5.4; 3270 4.4; 3597 1.3; 3957 -2.1; 4353 -1.6; 4788 2.7; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 -0.5; 9330 -1.6; 10263 -0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR-G75 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-G75 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.2dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 30 Hz   |  0.72 | 7.2 dB  |
| Peaking | 122 Hz  |  0.78 | -5.2 dB |
| Peaking | 2948 Hz |  2.37 | 12.8 dB |
| Peaking | 3898 Hz |  0.72 | -9.5 dB |
| Peaking | 5638 Hz |  1.99 | 12.8 dB |
| Peaking | 230 Hz  |  1.58 | -1.5 dB |
| Peaking | 698 Hz  |  0.24 | 1.2 dB  |
| Peaking | 1751 Hz |  3.21 | -3.5 dB |
| Peaking | 2397 Hz |  6.5  | 1.2 dB  |
| Peaking | 4155 Hz | 10.56 | -2.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sony%20MDR-G75/Sony%20MDR-G75.png)