## Sample Structure

### Project Name : All QR Code Generator

### Repo Name : QR-Generate-Android-App

- Repo : [_view_](https://github.com/one-numan/QR-Generate-Android-App)
- Android Play Store : [_view_](https://play.google.com/store/apps/details?id=com.all_qr_generator.qr_ganerator_android_app&pcampaignid=web_share)

---

Table Of Content

1. [Name of project , Domain , Target Audience](#t1)
2. [Purpose of Project](#t2)

3. [Tools and Technologies](#t3)

   - [Technologies and Version](#t3_1)

4. [Project Discription in Detail](#t4)

   - [Project Building Flow](#t4_1)

5. [Challenges & Solution](#t6)

---

### Name of Project , Domain , Target Audience

<a name='t1'></a>

- Name of Project : All QR Generator
- Domain : Tech
- Category : Productivity
- Target Audience :
  - Person Who Don't to share large text or large Url . Just Create QR and Share that
  - Photo Shops and Cyber Cafes .

### Purpose of Project

<a name='t2'></a>

- Learning , Build and Deployed
- Technologies evolves and Android is a market leader of Mobiles.
- Android App Market is Oceans for Developer .
- So I built and QR Generator Android App using Kotlin. Its very small simple and easy application . Previously, I was built in Web Application that is in Flask using previous fundamental knowledge
- **My Goal** is to learn how basic activity works and
  - How to GUI flows from FrontEnd to BackEnd and
  - Build App and Deployed into PlayStore take a feedback and
  - Improve it on the bases of feedbacks
  - The Re-Build and Then Deployed Update Version

### Tools and Technologies

<a name='t3'></a>

| Technologies                       | Version                         |
| ---------------------------------- | ------------------------------- |
| zxing:core                         | 3.5.3                           |
| journeyapps:zxing-android-embedded | 3.5.1                           |
| Kotlin androidx.core:core-ktx      | 1.12.0                          |
| Android Studio Version             | Electric Eel 2022.1.1 Patch 2   |
| Android Studio Run Time Version    | 11.0.15+0-b204356-9505619 amd64 |
| Target SDK                         | 34                              |
| Minimum SDK                        | 24                              |

### Project Discription in Detail

<a name='t4'></a>

#### Project Building Flow | Steps for Building Project

- Create Project in Android Studion
- Create Empty Activity
- Create UI in _.xml_ Files Or Front End
  - Create Button , Text Field and Images create ID
- Write Backend logic _.kt_ or Activities ,
  - Access Button , Text Field and Images though ID
  - Write Bussiness Logic Call Library and Performs Logic
- Add App Logo
- Create `.apk` Run and Test
- Generate Java KeyStore .jks : that help to update my app
- Generate Signed Bundle `abb` and Deployed on PlayStore

#### Activities , XML , Operations

- I learned that in Web Development we have FrontEnd and BackEnd
- Similar in Android We have **xml** for FrontEnd and **kt** for BackEnd
- All Activity wil be defined in AndroidManifest.xml automatically while creating activity
- Path of Acitiviy :

  - `C:\Users\OneNuman\AndroidStudioProjects\QRGaneratorAndroidApp\app\src\main\res\layout`

- Path Of XML

  - `C:\Users\OneNuman\AndroidStudioProjects\QRGaneratorAndroidApp\app\src\main\java\com\all_qr_generator\qr_ganerator_android_app`

  - so I built 7 Activity and 7 XML Files

    | Activity Name     | XMl Name                    |
    | ----------------- | --------------------------- |
    | MainActivity.kt   | activity_main.xml           |
    | Text_to_qr.kt     | activity_text_to_qr.xml     |
    | URL_to_qr.kt      | activity_url_to_qr.xml      |
    | Msg_to_qr.kt      | activity_msg_to_qr.xml      |
    | Call_to_qr.kt     | activity_call_to_qr.xml     |
    | Whatsapp_to_qr.kt | activity_whatsapp_to_qr.xml |
    | UPI_to_qr.kt      | activity_upi_to_qr.xml      |

### Challenges & Solution

<a name='t5'></a>

- I Faced Lots of Issue **building Signed Gradle Apk**

#### Development Issue

- Android Playstore I used Years ago and While Creating and building `build.gradle` SDK version Old issue
  - Googled Help me a lot
  - at the End, Version Will be updated in build.gradle 's files
- Similar Issue in Dependies . I used older version of Zxing lib that help me build QR 's Offline
  - I used 3.3.3 . So I'll Update it into 3.5.3

#### Feedback's Improvment

- **Fixed in Version 1.1** My Multiple Friend's Feedback .

  - App's has no Title bar is showing in Dark Theme and I didn't add in Light Themes
  - Each background showing black : Dark Theme . Text Not readable
  - Button also showing dark .
  - Input Field is not showing
  - Its Not Look Good
  - Working on Each Issue and Update Fixed Update in version 1.1 Deployed in PlayStore

- **Under Development** Download The QR
  - Showing Download and Save in Device
- **Under Development** Share QR
  - After Generate QR Will Show Share Button
