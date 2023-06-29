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
