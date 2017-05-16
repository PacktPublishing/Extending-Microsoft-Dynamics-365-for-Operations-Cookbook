# Extending Microsoft Dynamics 365 for Operations Cookbook
This is the code repository for [Extending Microsoft Dynamics 365 for Operations Cookbook](https://www.packtpub.com/application-development/extending-microsoft-dynamics-365-operations-cookbook?utm_source=github&utm_medium=repository&utm_content=9781786467133), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.

## About the Book
If you are a software developer new to Dynamics 365 for Operations programming or an experienced software engineer migrating from its predecessor, Dynamics AX, this book is an ideal tutorial to help you avoid the common pitfalls and make the most of this advanced
technology. This book is also useful if you are a solution architect or technical consultant, as it provides a deeper insight into the technology behind the solution.

## Instructions and Navigation
The code for Chapter 05 is organized into one folder, Chapter05 and the rest in one separate folder.

The code will look like the following:

```
public void modifiedField(FieldId _fieldId)
{
  super(_fieldId);
  switch (_fieldId)
  {
    case fieldNum(ConWHSVehicleServiceLine, ItemId):
    this.initFromInventTable(
    InventTable::find(this.ItemId));
    break;
  }
}  
```
 
 ## Related Products
* [Microsoft Dynamics AX 2012 Reporting Cookbook](https://www.packtpub.com/application-development/microsoft-dynamics-ax-2012-reporting-cookbook?utm_source=github&utm_medium=repository&utm_content=9781849687720)

* [Programming Microsoft Dynamics™ NAV 2015](https://www.packtpub.com/big-data-and-business-intelligence/programming-microsoft-dynamics%E2%84%A2-nav-2015?utm_source=github&utm_medium=repository&utm_content=9781784394202)

* [Microsoft Dynamics NAV 2015 Professional Reporting](https://www.packtpub.com/big-data-and-business-intelligence/microsoft-dynamics-nav-2015-professional-reporting?utm_source=github&utm_medium=repository&utm_content=9781785284731)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
