<p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1F6FEB&height=170&section=header&text=Mehdi%20Boudar&fontColor=FFFFFF&fontSize=44&fontAlignY=34&desc=Java%2021%20%C2%B7%20Spring%20Boot%20%C2%B7%20LLM%20Systems&descAlignY=54&descSize=18" width="100%" alt="Mehdi Boudar, AI and Platform Engineer" /> </p> <p align="center"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=23&duration=3400&pause=900&color=2F81F7&center=true&vCenter=true&width=760&lines=Production+LLM+systems+in+Java+21+%26+Spring+Boot;Multi-model+orchestration%2C+hybrid+RAG%2C+MCP+servers;10%2B+enterprise+brands+across+8+channels" alt="Production LLM systems in Java 21 and Spring Boot" /> </p> <p align="center"> <a href="https://mehdiboudar.com"><img src="https://img.shields.io/badge/Portfolio-mehdiboudar.com-1F6FEB?style=for-the-badge&logoColor=white" alt="Portfolio" /></a> <a href="https://www.linkedin.com/in/mehdi-boudar/"><img src="https://img.shields.io/badge/LinkedIn-mehdi--boudar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a> <a href="mailto:Meehdi99@gmail.com"><img src="https://img.shields.io/badge/Email-Meehdi99@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a> <a href="https://mehdiboudar.com"><img src="https://img.shields.io/badge/Oracle_Certified-Java_SE_17-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle Certified Professional, Java SE 17" /></a> </p>
Hi, I'm Mehdi
I build AI that talks to customers, and I build it in Java.

That combination is rarer than it sounds. Almost everyone doing LLM work reaches for Python, so companies already running Java and Spring tend to get told their stack is the wrong one. It isn't. I've spent the last year proving that inside a messaging platform used by more than ten enterprise brands across eight channels, in automotive, retail, real estate and education.

When someone messages one of those brands on WhatsApp at 2am, an agent I wrote answers them, in their own language, and books the appointment.

What I'm building
safq.ai
An AI that handles customer conversations on WhatsApp, Instagram and Messenger, plus the campaigns, the CRM sync and the ad tracking that go with them. I'm the only engineer on it: architecture, data model, billing, deployment, all of it. Six companies run their customer conversations through it today.

useinvestment.com
Growth diagnostics for Shopify stores. Point it at a shop and it reads the public catalogue, compares it against named competitors, and tells you what's actually costing you sales, with the evidence attached rather than a generic checklist.

mehdiboudar.com
My portfolio, and the long version of the engineering write-ups below.

Problems I enjoyed solving
Letting a business keep its WhatsApp app. To automate WhatsApp you need Meta's Cloud API, and connecting a number to it used to delete the WhatsApp Business app on that number. For a dealership whose sales team lives in that app all day, that's an immediate no. I implemented Meta's official coexistence, so the same number now works in both places at once and the message history stays in sync both ways. Nobody has to change how they work, which is usually what decides whether a deployment survives.

Keeping conversations alive when a model dies. AI models fail in strange ways: rate limits, regional outages, answers that get quietly worse. So the agent has five layers to fall through. Gemini, then Claude, then Gemini Flash, then GPT-4o-mini, then a scripted path that always replies. Each layer is a full replacement rather than a retry, and the agent keeps all of its tools the whole way down. A customer never sees it happen.

Understanding Darija. Moroccan customers write Darija and French mixed inside one sentence, often asking about a part number that appears nowhere in the documentation. Plain semantic search falls apart on that, so retrieval runs three ways at once: meaning, exact keyword, and a trick called HyDE that guesses what the answer would look like before going to find it.

Giving an AI real access to a CRM. Two Model Context Protocol servers in production. One puts several Zoho accounts behind a single interface so an assistant can work across all of them in one session. The other exposes eighteen tools over the conversation layer. Everything runs under per-user tokens, so nobody sees more than they should.

Tech I actually use
<p align="center"> <img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 21" /> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" /> <img src="https://img.shields.io/badge/PostgreSQL_/_pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL and pgvector" /> <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" /> <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Apache Kafka" /> </p> <p align="center"> <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini" /> <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude" /> <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" /> <img src="https://img.shields.io/badge/Model_Context_Protocol-0D1117?style=for-the-badge&logoColor=white" alt="Model Context Protocol" /> <img src="https://img.shields.io/badge/Hybrid_RAG-1F6FEB?style=for-the-badge&logoColor=white" alt="Hybrid RAG" /> </p> <p align="center"> <img src="https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp Cloud API" /> <img src="https://img.shields.io/badge/Zoho_CRM-E42527?style=for-the-badge&logo=zoho&logoColor=white" alt="Zoho CRM" /> <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce" /> <img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" alt="Stripe" /> <img src="https://img.shields.io/badge/OAuth2_/_HMAC-0D1117?style=for-the-badge&logoColor=white" alt="OAuth2 and HMAC" /> </p> <p align="center"> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/React-087EA4?style=for-the-badge&logo=react&logoColor=white" alt="React" /> <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" /> <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" /> <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" alt="Railway" /> </p>
I've also shipped things in Python, C#, PHP, MongoDB and Kubernetes. They're listed down here rather than up there because I'd rather be interviewed on the ones above.

Code you can read
Chatwoot (Ruby on Rails) The messaging platform whose campaign and broadcast engine I rebuilt to survive Meta's rules: rate limiting, retries, scheduling and delivery tracking. It imports 500,000 contacts in under ten minutes and sends 100,000 template messages in under thirty.

odc-fablab (Java, Spring Boot) The FabLab platform I built at Orange Morocco. Nine microservices talking over Kafka, live reservations that can't double-book thanks to optimistic locking, and ten-plus IoT machines wired in over REST.

Freelancer-Portal-Saas (Spring Boot, Angular) A full platform for freelancers and clients: projects, messaging, payments.

Most of what I do day to day sits in private repositories. The write-ups on mehdiboudar.com are the closest thing to a code tour.

Background
State Engineering Degree in Computer Science, EMSI Rabat, 2022 to 2025
Associate Degree in Software Development, ISTA NTIC Safi, 2019 to 2021
Oracle Certified Professional, Java SE 17 (1Z0-829)
Oracle Database SQL Certified Associate (1Z0-082)
Based in Rabat, Morocco (GMT+1). I speak English, French and Arabic. Open to remote work with European or US overlap, and happy to relocate.

<p align="center"> <img src="https://streak-stats.demolab.com?user=kusoyaji&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="Contribution streak" /> </p>
