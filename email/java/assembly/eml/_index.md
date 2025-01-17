---
title: Generate Reports in EML Files via Java 
weight: 3980
url: /java/assembly/eml/ 
description: Try our On-Premise message report creation APIs to create EML format reports on Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bulk Report Generation in EML Format via Java" h2="Generate EML email messages in bulk without requiring Outlook or Thunderbird." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EML" pfName="Aspose.Email" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" apiHomeLink="https://products.aspose.app/email/family" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/java" installationsDocsLink="https://docs.aspose.com/email/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/java" learnAsLink="https://docs.aspose.com/email/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email" >}}

{{% blocks/products/pf/agp/content h2="How to Generate EML Reports Using Java" %}}

 In order to create EML file reports, we’ll use
 [Aspose.Email for Java](https://products.aspose.com/email/java) 
 API which is a feature-rich, powerful and easy to use assembly API for Java platform. You can download its latest version directly from
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

{{% blocks/products/pf/agp/feature-section-col title="Steps to Generate EML Reports via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Create a template from MailMessage
1.  Add dynamic fields for Subject, To, From & HtmlBody fields
1.  Create a TemplateEngine using the MailMessage object
1.  Create data source and mapping to the template fields
1.  Create messages in bulk using TemplateEngine.Instantiate method
1.  Save messages in EML format

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email for Java supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Generate eml_Upper Messages in Bulk - C#" offSpacer="" %}}

```cs
//create a new MailMessage instance as a template
MailMessage template = new MailMessage();

//add template field to subject
template.setSubject("Hello, #FirstName#");
template.setFrom(MailAddress.to_MailAddress("This email address is being protected from spambots. You need JavaScript enabled to view it."));

//add template field to receipt
template.getTo().addMailAddress(new MailAddress("#Receipt#", true));

//add template field to html body 
//use GetSignment as the template routine, which will provide the same signment.
template.setHtmlBody("Dear #FirstName# #LastName#, Thank you for your interest in Aspose.Network.Have fun with it.#GetSignature()#");

//create a new TemplateEngine with the template message.
TemplateEngine engine = new TemplateEngine(template);

//fill a DataTable as data source
DataTable dt = new DataTable();
dt.getColumns().add("Receipt");
dt.getColumns().add("FirstName");
dt.getColumns().add("LastName");
DataRow dr;
dr = dt.newRow();
dr.set("Receipt", "Nancy.Davolio");
dr.set("FirstName", "Nancy");
dr.set("LastName", "Davolio");
dt.getRows().add(dr);
dr = dt.newRow();
dr.set("Receipt", "Andrew.Fuller");
dr.set("FirstName", "Andrew");
dr.set("LastName", "Fuller");
dt.getRows().add(dr);
dr = dt.newRow();
dr.set("Receipt", "Janet.Leverling");
dr.set("FirstName", "Janet");
dr.set("LastName", "Leverling");
dt.getRows().add(dr);

MailMessageCollection messages;
try{
	//create the messages from the template and datasource.
	messages = engine.instantiate(dt);
}catch (MailException ex){
	//print exception
}
    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Email for Java API" %}}

 Aspose.Email is a Microsoft Outlook and Thunderbird formats parsing solution. One can easily create, manipulate, convert email and storage formats such as MSG, EMLX, EML and MHT. Handling of email attachments, customization of message headers and implementation of different network protocols like POP3, IMAP & SMTP to send & receive emails is much easier. Its a standalone API and does not require Microsoft Outlook or any other software installation. ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Assemble EML" sectionDescription="Check our live demos to [create EML files](https://products.aspose.app/email/assembly/eml) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload EML file and hit the \"Assemble\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant EML file from the link" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EML" readMoreLink="https://docs.fileformat.com/email/eml/" >}}
EML file format represents email messages saved using Outlook and other relevant applications. Almost all emailing clients support this file format for its compliance with RFC-822 Internet Message Format Standard. Microsoft Outlook is the default software for opening EML message types. EML files can be used for saving to disc as well as sending out to recipients using communication protocols.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Report Generation Formats" subTitle="Using Java, one can easily generate reports of multiple formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/assembly/mbox" name="MBOX" description="Electronic Mail Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/assembly/msg" name="MSG" description="Outlook & Exchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/assembly/ost" name="OST" description="Offline Storage Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/assembly/pst" name="PST" description="Outlook Personal Storage Files" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}