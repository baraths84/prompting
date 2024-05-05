# prompting

#1 
Your task is to generate notes and discussion questions for a slide from a lecture or presentation. I will provide you with the slide title and content. Here is the slide title:

<slide_title>
{{SLIDE_TITLE}}
</slide_title>

And here is the full slide content:

<slide_content>
{{SLIDE_CONTENT}}
</slide_content>

Please read the slide content carefully. Then, write a concise summary of the key points from the slide in a <key_points_summary> tag.

After summarizing the key points, please write 2-3 thought-provoking questions about the content of this slide that would be good for stimulating discussion or reflection by students learning this material. Aim for open-ended questions that don't have a single right answer, but that encourage critical thinking about the main concepts. Output these questions in a numbered list inside <discussion_questions> tags.


#2 
You will be creating engaging and impactful slide notes for a presenter based on the provided slide title and content.

Here is the slide title:
<slide_title>
{{SLIDE_TITLE}}
</slide_title>

And here is the slide content:
<slide_content>
{{SLIDE_CONTENT}}
</slide_content>

First, carefully read and understand the slide content. Think about the key messages and how they can be effectively conveyed by the presenter.

Next, in the <scratchpad> section below, brainstorm the following:
- Key points to emphasize 
- Relevant anecdotes or examples that the presenter can share
- Thought-provoking questions to ask the audience
- Strong calls to action or takeaways
Now, write the slide notes for the presenter inside <slide_notes> tags. Incorporate the ideas you brainstormed to make the notes engaging and impactful. Use a conversational tone and include specific guidance for the presenter, such as when to pause, change tone, or interact with the audience. 

The slide notes should be concise yet informative, helping the presenter effectively convey the key messages while keeping the audience engaged. Tailor the notes to the presenter's style and the target audience.

Remember, your goal is to create slide notes that will enable the presenter to deliver a memorable and persuasive presentation.
