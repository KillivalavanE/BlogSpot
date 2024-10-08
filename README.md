
# 📝BlogSpot

**BlogSpot** is an AI-powered platform that automates blog creation, generating posts, images, and hashtags based on user input. It’s designed to help bloggers and content creators quickly produce high-quality, SEO-optimized content with minimal effort.


## API Reference

**OpenAI API**

**Davinci API (text generation)**:

- This API is used to generate blog content based on user input.
- Endpoint: https://api.openai.com/v1/completions
- Model: text-davinci-003
- Parameters include: prompt, temperature, max_tokens, top_p, frequency_penalty, and presence_penalty.

**DALL·E 2 API (image generation)**:

- This API generates images related to blog content.
- Endpoint: https://api.openai.com/v1/images/generations
- Parameters include: prompt, n, size, and response_format.

Both APIs require an API key for authorization, passed in the request headers.

## Features

*Autocorrect and Grammar Check:*

- Function: After users input their blog content, the platform performs thorough autocorrect and grammar checks.
- Purpose: Ensures that the final blog posts are error-free, professionally written, and polished, enhancing readability and quality.

*Image Generation:*

- Function: Utilizes the DALL·E 2 API to create images that are contextually relevant to the blog content.
- Storage: The generated images are stored in Cloudinary, providing a reliable and scalable solution for managing and retrieving images.
- Purpose: Enhances the visual appeal of blog posts with tailored images that complement the written content.

*Hashtags and Categories:*

- Function: Automatically generates relevant hashtags and assigns categories based on the content of the blog posts.
- Purpose: Optimizes blog posts for search engines and social media, helping users improve discoverability and engagement.


## Screenshots
![1](https://github.com/user-attachments/assets/da2492aa-7573-48d7-80be-bed829d80631)
![2](https://github.com/user-attachments/assets/f0049f64-e1a0-42c7-a7b4-95004c272102)
![3](https://github.com/user-attachments/assets/1cf675a2-0046-4139-92da-d0e47c3157d1)
![4](https://github.com/user-attachments/assets/536bd951-87fe-439d-b8e5-1d8b4a7bc988)


## Tech Stack

**Client:** React, Redux, TailwindCSS, 

**Server:** Node, Express, MongoDB

**External API:** OpenAI API

