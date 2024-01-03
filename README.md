# capstone
Summary:
For my capstone, I wanted to explore data on the National Parks. My specific question was what activities are available in each park. My project will look at the different national parks and create a way to sort through them based on personal preferences centering around activities available in the parks. 

Motivation:
The motivation for this project is to create a tool that would be useful if someone wanted to take a trip to a national park but needed help narrowing it down. Initially I was just going to look at fishing in national parks but I think it will make sense to include other activities.

Steps:
1. The first step was exploring the National Park Service API. I was able to find a list of activities for the National Park Service. Then I was able to look up each activity seperately and find a list of the parks in which you could do that activity. Then I wrote a for loop in order to retrieve this information and make a dataframe that included each national park and which activities were available there. This will allow a potential visitor to pick a park based on the activities they want to do on their trip.

2. The next step I wanted to research was how many visitors go to each park per year for the past 20 years in order to see trends of which parks are more popular. This would allow a visitor to decide if they don't mind visting the heavily trafficked parks or identify a less familiar park if they want to find a place less crowded. I was able to find this information in an excel file. I pulled that file into Python and then had to do a lot of cleaning on it. Then I converted it into a csv file.

3. After looking at this data it was far too big and difficult to break down so I did some research and found that the National Park Service breaks down the U.S. into regions. I was able to find those regions on their website. I opened my activites csv in excel and added the region data and cleaned up the data some more.

4. After finding and clearning the data, I made a Tableau dashboard where you can select the activities you enjoy and then find a park where you can do all your favorite activities.