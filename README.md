# PowerPoin-Addins-PictureTransferFrom-Mobile
This is Office PowerPoint Add-ins Sample, it can help PowerPoint user insert their photes from their Mobile phone to slides

## Quick Start

###Step1. Set Your Enviornment 


Make sure you install VisualStudio 2015(https://www.visualstudio.com/zh-cn/visual-studio-homepage-vs.aspx) and Office Developer Tools for 2015(https://www.microsoft.com/en-us/download/details.aspx?id=49972) 

###Step2. Run Demo

* Debug->Start Debugging or F5
* VS will launch Word or PowerPoint and Add-ins will run in office, Add-ins will give you a 2D image code
* Using your mobilephone to scan this 2D image code
* Then you can select your photes on mobile need transfer to Office, Click upload
* Your Word or PowerPoint Add-in pane will display your selected photoes
* Now, you can insert them into your Word file or PowerPoint


###Step3. Notes

This deme use Document.setSelectedDataAsync method in Office.js, it can snych string/array/html/image etc. you can reference https://dev.office.com/reference/add-ins/shared/document.setselecteddataasync get detail.

