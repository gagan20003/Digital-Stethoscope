# Digital-Stethescope

<br>
<details>
  <summary>Table of Contents</summary>
    <ol>
        <li>
            <a href="#introduction">Introduction</a>
            <ul>
                <li><a href="#technologies-used">Technologies Used</a></li>
            </ul>
        </li>
        <li>
          <a href="#Objectives">Getting Started</a>
        </li>
        <li>
            <a href="#literature-survey">Literature Survey</a>
            <ul>
                <li><a href="#ESP32">MicroController</a></li>
                <li><a href="#Deep-Learning-Model">Detection Model</a></li>
            </ul>
        </li>
   
        <li>
            <a href="#references">References</a> 
        </li>
        <li>
            <a href="#project-mentors">Project Mentors</a></li>
        </li>
        <li>
            <a href="#project-members">Project Members</a></li>
        </li>   
    </ol>
</details>

<hr>

## Introduction

Digital Stethoscope aims at producing an electronics based amplifying stethoscope, which can store/ transmit the sound waveform captured to another device. Some of the advantages and motivation to switch from mechanically to electronically based amplifying are :
- Better amplification, and a more flexible range of amplification
- Noise reduction capabilities 
- Ability to store and transmit sound captures in order to analyse them on a later date 

### Technologies Used
We have used the following technologies and software for our project
- Python
- TensorFlow
- LTSpice
- AVR C
- ESP32

## Objectives 
The main goals we have set out for this project are 
- Make a microphone - amplification module that can detect frequencies from 50Hz to 20kHz 
- Transmit the sound clip to an associated laptop wirelessly 
- Be able to detect the disease by using an associated Deep Learning model <hr>

<!--- Microcontroller description starts --->

<h2>ESP32</h2>
<img src="https://cdn.shopify.com/s/files/1/0609/6011/2892/files/doc-esp32-pinout-reference-wroom-devkit.png?width=1384" alt="ESP32 Pinout"
  width="700"
  height="500"
  align="middle"
>
<p>The microcontroller that we are using in our project is the ESP32.
The ESP32 is a high-performance microcontroller board that is widely used in Internet of Things (IoT) applications.
Espressif Systems manufactures it, and it is the successor to the ESP8266. The ESP32 is built around a dual-core 
Tensilica LX6 processor that operates at up to 240 MHz, providing plenty of processing power for IoT applications.
</p>

The ESP32 microcontroller board has the following key features:
<ol>
<li>
    <em>Wi-Fi and Bluetooth connectivity:</em> The ESP32 includes Wi-Fi and Bluetooth connectivity, making it simple to connect to the internet and other devices.
</li>
<li>
    <em> Low power consumption:</em> The ESP32 is energy-efficient, with multiple power modes that allow it to operate on very little power.
</li>
<li>
    <em> Large Memory:</em> The ESP32 comes up with up to 520 KB of SRAM and 4MB of flash memory, which is enough to run complex applications.
</li>
<li>
    <em>GPIO pins:</em> The ESP32 has a large number of GPIO pins, which makes it easy to interface with other devices and sensors.
</li>
<li>
    <em>Development tools:</em> There are many development tools available for it including Arduino IDE, ESP-IDF, and MicroPython.
</li>
</ol>
<p>
Overall, the ESP32 is a powerful and versatile microcontroller board that is well-suited for a wide range of IoT applications. Its built-in Wi-Fi and Bluetooth capabilities, low power consumption, and large memory make it a popular choice among developers.

In this project, the esp32 is used to transmit the data collected from the microphone to the ML model over the in-built Wi-Fi.
</p> <hr>


<!--- Microcontroller description ends --->

## Project Mentors

1. [Dharaneedaran K S](https://github.com/DharaneedaranKS)
2. [Hrishikesh Kulkarni](https://github.com/HrishiCoolkarni)

## Project Members

1. [Aditya Rajesh](https://github.com/Adityarajesh001)
2. [Aman Raj](https://github.com/amanrajNitk)
3. [Chandan Padmashali](https://github.com/CHANDAN-2003)
4. [Gagan Mahotiliya](https://github.com/gagan20003)
