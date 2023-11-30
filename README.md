<h1>ChatGPT Replica using Supabase db and Openai API.</h1>
This is the ChatGPT replica that allows users to engage with the AI model in real-time. The application closely resemble ChatGPT in terms of functionality and user experience, with a focus on user accounts and a record of previous interactions.

***This is the assessment project for MINDCASE CO.***


<h2>This Project is made by: Paramvir Rotwal</h2>



<img width="981" alt="Screenshot 2023-11-30 at 7 36 50 PM" src="https://github.com/pveerrotwal/ChatGPT-Replica-Project/assets/108364147/260cfa67-1b4b-425a-b86a-4a7bec2e0df4">

## Getting Started

1. **Chat Interface**:
    - Used **Shadcn UI** library to craft a chat interface similar to ChatGPT. The interface includes:
        - A dynamic chat section where user inquiries and AI replies appear immediately.
        - A text input section for posing questions to the AI.
        - A feature to fetch and display past interactions once the user logs in.
        - Options to initiate a new chat and erase prior chats, mirroring ChatGPT's functionality.
     
<img width="1135" alt="Screenshot 2023-11-30 at 7 37 22 PM" src="https://github.com/pveerrotwal/ChatGPT-Replica-Project/assets/108364147/5491ca6b-b425-4a20-9b12-5cb7cc562780">



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

*Hosted the website on a platform vercel:*

"https://chat-gpt-replica-project-git-main-pveerrotwals-projects.vercel.app"

   

