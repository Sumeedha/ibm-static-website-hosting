# 🌐 Hosting a Static Website on IBM Cloud  

This repository explains how I successfully hosted a **static website** on **IBM Cloud** using **Watsonx.ai Studio** and **Cloud Object Storage**.  

---

## 📌 Static vs Dynamic Websites  

- **Static Website** → Fixed content (HTML, CSS, JS) delivered as-is. Beginner-friendly and free to host.  
- **Dynamic Website** → Content generated in real time (requires backend, databases, licenses).  

For this project, I hosted a **static website** for a free and easy setup.  

---

## 🔑 Step-by-Step Process  

### 1️⃣ Login to IBM Cloud  
- Log in using Gmail or IBM credentials.  

### 2️⃣ Clean the Slate  
- Delete any old resources to avoid conflicts.  

### 3️⃣ Access Watsonx.ai Studio  
- Go to **Watsonx.ai Studio** → choose region.  
- Select **Lite Plan** → click **Create**.  

### 4️⃣ Provision Runtime  
- Click **Provision Watsonx.ai Runtime**.  
- Choose **Lite Plan** → **Create**.  

### 5️⃣ Create a Project  
- Give project **name + description**.  
- Add **Cloud Object Storage** (Lite Plan).  
- Click **Create**.  

### 6️⃣ Associate Runtime  
- Go to *Manage → Services & Integrations*.  
- Associate Watsonx.ai Runtime.  

### 7️⃣ Open IBM Cloud Dashboard  
- From project → open **Resources List** → **Storage → Cloud Object Storage**.  

### 8️⃣ Create a Bucket  
- Click **Create Bucket**.  
- Choose **Single Data Center** (for static hosting).  
- Select **nearest location** → **Create**.  

### 9️⃣ Upload Website Files  
- Inside bucket → **Upload** your `index.html` (and any CSS/JS/images).  

### 🔟 Set Public Permissions  
- Go to **Permissions → Create Access**.  
- Select **Public Access** → Role = **Object Reader** → **Create & Enable**.  

### 1️⃣1️⃣ Access Your Website  
- Click your `index.html` file → copy the **Object URL**.  
- Paste into browser → 🎉 Your static site is live!  

---

## 🎯 Key Learnings  
✔️ IBM Cloud setup for hosting static sites  
✔️ Watsonx.ai Studio + Runtime basics  
✔️ Cloud Object Storage usage  
✔️ Public permissions & access control  
✔️ Hosting a **free static website**  

---


---

✨ With IBM Cloud, you can quickly deploy static websites for free — perfect for portfolios, landing pages, or simple apps.  

