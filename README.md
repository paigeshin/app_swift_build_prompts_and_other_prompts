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

```
You are an Al programming assistant.
- Follow the user's requirements carefully & to the letter.
- First think step-by-step - describe your plan for what to build in pseudocode, written out in great detail
- Then output the code in a single codeblock
- Minimize any other prose
```

# **BEGINNER-FRIENDLY FOR IOS**

Specify the areas of expertise needed in your project and your coding style. Let’s start with a beginner-friendly starting prompt for iOS and web.

iOS is the easiest since all you need is Xcode and everything is available from the get-go. No need for third-party libraries, especially for beginners.

```
You’re an expert in iOS dev, SwiftUI, iOS architecture and a robust architecture with the best practices.

- Provide steps to create a new project in Xcode.
```

# **BEGINNER-FRIENDLY FOR WEB**

Web projects are more open and rely on many services and frameworks. You will be faced with dozens of choices, but let’s start with a popular one: React and CodeSandbox. It’s one of the easiest way to start.

```
You're a web developer that specializes in React and CSS.

- For CSS, use Styled-Components.
- Use CodeSandbox to quickly build prototypes.
- Provide steps to create a new project in CodeSandbox.
- Provide steps to install third party libraries that we need.
- Create everything inside App.js
```

# **START SIMPLE**

When starting to work with GPT-4, it's best to avoid creating complicated projects at first. The AI may be slow and pause randomly due to its limit in number of tokens per post. To avoid frustration, it's recommended to not ask for too much information all at once and to add details incrementally. For example, if you're asking for steps, it's better to wait for the next post to ask about the concept.

- In this example, we’re creating elements in a specific order.

```
Create a card with cover image, title, divider, subtitle, text, author (avatar + name).
```

# **WEB FULL STACK**

Most full-fledged web projects require their own customized stack. A popular one today is React with Next.js and Vercel.

```
You're a seasoned web developer that specializes in React, Next.js, Vercel and CSS.

- For content, use Contentful and GraphQL.
- For Authentification use Firebase and Firestore.
- We will need the Vimeo API to serve videos.
- Use Dropbox to get downloabable files for our paid customers
```

# **CODING STYLE**

Code outputs are often too slow to write and too long for a single post. So it’s a good idea to focus on new changes. It may be best to split into multiple files and components. This requires more organization but is future-proof.

```
Make your code as short, easy to understand and concise as possible.
- Only focus on code that is new or that are changing during new requests.- Split into components and small files that are no longer than 100 lines of code.
```

# **USER EXPERIENCE**

It never hurts to explore opportunities to make the project sustainable by understanding what features are essential and what features may be valuable to premium users.

```
Develop apps that are beautifully designed with a great user experience
- Think like an entrepreneur and give advice on new features and how we could monetize this app.
```

# **Concepts and Development**

At the beginning of the project, it’s best to keep it clear and simple with a concept that can be achieved in a single post. Be descriptive, use examples, and focus on small wins. Here are some examples:

```
Build a SwiftUI chat app that talks to a trainable AI.

I want a nice vector pattern like in the Apple Card hologram that animates on tap in SwiftUI.

Create a fun iOS app in SwiftUI that does colour matching. There will be two big circles next to each other and you can swipe vertically on it to change the brightness, horizontally to change the hue. Tolerance level for accepted answer should be not too hard at first and gradually harder. There should be a timer, and you have 10 secs to answer. There should be a button to submit answer below.

Create a blur card that emits particles only when it moves. Can you add a drag gesture that responds in a physics way, with the circles following the drag but also lagging a little bit like in real life with inertia, like hair moving and slower strands catching up.
```

# **ERRORS AND DEBUGGING**

Your code won’t always work. Sometimes, you need to ask multiple times. When you encounter errors, don’t hesitate to paste the error messages and give the specific line number or the element names that are erroneous.

```
{paste error message}
{error at line #}
{describe user experience issue}
```

# **UPDATE CODE AND FOCUS ON CHANGES**

When you deal with a lot of code, the responses from GPT-4 will be slow, repetitive and hang at random places. To make the experience better, ask to only show code that changes. Also, the AI will tend to forget about your code, so it’s a good idea to regularly paste your entire code to keep it up-to-date.

```
{Paste code}
{Ask change}
Focus only on code that changes
```

If the code keeps hanging, you can ask to continue from specific places.

```
Continue from {step # or "text from response"}
```

# **SELF IMPROVEMENTS**

AI can sometimes make errors and not fully meet the requirements you provide. Rather than suggesting specific changes, you can prompt ChatGPT to analyze and learn from its mistakes.

```
Did you fulfill all my requirements?
Is there a mistake in your code?
Review your code and offer improvements
```

# **Read Documentation and Summarize**

Experience the ease of accessing documentation with ChatGPT. Simply copy and paste an entire page of documentation, then ask for a summary or specific questions about it. This exceptional feature makes information readily available to everyone, without the need to purchase specialized products. Effortlessly explore documentations from sources like Stripe, React, Swift, and more with ChatGPT's unprecedented capabilities.

```
Read this documentation and summarize in bullet points:

{paste long documentation}
```

# **Midjourney Prompts**

By using this prompt, you can provide a brief set of keywords that describe the desired image.

```
You are a master at creating prompts for Midjourney v5
- create a prompt based on my short description
- follow this formula: A detailed image of [subject] [doing something interesting] during (time of day], taken with a [type of camera], using [type of lens] with cinematic lighting --v 5 --ar 16:9
```

# **Copywriting**

GPT-4 has the potential to design product pages by generating creative and engaging content for product descriptions, titles, and images. It can also generate personalized product recommendations based on user preferences, search history, and behavior. This can enhance the overall customer experience and lead to increased sales for businesses.

```
You are a thoughtful, helpful and expert copywriter for web and mobile apps. 
- All your writing should be limited to a paragraph with a max of 3 sentences.
- Write in a simple way that anyone can understand.
- Be as concise as possible. Less is better.
- Write in Markdown format with providing links to products mentioned.
```

# **Product Strategy**

The key to a successful product rests not only on how good the product is but also how well do you present it to the world. You should think about distribution, partnerships and strategies for email, social media and SEO.

# **ENTREPRENEUR**

```
You are my entrepreneur friend and you are an expert at turning good products into amazing opportunities to reach more audience and monetize better.
- I have an education platform that teaches hands on lessons about design and code. 
- I want to make it better to beginners and get them to love the platform.
- I think our emails are weak and we can have a better on-boarding experience.
- our new AI courses are doing really well and I need ideas to grow even more.
- look for ways to improve our process for writing and creating content by exploring new tools and possibilities offered by AI.
```

# **INSTAGRAM**

```
You're an expert and well known influencer on Instagram. You know what makes posts popular and how to get more likes and visibility. 
- suggest strategies to get more engagement to my posts.
- I post about design and code. 
- suggest the best tags to use.
- AI seems to be hot especially midjourney
```

# **TWITTER**

Transform your Twitter game by ditching the generic and forced tone. Instead, embrace a more conversational approach that feels natural and authentic. With these simple tips, you can write tweets that engage your followers without sounding like you're trying too hard.

```
You are an expert at tweeting. 
- your tweet should be concise and insightful.
- make it as human and interesting as possible.
- avoid hashtags, loud call to actions.
- sound more conversational and less generic.
- good use of multiple lines to make it easier to read.
- use bullet points if necessary.
- only use emojis when necessary.
- write tweets based on my text. 
- if it's long, use threads.
```

# **Comparison Tables**

Tables are a great way to organize data in a structured manner, making it easy to compare and contrast features. They are useful for summarizing large amounts of information and identifying patterns and trends, making them an essential tool for effective communication and data management.

```
Create a table for top 5 design tools with name, description, key features, # of users, link
```

# **Work from Previous Code**

Starting with your existing code can save you a lot of time when using ChatGPT. Provide your current code snippet to ChatGPT and ask it to create a sunflower pattern. Make sure to specify that everything should be kept in a single file for easier integration.

```
{Insert previous code}

Create a sunflower pattern and keep everything in 1 file
```

# **BE SPECIFIC WITH YOUR INSTRUCTIONS**

When working with ChatGPT, it's essential to be as specific as possible with your instructions. This will help the AI understand your requirements better and generate more accurate results.

# **Small Tasks**

Breaking down your project into smaller tasks makes it easier for ChatGPT to provide you with the necessary code changes. For example, you might want to resize the animation to full screen, remove the yellow background, and set the circles to fill color while removing the stroke.

```
resize to full screen
- remove yellow background
- set the circles to fill color and remove stroke.
```

# **BREAK TASKS INTO SMALLER PIECES**

Dividing tasks into smaller pieces ensures that ChatGPT can provide you with precise code changes for each task, allowing you to have better control over the customization process.

# **Randomized Colors**

Ask ChatGPT to generate randomized colors inspired by Apple's rainbow color palette to introduce a colorful variation to the animation. This way, you can create a visually appealing animation without manually selecting colors.

```
Can you make the colors randomized in a rainbow inspired by Apple's colors.
```

# **ASK FOR COLOR INSPIRATION**

When looking for color schemes, feel free to ask ChatGPT for inspiration or provide specific color palettes for the AI to work with.

# **Circle Sizes**

Customizing circle sizes and background colors adds a unique touch to your animation. Request ChatGPT to make the circles gradually bigger toward the center and smaller outside, with a black background.

```
Make the circles gradually bigger in the center and smaller outside
- Make the background black
```

# **EXPERIMENT WITH SIZES AND POSITIONS**

Don't hesitate to experiment with different sizes, positions, and other properties of your elements. ChatGPT can help you generate the necessary code to achieve your desired effect.

# **Show Code Changes**

When you need to apply multiple changes, it's helpful to see only the code changes rather than the entire code snippet. In your prompt, ask ChatGPT to show only the code changes. For instance, you might want to make the circles five times bigger and see the code changes for this specific modification.

```
Make the circles 5x bigger
- Show me code changes only
```

# **REQUEST CODE CHANGES ONLY**

Requesting only code changes helps you understand which parts of the code were modified and allows you to implement the changes more efficiently.

# **Update Code**

Once you've received the updated code from ChatGPT, paste the entire code in your Xcode project to implement the changes. Test the animation to ensure it reflects your customizations.

```
Update code: {paste entire code}
```

# **Animate on Tap**

To add an interactive element to your animation, ask ChatGPT to change the pattern to a galaxy when the user taps on it. Be specific with your prompt to ensure that the AI generates the correct code for the new pattern and tap interaction.

```
Animate on tap to another pattern: Galaxy
```

Animating an element in response to a tap gesture is a common way to create interactive and engaging user interfaces. In SwiftUI, you can achieve this by combining tap gestures, the **`withAnimation`** function, and state properties. In this section, we will discuss these concepts and provide examples of how to animate on tap.

# **ONTAPGESTURE MODIFIER**

The **`onTapGesture`** modifier is a convenient way to attach a tap gesture recognizer to a view in SwiftUI. It accepts an action closure that will be executed when the user taps the view. The **`onTapGesture`** modifier is more concise than using the **`gesture`** modifier with a **`TapGesture`**.

```swift
// Element
.onTapGesture {
		// Perform an action on tap
}
```

# **WITHANIMATION**

**`withAnimation`** is a function in SwiftUI that allows you to perform an animated change to a view. It takes an animation description as its argument and runs the specified closure inside an animation context. This means any changes to animatable properties inside the closure will be animated.

```swift
withAnimation(.spring()) {
    // Make changes to animatable properties
}
```

# **STATES**

In SwiftUI, **`@State`** is a property wrapper that allows you to store mutable state inside a view. By using state properties, you can keep track of the current state of your view and update it in response to user interactions, such as a tap gesture.

# **Entire Code for Section**

When you need the complete code for a specific section or view, you can request it from ChatGPT. This makes it easier to implement changes, especially when dealing with complex animations.

```
Can you give me the entire code for SunflowerView?
```

# **REQUEST COMPLETE CODE SECTIONS**

Asking for the entire code of a section allows you to implement changes more efficiently and avoid confusion when dealing with multiple code snippets.

# **Animation Timing**

To make your animation feel more dynamic and natural, ask ChatGPT to change the animation timing to use a spring effect. This will provide a more engaging and interactive experience for users.

```
The animation should use spring
```

Animation timing plays a crucial role in creating smooth and visually appealing animations. By controlling the timing of your animations, you can create a more natural and engaging user experience. In this section, we will discuss various animation timing options, provide examples, and offer tips on popular techniques.

# **TIMING OPTIONS**

1. **Linear:** A linear animation progresses at a constant pace from start to finish, with no acceleration or deceleration. This can sometimes result in a more mechanical feel.
2. **Ease-in:** Ease-in animations start slowly and gradually accelerate. This creates a sense of objects gradually picking up speed, making the animation feel more natural.
3. **Ease-out:** Ease-out animations start quickly and gradually decelerate. This simulates objects slowing down before coming to a stop, again providing a more natural feel.
4. **Ease-in-out:** Combining ease-in and ease-out, this animation starts slowly, accelerates, and then decelerates before stopping. It can be used to create smooth and fluid animations.
5. **Spring:** Spring animations create a bouncy effect, simulating the behavior of a spring. They can be used to create playful and dynamic animations.

```swift
.linear(duration: 2.0)
.easeIn(duration: 2.0)
.easeOut(duration: 2.0)
.easeInOut(duration: 2.0)
.spring(response: 0.5, dampingFraction: 0.5, blendDuration: 0)
```

# **TIPS AND POPULAR TECHNIQUES**

1. **Match animation timing to user expectations:** Choose the appropriate timing function based on the nature of the animation and the user's expectations. For example, use ease-out for objects that are expected to slow down before coming to a stop, and spring for animations that need to feel more playful and dynamic.
2. **Experiment with timing:** Don't be afraid to experiment with different timing functions and durations to create the desired effect. You can also combine multiple timing functions for complex animations.
3. **Custom timing curves:** In some cases, you might need more control over the animation timing. SwiftUI allows you to create custom timing curves using **`timingCurve(_: _: _: _: duration:)`** function, which provides even greater flexibility.
4. **Animate layout changes:** SwiftUI makes it easy to animate layout changes with the help of animation timing functions. Use these functions to smoothly transition between different layout states.
5. **Coordinated animations:** When creating complex animations with multiple elements, consider coordinating the timing of each element to create a more cohesive and visually appealing experience.

# **Expanding the Pattern**

If you want your animation to cover more of the screen, ask ChatGPT to spread out the circles and create a longer strand. This will create a more immersive visual experience for users.

```
**can you make the circles spread out more so that they fill the screen more, meaning longer strand**
```

# **ADJUST PATTERNS AND LAYOUTS**

Experiment with different patterns, layouts, and positioning to create a unique animation. ChatGPT can help you generate the code needed to implement these changes.

# **Fill Blank Space**

To make your galaxy pattern more intricate and visually interesting, request that ChatGPT increase the number of turns in the pattern, filling more of the blank space.

```
The galaxy circular pattern should have more turns unto itself to fill more the blank space
```

# **FINE-TUNE YOUR PATTERNS**

Don't hesitate to fine-tune your patterns and animations by adjusting various properties, such as turn count, spacing, and positioning. ChatGPT can provide you with the necessary code to achieve your desired result.

# **Layout**

By using prompts in ChatGPT, we can create an efficient design process. Designing in prompt allows you to generate code using natural language, making it more context-oriented and sentence-based as opposed to traditional coding, which is more programmatic and word-oriented.

```
You're an expert in iOS development, SwiftUI and animations.
- Give all the code in one file: ContentView.
- Make the background black.
- Create a card 360x240, padding 30, corner radius 30, gradient top left, #8E5AF7 to #5D11F7.
- Outline gradient top left, white 0.5 opacity, clear, white 0.5 opacity. 
- Content align left, each line is a row: 

Debit card (headline)
**** 0941 (body)
spacer
Valid Thru 06/05 (caption), spacer, sf symbol apple logo (large title)
```

ChatGPT can help you create a layout with ease. By providing specific guidelines and details such as card size, padding, and corner radius, you can generate the required code for your layout in SwiftUI.

# **DYNAMIC TYPE**

Dynamic Type is an essential feature in iOS development, enabling developers to create more accessible and user-friendly apps by automatically adjusting the font size based on user preferences. This feature allows users to choose their preferred text size in the iOS Settings app, making the text easier to read and navigate for users with visual impairments or those who prefer larger or smaller text.

**How Dynamic Type works:**

1. Built-in styles: iOS provides predefined text styles, such as large title, title, headline, body, callout, subhead, footnote, and caption. Each style is associated with a specific font size and weight. By using these styles, you ensure your app's text adheres to the iOS Human Interface Guidelines and benefits from Dynamic Type's automatic adjustments.
2. Scaling: When users change their preferred text size in the iOS Settings app, Dynamic Type scales the text in your app accordingly. The text will automatically resize, ensuring a consistent and comfortable reading experience for users with different preferences.
3. Customization: You can customize the Dynamic Type styles to suit your app's design, by modifying font, weight, or other attributes. However, it's essential to maintain the style names provided by iOS to ensure Dynamic Type works correctly.

To implement Dynamic Type in SwiftUI, use the **`.font()`** modifier with a predefined text style:

```swift
Text("Debit Card")
	.font(.headline)
```

# **GRADIENT**

To create a custom gradient in SwiftUI, you can use hex colors in your prompts. Chat GPT will generate the required code, including the color extension for utilizing hex color values.

```swift
LinearGradient(gradient: Gradient(colors: [Color(hex: "#8E5AF7"), Color(hex: "#5D11F7")]), startPoint: .topLeading, endPoint: .bottomTrailing)
```

# **OUTLINE GRADIENT**

By specifying the gradient outline and its properties in your prompt, you can create visually appealing and unique UI elements for your app. ChatGPT will generate the code for the gradient, including the start and end points for a diagonal gradient.

```swift
RoundedRectangle(cornerRadius: 30).strokeBorder(gradientOutline, lineWidth: 2)
```

# **SPACER**

A spacer in SwiftUI is used to create space between UI elements. By including a spacer in your prompt, you can push UI elements to desired positions and create a visually balanced layout for your app.

```swift
Spacer()
```

# **SF SYMBOLS**

SF Symbols is a collection of over 3,000 icons designed by Apple and integrated into the iOS system. These icons are vector-based and designed to work seamlessly with SwiftUI and UIKit, ensuring consistent and harmonious design across apps.

**Benefits of using SF Symbols:**

1. Consistency: SF Symbols are designed by Apple to complement the San Francisco font, which is the default font for iOS apps. By using these symbols, you ensure a consistent appearance and experience throughout your app and across the iOS ecosystem.
2. Scalability: SF Symbols are vector-based, meaning they can be scaled without losing quality. This allows you to use the same symbol in various sizes and contexts without worrying about pixelation or distortion.
3. Accessibility: SF Symbols are designed with accessibility in mind, offering a comprehensive range of symbols that can be used for essential functions and informative purposes. Using these symbols ensures your app remains accessible and easy to navigate for users with disabilities.

To use an SF Symbol in SwiftUI, use the **`Image(systemName:)`** initializer:

```swift
Image(systemName: "applelogo")
```

# **Create Component**

To make our code more manageable, we will create a separate component for the card. We will create a **`CardView`** that will have all the styling and layout code for the card. This will keep our **`ContentView`** clean and make it easier to maintain and apply the drag gesture later.

```
Create a component for the Card
```

# **Drag Gesture**

Next, we will make the card draggable horizontally and vertically. We will use SwiftUI's built-in drag gesture functionality to achieve this. We will create a **`@State`** variable called **`cardOffset`**, which will store the current X and Y offsets of the card. Then, we will attach a **`DragGesture`** to our **`CardView`** and update the **`cardOffset`** as the card is dragged.

To reset the card back to its original position, we will animate the **`cardOffset`** back to (0, 0) when the drag gesture ends. This will give a smooth transition as the card snaps back into place.

```
- Make the card draggable horizontally and vertically and reset after release with animation.
- Use Apple's best practices.

Give me the full code only for views that change. 
Make it easy to copy and paste the full code.
```

# **3D Rotate**

Now that our card is draggable, let's add some 3D rotation to make it more interactive. We will use the **`rotation3DEffect`** modifier to apply a 3D rotation based on the direction the card is being dragged.

We will use the **`cardOffset.width`** value to determine the rotation angle. This way, as the card is dragged left or right, the rotation angle will change accordingly. You can adjust the rotation speed by dividing the width by a different number – a smaller number will create a sharper rotation, while a larger number will create a more subtle rotation.

```
Can you make the card 3D rotate based on the direction that it's dragging towards.
```

# **ROTATION 3D EFFECT**

To further customize the 3D rotation, you can experiment with the rotation axis. By default, the rotation axis is set to (0, 1, 0), which means the card will rotate around the Y-axis. You can change the axis values to create different rotation effects.

For example, if you set the rotation axis to (1, 0, 0), the card will rotate around the X-axis. You can also try using negative values to reverse the rotation direction.

Don't forget to update your code and inform ChatGPT about any changes you make, as it will not be aware of them unless you tell it explicitly.

# **CAEmitterCell**

CAEmitterCell is a framework within SwiftUI or Swift that allows us to create and animate particles in our apps. With CAEmitterCell and CAEmitterLayer, you can create a range of particle effects by adjusting various properties such as emitter shape, size, position, cells, birth rate, lifetime, scale, and more. In our example, we will use UIViewRepresentable to utilize CAEmitterLayer, which is not specific to SwiftUI but rather specific to UIKit.

```
Make the card emit white particles around and above it.
- Each particle has a size of 20.
- Give me the full code for each view that changes.
```

# **Customize the Particles**

When customizing the particles, you may encounter issues with the color, transparency, and blending of the particles. In our example, we wanted the particles to be white with random opacity, and we wanted the size to change as they spread out. To achieve this, we modified the alpha range, alpha seed, and scale speed for the CAEmitterCell.

```
Make the particles white with random opacity and reduce in size as they animate

The particles appear as black
```

# **Allows Hit Testing**

In our example, we noticed that the particles were interfering with the drag functionality of the card view. To resolve this issue, we set the "allowsHitTesting" modifier to false. This ensures that the particles are not interactive, and the drag functionality works smoothly.

```
The particles are in the way of the drag.
```

# **Particles Position**

Our initial particle effect had the particles emitting from the center of the card view. To create a more visually appealing effect, we wanted the particles to spread along the border of the card instead. To achieve this, we created multiple emitter cells, positioning them along the border. By tweaking the birth rate, velocity, and lifetime of the particles, we were able to create a more continuous animation that spreads towards the border and not the center.

```
Make the particles spread along the border of the card.

The particles seem to reset their animation every second. Can you make the animation continuous and spread more towards the border and not the center?
```

# **Particles Color**

We can randomize the colors for the particles by selecting from a range of colors, such as blue, purple, pink, and cyan. This is achieved by modifying the particle emitter's properties, specifically the particleColor property, allowing for more visually appealing and dynamic particle effects in the animation.

```
Can you randomize the colors for the particles in blue, purple, pink and cyan.
```

# **Blend Mode**

Blend mode is a technique used to combine the colors of the particles with the colors of the background or other layers in the scene. In this tutorial, we use the blend mode 'Color Dodge' to create a unique and engaging visual effect. To apply the blend mode, we add a modifier to the Particle Emitter View in SwiftUI, making sure to specify that we are using SwiftUI to apply the blend mode.

```
ParticleEmitterView should have a blend mode of color dodge.

That doesn't work. Use SwiftUI to apply the blend mode.
```

To apply a blend mode to the particle emitter view, we will use SwiftUI. Add the following line of code after the **`allowsHitTesting`** in the ContentView:

```
.blendMode(.colorDodge)
```

# **Glow**

Adding a glow effect can enhance the appearance of our particles and create a more visually striking result. In this tutorial, we add a glow to the card by using the shadow property in SwiftUI. This property has four values: color, radius, x, and y. The radius determines the blur strength, creating a glowing effect around the card. By modifying these values, we can customize the intensity and appearance of the glow.

```
Add a glow to the card with color #5D11F7 and radius 120.
```

# **Dragging**

To make the particle animation interactive, we introduce dragging behavior. We want the particles' birth rate to increase when the card is being dragged and decrease when it's released. To achieve this, we use SwiftUI's DragGesture, which provides onChanged and onEnded callbacks. We update the particle emitter's birth rate accordingly, providing a more engaging and dynamic user experience.

This line of code sets the birth rate of the emitter cell (the rate at which particles are emitted) based on the dragging state. If the user is currently dragging (**`isDragging`** is true), the birth rate is set to 20 particles per second. If the user is not dragging (**`isDragging`** is false), the birth rate is set to 5 particles per second.

```
Change the emitterCell.birthRate = 20 when dragging happens and 5 on release.
```

This line indicates that the dragging detection is not working as expected, meaning the changes in birth rate are not being triggered when the user drags or releases.

```
It doesn't seem to detect the dragging change.

Is there a better way to write this?
```

This code snippet presents a better approach to updating the cell properties based on the dragging state.

- **`cell.velocity`**: This line sets the velocity of the particles based on the dragging state. If the user is dragging, the velocity is set to 100 units. If not, the velocity is set to 50 units.
- **`cell.lifetime`**: This line sets the lifetime of the particles based on the dragging state. If the user is dragging, the lifetime is set to 3 seconds. If not, the lifetime is set to 2 seconds.
- **`cell.scale`**: This line sets the scale of the particles based on the dragging state. If the user is dragging, the scale is set to 0.1. If not, the scale is set to 0.05.

By using this approach, you can modify the properties of the particles based on the dragging state. However, you still need to ensure that the **`isDragging`** variable is updated correctly as the user interacts with the view. To achieve this, you should use SwiftUI's DragGesture and its onChanged and onEnded callbacks to update the **`isDragging`** state.

```swift
cell.velocity = isDragging ? 100 : 50
cell.lifetime = isDragging ? 3 : 2
cell.scale = isDragging ? 0.1 : 0.05
```

# **Overlay**

The overlay is used to place one view on top of another, creating a composite effect. In this tutorial, we use the overlay to combine the glow effect with the particle animation. This step is essential because the blend mode 'Color Dodge' does not work well against a dark background, causing the particles to appear cropped. By using an overlay, we can ensure the particles are displayed correctly, regardless of the background color.

```swift
.overlay(
    ZStack {
        RoundedRectangle(cornerRadius: 30).stroke(.linearGradient(colors: [.white.opacity(0.6), .clear, .white.opacity(0.3)], startPoint: .topLeading, endPoint: .bottomTrailing))
        RoundedRectangle(cornerRadius: 30).stroke(.linearGradient(colors: [.white.opacity(0.4), .clear, .white.opacity(0.3)], startPoint: .topLeading, endPoint: .bottomTrailing), lineWidth: 20)
            .blur(radius: 30)
        RoundedRectangle(cornerRadius: 30).stroke(.linearGradient(colors: [Color(#colorLiteral(red: 0.5568627715, green: 0.3529411852, blue: 0.9686274529, alpha: 1)).opacity(1), Color(#colorLiteral(red: 0.5568627715, green: 0.3529411852, blue: 0.9686274529, alpha: 1)).opacity(0.6), Color(#colorLiteral(red: 0.5568627715, green: 0.3529411852, blue: 0.9686274529, alpha: 1)).opacity(1)], startPoint: .topLeading, endPoint: .bottomTrailing), lineWidth: 20)
            .blur(radius: 50)
            .opacity(isDragging ? 1 : 0)
        RoundedRectangle(cornerRadius: 30).fill(.linearGradient(colors: [Color(#colorLiteral(red: 0.5568627715, green: 0.3529411852, blue: 0.9686274529, alpha: 1)), Color(#colorLiteral(red: 0.5568627715, green: 0.3529411852, blue: 0.9686274529, alpha: 1)), Color(#colorLiteral(red: 0.2392156869, green: 0.6745098233, blue: 0.9686274529, alpha: 1)), Color(#colorLiteral(red: 0.4745098054, green: 0.8392156959, blue: 0.9764705896, alpha: 1))], startPoint: .topLeading, endPoint: .bottomTrailing))
            .blendMode(.overlay)
    }
)
```
