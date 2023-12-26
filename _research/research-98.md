---
title: "The production of self-floating adsorption functional materials by modifying hollow glass microspheres"
excerpt: "The review paper titled “Modifying Hollow Glass Microspheres to Obtain Self-floating Adsorbents for Wastewater Treatment: A Review” is currently under revision. <br/><img src='/images/Sory-1.png' style='width: 90%;'>"
collection: research
---

With the advent of the Internet of Things, smart voice boxes with capabilities to control other smart devices have sprung up. Our project **aims to create a Smart Voice Box for home device control based on the Raspberry Pi to solve some problems that harm the quality of family life**, such as the inconvenient manual operation, incompatibility with other smart devices, and privacy concerns with commercial smart voice boxes. The system consists of 7 modules, including keyword spotting & instruction fetching module, speech-to-text module, function switch module, home smart device integration module, machine intellectual dialogue module, music retrieving & playing module, and text-to-speech module.
<br/><img src='/images/Sory-2.png' style='width: 100%;'>  

A Raspberry Pi is utilized as a motherboard, connecting all other parts, and providing the computing ability. To receive voice instructions and respond, we adopt a microphone array for better reception and a loudspeaker to play sounds.  
<br/><img src='/images/Sory-3.png' style='width: 100%;'>

**When in idle condition**, the microphone array will keep detecting the keyword preset. After the wake-up word is detected, the voice box will keep checking the power of sound. Once the power detected is below a threshold, the microphone array will automatically stop recording, so that the system could process right clips of speaker's voice. Then, Speech-to-Text Module will first converts voice data into a WAVE file , and the WAVE data is then sent to API and converted into text. After that, Function Switch Module will execute specific functions accroding to instructions spoken by users. At last, specific function moudule is opearated. 
<br/><img src='/images/Sory-4.png' style='width: 100%;'>

**In offline mode**, Sory can only catch some keywords in your instructions, compare them with the corpus stored and finally respond correctly. **If connected to the network**, Sory will be smarter and more powerful. It can analyze the whole sentence spoken by users and use online API from Microsoft to understand the instructions.
<br/><img src='/images/Sory-5.png' style='width: 100%;'>

As the main speaker, I presented our team's developed smart speaker at **2022 University Students Research Presentation**, where it garnered unanimous praise and won the National Second Prize.  
<br/><img src='/images/Sory-6.png' style='width: 49%;'>      <img src='/images/Sory-7.png' style='width: 49%;'>

Now, my teammates and I are writing a business plan, preparing to transform Sory into a guardian spirit for the elderly, and participate in the National Internet+ Innovation and Entrepreneurship Competition. 
<br/><img src='/images/Sory-8.png' style='width: 100%;'>
