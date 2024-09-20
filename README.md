# Agora Lab Blog

Welcome to the **Agora Lab Blog**! This is an open-source platform where anyone can contribute their insights, research, and thoughts on artificial intelligence & machine learning. Our goal is to build a rich resource of knowledge that reflects the vibrant community around AI.

## How to Contribute

We welcome contributions from all members of the AI community. To submit a blog post, please follow the steps below:

1. **Fork the Repository**: Click the "Fork" button at the top right of this repository to create a copy of it under your GitHub account.

2. **Create a New Folder**: Navigate to the `posts` folder in your local copy of the repository. Here, create a new folder for your post. The name of this folder should be unique and use underscore separation (e.g., `understanding_swarms`).

3. **Add Your Post**: Inside your new post folder, create an `index.qmd` file. In this file, begin with a YAML header that includes the following required fields:

    ```yaml
    ---
    title: "Your Blog Title"
    description: "A brief description of your blog post."
    author: "Your Name"
    date: "YYYY-MM-DD"
    image: "your_thumbnail.png"
    categories: [tag1, tag2, tag3]
    bibliography: references.bib
    toc: true
    toc-depth: 3
    nocite: |
    @*
    ---
    ```

   Here’s an example header for reference:

    ```yaml
    ---
    title: "Understanding Swarms: Coordinated Intelligence for Complex Problem Solving"
    description: "An in-depth look at the Swarms framework, which allows scalable multi-agent collaboration using AI. Discover how agents work together to perform complex tasks autonomously."
    author: "Jack Tol"
    date: "2024-09-05"
    image: "thumbnail.png"
    categories: [AI, multi-agent systems, swarms, open-source, automation]
    bibliography: references.bib
    toc: true
    toc-depth: 3
    nocite: |
    @*
    ---
    ```

4. **Write Your Blog**: Below the YAML header, write your blog content using Markdown formatting.

5. **Preview Your Changes**: Before submitting your changes, it is highly recommended that you render your blog locally. To do this, you will need to install [Quarto](https://quarto.org/docs/get-started/), a tool for rendering Markdown documents. Follow the installation instructions provided on the Quarto documentation site.

6. **Submit a Pull Request**: After you have written and previewed your blog, commit your changes and submit a pull request to the main repository. A review team will go through your submission, and if approved, we will reach out to you about publishing your blog!

## About Agora Lab

Agora Lab is an open-source collective of AI engineers and creators with a mission to harness the power of artificial intelligence for the betterment of humanity. Our projects cover multiple areas, emphasizing open collaboration and high-impact results. We encourage contributions and discussions within our community, maintaining transparency and accessibility in all our endeavors.

For more information on our projects, values, and opportunities for engagement, please read through our other documentation. If you have any questions, feel free to reach out!

---
Thank you for becoming a part of the **Agora Lab Blog**. We look forward to your contributions!
