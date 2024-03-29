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

- **04/01/2024**
  
    Topics: (Mentalhealth, Motivation)
    - Today I came across multiple posts talking about "Toxic Positivity", and the first question that came to my mind is "How can positivity be toxic!?" 😅. Here is the explanation of what does "Toxic Positivity" means:

        > Toxic positivity is the belief that one should always maintain a positive mindset, no matter the circumstances. It discourages acknowledging or expressing negative emotions.
        
        I did some research about this and actually, the words in (Toxic positivity) are oxymoron, which means logically there is no such thing as "Toxic positivity". It's like saying "Square Circle" or "Married Bachelor" which doesn't make any sense.
        
        So, for now, let's call it "Fake positivity" or "Empty positivity". Which I truly believe it exists, where people throw around phrases like:
        - Good vibes only. ✌️😁
        - Stop being so negative, Think happy thoughts only. 🛑😃
        - Just be positive. 😊
        - Stay positive, everything will be fine.😃
        
        to someone going through a tough time or feeling stuck. These words feel empty and It's like a quick-fix without really understanding the depth of what the person is going through.
        
        I came across this example that will clarify things better:
        
        > Would you tell a crying baby to just cheer up and think positive?
        > No. You would realize the baby is crying because they are cold, hungry, wet, or want to be held. You would fix what was wrong instead of trying to silence them.
        
        It's good to have emotions and feel them.. just don't stay there forever. And If you surround yourself with an environment that solely emphasizes positive vibes, it can be harmful because it promotes an unrealistic approach to life.
        
        > We should grieve, be angry, feel rejected when appropriate. However, the key is not to stay in the emotion.
        
        **Resources:**
        - [Toxic Positivity](https://www.lipstickalley.com/threads/toxic-positivity.2017256/)
        - [Prerna Rohilla’s Post](https://www.linkedin.com/posts/contentonweb-prerna-rohilla_hello-fam-i-am-back-with-thursday-think-activity-7082630849363423232-7c8m)
        - [Toxic Positivity? Seriously?](https://www.youtube.com/watch?v=PW0q2jWouxQ)

- **06/01/2024**
  
    Topics: (kubernetes)
    - I recently found myself lacking knowledge about Kubernetes. I have read some posts about it, and I know it's like a management tool. It's somewhat similar to Composer and NPM for managing packages, but Kubernetes is for managing Docker containers. I didn't dive into it in the past because it was not relevant to me, and to be completely honest, I was running away from it (maybe scared). Now it's time to face it. 😬

        As they say, knowing the name of the enemy is the first step towards winning! Today, I want to shed light on its name. Kubernetes!? For some reason, I didn't like it. It's a long word, and I always find myself struggling to pronounce it. 🤔
        
        After researching, I found that Craig McLuckie, one of the founders of the Google-based Kubernetes project, said:
        
        > We had 13 other names we couldn’t get past Google’s legal department. It was the last day, and I had to pick something. I was driving into work, and I thought, ‘Well, [the technology] is like driving a container ship. What would the helmsman be called?’ So I tried to find something exotic. I had no idea what the Greek for that was. I had to look it up.
        
        Basically, the word "κυβερνήτης" ([Check How to pronounce κυβερνήτης](https://en.bab.la/pronunciation/greek/%CE%BA%CF%85%CE%B2%CE%B5%CF%81%CE%BD%CE%AE%CF%84%CE%B7%CF%82)) is a Greek term that translates to "helmsman" or "steersman" in English.
        
        To make sure, I opened Google Translator and typed "helmsman" then translated it into Greek, which gave me "πηδαλιούχος" pronounced as "pidalioúchos." That's incorrect; it's not even close to Kubernetes's word sound. I dug deeper and found the Liddell & Scott Greek-to-English lexicon, published in 1909, which had these meanings: "steersman, helmsman, guide, governor" for "κυβερνήτης." on page 397, which I was looking for. 
        
        Now, what does "helmsman" mean?
        
        > A helmsman or helm (sometimes driver or steersman) is a person who steers a ship, sailboat, submarine, or any other type of maritime vessel or spacecraft. 
        
        Another question: Why do people mention it sometimes as K8s?
        
        "K8s" is shorthand for Kubernetes because there are 8 letters between "K" and "s" in the word "Kubernetes" making it shorter and easier to type without spelling mistakes. 
        
        Now that I know the origin of "Kubernetes" I can sleep in peace. 😴
        
        **Resources:**
        - [How did they ever come up with that kooky ‘Kubernetes’ name? Here’s the inside story
        ](https://www.geekwire.com/2016/ever-come-kooky-kubernetes-name-heptio/)
        - [Liddell & Scott Greek-to-English lexicon, page:397](https://archive.org/details/dli.ernet.510177/page/397)
        - [Helmsman Definition](https://en.wikipedia.org/wiki/Helmsman).

- **08/01/2024**
  
    Topics: (Hypervisor)
    - What is a hypervisor? A hypervisor is a software that creates and runs virtual machines (VMs). It allows you to run multiple operating systems on a single physical machine and share the underlying hardware resources. It will allocate the resources (CPU, RAM, Storage, etc) to each VM. <br><br>

        There are two types:

        - Type 1: Bare Metal Hypervisor (Native Hypervisor)
           -  What? It directly communicates with hardware, making it efficient and secure without a middleman OS.It can allocate more resources to virtual machines than your server actually has. For instance, with 128GB of RAM and eight VMs, you can assign 24GB to each, totaling 192GB. However, VMs use only the necessary RAM for their tasks, not the full allocated amount.
            -  Who? Used by enterprises and data centers (e.g., Amazon, Google) for running multiple OS on one machine.
            -  When to Use: Large data centers or server farms for maximum performance and direct hardware access.
            - Example: VMware ESXi, Microsoft Hyper-V.


        - Type 2: Hosted Hypervisor
            - What? Operates within the regular OS, less powerful but user-friendly.
            Type 1 hypervisors allocate resources dynamically based on VM needs, making it easier. Type 2 hypervisors use fixed allocations, so if a user assigns 8GB to a VM, it takes that amount even if not fully used. This can lead to resource issues on the host machine.
            - Who? Used by developers and individuals for running multiple OS on one machine.
            - When to Use: Simple setups or software development when top performance is not critical.
            - Example: VMware Workstation, Oracle VM VirtualBox.

        Here is a diagram that explains it better than words. :smile: <br><br>
        ![Hypervisor](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Hyperviseur.svg/400px-Hyperviseur.svg.png)



        **Resources:**
        - [What is a hypervisor?](https://aws.amazon.com/what-is/hypervisor/)
        - [Hypervisor Diagram](https://en.wikipedia.org/wiki/Hypervisor#/media/File:Hyperviseur.svg)

- **09/01/2024**
  
    Topics: (Docker)
    - Have you ever wondered how Docker containers work? <br><br>
    <img src="memes/1.png" alt="how-docker-works" width="200"/><br><br>

        First, lets make these things clear:

        - VMs have their own kernel, making them heavier and slower compared to Docker containers.
        - Docker containers share the host machine's kernel, making them lightweight and faster than VMs.
        - There are different ways to create containers, but Docker is the most popular one (example: Podman, LXC, LXD, etc).
        - A container must follow the OCI (Open Container Initiative) standards to be considered a container.

        Now, lets see how (Docker Linux containers) works. <br><br>

        They are normal Linux processes that run in an isolated environment. And they rely on the following Linux features:
        - Namespaces: This keeps each container separate from the others. It isolates things like processes, network, user IDs, and file systems, but they still share the same basic system (kernel).
        - Control groups (cgroups): These control and limit how much of the computer's resources (like CPU, memory, disk, and network) each container can use. It helps in managing and isolating resource usage for a group of processes.

        So, now what happens when you execute a command like `docker run -it ubuntu bash`? <br><br>
        - Docker will create a new container process.
        - a new namespace will be created for the container.
        - a new cgroup will be created for the container.
        - a new root filesystem will be created for the container.
        - a new network interface will be created for the container.

    **Resources:**
    - [What Is a Standard Container](https://iximiuz.com/en/posts/oci-containers/)

- **09/01/2024**
  
    Topics: (Data Lake, Data Warehouse, Data Mart)

    - Well, data is everywhere every second of every day.As a backend developer, I used to  dodge terms related to data engineering. However, due to a recent project, I've started learning more about it.
    <br><br>
        <img src="memes/2.jpg" alt="how-docker-works" width="200"/>
    <br><br>
        So, I came across these terms: Data Lake, Data Warehouse, and Data Mart. I will break them down into simple terms that I can understand. 
        
        The format will be as follows:
        - Definition: (Definition)
        - Characteristics: (Characteristics)
        - Why it exists: (Why it exists)
        - Tools: (Tools that can be used to implement it)
<br><br><br>

    1. **Data Lake:**
        - **Definition:** A huge storage space for all raw data (For example: JSON, Videos, Database dumps, etc) where everything is dumped without organization.
        - **Characteristics**:
            - Stores raw data without modification.
            - Store structured, semi-structured, and unstructured data.
            - Can be Used for the entire data lifecycle.
        - **Why it exists:** Data is valuable nowdays and it can be used for many things. So, store it and you can use it later when you need it.
        - **Tools:** 
            - *Free:* Hadoop Distributed File System (HDFS)
            - *Paid:* Amazon S3, Azure Data Lake Storage, Google Cloud Storage
<br><br><br>
    2. **Data Warehouse:**
        - **Definition:** An organized storage place where data is structured and cleaned.
        - **Characteristics**:
            - Stores data in a structured way.
            - Requires transformed and cleaned data.
            - Time-variant data, meaning any existing data will be archived after perid of time (Example: 1 year) and stored in the Data Lake.
        - **Why it exists:** Since data is stored in a structured way, it can be used for reporting and analysis.
        - **Tools:** 
            - *Free:* PostgreSQL, MySQL, MariaDB (limitions: not scalable for HUGE data and not optimized for analytics purposes)
            - *Paid:* Amazon Redshift, Google BigQuery
<br><br><br>
    3. **Data Mart:**
        - **Definition:** A subset of a Data Warehouse, with a focus on specific topics.
        - **Characteristics**:
            - Users don't need advanced technical knowledge.
            - Subset of a Data Warehouse, smaller and topic-focused.
            - Users have read-only access to specific information.
        - **Why it exists:** Provides users a quick and easy access to data for specific topics.
        - **Tools:** 
            - *Free:* Microsoft Power BI (limited features)
            - *Paid:* Microsoft Power BI, Tableau, QlikView, Looker

    **Resources:**
    - [Data Lake vs Data Warehouse vs Data Mart](https://www.sprinkledata.com/blogs/data-lake-vs-data-warehouse-vs-data-mart)

- **11/01/2024**
  
    Topics: (Motivation, MentalHealth)
    - These are some thoughts I have learned/read somewhere that I would like to always make them stick in my mind and I want to write them down here so I can always come back to them and remind myself of them. <br><br>

        - ITS NOT YOU!. No matter your job or how high up you are, it's not because you're smarter, better, stronger, or hard worker than others. It's not about your connections. It's because God gave you this, and you should be always grateful for it. Don't let it get to your head, and be always humble.
<br><br>
        - YOU ONLY HAVE CONTROL OVER YOUR ACTIONS!. You can't control your life, your thoughts, your feelings, other people, or anything else. You have 0 control over everything except your actions. Focus on what you can control.
<br><br>

        - EVERY ONE IS REPLACEABLE!. No matter how good you are at what you do. Here is the bitter truth: You are replaceable and everyone is.
<br><br>

            And always remmber, things can be seen from different perspectives/angles. :smile:
            
            <img src="memes/3.jpg" alt="perspective" width="400"/><br><br>


- **14/01/2024**
  
    Topics: (Redis)
    - Ok, So I have been using Redis for a long time in many applications, for storing cache, sessions, and queues. And a question came up that I need to an answer for: Can we scale Redis? and if yes, how? <br><br>

        So, I did some research and here is what I found: <br><br>
        - Redis is in-memory data structure store, which means it stores data in RAM.
        - The amount of data that can be stored in Redis is limited by the amount of RAM available. The more RAM you have, the more data you can store.
        - When Redis uses all the available RAM, it supports swapping to disk. It can help to store more data and avoid crashing, but it will cause a huge performance drop.
        - Based on a real-world test done by Redis team. Redis can handle up to 2^32 keys (4294967296 keys). And Each key can hold a value with its own limits based on the chosen data structure. For example, a string can hold up to 512MB, a list can hold up to 2^32 elements. So, if you store 1 string in each key, you can store up to 4294967296 * 512MB = 2048000000000 MB which is roughly 2 TB of data. That's a lot of data (if you have that much RAM that is :smile:).
        - To estimate the storage capacity of Redis, you can use this formula: `Redis Storage Capacity = Total Available RAM − (Redis Metadata Overhead + OS RAM Usage)` where `Total Available RAM` is the total RAM available in the server, `Redis Metadata Overhead` Redis uses some amount of RAM for its internal metadata to manage keys, values, and other data structures efficiently. `OS RAM Usage` is the amount of RAM used by the operating system and other processes running on the server.

        So, how can we scale Redis? <br><br>
        - Add more RAM to the server. :smile:
        - Its all about the RAM. The more RAM you have, the more data you can store. Its the bottleneck of Redis.
        - When your redis server reach 2^32 keys, you can use Redis Cluster to scale it horizontally by adding more nodes to the cluster. And the load balancer will distribute the requests between the nodes.
        - If your app is using Redis for sessions, you can use sticky sessions(in the load balancer) to make sure that all the subsequent requests from the same user will be routed to the same Redis node where the user's session is stored, otherwise the user will be logged out because the session is not found when the request is routed to a different Redis node by the load balancer.

        **Resources:**
        - [How Much Data Can Redis Store?](https://www.dragonflydb.io/faq/how-much-data-can-redis-store)
        - [Redis FAQ](https://redis.io/docs/get-started/faq/)

- **17/01/2024**
  
    Topics: (NestJS, TypeScript)
    In upcoming days I will shift my focus to learning NestJS and TypeScript for various reasons.
    - Javascript is a very popular language used by many small, big and huge companies (everywhere).
    - Has a huge community and a lot of resources.
    - Can be used for many things (Frontend, Backend, Mobile, Desktop, etc).
    - In performance wise, its very fast and efficient language (very good for high traffic applications, example: Twitter/X).
    - Its a must have skill/tool for any developer that wants to find a work in the tech industry.

    So, I have enrolled in a course on Udemy to learn TypeScript and NestJS. I am on the first section of the course and here what I have learned so far:

    Why does TypeScript exist? <br><br>
    - Typescript is basically a superset of Javascript. It adds types to Javascript. It's like a layer on top of Javsacript. Typescript = Javascript + Type System.
    - Helps you catch errors before you run your code.
    - Helps you write better/Maintainable code.
    - Doesnt run in the browser or nodejs. It needs to be compiled to Javascript first.
    - It doesnt provide any performance benefits.
    - Its like a friend sitting next to you and telling you "Hey, you made a mistake here, you should fix it before you run your code".

    What is a type? <br><br>
    A type is something that describes the different properties and functions that a value has. Lets take exmple of a string:
    ```javascript
    let color = 'red';
    ```
    The type of `color` is `string`. It has properties like `length` and functions like `toUpperCase()`. <br><br>
    Another example: 
    ```javascript
    let count = 5;
    ```
    The type of `count` is `number`. It has properties like `toFixed()` and functions like `toString()`. <br><br>

    And there are 2 categories of types:
    - Primitive Types: (number, string, boolean, symbol, void, undefined, null)
        - They directly store/hold the value.
        - If you have variable a storing number 5, its like saying you have a number 5 in your hand.
    - Object Types: (functions, arrays, classes, objects).
        - They store a reference to the value.
        - They don't hold the actual data, but point to where the data is stored.
        - If you have a variable a storing an an object called Person, its like saying you have a piece of paper in your hand that has the address where the details about that Person are stored, not the Person itself.

    **Resources:**
    - [NestJS: The Complete Developer's Guide](https://www.udemy.com/course/nestjs-the-complete-developers-guide/)

- **18/01/2024**

    Topics: (TypeScript, Type annotations, Type inference)
    - As I go through the typescript course, here are some things I have learned. In TypeScript, there are two important concepts: Type annotations and Type inference.

        **Type Annotations:** We, as developers, use type annotations to tell TypeScript the type of value a variable will have. For example:
        ```typescript
        let apples: number = 5;
        ```
        Here, we're saying that `apples` will always be a number. If we try to assign a string, TypeScript will show an error.

        **Type Inference:** TypeScript tries to figure out the type of a variable by itself. For example:
        ```typescript
        let apples = 5;
        ```
        When we declare and initialize a variable in one line, TypeScript guesses its type. In this case, it's a number. If we try to assign a string, TypeScript will show an error.
        <br><br>
        ### When to use each one?

        **Type Inference:** Use it whenever possible. Let TypeScript do the work of figuring out types for you.

        **Type Annotations:**
        - When declaring a variable and initializing it in separate lines:
        ```typescript
        let apples; // should be let apples: number;
        ```
        - When a function needs to clarify the type it returns:
        ```typescript
        const numberToString = (num: number): string => {
            return num.toString();
        }
        ```
        - When a variable's type can't be inferred(guessed by TypeScript):

        When Typescript can't figure out the intended type (a scenario where a variable could potentially have multiple types), we need to use type annotations. For example:
        ```typescript
        let words = ['red', 'green', 'blue'];
        let foundWord = false;

        for (let i = 0; i < words.length; i++) {
            if (words[i] === 'green') {
                foundWord = words[i];
            }
        }
        ```
        to fix this, we need to add type annotations to `foundWord` variable:
        ```typescript
        let words = ['red', 'green', 'blue'];
        let foundWord: boolean | string = false;
        ```

    **Resources:**
    - [NestJS: The Complete Developer's Guide](https://www.udemy.com/course/nestjs-the-complete-developers-guide/)

- **20/01/2024**

    Topics: (TypeScript, Type Declaration Files)
    - Type Declaration Files are files that describe the whole API of a library that was written in Javascript. These files are the magic behind TypeScript. 

        Let's break it down with a simple example:
        Suppose there is a JavaScript library called mathLibrary.js with the following code:
        ```javascript
        const add = (a, b) => {
            return a + b;
        }
        ```
        If we try to use this library in a TypeScript file, we will get an error saying that `add` function doesn't exist. This is because TypeScript doesn't know anything about this library (because it's written in JavaScript without any type annotations). So, we need to create a type declaration file for this library. Let's call it mathLibrary.d.ts. It will look like this:
        ```typescript
        declare function add(a: number, b: number): number;
        ```
        Now, when we try to use this library in a TypeScript file, we will not get any errors. This is because TypeScript now knows about this library and its functions. It knows that `add` function takes 2 numbers and returns a number. So, if we try to pass a string, it will show an error.

        Typescript depends on type declaration files heavily. It's what makes TypeScript so powerful. If you do `npm install typescript`, you will see that it comes with a lot of type declaration files ".d.ts" files in the node_modules.

        Note: There is a tool called [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped) which has a lot of type declaration files for popular JavaScript libraries. You can install them using `npm install @types/<library-name>`. For example, if you want to install type declaration files for Googlemaps JS library, you can do `npm install @types/googlemaps` after that TypeScript will automatically find the type declaration files in the `node_modules/@types` folder and use them to check your code for errors.

        **Resources:**
        - [Type Declarations](https://www.typescriptlang.org/docs/handbook/2/type-declarations.html)


- **24/01/2024**

    Topics: (TypeScript, TSConfig)

    - TSConfig is a file that tells TypeScript how to behave. Typescript will use it to know what to do when it compiles our code. It's a JSON file that has a lot of options. I will foucs on tow of them for now, which was confusing to me at first.

        - `target`: This tells TypeScript what version of JavaScript to convert our code to. For example, if we set it to `ES2015`, TypeScript will convert our code to ES2015. If we set it to `ES2021`, TypeScript will convert our code to ES2021.
        - `module`: This tells TypeScript what (module system) to use. For example, if we set it to `commonjs`, TypeScript will convert our code to CommonJS. If we set it to `es2015`, TypeScript will convert our code to ES2015 modules. The default value is `commonjs` which is the most popular module system used in NodeJS.

        Here is a great post on StackOverflow that explains the difference between `target` and `module` in TSConfig: [What is the difference between target and module in tsconfig.json?](https://stackoverflow.com/a/61215252)

        Also, check this website (https://node.green) to see which features are supported in each version of nodejs.

- **31/01/2024**

    Topics: (TypeScript, NestJS)

    - I have been very busy lately, so I didn't have time to write about things. I reached "Persisting Data with TypeORM" section in [NestJS: The Complete Developer's Guide](https://www.udemy.com/course/nestjs-the-complete-developers-guide/) course. The learning curve is a bit steep, but I am enjoying it so far. I have learned a lot of things about TypeScript and NestJS that I will write about in the upcoming days so I can organize my thoughts about it.

        <br><br>
        <img src="memes/4.jpg" alt="perspective" width="400"/><br><br>


        **Resources:**
        - [NestJS: The Complete Developer's Guide](https://www.udemy.com/course/nestjs-the-complete-developers-guide/)

- **03/02/2024**

    Topics: (JWT, Authentication)

    - JWT (JSON Web Token) is a very popular way to authenticate users. It's a way to securely exchange data between client and server through a token. Here is how it works:

        1. User sends their credentials (i.e. username and password) to the server.
        2. The server checks if the credentials are correct.
        3. If valid, server creates a JWT token as follows:
            - To make a JWT token, server will use 3 things: Header, Payload, and Secret.
                - Header: It contains type of token and hashing algorithm used to sign a signature.
                    ```json
                    {
                        "alg": "HS256",
                        "typ": "JWT"
                    }
                    ```
                - Payload: It contains data that we want to send. For example, user's ID, username, email, etc.
                    ```json
                    {
                        "id": 1,
                        "name": "John Doe",
                        "admin": true
                    }
                    ```
                - Secret: It's a secret key that is used to sign a signature. It's only known by server.
                ```
                "MySecretKeyThatNoBodyKnowsButTheServer"
                ```
                - The server will use header (base64UrlEncode), payload (base64UrlEncode), and secret in order to create a signature. 
                ```
                signature = HMACSHA256(
                    base64UrlEncode(header) + "." +
                    base64UrlEncode(payload),
                    secret
                )
                ```
                - The output structure of JWT token will be like this:
                ```
                base64UrlEncode(header) + "." + base64UrlEncode(payload) + "." + signature 
                ```
        4. The server sends JWT token to client.

        And that's it.  Client will send JWT token in header of each request to server.

        Very important notes:
        - JWT token is not encrypted, it's just base64UrlEncoded. So, don't put any sensitive information in payload. Meaning, if for some reason an access token is stolen, an attacker will be able to decode it and see information in payload.[Check it here](https://jwt.io/).
        - Keep access token expiry short (e.g., 15 minutes) to limit attacker misuse if stolen.
        - Because access token is kept on client side, it's vulnerable to XSS attacks. Server can't set HttpOnly flag on it since client needs access to include it in requests.
        - Dont use an access token to generate a new access token when old one expires. If access token is stolen, an attacker will be able to generate new access tokens forever. Instead, use a refresh token to generate new access tokens.
        - Refresh tokens should have a long expiration time, and they are stored in HttpOnly cookies to prevent XSS attacks (only server can access them).
        - Protect a refresh token from CSRF attacks by using `SameSite ` attribute in cookie. [Check it here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie/SameSite) so a browser will only send a cookie to server if a request originated from same site that set cookie in first place (server).
        - As a security measure for refresh tokens. Create a table for refresh tokens in database and store refresh token's related information (user ID, expiration time, last used time, device, user agent, etc) to be able to revoke refresh token if it's stolen or check if refresh token was used before or not.
        

        <br><br>
        <img src="memes/5.png" alt="perspective" width="400"/><br><br>

        Drawbacks of JWT:
        - Logout doesn't really log you out:
            - Once a JWT token is created, it's valid until it expires. There is no way to invalidate it. So, if a user logs out, you can delete the access token from client side, but it's still valid until it expires.
        - Blocking a user is not possible:
            - If a user is blocked, there is no way to block them from accessing the system until their access token expires. Imagine you are a bank and one of the users's access token is stolen, you can't block it or do anything about it until it expires which is a big security risk for a bank that deals with money.
        - Changes by system are not reflected in real time:
            - If a user's role is changed from admin to regular user, there is no way to reflect this change in real time. The user will still have access to admin features until their access token expires.
        -  You can't know how many current users are logged-in:
            - Since JWT tokens are stateless, there is no way to know how many users are logged in at any given time in the system.

        
        Rule of thumb:
        - Use traditional session-based authentication. It's more secure and flexible than JWT.
        - JWT is a good fit for cases/situations where you issue a one-time token to be used for a specific purpose. [what is JWT good for, then?](http://cryto.net/~joepie91/blog/2016/06/13/stop-using-jwt-for-sessions/)

        **Resources:**
        - [JWT.io](https://jwt.io/)
        - [SameSite Cookie](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie/SameSite)
        - [HttpOnly Cookie](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies#restrict_access_to_cookies)
        - [IETF RFC 6749](https://www.rfc-editor.org/rfc/rfc6749)
        - [Access Token vs Refresh Token](https://jackywxd.medium.com/understand-jwt-access-token-vs-refresh-token-2951e5e45193)
        - [Refresh token with JWT authentication in Node.js](https://www.izertis.com/en/-/refresh-token-with-jwt-authentication-in-node-js)
        - [Stop using JWT for sessions](http://cryto.net/~joepie91/blog/2016/06/13/stop-using-jwt-for-sessions/)

- **04/02/2024**

    Topics: (JWT, Authentication, Blacklisting JWT)

    - As mentioned before, JWT has some drawbacks that make it unsuitable as an authentication system. However, there are ways to work around these drawbacks and make JWT more secure.

    One way to protect our system is to blacklist JWT tokens (although JWT is stateless and was not designed to be blacklisted). But as they say, tools can be used in ways they were not designed for.

    ### Here's how it works:

    First, make sure to add the `issued_at` (iat) claim to the payload of the JWT token when the server creates it. It's a timestamp that represents the time when the token was issued/created. For example:
    ```json
    {
        "name": "John Doe",
        "iat": 1643961600
    }
    ```

    Then, this is how the process will work when a user logs out or you want to block someone from accessing the system through an admin dashboard or something:

    1. When a user logs out, we will add their `user_id` and `minimum_issued_at` to a blacklist table in the database.
    ```sql
    INSERT INTO blacklist (user_id, minimum_issued_at) VALUES (1, NOW());
    ```
    2. When a user tries to access the system via a JWT token, it will go through this process:
        - The server will check if the JWT token is valid (not expired, not tampered with, etc.).
        - If the JWT token is valid, the server will check if the `user_id` that is in the JWT payload exists in the blacklist table.
        - If it exists, the server will check if the `iat` of the token is greater than `minimum_issued_at` in the blacklist table for that `user_id`.
            - NOTE: If the user has multiple records in the blacklist table, the server will check for the record with the latest `minimum_issued_at` value since it's the most recent one.
        - If the `iat` of the token is greater than `minimum_issued_at`, the server will allow the user to access the system.
        - If it's not greater, the server will deny the user access to the system (goodbye, you are blocked 😊 here is a 403 status code).

    Now, the blacklist table will have a lot of records over time (which is not good for performance/efficiency). So, we need to clean it up from time to time. We can do this by creating a cron job that runs every day and deletes all records that have `minimum_issued_at` less than the current time minus JWT token TTL (Time To Live). This way, we can keep the blacklist table clean and small.
    ```sql
    DELETE FROM blacklist WHERE minimum_issued_at < NOW() - INTERVAL 15 MINUTE;
    ```

    Additionally, you can also do global token invalidation by changing the secret key (not recommended, but it's an option). Or in the case of the Blacklist table, you can insert `user_id` with the value "all" and `minimum_issued_at` with the current time. And let the server check for this record first before checking for the user's record. If it exists, deny access to the system.

    Moreover, you can add more columns to the blacklist table to make it more flexible. For example, you can add a `platform` column to store the platform that the token was issued for (web, mobile, etc.). You can add a `device` column to store the device that the token was issued for (laptop, phone, etc.). This way, you can invalidate tokens based on the platform or device too.

    Drawbacks of Blacklisting JWT:
    - You need to query the database for each request to check if the token is blacklisted or not (since the table will be cleaned up from time to time, it will be small and fast to query + you can add an index on `user_id` and `minimum_issued_at` columns to make it faster to query + you can use a cache like Redis to store the blacklist table in memory to make it even faster).

    Conclusion:
    - Blacklisting JWT tokens is a good way to make JWT more secure and flexible even though it's not designed to be blacklisted. It's a good way to work around the drawbacks of JWT as an authentication system.

    **Resources:**
    - [How JWTs Could Be Dangerous and Its Alternatives](https://dev.to/pragativerma18/how-jwts-could-be-dangerous-and-its-alternatives-3k3j)

- **14/02/2024**

    Topics: (event loop, nodejs, browser, differences)

    - I have been learning about the event loop in NodeJS and the browser for the past few days. Here are some resources that I found helpful:
        - Node.js animated: Event Loop [Check it here](https://dev.to/nodedoctors/an-animated-guide-to-nodejs-event-loop-3g62)
        - Event Loop in Node.js vs Browser [Check it here](https://levelup.gitconnected.com/event-loop-in-node-js-vs-browser-28a3e6b57d8b)

        It seems like a complex topic, but I am starting to understand it better. I will keep digging deeper in the upcoming days.

        <img src="memes/6.jpg" alt="how-docker-works" width="300"/>

- **23/02/2024**

    Topics: (s3, minio, object storage, select query)

    - Did you know that you can run a select query on an object storage like S3 or Minio? I didn't know that until today, I thought you can only upload, download, and delete files from an object storage. But it turns out that you can run a select query on it too. Here is how it works by using `boto3` library which is a tool that allows you to interact with AWS services using Python.

    ```python
    import boto3

    s3 = boto3.client('s3')

    response = s3.select_object_content(
        Bucket='my-bucket',
        Key='my-file.csv',
        ExpressionType='SQL',
        Expression="SELECT * FROM s3object s WHERE s.column1 = 'value'",
        InputSerialization = {'CSV': {"FileHeaderInfo": "Use"}},
        OutputSerialization = {'CSV': {}},
    )
    ```
    This will run a select query on `my-file.csv` file in `my-bucket` bucket and return the result of the query.

    This is very useful when you have a huge file and you want to run a query on it without downloading the file first. And of course, you can do the same thing with Minio, which is an open-source object storage that is compatible with S3.

    Note: You can only run a select query on CSV, JSON, and Parquet files. (Parquet is a columnar storage file format that is optimized for reading and writing large datasets. It's a good choice for big data analytics.)

    As everything in tech, there are always trade-offs. You will face an issue if you have a lot of small files (i.e., millions of files). It will be slow and inefficient to run a select query on them even if do it in parallel. So, it's better to use other tools that will help you run a select query on a huge number of small files like Apache Hive, Apache Hadoop, Apache Spark, etc (I have never used them, but I have heard about them).

    **Resources:**
    - [SelectObjectContent](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#S3.Client.select_object_content)


- **11/03/2024**

    Topics: (gRPC, proto files)

    - I have been learning about gRPC for the past few days. It's a very interesting technology that allows you to communicate between microservices in a fast and efficient way. It's a good alternative to REST API for havey data transfer between microservices.

        <img src="memes/7.jpg" alt="grpc" width="400"/>


        Lets first check what is RPC (Remote Procedure Call):
        - Simply, it's a way to call a function another machine as if it was a local function. The network is abstracted away from the developer.
        Here is an example of how it works, using Python's `xmlrpc` library (which is one of the many ways to do RPC):
        ```python
        # client.py
        import xmlrpc.client

        proxy = xmlrpc.client.ServerProxy("http://localhost:8000/")
        print(proxy.add(2, 3))
        ```

        ```python
        # server.py
        from xmlrpc.server import SimpleXMLRPCServer
        from xmlrpc.server import SimpleXMLRPCRequestHandler

        def add(x, y):
            return x + y

        server = SimpleXMLRPCServer(("localhost", 8000))
        server.register_function(add, "add")
        server.serve_forever()
        ```
        When you run `client.py`, it will call `add` function in `server.py` and print the result.

        From the client's perspective, it gives an illusion that the function was called locally, but in reality, it was called on another machine with the network tasks abstracted away from the developer.

        Now, let's talk about gRPC:
        - Its Google's version of RPC. It's a modern, open-source, high-performance RPC framework that can run in any environment. 
        - It's a good fit for microservices architecture, where you have a lot of small services that need to communicate with each other in a fast and efficient way.
        - It uses HTTP/2 for transport, Google's Protocol Buffers (protobuf) as the interface definition language.
        - It's faster and more efficient than REST API because it uses binary data for network communication instead of JSON.

        Check "Quick start" section in [gRPC official website](https://grpc.io/docs/languages/python/quickstart/) to see how to use gRPC with Python.

        **Resources:**
        - [gRPC official website](https://grpc.io/)
    
- **28/03/2024**

    Topics: (software engineerer, software developer, differences)

    <img src="memes/8.jpg" alt="grpc" width="200"/>

    - I have been hearing these terms a lot lately (“Software Developer”, “Software Engineer”), and I was wondering what the difference between a software engineer and a software developer is. So, I did some research and here is what I found:

        None, ZERO, they are the same thing. The terms "coder", “Programmer”, “Developer”, “Software Developer”, “Software Engineer” are all used interchangeably. They all refer to a person who writes code to solve problems. Different companies use different titles, it's just a matter of preference.
    