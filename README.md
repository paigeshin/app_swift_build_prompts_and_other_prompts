# GPT Swift App Building

# **Meet ChatGPT, an innovative AI tool that empowers designers and developers to create stunning app designs without needing to master complex tools, programming languages and product design. In this tutorial, we'll explore how to harness the power of ChatGPT for app development, from generating beautiful designs with Midjourney, to crafting starting prompts, handling copywriting, and even developing product strategy. Let's dive in!**

# **Downloads**

To follow this course, you can download the **[source file](https://downloads.ctfassets.net/ooa29xqb8tix/3QmTznGqDjDC1aCFl2C7gG/926ef8f49819a5bd4a39335515c8a8d1/GPT-4_Course.zip)**, which will help you compare your progress.

# **GPT-4**

GPT-4 is more creative and collaborative than ever before. It can generate, edit, and iterate on creative tasks such as composing songs, writing screenplays, or learning a user's writing style.

1. **Expanded input**: GPT-4's increased input limit of 25,000 words allows for more detailed conversations, providing richer context for your projects.
2. **GPT-4 Vision**: Generate images from text descriptions and bring your design ideas to life effortlessly.
3. **Enhanced accuracy**: GPT-4's improved accuracy and understanding compared to its predecessor ensure your projects are executed with precision.

# **Getting Started with ChatGPT**

ChatGPT is an advanced language model developed by OpenAI, designed to generate human-like text, answer questions, and assist in various language-related tasks. New users will find this innovative AI model incredibly easy to use and adaptable to their individual needs.

1. Visit OpenAI's website: Go to **https://chat.openai.com/** to access ChatGPT.
2. Sign up or log in: If you don't have an OpenAI account, click on "Sign up" to create one.
3. ChatGPT 3.5 is available for free, but its performance and accuracy may not be as impressive as GPT-4. By subscribing for $20/month, you can upgrade to GPT-4 and also enjoy a faster version of ChatGPT 3.5.
4. Start a conversation: Input your query, question, or prompt in the designated text box within the ChatGPT interface.
5. Refine your input: For better results, ensure your queries are clear, precise, and accurately convey your desired outcome.
6. Experiment with multi-turn conversations: Engage in a more detailed and contextual interaction with ChatGPT by using multi-turn conversations.

# **Starting Prompts**

First, it's essential to identify the areas of expertise you possess and define your objectives for creating apps. By understanding your strengths and the purpose behind your app development, you can effectively align your efforts with your target audience's needs and interests. This foundation will enable you to create engaging, useful, and successful apps that cater to your users and help you achieve your desired outcomes.

# **OPENAI’S DEMO**

Based on the demo from OpenAI, you can set the requirements for your project.

**`You are an Al programming assistant.
- Follow the user's requirements carefully & to the letter.
- First think step-by-step - describe your plan for what to build in pseudocode, written out in great detail
- Then output the code in a single codeblock
- Minimize any other prose`**

# **BEGINNER-FRIENDLY FOR IOS**

Specify the areas of expertise needed in your project and your coding style. Let’s start with a beginner-friendly starting prompt for iOS and web.

iOS is the easiest since all you need is Xcode and everything is available from the get-go. No need for third-party libraries, especially for beginners.

**`You’re an expert in iOS dev, SwiftUI, iOS architecture and a robust architecture with the best practices.

- Provide steps to create a new project in Xcode.`**

# **BEGINNER-FRIENDLY FOR WEB**

Web projects are more open and rely on many services and frameworks. You will be faced with dozens of choices, but let’s start with a popular one: React and CodeSandbox. It’s one of the easiest way to start.

**`You're a web developer that specializes in React and CSS.

- For CSS, use Styled-Components.
- Use CodeSandbox to quickly build prototypes.
- Provide steps to create a new project in CodeSandbox.
- Provide steps to install third party libraries that we need.
- Create everything inside App.js`**

# **START SIMPLE**

When starting to work with GPT-4, it's best to avoid creating complicated projects at first. The AI may be slow and pause randomly due to its limit in number of tokens per post. To avoid frustration, it's recommended to not ask for too much information all at once and to add details incrementally. For example, if you're asking for steps, it's better to wait for the next post to ask about the concept.

- In this example, we’re creating elements in a specific order.

**`Create a card with cover image, title, divider, subtitle, text, author (avatar + name).`**

# **WEB FULL STACK**

Most full-fledged web projects require their own customized stack. A popular one today is React with Next.js and Vercel.

**`You're a seasoned web developer that specializes in React, Next.js, Vercel and CSS.

- For content, use Contentful and GraphQL.
- For Authentification use Firebase and Firestore.
- We will need the Vimeo API to serve videos.
- Use Dropbox to get downloabable files for our paid customers.`**

# **CODING STYLE**

Code outputs are often too slow to write and too long for a single post. So it’s a good idea to focus on new changes. It may be best to split into multiple files and components. This requires more organization but is future-proof.

- **`Make your code as short, easy to understand and concise as possible.
- Only focus on code that is new or that are changing during new requests.- Split into components and small files that are no longer than 100 lines of code.`**

# **USER EXPERIENCE**

It never hurts to explore opportunities to make the project sustainable by understanding what features are essential and what features may be valuable to premium users.

- **`Develop apps that are beautifully designed with a great user experience
- Think like an entrepreneur and give advice on new features and how we could monetize this app.`**

# **Concepts and Development**

At the beginning of the project, it’s best to keep it clear and simple with a concept that can be achieved in a single post. Be descriptive, use examples, and focus on small wins. Here are some examples:

**`Build a SwiftUI chat app that talks to a trainable AI.

I want a nice vector pattern like in the Apple Card hologram that animates on tap in SwiftUI.

Create a fun iOS app in SwiftUI that does colour matching. There will be two big circles next to each other and you can swipe vertically on it to change the brightness, horizontally to change the hue. Tolerance level for accepted answer should be not too hard at first and gradually harder. There should be a timer, and you have 10 secs to answer. There should be a button to submit answer below.

Create a blur card that emits particles only when it moves. Can you add a drag gesture that responds in a physics way, with the circles following the drag but also lagging a little bit like in real life with inertia, like hair moving and slower strands catching up.`**

# **ERRORS AND DEBUGGING**

Your code won’t always work. Sometimes, you need to ask multiple times. When you encounter errors, don’t hesitate to paste the error messages and give the specific line number or the element names that are erroneous.

**`{paste error message}
{error at line #}
{describe user experience issue}`**

# **UPDATE CODE AND FOCUS ON CHANGES**

When you deal with a lot of code, the responses from GPT-4 will be slow, repetitive and hang at random places. To make the experience better, ask to only show code that changes. Also, the AI will tend to forget about your code, so it’s a good idea to regularly paste your entire code to keep it up-to-date.

**`{Paste code}
{Ask change}
Focus only on code that changes`**

If the code keeps hanging, you can ask to continue from specific places.

**`Continue from {step # or "text from response"}`**

# **SELF IMPROVEMENTS**

AI can sometimes make errors and not fully meet the requirements you provide. Rather than suggesting specific changes, you can prompt ChatGPT to analyze and learn from its mistakes.

**`Did you fulfill all my requirements?
Is there a mistake in your code?
Review your code and offer improvements`**

# **Read Documentation and Summarize**

Experience the ease of accessing documentation with ChatGPT. Simply copy and paste an entire page of documentation, then ask for a summary or specific questions about it. This exceptional feature makes information readily available to everyone, without the need to purchase specialized products. Effortlessly explore documentations from sources like Stripe, React, Swift, and more with ChatGPT's unprecedented capabilities.

**`Read this documentation and summarize in bullet points:

{paste long documentation}`**

# **Midjourney Prompts**

By using this prompt, you can provide a brief set of keywords that describe the desired image.

**`You are a master at creating prompts for Midjourney v5
- create a prompt based on my short description
- follow this formula: A detailed image of [subject] [doing something interesting] during (time of day], taken with a [type of camera], using [type of lens] with cinematic lighting --v 5 --ar 16:9`**

# **Copywriting**

GPT-4 has the potential to design product pages by generating creative and engaging content for product descriptions, titles, and images. It can also generate personalized product recommendations based on user preferences, search history, and behavior. This can enhance the overall customer experience and lead to increased sales for businesses.

**`You are a thoughtful, helpful and expert copywriter for web and mobile apps. 
- All your writing should be limited to a paragraph with a max of 3 sentences.
- Write in a simple way that anyone can understand.
- Be as concise as possible. Less is better.
- Write in Markdown format with providing links to products mentioned.`**

# **Product Strategy**

The key to a successful product rests not only on how good the product is but also how well do you present it to the world. You should think about distribution, partnerships and strategies for email, social media and SEO.

# **ENTREPRENEUR**

**`You are my entrepreneur friend and you are an expert at turning good products into amazing opportunities to reach more audience and monetize better.
- I have an education platform that teaches hands on lessons about design and code. 
- I want to make it better to beginners and get them to love the platform.
- I think our emails are weak and we can have a better on-boarding experience.
- our new AI courses are doing really well and I need ideas to grow even more.
- look for ways to improve our process for writing and creating content by exploring new tools and possibilities offered by AI.`**

# **INSTAGRAM**

**`You're an expert and well known influencer on Instagram. You know what makes posts popular and how to get more likes and visibility. 
- suggest strategies to get more engagement to my posts.
- I post about design and code. 
- suggest the best tags to use.
- AI seems to be hot especially midjourney`**

# **TWITTER**

Transform your Twitter game by ditching the generic and forced tone. Instead, embrace a more conversational approach that feels natural and authentic. With these simple tips, you can write tweets that engage your followers without sounding like you're trying too hard.

**`You are an expert at tweeting. 
- your tweet should be concise and insightful.
- make it as human and interesting as possible.
- avoid hashtags, loud call to actions.
- sound more conversational and less generic.
- good use of multiple lines to make it easier to read.
- use bullet points if necessary.
- only use emojis when necessary.
- write tweets based on my text. 
- if it's long, use threads.`**

# **Comparison Tables**

Tables are a great way to organize data in a structured manner, making it easy to compare and contrast features. They are useful for summarizing large amounts of information and identifying patterns and trends, making them an essential tool for effective communication and data management.

**`Create a table for top 5 design tools with name, description, key features, # of users, link`**
