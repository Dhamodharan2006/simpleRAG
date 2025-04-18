🚀 𝐒𝐢𝐦𝐩𝐥𝐞 𝐑𝐞𝐭𝐫𝐢𝐞𝐯𝐚𝐥-𝐀𝐮𝐠𝐦𝐞𝐧𝐭𝐞𝐝 𝐆𝐞𝐧𝐞𝐫𝐚𝐭𝐢𝐨𝐧 (𝐑𝐀𝐆) 𝐂𝐡𝐚𝐭𝐛𝐨𝐭 🤖

🌟 𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰
This project focuses on building a Retrieval-Augmented Generation (RAG) pipeline that combines a Language Model (LLM) with a Retriever to generate more accurate, current, and domain-specific answers. Instead of relying solely on the model’s built-in knowledge, we use external data sources (like websites and documents) to retrieve relevant information, which enhances the model's responses and reduces hallucinations. 🔍

RAG is particularly useful for creating Domain-Specific LLMs, ensuring responses are accurate and contextually appropriate.

🛠️ 𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐢𝐞𝐬 𝐔𝐬𝐞𝐝:

𝟏.𝐖𝐞𝐛𝐁𝐚𝐬𝐞𝐋𝐨𝐚𝐝𝐞𝐫 🌐: Scrapes content from websites.

𝟐.𝐁𝐞𝐚𝐮𝐭𝐢𝐟𝐮𝐥𝐒𝐨𝐮𝐩 : Extracts useful data from HTML content.

𝟑.𝐋𝐚𝐧𝐠𝐂𝐡𝐚𝐢𝐧 🔗: Manages the flow of text processing, embedding generation, and document retrieval.

𝟒.𝐆𝐞𝐦𝐢𝐧𝐢 𝐄𝐦𝐛𝐞𝐝𝐝𝐢𝐧𝐠𝐬 🧠: Creates vector embeddings for the text data.

𝟓.𝐂𝐡𝐫𝐨𝐦𝐚𝐃𝐁 📦: Stores and retrieves the embeddings for fast and efficient searches.

𝟔.𝐆𝐫𝐚𝐝𝐢𝐨 🎮: Builds an interactive user interface for the chatbot.

🔧 𝐖𝐡𝐚𝐭 𝐈 𝐖𝐨𝐫𝐤𝐞𝐝 𝐎𝐧:

I developed the pipeline step-by-step to understand how RAG works. Here’s what I did:

𝐒𝐜𝐫𝐚𝐩𝐢𝐧𝐠 𝐃𝐚𝐭𝐚 🌐:

Scraped MCP-related content from 3 websites using WebBaseLoader (powered by BeautifulSoup).

𝐓𝐞𝐱𝐭 𝐏𝐫𝐨𝐜𝐞𝐬𝐬𝐢𝐧𝐠 ✂️:

Split the scraped text into manageable chunks using LangChain to ensure easy handling.

𝐄𝐦𝐛𝐞𝐝𝐝𝐢𝐧𝐠 𝐆𝐞𝐧𝐞𝐫𝐚𝐭𝐢𝐨𝐧 💡:

Created vector embeddings for the chunks using Gemini Embeddings.

𝐒𝐭𝐨𝐫𝐢𝐧𝐠 𝐄𝐦𝐛𝐞𝐝𝐝𝐢𝐧𝐠𝐬 🗄️:

Stored the embeddings in ChromaDB for efficient similarity-based retrieval.

𝐑𝐞𝐭𝐫𝐢𝐞𝐯𝐢𝐧𝐠 𝐈𝐧𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧 🔄:

Set up the retriever with LangChain to load, process, and manage the embeddings.

Integrated it with Gemini 1.5 Pro to generate contextual responses based on the retrieved information.

𝐈𝐧𝐭𝐞𝐫𝐚𝐜𝐭𝐢𝐯𝐞 𝐂𝐡𝐚𝐭𝐛𝐨𝐭 💬:

Built a simple Gradio UI to make the chatbot interactive and engaging for users.
