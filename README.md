# pbi-templates



Canvas: 16-9
Verticle alignmnet: Middle
Zoom: 100%


$GreyNeutral: #999999

$TextGrey: #605E5C

$TextDark: #252423

$ContextRed:

$ContextAmber:

$ContextGreen:

Council Green: #B9BF15

ChartBlue: #26B9C0

ChartGrey: #4D5A6F

![image](https://github.com/andymarsden/pbi-templates/assets/46504022/106c8f83-a6e5-4b99-bdb7-14546118a37b)

⭐Tip: Use Format Painter for visuals


#### Key indicators

The key indicators of the dashboard should be isolated and clearly labeled at the top of the dashboard. Try and keep groupings to a maximum of 3 and seperate dynamic from fixed indicators.

We use a multi row card to show single measure values. The has the advantage of left aligning data and providing a bar to give context. The left bar is an ideal vehicle for displaying simple RAG context, if this context is not requried a neaurtal color should be used.

##### Multi Row Card (for single measure)
![image](https://github.com/andymarsden/pbi-templates/assets/46504022/b7b13906-5e21-4c14-b6e4-40033f0f197f)

There should be no content within 10px of the left of the bar, furthest right of the value (or label) and the top and bottom.

Settings: 
- Accent Bar: On, 2px, {neutral:$GreyNeutral, Red: $ContextRed, Amber: $ContextAmber, Green: $ContextGreen}
- Category Labels: On, Font: Segoe Semibold, Font Size: 9px, Font color: $TextGrey
- Call out values: Font: Segoe ui, Font Size: 16px, Font color: $TextGrey

##### Fiters Panel 
The filters panel is important for non-static data. We use filters to provide users with the ability to interact and analyse data in a more personalised and targeted manner. 

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/5fbf08ca-56fb-4ab0-b577-9fd5aaa7a298)

Having the filters on a panel on the left of the platform gives a prominent display throughout all reports; users will be able to digest and understand the report.

##### Slicers on Filters Panel
Filters tend to be a slicer whether this is a dropdown, vertical list or a slider. 

![slicers_on_filters_pane](https://github.com/andymarsden/pbi-templates/assets/87974094/ce61140c-876a-40db-a223-254e872ea556)

It is very important you get the look and feel of this right. 

Settings: 
- Title: Heading: Heading 3, Font: Segoe ui SemiBold, Font Size: 8px, Font Color: $TextDark
- Slicer Header: Off
- Values: Font: Segoe ui, Font Size: 10px, Font Color: $TextDark, Padding: 4px

##### Alligning titles, line and visuals
The allignment is key in how the report looks. When alligned correctly the report looks much neater. 

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/731c2cee-22a4-420c-8176-5d5e33f86d86)

Title - Text box Font(Segoe UI), Font size: 9px, left padding: 0px, all other padding default
Line - Shapes element, Shape Style - Width: 0.5 width, Border: #B3B3B3
Visuals - Allign top of visual with line and allign the left border of the visual with the left side of the line / title

##### Informaton icon
The icon gives more information on what exaclty the visual below is showing. 

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/2704ddc3-588a-4cff-8384-5fd5e31b2de5)

You can do this by adding a button, once you have added a button click the button, go to actions in the format panel on the right hand side of power bi, navigate to action and turn it on.

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/d4b49c1b-6548-450b-9d95-8b529a6583af)

Now you will see that tooltip is displayed (should be 'On') - you can add text to the tooltip which will show once hovering over the button you have created, like in the image below.

![tooltip_iicon](https://github.com/andymarsden/pbi-templates/assets/87974094/de0880f0-8fa1-4240-a52f-81e87f479eca)


The line underneath is a line from the shapes elements. Shape Style - Width: 0.5 width, Border: #B3B3B3

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/3155cce3-0973-4705-82c9-890d7db3cfcc)

##### Top of platform infomation
![image](https://github.com/andymarsden/pbi-templates/assets/87974094/83be6971-c4b0-44a4-bc52-8d1536342d6a)
###### Styles and Fonts
Council Name - Font: Segoe (Bold), Font Size: 8px, Left Aligned (text box)
Team - Font: Segoe UI, Font Size: 10px, Left Aligned (text box)
Social Care Department - Same line / text box as Team, Font: Segoe UI, Font Size: 8.3px
Description - Same text box as Team but line below, Segoe UI, Font Size: 10px
Tab Name - On the section below Team, Social Care Department and Description, Font: Segoe (Bold), Font Size: 8px

##### Bookmarks bar
![bookmarks_bar](https://github.com/andymarsden/pbi-templates/assets/87974094/8cb2e9b0-9654-45ba-8942-2f184e5a5f8c)

The bookmarks bar is used to display different views of the current view.

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/c8743bea-49e2-48d2-b746-01e9a05f9dff)

##### Tornado chart 
![image](https://github.com/andymarsden/pbi-templates/assets/87974094/99846698-04db-4738-99dd-87eeb9d71e43)

A tornado chart is a great way of displaying data. An example of this is age and gender. 

You must change the age to a whole number. To do this follow the instructions below.

###### Instructions: 

1. Click the tornado chart
2. Click the age column in the data panel
3. Navigate to the top of the page and change format to the whole number

As well as this, make sure the colours are the same as in this guide (Female - ChartBlue, Male - ChartGrey). Using these colours ensures consistency throughout all reports. 

Remove the title as it is already clear with what is being visualised by the use of the legend labels.

##### Data Table
![image](https://github.com/andymarsden/pbi-templates/assets/87974094/4928890f-9e94-426b-9bf1-ae6b4d76c0e3)

We use data tables to display related data. Using this format we make it look slick and easy to the eye. 

###### Instructions:
Values: Font: Segoe ui, Font Size: 8px, Text color: $TextDark Background, color: White Alternate, text color: $TextDark
Totals: Font: Segoe ui, Font Size: 8px, bold
Grid: Border: Section: All, Color: ChartGrey, Width: 1
Column Headers: Font: Segoe ui, Font Size: 8px, Text color: $TextDark

##### What a Good One Looks Like VS What a Bad One Looks like

| WAGOLL | WABOLL |
| ------------- | ------------- |
| ![image](https://github.com/andymarsden/pbi-templates/assets/87974094/972a65b8-443e-4988-b689-5f9666958994) | ![image](https://github.com/andymarsden/pbi-templates/assets/87974094/e980faae-6ac9-4517-9691-476e09ffa963)

  |





  
