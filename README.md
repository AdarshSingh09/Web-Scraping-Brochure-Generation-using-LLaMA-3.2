# 📌 Web Scraping & Brochure Generation using LLaMA 3.2

This project automates **web content extraction** and **brochure generation** using **LLaMA 3.2**. It scrapes a website, filters useful links, extracts page content, and generates a **company brochure** suitable for customers, investors, and stakeholders.

---

## 🚀 Features
✅ **Automated Web Scraping** – Extracts and filters relevant website links  
✅ **Content Extraction** – Retrieves textual content while removing unnecessary elements  
✅ **AI-Powered Filtering** – Uses **LLaMA 3.2** to select the most useful links  
✅ **Brochure Generation** – Generates structured content using LLaMA 3.2  
✅ **Local Execution** – Runs efficiently on a local machine via **Ollama**  

---

## 🛠️ Methodology

### **1️⃣ Web Scraping**
- Extracts **all links** from a website using `BeautifulSoup`
- Converts **relative URLs** to **absolute URLs**
- Filters out **irrelevant links** (`#`, `mailto:`, PDFs, images, etc.)
- Retains only **domain-specific** links

### **2️⃣ AI-Based Link Filtering**
- Uses **LLaMA 3.2** to select **the most relevant links** for a company brochure

### **3️⃣ Content Extraction**
- Fetches **clean textual content** from selected links  
- Limits extracted text **to fit within LLaMA’s context window**  

### **4️⃣ Brochure Generation with LLaMA 3.2**
- Combines extracted text into a structured prompt  
- Generates a **company brochure** with AI  

---

## 🧠 Model Used: LLaMA 3.2 (3.2B Parameters)
- **Architecture:** LLaMA (Meta AI)  
- **Parameters:** **3.2B**  
- **Context Length:** **131072 tokens**  
- **Quantization:** **Q4_K_M**  
- **Inference Engine:** **Ollama** (for running LLaMA locally)  

---

