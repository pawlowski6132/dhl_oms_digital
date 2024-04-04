### Friday 3/8/24
Started this project today. I'm building a site to guide developers building digital OMS tools.

1. Built repository in Github
2. Built static webapp in Azure
3. Built local folder on Personal Dell / One Drive
4. Cloned the repo to that folder
5. Tested that local commit/sync gets uploaded to Azure properly.

### Monday 3/11/24
#### 08:30
For future projects, pay attention to the order you build the physical folder structure locally and the github repository. I build the physical folder locally and then cloned the repository locally and now I have nested folders withthe same name. It's confusing.

Today, I continue to deep-dive further into bootstrap, learning until I'm ready to begin to build a navigation home page for the DSC/AEMCE/Analystics community. I've left the Udemy videos and am looking at a playlist from Youtube: 

[Boostrap Playlist](https://www.youtube.com/watch?v=irfbn103AzE&list=PL4cUxeGkcC9joIM91nLzd_qaH_AimmdAR&index=7)

1. Went through #6, Container
2. Got through 5 minutes of #7, Grid system

I had a heck of a time trouble shooting why my code wasn't displaying the columns. CoPilot didn't help. Went to Google Gemini and it found that the class name I was using (because I typed it wrong) was "background-primary" when that class name doesn't exist. It's "bg-primary"

### Tuesday 3/12/24
Watched a few more youtube videos:

1. Finished #7, Grid System
2. #8 Grid Layout
3. #9 Navbar
4. #10 Cards

## Wednesday 3/13/24
Watched a few more youtube vieos from the Boostrap5 playlist

1. Accordin
2. Lists
3. Icons
1. #14 Forms
2. #15 Tooltips
3. # 16 Modals

## Thursday - 
Jack had my computer at Decca

## Monday 4/1/24
Slowing down and starting to build a navbar and sidebar. I have the basic building blocks but I want to understand how everything's working in greater detail so I can make adjustments without breaking anything.

I have a navbar and sidebar included now.

## Tuesday 4/2/24
Not a lot of work but, nice impact. I was able to find a way to change the background color of the bootstrap navbar component: I put a custom class in a custom.css file and then add that class in the navbar. 

I also changed the navbar type to include a logo which I downloaded and added to the project in the assets file. However, I did have a little trouble showing the jpg because the assets folder was outside of the index.html path so, I had to move the whole assets folder to the srce folder to I can just reference the relative path.

I also found a way to change the sidebar color from black to "light" without using a custom class.

I also just changed the labels around so, now it's starting to take shape.

## Thursday 4/4/24
I'm re-thinking my approach again. Now, I'm just going to build one solution for the DPDB1 and make it really simple with just a nav bar at the top, an image map as the main page to display and then click-outs to the information. Each solution will have it's own page and it will be a channel in the teams site.

I used THIS video to help with the header build
https://www.youtube.com/watch?v=GxwHXxumdQk&t=326

And THIS video to help with the image map creation.
https://www.youtube.com/watch?v=K7lkHyUWEso&t=287s

HERE's a link to the image map making site.
imagemap.org

I got a prototype working but, the coordinates of the map are off. I'll have to muck with that but the POC works and I was even able to embed it into a teams channel.

Also, i had to link the dpdb1.html page to the index page in order for it to load over the internet. i'll fix that later too.

