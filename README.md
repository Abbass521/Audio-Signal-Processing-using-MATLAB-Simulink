# Audio-Signal-Processing-using-MATLAB-Simulink
I have done an interesting project of audio signal processing. In this project first I have done basic filtering of the noise, echo effect, flange effect, graphic equalizer and reverb effect.
# Basic-Filtering
In the first task, I implemented the low-pass filter to remove the noise from the recorded audio signal. In this project, a low-pass filter (LPF) with a cutoff frequency of 8 kHz is implemented to eliminate white Gaussian noise. A notch filter is also designed to remove specific undesired frequencies, such as hums or electrical interference. Initially, I recorded the audio signal using MATLAB and stored it. I we selected a segment of the signal to apply low low-pass filter to it. Here is the block diagram, magnitude, and phase response of the filtered audio signal;

![Image](https://github.com/user-attachments/assets/581f1923-3f0f-42b2-b612-15998571caa6)


![Image](https://github.com/user-attachments/assets/e55bfd68-5859-40e5-950d-b56c4b144340)

![Image](https://github.com/user-attachments/assets/049092f7-784b-4a54-a9fb-21453f651291)


# Graphic-Equalizer

In this task, I observed the frequency response of the graphic equalizer by changing the gain and order of the equalizer. In this project, a 10-band equalizer is designed using MATLAB, enabling real-time adjustment of audio frequencies. Each band represents a distinct range of frequencies, and users can amplify or attenuate these ranges to enhance or balance the sound. Users can amplify or attenuate specific ranges to tailor the audio output, enhancing its quality or balance. By connecting external devices like mobile phones, live audio signals are processed, and the frequency response is visualized dynamically. Magnitude and phase response are given below;

![Image](https://github.com/user-attachments/assets/ba7cb055-772c-4ab9-98b8-dd4808e7d97a)

![Image](https://github.com/user-attachments/assets/82d1f537-4599-4c5a-b160-f8bec5a4101f)


# Echo-Effect

The echo effect replicates the natural phenomenon of sound reflections, adding a sense of depth and spatiality to audio. In this project, MATLAB is used to introduce a delayed version of the original signal, creating an echo that can be tuned for delay time and attenuation. Multiple echoes can be layered to simulate complex environments like large halls or open fields. This effect enriches the auditory experience, making it a popular choice in music production and sound design.

![Image](https://github.com/user-attachments/assets/d8375b9b-b8f2-4746-80cc-107f604a1eaa)

![Image](https://github.com/user-attachments/assets/a0d74c38-33f9-4fff-aa52-99a1d50213be)

