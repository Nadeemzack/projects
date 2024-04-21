### Project Name : IP Checker

- Repo : [_view_](https://github.com/one-numan/ipChecker)
- Host Url : [_view_](https://onenuman1.pythonanywhere.com)

---

Table Of Content

1. [Name of project , Domain , Target Audience](#t1)
2. [Purpose of Project ](#t2)
3. [Tools and Technologies](#t3)

   - [Front-End](#t3_1)

   - [Back-End](#t3_2)

   - [DB & Develoyment](#t3_3)

4. [Project Discription in Detail](#t4)

   - [2 Different Users Flow](#t4_1)

   - [Execution Flow](#t4_2)

5. [Challenges & Solution](#t6)

---

### Name of project , Domain , Target Audience

<a name='t1'></a>

Name Of Project : IP Checker

Domain : Networking

Target Audience : Networking Student

My Role : Idea to Execute

---

### Purpose of Project

<a name='t2'></a>

- **Learning Purpose** How can I check my Internet Protocal Address ? Or Check any IP address : Build An Web Portal
- One Click Check IP Mobile Network IP Address without Typing `ip config` or `ifconfig` or In Mobile Phone
- Enter Any IP and Check there Information Like Which Location , City , Country , IP Class , Region Code , Timezone etc

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
  | Flask                    | 2.1.2   |
  | Lib                      | 1.0.4   |

- DB & Develoyment
  <a name='t3_3'></a>

  | Tools       | Name           | URL  |
  | ----------- | -------------- | ---- |
  | Deployement | PythonAnyWhere | View |

### Project Discription in Detail

<a name='t4'></a>

#### 2 Different Users Flow

<a name='t4_1'></a>

##### 1. Users Flow : Check Own IP :

1. Home Page
1. Check own IP
1. HTML Table Give an List of Important Information for IP

##### 2. Users Flow : Enter Another IP and Check Information :

1. Home Page
1. Enter IP and Click on Search Icons
1. HTML Table Give an List of Important Information for IP

<a name='t4_2'></a>

#### Execution Flow

1.  Install Python , Flask , Other Required Modules and Libary
1.  create Flask App
1.  create Routes / End Points
1.  Bussiness Logic

        FrontEnd Side : When User Input Any IP in Client Side Form Click on Search Button
        Backend Side  : Take that Input Values
                        Calling Function Libarary ipapi.location(ip=user_input)
                        If No Error will be dictonary_data_of__parameter_and_values
                        That the dictionary_data_ will to send to Client Side
        FrontEnd Side : That Will be represent into Responsive and Beautiful Tables

---

### Challenges & Solution

<a name='t5'></a>

1. If Enter Wrong Ipapi Raise Exception

   > Solution : Add a Try Take If Any Exception raise then Represent `Beautiful Error page`

2. venv is very Important After Binding project and Deployed

   > To Save Unused version will not upload into Deployment Portal
