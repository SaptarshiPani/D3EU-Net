Title - "D3EU-Net: A Diffusion and DeepSeek-aided Dual Encoder-based U-Net Model for Microscopic Medical Image Segmentation". <br />
Authors - Saptarshi Pani, Asya Lyanova, Dmitrii Kaplun, Ram Sarkar. <br />

1. Workflow of overall D3EU-Net model.

<img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/bd1daea8-2292-4ecd-9459-4f2afb9d559f" />

2. Ablation Study Results on TNBC and MonuSeg datasets.

<img width="381" height="333" alt="Image" src="https://github.com/user-attachments/assets/7584548e-b11c-4c61-9939-dedd6a628b89" />

4. SOTA Comparison Results on TNBC and MonuSeg datasets.

<img width="417" height="232" alt="Image" src="https://github.com/user-attachments/assets/229ad300-4d50-444d-a630-3935f4387a69" />
<img width="366" height="173" alt="Image" src="https://github.com/user-attachments/assets/505fd9b1-4359-4d36-9bab-af1d79924a1e" />

5. Computational Time Analysis on the 3 datasets.

<img width="561" height="111" alt="Image" src="https://github.com/user-attachments/assets/965258aa-7d7a-4efc-8871-86e33e8937d3" />

6a. Diffusion Noising-Denoising process on TNBC dataset.

<img width="1575" height="409" alt="Image" src="https://github.com/user-attachments/assets/c8cdca9d-4c25-4d00-8887-09170d13c589" />

6b. Diffusion Noising-Denoising process on MonuSeg dataset.

<img width="1575" height="409" alt="Image" src="https://github.com/user-attachments/assets/179437df-e831-4af7-b491-f7fb22c905b1" />

6c. Diffusion Noising-Denoising process on GlaS dataset.

<img width="1575" height="409" alt="Image" src="https://github.com/user-attachments/assets/c6c259bf-6eff-4554-9ba4-db50cdc4de56" />

7a. Training curves displaying the history of loss while training the model's performance on TNBC dataset.

<img width="855" height="470" alt="Image" src="https://github.com/user-attachments/assets/7ced0e3e-0143-491a-8271-1e84110cd9ec" />

7b. Training curves displaying the history of loss while training the model's performance on MonuSeg dataset.

<img width="854" height="470" alt="Image" src="https://github.com/user-attachments/assets/e2765998-b55f-42fe-ae3f-8a9aa8a4ff05" />

7c. Training curves displaying the history of loss while training the model's performance on GlaS dataset.

<img width="846" height="470" alt="Image" src="https://github.com/user-attachments/assets/81ca6aad-22d3-4890-8da7-8a646364f8d6" />

8a. Heatmap images displaying some noisy images from TNBC dataset.

<img width="1571" height="795" alt="Image" src="https://github.com/user-attachments/assets/d2c3cb5f-b416-4a03-9134-caf603223752" />

8b. Heatmap images displaying some noisy images from MonuSeg dataset.

<img width="1571" height="795" alt="Image" src="https://github.com/user-attachments/assets/8277f8c2-2f1a-45ca-ac09-a08dd350dd2b" />

8c. Heatmap images displaying some noisy images from GlaS dataset.

<img width="1571" height="795" alt="Image" src="https://github.com/user-attachments/assets/085a85cb-8e5f-4e8f-af1f-efd2ce757e42" />

9a. Sample DeepSeek-R1 generated text for TNBC dataset :- <br />

"Based on the exceptionally detailed morphological account, which is highly characteristic of a high-grade invasive breast carcinoma, several critical diagnostic insights can be elaborated. The described high cellularity and marked nuclear pleomorphism encompassing both ovoid and spindled forms are hallmark features of a poorly differentiated neoplasm, often correlating with aggressive biological behavior and high histological grade (Grade 3). The alignment of these hyperchromatic, mitotically active nuclei along eosinophilic collagenous stroma is highly suggestive of an invasive carcinoma with a scirrhous or desmoplastic pattern, where the malignant cells induce a profound host stromal response. The prominent nuclear overlapping and concave junctions indicate a loss of cellular cohesion and a crowded, syncytial-like growth pattern, frequently seen in basal-like or triple-negative breast cancers. Furthermore, the dense chromatin and occasional prominent nucleoli are cytological features associated with high proliferative activity and potential mutations in the p53 tumor suppressor gene. The anisotropic stromal patterns and low-contrast zones are not merely background artifact but represent critical contextual clues; the invading tumor cells are intricately associated with and disrupting the native breast architecture, and the pale, ill-defined cytoplasm can often lead to under-estimation of nuclear size and confound automated image analysis, necessitating careful manual review. In sum, this constellation of features strongly argues against a benign or low-grade lesion and points toward an invasive carcinoma of no special type (NST) with likely basal-like characteristics, warranting confirmation with immunohistochemical staining for cytokeratins (CK5/6, CK14), EGFR, and triple-negative markers (ER, PR, HER2)."

9b. Sample DeepSeek-R1 generated text for MonuSeg dataset :- <br />

"This detailed morphological account is quintessential for a high-grade invasive breast carcinoma, most likely of no special type (NST), and carries significant diagnostic and prognostic implications. The marked nuclear pleomorphism, encompassing both pyknotic and substantially enlarged forms with irregular outlines, is a cardinal feature of high histological grade (Grade 3, Nottingham grading system), directly correlating with increased genomic instability and aggressive tumor behavior. The observed chromatin pattern—hyperchromatic with clumping and prominent nucleoli—is highly suggestive of a high proliferative index (elevated Ki-67) and is frequently associated with mutations in the TP53 tumor suppressor gene, a hallmark of basal-like breast cancers. The architectural pattern of crowded sheets and nests with loose cohesion, narrow cytoplasmic necks, and nuclear fusion indicates a loss of normal cell-to-cell adhesion, a phenomenon often driven by the downregulation of E-cadherin, which is characteristic of lobular carcinomas but can also be seen in high-grade NST cancers. The presence of mitotic figures and apoptotic bodies further confirms the tumor's rapid growth fraction. Critically, the anisotropic stroma with thin fibrous septa represents a desmoplastic reaction, a host-response mechanism where the tumor induces collagen deposition that facilitates invasion; distinguishing true tumor nuclei from the mentioned confounders—apoptotic fragments, lymphocytes, and erythrocytes—is not merely an academic exercise but is essential for accurate mitotic count assessment and unequivocal diagnosis, as misclassification can alter therapeutic strategies, particularly in distinguishing a high-grade carcinoma from a lymphoproliferative disorder or a spindle cell lesion. This constellation of features underscores the challenges in both manual and AI-powered segmentation, where precise nuclear delineation is paramount for predicting response to chemotherapy and overall patient prognosis."

9c. Sample DeepSeek-R1 generated text for GlaS dataset :- <br />

"Based on the described macroscopic morphology, this specimen exhibits a classic yet aggressive presentation of colorectal adenocarcinoma with several critical prognostic implications. The multifocal, multilobulated architecture with a dominant mass and true satellite nodules is highly characteristic of intramural metastatic spread, often via lymphovascular invasion (LVI), which significantly upstages the disease and increases the risk of local recurrence. The heterogeneous margin is a key diagnostic feature: the polypoid, sharply demarcated areas suggest an exophytic growth component, potentially arising from a pre-existing adenoma, while the spiculated and jagged invasion fronts with filamentous extensions are histopathological hallmarks of a desmoplastic reaction—a host stromal response induced by the tumor's infiltrative behavior that is correlated with poorer outcomes. The internal lacunae and cavitations are highly suggestive of necrotic debris within glandular lumina, a common finding in high-grade tumors with rapid, dysregulated growth leading to central ischemia. The presence of small, isolated tumor islands detached from the main mass is particularly ominous, as these likely represent either extensive lymphatic permeation, perineural invasion, or, most significantly, tumor budding—a well-established independent predictor of lymph node metastasis and reduced survival in colorectal carcinoma. The observation of border-touching partial sections underscores the necessity for complete serial sectioning to accurately assess the true depth of invasion (yielding the critical pT stage) and margin status, as an involved surgical margin (particularly the circumferential radial margin in rectal cancers) is a paramount finding dictating the need for adjuvant chemoradiation. This constellation of features paints a picture of an advanced, biologically aggressive malignancy requiring comprehensive staging and aggressive multimodal therapy."
