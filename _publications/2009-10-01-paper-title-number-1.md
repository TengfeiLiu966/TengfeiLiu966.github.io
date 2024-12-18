**HC-LLM: Historical-Constrained Large Language Models for Radiology Report Generation**

### 摘要
Radiology report generation (RRG) models typically focus on individual exams, often overlooking the integration of historical visual or textual data, which is crucial for patient follow-ups. Traditional methods usually struggle with long sequence dependencies when incorporating historical information, but large language models (LLMs) excel at in-context learning, making them well-suited for analyzing longitudinal medical data. In light of this, we propose a novel Historical-Constrained Large Language Models (HC-LLM) framework for RRG, empowering LLMs with longitudinal report generation capabilities by constraining the consistency and differences between longitudinal images and their corresponding reports. Specifically, our approach extracts both time-shared and time-specific features from longitudinal chest X-rays and diagnostic reports to capture disease progression. Then, we ensure consistent representation by applying intra-modality similarity constraints and aligning various features across modalities with multimodal contrastive and structural constraints. These combined constraints effectively guide the LLMs in generating diagnostic reports that accurately reflect the progression of the disease, achieving state-of-the-art results on the Longitudinal-MIMIC dataset. Notably, our approach performs well even without historical data during testing and can be easily adapted to other multimodal large models, enhancing its versatility.
---

### 框架图
![HC-LLM Framework](images/HC-LLM.jpg)  
*Figure 1: An overview of the HC-LLM framework, illustrating the integration of historical radiology images and reports with temporal-aware prompts.*

---

### 论文链接
[📄 **Download Paper**](https://arxiv.org/pdf/2412.11070)  
[🔗 **View on arXiv**](https://arxiv.org/abs/2412.11070)

---

### 推荐引用
```bibtex
@misc{liu2024hcllmhistoricalconstrainedlargelanguage,
      title={HC-LLM: Historical-Constrained Large Language Models for Radiology Report Generation}, 
      author={Tengfei Liu and Jiapu Wang and Yongli Hu and Mingjie Li and Junfei Yi and Xiaojun Chang and Junbin Gao and Baocai Yin},
      year={2024},
      eprint={2412.11070},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2412.11070}, 
}
