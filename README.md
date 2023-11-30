<h1>ChatGPT Replica using Supabase db and Openai API.</h1>
This is the ChatGPT replica that allows users to engage with the AI model in real-time. The application closely resemble ChatGPT in terms of functionality and user experience, with a focus on user accounts and a record of previous interactions.


<h2>This Project is made by: Paramvir Rotwal</h2>
This is the assessment project for MINDCASE CO. 

## Getting Started

1. **Chat Interface**:
    - Used **Shadcn UI** library to craft a chat interface similar to ChatGPT. The interface includes:
        - A dynamic chat section where user inquiries and AI replies appear immediately.
        - A text input section for posing questions to the AI.
        - A feature to fetch and display past interactions once the user logs in.
        - Options to initiate a new chat and erase prior chats, mirroring ChatGPT's functionality.
2. **Setup & Authentication**:
    - Start a project with **NextJS** (used `create-next-app` and not `create-react-app`).
    - Incorporate Supabase for user authentication:
        - Permit new users to sign up via email and password and/or Google.
        - Allow registered users to sign in and securely maintain their sessions.
        - After logging in, users should be able to access their profile and review their past engagements.
3. **Database Structure**:
    - Used Supabase to structure database tables.
    - Your database should, at the very least, contain tables for Users, Chats, and Messages. The Messages table should record each user's queries and the corresponding AI replies.
4. **API Connection:**
    - To populate the database, you need to connect to OpenAI’s API key.
5. **Miscellaneous**:
    - Conclude by hosting your website on a platform of your choice (e.g., Vercel, Netlify).

