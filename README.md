# Sigma-Delta-Modulator
Design and simulation of first and second order oversampling SDM working at 1-Msps rate.

## First Order SDM Modulator


### Circuit Schematic
![alt text](https://user-images.githubusercontent.com/90058055/225763547-f9375407-bbcc-4099-97c7-0e46172fcb2c.png "Circuit Schematic")

### DC Test
![alt text](https://user-images.githubusercontent.com/90058055/225960379-9875fbad-f4a7-44f8-a855-47d8a794e805.jpg "DC Test")
<br>
Periodicity in the integrator and quantizer outputs can be observed, which is known as (limit cycle). The large
quantization errors associated with one-bit quantization can make it challenging to maintain stability and
achieve accurate results.

### Sin Wave Test
![alt text](https://user-images.githubusercontent.com/90058055/225961652-fa94ae47-6576-446c-aca0-d73db9527303.jpg "Sin Wave Test")

### Output FFT
![alt text](https://user-images.githubusercontent.com/90058055/225962219-6c2135ab-cc3b-4948-8d31-b4574c104508.jpg "Output FFT")
<br>
Since the modulator is first-order, the noise is shaped with a slope of -20 dB/decade. 

## Second Order SDM Modulator

### Circuit Schematic
![alt text](https://user-images.githubusercontent.com/90058055/225964411-02247ea9-6717-4d2c-838f-e58fcf8da72d.png "Output FFT")

### Sin Wave Test
![alt text](https://user-images.githubusercontent.com/90058055/225966488-fa388409-5df7-4784-986d-56fa3f92e5c8.jpg "Sin Wave Test")

### Output FFT
![alt text](https://user-images.githubusercontent.com/90058055/225966655-c077176a-8b00-4b1c-8436-d05f39359b35.jpg "Output FFT")
<br>
Since the modulator is second-order, the noise is shaped with a slope of -40 dB/decade. 
