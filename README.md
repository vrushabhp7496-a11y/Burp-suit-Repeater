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



