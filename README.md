# My Learning Journey

Welcome!, this is a personal space where I share my learning progress and thoughts about things. If for some reason you find this repo, I hope you find it useful. :smile:

To make things neater and more organized for myself, I will be making it in sync with my dev blog on [dev.to](https://dev.to/). Can be found [here](https://dev.to/irakan) for better categorization and easier navigation.

## Why am I doing this? :thinking:
They say that writing things down helps you remember things better. I'm doing this to help me remember what I've learned and to reflect on my progress. It will organize my thoughts and help me see the bigger picture. I also hope that this will help me become a better writer.

> - "I write to discover what I know." - Flannery O'Connor


## Current Skill Levels as of 1st January 2024 (01/01/2024) :calendar: ( this list is not exhaustive, but it highlights the main skills I have ) :computer:

| Skill                                        | Level                  |
|----------------------------------------------|------------------------|
| PHP (Laravel) ❤️                                | █████████░ (9/10)    |
| PHPUNIT Testing                              | █████████░ (9/10)    |
| JavaScript (Vue.js)                          | ████████░░ (8/10)    |
| Laravel Inertia.js                           | ████████░░ (8/10)    |
| CSS (Tailwind CSS)                           | ██████░░░░ (6/10)  *(Note: Not a designer, but can make things look good)* |
| SQL (MySQL)                                  | ████████░░ (8/10)    |
| NoSQL (MongoDB)                              | ███████░░░ (7/10)  |
| Git                                          | ████████░░ (8/10)    |
| Linux (Ubuntu) + Bash Scripting              | ███████░░░ (7/10)    |
| Docker                                       | ███████░░░ (7/10)    |
| WSL2 (Windows Subsystem for Linux) ❤️           | ███████░░░ (7/10)    |
| VSCode (Visual Studio Code)  ❤️                 | ████████░░ (8/10)    |
| REST API                                     | █████████░ (9/10)    |
| OOP (Object Oriented Programming)            | █████████░ (9/10)    |
| Github Actions (CI/CD)                       | ███████░░░ (7/10)    |
| S3 (Amazon Simple Storage Service)           | ███████░░░ (7/10)    |
| Mermaid (Diagramming and Charting Tool) + Chatgpt :exploding_head: | █████████░ (9/10) |
| Started learning Python for the past 2 months (Still a beginner) | ████░░░░░░ (4/10) |
Apache KFKA | ████░░░░░░ (4/10) |


## Monthly Progress :chart_with_upwards_trend: ( I will update throughout each month, whenever I learn something new )
## Fomat will be as follows:
### Month/Year (MM/YYYY)
- **Day/Month/Year (DD/MM/YYYY)** 

    Topics: (List of topics that I will write about)
    - Learned about this
    - Learned about that
    - Learned about this other thing

    **Resources:**
    - [Link to resource 1](https://www.google.com)
    - [Link to resource 2](https://www.google.com)

----------------------------------------------------------
### 01/2024
- **01/01/2024**

    Topics: (Laravel)
    - It turns out that in (Laravel Eloquent) there is an `increment` and `decrement` methods built in that you can use to increment or decrement a column value by a given amount.<br><br>For example, if you have a `balance` column in your `users` table, you can do something like this: `$user->increment('balance', 100);` to add 100 to the user's balance. You can also do `$user->decrement('balance', 100);` to subtract 100 from the user's balance.<br><br> But make sure that you are not using SIGNED INT for the column, otherwise you will have negative values. You can use UNSIGNED INT instead.

    **Resources:**
    - [Laravel Eloquent increment()](https://laravel.com/docs/10.x/queries#increment-and-decrement)

- **02/01/2024**

    Topics: (Twitter/X)
    - I like Twitter/X, its my favorite social media platform. I like to use it follow people I am interested in and inspire me. <br><br>Twitter/X has a `For You` tab which is an alothorithmically generated feed of tweets that it thinks you will like. I like this feature because it helps me discover new people and things that I am interested in.<br><br> But, recently I have noticed Its been showing me things that I am not interested in whatsoever. When you go to `https://twitter.com/settings/your_twitter_data/twitter_interests` you can see what are the topcis Twitter/X thinks you are interested in. <br><br>So, I counted them using javascript in the console and I have `377` topics apparently. And belive me when I see that 80% of them are not things I am interested in (Example: Mark Zuckerberg, Vladimir Putin, Pumpkin recipes :jack_o_lantern:, etc). So, I deleted them by executing javascript in the browser's console that will uncheck all the checkboxes. Hope this helps me get better recommendations. :smile: <br><br>
    ***NOTE: when trying to copy a code snippet and paste it in browser's (Chrome) console, you will need to allow pasting in the console by writing `allow pasting` in the console and pressing enter. Then you can paste the code snippet and press enter to execute it.***

    **Resources:**
    - [Bulk Uncheck Twitter/X Interests](https://peshmerge.io/how-to-check-uncheck-all-checkboxes-on-a-web-page-using-vanilla-javascript/)

- **03/01/2024**

    Topics: (Meetings)
    - Today while driving, I was listening to a podcast between David Heinemeier Hansson and Jason Fried (Basecamp founders). They were talking about how toxic meetings are for various reasons:
        - 1 hour meeting with 5 people is not a 1 hour meeting, its a 5 hour meeting. Because you are taking 1 hour of each person's time. So, you need to be very careful when you call a meeting.
        - They involve coordination, causing scheduling issues and disrupting everyone's workflow and mindset
        - They are usually not productive, because people are rarely prepared for them.
        - They drift off topic and go on tangents that are not relevant to the meeting.

        After I finished listing to the podcast, I wanted to check if there are facts that support this. I found this reserch on [Harvard Business Review](https://hbr.org/2017/07/stop-the-meeting-madness) According to their survey of 182 senior managers across industries:
        - 65% said meetings hindered their personal work completion.
        - 71% found meetings unproductive and inefficient.
        - 64% felt meetings compromised deep thinking.
        - 62% believed meetings missed opportunities to bring the team closer.

        So, here is what some companies (Example: Basecamp and 37signals) do to avoid traditional meetings:
        - They go to first-writing approach instead of a first-meeeting approach. If there's something to discuss, write it down first, share it with the team, and then have a meeting only if and only if it's absolutely necessary.
        - They use automatic weekly check-ins, like "What did you do this week?" through platforms like Slack. This keeps everyone informed and enables the creation of weekly reports for the team and stakeholders.
        - There are also occasional automated "social questions" to encourage team members to share non-work-related activities, fostering better relationships.

        As a result, the stakeholders are happy because they are getting weekly reports and the team is happy because they are not wasting their time in meetings. :smile:

        **Resources:**
        - [Stop the Meeting Madness](https://hbr.org/2022/03/dear-manager-youre-holding-too-many-meetings)
        - [Meetings are Toxic (Season 2)](https://37signals.com/podcast/meetings-are-toxic-season-2/)
        - [How We Communicate](https://37signals.com/how-we-communicate/)

