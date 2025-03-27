Simple Blog with Cloudflare Workers (Forked Version)

This project is a lightweight, serverless blog system built on Cloudflare Workers and KV storage, forked from [original repo]. 

this version offers several key advantages:

-Simplicity & Lightweight: A streamlined codebase with no external template engine dependencies (e.g., Mustache.js in Version B), making it easier to deploy and maintain.

-Performance Optimized: Direct HTML generation with built-in Markdown parsing, avoiding the overhead of dynamic template rendering, resulting in faster page loads.

-Granular Cache Control: Fine-tuned caching with per-page purge support (e.g., /admin/preview-and-purge), unlike Version B’s broader cache-clearing approach, enhancing efficiency for frequent updates.

-Integrated Editing Experience: Features a built-in Markdown editor and real-time preview functionality, providing a smoother content creation process compared to Version B’s reliance on external tools.

-Modern Security: Leverages Cloudflare Access for authentication, offering a more secure and scalable solution than Version B’s basic auth mechanism.

Ideal for users seeking a fast, simple, and efficient blogging platform without the complexity of advanced features like tags or themes. 

Contributions welcome!

