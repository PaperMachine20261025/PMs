Analyzing K-12 AI education: A large language model study of classroom instruction on learning theories, pedagogy, tools, and AI literacy

Di Wu, Meng Chen, Xu Chen ∗, Xing Liu

The Faculty of Artiﬁcial Intelligence in Education, Central China Normal University, Wuhan, 430079, China

A R T I C L E I N F O A B S T R A C T

Keywords: AI education Large language models Pedagogical approaches AI literacy

1. Introduction

Leveraging big data, large models, and potent computing power, artiﬁcial intelligence (AI) technology has been rapidly advancing. This progress has been evidenced by the development of large language models (LLMs) like ChatGPT, the evolution of multi-modal models such as GPT-4, and the progression of the long video generation model, Sora. AI technology has shifted from merely understanding language to comprehending and simulating the world, a transition that has drastically reshaped various industries. The profound impact of AI technology, particularly generative AI, on future labor demands is widely recognized. As a result, AI literacy has emerged as a critical technical skill in the 21st century. Several global organizations and nations are increasingly advocating for the inclusion of AI classroom instruction in K-12 education. For example, UNESCO (2021) has undertaken a comprehensive analysis of AI course content and AI literacy in primary and secondary schools worldwide. AI4K12 (2019), ISTE (2022), and Digcomp (2022) have presented

* Corresponding author. E-mail address: chenxu@ccnu.edu.cn (X. Chen).

https://doi.org/10.1016/j.caeai.2024.100295 Received 7 May 2024; Received in revised form 6 September 2024; Accepted 9 September 2024

Available online 17 September 2024 2666-920X/© 2024 The Author(s). Published by Elsevier Ltd. This is an open access article under the CC BY-NC-ND license (http://creativecommons.org/licenses/bync-nd/4.0/).

Computers and Education: Artiﬁcial Intelligence

journal homepage: www.sciencedirect.com/journal/computers-and-education-artiﬁcial-intelligence

There is growing recognition among researchers and stakeholders about the signiﬁcant impact of artiﬁcial intelligence (AI) technology on classroom instruction. As a crucial element in developing AI literacy, AI education in K-12 schools is increasingly gaining attention. However, most existing research on K-12 AI education relies on experiential methodologies and suﬀers from a lack of quantitative analysis based on extensive classroom data, hindering a comprehensive depiction of AI education’s current state at these educational levels. To address this gap, this article employs the advanced semantic understanding capabilities of large language models (LLMs) to create an intelligent analysis framework that identiﬁes learning theories, pedagogical approaches, learning tools, and levels of AI literacy in AI classroom instruction. Compared with the results of manual analysis, analysis based on LLMs can achieve more than 90% consistency. Our ﬁndings, based on the analysis of 98 classroom instruction videos in central Chinese cities, reveal that current AI classroom instruction insuﬃciently foster AI literacy, with only 35.71% addressing higher-level skills such as evaluating and creating AI. AI ethics are even less commonly addressed, featured in just 5.1% of classroom instruction. We classiﬁed AI classroom instruction into three categories: conceptual (50%), heuristic (18.37%), and experimental (31.63%). Correlation analysis suggests a signiﬁcant relationship between the adoption of pedagogical approaches and the development of advanced AI literacy. Speciﬁcally, integrating Project-based/Problem-based learning (PBL) with Collaborative learning appears eﬀective in cultivating the capacity to evaluate and create AI.

pertinent frameworks for AI education. These frameworks outline the essential AI concepts that students should grasp at diﬀerent stages, the competency standards they should meet, and the standards that educators should uphold. Their goal is to guide educators and researchers in crafting suitable strategies and projects to enhance learners’ competency in AI knowledge, skills, and attitudes.

The implementation of AI education in K-12 settings is underpinned by various learning theories (Ng et al., 2023), pedagogical approaches (Su et al., 2022; Yue et al., 2022; Ng et al., 2023), and learning tools (Yim & Su, 2024). Yue et al. (2022) identiﬁed four widely used types of learning theories (Behaviorism, Cognitivism, Constructivism and Constructionism) and nine types of pedagogical approaches (Direct instruction, Interactive learning, Project-based learning, Participatory learning, Collaborative learning, Hands-on only, Game-based learning, Inquiry-based learning, and Design-oriented learning) by coding of reviewed studies. Ng et al. (2023) summarized the three most commonly used pedagogical approaches, including Collaborative learning, Project-based/Problembased learning, and Learning with game elements. Li et al. ((2024)

In recent years, there has been a surge in research on K-12 AI education. Empirical studies have explored various aspects of AI education implementation, from curriculum design to student outcomes. For instance, Chai et al. (2021) used the Positive Technological Development Framework to assess student learning on AI issues. Kim et al. (2021b) investigated the eﬀectiveness of AI education programs in developing computational thinking skills among K-12 students. Recent systematic reviews have shed light on the current state of AI in education. Sanusi et al. (2023) conducted a review of teaching and learning machine learning in educational settings, highlighting the growing interest in integrating machine learning concepts into curricula. Their ﬁndings underscore the importance of developing appropriate pedagogical approaches for teaching machine learning across diﬀerent educational levels. Lee and Kwon (2024) revealed that various topics are covered in K-12 AI education, including fundamental AI concepts, diﬀerent types of AI, AI applications, and ethical considerations related to AI. Su et al. (2022) examined 14 learning experiences in the Asian-Paciﬁc region, mapping AI tools, activities, educational models, and research outcomes. Li et al. ((2024) analyzed learning task design in 47 empirical studies on K-12 AI education, identifying four dimensions including theoretical foundations, learning contents, pedagogical approach, and assessment and outcomes.

Despite the growing body of research on AI education, signiﬁcant gaps remain. Most existing studies rely on qualitative methodologies or small-scale quantitative analyses, limiting our understanding of AI education’s broader implementation and eﬀectiveness. There is a notable lack of data-driven analyses of actual classroom practices in AI education. Moreover, while individual studies have explored various aspects of AI education, few have attempted to integrate analyses of learning theories, pedagogical approaches, learning tools, and AI literacy outcomes within a single study. This integration is crucial for developing a comprehensive understanding of eﬀective AI education practices. The advent of LLMs presents a unique opportunity to address these research gaps. LLMs’ advanced natural language processing capabilities can be leveraged to analyze vast amounts of educational data, including classroom dialogues and instructional materials. This approach can provide insights into AI education practices at a scale and depth previously unattainable.

To address the limitations, this study employs LLMs to conduct a comprehensive, quantitative analysis of AI education in K-12 settings. By analyzing 98 AI classroom instructional videos, we seek to provide a data-driven understanding of current AI education practices and their eﬀectiveness in fostering AI literacy, aiming at contributing to the growing body of knowledge on AI education, provide practical insights for educators and policymakers, and demonstrate the potential of LLMs as a tool for educational research and assessment.

2. Literature review

2.1. LLMs in education

LLMs hold signiﬁcant potential for enhancing teaching and learning (Dao et al., 2023). They are applied in various educational areas, including automated assessment (Naismith et al., 2023; Khayi et al., 2021; Moore et al., 2022), personalized learning (Xiao et al., 2023; Liang et al., 2023), and intelligent tutoring (Chen et al., 2023; Hicke et al., 2023; Tack & Piech, 2022). For automated assessment, LLMs have been ﬁnetuned to evaluate student responses and discourse coherence (Khayi et al., 2021; Moore et al., 2022; Naismith et al., 2023). In content creation, LLMs generate interactive materials like quizzes and multimedia resources to boost engagement (Chen & Wu, 2024). For personalized learning, LLMs help develop eﬃcient student models and instructional exercises (Liang et al., 2023; Xiao et al., 2023). In intelligent tutoring,

Some studies suggest that LLMs can replicate human-like reasoning and decision-making in classroom instruction (Whitehill & LoCasale- Crouch, 2024; Wang & Demszky, 2023). Whitehill and LoCasale-Crouch (2024) found that LLMs’ analysis of classroom speech closely aligns with scores provided by human experts. Similarly, Wang and Demszky (2023) noted that while ChatGPT generates relevant instructional feedback, it often lacks originality and depth. Whitehill and LoCasale-Crouch (2024) also demonstrated that automating classroom instruction evaluation using LLMs and Bag-of-Words models can oﬀer teachers more speciﬁc, frequent, and actionable feedback. Wang and Demszky (2023) further explored the use of generative AI as a tool to coach teachers in classroom instruction. Although these studies highlight the potential of LLMs in providing instructional feedback, they oﬀer limited insights into how teachers can design and strategically reﬁne their pedagogical approaches.

2.2. AI education in K-12 settings

AI education has gained prominence in 21st-century learning due to the pervasive inﬂuence of AI technologies in various aspects of life. Recognizing the importance of AI literacy across educational levels, Governments worldwide, including the United States, China, and Germany, have implemented national AI strategic plans (Laupichler et al., 2022; Ng et al., 2021a). Several nations are actively working to advance AI education in primary and secondary schools (Casal-Otero et al., 2023). In the United States, the AI4K12 program is a notable initiative to integrate AI into schools (Heintz, 2021). In China, the Ministry of Education has incorporated AI into the mandatory secondary school curriculum (Ottenbreit-Leftwich et al., 2021; Xiao & Song, 2021). Singapore launched the “AI Singapore” project in 2018 to develop students’ AI capabilities (Su et al., 2022). South Korea planned to introduce AI education for all high school students in 2021 and expand it to younger grades by 2025 (Kim et al., 2021a).

AI literacy encompasses the competencies that enable individuals to critically evaluate AI technologies and leverage them for eﬀective communication and collaboration (Long & Magerko, 2020). The term “AI literacy” emerged from researchers’ focus on preparing students for an AI-driven future (Wang & Cheng, 2021). This concept entails the design and implementation of AI learning activities, tools, applications, and pedagogical models (Yim & Su, 2024). Ng et al. (2021b) proposed four categories of AI literacy: (1) know and understand AI, (2) use and apply AI, (3) evaluate and create AI, and (4) AI ethics. Touretzky et al. (2019) identiﬁed ﬁve key components for K-12 students to learn about AI: perception, representation and reasoning, learning, natural interaction, and societal impact. Evaluating AI literacy in K-12 education is crucial. Governments and universities worldwide are collaborating with researchers, policymakers, software developers, and educators to develop curriculum guides, tools, pedagogies, content knowledge, and assessment methods. The goal is to equip K-12 learners with AI literacy skills (Ng et al., 2021b; Payne & Journell, 2019). However, developing, implementing, and scaling AI curricula presents signiﬁcant challenges. To address these, it is essential to establish a robust, evidence-based research foundation in AI education that can guide and inform the development of AI curricula (Wang & Lester, 2023).

2.3. Characteristics of AI classroom instruction in K-12 settings

Three widely accepted learning theories—constructivism, cognitivism, and behaviorism—serve as foundational frameworks for teach-

Pedagogical approaches in AI education encompass a range of methods, including direct instruction, interactive learning, project-based and problem-based learning, participatory learning, collaborative learning, hands-on activities, game-based learning, inquiry-based learning, and design-oriented learning (Ng et al., 2023; Lee & Kwon, 2024). Game-based learning, for instance, is an accessible way to introduce AI concepts to beginners with limited computer science backgrounds, helping to sustain their motivation (Long & Magerko, 2020; Ng et al., 2021a, 2021b). Some researchers advocate for hands-on activities through case studies to enhance understanding of AI concepts (Shamir & Levin, 2022; Vartiainen et al., 2021). In project-based learning, the emphasis is on contextualized, real-world problem-solving (Vartiainen et al., 2021). While there are pedagogical guidelines for fostering AI literacy in students (ISTE, 2022; UNESCO, 2021; AI4K12, 2019), current research often relies on case studies to identify teaching methods used in classrooms, oﬀering a limited perspective that does not account for the potential impact of integrating multiple pedagogical approaches.

Educators can select from a variety of AI learning tools based on learning objectives and tool functionalities. Lee and Kwon (2024) categorizes these tools into three groups: programming languages and environments, machine learning and AI platforms, and educational platforms and provisioning, which include tools such as Scratch, Scikit- Learn, and School-Book. When choosing or developing AI tools, educators must consider factors such as age-appropriateness (Lee & Kwon, 2024) and alignment with the content being taught. It is also crucial for educators to regularly assess the eﬀectiveness of these tools in achieving instructional goals and make necessary adjustments based on feedback. Thoughtful integration of these tools can enhance teaching and learning outcomes.

Regarding AI learning outcomes, research has primarily focused on areas such as AI knowledge acquisition (Chiu et al., 2022; Aung et al., 2022), skills and performance related to AI (Park & Kwon, 2024; Shamir & Levin, 2021), motivation and attitudes (Aung et al., 2022; Chiu et al., 2022), and social impact and career exploration (Lin et al., 2022; Park & Kwon, 2024). Notably, AI knowledge is often assessed alongside other critical skills, such as problem-solving (Park & Kwon, 2024) and computational thinking (Shamir & Levin, 2021). Although Lee and Kwon (2024) acknowledges the signiﬁcant contributions of these studies in enhancing students’ AI literacy, no research has systematically evaluated classroom eﬀectiveness based on the four dimensions of AI literacy: understanding AI, applying AI, evaluating and creating AI, and AI ethics (Ng et al., 2021b).

The integration of established learning theories, pedagogical approaches, and learning tools is essential for developing students’ AI literacy through classroom implementation. According to Lee and Kwon (2024)’s systematic review, AI classroom instruction topics include (a) awareness of AI, (b) AI applications, and (c) future work in AI. However, existing research lacks a comprehensive, quantitative analysis of classroom teaching practices that encompass learning theories, pedagogical approaches, learning tools, and AI literacy. This gap hinders a thorough understanding of the current state of AI education.

3. Research aims and questions

This study proposes a novel quantitative method for analyzing AI classroom instruction videos. The method involves converting class-

RQ1: To what degree are the results of LLM’s analysis of AI classroom instruction videos reliable?

RQ2: Which learning theories, pedagogies approaches, and learning tools have been commonly used, and what are the outcomes of AI literacy in K-12 AI education?

RQ3: What types of AI classroom instruction can be classiﬁed by integrating learning theories, pedagogical approaches, learning tools, and AI literacy?

4. Methods

To address the research questions posed, we devised two paths for analyzing the AI classroom instruction videos at both primary and secondary levels: LLMs-based analysis and manual analysis. Drawing from the ﬁndings yielded by LLMs-based analyses, we extract and examine the salient characteristics inherent in the learning theories, pedagogical approaches, learning tools, and AI literacy associated with AI classroom instruction in K-12 settings, as shown in Fig. 1.

Our study focuses on four independent variables: learning theories, pedagogical approaches, learning tools, and AI literacy. To analyze these variables, we developed a comprehensive Python-based program as our primary research tool. This program utilizes ﬀmpeg for Video-to-Speech conversion, OpenAI’s Whisper model for Speech-to-Text transcription, and NVIDIA’s Nemo (Nvidia, 2024) for Text-to-Dialogue processing. The core analysis is performed using GPT-4 API provided by Microsoft Azure cloud services, which interprets the dialogue to extract information on our independent variables. We crafted specialized prompts to guide the LLM in analyzing these four independent variables. Our tool chain allows for systematic processing of multimodal classroom data, providing a robust framework for quantitative analysis of AI education practices.

4.1. Data source

Starting in 2020, China initiated a pilot program in select primary and secondary schools to introduce AI courses. A portion of these classes were comprehensively video recorded and subsequently shared as open educational resources. The dataset for this study is exclusively derived from AI classroom instruction videos from a central city in China, encompassing a total of 98 videos, each conducted by various teachers. The duration of these videos varies, ranging from a minimum of 30 minutes to a maximum of 46 minutes.

The collection of 98 instructional videos is divided between primary and secondary schools, with 90 videos for primary schools and 8 for secondary schools. Speciﬁcally, the breakdown for primary schools includes 6 videos for 3rd grade, 37 videos for 4th grade, and 46 videos for 5th grade. In contrast, secondary school features 1 video for 6th grade, 3 videos for 7th grade, and 1 video for 8th grade. The program is predominantly focused on primary school, and the majority of the videos are concentrated in 4th and 5th grades. There are a total of 62 teachers, divided between primary and secondary schools, with 55 teachers for primary schools and 7 for secondary schools. Speciﬁcally, 3 teachers are for 3rd grade, 26 teachers for 4th grade, and 29 teachers for 5th grade. There is 1 teacher for 6th grade. Additionally, 3 teachers teach across both 4th and 5th grades, and 1 teacher teaches across both 5th and 6th grades.

Fig. 1. Framework for analyzing AI classroom instruction in K-12 settings.

4.2. LLMs-based analysis

quently, ﬀmpeg is used once again to adjust the output audio to the optimal frequency of 16,000 Hz for speech processing. • Speech-to-Text conversion. Given the superior capabilities of OpenAI’s Whisper model in speech recognition, this study adopts Whisper-large-v3 for the conversion of speech to text. Throughout the process, audio segments are partitioned into 30-second chunks, and Flash-Attention 2 is employed to expedite the computation. The transcription output not only encompasses the textual content but also annotates each segment with its corresponding start and end times, thereby streamlining the alignment of speaker turns. • Text-to-Dialogue conversion. To discern the distinct speaker identities within the text content, the study employs NVIDIA’s NeMo (Nvidia, 2024) for speaker diarization. Given the variable number of student participants in class discussions, speaker labels are provisionally assigned as “teacher,” “student 1,” “student 2,” and so forth. The diarization process involves speech activity detection, executed by the “𝑣𝑎𝑑_𝑚𝑢𝑙𝑡𝑖𝑙𝑖𝑛𝑔𝑢𝑎𝑙_𝑚𝑎𝑟𝑏𝑙𝑒𝑛𝑒𝑡” model, and speaker identiﬁcation, conducted using the 𝑡𝑖𝑡𝑎𝑛𝑒𝑡_𝑙𝑎𝑟𝑔𝑒model. A matching algorithm, predicated on the principles of intersection and coverage, is developed to quantify the correspondence between the transcribed text and the identiﬁed speakers. The outcome is a structured classroom dialogue, establishing a one-to-one relationship between the speakers and their respective textual contributions.

This study develops an intelligent AI classroom instruction video analysis framework, incorporating a suite of technologies including speech recognition, speaker diarization, and long text analysis, as illustrated in Fig. 1.

4.2.1. Extraction of class dialogue Classroom dialogue provides valuable insights into the learning theories and pedagogical approaches employed by educators, encapsulating details about both the educational tools utilized and the resulting students’ AI literacy. However, collecting extensive datasets of classroom dialogue poses signiﬁcant challenges. In contrast, videos of classroom instruction are more accessible and abundant. This study harnesses such video resources to extract classroom dialogues, employing a sequential process that includes Video-to-Speech, Speech-to-Text, and Text-to- Dialogue conversion.

• Video-to-Speech conversion. The ﬀmpeg library is employed to isolate the audio tracks from classroom instruction videos. Nonetheless, these original tracks may include background music and noise that potentially impede the accuracy of subsequent speech recognition processes. To mitigate this issue, the demucs library is utilized to segregate spoken dialogue from extraneous sounds. Subse-

• Long text chunking. The upper token input threshold for GPT-4 stands at 8,192 tokens, yet the classroom dialogues in question extend between 10,000 and 19,000 tokens, surpassing the single input capacity of the model. To address this, a sentence-level text chunking algorithm has been designed. With the aid of the tiktoken package, this algorithm tallies tokens for individual sentences and segments the text into portions, each not exceeding 6,000 tokens. Consequently, the comprehensive classroom dialogue is systematically segmented into 2 to 4 such chunks for processing. • Prompt construction. The eﬀectiveness of large language model outputs hinges on well-crafted input prompts. For optimized AI classroom instruction analysis, prompt design is stratiﬁed across three critical dimensions. Firstly, the model’s role is articulated, casting it as an expert in AI education. Secondly, the model’s tasks are delineated, analyzing classroom dialogue from the viewpoints of learning theories, pedagogical approaches, learning tools, and AI literacy. Learning theories encompass Behaviorism, Cognitivism, and Constructivism. Pedagogical approaches span a variety that includes Direct instruction, Interactive learning, Experiential learning, Project-based / Problem-based learning (PBL), Participatory learning, Collaborative learning, Hands-on only, Situated learning, Game-based learning, Inquiry-based learning, and Design-oriented learning. Learning tools are extended to both hardware and software resources. AI literacy is deﬁned as knowledge and understand AI, use and apply AI, evaluate and create AI and AI ethics. Finally, the desired format for the output is stipulated as JSON, to streamline the integration with subsequent statistical analyses. Detailed prompt exemplars are systematically outlined in Appendix A. • Classroom instruction analysis. The analysis is conducted using the GPT-4 model, which operates on carefully constructed prompts in step 2. At the beginning of the analysis process, the overarching prompts are introduced to the model. It is then explicitly communicated that the classroom dialogue will be presented in segmented parts due to its length. Upon the sequential input of these parts, the model proceeds to the summarization and comprehensive analysis phase.

4.3. Manual analysis

The manual evaluation process is centered around the design of analysis questionnaires and the manual quantitative analysis of the AI classroom instruction videos. Expertise in education was a prerequisite for the graduate students who were enlisted to scrutinize the AI classroom. Questionnaire Star served as the chosen platform for the aggregation of the responses.

• Analysis questionnaire design. The questionnaire is comprehensively constructed to explore four fundamental dimensions: learning theory, pedagogical approaches, learning tools, and AI literacy. Formatted as multiple-choice questions, it comprises a set of ﬁve items, including one that speciﬁcally requests the name of the AI classroom. Every question enumerates all potential answers, ensuring alignment with the prompts of the large language model. For instance, within the learning theory category, the choices span Behaviorism, Cognitivism, and Constructivism. Please see Appendix B for the detailed questionnaire. • Manual quantitative analysis. Each AI instructional Video spans 40 minutes, making the manual analysis of each video quite time-

4.4. Comparison of two paths

Given that the outcomes derived from both LLMs-based analysis and manual analysis can be interpreted as a series of categorical choices, we utilize the Jaccard index to quantify the similarity between the results obtained through these two methodologies. The computation of this measure is as follows.

𝑆𝑖𝑚𝑖𝑙𝑎𝑟𝑖𝑡𝑦= (𝐿∩𝑀)∕(𝐿∪𝑀) ∗100% (1)

L denotes the set of results from the LLMs-based analysis, while M signiﬁes the set emerging from the manual analysis. “L ∩M” denotes their intersection, and “L ∪M” represents their union. A higher Jaccard index value is indicative of greater consistency between the ﬁndings of the two analytical approaches.

4.5. Further exploration of analysis results

To delve deeper into the characteristics of AI classroom instruction in K-12 settings from four key perspectives—learning theories, pedagogical approaches, learning tools, and AI literacy — we expanded our research to the classiﬁcation of AI classroom instruction and the interrelationships among the four aspects. This comprehensive analysis was based on analysis results generated through LLMs. We treated the selection within each aspect as a separate dimension, resulting in a total of 19 distinct dimensions. Speciﬁcally, learning theories comprise 3 dimensions, pedagogical approaches encompass 10 dimensions, learning tools are divided into 2 dimensions, and AI literacy is broken down into 4 dimensions. The analytical outcomes for 98 AI classroom instruction videos were organized into a 98 by 19 matrix. Entries in the matrix are binary, consisting of 0 s and 1 s; where a ‘1’ signiﬁes the implementation of a particular approach or tool within that dimension, and a ‘0’ indicates non-implementation.

4.5.1. AI classroom instruction types from four perspectives To gain a more nuanced understanding of the overarching pedagogical traits of AI classroom instruction in k-12 settings, we applied a clustering technique to the 19-dimensional data we had structured. The process principally involved three steps:

• Data dimensionality reduction. For dimensionality reduction, we employed the Principal Component Analysis (PCA) method, which preserved the core teaching characteristics of AI classroom instruction. • Calculate the optimal number of clusters. To determine the most suitable number of clusters, we utilized the K-means algorithm, performing iterative clustering ranging from 1 to 10 clusters. This

approach resulted in identifying 3 as the optimal number of clusters. The clustering result of K-means is shown in Fig. 2a, but according to the distribution of data points in the ﬁgure, there are still some data points belonging to the category that need to be further corrected. • AI classroom instruction types. Recognizing that linear boundaries might not adequately separate the data, we employed the Gaussian Mixture Model (GMM) and adhered to the previously established cluster count of three to categorize each classroom instruction video. After classiﬁcation, our ﬁndings indicate that AI classroom instruction in K-12 settings can be distinctly categorized into three types. We further analyzed the pedagogical approaches and instruction content of these three types of classroom instruction. Ultimately, we deﬁne these three types of classroom instruction as Conceptual, Experimental, and Heuristic. (Fig. 2b).

4.5.2. Classroom instruction characteristics analysis from four perspectives To analyze the correlations among various dimensions, we utilized a 19-dimensional matrix and implemented the AGENS algorithm for hierarchical clustering. This process consists of three main steps:

• Initialization of Cluster Set. Each dimension is initially treated as an individual cluster. In our study, each cluster is represented as a row vector containing 98 elements, corresponding to the number of classroom instruction videos analyzed. Consequently, we begin with a total of 19 clusters. • Circular Hierarchical Clustering. We employ the Euclidean distance metric to assess the similarity between clusters. The two clusters demonstrating the closest proximity are merged to form a new, combined cluster. This process is indicative of the hierarchical clustering principle, where clusters at lower levels of the tree exhibit higher similarity. After each merging step, we recalculate the similarities among all remaining clusters and continue this iterative clustering until only one cluster remains or a predeﬁned condition is met. • Drawing Hierarchical Relationship Tree. To visualize the hierarchical relationships among the dimensions, we utilize the dendrogram package to create a dendrogram based on the 19x98 matrix. To enhance the clarity and relevance of the dendrogram, we preprocess the data by excluding dimensions where over 80% of the data points are either 1 or 0. This step helps in focusing on the dimensions that provide more variability and potentially more insightful correlations.

Fig. 2. AI classroom instruction classiﬁcation. (a) Clustering features of K-means (b) Clustering features of GMM.

5. Results

5.1. Comparison of LLMs-based analysis and manual analysis

To assess the coherence between analyses conducted using LLMs and those performed manually, we quantiﬁed various perspectives including learning theory, pedagogical approaches, learning tools, learning outputs, and overall similarity. According to Fig. 3, a high degree of consistency was observed between LLM-based analysis and manual analysis, particularly in objective categories such as learning tools, where a perfect 100% match was achieved.

In the dimension of learning theory, the LLMs accurately identiﬁed Constructivism as the primary learning theory. However, the manual analysis revealed the presence of Behaviorism in one classroom and Cognitivism in two, indicating that LLMs may have prioritized the predominant learning theory. For pedagogical approaches, concordance between LLM-based and manual analyses was observed with Interactive learning, Inquiry-based learning, Direct instruction, Participatory learning, Design-oriented learning, and Situated learning. Discrepancies emerged in 1-2 classrooms concerning Collaborative learning, PBL, and Experiential learning, likely because these methods are more discernible through visual cues in the video, whereas LLMs relied solely on transcribed teacher dialogue. Determining learning output proved the most challenging, requiring a match between teacher-delivered content and speciﬁc AI literacy like knowledge, application skills, evaluation skills, and ethics. The LLM was adept at ascertaining elements related to ‘Knowledge and Understanding AI’ and ‘Using and Applying AI’. Nonetheless, there was a miss rate of 1-2 lessons for ‘Evaluate and Create AI’ and ‘AI Ethics’. This is principally attributed to homophonic errors in the conversion of speech to Chinese text, leading to semantic errors.

5.2. Statistics analysis of AI classroom instruction

We conducted a statistical analysis of AI classroom instruction videos in K-12 settings from four perspectives, as detailed in Fig. 4. The analysis sheds light on the prevalent learning theories, pedagogical approaches, learning tools, and focus areas of AI literacy training. The percentages shown in Fig. 4 indicate the proportion of lessons that incorporate each teaching approach at least once.

For learning theory, all AI classroom instruction in our dataset adheres to Constructivism as the foundational learning theory, which underscores the distinct characteristics of AI education compared to traditional subjects. This approach emphasizes student-centered learning, with teachers facilitating rather than directing the learning process. This ﬁnding aligns with existing research that reviews AI education practices (Kim et al., 2021a; Xiao & Song, 2021).

Fig. 3. Comparison of LLMs-based analysis and manual analysis.

Fig. 4. Statistics analysis of AI classroom instruction in K-12 settings.

In terms of pedagogical approaches, our analysis shows that 100% of the lessons incorporate Interactive learning, meaning every lesson in our sample includes at least one segment employing Interactive learning. Contrary to the expectations set by the review literature (Ng et al., 2023), which suggests that PBL) is the predominant pedagogical approach in AI classroom instruction, our ﬁndings reveal that only 42.86% of the lessons implemented this approach. Inquiry-based and Collaborative learning were more prevalent, used in over 60% of the lessons, encouraging students to collaborate on research projects centered around speciﬁc AI-related issues. Other methods, such as Design-oriented learning, Situated learning, and Game-based learning, were less common,

appearing in less than 12% of the lessons. This indicates a potential

shortage of situational and game-based educational tools that could en-

hance student interest and engagement.

Regards learning tools, software tools were the primary learning

aids, used in 79.59% of classroom instruction, which mainly focused

on software algorithms and applications, such as computer vision and

natural language processing. Hardware tools were less prevalent, used

in 38.78% of classroom instruction, and only 24.49% of classroom in-

struction combined both software and hardware tools, indicating a lesser

In the aspect of AI literacy, the aspect of AI literacy revealing the most signiﬁcant oversight is AI ethics, which was mentioned in only 5.1% of classrooms. This suggests a need for greater emphasis on imparting ethical considerations of AI use among students. Additionally, while most classroom instructions cover basic AI knowledge and application skills, only 35.71% extend into higher-level skills such as evaluating and creating AI, indicating potential areas for further curriculum development to enhance higher-order cognitive skills.

5.3. The types of AI classroom instruction

The AI classroom instruction videos analyzed have been categorized into three distinct types: Conceptual, Heuristic, and Experimental, each comprising 50%, 18.37%, and 31.63% of the total classroom instruction videos respectively. These categories exhibit signiﬁcant diﬀerences in their pedagogical approaches and focus on AI literacy as illustrated in Fig. 5. Most of these three types of classroom instruction are based on constructivism. Below are the three types of classroom instruction from pedagogical approaches, AI literacy, and content focus.

(1) Conceptual: This type of AI classroom instruction focuses on understanding fundamental principles and theories. The teaching often emphasizes core AI concepts, enabling students to grasp the essential ideas and frameworks that underpin the ﬁeld.

• Pedagogical approaches: Direct instruction and participatory learning are prevalent, promoting learning through discussion and engagement. For example, in the “Starting the Python journey” classroom, the teacher provides explanations about AI applications, such as logistics and medical uses, thereby giving information directly to

Fig. 5. Three types for AI classroom instruction integrating learning theories, pedagogies approaches, learning tools, and AI literacy.

the students. In the “Into the Internet of Things” classroom, the teacher directly explains the working principle of smart devices such as XiaoAi speakers and smart doorbells. • AI Literacy: There is less emphasis on enabling students to evaluate and create AI, focusing more on foundational knowledge. This type of classroom tends to prioritize understanding basic concepts and theories over the development of critical thinking and practical skills necessary for AI innovation and application. Consequently, students may lack the competencies required to critically assess AI technologies and contribute to their development. • Content Focus: Conceptual instruction typically covers basic AI concepts and application scenarios. The topics such as “Into Big Data”, “Into the Internet of Things”, “Introducing Artiﬁcial Intelligence”, “Opening the Door of Wisdom”, “Starting the Python Journey” and “Journey to the Future” suggest an emphasis on broader understanding rather than deep technical skills.

(2) Heuristic: This type of AI classroom instruction encourages students to develop intuitive strategies and rules of thumb for tackling problems. Lessons often include case studies, and practical examples, that require students to apply their knowledge creatively and adaptively.

• Pedagogical Approaches: All heuristic classroom instruction employs Inquiry-based learning and PBL, aiming to foster problemsolving skills and critical thinking. However, participatory learning and experimental learning are used less frequently, indicating a focus on individual or small-group problem-solving rather than large-group discussions. For example, in the “Smart Navigation” classroom, the teacher fosters the spirit of inquiry by centering a

practical, real-world problem and prompting students to explore diﬀerent routes to their destination and choose the best one. • AI Literacy: The focus is on applying AI concepts to real-world problems, but there may be less emphasis on developing collaborative skills due to the lower use of group-based methods. While students are encouraged to understand and utilize AI in practical contexts, the lack of emphasis on group activities may hinder the development of teamwork and communication skills, which are essential for collaborative innovation in AI. • Content Focus: These classroom instructions tend to concentrate on speciﬁc practical problems, such as “Smart Navigation”, “Explore the Sorting Robot”, “AI in Life”, “Exploring Face Recognition” and “The Secret of the Human Face”, with a medium granularity of knowledge points.

(3) Experimental: This type of classroom instruction encourages students engage in designing, building, and testing AI models and applications. The aim is to provide students with practical skills and direct experience in developing and implementing AI technologies.

• Pedagogical Approaches: Predominantly utilizing PBL, these classroom instructions encourage active and collaborative learning environments. Direct instruction is less commonly used, supporting a more student-led approach. For instance, in the “Target Tracking - The Little Detective” classroom, the teacher designs an activity where students are tasked with creating a crime-tracking device. The students are divided into eight groups to collaboratively work on this task. Similarly, in the “Smart Trash Can (Lessons 1-4)” series, the teacher engages students in brainstorming and discussing the issues associated with traditional trash cans and exploring how smart trash cans could address these problems. • AI Literacy: There is a signiﬁcant emphasis on training students to both evaluate and create AI, indicating a higher level of cognitive skills development compared to the other types. This approach ensures that students not only understand AI concepts but also apply them critically and innovatively to real-world scenarios. • Content Focus: The classroom instruction often consists of a series of classroom instruction with a ﬁner granularity of knowledge points, suggesting a deeper dive into speciﬁc AI technologies or applications.

The dendrogram produced from our hierarchical clustering analysis provides insightful revelations into the relationships between diﬀerent pedagogical approaches and their impact on AI literacy. As depicted in Fig. 6, the distance value between “Project-based learning/Problembased learning” and “Evaluate and create AI” is 5.20, the dendrogram clearly indicates a signiﬁcant association between PBL methods and the cultivation of capabilities to “evaluate and create AI.” However, previous classiﬁcation results suggest that using PBL alone may not suﬃce for the promotion of higher-order AI literacy. Instead, when PBL is combined with Collaborative Learning, there is a notable improvement in developing advanced AI literacy skills. This combination likely oﬀers a richer, more interactive learning atmosphere that fosters deeper understanding and skill development. The hierarchical relationship tree

Fig. 6. Three types of classroom instruction’s characteristics analysis.

further supports these ﬁndings by showing that Collaborative Learning is linked closely with PBL and the “evaluate and create AI” capabilities at a higher hierarchical level. This alignment underscores the synergy between these methods and their collective impact on advancing AI literacy. Additionally, the distance value between “Experiential learning” and “Hardware tools” is 5.20, it indicates that classroom instruction videos incorporating hardware tools tend to adopt Experimental Learning methods. This combination is likely due to the hands-on nature of hardware tools.

6. Discussion

The integration of AI into K-12 education has gained signiﬁcant attention, with various countries and international organizations establishing frameworks to guide AI course development. However, existing AI education research lacks data-driven analyses of classroom practices and comprehensive studies integrating learning theories, pedagogical approaches, tools, and AI literacy outcomes. This study addresses this gap by employing LLMs to construct an intelligent analysis framework, enabling the classiﬁcation of AI classroom instruction based on four key perspectives: learning theory, pedagogical approaches, learning tools, and AI literacy.

6.1. Comparison of LLMs-based analysis and manual analysis on AI classroom instruction

To validate the eﬀectiveness of our LLM-based analysis framework, we conducted a comparative study between LLM-based analysis and traditional manual analysis of AI classroom instruction. Our ﬁndings reveal a high degree of consistency between LLM-based and manual analyses across various dimensions of AI education. This aligns with recent research (Parker et al., 2024), which demonstrated that GPT-4 achieves human or near-human level performance across a range of tasks in analyzing education feedback surveys.

In terms of learning tools and learning theory analysis, the results of LLM-based analysis show a high degree of consistency with manual analysis. The perfect 100% match in identifying learning tools demonstrates the LLM’s proﬁciency in recognizing and categorizing speciﬁc educational resources mentioned in the course transcripts. This suggests that LLMs can be particularly eﬀective in tasks requiring the identiﬁcation of concrete, well-deﬁned elements within educational contexts.

While there was strong concordance in identifying most pedagogical approaches, minor discrepancies were observed in 1-2 courses for Collaborative Learning, PBL, and Experiential Learning. These diﬀerences likely stem from the LLM’s reliance on textual data alone, whereas manual analysis beneﬁted from visual cues in the video recordings. This limitation highlights the potential for enhancing LLM performance by incorporating multimodal data in future analyses.

The assessment of learning outcomes presented the greatest challenge, with the LLM showing high accuracy in identifying ‘Knowledge and Understanding AI’ and ‘Using and Applying AI’, but occasionally missing ‘Evaluate and Create AI’ and ‘AI Ethics’ in 1-2 lessons. This discrepancy can be attributed to the complexity of inferring higher-order

The high level of consistency between LLM-based and manual analyses in most areas supports the viability of using LLMs for large-scale analysis of educational content. This approach oﬀers signiﬁcant advantages in terms of eﬃciency and scalability, potentially allowing for more comprehensive and frequent assessments of AI education programs. However, the identiﬁed discrepancies also point to areas for improvement, such as integrating visual and auditory data alongside text to enhance the LLM’s ability and ﬁne-tuning LLMs on educational datasets.

6.2. Current status of AI classroom instruction in k-12 settings based on LLMs analysis

Our LLM-based analysis of AI classroom instruction in K-12 schools reveals a complex landscape that both aligns with recent research ﬁndings and highlights signiﬁcant gaps in current AI education practices. This comprehensive examination provides crucial insights into the theoretical underpinnings, pedagogical approaches, and content focus of existing AI curricula, addressing several key areas in the literature.

The analysis categorized AI classroom instruction into three main types: conceptual (50%), heuristic (18.37%), and experimental (31.63%). This distribution basically aligns with recent studies on AI education content (Lee & Kwon, 2024), reﬂecting a balanced approach between theoretical understanding and practical application. However, this balance may not be optimal for developing the full spectrum of AI literacy skills required in the rapidly evolving ﬁeld of artiﬁcial intelligence.

Conceptual instruction, focusing on broad AI concepts through direct instruction and participatory learning, provides a crucial foundation for AI understanding (Alonso, 2020). However, our ﬁndings suggest that this approach alone may be insuﬃcient for developing higher-order AI skills, highlighting a potential area for curriculum enhancement. Experimental instruction, emphasizing PBL and group collaboration, aligns with research demonstrating the positive impact of hands-on AI tools on students’ computational thinking and self-eﬃcacy (Shamir & Levin, 2022). This approach shows promise in fostering higher-level AI literacy but is currently underrepresented in the curriculum. Heuristic instruction, while employing inquiry-based and PBL approaches, lacks suﬃcient practical and collaborative elements. This gap presents an opportunity for improvement, as collaborative learning has been shown to enhance AI literacy and motivation.

The analysis reveals a preference for traditional teaching methods over innovative approaches like situated learning and game-based learning. There is the signiﬁcant deﬁciency in teaching high-level AI skills (evaluate and create AI), with only 35.71% of classroom instruction engaging in these areas. Our ﬁndings suggest that current approaches may not adequately support the development of higher-order AI skills, indicating a need for instructional redesign to address this shortfall.

Perhaps most concerning is the signiﬁcant underrepresentation of AI ethics in classroom instruction, with only 5 out of 98 instances addressing this critical area. This ﬁnding is particularly alarming given the growing emphasis on ethical AI. Researchers have emphasized the importance of developing an understanding of the risks, biases, and beneﬁts associated with AI as a crucial component of AI literacy (Jang et al., 2022; Monteith et al., 2022). The lack of focus on AI ethics in current instruction represents a critical gap between educational practices and the ethical considerations necessary for responsible AI development and use.

6.3. Directions for improving AI classroom instruction in k-12 settings

Our analysis of AI courses indicates signiﬁcant potential for enhancement in AI literacy, pedagogical strategies, and content design for AI education in primary and secondary schools.

Our correlation analysis indicates that combining PBL with Collaborative learning can eﬀectively develop higher-level AI skills. However, currently, less than 40% of teachers utilize these proven methods. Additionally, innovative educational approaches like Situated Learning and Game-based Learning, despite their potential to boost engagement and contextual understanding, are rarely implemented. Future AI course instruction should expand the use of eﬀective instructional strategies and incorporate both Situated and Game-Based Learning to enhance the educational experience.

The AI teaching in k-12 schools is often characterized by coarsegrained content and lacks a systematic structure, which impedes the development of advanced AI literacy. To rectify this, future AI education should focus on creating a more structured curriculum that progressively builds upon students’ knowledge and skills. This could entail a series of interconnected courses that gradually increase in complexity and depth, thereby fostering a robust and comprehensive understanding of AI.

We recommend that future research initiatives focus on integrating multi-modal data sources to provide a more comprehensive understanding of AI classroom dynamics. Additionally, we propose that researchers design and implement extended research projects that track students’ AI literacy development from elementary through secondary education. These studies should aim to evaluate how diﬀerent instructional approaches, particularly those combining collaborative learning and PBL, inﬂuence students’ AI knowledge acquisition, skill development, and career aspirations over time.

For curriculum writers, we recommend developing dedicated modules that explore ethical implications of AI, including privacy concerns, potential biases, and societal impacts. These modules should be woven throughout the curriculum, progressively building students’ understanding of AI ethics as they advance in their studies. Furthermore, curriculum writers should focus on designing project-based units that challenge students to critically assess existing AI systems and create their own AI solutions.

We strongly recommend that teachers explore and implement instructional strategies that integrate collaborative learning with PBL approaches. This could involve designing group projects where students collaboratively tackle real-world AI challenges, fostering both teamwork skills and practical AI knowledge.

For policymakers, we recommend developing comprehensive AI education standards that explicitly require the integration of ethics throughout the curriculum. These standards should also emphasize the importance of hands-on, project-based learning experiences that engage students in evaluating and creating AI solutions.

6.4. Limitations

While our study employs LLMs to conduct a quantitative analysis of AI classroom instruction, the approach presents certain limitations.

Our current analysis framework primarily relies on dialogue data from teacher-student interactions, lacking multi-modal data integration. This limitation can reduce the visibility of less dialogue-intensive pedagogical approaches like Collaborative learning. Future research should explore ways to incorporate visual and other non-verbal data to provide a more comprehensive analysis of classroom dynamics.

The assessment of AI literacy development is based on observed teaching content and methods, which may not accurately reﬂect actual student outcomes. Future studies should incorporate direct measures of student learning and skill development to validate the eﬀectiveness of diﬀerent instructional approaches. Our study focused on publicly available AI classroom instruction videos, which may not represent the full spectrum of AI education approaches globally. This limitation could introduce selection bias, potentially overrepresenting certain types of instruction or educational contexts.

The use of LLMs as the primary analytical tool may introduce biases based on the training data and algorithms used. Future research should consider triangulating LLM analysis with other methodologies to enhance the robustness of ﬁndings. The statistical analyses conducted in this study are based on the LLM’s interpretation of classroom instruction, which may not capture all nuances of human-led analysis. Further validation of these statistical outcomes through human expert review would strengthen the reliability of our ﬁndings.

Our analysis does not account for potential variations in student demographics, prior knowledge, or learning styles. This limitation could mask important diﬀerences in the eﬀectiveness of various instructional approaches for diﬀerent student populations. Additionally, all experimental data in this study are sourced from publicly available AI classroom instruction videos. This reliance on public data may introduce a bias towards instruction that is more likely to be recorded and shared, potentially excluding valuable insights from less visible educational contexts.

7. Conclusion

This study addresses a critical gap in AI education research by developing an innovative framework for analyzing classroom instruction using LLMs. Our approach provides a quantitative analysis of actual classroom data, moving beyond the limitations of previous research that primarily relied on literature reviews. Our ﬁndings reveal key insights into the current state of AI education in K-12 settings, identifying three distinct types of AI courses: conceptual, heuristic, and experimental, with conceptual courses being the most prevalent.

Our analysis indicates a signiﬁcant gap in training for advanced AI literacy skills, particularly in evaluating and creating AI systems. We also found a concerning underrepresentation of AI ethics in current curricula. These ﬁndings underscore the need for more balanced AI curricula that incorporate ethics, advanced AI skills, and innovative teaching methods. Our study reveals that combining collaborative learning with PBL can eﬀectively develop higher-level AI skills, though PBL was implemented in less than half of the observed courses.

These insights have signiﬁcant implications for curriculum developers, educators, and policymakers, emphasizing the need for more comprehensive and ethically grounded AI education. While our study provides valuable insights, we acknowledge its limitations, particularly in analyzing only processed teacher-student dialogue data and basing observations on single lessons.

Future research should address these limitations by integrating multi-modal large models for more comprehensive analysis and conducting longitudinal studies to better understand the long-term impact of AI education approaches. As AI continues to shape our world, ensur-

Ethical approval

The study was approved by an ethical committee with ID: CCNU- IRB-202408001A. Informed consent was obtained from all participants, and their privacy rights were strictly observed.

CRediT authorship contribution statement

Di Wu: Writing – review & editing, Methodology, Conceptualization. Meng Chen: Writing – original draft, Visualization, Formal analysis. Xu Chen: Writing – original draft, Software, Data curation. Xing Liu: Writing – original draft, Validation.

Declaration of competing interest

The authors declare that they have no known competing ﬁnancial interests or personal relationships that could have appeared to inﬂuence the work reported in this paper.

Data availability

The data can be obtained by sending request e-mails to the corresponding author.

Acknowledgements

This work was supported by the National Natural Science Foundation of China (Grant No 42301496).

Appendix A. Prompts for AI classroom instruction analysis

The complete prompts utilized for AI classroom instruction Analysis are as follows:

“As an education expert in K-12 AI classroom instruction videos, you are conducting a systematic analysis of a given K-12 artiﬁcial intelligence course from four dimensions: learning theory, pedagogical approaches, learning tools, and learning outcomes. In terms of learning theory, it includes Behaviorism, Cognitivism, and Constructivism. Pedagogical approaches include Direct instruction, Interactive learning, Experiential learning, Project-based learning/Problem-based learning, Participatory learning, Collaborative learning, Hands-on only, Situated learning, Game-based learning, Inquiry-based learning, and Designoriented learning. Learning tools include Hardware tools and software applications. For example, smart fans and infrared sensors are hardware tools. Hardware tools do not consider common devices such as interactive whiteboards and large screens. Scratch and lab platforms are software applications. Learning outcomes encompass knowledge and understand AI, use and apply AI, valuate and create AI and AI ethics. Based on the above content, please analyze the learning theory, pedagogical approaches, and learning tools employed in the given text, and identify the student abilities developed in the four dimensions of learning outcomes. The ﬁnal result is output in Json format, refer to the sample below.

<{ “Learning theory”: “Constructivism”: “This is evident in the way the teacher prompts students to guess and describe processes, encouraging them to construct knowledge through exploration and discussion. The dialogue shows the teacher facilitating an environment where students actively construct their understanding of the sorting robot’s functionality through guided discovery rather than simply receiving information passively.”,

“Problem-based learning”: “The teacher is guiding the students to think about the problem of sorting coins and fruits, and how technology can address this problem.” “Direct Instruction”: “The teacher explains the concepts and functionality of the robot and its components” ],

“Learning tools”: [ “Hardware tools”:” infrared sensors”, ], “Learning outcomes”: { “Knowledge and understand AI”: { “Developed”: true, “Examples”: [ “Understanding the functionality of sorting robots”, “Recognizing the role of size and color in sorting mechanisms”, “Comprehending the concept of image recognition in AI” ] },

“Use and apply AI”: { “developed”: true, “examples”: [ “Discussing the practical application of sorting robots”, “Identifying the use of AI in logistical operations” ] },

“Evaluate and create AI”: { “Developed”: false, “Examples”: [] }, “AI ethics”: “Developed”: false, “Examples”: [] } }>”

Appendix B. Analysis questionnaire for AI classroom instruction (translated to English)

B.1. Which one or more of these learning theories do you think has been primarily adopted in this classroom instruction video?

1. Constructivism 2. Cognitivism 3. Behaviorism

B.2. What do you think are the main pedagogical approaches taken in this classroom instruction video?

1. Interactive learning 2. Experiential learning 3. Inquiry-based learning 4. Participatory learning 5. Direct instruction 6. Project-based / Problem-based learning 7. Collaborative learning 8. Design-oriented learning 9. Game-based learning 10. Situated learning

B.3. What learning tools do you think are used in this classroom instruction video?

1. Hardware tools, e.g. smart fans, infrared sensors, etc 2. Software applications, e.g. Scratch, lab platforms, etc

B.4. What aspects of AI literacy do you think are being developed in this classroom instruction video?

1. Knowledge and understand AI 2. Use and apply AI 3. Evaluate and create AI 4. AI ethics

AI4K12 (2019). Five big ideas about ai. https://ai4k12 .org /big -idea -1 -overview/. (Ac-

cessed 10 May 2024). Alonso, J. M. (2020). Teaching explainable artiﬁcial intelligence to high school students.

International Journal of Computational Intelligence Systems, 13, 974–987. https://doi . org /10 .2991 /ijcis .d .200715 .003. Aung, Z. H., Sanium, S., Songsaksuppachok, C., Kusakunniran, W., Precharattana, M.,

Chuechote, S., Pongsanon, K., & Ritthipravat, P. (2022). Designing a novel teaching platform for ai: A case study in a Thai school context. Journal of Computer Assisted Learning, 386, 1714–1729. https://doi .org /10 .1111 /jcal .12706. Bergman, I., Franke Föyen, L., Gustavsson, A., & Van den Hurk, W. (2024). Test–retest

reliability, practice eﬀects and estimates of change: A study on the mindmore digital cognitive assessment tool. Scandinavian Journal of Psychology. https://doi .org /10 . 1111 /sjop .13054. Casal-Otero, L., Catalá, A., Fernández-Morante, C., Taboada, M., Cebreiro, B., & Barro,

S. (2023). Ai literacy in k-12: A systematic literature review. International Journal of STEM Education, 10, 1–17. https://doi .org /10 .1186 /s40594 -023 -00418 -7. Chai, C. S., Lin, P.-Y., Jong, M. S.-Y., Dai, Y., Chiu, T. K. F., & Qin, J. (2021). Percep-

tions of and behavioral intentions towards learning artiﬁcial intelligence in primary school students. Educational Technology & Society, 243, 89–101. https://www .jstor . org /stable /27032858. (Accessed 4 September 2021). Chen, X., & Wu, D. (2024). Automatic generation of multimedia teaching materials based

on generative ai: Taking Tang poetry as an example. IEEE Transactions on Learning Technology, 17, 1353–1366. https://doi .org /10 .1109 /TLT .2024 .3378279. Chen, Y., Ding, N., Zheng, H.-T., Liu, Z., Sun, M., & Zhou, B. (2023). Empowering private

tutoring by chaining large language models, arXiv :2309 .08112 [abs]. https://doi .org / 10 .48550 /arXiv .2309 .08112. Chiu, T. K. F., Meng, H., Chai, C.-S., King, I., Wong, S., & Yam, Y. (2022). Creation and

evaluation of a pretertiary artiﬁcial intelligence (ai) curriculum. IEEE Transactions on Education, 651, 30–39. https://doi .org /10 .1109 /TE .2021 .3085878. Dao, X.-Q., Le, N.-B., Vo, T.-D., Ngo, B.-B., Phan, X.-D., Cooh, A. C., FeCl, B., HNO, C.,

& NaCl, D. (2023). Llms’ capabilities at the high school level in chemistry: Cases of chatgpt and Microsoft bing chat. ChemRxiv, https://doi .org /10 .26434 /chemrxiv - 2023 -kxxpd. Digcomp (2022). Digcomp 2.2: The digital competence framework for citizens - with new

examples of knowledge, skills and attitudes. https://publications .jrc .ec .europa .eu / repository /%20handle /JRC128415. (Accessed 10 May 2024). GSE (2023). Ai in education: Embracing a human-centred approach to learning.

https://www .gsineducation .com /blog /aiin -education -embracing -a -human -centered - approach -to -learning. (Accessed 20 August 2024). Heintz, F. (2021). Three interviews about k-12 ai education in America, Europe, and

Singapore. Künstliche Intelligenz, 35, 233–237. https://doi .org /10 .1007 /s13218 -021 - 00730 -w. Hicke, Y., Agarwal, A., Ma, Q., & Denny, P. (2023). Ai-ta: Towards an intelligent question-

answer teaching assistant using open-source llms. ArXiv, https://doi .org /10 .48550 / arXiv .2311 .02775. ISTE (2022). Hands-on ai projects for the classroom. https://cdn .iste .org /www -root /

Libraries /Documents %20 %26 %20Files /%20Artiﬁcial %20Intelligence /AIGDK5 _ 1120 .pdf. (Accessed 10 May 2024). Jang, J., Jeon, J., & Jung, S. K. (2022). Development of stem-based ai education program

for sustainable improvement of elementary learners. Sustainability, 1422. https://doi . org /10 .3390 /su142215178. Khayi, N. A., Rus, V., & Tamang, L. J. (2021). Towards improving open student answer

assessment using pretrained transformers. In The international FLAIRS conference proceedings. Kim, S., Jang, Y., Choi, S., Kim, W., Jung, H., Kim, S., & Kim, H. (2021a). Analyzing teacher

competency with tpack for k-12 ai education. Künstliche Intelligenz, 35, 139–151. https://doi .org /10 .1007 /s13218 -021 -00731 -9. Kim, S., Jang, Y., Kim, W., Choi, S., Jung, H., Kim, S., & Kim, H. (2021b). Why and what to

teach: Ai curriculum for elementary school. Proceedings of the AAAI Conference on Artiﬁcial Intelligence, 3517, 15569–15576. https://doi .org /10 .1609 /aaai .v35i17 .17833. Krapﬂ, J. E. (2016). Behaviorism and society. Behavior Analyst, 39, 123–129. https://

doi .org /10 .1007 /s40614 -016 -0063 -8. Laupichler, M. C., Aster, A., Schirch, J., & Raupach, T. (2022). Artiﬁcial intelligence

literacy in higher and adult education: A scoping literature review. Computers and Education: Artiﬁcial Intelligence, 3, Article 100101. https://doi .org /10 .1016 /j .caeai . 2022 .100101. Lee, S. J., & Kwon, K. (2024). A systematic review of ai education in k-12 classrooms from

2018 to 2023: Topics, strategies, and learning outcomes. Computers and Education: Artiﬁcial Intelligence, 6, Article 100211. https://doi .org /10 .1016 /j .caeai .2024 .100211. Li, L., Yu, F., & Zhang, E. ((2024). Asystematic review of learning task design for k-12 ai

education: Trends, challenges, and opportunities. Computers and Education: Artiﬁcial Intelligence, 6, Article 100217. https://doi .org /10 .1016 /j .caeai .2024 .100217. Liang, Z., Yu, W., Rajpurohit, T., Clark, P., Zhang, X., & Kaylan, A. (2023). Let gpt be a

math tutor: Teaching math word problem solvers with customized exercise generation, arXiv :2305 .14386 [abs]. https://doi .org /10 .48550 /arXiv .2305 .14386. Lin, X., Liu, H., Sun, Q., Li, X., Qian, H., Sun, Z., & Lam, T. L. (2022). Applying project-

based learning in artiﬁcial intelligence and marine discipline: An evaluation study on a robotic sailboat platform. IET Cyber-Systems and Robotics, 42, 86–96. https:// doi .org /10 .1049 /csy2 .12050.

learning .com /post /cognitivismlearning -theories. (Accessed 20 August 2024). McLeod, S. (2024). Constructivism learning theory & philosophy of education.

https://www .simplypsychology .org /constructivism .html #Constructivism -Teaching - Philosophy. (Accessed 20 August 2024). Monteith, B., Noyce, P., & Zhang, P. (2022). Teaching artiﬁcial intelligence through the

arts in Beijing. The Science Teacher, 895, 42–49. https://doi .org /10 .1080 /00368555 . 2022 .12293698. Moore, S., Nguyen, H. A., Bier, N. L., Domadia, T., & Stamper, J. C. (2022). Assessing the

quality of student-generated short answer questions using gpt-3. In European conference on technology enhanced learning (pp. 243–257). Naismith, B., Mulcaire, P., & Burstein, J. (2023). Automated evaluation of written dis-

course coherence using gpt-4 (pp. 394–403). Association for Computational Linguistics. Ng, D. T. K., Lee, M., Tan, R. J. Y., Hu, X., Downie, J. S., & Chu, S. K. W. (2023). A review

of ai teaching and learning from 2000 to 2020. Education and Information Technologies, 28, 8445–8501. https://doi .org /10 .1007 /s10639 -022 -11491 -w. Ng, D. T. K., Leung, J. K. L., Chu, S. K.-W., & Qiao, M. S. (2021a). Ai literacy: Deﬁnition,

teaching, evaluation and ethical issues. Proceedings of the Association for Information Science and Technology, 58. https://doi .org /10 .1002 /pra2 .487. Ng, D. T. K., Leung, J. K. L., Chu, S. K.-W., & Qiao, M. S. (2021b). Conceptualizing ai

literacy: An exploratory review. Computers and Education: Artiﬁcial Intelligence, 2, Article 100041. https://doi .org /10 .1016 /j .caeai .2021 .100041. Nvidia (2024). Nemo. https://github .com /NVIDIA /NeMo. (Accessed 6 March 2024). Ottenbreit-Leftwich, A. T., Glazewski, K. D., Jeon, M., Hmelo-Silver, C. E., Mott, B. W.,

Lee, S. J., & Lester, J. C. (2021). How do elementary students conceptualize artiﬁcial intelligence? In Proceedings of the 52nd ACM technical symposium on computer science education. Park, W., & Kwon, H. (2024). Implementing artiﬁcial intelligence education for middle

school technology education in Republic of Korea. International Journal of Technology and Design Education, 34, 109–135. https://doi .org /10 .1007 /s10798 -023 -09812 -2. Parker, M. J., Anderson, C., Stone, C., & Oh, Y. (2024). A large language model approach

to educational survey feedback analysis. Journal of Artiﬁcial Intelligence in Education. https://doi .org /10 .1007 /s40593 -024 -00414 -0. Payne, K. A., & Journell, W. (2019). “we have those kinds of conversations here ”: Address-

ing contentious politics with elementary students. Teaching and Teacher Education. https://doi .org /10 .1016 /J .TATE .2018 .12 .008. Sanusi, I. T., Oyelere, S. S., Vartiainen, H., Suhonen, J., & Tukiainen, M. (2023). A system-

atic review of teaching and learning machine learning in k-12 education. Education and Information Technologies, 285, 5967–5997. https://doi .org /10 .1007 /s10639 -022 - 11416 -7. Shamir, G., & Levin, I. (2021). Neural network construction practices in elementary school.

Künstliche Intelligenz, 35, 181–189. https://doi .org /10 .1007 /s13218 -021 -00729 -3. Shamir, G., & Levin, I. (2022). Teaching machine learning in elementary school. Inter-

national Journal of Child-Computer Interaction, 31, Article 100415. https://doi .org /10 . 1016 /j .ijcci .2021 .100415. Smithies, T. D., Toth, A. J., & Campbell, M. J. (2024). Test–retest reliability and practice ef-

fects on a shortened version of the category switch task – a pilot study. Journal of Cognitive Psychology, 366, 742–753. https://doi .org /10 .1080 /20445911 .2024 .2357363.

cations in multimodal deep learning. ArXiv. https://doi .org /10 .48550 /arXiv .2202 . 09195 . Tack, A., & Piech, C. (2022). The ai teacher test: Measuring the pedagogical ability of

blender and gpt-3 in educational dialogues, arXiv :2205 .07540 [abs]. https://doi .org / 10 .48550 /arXiv .2205 .07540. Touretzky, D. S., Gardner-Mccune, C., Martin, F. G., & Seehorn, D. W. (2019). Envisioning

ai for k-12: What should every child know about ai? In AAAI conference on artiﬁcial intelligence. UNESCO (2021). K-12 ai curricula: A mapping of government-endorsed ai curricula.

https://unesdoc .unesco .org /ark :/48223 /pf0000380602. (Accessed 10 May 2024). Vartiainen, H., Toivonen, T., Jormanainen, I., Kahila, J., Tedre, M., & Valtonen, T.

(2021). Machine learning for middle schoolers: Learning through data-driven design. International Journal of Child-Computer Interaction, 29, Article 100281. https:// doi .org /10 .1016 /j .ijcci .2021 .100281. Wang, N., & Lester, J. (2023). K-12 education in the age of ai: A call to action for k-

12 ai literacy. Journal of Artiﬁcial Intelligence in Education, 332, 228–232. https:// doi .org /10 .1007 /s40593 -023 -00358 -x. Wang, R., & Demszky, D. (2023). Is chatgpt a good teacher coach? Measuring zero-shot

performance for scoring and providing actionable insights on classroom instruction (pp. 626–667). Association for Computational Linguistics. Wang, T., & Cheng, E. C. K. (2021). An investigation of barriers to Hong Kong k-12 schools

incorporating artiﬁcial intelligence in education. Computers and Education: Artiﬁcial Intelligence, 2, Article 100031. https://doi .org /10 .1016 /j .caeai .2021 .100031. Whitehill, J., & LoCasale-Crouch, J. (2024). Automated evaluation of classroom instruc-

tional support with llms and bows: Connecting global predictions to speciﬁc feedback. Journal of Educational Data Mining, 161, 34–60. https://doi .org /10 .5281 /zenodo . 10974824. Wisner, K., Kim, S., Meek, P. M., Tarasenko, L. M., Weston, M. J., & O’Grady, T. P. (2024).

Test–retest reliability of the verran professional governance scale©. Journal of Nursing Measurement. https://doi .org /10 .1891 /JNM -2023 -0110. Xiao, C., Xu, S. X., Zhang, K., Wang, Y., & Xia, L. (2023). Evaluating reading comprehen-

sion exercises generated by llms: A showcase of chatgpt in education applications. In Workshop on innovative use of NLP for building educational applications. Xiao, W., & Song, T. (2021). Current situation of artiﬁcial intelligence education in pri-

mary and secondary schools in China. Retracted on September 15. In 2021 the sixth international conference on information management and technology (pp. 1–4). Yim, I. H. Y., & Su, J. (2024). Artiﬁcial intelligence (ai) learning tools in k-12 education:

A scoping review. Journal of Computers in Education, 1(39). https://doi .org /10 .1007 / s40692 -023 -00304 -9. Yue, M., Jong, M. S.-Y., & Dai, Y. (2022). Pedagogical design of k-12 artiﬁcial intelli-

gence education: A systematic review. Sustainability, 1423. https://doi .org /10 .3390 / su142315620.