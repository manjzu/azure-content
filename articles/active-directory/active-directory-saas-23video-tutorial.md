<properties
	pageTitle="Tutorial: Azure Active Directory integration with 23 Video | Microsoft Azure"
	description="Learn how to configure single sign-on between Azure Active Directory and 23 Video."
	services="active-directory"
	documentationCenter=""
	authors="jeevansd"
	manager="femila"
	editor=""/>

<tags
	ms.service="active-directory"
	ms.workload="identity"
	ms.tgt_pltfrm="na"
	ms.devlang="na"
	ms.topic="article"
	ms.date="10/24/2016"
	ms.author="jeedes"/>


# Tutorial: Azure Active Directory integration with 23 Video

The objective of this tutorial is to show you how to integrate 23 Video with Azure Active Directory (Azure AD).  
Integrating 23 Video with Azure AD provides you with the following benefits: 

- You can control in Azure AD who has access to 23 Video 
- You can enable your users to automatically get signed-on to 23 Video (Single Sign-On) with their Azure AD accounts

If you want to know more details about SaaS app integration with Azure AD, see [What is application access and single sign-on with Azure Active Directory](active-directory-appssoaccess-whatis.md).

## Prerequisites 

To configure Azure AD integration with 23 Video, you need the following items:

- An Azure AD subscription
- A 23 Video single-sign on enabled subscription


> [AZURE.NOTE] To test the steps in this tutorial, we do not recommend using a production environment.


To test the steps in this tutorial, you should follow these recommendations:

- You should not use your production environment, unless this is necessary.
- If you don't have an Azure AD trial environment, you can get a one-month trial [here](https://azure.microsoft.com/pricing/free-trial/). 

 
## Scenario Description
The objective of this tutorial is to enable you to test Azure AD single sign-on in a test environment.  
The scenario outlined in this tutorial consists of two main building blocks:

1. Adding 23 Video from the gallery 
2. Configuring and testing Azure AD single sign-on


## Adding 23 Video from the gallery
To configure the integration of 23 Video into Azure AD, you need to add 23 Video from the gallery to your list of managed SaaS apps.

**To add 23 Video from the gallery, perform the following steps:**

1. In the **Azure classic portal**, on the left navigation pane, click **Active Directory**. 

	![Active Directory][1]

2. From the **Directory** list, select the directory for which you want to enable directory integration.

3. To open the applications view, in the directory view, click **Applications** in the top menu.

	![Applications][2]

4. Click **Add** at the bottom of the page.

	![Applications][3]

5. On the **What do you want to do** dialog, click **Add an application from the gallery**.

	![Applications][4]

6. In the search box, type **23 Video**.

	![Applications][5]

7. In the results pane, select **23 Video**, and then click **Complete** to add the application.

	![Applications][25]

##  Configuring and testing Azure AD single sign-on
The objective of this section is to show you how to configure and test Azure AD single sign-on with 23 Video based on a test user called "Britta Simon".

For single sign-on to work, Azure AD needs to know what the counterpart user in 23 Video to an user in Azure AD is. In other words, a link relationship between an Azure AD user and the related user in 23 Video needs to be established.  
This link relationship is established by assigning the value of the **user name** in Azure AD as the value of the **Username** in 23 Video.
 
To configure and test Azure AD single sign-on with 23 Video, you need to complete the following building blocks:

1. **[Configuring Azure AD Single Sign-On](#configuring-azure-ad-single-single-sign-on)** - to enable your users to use this feature.
2. **[Creating an Azure AD test user](#creating-an-azure-ad-test-user)** - to test Azure AD single sign-on with Britta Simon.
4. **[Creating a 23 Video test user](#creating-a-23-video-test-user)** - to have a counterpart of Britta Simon in 23 Video that is linked to the Azure AD representation of her.
5. **[Assigning the Azure AD test user](#assigning-the-azure-ad-test-user)** - to enable Britta Simon to use Azure AD single sign-on.
5. **[Testing Single Sign-On](#testing-single-sign-on)** - to verify whether the configuration works.

### Configuring Azure AD Single Sign-On

The objective of this section is to enable Azure AD single sign-on in the Azure classic portal and to configure single sign-on in your 23 Video application.

**To configure Azure AD single sign-on with 23 Video, perform the following steps:**

1. In the Azure classic portal, on the **23 Video** application integration page, click **Configure single sign-on** to open the **Configure Single Sign-On**  dialog.

	![Configure Single Sign-On][6] 

2. On the **How would you like users to sign on to 23 Video** page, select **Azure AD Single Sign-On**, and then click **Next**.

	![Azure AD Single Sign-On][7] 

3. On the **Configure App Settings** dialog page, perform the following steps:

	![Azure AD Single Sign-On][8] 
 
     a. In the **Reply URL** textbox, type the URL used by your users to sign-on to your 23 Video site (e.g.: *https://britta-simon.23Video.com/saml/login*).

     > [AZURE.NOTE] Active Directory integration using SAML 2.0 is available for all 23 Video users. Please contact the Support at [support@23company.com](mailto:support@23company.com) if you need the related metadata.

     b. Click **Next**.
 
4. On the **Configure single sign-on at 23 Video** page, perform the following steps:

	![Azure AD Single Sign-On][9] 

    a. Click Download certificate, and then save the file on your computer.

    b. Contact your 23 Video support team via [support@23company.com](mailto:support@23company.com), provide them with the downloaded certificate, the **Issuer URL**, the **Single Sign-On Service URL**, the **Single Sign-Out URL**, and then ask them to setup SSO for your 23 Video app. 

    c. Click **Next**.


6. On the Azure classic portal, select the single sign-on configuration confirmation, and then click **Next**. 

	![Azure AD Single Sign-On][10]

7. On the **Single sign-on confirmation** page, click **Complete**.  
  
	![Azure AD Single Sign-On][11]




### Creating an Azure AD test user
The objective of this section is to create a test user in the Azure classic portal called Britta Simon.

![Create Azure AD User][20]

**To create a test user in Azure AD, perform the following steps:**

1. In the **Azure classic portal**, on the left navigation pane, click **Active Directory**.

	![Creating an Azure AD test user](./media/active-directory-saas-23video-tutorial/create_aaduser_09.png)  

2. From the **Directory** list, select the directory for which you want to enable directory integration.

3. To display the list of users, in the menu on the top, click **Users**.

	![Creating an Azure AD test user](./media/active-directory-saas-23video-tutorial/create_aaduser_03.png) 
 
4. To open the **Add User** dialog, in the toolbar on the bottom, click **Add User**. 

	![Creating an Azure AD test user](./media/active-directory-saas-23video-tutorial/create_aaduser_04.png) 

5. On the **Tell us about this user** dialog page, perform the following steps: 

	![Creating an Azure AD test user](./media/active-directory-saas-23video-tutorial/create_aaduser_05.png)  

    a. As Type Of User, select New user in your organization.

    b. In the User Name **textbox**, type **BrittaSimon**.

    c. Click **Next**.

6.  On the **User Profile** dialog page, perform the following steps: 

	![Creating an Azure AD test user](./media/active-directory-saas-23video-tutorial/create_aaduser_06.png) 
 
    a. In the **First Name** textbox, type **Britta**.  

    b. In the **Last Name** textbox, type, **Simon**.

    c. In the **Display Name** textbox, type **Britta Simon**.

    d. In the **Role** list, select **User**.
    e. Click **Next**.

7. On the **Get temporary password** dialog page, click **create**.

	![Creating an Azure AD test user](./media/active-directory-saas-23video-tutorial/create_aaduser_07.png) 
 
8. On the **Get temporary password** dialog page, perform the following steps:

	![Creating an Azure AD test user](./media/active-directory-saas-23video-tutorial/create_aaduser_08.png) 
  
    a. Write down the value of the **New Password**.

    b. Click **Complete**.   

  
 
### Creating a 23 Video test user

The objective of this section is to create a user called Britta Simon in 23 Video.

**To create a user called Britta Simon in 23 Video, perform the following steps:**

1. Sign on to your 23 Video company site as administrator.

1. Go to **Settings**.


2. In **Users** section, click **Configure**.

	![Assign User][400]

3. Click **Add a new user**. 

	![Assign User][401]

4. In the **Invite someone to join this site** section, perform the following steps:

	![Assign User][402]

    a. In the **E-mail addresses** textbox, type Britta Simon's email address in Azure AD.

    b. Click **Add the user**.   


### Assigning the Azure AD test user

The objective of this section is to enabling Britta Simon to use Azure single sign-on by granting her access to 23 Video.

![Assign User][200] 

**To assign Britta Simon to 23 Video, perform the following steps:**

1. On the Azure classic portal, to open the applications view, in the directory view, click **Applications** in the top menu.

	![Assign User][201] 

2. In the applications list, select **23 Video**.

	![Assign User][202] 

1. In the menu on the top, click **Users**.

	![Assign User][203] 

1. In the Users list, select **Britta Simon**.

2. In the toolbar on the bottom, click **Assign**.

	![Assign User][205]



### Testing Single Sign-On

The objective of this section is to test your Azure AD single sign-on configuration using the Access Panel.  
When you click the 23 Video tile in the Access Panel, you should get automatically signed-on to your 23 Video application.


## Additional Resources

* [List of Tutorials on How to Integrate SaaS Apps with Azure Active Directory](active-directory-saas-tutorial-list.md)
* [What is application access and single sign-on with Azure Active Directory?](active-directory-appssoaccess-whatis.md)


<!--Image references-->
[1]: ./media/active-directory-saas-23video-tutorial/tutorial_general_01.png
[2]: ./media/active-directory-saas-23video-tutorial/tutorial_general_02.png
[3]: ./media/active-directory-saas-23video-tutorial/tutorial_general_03.png
[4]: ./media/active-directory-saas-23video-tutorial/tutorial_general_04.png
[5]: ./media/active-directory-saas-23video-tutorial/tutorial_23video_01.png
[25]: ./media/active-directory-saas-23video-tutorial/tutorial_23video_02.png

[6]: ./media/active-directory-saas-23video-tutorial/tutorial_general_05.png
[7]: ./media/active-directory-saas-23video-tutorial/tutorial_23video_03.png
[8]: ./media/active-directory-saas-23video-tutorial/tutorial_23video_04.png
[9]: ./media/active-directory-saas-23video-tutorial/tutorial_23video_05.png
[10]: ./media/active-directory-saas-23video-tutorial/tutorial_general_06.png
[11]: ./media/active-directory-saas-23video-tutorial/tutorial_general_07.png
[20]: ./media/active-directory-saas-23video-tutorial/tutorial_general_100.png

[200]: ./media/active-directory-saas-23video-tutorial/tutorial_general_200.png
[201]: ./media/active-directory-saas-23video-tutorial/tutorial_general_201.png
[202]: ./media/active-directory-saas-23video-tutorial/tutorial_23video_07.png
[203]: ./media/active-directory-saas-23video-tutorial/tutorial_general_203.png
[204]: ./media/active-directory-saas-23video-tutorial/tutorial_general_204.png
[205]: ./media/active-directory-saas-23video-tutorial/tutorial_general_205.png

[400]: ./media/active-directory-saas-23video-tutorial/tutorial_23video_10.png
[401]: ./media/active-directory-saas-23video-tutorial/tutorial_23video_11.png
[402]: ./media/active-directory-saas-23video-tutorial/tutorial_23video_12.png




