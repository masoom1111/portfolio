# Assignment 3&4

This assignment served a purpose to find a visualization -> Critique it -> Wireframe your solution -> Get First Hand Feedback -> Final Implementation (Revamped Viz)
Here's the process I followed:

## The Original Visualization
I am a huge cricket fan, so the first place I encounter lots of visualization is on cricket articles. ESPN Cricinfo, being one of the most popular ones, I was searching and found a 2015 article. The context of this article in a nutshell: India vs. Australia (World Cup Semifinal) and is India prepared for this encounter?

Source:[ESPNCricinfo](https://www.espncricinfo.com/story/tactics-board-how-india-can-beat-australia-1187863)

Note: The dataset was not available, but as the data points were few I created it in my own excel sheet and used it for my Viz.

![image](https://user-images.githubusercontent.com/30127254/141017585-11c17ae4-819c-493c-adfb-e8b18f20d068.png)

## Critique Phase
First of all, looking at the visualization, you would wonder *"WOW" looks fancy!, there cannot be anything wrong with this visualization*. This was the aim for this visualization, to catch the audience's eye. It does that really well, getting a top score in engagement and visual aesthetics. However does it tell you a story? Are the numbers clear? Or your only focus is on those fancy cricket shots?

The Critique google form filled contains the major chunk of my answers on the above questions and additional critiques for the viz. 
But to summarise them here:
1. Confuses the audience to measure from the helmet or bat
2. Don't understand what the numbers are telling on the first glance, especially the red blocks
3. There is no use of the y-axis if the numbers are already being provided, it makes it even more confusing
4. There is no story or takeaway being conveyed by these numbers. Does it tell Indian batters will do good or bad? That needs to be answered, so the audience has some takeaway from this viz.

So my thought process was to answer all these questions and incorporate a simple graphical viz.

## Wireframe solution via Sketches

First of all, I started with who the audience is?
Audience: Cricket fanatics/enthusiasts, who closely follow the Indian Cricket Team. Also, Cricket wizards, who provide prediction and comments on how the Indian team will do, especially it being a world cup scenario, they would want to use appealing viz to convey their suggestions and be the critics.

I came up with 2 options at first.

Option 1:
![Option1](https://user-images.githubusercontent.com/30127254/141027484-2f8a90a4-a47e-44cc-a530-169a7f0710b9.jpeg)
Firstly I changed the title to something which clearly conveys the meaning of the whole article and what the viz is trying to convey. As Australia has 2 left arm pacers, Mitchell Johnson and Mitchell Starc. The subtitle now contains the actual title of the original cricinfo viz, conveying the point of the averages and dismissals since 2015.

Using a bargraph was the simplest and most convenient option as again the data points were few and having 2 distinct columns for both the categories, batting average and dismissals respectively.
Colors used were Blue and yellow, both being subtle and contrasting.

![Option2](https://user-images.githubusercontent.com/30127254/141027487-509ed4a5-742f-46cc-868e-5294ababfa7e.jpeg)

After thinking a lot, I developed a prototype of using the dimensions in a smarter way, this led me to create a heat map. In the heat map the Size indicates the batting average, so the higher the batting average, more space covered by that block. As heat map provides us the colors to play with, so the colors I used were according to the dismissals. 
As I did not have sketch pens of same color with different shades, I tried to use different colors, but in my head it was having Dark Red- Light Red color scheme (better displayed on Tableau depiction below).

![Option2_Depiction](https://user-images.githubusercontent.com/30127254/141028432-f0445609-c9de-45f8-969a-de638226df5a.PNG)

## Testing the solutions

### Interview 1: (Mechanical Engineer- Cricket Fan -> Suitable Audience)
For option 1
- Can you tell me what you think this is?

Indians Top Order Batting Average against Mitchell Johnson

- Can you describe to me what this is telling you?

It tells that majority of indian batters are good against left arm pace and will be victorious against the Australian left arm pacers.

- Is there anything you find surprising or confusing?

Is the average line for batting average of whom? Is it indians or international? That was confusing.

- Who do you think is the intended audience for this?

Cricket fans and cricket critics.

- Is there anything you would change or do differently?

I would add what the average line exactly means and also add red color for dismissals as wickets in Cricket is always red.

For Option 2 additional comment:
Very confusing, to figure out what is bigger and what is not. Avoid this style as not very user friendly for a fan to analyse such a heat map style. Makes you think a lot to understand what it means.

### Interview 2: (Robotics Intern- Not a Cricket Fan)

- Can you tell me what you think this is?

Basically, tells the batting average and dismissals of different players with their average.

- Can you describe to me what this is telling you?

This tells me Virat Kohli has nice batting average and Shikhar Dhawan is doing bad with dismissals. 

- Is there anything you find surprising or confusing?

Subtitle is confusing as Vs. is not telling me. 
Who is this Johnson threat?

- Who do you think is the intended audience for this?

Cricket analysers and pandits, media and news people. Also, team analyst who prepare strategists.

- Is there anything you would change or do differently?

Remove the Y-axis, change the subtitle wordings of VS. 

For Option 2 additional comment:
Interesting visualization, I like how it uses the scale but not the visualization for general public, makes it more complicated like my robotics graph and suited more for the team strategics/analysts.

## Takeaway from Interview
It was clear to me that the audience which I had in mind did relate to the bar chart and the interviewees also had the same audience in mind. Both of them understood and dealt with batting average first, as that's the more important metric as it has the average line associated with it.

The bar chart was the way to go and the title did convey the takeaway for my intended audience of cricket enthusiasts. It was clearly noticed that the option 2 needs to be shelved. There are a few things that could be changed and made better to make it even more clear and avoid the speculation. 

Incorporating this feedback I made a flourish template as shown below:

<div class="flourish-embed flourish-chart" data-src="visualisation/7771793"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## In-class Peer Feedback

The in-class peers with their expertise in the subject, made me look into it in even more depth.
1. What worked?
Made the visual quite simpler, without the eye catchy imagery and the numbers tell you a story, especially the average line was game-changing.

2. What didn't work?
Too strong color red, deviates attention from batting average to dismissals. 

3. What questions came up?
Does the audience know what Aussie means?
International batting average of what or against whom?

4. What new inspiration arose?
Try separting the viz into 2 with a side by side comparison, to make the eye movement lesser, and not get confused with the batting average line as the dismissals feel left alone in that.

Takeaway: After the peer feedback in class, they helped me enhance the nuances with color of red, making it lighter to ensure the focus is as intended. Also as dismissals was getting lost in the story of batting average, visualizing side by side as grid of bar graphs would add a whole new dimension and convey the much needed story.

So after this I went back to the "drawing board" and sketched what I had in mind. 

![Option3](https://user-images.githubusercontent.com/30127254/141027488-cfbb7976-6573-4783-9598-2d360e57c0b7.jpeg)

## The Solution

After incorporating all the feedback and going back and forth on the drawing board, experimenting with Tableau and Flourish. I am amazed how a minimal data set with eye-appealing visualization can be completely transformed into something simple, clear and informative. 

Here I made it into grid of bar graphs, along with that lightened the red color so the emphasis is not stole by it. Let the batting average line tell a story of the Indian batters are ready with 4 out of 5 above the average line and can use the right graph to see the dismissal statistic. Changed the writing of Title and Subtitle so it makes it more clear even for someone who has less idea about cricket, by avoiding particular bowler name and just saying Australian bowlers.

<div class="flourish-embed flourish-chart" data-src="visualisation/7780469"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# [Portfolio Main Page](https://masoom1111.github.io/portfolio/)

