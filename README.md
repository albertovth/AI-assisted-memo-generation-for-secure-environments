# AI-Assisted Memo Generation for Secure Environments

Final project for the Building AI course

## Summary

This project explores the use of pre-trained transformer models for automated memo and report generation, at the same time data privacy for sensitive organizational information is maintained. 

## Background

Organizations are increasingly turning to AI to automate routine tasks. 
Several tools have become readily available to train generative language models, with organizational or private data. One example is https://gpt-trainer.com/
This possibility opens for large potential efficiency gains for organizations, particularly those that depend on document generation,
like memos, reports, correspondence and analysis.
However, the use of cloud-based AI services raises concerns about data privacy, especially for sensitive information.
The following points summarize the project:

* Organizations who store sensitive information on cloud servers, increase the risk of exposing this information
* At the same time, the potential benefits of AI create a desire for AI capabilities
* This creates a need for secure, AI-powered document generation, either on-premises or externally

This project is driven by the need to balance the efficiency gains from AI with the imperative of data security. 

## How is it used?

The solution involves two main alternative approaches:
i) Partnering with AI-providers, to create secure processing infrastructures.
ii) Investing in on-premises hardware, to host and train AI-models in-house.

This solution is necessary in environments where data sensitivity is paramount, such as government agencies, banks or healthcare providers. 
Users would be organizational staff who require secure and efficient document creation.

Images and diagrams of the system architecture can help visualize the setup and workflow.

## Data sources and AI-methods

Data will come from the organization's own archives. This data can include internal memos and reports. 
The project will ensure that all sensitive information remains within the organization's secure data perimeter. 
The data will be used to adapt pre-trained transformer models to generate language in text form, in a way that responds to the document needs of the organization.

The project could make use of AI libraries like TensorFlow or PyTorch. Other possibilities are Hugging Face's Transformers, where several models are available. The project can also use Scikit-learn, for simpler tasks, and ONNX, to facilitate work accross models and frameworks. The choice of library(ies) will depend on the organization's specific needs, and the approach selected.

An alternative to in-house model training is partnering with AI-providers like OpenAI, Microsoft, or Google, to use their advanced models securely. These providers may offer appropriate dedicated enterprise solutions, in line with data privacy. Such partnerships might make the project simpler, but would also depend on appropriate service agreements, and a high level of trust with the provider, which might not be applicable for all types of organizatios.

## Challenges

- There is a high cost and expertise needed to set up in-house AI infrastructures.
- Agreements with providers can be intricate and involve high risk for involved parties.
- International data privacy laws are complex, and could hinder or complicate the project.
- Ethical considerations include potential misuse of AI-generated documents and ensuring that AI-generated texts are clearly identified as such.

These risks should be measured against the risk of allowing organizations either: 
i) use current AI models without securing their data, or 
ii) prohibit the use of AI models in their organizations, missing out on the potential benefits.

## What next?

The implementation of this project implies collaboration with cybersecurity experts and legal advisors, depending on the organization.
Further development could also involve creating more sophisticated models tailored to different types of documents and organizational needs.

## Acknowledgments

This project draws inspiration from a variety of sources. Notable references include:

- Davenport, T. H., & Bean, R. (2022, June 15). Becoming an ‘AI Powerhouse’ Means Going All In. MIT Sloan Management Review. Available at: [MIT Sloan Management Review - Becoming an ‘AI Powerhouse’ Means Going All In](https://sloanreview.mit.edu/article/becoming-an-ai-powerhouse-means-going-all-in/)

- Lakhani, K. (2023, August 04). AI Won’t Replace Humans — But Humans With AI Will Replace Humans Without AI. Harvard Business Review. Available at: [Harvard Business Review - AI Won’t Replace Humans — But Humans With AI Will Replace Humans Without AI](https://hbr.org/2023/08/ai-wont-replace-humans-but-humans-with-ai-will-replace-humans-without-ai)

- Martinho-Truswell, E. (2018, January 26). How AI Could Help the Public Sector. Harvard Business Review. Updated January 29, 2018. Available at: [Harvard Business Review - How AI Could Help the Public Sector](https://hbr.org/2018/01/how-ai-could-help-the-public-sector)

- Rebitzer, J. B., & Rebitzer, R. S. (2023, September 14). AI Adoption in U.S. Health Care Won’t Be Easy. Harvard Business Review. Available at: [Harvard Business Review - AI Adoption in U.S. Health Care Won’t Be Easy](https://hbr.org/2023/09/ai-adoption-in-us-health-care-wont-be-easy)

- Sponsor content by Cloudera, AMD & Dell. (2023, August 28). How a Hybrid Platform Can Help Enable Trusted Generative AI. Harvard Business Review. Available at: [Harvard Business Review - How a Hybrid Platform Can Help Enable Trusted Generative AI](https://hbr.org/2023/08/how-a-hybrid-platform-can-help-enable-trusted-generative-ai)

Please note that these references are used for inspirational purposes, and to frame the context of the project within current discussions on AI and data privacy. The actual content and ideas within the project README are original, created for the Building AI course.



