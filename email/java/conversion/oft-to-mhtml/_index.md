---
title: Convert OFT to MHTML via Java 
weight: 3350
url: /java/conversion/oft-to-mhtml/ 
description: Sample Java conversion code for OFT format to MHTML file. Use this example code to export message to MHTML within any Web or Desktop Java based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert OFT to MHTML in Java" h2="Native OFT to MHTML conversion using Aspose.Email for Java library, without needing any additional software." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="Aspose.Email" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OFT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/java" installationsDocsLink="https://docs.aspose.com/email/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/java" learnAsLink="https://docs.aspose.com/email/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email" >}}

{{% blocks/products/pf/agp/content h2="How to Convert OFT to MHTML Using Java" %}}

 In order to render OFT to MHTML, we’ll use
 [Aspose.Email for Java](https://products.aspose.com/email/java) 
 API which is a feature-rich, powerful and easy to use conversion API for Java platform. You can download its latest version directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email) 
 and install it within your Maven-based project by adding the following configurations to the pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-email</artifactId>
<version>version of aspose-email API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert OFT to MHTML via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email API makes it easy for the developers to convert OFT file to MHTML in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Load OFT file with Aspose.Email for Java MailMessage.load.
+  Call the save() method.
+  Pass the output file path with (MHTML) file extension.
+  Open MHTML file in compatible program.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email for Java supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with Java Runtime Environment for JSP/JSF Application and Desktop Applications.
-  Get latest version of Aspose.Email for Java directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Convert OFT to MHTML - Java‎" offSpacer="" %}}

```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a MHTML 
message.save("Saved File.mhtml", SaveOptions.getDefaultMhtml());    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="OFT to MHTML Conversion Live Demos" sectionDescription="[Convert OFT to MHTML](https://products.aspose.app/email/conversion/oft-to-mhtml) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your OFT file, it will be converted instantly to MHTML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="About Aspose.Email for Java API" %}}

 Aspose.Email is a Microsoft Outlook and Thunderbird formats parsing solution. One can easily create, manipulate, convert email and storage formats such as MSG, EMLX, EML and MHT. Handling of email attachments, customization of message headers and implementation of different network protocols like POP3, IMAP & SMTP to send & receive emails is much easier. Its a standalone API and does not require Microsoft Outlook or any other software installation. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="OFT" readMoreLink="https://docs.fileformat.com/email/oft/" >}}

Files with .OFT extension represent message template files that are created using Microsoft Outlook. The pre-formatted layout set for message templates is then used for sending out emails with common information to save time. Such files can be generated by creating a new email, adding necessary information and then using the Save As Office Template (*.oft) dropdown from Microsoft Outlook. Users can open the OFT files by double clicking on it and it will open in associated application on that particular system.


        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Files with MHTML extension represent a web page archive format that can be created by a number of different applications. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. Microsoft Windows uses MHTML file format for recording scenarios of problems observed during the usage of any application on Windows that raises issues. The MHTML file format encodes the page contents similar to specifications defined in message/rfc822 which is plain text email related specifications. The actual specifications of the format are as detailed by RFC 2557.


        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert OFT into many other file formats including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/oft-to-eml" name="OFT TO EML" description="Outlook Email Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/oft-to-emlx" name="OFT TO EMLX" description="Apple EMLX Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/oft-to-html" name="OFT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/oft-to-ics" name="OFT TO ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/oft-to-mbox" name="OFT TO MBOX" description="Electronic Mail Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/oft-to-msg" name="OFT TO MSG" description="Outlook & Exchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/oft-to-ost" name="OFT TO OST" description="Offline Storage Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/oft-to-pst" name="OFT TO PST" description="Outlook Personal Storage Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/oft-to-vcf" name="OFT TO VCF" description="Virtual Card Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}