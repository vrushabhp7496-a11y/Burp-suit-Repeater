## Welcome back in Burp suite Repeater module.
- In previous Project we have discussed about what is Burp suite
1. Its usage
2. Different modules in burp suite
3. Feature of the burp suit 
4. Burp suit option and many more module related to burp suit 
5. Now in this project wewill discuss about a very important feature in burp suit that is Repeater feature.we are goint to discuss about 
6. Repeater
7. Feataure related to it
8. Practicle example
## Lets start
## Repeater:
----
- This feature in burp suit allows us to modify and resend the request we captured in proxy tool.
- We can send number of request ata aone time to see how website behaves.alternatively we can manually create request and send them using repeater.
- The ability to edit and resend the request multiple time make repeater very useful for webapplication pentesting.
- Lets discuss about the main sections of repeater feature.
- Take alook at screenshot below.
- First of all I turned on proxy tab and captured request sent google.
- Then I sent this request to repeater byr right clicking on it and selecting option SEND TO REPEATER.
- See the screenshot below
- <img width="1174" height="665" alt="Screenshot 2026-05-03 075908" src="https://github.com/user-attachments/assets/aaed0b43-90a5-4477-af30-c33d085c11df" />
---
## Lets see the interface of the repeater tab 
<img width="1911" height="766" alt="Screenshot 2026-05-03 075925" src="https://github.com/user-attachments/assets/c21ff5c4-ad8a-4cab-bb27-5b7f59700c0f" />

---

- The screenshot above with number shows the interface containing main features.lets discuss one by one
1. Request list: Located at the top of it shows the number of reuest list in repeater.
2. Request control: Located below the request klist this tab helps us to send a request,cancle request,and navigate through request history.
3. Request and response view: We can edit the rquest in request view and we can see the response in response tab.response tab is located beside request tab.
4. Layout option: This option helps us to use different types of layouts to view the request and response tab.
5. Inspector tab: ositioned on the right-hand side, the Inspector allows us to analyze and modify requests in a more intuitive manner than using the raw editor.
6. Target: This tab lets us know which site or web we are targeting.

---
## Message analysys toolbar: 
<img width="287" height="69" alt="Screenshot 2026-05-03 084017" src="https://github.com/user-attachments/assets/06a040ed-a33f-44c1-a8eb-14437e27d3b0" />

1. Pretty: This is the default option which takes raw response and slightly edit it to redable format
2. Raw: This option displays unmodified raw response received directly from the server.
3. Hex: By selscting this we can view the response in bit format.
4. Render: This option helps us to visualize how would a web page look in web browser.

---
## INSPECTOR: 
<img width="488" height="407" alt="Screenshot 2026-05-03 084414" src="https://github.com/user-attachments/assets/426178d9-4844-4d8b-86cf-8c4c03017ad1" />

- Inspector is a supplementary feature to the Request and Response views in the Repeater module. It is also used to obtain a visually organized breakdown of requests and responses.
1. Request attributes: In the Request Attributes section, we can change elements related to the location, method, and protocol of the request
2. Request query parameters : This refer to data sent to server via url.
3. Request body parameter: Any data sent regarding POST request is shown in this tab.we can modify request here before sending.
4. Request cookie: This section contain the modifiable cooke sent with each request.
5. Response header: This section displays the headers recieced from the server in response of our request.this is only for seeing purpose we cannot do any changes in this section.

---
## Practical Exapmle: 
1. The Practical example in tryhack room iclude
2. Capturing the request using proxy
3. Send it to repeater
4. Edit and set the value FlagAuthorised: True
5. See the scrrenshots below for requet and response i got
---
<img width="1426" height="664" alt="Screenshot 2026-05-03 092530" src="https://github.com/user-attachments/assets/aca601d2-43a8-4d0e-afab-d37b154bb544" />

---

<img width="709" height="570" alt="Screenshot 2026-05-03 092613" src="https://github.com/user-attachments/assets/a8d078ad-5a93-4ab2-84cd-cb00c3fb9690" />

---
<img width="768" height="358" alt="Screenshot 2026-05-03 092702" src="https://github.com/user-attachments/assets/4a9e837d-ffc8-437b-968c-87874044addd" />

---

<img width="388" height="241" alt="Screenshot 2026-05-03 092733" src="https://github.com/user-attachments/assets/ba6335f4-f99d-4aae-9680-9b1af464e7fe" />

---

## Practical challange 2:
- In this challange we tasked to visit the ip adress provided
- Navigate through products where numeric value endpoint
- Capture this numeric value in Intercepter and send it to repeatre
- Manuplate the value until error 500 occure

  ---

## Motive of this example 2 is
  - To check input validation
  - Error handling - Dos attack
  - Logic flaws
  - Here the most important thing is what should be the valid server response these are as follows
      1. 200 ok
      2. 404 not found
      3. 400 bad request
   
  ---

  For Further analysis see the screenshot below

  ---

  <img width="567" height="89" alt="Screenshot 2026-05-03 093550" src="https://github.com/user-attachments/assets/8ebeae78-84c3-47be-9167-fceb4f85e240" />

  ---

  <img width="1001" height="601" alt="Screenshot 2026-05-03 093605" src="https://github.com/user-attachments/assets/a0399d22-13b8-4b60-892c-410dbd19769a" />

  ---

  <img width="707" height="284" alt="Screenshot 2026-05-03 093755" src="https://github.com/user-attachments/assets/a7a9c91b-690b-4c86-868a-47ea59cbf3fd" />

  ---

  <img width="768" height="552" alt="Screenshot 2026-05-03 093804" src="https://github.com/user-attachments/assets/e8b70eb2-f2d7-4029-b5c4-b84fc8224de2" />


  ---
 ## OUTCOME OF THIS PROJECT IS AS FOLLWS:
 1. WE LEARNED WHAT IS REPEATER
 2. HOW TO CAPTURE REQUEST SEND TO REPEATER
 3. EDIT REQUEST VALUE
 4. TEST INPUT VALIDATION
 5. TEST SERVER RESPONSE TO UNRECCONGNIZED VALUES

---

- We will discuss Repeater once again in Race condition module which is advanced vulnerability.
- We will see another feature of repeater tab in Race condition module.

---

THANK YOIU






