# Cece Mini Program Development Plan Report

## Background Research Report for Cece

### 1. Platform Overview

Cece is a mobile application combining **fortune-telling**, **mental health management**, and **social interaction**. It incorporates traditional tools like **Bazi**, **astrology**, and **Tarot card readings** with **psychological support** services, psychological tests, and meditation training. Utilizing **AI algorithms** and **big data**, Cece generates personalized reports for users, aiming to offer comprehensive services in both fortune-telling and mental health. Cece's goal is to create a holistic, interactive community where users can “discover a better version of themselves.”

### 2. Core Features

- **Fortune-telling**: Personalized fate analysis and future predictions based on tools like Bazi, astrology, and Tarot.
- **Mental Health**: Integrated psychological assessments, meditation exercises, and emotional support to help users manage emotions and stress.
- **Social Interaction**: Users can share their fortune-telling results and engage with like-minded individuals, fostering a social network focused on fortune-telling and mental health.

### 3. Market Positioning

Cece primarily targets **young users**, especially those interested in fortune-telling, astrology, and mental health. By combining psychology and fortune-telling, Cece not only serves as a source of entertainment but also offers emotional support and psychological adjustment. This unique positioning gives it an edge over competitors.

### 4. Competitive Advantages

- **Diverse Functional Integration**: Cece combines multiple tools for fortune-telling and mental health, allowing users to experience a variety of services on one platform.
- **Personalized Experience**: AI-driven reports increase user engagement.
- **Psychology and Fortune-telling Fusion**: Unlike typical fortune-telling apps, Cece enhances user value with psychological support.
- **Community Interaction**: Social features promote user engagement and create emotional support networks.

### 5. Future Outlook

Cece aims to deepen its mental health features, offering more psychology-related services while improving the accuracy of its fortune-telling predictions. The platform plans to expand internationally, attracting a broader user base while continually optimizing user experience through data analysis.

### 6. Insights for the Project

Cece's success lies in its integration of diverse features, especially its fusion of **psychology and fortune-telling**. For our project, we can draw inspiration from Cece’s user experience design and social interaction features. By integrating Bazi, astrology, and Tarot, we can introduce psychological assessments and interaction modules to enhance user engagement. Additionally, utilizing AI algorithms and big data can improve the accuracy of personalized analyses and drive the optimization and expansion of data models.

---

# 1. Project Background and Research Report

## 1.1 Background Overview

There is a growing demand for psychological analysis and fortune-telling in modern society, especially among younger users, where astrology and horoscope analysis have gained significant attention. We plan to develop a mini-program that combines **Bazi**, **Ziwei Doushu**, **Six Yao divination**, **astrology and horoscope analysis**, with potential future expansions into **palmistry and face-reading**, meeting the demand for diverse, personalized fortune-telling services.

## 1.2 Market Research

Several astrology and horoscope apps already exist, offering horoscope forecasts and synastry analysis. However, these apps often lack comprehensive fortune-telling or are limited to astrology. Our project not only integrates Bazi and Ziwei Doushu from Chinese fortune-telling but also incorporates astrology and horoscope analysis from the West. This approach fills the gaps in current products and, through modern technology, provides users with multidimensional fate analysis.

---

# 2. Plan Details

## 2.1 Core Features Design

- **Bazi Calculation and Analysis**: Users enter their birthdate and time, and the system automatically calculates their Bazi based on the **Heavenly Stems and Earthly Branches** and **Five Elements**. The results, combined with **Ziwei Doushu**, offer personality analysis, fortune predictions, and insights into areas like marriage and career. Predictions for future events are provided based on **annual** and **monthly cycles**.
- **Astrology and Horoscope Analysis**:
    - **Horoscope Analysis**: Provides users with personality traits, love insights, career trends, and health forecasts based on their zodiac sign, presented through Western astrology principles.
    - **Horoscope Chart Calculation**: A complete personal horoscope chart is generated using the user's birth time and location, revealing inner characteristics, emotional patterns, and future directions through planetary positions and house placements. Key life moments are predicted by analyzing **planetary aspects** and **house placements**.

## 2.2 Liu Yao Divination

- **Coin Identification and Hexagram Generation**: Users upload a photo of tossed coins, and the program uses image recognition technology to generate a Six Yao hexagram. The system calculates **Yao Ci** based on the coin results, producing a full hexagram and offering **I Ching-based** interpretations for decision-making.
- **Detailed Hexagram Interpretation**: The system retrieves relevant hexagram meanings from a database, offering personalized explanations based on user inquiries and predicting the outcome of events.

## 2.3 Data Structure and Information Repository

- **Fortune-telling Database**: A database combining Bazi, Ziwei Doushu, astrology, and other information. Users' personal data is matched with the database to generate unique fortune-telling, horoscope, and divination reports. The database will include parameters like **12 zodiac houses**, **Four Pillars**, and **planetary positions**, supporting dynamic queries.
- **Six Yao Hexagram Database**: A comprehensive database of 64 hexagrams and their interpretations, covering detailed aspects of each hexagram, such as **changing lines** and overall fortune trends, ensuring precise analysis.

## 2.4 Frontend Features and Design

- **User Input Interface**: A simplified interface supports the input of birthdate, time, location, and coin toss images. The interface ensures ease of use, particularly for uploading images and entering fortune-telling data.
- **Results Display Interface**:
    - **Visualized Horoscope**: Offers a detailed chart displaying planetary positions, house placements, and aspects, making horoscope analysis easier for users to understand.
    - **Textual Bazi and Hexagram Interpretations**: Bazi interpretations are presented with clear, simple language, combining charts to explain personality and future trends. The Bazi section will also feature a fortune trend chart, while hexagram interpretations will be progressively explained in relation to specific user queries.

---

## 2.5 Backend Architecture

- **Algorithm Development**:
    - **Bazi and Ziwei Doushu Algorithms**: Construct models based on **Heavenly Stems**, **Earthly Branches**, and **Five Element cycles** to calculate Bazi. These calculations will be integrated with the fortune-telling database to produce detailed, personalized interpretations.
    - **Horoscope Algorithm**: Develop an algorithm that calculates planetary positions based on user-inputted birth time and location. The system will connect with the astrology database to offer personality, career, and love insights.
    - **Six Yao Hexagram Generation Algorithm**: Through image recognition, capture coin toss results and generate hexagrams accordingly. Based on the I Ching’s 64 hexagrams, the system will offer predictive advice in response to user queries.

---

## 2.6 Expansion Features and Future Development

- **Palmistry and Face Reading Analysis** (future development):
    - **Initial Image Recognition Design**: Future functionality will include palmistry and face-reading analysis based on image recognition. By identifying key features, the system will generate analyses regarding personality, health, and destiny.
    - **Data Collection and Model Training**: Develop a palmistry and face-reading dataset to train AI models capable of recognizing and analyzing user features.
- **Social Interaction Feature**: In the future, we plan to add sharing and interaction modules, where users can share their fortune-telling and horoscope results, and exchange insights with others. APIs will support integration with social features, fostering a community centered on fortune-telling and mental health.
- **Mental Health Expansion**: Drawing inspiration from Cece’s mental health offerings, we aim to expand into psychological assessments and guided meditation, offering a more holistic user experience.

---

## 2.7 Interface and Expansion Design

- **Local Scripts and API Integration**: While the initial phase will focus on local scripts, we will design API interfaces for potential integration with **WeChat Mini Programs** and web platforms, ensuring the system is scalable across multiple platforms. The API will support multi-language expansion, further enhancing the user experience.
- **Cross-Platform Data Synchronization**: As users may access the platform across various devices, we will design a system to synchronize data seamlessly across platforms, ensuring consistent access to personal fortune-telling and horoscope data.

## 2.8 Data Security and Privacy Protection

- **User Data Encryption**: All user data (birthdate, location, etc.) will be encrypted during storage and transmission to ensure security.
- **Privacy Protection Policy**: A detailed privacy protection policy will be established during development, ensuring users’ personal information is not misused or leaked. Users will also have control over the visibility of their shared fortune-telling or horoscope results.

---

## 3. Vision and Future Planning

### 3.1 Vision

The core vision of this project is to combine **traditional fortune-telling** with **modern AI technology** to provide users with comprehensive tools for fate analysis, mental health management, and life decision support. We aim to deliver personalized fate interpretations, helping users make more informed decisions at key moments in life. Future expansions will include **palmistry** and **face-reading** tools, building a full-spectrum life guidance platform.
