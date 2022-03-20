# Assignment 1: Build and deploy a custom Google Map for a non-profit organization
It's common to find that organizations want a useful map that match the rest of their website, but don't have access to Esri software. This assignment demonstrates how to create an embed-ready map that doesn't require knowledge about or the use of propiertary Esri software.

## Choosing an organization & generating its color palette
For this assignment I selected the Breathe Project, a non-profit advocacy group that provides information on air quality in the Pittsburgh area. To ensure that the map I built would match the look and feel of the Breathe Project's existing website, I took a representative screenshot for reference.

![Breathe Project Color Sample](https://user-images.githubusercontent.com/92963323/159184287-19da4ff5-fef8-4280-b7d8-16b4be307027.png)

With this in mind, I uploaded this color sample to Canva to generate the hex codes necessary to replicate the website colors in my map.

![Screen Shot 2022-03-20 at 4 22 36 PM](https://user-images.githubusercontent.com/92963323/159184525-922729d2-1859-4c49-81a2-d86d3cd0089e.png)

## Summarizing design decisions
In Google's Map Styling Wizard, I chose the Standard theme and in the "MORE OPTIONS" window changed the color codes according to the hex codes I created using Canva.

![Screen Shot 2022-03-20 at 7 36 48 PM](https://user-images.githubusercontent.com/92963323/159190942-945ec92c-3458-427f-a101-3489f692a468.png)

In designing this map I tried to create an output that would fit seamlessly into the Breathe Project's current color theme. Since Pittsburgh has a lot of waterways and parks, represented by light colors, I wanted to contrast these areas with darker land without overshadowing the important underlying features. I used dark blue and slate blue for administrative land parcels and natural landscape, respectively, and to draw attention to these designated points of interest I went back into Canva and created a bright blue shade based on that of the Breathe Project website's toolbar. I did the same thing for park features, creating a light green based on the leaves shown in the original screenshot I took from the Breathe Project. I adjusted default shades of yellow and orange to signify transit services while matching the rest of the Breathe Project color palette and largely retained some built-in colors for certain areas, adjusting them only slightly to fit the overall theme. Comparing the map that I created and the Breathe Project website I think that the two fit well together; despite the contrast the map has a lightness to it that blends well with the Breathe Project's look.

![Screen Shot 2022-03-20 at 7 38 38 PM](https://user-images.githubusercontent.com/92963323/159190964-133062c0-b6ad-4f4f-8341-b9c6562b635e.png)

Go [here](/jsoncode1.md) to view the JSON code for this map.
