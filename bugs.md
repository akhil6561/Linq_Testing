**Defect1_Description:**   
Confirm Email page is shown for phone number login   

**Steps to reproduce:**   
1. Go to https://linqapp.com/welcome   
2. Enter already registered phone number and click ‘Continue’   
3. Verify if page name is about verifying the phone number   

**Expected result:**   
Page name should be ‘Verify phone number’(this is just an example name.)   

**Actual result:**   
Page name to verify the phone number is shown as ‘Confirm Email’.   


**Defect2_Description:**   
Contact info is not removed from the form after deletion  

**Steps to reproduce:**   
1.Go to https://linqapp.com/welcome and login     
2.Click 'Edit Contact' link   
3.Click 'Add Contact Information' button   
4.Click 'Phone Number' option   
5.Select 'Phone Type, then enter valid phone number and Click 'Save' button   
6.Click 'Edit/Delete' option for phone number   
7.Click 'Delete' button and click 'Delete' on confirmation popup as well   
8.Check if phone number is removed from the form   
  
**Expected result:**   
Phone number should be removed from the form    

**Actual result:**   
Phone number remains on the form and an error is shown on trying to delete again.   
Note: Same issue happens for email, address.. etc.   


**Defect3_Description:**
User is allowed to save phone number with more than 10 digits   

Steps to reproduce:
1.Go to https://linqapp.com/welcome and login     
2.Click 'Edit Contact' link   
3.Click 'Add Contact Information' button   
4.Click 'Phone Number' option   
5.Select 'Phone Type, then enter phone number with 20 digits and Click 'Save' button   

**Expected result:**
User should be shown error saying that the phone number isn’t valid   

**Actual result:**
Phone is updated even though it’s invalid   


**Defect4_Description:**
User is able to create profile without last name and unwanted number is added on name.    

Steps to reproduce:   
1.Go to https://linqapp.com/welcome   
2.Enter a new phone number and click Continue  
3.Enter only first name, email address and click continue   
4.Proceed and and complete the page creation  
5.Check how the first name is shown on profile   

**Expected result:**   
1.User should not be able to create profile without last name   
2.Unwanted number should not be added to the name in profile   

**Actual result:**
User is able to create profile without last name and unwanted number is added on name.   

 

