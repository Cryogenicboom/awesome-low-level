# Contribution Guidelines

We welcome contributions from anyone who wants to help improve the Awesome Low Level collection. You don't need to be an expert. If you find a useful resource, notice outdated information, spot a mistake, improve clarity of existing phrases, or have an idea that would improve the learning path, feel free to contribute.

## Before Contributing

- Read through the existing sections and follow the current structure and writing style.
- Check whether the resource already exists before adding it.
- Make sure the resource is relevant to low-level programming, system programming, computer systems, or one of the specialized fields covered here.
- Prefer high-quality resources such as books, university courses, official documentation, technical articles, well-maintained projects, and practical tutorials.
- Avoid adding resources just because they are popular. The resource should provide real value to someone learning the subject.
- Avoid adding large numbers of similar resources. The goal is to provide useful choices, not an overwhelming list.

## How Sections and Resources Are Structured

This repo isn't a plain list of links. Each section is written like a short guide: a bit of explanation first, then the resources that support it.

- **Start with an explanation.** Every section (or subsection) opens with one or more paragraphs explaining what the topic is, why it matters, and what someone will typically learn or work with in that area.
- **Use a `>` blockquote for extra context.** Additional notes, real-world context, common tools, or things worth knowing are added as a blockquote after the main explanation, not stuffed into the resource list.
- **Keep the resource list itself simple.** Resources are listed as bold links, generally without an inline description:

  ```md
  - **[Resource Name](https://example.com/)**
  ```

  The explanation paragraph and blockquote above the list are what give the resource its context, so most entries don't need their own description. Only add a short one-line explanation after a resource if it genuinely needs its own clarification that isn't already covered above (this should be the exception, not the norm):

  ```md
  - **[Resource Name](https://example.com/):** A short note only if the section text above doesn't already explain why it's here.
  ```

- **Order resources by priority.** Resources are generally listed in the order someone should go through them, not alphabetically. If you're adding a resource, place it where it makes the most sense in that priority order, not just at the end of the list.
- **Link important keywords to Wikipedia on first mention.** When your explanation introduces a technical term (e.g. pointers, memory addresses, logic gates, instruction set architecture), link it to its Wikipedia article the first time it appears in that section, the same way the rest of the README does:

  ```md
  You'll need to learn topics such as [pointers](https://en.wikipedia.org/wiki/Pointer_(computer_programming)) and [memory addresses](https://en.wikipedia.org/wiki/Memory_address).
  ```

  Only link a term the first time it shows up in a given section, not every time it's repeated afterward. Not every word needs a link, just the core technical terms someone might not already know.

## Resource Guidelines

When proposing a resource, make sure it has:

- **A working, direct link** to the resource itself (not a search result or a redirect).
- **A clear fit** for the section you're adding it to. If it doesn't fit an existing section well, consider whether it needs a new section instead (see below).

### Prefer

- Free or freely accessible resources when possible.
- Official documentation and primary sources.
- University courses and lectures.
- Well-written books and technical references.
- Hands-on projects and exercises.
- Resources that are actively maintained when maintenance is important.
- Resources that teach concepts clearly rather than simply providing quick answers.

### Avoid

- Low-quality or misleading tutorials.
- Duplicate resources that provide little additional value over what's already listed.
- Resources that are mostly promotional content.
- Dead or inaccessible links.
- Content that is unrelated to the section.
- Resources that encourage copying without understanding.

## Formatting Guidelines

Please keep the formatting consistent with the rest of the repository.

- Use Markdown headings to organize sections, matching the existing heading depth (`##`, `###`, `####`, etc.) rather than introducing new levels arbitrarily.
- Use bullet points for resource lists.
- Use bold text for resource names.
- Write explanations in clear, simple, and easy-to-read prose, matching the tone of the existing sections.
- Use `>` blockquotes for notes, extra context, and recommendations, the same way the rest of the README does.
- Keep the existing order and structure of sections unless there is a good reason to change them.
- Do not unnecessarily change formatting in unrelated sections.

## Adding a New Section

If you want to add a completely new topic or specialized field:

1. Make sure it fits the overall scope of the project.
2. Write an explanation of the topic, following the same style as the existing sections (what it is, why it matters, what tools or concepts are involved).
3. Add a `>` blockquote with extra context if it helps, the same way other sections do.
4. Add a small selection of high-quality resources, in priority order.
5. Update the Table of Contents to include the new section, matching the existing indentation and anchor-link style.
6. Keep the new section consistent with the existing structure and heading depth.

Please avoid creating a section for every small or highly specific topic. New sections should represent a meaningful area of low-level programming.

## Use of AI Tools

You're welcome to use AI tools to help polish your writing when contributing. For example, fixing grammar or tightening up a sentence you've already written.

However:

- **Write the explanation yourself first.** Section descriptions and context should reflect your own understanding, not something generated from scratch by an AI.
- **Don't paste AI-generated text directly into a contribution.** If a paragraph reads generically or doesn't sound like the rest of the README, it will likely be asked to be rewritten.
- **Keep it in your own voice.** Minor grammar or phrasing cleanup is fine. Wholesale AI-written sections are not, even if the resource you're adding is genuinely good.

## Pull Requests

When submitting a pull request:

- Clearly explain what you changed.
- Explain why the change is useful.
- Keep each pull request focused on a specific improvement when possible.
- Make sure links work before submitting.
- Check your Markdown formatting.
- Update the Table of Contents if you add or rename a section.
- Do not include unrelated changes in the same pull request.

Before submitting, review your changes and make sure they match the style and quality of the existing collection.