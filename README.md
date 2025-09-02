![Header image](https://github.com/Sevastiyan/Sevastiyan/blob/main/sava-bobov-eVa2FK83K6w-unsplash-Sevi.jpg)

> AI Engineer | Biomedical AI Specialist | Full-Stack Developer
>
> Transforming healthcare and interactive systems through innovation in AI, and digital technology.

---
# 🌌 About Me

Not just a data scientist or a full-stack developer; I'm a Generalist passionate about all things tech (such as technology and techno music)! With a unique blend of science, technology, and a knack for innovation, I’m focused on building cutting-edge digital systems for real-world impact.
- Innovating in Digital Health: From smart insoles for gait analysis to real-time AI models for posture.
- Empowering Machines: Teaching them to recognize human movement and make insightful recommendations.
- Delivering on Execution: Building and deploying practical tech solutions for user-facing platforms.

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
> **Objective:** Built a fault-tolerant backend capable of processing millions of bio-signal data points per hour to power real-time sleep detection and personalized insights.
>
> **Tech Stack:** AWS (DynamoDB, Lambda), Next.js, Node.js, Python, Docker, AI Modeling
>
> 📋 **Challenges:**
>
> * Engineered a high-throughput data pipeline handling 2.5M+ bio-signal points/hour with consistent low-latency processing.
> * Integrated AI models for bio-signal analysis, improving sleep pattern detection accuracy.
> * Designed DynamoDB schemas optimized for heavy write loads and time-series queries.
> * Launched a subscription-based feature set with tailored recommendations based on individual sleep profiles.
> * Ensured 99.99% uptime through resilient AWS infrastructure design.
>
> 🎯 **Impact:** Connected thousands of devices into a unified analytics ecosystem, delivering actionable sleep insights to premium users and improving user-reported sleep quality.

### BCG Vital Sign Extraction

> **Company:** [Wethm LLC](https://www.wethm.com), South Korea
>
> **Objective:** Increased the accuracy of heart rate and breathing rate detection from BCG mattress sensors for non-invasive health monitoring.
>
> **Tech Stack:** Python, SciPy, Signal Processing Toolkits, Filter Design, Peak Detection Algorithms
>
> 📋 **Challenges:**
>
> * Developed advanced filtering to suppress micro-movement noise during sleep.
> * Implemented robust peak detection for heartbeat and respiratory cycles in low-SNR conditions.
> * Optimized algorithms for embedded deployment on resource-limited devices.
> * Reduced false positives caused by environmental vibrations and partner movement.
>
> 🎯 **Impact:** Delivered stable, clinically relevant vital sign measurements from contactless sensors, enabling long-term at-home health monitoring without wearable devices.

---

## Clinical Innovation Project – Remote Health Monitoring Through Gait

### IoT-Powered Patient Activity Monitoring

> **Company:** [FlexoSense Pte. Ltd.](https://www.flexosense.com), Singapore
>
> **Objective:** Designed an IoT-enabled gait monitoring platform to help hospitals remotely track patient mobility and recovery.
>
> **Tech Stack:** IoT Sensors, Android (Java), Python (ML Models), AES-256 Encryption, MQTT
>
> 📋 **Challenges:**
>
> * Built a HIPAA-compliant data model using AES-256 encryption to protect patient data.
> * Trained activity detection models achieving 96% accuracy across varied patient profiles.
> * Developed a real-time Android dashboard for hospital staff to monitor gait metrics remotely.
> * Coordinated with healthcare teams in an MOH-funded pilot to align technical design with clinical workflows.
>
> 🎯 **Impact:** Deployed in Singapore’s major hospitals, enabling clinicians to detect mobility decline early and reduce the need for in-person visits, improving recovery outcomes.

### Real-Time Incident Detection System

> **Company:** [FlexoSense Pte. Ltd.](https://www.flexosense.com), Singapore
>
> **Objective:** Built an AI-powered safety monitoring system for industrial environments, detecting incidents in real time to prevent workplace injuries.
>
> **Tech Stack:** IoT Sensors, Android (Java), Python (ML Models), Real-Time Processing
>
> 📋 **Challenges:**
>
> * Developed machine learning models with 98% accuracy in detecting falls and hazardous events.
> * Conducted large-scale field testing to minimize false positives and ensure robustness in diverse conditions.
> * Integrated real-time incident alerts into Android dashboards for safety team response within seconds.
> * Ensured seamless adoption by aligning with existing workplace safety protocols.
>
> 🎯 **Impact:** Reduced workplace hazards through instant detection and response, already in use by industrial clients to protect worker health and safety.

---

## Gait Analysis SDK (POC)

> **Company:** Independent R\&D Project
>
> **Objective:** Created an Android SDK to compute spatiotemporal gait metrics from raw IMU, magnetometer, and pressure sensor data.
>
> **Tech Stack:** Kotlin, Java, Python (Algorithm Prototyping), Low-pass Filtering, Quaternion-based Gravity Compensation, ZUPT Integration
>
> 📋 **Challenges:**
>
> * Implemented quaternion-based gravity compensation for high-accuracy step segmentation.
> * Designed stance phase detection from gyroscope data to enhance temporal metric precision.
> * Developed a modular, lightweight SDK for seamless integration into third-party apps.
> * Validated accuracy across walking speeds, terrains, and footwear types.
>
> 🎯 **Impact:** Provided a reusable foundation for mobile health apps, rehabilitation tools, and sports analytics platforms, supporting precise gait measurement in the field.
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

