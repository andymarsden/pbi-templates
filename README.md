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

##### Fiters Pane 
The filters pane is important for non-static data. We use filters to provide users with the ability to interact and analyse data in a more personalised and targeted manner. 

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/5fbf08ca-56fb-4ab0-b577-9fd5aaa7a298)

Having the filters on a pane on the left of the platform gives a prominent display throughout all reports; users will be able to digest and understand the report.

##### Slicers on Filters Pane
Filters tend to be a slicer whether this is a dropdown, vertical list or a slider. 

![slicers_on_filters_pane](https://github.com/andymarsden/pbi-templates/assets/87974094/ce61140c-876a-40db-a223-254e872ea556)

It is very important you get the look and feel of this right. 

Settings: 
- Title: Heading: Heading 3, Font: Segoe ui SemiBold, Font Size: 8px, Font Color: $TextDark
- Slicer Header: Off
- Values: Font: Segoe ui, Font Size: 10px, Font Color: $TextDark, Padding: 4px

##### Informaton icon
The icon gives more information on what exaclty the visual below is showing. 

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/2704ddc3-588a-4cff-8384-5fd5e31b2de5)

You can do this by adding a button, once you have added a button click the button, go to actions in the format pane on the right hand side of power bi, navigate to action and turn it on.

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/d4b49c1b-6548-450b-9d95-8b529a6583af)

Now you will see that tooltip is displayed (should be 'On') - you can add text to the tooltip which will show once hovering over the button you have created, like in the image below.

![tooltip_iicon](https://github.com/andymarsden/pbi-templates/assets/87974094/de0880f0-8fa1-4240-a52f-81e87f479eca)

##### Bookmarks bar
![bookmarks_bar](https://github.com/andymarsden/pbi-templates/assets/87974094/8cb2e9b0-9654-45ba-8942-2f184e5a5f8c)

The bookmarks bar is used to display different views of the current view. 

![image](https://github.com/andymarsden/pbi-templates/assets/87974094/c8743bea-49e2-48d2-b746-01e9a05f9dff)









  
