In many audio processing applications, the occurrence of noise reduces the overall quality of the signal. This affects the performance of the subsequent steps such as Speech recognition, and speaker identification. This paper presents a real-time noise reduction and segmentation approach for audio signals using spectral subtraction. The proposed method segments the audio. Segment-wise noise reduction is beneficial in terms of computational efficiency and flexibility. The algorithm used is Voice Activity Detection (VAD) the algorithm can achieve real-time performance and handle large audio files efficiently by processing smaller segments individually. It also allows easy parameter tuning and optimization based on each segment's characteristics, hence enhancing noise reduction's effectiveness. It is effective as it also removes pauses, silences and unnecessary sounds making the audio contain only relevant information. The efficiency of the proposed method is evaluated by comparing various metrics such as  Root Mean Square (RMS) energy, Amplitude, Zero Crossing Rate (ZCR) spectral contrast, and spectral flatness. 