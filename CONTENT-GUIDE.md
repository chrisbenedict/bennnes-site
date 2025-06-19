# Blog Post Templates

## Cooking Post Template

Copy this template when adding new cooking posts to `cooking.html`:

```html
<article class="post">
    <h2>Your Post Title Here</h2>
    <p class="post-date">Month Day, 2025</p>
    <p>Your opening paragraph here...</p>
    <p>Continue with your content. You can include:</p>
    <ul>
        <li>Ingredient lists</li>
        <li>Cooking tips</li>
        <li>Step-by-step instructions</li>
        <li>Personal observations</li>
    </ul>
    <p>More paragraphs as needed...</p>
</article>
```

## Random Thoughts Template

Copy this template when adding new posts to `random.html`:

```html
<article class="post">
    <h2>Your Thought-Provoking Title</h2>
    <p class="post-date">Month Day, 2025</p>
    <p>Your opening thought or observation...</p>
    <p>Expand on your ideas here. Keep the tone conversational and authentic.</p>
    <p>End with something that ties it all together or leaves the reader thinking.</p>
</article>
```

## Homepage Updates

When you add new posts, update the "Recent Posts" section on `index.html`:

```html
<article class="post-card">
    <h3>Your New Post Title</h3>
    <p>A brief preview or excerpt from your post...</p>
    <a href="cooking.html" class="read-more">Read more</a>
</article>
```

## Content Guidelines

### Writing Style
- **Be authentic** - write in your own voice
- **Keep it conversational** - like you're talking to a friend
- **Focus on stories** - people connect with personal experiences
- **Use specific details** - they make your writing more engaging

### Post Structure
- **Start with a hook** - grab attention in the first sentence
- **Use short paragraphs** - easier to read on all devices
- **Include personal insights** - what did you learn or observe?
- **End with impact** - leave readers with something to think about

### Technical Notes
- **Always include the date** with class `post-date`
- **Keep titles descriptive** but not too long
- **Maintain the minimalist aesthetic** - content is king
- **Test on mobile** - open files in your browser and resize

## Quick Workflow

1. **Write your post** using the templates above
2. **Add to appropriate page** (cooking.html or random.html)
3. **Update homepage** with a preview card
4. **Preview locally** by opening the HTML file in your browser
5. **Commit and push** to GitHub
6. **Check live site** in a few minutes

Remember: The beauty of this setup is its simplicity. Focus on writing great content, and the minimalist design will make it shine!
