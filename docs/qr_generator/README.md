### Project Name : QR Generator

- Repo :

---

Table Of Content

1. [Name of project , Domain , Target Audience](#t1)
2. [Purpose of Project](#t2)

3. [Tools and Technologies](#t3)

   - [Front-End](#t3_1)

   - [Back-End](#t3_2)

   - [DB & Develoyment](#t3_3)

4. [Project Discription in Detail](#t4)

   - [Project Building Flow](#t4_1)

5. [Challenges & Solution](#t6)

6. [Advantages and Disadvantages](#t7)

---

### Name of project , Domain , Target Audience

<a name='t1'></a>
Name Of Project : QR Generator

Domain : Internet Media

Target Audience :

- All Internet Users
- Photo Copy Shops , Share Whatsapp Number in form **QR**
- In College Lecture Share URl instead of **URL**

### Purpose of Project

<a name='t2'></a>

- **Learning** How to Create or Generate QR
  - Can I Create _Whatsapp Phone Number , URL , Text Message_ . **Yes I Can!**
- Build an Web Portal : Where User Can Insert There Whatsapp Number and Create QR . Similarly for URL , Text Message
- Taking Users Input in HTML Form , Generate QR in Back-End and Send QR `png` image in Front-End

### Tools and Technologies

<a name='t3'></a>

- Front-End
  <a name='t3_1'></a>

  | Front-End Technologies | Version |
  | ---------------------- | ------- |
  | HTML                   | 5       |
  | CSS                    | 3       |
  | Bootstrap              | 5.1     |

- Back-End
  <a name='t3_2'></a>

  | Backend-End Technologies | Version |
  | ------------------------ | ------- |
  | Python                   | 3.8.10  |
  | Flask                    | 2.1.3   |
  | qrcode                   | 7.3.1   |

- DB & Develoyment
  <a name='t3_3'></a>

  | Tools       | Name           |
  | ----------- | -------------- |
  | Deployement | PythonAnyWhere |

### Project Discription in Detail

<a name='t4'></a>

#### Execution Flow

1.  Installing Python and Create `Virtual env` and Installing Modules

1.  Create Flask App

1.  Create Routes

1.  Bussiness Logic : Steps

    ```
        1. Front End : In 4 Different HTML Form Like URL , Text Message and UPI . Filling Input and Click on Submit

        2. Back End : The Input parameter will be pass in the Function

        2.1 img = qrcode.make(qr) #This Will Return Type qrcode.image.pil.PilImage

        2.2 img.save(path/qr.png) # Image Will be Save

        3. Front End : send_file(path/qr.png) to User that Will be download to client side
    ```

### Challenges & Solution

<a name='t5'></a>

1. If We Pass No values then Click Page will be loaded and Created Issue
   - The Using Max Length Attribute in the Html Form
2. If Some Pass Wrong . I Will Generated QR but the Wrong
   - _I passed my name in Whatsapp Mobile Number it will be generated QR but not correct_
   - So I added `patterns` or `regular Expression` in the html tag that check User Input in correct manner . If its correct then It will be submited

### Advantages

<a name='t5'></a>

1. Easy and Quickly QR generated
2. No auth Login for generating QR

### Disadvantagea

1. Unable to Check Its URL Correct Or Not
   - If Some one Insert an URL . Its Not Checking URL Exist or Not
2. Similar For Whatsapp Creation to Unable to this Whatsapp Users Exist or not
3. No QR Images Color and Background Color

_All Disadvantage I'll Will be feature for the next Version_
