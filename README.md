# Portfolio
The following is some of my work from Try.com.

1. Consumer Mobile app
2. Internal admin tool + workflow system
3. Desktop Chrome Extension
4. Web animation
5. Information Architecture + wireframing

---

## 1. Mobile app for Try.com Credit Card
Watch the below screencap of our iOS onboarding where the user
* connects a retailer account
* auto issue, approve credit and inject Try credit card into retailer wallet
* post-onboarding animation explainer

https://user-images.githubusercontent.com/329761/130305045-de754bc9-2345-4595-b9bc-d61d97913d6b.mp4

![mobile-app](https://user-images.githubusercontent.com/329761/130306472-2d293c32-3095-4e2e-870f-0d88fe763ff6.png)
![mobile-app-home](https://user-images.githubusercontent.com/329761/130306700-394ea42d-44c1-4679-ae11-e1d86721e27c.png)
![iphone](https://user-images.githubusercontent.com/329761/130308426-08174d50-43f5-4ef6-8e77-f8ca31cc9fcc.png)

----
## 2. Internal admin tool + workflow
Our internal system at Try.com was built to be as beautiful and easy to use as a high-end consumer app. The workflow tool made use of a rule-based system to push orders through their correct flow depending on their state. I made extensive use of Figma's component system to design each and every possible state in each workflow.

### Key Features of Customer View
* top-right: heads-up display of account verification and trust levels, making use of traffic light colors to surface immediate dangers
* workflow list: the panel on the left was a real-time (websockets) list of open workflow tasks, notice the tab groups C1-C2-C3-C4. Each category has separate flows and risk analysts worked through the list of tasks by category
* center: reduce clutter by using icons where possible (links to stripe/intercom) and traffic light warnings where necessary
* right: latest customer support chat / email conversations with the customer

![Bags Big Screen](https://user-images.githubusercontent.com/329761/130306148-45ba4fd8-b3f1-402f-bb61-a9e2f2cbaf04.png)



### Universal Search
#### Problem
We needed a single interface to search across entities: Customers, Orders,  Merchants. Our customerbase had grown significantly and we needed to have a quick way to visually deduce between customers with similar names.

#### Solution
* The search panel is available in the interface at all times, also via keyboard shortcut `/`. 
* Results ordered by last visit, likely most relevant customer first
* Can immediately see customer's credit score which would be another ditinguishing trait between customers with similar names
* Profile thumbnail helps immediately distinguish customers along with email

![image](https://user-images.githubusercontent.com/329761/130304101-4e342b38-bcb1-404f-a1cc-3cfa0ba072dc.png)



----
## 3. Animation
Here's one of many animations we used over the years. You can read how I made this on "Mastering Nested Looping Animatinos at 60fps" - https://medium.com/@arush/you-too-can-master-the-dark-art-of-60fps-animation-9406a7872770

(this animated gif is a screencap and not indicative of actual perf)
![cc-slider](https://user-images.githubusercontent.com/329761/130305126-6f0d2c03-2b9b-49fa-ac17-acd836ef9096.gif)


-----
## 4. Information Architecture + Wireframing
Here's the Miro board where requirements gathering turned into wireframes and mockups: https://miro.com/app/board/o9J_kzPiudQ=/
<img width="1012" alt="Screen Shot 2021-08-21 at 4 02 16 AM" src="https://user-images.githubusercontent.com/329761/130308470-c3ac245c-7464-4574-891b-cd5c4e042d81.png">


### UML work
![keep-return-flow](https://user-images.githubusercontent.com/329761/130306952-e45b38ec-c2ce-4b5e-a4ba-37e18ea3d45e.png)
![ChromeX E2E Flow](https://user-images.githubusercontent.com/329761/130307878-22d91581-02bd-4f7b-b6b8-093bc6fc1e24.png)


### Wireframe flows
![Onboarding + Try Button Install flows](https://user-images.githubusercontent.com/329761/130306983-a61c63c2-f44f-43b4-bda4-782e6f80f644.png)
![Checkout Flow](https://user-images.githubusercontent.com/329761/130307928-8ac58790-1b3c-4c7e-9c8c-8741e08ea191.png)


----

## 5. Desktop Chrome Extension Onboarding
![Desktop - Website](https://user-images.githubusercontent.com/329761/130308541-622a604c-027f-47ab-91ca-df3886febb75.png)
![MacBook](https://user-images.githubusercontent.com/329761/130306564-435e3711-db53-4a74-ba22-0b24e7f0e665.png)
![MacBook-1](https://user-images.githubusercontent.com/329761/130306478-818d7e62-bb3b-49b5-b54c-746840a58b7e.png)
![MacBook-2](https://user-images.githubusercontent.com/329761/130306480-32be6b62-adf9-4816-aec8-0c7f6b717379.png)
![MacBook-3](https://user-images.githubusercontent.com/329761/130306481-fbe7bea9-4184-477f-b07f-74058c01aebf.png)
![MacBook-4](https://user-images.githubusercontent.com/329761/130306483-c6ca6d3b-31ab-4c7b-9dfe-69d4933a2817.png)
![MacBook-5](https://user-images.githubusercontent.com/329761/130306485-3218e32c-9959-41eb-af94-64b397a8c303.png)
![MacBook-6](https://user-images.githubusercontent.com/329761/130306486-1d17696b-ceea-4d03-96d3-d822058df9bb.png)
![MacBook-7](https://user-images.githubusercontent.com/329761/130306487-6048935c-4727-48db-9277-37df72d646d8.png)
![MacBook-8](https://user-images.githubusercontent.com/329761/130306488-02f4a77a-9bd8-4128-b8ae-477c6e38d57d.png)
![MacBook-9](https://user-images.githubusercontent.com/329761/130306492-f9453a7c-abdd-4f63-9fe0-2bc68ac4ed63.png)
![MacBook-10](https://user-images.githubusercontent.com/329761/130306496-d1e73252-0588-498d-b667-b2d2aa34d2cd.png)
![MacBook-11](https://user-images.githubusercontent.com/329761/130306497-449828de-646d-402f-9af4-d6b3ad7c37f3.png)
![MacBook-12](https://user-images.githubusercontent.com/329761/130306500-9a86c1cd-e931-4c5f-8206-705a2f717ee4.png)
