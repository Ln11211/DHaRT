## DHaRT
DeHazing in Real Time . A Deep neural network approach at dehazing in real time.

# GUI

https://github.com/Ln11211/DHaRT/assets/91385411/1fbd9a4c-963c-4ceb-8319-92f52a6abf92

Objective: The primary objective of this project is to create an artificial intelligence and machine learning (AI-ML) based algorithm that is capable of processing real-time video footage taken during indoor fire incidents.

Challenges: In indoor fire situations, smoke and haze can severely impair visibility, making it extremely challenging for first responders and rescue teams to navigate and assess the situation effectively. Traditional video feeds can become practically useless due to the dense smoke and haze, which hampers the ability to make timely and informed decisions during rescue operations.

Proposed Solution: The proposed solution is to design and develop an intelligent de-smoking/de-hazing algorithm. This algorithm aims to remove or significantly reduce the smoke and haze from real-time video streams captured in indoor fire scenarios. By doing so, it aims to provide clearer and more actionable visual information to aid rescue teams in their operations.

Key Components:

AI-ML Technology: The algorithm is based around a deep neural network architecture- The Encoder-Decoder architecture, which has shown a great promise in image and video enhancement tasks. The use of a Deep learning model is the right solution to this task due to the avilability of datasets and accelerated hardware for implementation of the training algorithms.

Encoder-Decoder Architecture: The algorithm is expected to employ an Encoder-Decoder architecture, which is a common framework for tasks involving image and video processing. It will use this architecture to effectively dehaze and reproduce video frames.

Custom Loss Functions: The design has incorporated custom loss function to ensure that the dehazing process is optimized for the unique challenges posed by indoor fire hazards. The model has trained well along with this Loss function.

Real-time Processing: The algorithm must operate in real-time, meaning it should process video frames as they are captured, making it possible for rescue teams to have immediate access to enhanced video feeds and this is what my alogirthm aims for.

Dataset and Training: The development of the algorithm has involved training it on relevant "Indoor Haze" datasets such as SOTS, RESIDE, REVIDE image datasets, as none could be found specific to indoor fire scenarios. The goal is to teach the algorithm to recognize and remove haze effectively no matter the variability in real time use case.

Deployment Considerations: To be useful in real-world rescue operations, the algorithm must be deployable on hardware that can handle real-time processing, Keeping this in mind, the algorithm works to the best and swiftly with GPU-accelerated hardware. I have also developed the quantized and Pruned version of the Neural Network model for hardware deployment.

Significance:

The successful development of this intelligent de-smoking/de-hazing algorithm has significant implications for improving the effectiveness and safety of indoor firefighting and rescue operations. By enhancing visibility through the removal of smoke and haze, the algorithm can provide valuable insights to first responders, allowing them to make better-informed decisions, locate individuals in distress, and carry out rescue efforts more efficiently.

In summary, the problem statement highlights the pressing need to address the challenges of indoor fire hazards, specifically the visibility issues caused by smoke and haze. The proposed solution involves leveraging AI-ML technologies to develop an intelligent de-smoking/de-hazing algorithm capable of processing real-time video footage, ultimately aiding and enhancing the effectiveness of rescue operations in such scenarios.


Some architectures are:-

# Downsampling-Upsamling Convolution

![model](https://github.com/Ln11211/DHaRT/assets/91385411/5be2a432-2663-4fd4-9ead-c32a9788c82e)

# UNet like

![model](https://github.com/Ln11211/DHaRT/assets/91385411/a9a4e93f-e0be-4fd7-b84a-ad3e7b4880c5)

![image](https://github.com/Ln11211/DHaRT/assets/91385411/4354576a-bbe3-4637-941b-c515236a1466)
