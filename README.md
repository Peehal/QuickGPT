QuickGPT – AI Chatbot Application (MERN + Gemini + ImageKit)

QuickGPT is a full-stack AI chatbot application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) with integrated Google
Gemini AI, OpenAI React SDK, and ImageKit for AI-generated images.
It allows users to sign up, generate AI text, generate images, and purchase credits through an online payment gateway.


FEATURES
Secure Authentication:
1. JWT-based signup and login
2. Passwords hashed using bcrypt
3. Auth-protected routes for AI text and image generation
4. Persistent user sessions

AI Text Generation

1. High-quality responses powered by Google Gemini
2. Integrated via the OpenAI React client
3. Smooth, chat-style UI with streaming responses
4. Credits auto-deducted per generation

AI Image Generation

1. Generate images from user prompts
2. Powered by ImageKit AI
3. Globally optimized CDN delivery
4. Multiple output resolutions supported

Credit System + Online Payments

1. New users receive free credits
2. Integrated online payment gateway (Stripe)
3. Credits added instantly after successful payment
4. Secure backend verification
5. Full transaction history stored

Database (MongoDB / Atlas)

1. Users
2. Chats
3. Transactions

Testing(Postman)

Tests:
1. User registration/login
2. JWT-protected routes
3. Credit deduction
4. Text and image generation
5. Payment verification
