![Header image](https://github.com/Sevastiyan/Sevastiyan/blob/main/sava-bobov-eVa2FK83K6w-unsplash-Sevi.jpg)

> AI Engineer | Biomedical AI Specialist | Full-Stack Developer
>
> Transforming healthcare and interactive systems through innovation in AI, and digital technology.

---
# 🌌 About Me

Senior AI Engineer building production-grade, low-latency computer-vision and embedded ML systems for health & ergonomics. I design AI/ML solutions, scalable cloud infrastructure, and secure backend systems, so products can give fast, personalized feedback. Currently shipping posture detection on Samsung Smart TVs and architecting a backend for a haptics-enabled ergonomic seat. My expertise spans:
- **Artificial Intelligence & Machine Learning:** Real-time computer vision (pose estimation, gait analysis), biosignal interpretation, and model optimization for edge devices and cloud pipelines.
- **Cloud Engineering:** Architected and deployed large-scale data ingestion, API services, and inference backends on AWS (Lambda, API Gateway, DynamoDB, S3), supporting thousands of concurrent users.
- **Cybersecurity & Data Privacy:** Designed secure, compliant data flows for healthcare pilots (MOH Singapore) and consumer products, ensuring patient and user data confidentiality.
- **Backend Development:** Delivered resilient APIs, streaming pipelines, and subscription-based platforms (Next.js, Node.js, Python) powering real-time analytics and personalized feedback loops.
Across roles at Neurabody, Wethm, and FlexoSense, I’ve deployed systems in production environments ranging from Samsung Smart TVs to clinical hospitals — always focused on reliability and security.

---

# 🗂️ Sevastiyan's Tech Portfolio

## Motion Insight Systems

> **Project:** Real-time Pose Detection & Posture Coaching
>
> **Company:** [Neurabody](https://neurabody.ai), South Korea
>
> **Objective:** Created a real-time full-body posture detection platform for interactive workouts, integrating mobile devices and TVs to deliver AI-driven feedback during exercise sessions.
>
> **Tech Stack:** MediaPipe BlazePose, React, AWS Kinesis Video Streams (WebRTC), Tailwind CSS, Node.js, AWS Lambda
>
> 📋 **Challenges:**
>
> * Designed a low-latency pose estimation pipeline using BlazePose + WebRTC, achieving sub-200ms round-trip time for annotated video feedback.
> * Integrated AWS Kinesis Video Streams for stable, high-quality video communication between devices.
> * Developed a unified rendering layer that merges live video feed with skeletal landmarks on a single canvas for precise alignment.
> * Optimized memory usage and garbage collection to eliminate jank during continuous real-time processing.
> * Built a mobile-to-TV remote control workflow for interactive workouts, ensuring full-body visibility in varying environments.
>
> 🎯 **Impact:** Enabled users to receive instant, accurate posture feedback during fitness and rehabilitation programs. Enhanced engagement through interactive AI coaching, paving the way for fully remote, AI-powered personal training.

---

## Wethm Sleep Intelligence Hub

### Bio-signal Processing & Sleep Analytics

> **Company:** [Wethm LLC](https://www.wethm.com), South Korea
>
> **Objective:** Built the production platform to ingest BCG signals via IoT devices, transform the data for AI inference, and deliver sleep insights to users.
>
> **Tech Stack:** AWS (Lambda, DynamoDB), Node.js / TypeScript, Python, Docker, MQTT, Next.js
>
> **Techniques:** IoT Data Ingestion, Time-series Modeling, API Design, Encrypted Data Pipelines
>
> 📋 **Key Contributions:**
>
> * Implemented MQTT-based ingestion to collect BCG data in real-time and remotely control connected devices.
> * Developed AWS Lambda functions to transform and preprocess incoming data for AI inference.
> * Designed a DynamoDB time-series schema to efficiently store AI outputs and vitals for downstream queries.
> * Built server-side delivery APIs to provide nightly sleep reports, trends, and personalized recommendations.
> * Ensured privacy and reliability with encrypted pipelines and access-controlled endpoints
>
> 🎯 **Impact:** Turned the AI models into a production-ready platform, enabling seamless data flow from devices to AI to client-facing insights at scale..

### Multimodal Sleep AI Pipeline

> **Company:** [Wethm LLC](https://www.wethm.com), South Korea
>
> **Objective:** Developed the core AI pipeline that transforms raw BCG signals into heart rate, breathing rate, and sleep stages, forming the backbone of the company’s sleep analytics system.
>
> **Tech Stack:** Python, Tensorflow, Keras, SciPy
>
> **Techniques:** Signal Processing Toolkits, Filter Design, Peak Detection Algorithms
>
> 📋 **Key Contributions:**
>
> * Architected a multimodal AI pipeline:
>   * **Stage 1**: Classifier extracts heart rate (HR) and breathing rate (BR) from BCG data.
>   * **Stage 2**: Higher-level AI model maps HR + BR into sleep staging and scoring.
> * Deployed server-side descriptive analytics to generate user-friendly insights and tailored sleep recommendations.
> * Implemented robust peak detection for heartbeat and respiratory cycles in low-SNR conditions.
> * Optimized algorithms for embedded deployment on resource-limited devices.

>
> 🎯 **Impact:** Delivered the foundational wearable-free vital-sign and sleep-stage engine that powers downstream analytics and user-facing insights.

---

## Remote Health Monitoring Through Gait

### [Gait Analysis](/projects/my_gait_algorithm/README.md)

> **Company:** [FlexoSense Pte. Ltd.](https://www.flexosense.com), Singapore
>
> **Objective:** Engineered a sensor-fusion gait analysis algorithm that transforms low-cost IoT smart insoles into a research-grade tool, delivering spatiotemporal metrics comparable to the CAREN gold-standard motion analysis system.
>
> **Tech Stack:** Kotlin, Java, Python (Prototyping), Android SDK Development
>
> **Techniques:** Sensor Fusion (IMU, Magnetometer, Pressure Sensors), Low-pass Filtering, Quaternion-based Gravity Compensation, Zero-Velocity Updates (ZUPT), Stance Phase Detection
>
> 📋 **Key Contributions:**
>
> * Designed and implemented the core sensor-fusion algorithm combining IMU, magnetometer, and plantar pressure signals.
> * Applied quaternion-based gravity compensation for robust step segmentation and orientation tracking.
> * Developed stance phase detection from gyroscope data, improving temporal metric precision.
> * Built a lightweight, modular Android SDK for seamless third-party integration.
> * Independently validated against a gold-standard gait lab, demonstrating strong agreement in key spatiotemporal metrics.
>
> 🎯 **Impact:** Elevated smart insoles into a field-ready gait lab, enabling rehabilitation, sports science, and mobile health applications with research-grade precision at a fraction of the cost.

### IoT-Powered Patient Activity Monitoring

> **Company:** [FlexoSense Pte. Ltd.](https://www.flexosense.com), Singapore
>
> **Objective:** Adapted smart insole technology for a Ministry of Health–funded pilot, enabling hospitals to remotely monitor patient mobility and recovery.
>
> **Tech Stack:** IoT Sensors, Android (Java), Python (ML Models), AES-256 Encryption, MQTT
>
> 📋 **Key Contributions:**
>
> * Integrated gait analysis insoles into a secure, hospital-ready monitoring platform.
> * Developed activity detection models with 96% accuracy across diverse patient profiles.
> * Built a real-time Android dashboard for podiatrists and clinicians to visualize gait and mobility trends.
> * Collaborated with healthcare teams to align technical design with clinical workflows during the MOH pilot.
>
> 🎯 **Impact:** Deployed in Singapore’s major hospitals, enabling clinicians to track recovery remotely, detect mobility decline early, and reduce unnecessary in-person visits.

### Real-Time Incident Detection System

> **Company:** [FlexoSense Pte. Ltd.](https://www.flexosense.com), Singapore
>
> **Objective:** Built an AI-powered safety monitoring system for industrial environments, detecting incidents in real time to prevent workplace injuries.
>
> **Tech Stack:** IoT Sensors, Android (Java), Python (ML Models), Real-Time Processing
>
> 📋 **Key Contributions:**
>
> * Developed machine learning models with 98% accuracy in detecting falls and hazardous events.
> * Conducted large-scale field testing to minimize false positives and ensure robustness in diverse conditions.
> * Integrated real-time incident alerts into Android dashboards for safety team response within seconds.
> * Ensured seamless adoption by aligning with existing workplace safety protocols.
>
> 🎯 **Impact:** Reduced workplace hazards through instant detection and response, already in use by industrial clients to protect worker health and safety.



---

# ⚙️ Technologies I Use

|                                                                                                                       Language                                                                                                                        |                                                                                                                                                                                                                           Technology                                                                                                                                                                                                                            |                                                                                                             Framework                                                                                                              |                                                                                                                               Tools                                                                                                                               |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|                                                                         ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)                                                                         |                                                                ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)                                                                | ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) |    ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)    |
| ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) | ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) |         ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)         |                                                         ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)                                                         |
|                                                                       ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)                                                                       |                                                                                                                                                                            ![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)                                                                                                                                                                             |                                                                                                                                                                                                                                    | ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white) ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) |

|                                                                                                                                                                                                        🌩️ Cloud and Deployment                                                                                                                                                                                                         |
|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| ![MongoDb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)  ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) |

---

# 🌱 I’m currently learning:

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=for-the-badge&logo=cypress&logoColor=058a5e)

---
# 💻 My Code in Action

```javascript
const coffeeAndMusic = (goodMusic, coffee) => ({
    dataScience: "📊",
    softwareEngineering: "👨‍💻",
});

const createInnovation = (dataScience, softwareEngineering) => ({
    mobileApps: "📱",
    webPlatforms: "🌐",
    backendServices: "🧮",
    aiModels: "🤖",
});

const launchProducts = () =>
    Promise.resolve({
        products: createInnovation(...coffeeAndMusic("🎧", "☕")),
        growth: "📈",
    });

// Call launchProducts() for something interesting
```
---

# 📫 Connect with Me

<a href="mailto: abc@example.com">![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)</a>
<a href="https://www.linkedin.com/in/sevastiyan-tsvetkov/">![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)</a>
<a href=https://wa.me/821037674724>![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)</a>
<a href=https://signal.me/#p/+6596430016>![Signal](https://img.shields.io/badge/Signal-%23039BE5.svg?style=for-the-badge&logo=Signal&logoColor=white)</a>


---

