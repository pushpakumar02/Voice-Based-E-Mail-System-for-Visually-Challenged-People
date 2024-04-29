# Voice Based E-mail for Visually Challenged People

| CHAPTER NO: | TABLE OF CONTENT |
|-------------|------------------|
| 1           | [Abstract](#abstract)         |
| 2           | [Introduction](#introduction)     |
| 3           | [Problem Definition:](#problem-definition) |
| 4           | [Existing System](#existing-system)  |
| 5           | [Proposed System](#proposed-system)  |
| 6           | [Literature Survey](#literature-survey) |
| 7           | [Requirements](#requirements)     |
|             | - [Hardware Requirements:](#hardware-requirements) |
|             | - [Software Requirements:](#software-requirements) |
|             | - [Functional Requirements:](#functional-requirements) |
| 8           | [Contents](#contents)         |
|             | - [Overview](#overview)       |
|             | - [Research challenges](#research-challenges) |
|             | - [Objectives](#objectives)     |
|             | - [Scope of the project](#scope-of-the-project) |
|             | - [Contributions](#contributions)  |
| 9           | [System Architecture](#system-architecture) |
|             | - [Data Flow Diagram](#data-flow-diagram) |
| 10          | [Python Libraries Used](#python-libraries-used) |
| 11          | [Steps involved in web scraping:](#steps-involved-in-web-scraping) |
| 12          | [Modules](#modules)          |
|             | 1) [Login Module](#login-module)  |
|             | 2) [Validate the voice.](#validate-the-voice) |
|             | 3) [Speech to Text](#speech-to-text) |
|             | 4) [Creating Dashboard for,](#creating-dashboard-for) |
|             | 5) [Compose a Mail](#compose-a-mail) |
|             | 6) [Read Inbox Mails](#read-inbox-mails) |
|             | 7) [Read Sent Mails](#read-sent-mails) |
|             | 8) [Log out Page](#log-out-page)  |
| 13          | [Techniques Used](#techniques-used)  |
|             | 1. [Voice Authentication](#voice-authentication) |
|             | 2. [Text to Speech Conversion](#text-to-speech-conversion) |
| 14          | [Implementation](#implementation)   |
| 15          | [Comparison of Existing and Proposed System](#comparison-of-existing-and-proposed-system) |
| 16          | [Authentication and security](#authentication-and-security) |
| 17          | [Future Scope](#future-scope)     |
| 18          | [Conclusion](#conclusion)       |
| 19          | [References](#references)       |

| CHAPTER NO: | TABLE OF CONTENT |
|-------------|------------------|
| 1           | Abstract         |
| 2           | International Economic Review |
| 3           | Introduction     |
| 4           | Objectives       |
| 5           | Literature Survey |
|             | - Sharma and mittal in their study “prospects of e-commerce in India”. |
|             | - Miyazaki and fernandez (2001) |
|             | - Samadi and ali (2010) |
|             | - Abhijit  mitra |
|             | - D.k.Gangeshwar |
|             | - Martin dodge |
|             | - Vijay  govindarajan |
| 2.1         | Research methodology: |
| 11          | Research Design: |
| 12          | Sampling Design and Data Collection: |
| 13          | Statistical Tools: |
| 14          | Data analysis: |
| 15          | Information Search |
| 16          | ShopBots |
| 17          | Branding and Uniformity among Products |
| 18          | Branding and Distinction among Vendors |
| 19          | The Role of Ignorance |
| 20          | Research Focus |
| 21          | Implications |
| 21          | Customer Relationship Management (CRM) |
| 23          | Patronage Loyalty |
| 24          | Database Marketing |
| 25          | Special Loyalty Programs |
| 26          | Frequency Marketing |
| 27          | Affinity Marketing |
| 28          | Customer Lifetime Value |
| 29          | Corrective Action Plans |
| 30          | Existing System |
| 31          | Proposed System |
|             | Scope of the Project |
| 1.1         | Requirements |
|             | - Hardware Requirements: |
|             | - Software Requirements: |
| 32          | The functional requirements of the project are |
| 33          | The non-functional requirements of the project |
| 34          | Details of Technology |


## Abstract:
We have seen that the inception of the Internet has dramatically revolutionized many fields. The Internet has made the life of people so easy that people today have access to any information they want sitting in their homes. One of the main fields that the Internet has revolutionized is communication. When talking about communication over the Internet, the first thing that comes to our mind is E-mail. 

E-mails are considered to be the most reliable way of communication over the Internet, for sending or receiving important information. But there is a special criterion for humans to access the Internet and the criteria is you must be able to see. 

You must be thinking that what sort of criteria is this, everyone with eyes can see. But there are also specially-abled people in our society who are not gifted with what you have. A survey shows that there are more than 250 million visually challenged people around the globe. That is, around 250 million people are unaware of how to use the Internet or E-mail. 

The only way by which a visually impaired person can send an E-mail is, they have to dictate the entire content of the mail to a third person (not visually challenged ) and then the third person will compose the mail and send it on the behalf of the visually impaired person. But this is not the correct way to deal with this problem. It is very less likely that a visually challenged person can find someone for help every time. 

Although for these reasons specially-abled people are criticized by our society. So, for the betterment of society and giving equal status to such specially-abled people, we have come up with this project idea which allows the user to send mails using voice commands without the need for a keyboard or any other visual things.

In Our Project, the database is considered to be the main pillar of every project. In our application, a database is used to store user details such as name, age, etc. The database here is also used to keep information about the emails sent or received or in the draft.


# Introduction

Every human being is widely accessing knowledge and information and also uses it for communication through the internet. However, blind people face difficulties in accessing these net-based information, also in using any service provided through the internet. Due to its simplicity and accessibility, the Internet is widely used in almost all communication applications. In recent times, numerous applications based on the internet have been developed to make communication more reliable and efficient. Out of these numerous applications, E-mail is the most widely used and reliable way to communicate with each other.

The usage of e-mail is quite easy and lucid for regular users, but when it comes to users with visual defects, the system is yet very difficult to use. The current system is not useful for people with visual defects as the available systems are based on visual perceptions. However, there are significant advancements in technologies nowadays, especially for visually challenged people. The advancement in computer-based accessible systems has opened up many possibilities for the visually impaired across the world in a wide way. Audio-based virtual environments like screen readers and many voice-based search engines have helped blind people to access internet applications immensely. 

The contribution made by this research has enabled blind people to send and receive voice-based e-mail messages with the help of a computer.

## Artificial Intelligence for Speech Recognition

Artificial intelligence (AI) is a technology used for creating intelligent systems and machines that simulate human intelligence. Some artificial intelligence applications include various expert systems, natural language processing (NLP), machine vision, and speech recognition. Natural Language Processing (NLP) involves understanding and analyzing human language such as English by extracting metadata from keywords, emotions, relations, and concepts.

## Problem Definition

The visually challenged people find it very difficult to utilize this technology because using them requires visual perception. However, not all people can use the internet. This is because in order to access the internet you would need to know what is written on the screen. If that is not visible, it is of no use. This makes the internet a completely useless technology for the visually impaired and illiterate people.

## Existing System

Simple e-mail systems are available in which only voice recognition and text-to-speech systems are accessible by remembering the keyboard shortcuts to access. The existing voice-based e-mail system has made use of IVR, Speech to text converter, Mouse click event, and Screen reader. There will be a small icon of a mic on which clicking the user had to speak and his/her speech will be converted to text format, which the blind people would see and read also, as in references.

### Disadvantages:

- User have to use a mouse connected to the computer and should perform mouse click events to send and receive emails.
- In the existing system, they have chosen Web UI as the interface for the system which is not easy for impaired people to use.
- The existing mail services do not provide easy access to visually challenged people because they are in written format or any type of attached information and there is no read-out option to hear the mail that is received to their mail addresses.

## Proposed System

Because using this technology involves visual perception, it is extremely difficult for visually impaired persons to use it. This is because in order to access the internet you would need to know what is written on the screen, which is not possible for a blind person. In this proposed system, it mainly concentrates on four different types of technologies:

- Speech-to-Text (STT): This module collects the speech given by the user and converts it to Text.
- Text-to-Speech (TTS): This converts the response given to the system to Speech.
- Chatbot: For making the conversation more sensible and for giving responses more like a human.
- Mail Communication Module: For sending and receiving emails.

### Advantages:

- Doesn’t need any mouse click events to send and receive emails.
- Purely based on the voice commands given by the user.
- Chatbot is used to make the conversation smooth and more like a human response.
- User-friendly (as Blind person can easily use a web-based application).
- Easy Storage of data.
- More efficient.
- Requires less effort and time.
- The system that we are developing is entirely different from the existing ones. Unlike other systems which focus only on a particular set of people, our system is focused on visually challenged people too.
- It also helps handicapped and illiterate people.

# Literature Survey

In this section, we provide a comprehensive review of the literature on the existing related technical issues. In [2], and in a voice of the architectural email, it is proposed that it helps blind people access the email. The current system is not blind, as it does not give a sound opinion about the reading of its content. The proposed system uses speech recognition, Interactive voice response, and a click of the mouse. In addition, for added security, the purpose, the device is used to authenticate the user. The first module will be registered in the system. This module will collect all of a user's information and tell them what information you will enter. In the second module, the login module, the system prompts the user to enter a user name and a password. Do this with the help of voice commands.
To perform the voice of the check, you will need more tests and voice. The user is then redirected to the inbox page after the registration has been completed. Once you have logged in, the user can carry out the normal operation of the mail system. System Settings: How To Create Email Account, Email, It's Trash. The user can switch between them with the help of voice commands. The paper proposes a system that relies on a system with a voice command, based on that, in contrast to the pre-existing email system. The whole system is, in essence, is based on converting the number to text. Once made use, the implementation of the system will prompt the user to speak commands to make use of the relevant services. If the user wants to access the relevant services, it is necessary to state that this command will work. This program uses the IMAP (Internet Message Access Protocol). This is a standard Internet protocol used by an email to send an email from a mail server over TCP / IP. The main type of activity, the screen, will be the first screen displayed from the beginning of the year. On this screen, waiting for the user to press a single button, and the system will start to receive your voice commands. It's a full-size single button to tap anywhere on the screen. Then, with the help of voice commands, the user can send an email to read it. In [4]. the system uses three main technologies:
- To convert the number to text 
- Text-to-speech. 
- Interactive Voice Response. 

When you are visiting the site for the first time, it needs to register with the help of voice commands. Also, once you register, the user's audio data and a note will be saved in the database. And the user will receive a user id and password after the user logs in to receive an email in such a system. The user interface has been developed with the help of Adobe Dreamweaver CS3. The site is primarily centered on the concept of efficiency and effectiveness. In addition, there is a "Contacts" page, where the user can offer any suggestions or any help if they need it. At the time, one of the e-system is proposed, which is easily accessible for the blind. You can use the voice-to-text converter-text-to-speech converter and the Viterbi algorithm. The algorithmic rule, which is working with the technology, does not find it to be the most appropriate word; as soon as the user says so, so it is, as your guessed word, for a given the word pronounced. The user registers at the site where they are for the first time, the visit to the site. This system will reduce some of the disadvantages of the current system. Sorry, this scheme is the efficiency of the Viterbi algorithm to reduce the number of errors will increase and require more space. a system for the blind and the illiterate is proposed to improve their interaction with the email system. This system eliminates the use of IVR technology that are using screen readers, Braille keyboards. There, we used the speech-to-text and text-to-speech conversion. Voice commands are also used for other activities as well. For registration, you may use your identity, your email address, and your password. This is functionality to use the function that tells PHP to email. This is the library, which you can use to send an email. To obtain the user's email from the IMAP server. This Lash-Morris-Pratt algorithm is used to search for email collection boxes. Thus, the system's environment is clean, the voice-controlled by a feedback system in each step. Sorry, this scheme is that it uses Gmail as a host server so that we can make use of other email services like Yahoo, Google, etc. Proposed a voting scheme, which is based on the PCs and mobile devices for the blind. They are the most important elements found in the system's work in the note below. 

1. G-mail system messages, refer to the buyer's email.
2. RSS-Real simple syndication news 
3. Let's listen to the music 
4. The system's red book and reader 
5. Search for your discs and folders using the bridge's Browser. 

It is a software architecture used for the blind, with easy access to the email and MMS messaging functionality into the operating system. The graphical user interface design can be achieved with the help of voice commands and a mouse, but with the help of the keyboard. RSS feeds are also used along with email, which is simple syndication to distribute a list of headlines, announcements of new products and services. We have also prepared an application for you. Along with email, other apps can be accessed by using a voice command. The authors propose the Tetra-Entry, a blind-friendly email client, to overcome the favorability and the convenience of email activities.
The number of blind people is rapidly increasing, so the research's main goal is to develop a simple, inexpensive, user-friendly, and compact device that allows visually impaired people to use multimedia applications of operating systems such as text, music player, and dialing system by integrating a GSM module. All of the forementioned features are included on a low-cost Raspberry Pi board. At the period, [16], one of the E-Systems that is easily accessible to the blind is proposed. 
You can use the Viterbi method, as well as the voice-to-text and text-to-speech converters. The computational rule that works with the technology does not determine it to be the most acceptable word; yet, as soon as the user says it, it is spoken as your guessed word for a particular word. The user creates an account on the site that they are visiting or the first time. This system will mitigate some of the present system's drawbacks. Sorry, but the Viterbi algorithm's efficiency in reducing the number of errors will increase, requiring more space.  
A solution for the blind and illiterate to better their interaction with the email system is proposed in. This technique eliminates the need for screen readers and Braille keyboards while using IVR technology. Speech-to-text and text-to-speech conversions were utilized there. Voice instructions are also employed for a variety of different tasks. Your identity, email address, and password can all be used to register. This is the ability to use the function that instructs PHP to send an email. This is the email library from which you can send an email. The IMAP server is used to retrieve the user's email. To find email collection boxes.

# Voice Based Technology for the Blind

## Literature Review

Pranjal Ingle et al. (2016) [1] utilized three types of technologies to create the application, namely STT (speech-to-text) where speech is converted to text, TTS (text-to-speech) to convert text to speech, and IVR (interactive voice response) which describes the interaction between the user and the technology in many ways like keyboard or voice message. It also allows the user to interact with the mail system. The main disadvantage includes the usage of high sensitive mics which are mostly not available to all the users.

Jain. V. et al. (2021) [2], proposed a voice-based email system that visually impaired people can use to easily access email. With the aid of technology, this initiative aims to assist blind people in sending and receiving voice mails. The advancements in text-to-voice email delivery for people who are blind or visually impaired are the main topic of this study. This study offers a text-to-voice and voice-to-text email access method for those who are blind. This enables persons who are blind to send mail using voice control instead of a keypad.

Divesh Jethani et al. (2018) [3] proposed a voice-based system for the visually blind with multi-lingual facility. The system provides a good GUI for all types of users. The user will be able to send, receive, read, and delete mail from the mail system. But the main disadvantage includes the usage of mouse clicks, which is necessary at some places of the proposed application.

Dr. S. Brintha et al. [4] proposed a system with TTS and STT to read and record symbolic linguistic representations like phonetic transcriptions. The architecture of the system includes two modules namely interface selection and mailing option, the first module selects the type of users that is blind user or sighted user. And the second module includes the simple mailing options to perform all tasks.

Parkhi Bhardwaj et al. (2016) [5] uses an extra speech recognition technology along with all other converters and IVR to develop the application. The proposed system provides more features than existing GUI. Java was the core programming language used. The application can be used by all types of handicapped people and illiterate people.

## Summary of the Literature Survey

Various technologies to develop a voice-based E-Mail system were discussed in the literature survey. Since existing systems like screen readers have some disadvantages, the proposed work in this model takes the best advantage of technology to use features which have the highest accuracy in capturing voice and displaying contents needed by visually impaired people.

## Requirements

### Hardware Requirements:
- Intel Processor
- At least 2 GB RAM
- At least 60 GB of Usable Hard Disk Space
- Microphone and Speaker

### Software Requirements:
- Python 3.x
- Pip to install Packages
- Pycharm Community Edition
- Windows Operating System

## Functional Requirements

The input/output in this software is in the form of forms, speech, and gestures. The data is saved in tables in a database, which is where the storage process takes place. The computation is done via queries, APIs, and procedures that are designed to take as little time as possible. The user will initially register with the system so that he or she can log in later, similar to how a naive person would do with an existing Gmail account. After successfully registering and logging in, the user will be sent to the main menu, which includes operations like compose, inbox, and trash. After selecting a specific operation, the user will finish the operation by performing the related activities. Finally, the API will conduct tasks by connecting to Google's email account. The data flow diagram depicts the flow of a set of data in accordance with a specific information system paradigm. It's used to sketch out a data system's design and structure without providing processing time alternatives in order, such as yes or no choices in traditional flow chat time.

## Contents

Although our culture blames those who are blind for these reasons, the visually impaired may now use the Internet thanks to a range of dependable and efficient technology. As a result, we have developed this design concept for a voicemail system that is email-friendly and can be used by an eyeless person in order to advance society and grant similar especially suitable people an equal status and respect. This gives blind people the ability to send and receive messages using voice commands. Other visual enhancements or a keyboard are not necessary for this system. This is based on the usage of STS and TTS transformers, or speech to text and text to speech, respectively, for translating spoken words into written and audible forms. The person utilizing this method wouldn't have any prior knowledge of the keyboard's layout, the alphabet's positions, or the locations of the keys. The user will respond after being automatically fed voice commands to carry out certain actions by the system. The user merely needs to correctly follow the directions that the system offers. With the use of voice commands and the suggested technology, visually impaired persons might access emails on their own.

## Overview

The internet has become one of the desired or practical things for daily life. By gaining access to information, facilitating interpersonal interactions, and growing enterprises and associations, it has made people's lives more comfortable. The internet becomes the first luxury for a 24-hour lifestyle. Everyone who uses the data and information on the internet. People's lives are made simpler when they use the internet for communication. The internet has significantly altered the realms of communication. Global e-mail drug users were four billion in 2021, and the figure is expected to rise to 4.6 billion by 2025. In 2021, there were over 306 billion emails sent and received per day globally. For sharing and inputting sensitive or private information, electronic correspondence communication has shown to be the most secure and safest method. To utilise the Internet, a person must meet the prerequisite of being able to see, which is a need that must be satisfied. Because surfing the internet involves visual sense, it has become a scourge for those who are visually impaired. More than 250 million individuals, according to a check, do not know how to use email or internet installations for communication. The only way an eyeless person can utilise all these internet features is if they dictate the entire material to a third party who isn't visually impaired. The third party will then send, receive, and read out the messages at the visually impaired person's request. Although the average person assists the blind in accessing their mail, that isn't the best method to approach the problem. Because the visually impaired individual demands assistance whenever he or she can find it.

# Research Challenges

Emailing doesn't pose a significant challenge to individuals with sight, but it presents considerable difficulties for those without sight due to its interference with work obligations. Audio-based emails are preferred by those without eyes, as they can easily reply to spoken commands. However, there are fewer options available for making this audio-based email accessible to the blind. This voice-based email system is helpful for those without eyes, as it enables them to understand their location. However, users need to remember mouse clicks and keyboard shortcuts, which can pose usability challenges for all users, including the blind. The system is limited to desktop computers and occasionally struggles to properly decode content. Future updates to the system's UI may include new functionality.

## Objectives

The primary goal of this article is to create a voice-based emailing system that enables visually impaired and illiterate persons to use everyday technologies like sending and receiving emails and accessing the internet. With this system, blind users may easily log in by speaking. The main aim of developing this system is to increase the sense of community among those who are blind or visually impaired. Users of all ages can easily access the email system. In the future, this technology may be improved and used for additional services, such as texting and using voice commands to operate other applications, in addition to email.

## Scope of the Project

The development of computer-based accessible solutions has provided many new opportunities for the blind and visually impaired globally. However, utilizing these solutions involves visual sight, making it extremely difficult for visually impaired individuals to use them. The proposed system addresses the weaknesses of the current system. Unlike current systems, the proposed approach is voice command anchored, making it more accessible. The availability of the suggested system is a crucial factor taken into consideration, as it is completely different from the present system.

Python is used to implement the requested task. The focus is on providing basic features like creating, reading, transferring, and reading emails using voice-based instructions. Our method is favorable to all individuals, whether normal, visually handicapped, or illiterate, whereas the current system concentrates more on normal people.

## Contributions

Our contributions are summarized as follows:

1. The STT (Speech-to-Text) module converts recognized speech through the microphone to text and stores it in a variable. Alternatively, it throws an exception.
2. The TTS (Text-to-Speech) module converts text to audio in .mp3 format and plays the created file.
3. GTTS (Google Text-to-Speech) library in Python. This platform-independent module automatically produces an audio file while accepting input in text format along with language and speed parameters. It also reads out messages in emails for the user.
4. The SMTP (Simple Mail Transfer Protocol) module is imported using the keyword smtplib. It is used to connect to Gmail and compose emails, acting as a connection to Gmail to perform other functions as well.

## System Architecture
<img src="https://github.com/Pushpakumar02/VOICE-BASED-E-MAIL-SYSTEM-FOR-VISUALLY-CHALLENGED-PEOPLE/blob/main/images/System%20Architecture.png" />

## Data Flow Diagram
<img src="https://github.com/Pushpakumar02/VOICE-BASED-E-MAIL-SYSTEM-FOR-VISUALLY-CHALLENGED-PEOPLE/blob/main/images/Data%20Flow%20Diagram.png" />

# Python Libraries Used

The proposed system utilizes several Python libraries to implement various functionalities. Here is a list of the libraries used along with their descriptions:

1. **SpeechRecognition**
    - SpeechRecognition is a Python library used for speech recognition, which is essential for many day-to-day applications like home automation and artificial intelligence.
    - It enables the conversion of speech to text and is compatible with microcontrollers such as Raspberry Pi when used with an external microphone.

2. **Pyglet**
    - Pyglet is a powerful library for developing visually rich GUI applications such as games and multimedia on Windows, macOS, and Linux.
    - It supports various features including windowing, user interface event handling, OpenGL graphics, loading images and videos, and playing sounds and music.
    - Pyglet does not require external dependencies or installations, making distribution and installation simpler.

3. **BeautifulSoup4**
    - BeautifulSoup4 is a Python library used for web scraping or web data extraction.
    - It allows parsing HTML content and extracting useful information from websites, making it suitable for various applications including data mining and web automation.

4. **gTTS (Google Text-to-Speech)**
    - gTTS is an easy-to-use tool for converting text to audio, commonly known as the Google Text-to-Speech API.
    - It supports multiple languages and audio speeds, allowing users to generate audio files in mp3 format from input text.

5. **PyAudio**
    - PyAudio is a Python binding for PortAudio, a cross-platform library for audio input and output.
    - It enables recording and playing sound across different platforms such as Windows, macOS, and Linux, making it suitable for various audio applications.

## Speech Recognition

Speech Recognition is crucial for converting spoken language into text, enabling interaction with the system through voice commands.

## Pyglet

Pyglet is a powerful library for developing visually rich GUI applications like games and multimedia.

## BeautifulSoup4

BeautifulSoup4 is used for web scraping, allowing the extraction of useful information from HTML content.

## gTTS (Google Text-to-Speech)

gTTS is used for converting text into audio, providing an easy-to-use tool for generating audio files from input text.

## PyAudio

PyAudio enables audio input and output, facilitating tasks like recording and playing sound across different platforms.

---

## Modules

The proposed system consists of several modules to perform various tasks:

1. **Login Module**
    - This module handles user authentication by verifying the username and password.
    - Users can register, login, and reset their passwords.
    - Face recognition is used for additional security.

2. **Voice Validation**
    - Voice authentication verifies a user based on their unique biometric characteristics, enhancing security.
    - It utilizes neural networks for accurate voice authentication.

3. **Speech to Text**
    - This module converts speech input into text, allowing users to interact with the system through voice commands.
    - It uses the SpeechRecognition library for speech-to-text conversion.

4. **Dashboard Creation**
    - A dashboard is created to display various types of visual data in one place, providing easy access to important information.
    - Dashboards are highly customizable and can include key performance indicators (KPIs) and other business metrics.

5. **Logout Page**
    - This module allows users to securely log out of their email accounts.

Each module serves a specific purpose in the system, contributing to its overall functionality and usability.

# Techniques Used

Voice authentication, text-to-speech conversion, and speech-to-text conversion are crucial techniques employed in the proposed system. Here's an overview of each technique:

## 1. Voice Authentication

Voice authentication, also known as voice recognition or speaker recognition, is a biometric authentication technology that identifies users based on their unique voice patterns. It involves two key types:

### A. Text-dependent
- Requires the user to speak a specific phrase or passphrase.
- The spoken phrase is compared to a pre-recorded sample.
- Used for hands-free mobile authentication, IVR systems, and web applications.

### B. Text-independent
- Does not require a specific phrase for authentication.
- Analyzes various voice characteristics for identification.
- More convenient but requires longer training and testing samples.
- Useful for call centers, IoT devices, and web applications.

### Working of Voice Authentication
- Initial template creation: Templates are created from speech samples for identification.
- Voiceprint extraction: Unique characteristics of a person's speech are extracted.
- Comparison: The voiceprint is compared to stored templates for authentication.
- Voice authentication ensures secure access to systems using unique voice patterns.

### Uses of Voice Authentication
1. **Mobile applications:** Hands-free authentication for mobile devices.
2. **Call centers and IVR systems:** Secure authentication during customer support calls.
3. **Web applications:** Web-based authentication for banking and e-commerce.
4. **Internet of things (IoT):** Secure access to IoT devices using voice.

### Challenges of Voice Authentication
1. **Authentication through audio deep fakes:** Deep fakes pose a threat to voice authentication systems.
2. **Lack of accuracy:** Background noise can affect authentication accuracy.
3. **Text to Speech Conversion:** Challenges in converting text to speech accurately.

## 2. Text to Speech (TTS) Conversion

Text to Speech (TTS) conversion is a technology that converts written text into spoken language. It enables users, especially visually impaired individuals, to access and comprehend digital content more easily.

### Working of Text to Speech Conversion
- Text input: Written text is provided as input to the TTS system.
- Conversion: The system converts the text into spoken language using algorithms.
- Output: The converted text is outputted as speech, usually in the form of an audio file.

### Uses of Text to Speech Conversion
- **Accessibility:** Provides access to digital content for visually impaired individuals.
- **Educational tools:** Assists in learning and comprehension.
- **Global education system:** Aids in delivering educational content globally.

## 3. Speech to Text (STT) Conversion

Speech to Text (STT) conversion is the process of converting spoken language into written text. It enables users to interact with systems and devices through voice commands.

### Working of Speech to Text Conversion
- Speech input: Spoken language is provided as input to the STT system.
- Recognition: The system recognizes and transcribes the spoken language into text.
- Output: The transcribed text is outputted for further processing or action.

### Uses of Speech to Text Conversion
- **Voice commands:** Interacting with systems and devices using voice.
- **Dictation software:** Converting spoken words into text for documentation.
- **Phone applications:** Enabling voice input for various applications.

Each of these techniques plays a crucial role in the proposed system, enhancing accessibility and usability for users.

# Experimental Setup

The proposed system utilizes various techniques and modules to enable accessibility and usability for visually challenged individuals. Here's an overview of the experimental setup:

## A. Speech-to-Text with Artificial Intelligence

Google Cloud Speech-to-Text is used to convert spoken language into text. It provides a robust API with neural network models supporting 120 languages. However, it struggles with streaming or pre-recorded audio.

## B. Text to Speech (TTS) Conversion

Text to Speech conversion is utilized to convert written text into spoken language. It acts as an automatic verbalizer, providing a human-like voice output.

### Structure of a Text-to-Speech Unification System

The synthesis of text involves several stages:
- **Text Processing:** This stage involves tokenizing the text and analyzing token types.
- **Prosody Generation:** Prosody, including inflection factors, phrasing, and accentuation, is generated to provide natural speech.

## C. Processing of Natural Language

This module processes language, focusing on prosody and text analysis.

## D. Digital Signal Processing

Digital Signal Processing converts representative data into audible speech.

## Implementation

### Procedure
The proposed system aims to make email accessible to visually challenged individuals and society as a whole. The system prioritizes user-friendliness for all users, including visually impaired and illiterate individuals.
1. **Registration:** Users register through a form, assisted by voice commands.
2. **Login:** Users log in by speaking their username and password, which is converted from speech to text for authentication.
3. **Accessing Services:** After successful login, users can access various sections like Compose, Inbox, and Sent Mail.
4. **Navigation:** The system prompts users to perform specific operations to access various services, and users interact using voice commands.

The system focuses on providing a seamless experience for all users, ensuring accessibility and usability.

## Output Screenshot
<img src="https://github.com/Pushpakumar02/VOICE-BASED-E-MAIL-SYSTEM-FOR-VISUALLY-CHALLENGED-PEOPLE/blob/main/images/Output_Screenshot.png" />

| SR NO. | EXISTING SYSTEM                                 | PROPOSED SYSTEM                                |
|--------|------------------------------------------------|------------------------------------------------|
| 1.     | Less security.                                 | High Security provided.                        |
| 2.     | Depends on Keyboard.                           | The entire structure is based on IVR - Interactive Voice Response. |
| 3.     | Slow processing.                               | Faster and more efficient.                     |
| 4.     | The disables cannot use the normal mail system. | The disables can use the normal mail system.  |
| 5.     | Blind people are not being able to interact with the web based email system. | They will be able to interact with the web based email system. |
| 6.     | It is insecure in comparison to the progressive system. | It has high security, which makes it more trustable. |
| 7.     | The keyboard is mandatory in this system.      | Because the system is based on IVR (Interactive Voice Response), a keyboard is not required. |
| 8.     | Time-consuming process (Slow execution).       | It is more efficient and faster than a typical system. |
| 9.     | The only person without disabilities can use the system. | Both normal and disabled people can use the system. |
| 10.    | People who are blind are unable to engage with others or use the web-based email system. | The web-based email system will allow blind individuals to engage with it (using voice commands). |

## Authentication and Security

Users with account information such as passwords and usernames are provided due to authentication, ensuring that the user has the right password and username every time they need to sign in to the app. Therefore, this data should be stored in a database for future comparison. For identification, we will apply the control system to the user. Keeping a password straight may be dangerous: Keeping a password straight can be dangerous and a simple and easy way to keep the password simple and show them how to create a table in the database. When the user login request arrives, the server will be called in to see the live load to store the username and password. This information will then be redirected to the password stored in the database. Finally, if the game is successful, the user will be able to access the app. Only passwords stored in plain text can be dangerous and will remain open to attack. With cybercrime, the government steals passwords, and you can block the account. However, one way to save it is to save it by converting it into a non-convertible form and a real password. This process is called hashing.

## Future Scope

There is wide future scope of this system; many enhancements can be done in the system such as including different languages, including functionality of accessing the deleted mails and spam mails. Also, this system can be enhanced such that it can also send attachments which are more beneficial for visually challenged people. This system can be made available to all regional people who are not educated enough and inclusion of different languages will make this system easily accessible. Furthermore, sign language system can also be integrated with the system to make the system more scalable and robust.

## Conclusion

In our Project we proposes a system that will be beneficial for society by allowing disable people also to grow along with society. This project makes visually challenged people able enough to be part of growing digital India by allowing them to communicate via internet and also making life of such people much easier. This system overcomes many drawbacks that were faced by visually challenged people such as sending and receiving emails. Success of this project can make an impact on developers motivating them to make something useful that can help visually challenged or blind people. We have proposed a system which will help the visually impaired people to access email services efficiently. This system will help overcome the drawbacks that were earlier faced by the blind people in accessing emails. We have eliminated the using of keyboard shortcuts along with screen readers which will help reducing the cognitive load of remembering keyboard shortcuts. Also, any naive user who does not know the location of keys on the keyboard need not worry as keyboard usage eliminated. The user only needs to follow the instructions given by the IVR and use mouse clicks accordingly to get the respective services offered.

## References

1. Parkhi Bhardwaj, Gunjan Sethi. "Voice Based E-mail System for Visually Impaired: A Review". International Research Journal of Engineering and Technology (IRJET) on December, volume 12. Posted: 2020.
2. John Klensin, Ned Freed, Marshall, T Rose, Einar, A Stefferud, Dave Crocker. "SMTP Service Extensions". IETF. Posted: 1995-11.
3. K Jayachandran, P Anbunami. "Voice Based Email for Blind People". Published in International Journal of Engineering and Technology. Posted: 2018.
4. Carmel Mary, Belinda, Rupavathy N Mahalakshmi, N. "Voice based e-mail System for Visually Impaired". Published in International Journal of Engineering and Technology. Posted: 2018.
5. A Mamatha, V Jade, J Saravana, A Purshotham, A V Suhas. "Voice Based E-mail System for Visually Impaired". International Journal of Research in Engineering. Posted: 2020.
6. A Belekar, S Sunka, N Bhawar, S Bagade. "Voice Based E-mail for The Visually Impaired".
7. Al Smadi, Takialddin, et al. "Artificial intelligence for speech recognition based on neural networks". Journal of Signal and Information Processing 6.02 (2015): 66.
8. Lazar, Jonathan, et al. "What frustrates screen reader users on the web: A study of 100 blind users". International Journal of Human-Computer Interaction 22.3 (2007): 247-269.
9. December, John. "Units of analysis for Internet communication". Journal of Computer-Mediated Communication 1.4 (1996): JCMC143.
10. Pathan, Naziya, et al. "V-Mail (Voice Based E-Mail Application)" (2019).
11. Symons, Gary Mark, and Kirk David Symons. "Digital media editing interface using a supercursor for selecting media clips for editing". U.S. Patent No. 8,527,879. 3 Sep. 2013.
12. Shabana, T., et al. "Voice based email system for blinds". International Journal of Advance Foundation And Research In Science & Engineering (IJAFRSE) Volume 1 (2015).
13. Al Smadi, Takialddin, et al. "Artificial intelligence for speech recognition based on neural networks". Journal of Signal and Information Processing 6.02 (2015): 66.
14. Senders, Joeky T., et al. "Natural and artificial intelligence in neurosurgery: a systematic review". Neurosurgery 83.2 (2018): 181-192.
15. Collobert, Ronan, et al. "Natural language processing (almost) from scratch". Journal of Machine Learning Research 12.Aug (2011): 2493-2537.
16. G. O. Young. "Synthetic structure of industrial plastics (Book style with paper title and editor)". In Plastics, 2nd ed. vol. 3, J. Peters, Ed. New York: McGraw-Hill, 1964, pp. 15–64.
17. The Radicati website. "Email Statistics Report, 2014-2018". Available: http://www.radicati.com/wp/wpcontent/uploads/2014/01/EmailStatisticsReport-20142018-Executive-Summary.pdf.
18. Ingle, Pranjal, Harshada Kanade, and Arti Lanke. "Voice based e-mail System for Blinds". International Journal of Research Studies in Computer Science and Engineering (IJRSCSE) (2016): 25-30.
19. Isewon, Itunuoluwa, O. J. Oyelade, and O. O. Oladipupo. "Design and implementation of text to speech conversion for visually impaired people". International Journal of Applied Information Systems 7.2 (2012): 26-30.
20. Shakhovska, N., O. Basystiuk, and K. Shakhovska. "Development of the speech-to-text chatbot interface based on Google API". CEUR Workshop Proceedings. Vol. 2386. 2019.
21. Juniper Networks. "IPsec Authentication Solutions". Available: https://www.juniper.net/documentation/en_US/junos/topics/concept/ipsec-authentication-solutions.html.
22. Arlinghaus, Robert, et al. "Understanding the complexity of catch-and-release in recreational fishing: an integrative synthesis of global knowledge from historical, ethical, social, and biological perspectives". Reviews in Fisheries Science 15.1-2 (2007): 75-167.
23. Cole, Ron, et al. "The challenge of spoken language systems: Research directions for the nineties". IEEE transactions on Speech and Audio processing 3.1 (1995): 1-21.


