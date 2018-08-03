---
layout: post
title:      "My First CLI"
date:       2018-08-03 20:59:47 +0000
permalink:  my_first_cli
---


***The Project***

There is a sense of accomplishment with completing my first "independant" project, but there is also a great sense of relief! I am excellent at following directions, so each of the other lessons before this one was *easier* because there was a specific format that I followed with step-by-step directions on how to complete the labs. This lesson was about choosing a topic that interests me and then starting from scratch. Starting from scratch is great because I get to choose my topic and how it is going to look, but it is also daunting because I have to choose one topic that interests me and code all the details on how it is going to look!

I chose something that relates to the humane society because animals are an important part of my life and because there are so many animals that need help and homes and this is a topic that is heartfelt for me. I worked with a specific shelter in transporting animals from "high-kill" shelters in the southeastern US to "no-kill" shelters in the northeastern US. To continue to be able to save animals and help them to become adopted these shelters need donations to be able to afford to transport the animals as well as house and board them once they arrive. This is what gave me the idea for my project.

I chose to use the Hornell Humane Society website for this project at this url: [https://www.hornellanimalshelter.org/donate.html](http://)

I chose this website not only because I think this is something worthy of more awareness and support, but also because I can get basic and detailed information on the same page. I thought this would meet the requirements for the project without making it too complicated. What is interesting about this is that in hindsight, if I had chosen something that was a little more detailed, it might have been slightly less complicated...

***My Roadblocks***

The examples I looked at on how to complete this project took a url and then used HTML/CSS selectors to parse what was needed to pull the information. My project only takes one url and then to pull the information you use the selectors. I was able to get the information I wanted for the headings, but it took a bit of coding to get it into an ordered list. The biggest challenge was in going to the next level and getting the unordered list under each heading. The selectors are not descriptive and are exactly the same for all the headings, so it was a challenge to make it all work the way I wanted it to work. I'm happy that my code *works* and I am looking forward to learning how to make it more elegant as I move forward in class.

***The Process***

I wrote out on paper what I wanted the CLI to do from the user's perspective and then how I thought the process would work in coding it out and what I wanted the code to say. After using Bundler to create my files I set up my environment file and my cli, scraper and supplies classes. 

*CLI:*
The CLI (command-line interface) welcomes the user and asks what type of donation they are interested in making. It gives them the option to make the following choices: 1 Financial donation, 2 Supplies donation, Exit. When they choose option 1 the user is given the address to send a check. When they choose option 2 they are given the list of categories from which they can choose to donate some type of item that is needed at the shelter like so:
```
Here are the types of supplies needed:
1. Toys & Enrichment
2. Office Supplies
3. Cleaning Supplies
4. Food & Treats
5. Kennel Care
6. More!
```
The user will then choose another number to see the list of items for each category. When the user is finished, they will type exit and the CLI will thank the user and exit the program.

*Scraper*
The Scraper class contains the methods that will take the information off the website and organize it into readable lists for the numbered list of headings and the list of items that falls into each heading category.

*Supplies*
The Supplies class contains the object information for the headings and arranges them in an array so they can be used to make the numbered list for the next choice the user makes in the CLI.

I learned so much going through this process and I also realized that I know much more than I thought I did! In the end, it was less complicated than I expected it to be, even though it took me longer than I hoped it would. I think that I would have been done sooner if I hadn't worried so much about how difficult it might be...

Lesson learned: Just do it and keep doing it and let it happen!
