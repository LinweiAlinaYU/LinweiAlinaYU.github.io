---
title: "A Comparative Study of Technological and Engineering Education Policies in China and the USA"
excerpt: "Assisted STEM education policy research of the *Standards for Technological and Engineering Literacy* published in the United States (ITEEA, 2020), and *The Science Curriculum Standards of Compulsory Education (the 2020 vision)* in China (MoE, 2020). Conducted literature review and conducted content analysis. <br/><img src='/images/acoustic-1.png' style='width: 90%;'>"
collection: research
---

This research project focuses on the design and implementation of an **OFDM (Orthogonal Frequency Division Multiplexing) acoustic communication system**, emphasizing the division into three layers: physical layer, data link layer, and application layer. The system utilizes speakers and microphones as the primary components for transmitting and receiving data through sound waves. A GUI (Graphical User Interface) is developed to provide user-friendly control and visualization.

The project aims to establish a **reliable** and **efficient** communication channel for transmitting data through **sound waves**. To achieve this, **adaptive frame detection and dynamic thresholding techniques** are implemented to enhance the system's performance.

<br/><img src='/images/acoustic-2.png' style='width: 100%;'> 

In high school, our teacher would first take an answer sheet and **burn holes at the positions of the correct options** when correcting our answer sheets. This way, when correcting the students' answer sheets, all the teacher needed to do was to overlay the burned answer sheet on top of the students' answer sheets and observe if the punched holes matched the students' selections, thus determining if their answers were correct or not. This method served as inspiration in the field of adaptive frame detection, where we also **use a "matching" approach to detect frame headers**. Upon receiving a signal, we similarly utilize a **frame header matching matrix** to align it with the received signal. When the correlation between the two is maximized, the frame header can be accurately identified.

<br/><img src='/images/acoustic-3.png' style='width: 49%;'>   <img src='/images/acoustic-4.png' style='width: 49%;'> 

Mass is a measure of an object's inertia, including the source of noise. It is because the source of noise also possesses inertia that **noise exhibits a certain trend in its variations**. If we can predict or fit this trend, we can mitigate the influence of noise on decision-making to some extent. The dynamic thresholding technique we have designed is based on this idea. We drew inspiration from RNN (Recurrent Neural Network) and **dynamically adjust our decision threshold** based on previously received data.

<br/><img src='/images/acoustic-5.png' style='width: 49%;'>   <img src='/images/acoustic-6.png' style='width: 49%;'> 

We do not rely on experience to obtain the parameters in dynamic decision-making. Instead, we extract samples from multiple scenarios and explore all possible parameter combinations for each scenario. Ultimately, we select the parameters that perform exceptionally well across all scenarios.

<br/><img src='/images/acoustic-7.png' style='width: 49%;'>   <img src='/images/acoustic-8.png' style='width: 49%;'> 

The final experimental results demonstrate the effectiveness of our algorithm. Our system enables data transmission in channels with significant interference, such as in the presence of acoustic noise, making it feasible.

<br/><img src='/images/acoustic-9.png' style='width: 100%;'> 

