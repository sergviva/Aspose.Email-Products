---
title: Convert PST to VCF via C++ application 
weight: 1250
url: /cpp/conversion/pst-to-vcf/ 
description: Sample C++ conversion code for PST document to VCF format. Use example code for batch PST to VCF conversion within any C++ Application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert PST to VCF in C++" h2="High performance PST to VCF conversion using Aspose.Email for C++ library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="VCF" pfName="Aspose.Email" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PST" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/cpp" installationsDocsLink="https://docs.aspose.com/email/cpp" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/cpp" learnAsLink="https://docs.aspose.com/email/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert PST to VCF Using C++" %}}

 In order to convert PST to VCF, we’ll use
 [Aspose.Email for C++](https://products.aspose.com/email/cpp) 
 API which is a feature-rich, powerful and easy to use document manipulation and conversion API for C++ platform. You can download its latest version directly, just open
 [NuGet](https://www.nuget.org/packages/aspose.email) 
 package manager, search for
 **Aspose.Email.Cpp** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert PST to VCF via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email API makes it easy for the developers to convert PST file to VCF in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Load PST file with PersonalStorage::FromFile.
+  Call the SaveAs() method having two parameters.
+  Output VCF file and FileFormat::Vcf as parameters.
+  VCF file will be saved at the specified path.
+  Open VCF file in compatible program.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email for C++ supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
-  Aspose.Email for C++ DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Convert PST to VCF - C++‎" offSpacer="" %}}

```cs
// Load the Outlook PST file
System::SharedPtr<PersonalStorage> personalStorage = PersonalStorage::FromFile(L"Outlook.pst");
// Get the Contacts folder
System::SharedPtr<FolderInfo> folderInfo = personalStorage->get_RootFolder()->GetSubFolder(L"Contacts");
// Loop through all the contacts in this folder
System::SharedPtr<MessageInfoCollection> messageInfoCollection = folderInfo->GetContents();
    
{
    auto messageInfo_enumerator = (messageInfoCollection)->GetEnumerator();
    decltype(messageInfo_enumerator->get_Current()) messageInfo;
    while (messageInfo_enumerator->MoveNext() && (messageInfo = messageInfo_enumerator->get_Current(), true)){
        // Get the contact information
        System::SharedPtr<MapiContact> contact = System::DynamicCast<Aspose::Email::Outlook::MapiContact>(personalStorage->ExtractMessage(messageInfo)->ToMapiMessageItem());
        
        // Save to disk in vCard VCF format
        contact->Save(L"Contacts\\" + contact->get_NameInfo()->get_DisplayName() + L".vcf", Aspose::Email::Outlook::ContactSaveFormat::VCard);
    }
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PST to VCF Conversion Live Demos" sectionDescription="[Convert PST to VCF](https://products.aspose.app/email/conversion/pst-to-vcf) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PST file, it will be converted instantly to VCF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="About Aspose.Email for C++ API" %}}

 Aspose.Email is a Microsoft Outlook and Thunderbird formats parsing solution. One can easily create, manipulate, convert email and storage formats such as MSG, EMLX, EML and MHT. Handling of email attachments, customization of message headers and implementation of different network protocols like POP3, IMAP & SMTP to send & receive emails is much easier. Its a standalone API and does not require Microsoft Outlook or any other software installation. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PST" readMoreLink="https://docs.fileformat.com/email/pst/" >}}

Files with .PST extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. User information is stored in folders of different types that include emails, calendar items, notes, contacts, and several other file formats. PST files are used for archiving emailing data offline that can be later loaded and viewed in various applications.


        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="VCF" readMoreLink="https://docs.fileformat.com/email/vcf/" >}}

VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. The format is widely used for data interchange among popular information exchange applications. Most operating systems such as Windows and MacOS come with default applications to create and open these files. A single VCF file can contain contact information for one or multiple contacts. A VCF file usually contains information such as contact's name, address, phone number, email, birthday, photographs and audio in addition to a number of other fields. Being supported by email clients and services, there is no loss of data during the transfer of contacts via using the vCard format. The media type for VCF file format is text/vcard.


        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PST into many other file formats including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/pst-to-eml" name="PST TO EML" description="Outlook Email Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/pst-to-emlx" name="PST TO EMLX" description="Apple EMLX Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/pst-to-html" name="PST TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/pst-to-ics" name="PST TO ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/pst-to-mbox" name="PST TO MBOX" description="Electronic Mail Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/pst-to-mhtml" name="PST TO MHTML" description="Web Page Archive Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/pst-to-msg" name="PST TO MSG" description="Outlook & Exchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/pst-to-oft" name="PST TO OFT" description="Outlook Email Templates" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/pst-to-ost" name="PST TO OST" description="Offline Storage Files" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}