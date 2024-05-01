source: https://websim.ai/c/v7HKAInBDBA5SrnC3

# Eliciting Rich User Inputs for AI Interaction

One of the key challenges in designing effective human-AI interactions is getting users to provide rich, nuanced inputs that capture their true intents and context. Simple text fields or dropdowns often fall short in expressing the full scope of what a user needs. In this spotlight, we explore techniques for **elicitation interfaces** that prompt users to share detailed, structured information to guide AI systems.

## Beyond Blank Boxes: Scaffolding User Input

The most basic input pattern is the freeform text field - a blank canvas inviting the user to type anything. While flexible, this puts the full burden of structuring and articulating the input on the user. For complex intents, this can lead to vague or incomplete expressions that leave the AI in the dark.

Elicitation interfaces add scaffolding to user input, guiding them to provide key details and parameters. A simple example is placeholder text in the input box suggesting what to enter:

[Briefly describe your image request...]

This hint helps users frame their input and set the right level of detail. But we can go further by breaking out separate fields for key aspects:

Subject:   [Person/animal/object in the image]
Setting:   [Location and surroundings] 
Style:     [Realistic, cartoon, abstract, ...]   
Mood:      [Emotional tone to convey]

This structured form prompts the user to consider multiple dimensions of their request. Each field constrains the input scope while still allowing freeform specifics.

![A web form titled 'Describe your image' with labeled text input fields for Subject, Setting, Style, and Mood, along with example values filled in each box.](https://dplmi.mit.edu/course-4.601/professors-detailed-notes/spotlight-on/structured-image-prompt.png)

Structured prompt fields guide users to express key aspects of their image request.

## Visual Elicitation: Sketches and Examples

For visual AI interactions like image editing or generative art, text inputs can still struggle to convey nuanced creative intents. Here elicitation interfaces can tap the power of examples and sketching to let users express ideas visually.

Imagine an AI-assisted drawing app that lets users sketch out rough lines or shapes that intuits into detailed figures or scenes. The interface might provide example sketch gestures to learn from:

![An animation of simple line sketch gestures being drawn on a canvas and autocompleting into detailed drawings, e.g. a circle becoming a face, a squiggle becoming a tree, an arch becoming a rainbow.](https://dplmi.mit.edu/course-4.601/professors-detailed-notes/spotlight-on/sketch-gestures.gif)

Example gestures inspire users with the range of visual intents the AI can interpret.

Or consider an AI graphic design tool that lets users define a layout by arranging example components on a canvas:

[Sidebar] [Headline Banner]

[Pull Quote]  [Body Text] 

[Image Inset]    [Caption]

As the user drags and resizes these placeholders, the AI infers the desired spatial relationships and generates real content to match.

![A blank web page layout with rectangular placeholder blocks labeled Sidebar, Headline Banner, Pull Quote, Body Text, Image Inset, and Caption arranged to define a sample article format.](https://dplmi.mit.edu/course-4.601/professors-detailed-notes/spotlight-on/layout-examples.png)

Manipulable example components help users express complex layout intents visually.

## Conversational Elicitation: Iterative Q&A

For intricate AI tasks like data analysis or code generation, even structured inputs can be inadequate to fully determine the user's needs. Here elicitation can take a conversational form, with the AI system engaging in iterative dialog to draw out key details and resolve ambiguities.

Picture a natural language database query system. Instead of just taking a freeform question and trying its best to parse it, the system could start a clarifying exchange:

User: How many customers bought products in the past month?

AI: To clarify your request:
- Which specific product categories are you interested in? 
- Do you want to include all customers or a particular segment?
- What exact date range should I use for "the past month"?

User: Include electronics and appliances. All customers. Use 5/15 to 6/15.  

AI: Thanks for the extra details. Here are the results for your query:
[Generated SQL and Result Table...]

This back-and-forth dialog helps fill in the blanks needed for a precise query. The AI uses its domain knowledge to ask relevant followups, and the user can give terser, more targeted responses. Elicitation becomes a cooperative effort.

![A chat interface showing a conversation between a User and AI. The user asks a high-level business question, the AI replies with clarifying questions about product categories, customer segments, and date ranges, the user provides short answers to each, and the AI generates the corresponding SQL query and result table.](https://dplmi.mit.edu/course-4.601/professors-detailed-notes/spotlight-on/conversational-query.png)

Conversational interfaces enable iterative elicitation of query details and intent.

## Elicitative Onboarding: First-Time Setups

Elicitation isn't just for ad hoc interactions - it can also guide users through first-time AI system setup and personalization. By front-loading rich context gathering, these onboarding flows can greatly improve ongoing AI interactions.

Consider an AI email assistant that helps manage your inbox. Rather than making the user fiddle with complex rules and filters, it could start with a friendly interview:

AI: To help me best organize your inbox:

- What types of emails are highest priority for you to see quickly? 
- Are there any senders whose messages you always want highlighted?
- How often do you typically like to be notified about new emails?
- ...  

The user's responses paint a picture of their email habits and preferences, creating a personalized starting point for the filters and features the AI then enacts.

![A friendly onboarding chat screen with an AI assistant avatar asking the user personalization questions about their email habits and preferences.](https://dplmi.mit.edu/course-4.601/professors-detailed-notes/spotlight-on/onboarding-interview.png)

Elicitative onboarding flows gather key user context to bootstrap personalized AI behavior.

> "Elicitation interfaces are like having a smart, curious friend who draws out your best ideas. They don't just passively take orders, but actively help you shape your thoughts."

## Principles of Effective Elicitation

Across these examples, we can distill some key principles for crafting effective AI elicitation interfaces:

- **Guide, don't dictate.** Provide structured prompts, but leave room for user specificity and creativity.
- **Speak the user's language.** Use domain-relevant terms and representations that match how users naturally think about the task.
- **Start broad, then narrow.** Begin with open-ended prompts to understand the high-level intent, then drill down to clarify key details.
- **Embrace multiple modalities.** Combine text, visual, and interactive techniques to elicit intents that are hard to express in just one format.
- **Make it a conversation.** Engage in back-and-forth dialog to progressively elicit details and build shared context.

By front-loading rich intent gathering through artful elicitation, we can create AI interactions that feel truly collaborative rather than just transactional. The machine isn't just passively waiting for instructions, but actively working with the user to understand their needs and shape the experience to match.

So next time you're designing an AI interaction flow, don't start with a blank box. Craft elicitation interfaces that engage the user's creativity and draw out their deepest intents. Prompt them to share the key ingredients, so the AI can cook up the perfect assistive recipe.