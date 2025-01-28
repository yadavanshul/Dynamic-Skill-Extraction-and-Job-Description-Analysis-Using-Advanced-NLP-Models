# **Dynamic Skill Extraction and Job Description Analysis Using Advanced NLP Models**

## 📋 **Overview**
This project focuses on extracting key technical and non-technical skills, tools, and qualifications from job descriptions using state-of-the-art Natural Language Processing (NLP) models. The goal is to build a robust pipeline to analyze job descriptions dynamically, ensuring accurate and contextually relevant keyword extraction while comparing outputs from multiple advanced NLP models.

---

## 🚀 **Key Features**
- **Keyword Extraction**: Utilized models like **KeyBERT**, **RAKE**, and Hugging Face Transformers to extract skills and technologies from job descriptions.
- **Model Comparison**: Benchmarked outputs from **Falcon-7B**, **MPT-7B**, **GPT-J**, **BLOOM**, and other models for consistency and accuracy.
- **Dynamic Prompting**: Designed task-specific prompts for extracting structured insights such as responsibilities, skills, and qualifications.
- **O*NET Integration**: Integrated the O*NET API to fetch additional job-specific details for enriched keyword extraction.
- **Future Scalability**: Exploring **DeepSeek** and other cutting-edge LLMs to enhance the system's performance and scalability.

---

## 🛠️ **Technologies Used**
- **Programming Languages**: Python
- **Libraries and Frameworks**:
  - **NLP Models**: KeyBERT, Hugging Face Transformers
  - **Models**: Falcon-7B, GPT-J, BLOOM, MPT
  - **Text Processing**: RAKE, SpaCy
- **APIs**: O*NET Online API
- **Utilities**: JSON, Pandas, PyTorch
- **Future Plans**: DeepSeek and other advanced LLMs

---

## 🔧 **How It Works**
1. **Input**: The system takes job descriptions as input.
2. **Keyword Extraction**: Implements multiple extraction methods like KeyBERT, RAKE, and pre-trained models.
3. **Classification**: Dynamically classifies job descriptions into technical or non-technical categories.
4. **Model Benchmarking**: Runs the job description against multiple NLP models to analyze and compare results.
5. **Output**: Produces a structured JSON or plain-text output containing core responsibilities, required skills, and qualifications.

---

## 🤝 **Contributing**
Contributions are welcome! If you'd like to improve the pipeline or add support for new models, feel free to open a pull request.

---

## 📫 **Contact**
For questions or collaboration, reach out via:
- **Email**: [anshul.yadavsisotiya@gmail.com](mailto:anshul.yadavsisotiya@gmail.com)
- **LinkedIn**: [Anshul Yadav](https://www.linkedin.com/in/yadavanshul36/)

---

## 🛠️ **Future Enhancements**
- Integrate **DeepSeek** and other upcoming LLMs for improved performance.
- Build a web-based interface for uploading job descriptions and visualizing results.
- Automate real-time benchmarking for faster and more scalable insights.

---

## 🌟 **Acknowledgments**
Special thanks to the open-source NLP community and Hugging Face for providing amazing tools and resources.
