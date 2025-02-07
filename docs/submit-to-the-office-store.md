---
title: Make your solutions available in AppSource and within Office 
description: Upload Office Add-ins, SharePoint Add-ins, Power BI custom visuals, and Microsoft Teams apps to AppSource and make them available in the Office Store within Office.
localization_priority: Priority
---


# Make your solutions available in AppSource and within Office

Microsoft AppSource provides a convenient location for you to upload new Office Web Add-ins, SharePoint Add-ins, Power BI custom visuals, and Microsoft Teams apps that provide solutions for both consumers and businesses. When you add your solution to AppSource, you also make it available in the Office Store within Office. To include your solution in AppSource and within Office, you submit it to the [Seller Dashboard](https://sellerdashboard.microsoft.com/Application/Summary). You need to create an individual or company account and, if applicable, add payout information. For details, see:

- [Register as an app developer](https://partner.microsoft.com/dashboard/account/v3/enrollment/introduction/office). After you create your account, it goes through an approval process.
- [Use the Seller Dashboard to submit your solution to AppSource and within Office](use-the-seller-dashboard-to-submit-to-the-office-store.md).

>[!IMPORTANT]
>We're migrating management of Office solutions from Seller Dashboard to Partner Center. For details, see [Moving from Seller Dashboard to Partner Center](https://developer.microsoft.com/office/blogs/moving-management-of-solutions-from-seller-dashboard-to-partner-center/) and read the [FAQ](partner-center-faq.md).

For information about how to submit Power BI custom visuals to AppSource, see [Publish custom visuals to AppSource and make them available within Office](/power-bi/developer/office-store).

> [!NOTE]
> Office VSTO add-ins and COM add-ins cannot be submitted to AppSource. For more about the distinction between types of Office add-ins, see [How are Office Add-ins different from COM and VSTO add-ins?](https://docs.microsoft.com/office/dev/add-ins/overview/office-add-ins#how-are-office-add-ins-different-from-com-and-vsto-add-ins).

<a name="bk_approval"> </a>
## Approval process

After your account is approved, you can submit your solution to the Seller Dashboard. You can make changes at any point before you submit for approval, but during the approval process, you won't be able to make any changes.

In order for your submission to be approved:

- It must be free of viruses. If you need virus detection software, see the [Microsoft Safety & Security Center](https://go.microsoft.com/fwlink/?LinkId=248711).
- It must not contain inadmissible or offensive material.
- It must be stable and functional.
- Any material that you associate with your apps or add-ins, such as descriptions and support documentation, must be accurate. Use correct spelling, capitalization, punctuation, and grammar in your descriptions and materials.
- If you want a tailored experience for users in a regional store, you can add additional languages so that your add-in appears in another language store with localized metadata. Your service and your add-in manifest must be updated appropriately. You must also provide descriptions for each language you add.
- If your free app or add-in contains an in-app purchase, the AppSource listing for your add-in will reflect this by stating 'Additional purchase may be required' under the pricing options.

For more details about AppSource requirements, see [Validation policies for apps and add-ins submitted to the AppSource](validation-policies.md).

<a name="bk_Validation"> </a>
## Validation process

After you submit your solution:

1. Your submission goes through a series of automated checks to ensure that it complies with the [validation policies](validation-policies.md).

2. The Validation team reviews your submission. This can take 3-5 working days, depending on the volume of submissions in the queue.

   > [!NOTE]
   > The Validation team tests Office Add-ins on all the platforms that the add-in is required to support. For details about supported platforms, see the [Office Add-ins host and platform availability page](/office/dev/add-ins/overview/office-add-in-availability).

   For a seamless validation experience, provide detailed test notes with your submission, including:

   - Information about any sample data your app or add-in needs.
   - Configuration instructions, if required.
   - Information about a test or demo account that your app or add-in needs.

   > [!NOTE]
   > Because our team is located in multiple time zones, we request that you do not configure test accounts that require developer interaction before we can test.

3. When the validation process is complete, you receive a message to let you know that either your submission is approved, or you need to make changes and resubmit it. You can also follow these steps to check the approval status in the Seller Dashboard:

   - Sign in to the [Seller Dashboard](https://go.microsoft.com/fwlink/?LinkId=248605).
   - On the **Manage** tab, your submission status appears under the submission name.
      - If the status is **pending approval**, your submission is still being verified. When it is in this state, you can't update or resubmit it.
      - If the status is **approved**, your submission is approved to be listed in the appropriate marketplaces.

        > [!NOTE]
        > After your submission is approved in the Seller Dashboard, there might be a delay before it is published to the AppSource. After approval, a submission typically appears in the AppSource within 24 hours.

      - If the status is **changes requested**, your submission needs changes to be approved. Choose your submission, and then on the summary page, select **View the add-in report** for details about the required changes.

If you make changes after your submission is approved, it must go through the approval process again.

If you have questions about policies or requirements in your report, you can engage with the AppSource Validation Team via [Stack Overflow](https://stackoverflow.com/search?q=office-store). Tag your question with "Office-Store".

## See also

- [Office Add-ins](/office/dev/add-ins/overview/office-add-ins)  
- [SharePoint Add-ins](/sharepoint/dev/sp-add-ins/sharepoint-add-ins)
