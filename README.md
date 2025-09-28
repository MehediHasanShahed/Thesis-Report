# A Deep Learning Approach of Translating Speech into 3D Hand Sign Language (ASL)

## 📄 Project Overview

This research introduces an AI-driven system that translates spoken English into **3D animated American Sign Language (ASL)**. The system bridges the communication gap between hearing and Deaf or Hard of Hearing (DHH) individuals by leveraging **Automatic Speech Recognition (ASR)**, **Natural Language Processing (NLP)**, and **3D motion generation**. Unlike traditional 2D recognition systems, this project uses 3D avatars to ensure more accurate and natural sign representation.

## 👨‍🔬 Authors

* **Kazi Mahathir Rahman**
* **Naveed Imtiaz Nafis**
* **Mohammad Al Rafi**
* **Mehedi Hasan Shahed**
* **Md. Farhan Sadik**

**Supervisor:** BRAC University, Department of Computer Science and Engineering

## 🧠 Key Technologies

* **Speech-to-Text:** Whisper (Transformer-based ASR)
* **Text-to-Gloss Conversion:** T5, BART, MarianMT, Word2Vec, FastText, BERT
* **Pose Estimation:** OpenPifPaf, ResNet50, RTMPose3D, MediaPipe
* **Animation Modeling:** LSTM, Bi-LSTM, Linear Interpolation
* **3D Rendering & Avatars:** Unity integration
* **Datasets:** WLASL, How2Sign, BookCorpus (custom ASL Gloss Corpus)

## 🚀 System Features

* **Voice Input:** Converts spoken English into text with high accuracy.
* **ASL Gloss Translation:** Maps English text to ASL glosses using advanced NLP.
* **3D Gesture Mapping:** Transforms glosses into anatomical keypoints.
* **Real-time 3D Animation:** Generates smooth and natural ASL gestures with rigged avatars.
* **Dataset Integration:** Trained on large-scale ASL datasets for accurate real-world performance.

## 📊 Outcomes

* Achieved reliable **speech-to-ASL gloss translation** using transformer-based models.
* Developed **3D skeletal models** from video datasets for precise sign representation.
* Implemented **animation smoothing techniques (Bi-LSTM, interpolation)** to ensure natural transitions.
* Demonstrated real-time translation with Whisper + NLP + 3D gesture modeling pipeline.

## 🔍 Highlights

* Real-time accessibility for Deaf and Hard of Hearing (DHH) communities.
* Use of **3D avatars** instead of static/2D systems for greater accuracy.
* Scalable approach integrating NLP and deep learning.
* Cross-domain applications in **education, broadcasting, public services, and healthcare**.

## 📈 Future Enhancements

* Expand dataset coverage to include more ASL signs and phrases.
* Develop **cloud-based deployment** for universal access.
* Incorporate **facial expressions and body posture** for richer sign representation.
* Extend system to support **multilingual sign languages** (e.g., BSL, IS).

## 📚 Citation

If you reference this project in academic work, please cite the following:

Kazi M. Rahman, Naveed I. Nafis, Mohammad A. Rafi, Mehedi H. Shahed, Md. F. Sadik.
"A Deep Learning Approach of Translating Speech into 3D Hand Sign Language (ASL)."
BRAC University, 2025.

## 📬 Contact

For further information or collaboration inquiries:

* **Email:** [kazi.mahathir.rahman@g.bracu.ac.bd](mailto:kazi.mahathir.rahman@g.bracu.ac.bd) | [naveed.imteaz.nafis@g.bracu.ac.bd](mailto:naveed.imteaz.nafis@g.bracu.ac.bd) | [mohammad.al.rafi@g.bracu.ac.bd](mailto:mohammad.al.rafi@g.bracu.ac.bd) | [mehedi.hasan.shahed@g.bracu.ac.bd](mailto:mehedi.hasan.shahed@g.bracu.ac.bd) | [md.farhan.sadik@g.bracu.ac.bd](mailto:md.farhan.sadik@g.bracu.ac.bd)
* **Institution:** Department of Computer Science and Engineering, BRAC University

---

**License:** This project is academic in nature and may be reused for research or educational purposes with proper attribution.
