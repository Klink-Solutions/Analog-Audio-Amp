# Analog-Audio-Amp
### A low cost Audio Amplifier with input amplifier, bandpass filter & analog display
 A through-hole analog headphone amplifier built on a test board (no PCB). It has adjustable high-pass and low-pass filters, a volume knob, a stereo/mono switch, and a fully analog 10-segment LED level meter for each channel. Designed and simulated in Fusion (schematic and electronics), with SPICE models for simulation.
 
<img width="915" height="568" alt="AMP Render 1" src="https://github.com/user-attachments/assets/0053a674-355c-4dc8-893a-60895fbf5ecb" />
<img width="1015" height="707" alt="Screenshot 2026-10-25 at 20 18 22" src="https://github.com/user-attachments/assets/423b42e8-c21d-49e1-88b1-06b55c958235" />


## What is this?

A through-hole analog headphone amplifier with  adjustable high-pass and low-pass filters, a volume knob, a stereo/mono switch, and a fully analog 10-segment LED level meter for each channel. Designed in KiCad and simualted with its built in NgSpice tools.

## The goals:

* Take a stereo line-level signal in, filter it, amplify it, and drive headphones.
* Adjustable Treble and Bass gain, each set with a knob.
* Stereo or Mono mode set with a switch.
* Physical 10-segment LED bar per channel, driven fully analog.
* Through-hole parts only.
* Total cost under $30. 

## Repository content
| Path | Contents |
|------|----------|
|[CAD/](CAD/)| Fusion and step file of amplifier enclosure|
|[Schematics/](Schematics/)| KiCad project (schematics and simulation file)|
|[BOM.md](BOM.md)|	Bill of materials|
|[JOURNAL.md](JOURNAL.md)|	Devlog, synced from Half Life|
|[LICENSE](LICENSE)|	MIT licence|
|[README.md](README.md)| You are here|


## Bill of materials
| Item | Qty | Supplier | Cost/item | Total Cost | link |
| --- | --- | --- | --- | --- | --- |
| LM3915N(XBLW) | 2 | LCSC | $ 0.52 | $ 1.04 | https://www.lcsc.com/product-detail/C55109574.html |
| NE5532P | 10 | LCSC | $ 0.35 | $ 3.50 | https://www.lcsc.com/product-detail/C5326.html |
| Rectangular leds | 60 | LCSC |$ 0.03 | $ 1.80 | https://www.lcsc.com/product-detail/C5440571.html?s_z=n_q_t_led |
| Hong Cheng HC-DC-005-1.6-03A | 5 | LCSC | $ 0.11 | $ 0.55 | https://www.lcsc.com/product-detail/C55122129.html |
| SHOU HAN PJ-313 5JCJ | 5 | LCSC |$ 0.11 | $ 0.55 | https://www.lcsc.com/product-detail/C668607.html |
| RK16312101A2 | 2 | LCSC | $  2.96 | $ 5.92 | https://www.lcsc.com/product-detail/C470593.html |
| Estimated total shipping | 1 |  | $ 11.87 |

The project uses a few additional parts that I had a lying around at home and are so not includes in this BOM

## Help

Contact author 

## Author

Lucas Klemmer  
klinksolutions22@gmail.com

## License
MIT LIcense

If anyone ends up reproducing this project  or making it even better I would be happy to see your improvements and add them to the official release.
