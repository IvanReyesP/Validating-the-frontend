# 🚦 Urban Routes - Frontend QA Testing Project

## 📋 Project Description
This project focused on testing the **frontend** of **Urban Routes**, a vehicle reservation application.  
I created **checklists for UI validation** and designed **test cases** to ensure the correct behavior of critical features such as the **reservation button** and the **reservation logic**.  

The testing process also included validating **payment method windows** (add new card, card form validations) to guarantee a smooth and error-free user experience.  
Additionally, the application was tested on **two operating systems** and with **two different screen resolutions** using **browser DevTools**, ensuring consistency and compatibility across environments.  

---

## 🎯 Objectives
- Verify the **usability and design consistency** of the UI.  
- Ensure correct functioning of the **reservation process**.  
- Validate workflows for **payment method selection** and **card addition**.  
- Test cross-platform behavior on **two operating systems**.  
- Check adaptability to **different screen resolutions** with **DevTools**.  
- Detect and report issues to improve user experience.  

---

## 🛠️ Tools & Technologies
- ✅ **Design Validation:** Figma  
- ✅ **Bug Tracking & Reporting:** Jira  
- ✅ **Test Design:** Checklists, Positive & Negative Test Cases  
- ✅ **Environment:** Web application frontend (Urban Routes)  
- ✅ **Compatibility Testing:** Two OS & two screen resolutions (via **DevTools**)  

---

## 🔍 Testing Approach
- Designed **UI checklists** to review layout, responsiveness, and alignment.  
- Created test cases for **"Reserve" button** functionality and reservation flow logic.  
- Validated **payment method screens**, including form field validations when adding a new card.  
- Performed **compatibility testing** on **two operating systems**.  
- Simulated **different resolutions with DevTools** to validate responsive design and layout behavior.  
- Reported inconsistencies and bugs in **Jira** for tracking and resolution.  

---

## 📊 Some Sample Test Cases
| ID | Test Scenario | Input | Expected Result | Status |
|----|---------------|-------|-----------------|--------|
| P-1 | Click on "Reserve" with valid details | Valid trip data | A window with the title "Reserved Car" will appear in the center of the screen. Inside you will find the brand, license plate number, icon, address of the vehicle, as well as the cost of the trip and the "cancel" button. | ⚠️ Bug reported|
| p-2 | Identify the logic of the reserve function if the timer starts counting the time from when the reserve button is clicked | Valid trip data | The “Reserved Car” popup is displayed with the timer counting down the free time below the header. | ✅ Passed |


---

## 🐞 Findings
- Misalignment in **reserved car  window** in one resolution.  
- Reservation button not disabled when mandatory fields were empty.  
- Missing error validation for special characters in cardholder’s name field.  

---

## 📌 Conclusion
Through this project, I reinforced my QA skills by testing **frontend UI/UX**, validating **critical workflows**, and ensuring **cross-platform compatibility**.  
Using **DevTools** allowed me to simulate different environments and resolutions, while **Figma** ensured design consistency and **Jira** facilitated efficient bug tracking.  

---



