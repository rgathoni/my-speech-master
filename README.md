## Project Description

This has been an ongoing project where over the course of 2 years, I have explored
different machine learning technologies and independently defined a problem I
would like like to address through the utilization of such tools. Given my interest in social
enterpreneurship and technology, I am motivated to address the challenges faced by minority populations, particularly individuals with disabilities. I focus on enhancing inclusivity and accessibility by harnessing machine learning capabilities in image and language processing. This aligns with my values and represents a meaningful contribution to creating a more inclusive society.

## Building For Impact

The aim of my project is to provide a proof of concept on what it means to build systems that are truly inclusive by developing solutions that naturally accommodate the diverse needs and capabilities of people as they are rather than those that individuals must adapt to. I create a considerate environment to facilitate seamless exchanges between deaf or hard-of-hearing and hearing individuals. While it may be a simple demonstration on the surface, its significance lies in showcasing the potential for technology to prioritize the needs of minority populations, consider diverse perspectives, and design solutions that cater to their specific requirements. Through iterative development, user-centric design principles, and integration of user feedback, I exemplify the iterative process of creating impactful technology that addresses real-world challenges. My POC inspires further exploration and innovation in leveraging technology for social good, emphasizing its transformative power when wielded responsibly and with a focus on creating positive societal impact.

DEMO: [link](https://www.loom.com/share/39db33465cde41598c96ef0ebde2e1b4?sid=ae7f2371-0187-4c31-8958-a2534e655ead)

## BREAKDOWN

Below is a breakdown of the project:

### 1. Image Processing

This contains the model for sign language detection.
Main files include:

1. collect_imgs.py
2. create_dataset.py
3. train_classifier.py
4. inference_classifier.py

## How to run the Object Detection Program

Allow program access to your device's camera and microphone

### 1. Local Setup

Activate the virtual environment with:

```bash
$  venv\Scripts\activate
```

### 2. Navigate to SignDetection

Run the 4 main files in sequence

```bash
$  python collect_imgs.py
$  python create_dataset.py
$  python train_classifier.py
$  python inference_classifier.py
```

#### 3. Exit terminal

Terminate

```bash
$ Ctrl + c
```

### 2. Language Processing

This contains the model for speech-to-text conversion

## How to run the Language Program

### 1. Local Setup

Activate the virtual environment with:

```bash
$  venv\Scripts\activate
```

### 2. Navigate to transcription

Clear npm cache and reinstall dependencies if it doesn’t work

```bash
> npm cache clean –force[npm cache clean --force]
> npm install
> npm start
```

#### 3. Exit terminal

End batch job

```bash
$ Ctrl + c
```

### 3. Integrated Model

This is the integrated model
