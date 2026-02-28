# HTT-DPNet

<b>Heterogeneous Text-rich Temporal Graph Network for Diagnosis</b>
<br><em>Qing Li,Zehao Li,Fei Duan</em></br>


**Abstract**: 
Electronic Health Records (EHR) have greatly facilitated predictive models based on deep learning. However, due to the missing features and diverse heterogeneity of EHR data, most studies focus only on basic medical concepts such as diagnosis and medications, resulting in the insufficient utilization of EHR resources. Moreover, integrating accurate, professional medical knowledge highly relevant to predictive tasks remains a challenge. We propose HTT-DPNet, a model that improves diagnostic prediction tasks by constructing a heterogeneous rich-text temporal graph for each patient. First, we connect various heterogeneous medical concept nodes through temporal seeds and link these temporal seeds using temporal edges. Second, we prompt large language models (LLM) to generate richly detailed, task-relevant knowledge texts based on the medical concepts present in EHR. Finally, we design a Temporal Semantic Graph Neural Network to learn the structural, semantic, and temporal information in the rich-text temporal graph. We conducted extensive experiments on two commonly used real-world datasets. The experimental results show that HTT-DPNet surpasses state-of-the-art models, highlighting the potential of using heterogeneous rich-text temporal graphs in diagnostic prediction tasks. 
<img src="doc/main.jpg" alt="" align=center />
The code will be made public after receipt.
