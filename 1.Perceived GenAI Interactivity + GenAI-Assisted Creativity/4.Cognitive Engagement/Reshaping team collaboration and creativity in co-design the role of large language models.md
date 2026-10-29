ISSN: 1571-0882 (Print) 1745-3755 (Online) Journal homepage: www.tandfonline.com/journals/ncdn20

Reshaping team collaboration and creativity in codesign: the role of large language models

Deyin Zhang, Jianan Shen, Shijian Luo, Xiyuan Zhang & Wei Liu

To cite this article: Deyin Zhang, Jianan Shen, Shijian Luo, Xiyuan Zhang & Wei Liu (06 Mar 2026): Reshaping team collaboration and creativity in co-design: the role of large language models, CoDesign, DOI: 10.1080/15710882.2026.2641141

To link to this article:  https://doi.org/10.1080/15710882.2026.2641141

Published online: 06 Mar 2026.

Submit your article to this journal

Article views: 414

View related articles

View Crossmark data

Citing articles: 1 View citing articles

Reshaping team collaboration and creativity in co-design: the role of large language models

Deyin Zhanga,b, Jianan Shena, Shijian Luoa, Xiyuan Zhanga and Wei Liub

aCollege of Computer Science and Technology, Zhejiang University, Hangzhou, China; bDepartment of Engineering, King’s College London, London, UK

ABSTRACT Large Language Models (LLMs) are increasingly integrated into codesign practices, yet their impact on collaboration structure, cog­ nitive activity, and creativity remains underexplored. This study investigates how LLMs reshape team collaboration and cognitive processes in co-design, focusing on novice designer teams. Drawing on the co-evolution model, we propose a structured ana­ lytical framework that links collaborative cognitive activities with problem-solution structures and transitions. A mixed-methods study (N = 40) combining protocol analysis, self-report scales, and expert evaluation was conducted to investigate LLM-supported codesign. The results show that LLMs accelerate transitions between the problem and solution spaces, increasing the pace of collabora­ tion. LLMs are also associated with fewer segments per space unit, indicating a redistribution of within-space elaboration. LLMs sup­ port information processing and early-stage ideation in the pro­ blem space. However, in the solution space, LLM use is associated with lower engagement in conceptual integration, functional rea­ soning, and decision-making. LLMs enhance outcome novelty and self-perceived creativity, but show limited improvement in out­ come usefulness and in team-level creativity support related to expressiveness, collaboration, and immersion. These findings pro­ vide multi-level insights into how LLMs influence collaboration structure, cognitive activity distribution, and creativity in codesign, informing the targeted development of LLM-based tools for collaborative design innovation.

ARTICLE HISTORY Received 10 June 2025 Accepted 27 February 2026

KEYWORDS Co-design; large language models; Team-LLM collaboration; co-evolution; creativity

1. Introduction

Design challenges are becoming increasingly complex, and the demand for innovation is rising. In response, co-design has been widely recognised as an effective approach for collective value creation and design innovation (Sanders and Stappers 2008). To balance innovation with feasibility, co-design teams typically iterate between problem identifica­ tion and solution development. This iteration is supported by collective discussion, information integration, and concept evaluation (Lee, Ostwald, and Gu 2020). However, this process depends heavily on designers’ domain knowledge, structured reasoning, and communication skills. For novice designers in particular, limited

CONTACT Shijian Luo sjluo@zju.edu.cn

With the rapid development of generative AI, large language models (LLMs) are increas­ ingly integrated into design practice. LLMs act as external tools that support co-creation, stimulate idea generation, and enhance designers’ expressive capacity through information generation, knowledge organisation, and interactive feedback (Göpfert et al. 2024). Existing research on LLMs in co-design mainly focuses on two areas. First, studies examine how generative capabilities inspire ideas and provide knowledge prompts (Chang and Li 2025; Doshi and Hauser 2024). Second, research investigates how LLM interventions shape the design process, particularly cognitive patterns and process structures (Wadinambiarachchi et al. 2024; Zhou et al. 2025). Although these studies provide initial insights into human-AI collaboration, they largely focus on individual task performance. As a result, team structures, interaction rhythms, and patterns of collaborative cognitive activity remain underexplored.

Co-design is often conceptualised as an iterative and evolving process of co-evolution, in which designers move iteratively between problem framing, hypothesis generation, and meaning construction (Wiltschnig, Christensen, and Ball 2013). The co-evolution model proposed by M. L. Maher and Poon (1996) provides a foundational theoretical framework for understanding how cognitive space shifts within collaboration. This model has been widely applied in early-stage design to explain the structure and evolu­ tion of collaborative exploration (Guo et al. 2024). However, existing research has not sufficiently explored how LLM integration influences cognitive effort among team members and alters the depth of team engagement. Specifically, prior research has emphasised advantages such as enhanced efficiency (Ge et al. 2025), improved informa­ tion integration (Zamfirescu-Pereira et al. 2025), and richer creative output (Petridis, Terry, and Cai 2024). However, the processes through which teams collaborate with LLMs remain insufficiently examined (Gero, Kannengiesser, and Crilly 2022). This study addresses a critical gap by investigating how LLMs reshape the distribution of collabora­ tive cognitive activities, thereby providing new insights into the dynamics of Team-LLM co-design.

Building on the co-evolution perspective, this study conceptualises LLMs not merely as idea-generation aids but as external cognitive catalysts that reshape the internal dynamics of team collaboration. Specifically, we propose a process-based explanatory logic that links LLM use to changes in the co-evolutionary structure of co-design. LLMs are expected to influence the rhythm of transitions between the problem and solution spaces, as well as the depth of cognitive elaboration within each space. Together, these structural shifts redistribute collaborative cognitive activity. Collaborative engagement is expected to shift towards faster, externally oriented processes, including information retrieval and visual attention. In contrast, engagement in deeper integrative processes, such as functional reasoning, evaluative decision-making, and conceptual integration, is expected to decrease.

Drawing on prior research on design cognition and creativity, we outline how these process-level changes may relate to creativity outcomes. Specifically, a faster coevolutionary rhythm characterised by more frequent transitions between the problem and solution spaces is expected to support divergent exploration and be associated with higher novelty. Increased engagement in information retrieval and visual attention further reinforces this effect. In contrast, reduced depth of cognitive elaboration within

We further argue that these process-level changes have downstream consequences for creativity. Accelerated exploration may enhance perceived creativity and outcome novelty. By contrast, reduced cognitive depth may constrain usefulness and sustained team-level co-creativity. Through this framework, collaboration structure, cognitive activity distribution, and creativity outcomes are examined as a unified explanatory chain rather than independent analytical layers.

We adopt a Team-LLM co-design perspective to systematically examine how LLMs influence the structure and rhythm of collaboration, the depth and distribution of cognitive activities, and the translation of these process-level changes into perceived and actual creativity of team outputs. Specifically, it addresses the following research questions:

RQ1. How does LLM integration reshape the structure and rhythm of team collaboration?

RQ2. How does LLM integration influence the depth and distribution of collaborative cognitive activities in co-design teams?

RQ3. How do LLM-related changes in collaboration structure and collaborative cogni­ tion relate to perceived creativity and to the novelty and usefulness of design outcomes?

2. Literature review

2.1. Collaborative conceptual design and the application of LLMs

In the early stages of co-design, design tasks and problem boundaries are often illdefined. Team members must negotiate a shared understanding through information integration and collaboration, gradually developing preliminary design ideas (Gaete Cruz et al. 2023). This process places high demands on cognitive processing, verbal articula­ tion, and coordination skills. For novice designers in particular, limitations in informa­ tion integration and collaborative capabilities often hinder creative advancement (Ahmed, Wallace, and Blessing 2003).

Recently, LLMs have been increasingly adopted in co-design contexts due to their strengths in semantic generation, information synthesis, and structured knowledge representation (L. Chen et al. 2024). Existing studies have demonstrated that LLMs can effectively support problem framing and idea generation, as well as output refinement and knowledge supplementation (Chiarello et al. 2024). Some researchers have further embedded general-purpose LLMs into specific design scenarios by developing custo­ mised generation tools to enhance task relevance. These tools not only expand the scope of ideation but also help streamline design workflows and improve efficiency in creative tasks. For example, X. Chen et al. (2024) proposed a prompt optimisation system that improved both novice and experienced designers’ fluency and flexibility in concept

Existing studies on LLMs in co-design can be broadly grouped into two directions. One focuses on the development and integration of design tools. This includes the optimisation of prompt mechanisms, interface design improvements, and contextual adaptation to enhance model effectiveness for creativity and task execution (J. Zhang and Arawjo 2025). The second direction assesses the effectiveness of LLMs in enhancing codesign outcomes, primarily by evaluating improvements in the novelty, diversity, and efficiency of generated ideas (Göpfert et al. 2024). However, most studies remain con­ centrated on individual-level human-LLM interaction and offer limited understanding of how LLMs reshape team collaboration structure, cognitive pacing, and co-creation patterns (Guo et al. 2024).

As highlighted in (Le Dantec 2010), the cognitive process of design is significantly influenced by surrounding media and environments. Within this context, LLMs have entered co-creation processes not only as knowledge resources, but also as interactive participants that reconfigure how teams share information, construct meaning, and express ideas. This study contributes by systematically examining how LLMs intervene in team-based co-design processes. Specifically, it investigates how LLMs reshape cog­ nitive activity and space structures, and how they influence creativity at three levels: individual perception, team support, and collaborative outcomes.

2.2. Co-evolution model

The co-evolution model conceptualises the design process as a dynamic mechanism characterised by the continuous and reciprocal evolution of the problem space and the solution space (M. L. Maher and Poon 1996). Within this model, the Problem Space (P) and the Solution Space (S) mutually shape each other over time (t), as illustrated in Figure 1. This framework has been widely adopted to analyse how designers, particularly under conditions of uncertainty, reconstruct the relationship between problems and solutions through language, analogy, and external feedback (Dorst 2019).

Subsequent studies have sought to extend the original model. Dorst and Cross (2001) introduced the concepts of the ‘default’ and ‘surprise’ spaces, emphasising that creativity emerges through the recognition of information structures and the recon­ struction of problem-solution pairings. M. Maher and Tang (2003) further proposed a dual-space collaborative search model, articulating the co-evolution process as a two-phase structure comprising ‘problem-driven exploration, solution generation, and revision’. This model was subsequently extended to a behavioural analysis frame­ work applicable to cognitive research. Dorst (2019) argued that co-evolution involves not only forward progression but also an ‘upward jump’ mechanism that starts from the solution space, highlighting how reflective practices in design can trigger problem redefinition and redirect design evolution. Crilly and Moroşanu Firth (2019) expanded the original model by proposing a multi-level perspective on parallel space evolution. This extension broadened the model’s applicability in terms of design

Figure 1. The co-evolution model proposed by M. L. Maher and Poon (1996).

space structure by highlighting that co-evolution can occur simultaneously across different levels of abstraction. It also incorporated cognitive reception and the process of idea acceptance into the model.

Although the co-evolution model has been extensively validated in design cognition research, its application in collaborative contexts remains relatively underexplored. This gap is particularly evident in design teams that include LLM tools. To date, existing empirical research has not yet fully examined how these tools reshape problem-solution space dynamics or reorganise collaborative cognitive and co-evolutionary processes in team-based design. While some studies have touched on multi-level co-evolutionary dynamics, such as (Crilly and Moroşanu Firth 2019), few have combined these perspec­ tives with analyses of collaborative cognitive behaviours through dynamic modelling. As a result, existing research provides limited insight into how changes in co-evolutionary structure are enacted through collaborative cognition in team-based design.

Building upon the work of Crilly and Moroşanu Firth (2019), this study integrates the structural features of problem – solution spaces with the coding of collaborative cognitive activities. It aims to examine whether LLM involvement alters the progression of design spaces and the distribution of cognitive activities during collaboration. This approach seeks to deepen our understanding of how structural and processual dynamics interact within Team-LLM co-design. By linking space-level transitions with the depth and distribution of collaborative cognitive activities, the co-evolution model is operationa­ lised as a process-oriented framework, rather than a purely structural description.

Importantly, movement between problem and solution spaces alone does not guar­ antee creative quality in co-design. Prior research suggests that while outcome novelty may emerge from accelerated exploration, usefulness often depends on sustained cogni­ tive elaboration, functional reasoning, and evaluative decision-making. Understanding the creative implications of co-evolution therefore requires attention to how collabora­ tive cognitive activities are distributed and enacted within and across design spaces. This study addresses this issue by analytically linking co-evolutionary structure with colla­ borative cognitive activity patterns to explain variations in creative processes and outcomes.

2.3. Creativity assessment

Creativity, as a core capability in co-design research, is commonly defined as the potential to generate ideas that are both novel and useful (Jagtap 2019). It is not solely derived from individual abilities but is also shaped by task context, motivational factors, and social interactions (Hay et al. 2020; Y. S. Kim, Jin, and Lee 2011). Creative performance is inherently multidimensional. It encompasses originality, usefulness, and aesthetic quality (Christensen and Ball 2016; Oman et al. 2013), as well as divergent thinking indicators such as fluency, flexibility, and variety (Shah, Smith, and Vargas-Hernandez 2003). Existing research generally distinguishes between two complementary approaches to creativity assessment. One approach is outcome-oriented, focusing on the novelty and feasibility of design solutions and emphasising objective evaluation of outputs (Keshwani et al. 2017). The other is process-oriented and attends to designers’ self-perception and emotional experience during idea generation (Silvia et al. 2012).

Assessing collaborative creativity in design contexts is inherently complex. To address this complexity, researchers have proposed a range of tools targeting both individual and team dimensions of creativity. These include self-report measures of personal creative perception, instruments for gauging perceived team support, and expert evaluations of design outcomes. For instance, self-report instruments such as the Short Scale of Creative Self (SSCS) are commonly used to capture designers’ perceived creativity during task engagement (Zielińska, Lebuda, and Karwowski 2022). The Creativity Support Index (CSI), although originally developed for human-computer interaction, has been used to assess external system support in co-design contexts such as ideation, exploration, and expression (Cherry and Latulipe 2014). In addition, expert evaluation methods are frequently adopted to assess the originality and feasibility of design outcomes, offering a relatively objective external judgement (Chulvi et al. 2012). Other approaches include the use of design diaries, verbal protocol analysis, and cognitive path tracing to examine the evolution of reasoning processes (Taura et al. 2012). Measures of ideational fluency, such as the Alternative Uses Task, have also been widely used (Gilhooly et al. 2007). Although these tools were not originally developed for co-design, they have provided valuable reference points for the quantitative study of creative activity.

Given that creativity in co-design involves interactions between individual perception, team processes, and final outcomes, no single measurement approach is sufficient to capture the overall impact of LLMs on creativity. Therefore, this study adopts a multi-level evaluation framework that integrates three complemen­ tary methods: (1) The SSCS to assess individual perceived creativity, capturing the designers’ subjective belief in their own creative potential; (2) The CSI to measure the perceived creative support at the team level, which evaluates how LLMs aid team members in aspects like collaboration, expression, and exploration; (3) Expert ratings to evaluate the novelty and usefulness of the final outcomes. This integrated framework systematically identifies creativity-related changes following

3. Methods

To empirically examine the proposed process-based explanatory logic, this study adopted a quasi-experimental design. The design focused on a linked sequence of structural, cognitive, and creative changes induced by LLMs. The methodological strategy com­ prised three analytical layers. First, the co-evolutionary structure was quantified to capture differences in collaboration rhythm and in the depth of within-space cognitive elaboration. This structural analysis provided the foundation for the subsequent process investigation. Second, collaborative cognitive activities were coded to examine how changes in co-evolutionary structure were reflected in the redistribution of cognitive effort across the problem and solution spaces (RQ2). Finally, creativity was assessed at individual, team, and outcome levels to evaluate the downstream creative consequences of these process-level dynamics (RQ3).

To examine the impact of LLMs on collaboration structure and cognitive activities (RQ1 & RQ2), we conducted a quasi-experiment with 40 participants. Cross-coding was used to link problem – solution structures with cognitive activities. For creativity (RQ3), two perception scales and expert ratings were used to assess outcome creativity.

3.1. Participants

Forty design students (16 male, 24 female) from two universities participated, including 38 undergraduates and 2 first-year master’s students. Their average age was 21.13 (SD = 0.72), with an average of 2.75 years (SD = 0.78) of design education, qualifying them as novice designers (Dreyfus and Dreyfus 2005).

Participants were recruited through an online forum, and participation was voluntary. This recruitment approach constitutes a form of convenience sampling commonly used in exploratory design research. Participants received a small monetary compensation of £6 in recognition of their time.

All participants reported at least three months of regular experience using LLM tools in design activities, including their use as auxiliary tools for design-related tasks. All participants provided informed consent prior to participation.

3.2. Experimental design and procedures

Participants formed 20 two-person teams (Team 1 to 20), each completing a 90-minute co-design task to develop an innovative product for children. The task focused on proposing a conceptual product design rather than a fully developed technical solution. The task was open-ended, enabling teams to negotiate the product direction, user needs, and design solutions. Participants were required to collaboratively define target users, usage scenarios, and core functions, while articulating the rationale behind their design decisions. Participants were not explicitly informed that the study focused on creativity, nor were they instructed to maximise creativity or originality. Instead, the task was

Teams were encouraged to consider various aspects of early-stage product design at a conceptual level, such as potential usage contexts, existing or competing products, functional value for children, long-term use, and safety considerations. In addition, design-related aspects, including form, material, cost, and contextual appropriateness across different usage settings, were presented as design considerations. These considera­ tions were provided solely as pre-task prompts to support reflection and discussion, rather than as requirements that needed to be explicitly addressed or completed during the task.

The expected outputs for each team included a complete design proposal presented through a combination of design sketches and explanatory text, detailing all final design conclusions and necessary product details.

Teams 1 to 10 (control group) were not permitted to use any internet-connected devices. Teams 11 to 20 (experimental group) used laptops with ChatGPT-4 and were instructed to integrate it consistently throughout the co-design process. Participants in the experimental group were informed that they were free to use the LLM as part of the task. No structured guidance was provided regarding when, how, or for what purposes the LLM should be used, and no constraints were imposed on the number, type, or content of prompts. All participants had prior experience using LLMs, which was confirmed during recruitment, ensuring a basic level of familiarity and competence. Accordingly, participants did not receive any additional training or instruction on LLM usage or prompt formulation prior to or during the experiment. This design choice was intended to capture participants’ autonomous and naturalistic use of LLMs in co-design contexts, reflecting typical adoption patterns in everyday design practice.

For the experimental group, LLM access was available throughout the session, and teams were free to decide when to consult the model and how to interleave LLM querying with direct team discussion during collaboration. Both collaborators were permitted to interact with the LLM. Participants were instructed to share the content of their inter­ actions with the model, including the questions posed and responses received, with their teammate as part of the ongoing design discussion. This approach embedded LLM use within the collaborative workflow, rather than positioning it as an isolated or individual activity. All interactions with the LLMs were recorded for replicability and analysis.

Each team was provided with pen-and-paper materials to support the production of design sketches during the session. All participants were trained in the think-aloud method prior to the task and were instructed to continuously verbalise their thoughts, reasoning, and design intentions throughout the co-design process. All participants demonstrated an adequate understanding of the think-aloud procedure and were able to verbalise their thinking continuously during the task. The resulting verbal protocols were transcribed and served as the primary qualitative data for the protocol coding and analysis described in Section 3.3. Figure 2 shows the experimental scenario.

3.3. Protocol coding scheme

3.3.1. Coding the collaborative space structure In this study, each collaborative design session conducted by a two-person team was treated as one protocol for coding and analysis. Drawing on the co-evolutionary model,

Figure 2. The experimental scenario.

this study developed a coding framework to analyse the structure of the co-design space. Each conversational turn was treated as the basic unit of annotation and categorised as either a Problem or a Solution Space Segment. Segments related to problem definition, needs analysis, or user assumptions were coded as problem space. Segments involving idea generation, solution refinement, or discussion of visual or functional features were generally coded as solution space. However, when idea generation was oriented towards reframing the design problem, exploring user needs, or questioning underlying assump­ tions, such segments were coded as problem space. When a turn addressed both problem framing and early ideation, the dominant semantic intent guided categorisation. Ambiguous cases were resolved through double-coding and consensus among coders.

The study then constructed a sequential structure of the co-design space. Adjacent segments of the same type that formed semantically coherent and task-relevant discourse were merged into a Space Unit, representing a complete episode of either problem exploration or solution development.

In this coding approach, each conversational turn is coded as a space segment within either the problem or solution space. Consecutive segments that remain within the same space are aggregated into a single space unit, representing a continuous episode of problem exploration or solution development. A new space unit is initiated only when the discussion shifts between problem and solution spaces. For example, several succes­ sive turns clarifying user needs are coded as individual problem space segments but together form one problem space unit, whereas a subsequent turn proposing a design idea initiates a new solution space unit. In this way, space segments capture fine-grained conversational actions, while space units define the boundaries of sustained engagement within a design space and provide the basis for analysing space transitions and withinspace elaboration.

Figure 3 illustrates an example of space-based coding grounded in the co-evolution model. The collaboration began in the problem space with a discussion on children’s cooperation (P1), followed by associative exploration (P2). The interaction then shifted to the solution space, where the team proposed a sequence of ideas: shape-matching puzzles (S1), story progression through shape-matching interactions (S2), animal sounds

Figure 3. An example of space-based coding.

and grooves (S3), a physical storybook (S4), and integrating magnets and NFC technol­ ogy (S5). The dialogue returned to the problem space for technical consultation on hardware feasibility (P3-P6), which led to a built-in speaker proposal (S6). Finally, the team revisited the problem space to recall experiences with children’s toys (P7-P9), inspiring the concept of a storybook series (S7).

Based on this structure, seven indicators were extracted across the problem and solution spaces to quantify collaboration rhythm and within-space elaboration (cf. Table 1).

All coding was manually conducted by two researchers using transcriptions of the experimental sessions. NVivo 14 and Excel were used for data management and analysis. Inter-rater reliability was assessed through a cross-coding trial on 10% of the data prior to formal coding. The Cohen’s Kappa coefficient for space structure coding reached 0.724, indicating substantial agreement. Discrepancies were resolved through discussion to ensure a unified coding scheme.

3.3.2. Collaborative cognitive activities To identify typical cognitive activities in co-design, this study developed a coding frame­ work for collaborative cognitive activities grounded in the cognitive classification frame­ work proposed in Hay et al. (2017). This framework synthesised six major types of cognitive processes based on 47 protocol studies. While originally developed for indivi­ dual designers, the taxonomy provides a robust foundation for collaborative analysis.

To better suit the co-design context, the categories were refined based on the char­ acteristics of team interactions. The final coding scheme included nine categories:

Dimension Indicator Operational Definition Space Structure

problem space unit

Indicator

count

problem space segments solution space unit

count

solution space segments transition count Number of transitions between problem and solution spaces Internal Elaboration

problem space

Indicator

segment count

solution space

segment count

problem segments per

unit

problem space units. solution segments per

unit

3.4. Multidimensional evaluation of creativity

Number of problem space units formed by merging consecutive

Number of solution space units formed by merging consecutive

Number of utterances labelled as problem space segments

Number of utterances labelled as solution space segments

Number of problem space segments divided by the number of

Number of solution space segments divided by the number of

solution space units.

Information Retrieval (IR), Semantic Interpretation and Association (SI), Visual Attention (VA), Mental Imagery Generation and Maintenance (MI), Problem Structuring (PS), Evaluation or Decision-Making (ED), Functional Reasoning (FR), Concept Generation and Synthesis (CG), and Creative Output-Level Reasoning (CR), as shown in Table 2. The framework exhibited clear semantic boundaries and strong inter-coder reliability across repeated trials.

Prior to formal coding, the first two authors independently annotated 10% of the dataset using transcripts and audio. Inter-coder reliability was satisfactory (Cohen’s Kappa = 0.645), and discrepancies were resolved through discussion.

To evaluate the impact of LLM intervention on creativity, a multidimensional assessment strategy was adopted across three levels: individual perception, team-level creativity support, and the outcome quality. First, the SSCS (Zielińska, Lebuda, and Karwowski 2022) was employed to assess participants’ self-perceived creativity, which consists of two subscales: Creative Self-Efficacy (CSE) and Creative Personal Identity (CPI). Each item was rated on a five-point Likert scale, and average scores of CSE and CPI were used to indicate perceived creative potential.

Second, team-level creativity support during collaboration was assessed using the CSI (Cherry and Latulipe 2014). The scale includes six dimensions: Collaboration, Enjoyment, Exploration, Expressiveness, Immersion, and Result Worth Effort. Each dimension contains two items rated on a 1–10 Likert scale. Participants also rankordered the relative importance of each dimension in paired comparisons. A weighted composite score from 1 to 100 was calculated to reflect overall system support for creativity.

The CSI, originally developed to assess perceived creativity support from interactive systems, was adapted in this study to capture creativity support at the team level. Participants evaluated the extent to which the LLM supported their team’s collaborative creativity during the co-design task, with reference to joint activity and shared outcomes rather than individual experience alone. The scale was selected for its suitability in assessing tool-mediated creativity support in collaborative contexts, rather than internal team processes or stable team characteristics.

Category Coding Description Example Information

IR Accessing or recalling information

Retrieval

to support ongoing design cognition.

SI Making sense of information and

Interpretation and Association

establishing conceptual associations.

Visual Attention VA Focusing on visual features or

spatial relations of design elements.

Mental Imagery

MI Forming, maintaining, or

Generation and Maintenance

modifying mental representations during the process.

Problem

PS Defining, decomposing, or

Structuring

reframing the problem to clarify constraints and goals.

Evaluation or

ED Assessing options and making

Decision-making

choices aligned with design objectives.

Functional

FR Reasoning about functions,

Reasoning

mechanisms, and causality to ensure feasibility.

bottom to help launch the dart, then it can rotate and brace against the edge of the wall opening”. Concept

CG Proposing and integrating

Generation and Synthesis

solution ideas into more coherent concepts.

Creative Output-

CR Judging the novelty,

level Reasoning

distinctiveness, and expressive quality of outcomes.

3.5. Data analysis and statistical procedures

“Children nowadays are different from before, and

boys are more likely to play with building block models”. Semantic

“For example, TikTok is like this — it’s kind of like

a flat surface, and there’s a hole right here”.

“Yep, and each of the rectangles is rounded (at the

corners.)”

“What I’m imagining is something bigger, like an

interactive setup you can use on the street — kind of like a public monitoring thing”.

“Underneath is a chassis, but how do you charge

it?”

“Well, I think this one should be able to go deeper.

And it feels more tangible”.

“Right, and then we can also add a small rod at the

“So can we develop a rotary pen?”

“What else can we try? Maybe a scene where the

bird is holding something, and use this as the background”.

In addition, three experts with over ten years of design experience independently conducted blind evaluations of all design outcomes. The experts were not informed of the specific research hypotheses, the role of LLMs in the study, or the experimental condition from which each design outcome originated. All artefacts were anonymised prior to evaluation to minimise potential expectancy effects and condition-related bias. Each outcome was rated on novelty and usefulness using a five-point scale. Novelty and usefulness were selected as evaluation criteria because they represent two core and widely accepted dimensions of creativity in design research, capturing respectively the origin­ ality of ideas and their functional and practical value (Ranjan, Siddharth, and Chakrabarti 2018; Runco and Jaeger 2012; Sarkar and Chakrabarti 2011). The average of the two scores represented the objective creativity score for each team. Correlation coefficients of 0.720 (novelty) and 0.761 (usefulness) indicated good inter-rater reliability (p < .001).

All protocol data were analysed at the team level. Each team constituted one analytical unit, based on a single collaborative design session. To address the three research questions, different statistical analyses were applied to co-evolutionary structure indica­ tors, collaborative cognitive activities, and creativity-related measures.

For co-evolutionary structure indicators (RQ1), including the number of problem and solution space units, transition counts, segment counts, and average segments per unit, descriptive statistics were first computed at the team level. As all indicators met

For collaborative cognitive activities (RQ2), frequencies of coded cognitive activity categories were analysed at the team level. Non-parametric Mann-Whitney U tests were employed to examine group differences in overall cognitive activity distributions as well as space-specific frequencies within the problem and solution spaces.

For creativity-related measures (RQ3), statistical analyses were conducted according to the measurement level and distributional properties of each measure. Self-perceived creativity scores from the SSCS were analysed using Mann-Whitney U tests for overall scores and independent samples t-tests for subscale comparisons. Perceived team-level creativity support measured by the CSI was analysed using an independent samples t-test for the overall score, followed by a multivariate analysis of variance to examine group differences across the six CSI subdimensions. Expert ratings of design outcomes on novelty and usefulness were analysed using independent samples t-tests.

Statistical analyses were conducted using SPSS (Version 29.0.1.0), with significance levels set at p < 0.05.

4. Results

4.1. Structural shifts in problem-solution transitions

All structural indicators were computed at the team level, with each of the 20 teams constituting one analytical unit. To examine how LLMs influence the structural characteristics of co-evolution, we compared the LLM-supported and non-LLM-supported groups across four indicators: the number of problemand solution-space units, the number of space transitions, the number of problemand solution-space segments, and the average number of segments per unit (cf. Figure 4). All indicators met the assumptions for independent samples t-tests.

4.1.1. Shifts in the structure of co-evolutionary design space The LLMs group exhibited significantly more space units in both the problem space (M = 21.40, SD = 2.41) and solution space (M = 21.30, SD = 2.26) than the non-LLMs group (problem space: M = 15.80, SD = 1.87; solution space: M = 15.40, SD = 1.84), p < .001, Cohen’s d = 2.16 and 2.06. The number of space transitions was also signifi­ cantly higher for the LLMs group (M = 41.70, SD = 4.64) compared to the non-LLMs group (M = 30.20, SD = 3.68), p < .001, Cohen’s d = 4.19. These findings suggest that the introduction of LLMs substantially accelerated the collaborative rhythm between pro­ blem and solution spaces.

However, the average number of segments per unit was significantly lower in the LLMs group for both problem (M = 3.68, SD = 0.34) and solution space (M = 4.23, SD = 0.46), compared to the non-LLMs group (problem space: M = 4.98, SD = 0.50; solution space: M = 5.69, SD = 0.82), p < .001, Cohen’s d = 0.43 and 0.67. This pattern indicates reduced withinspace verbal elaboration, as reflected by fewer segments per space unit, following LLMs intervention.

Figure 4. Comparison of co-evolutionary space structures in LLMs and non-LLMs groups. *Note: ***p < .001. Error bars represent standard deviations (SD), and bars indicate mean values.

Overall, these findings reveal a distinct shift in co-evolutionary structure. LLM-supported teams transitioned more frequently between design spaces at the unit level but showed less sustained within-space verbal elaboration, as indicated by fewer segments per space unit.

4.1.2. Distribution of collaboration between problem and solution spaces To examine whether LLM use affected the collaborative emphasis between problem and solution spaces, we analysed the proportion of coded segments assigned to each space. The LLMs group showed a problem-space proportion of 46.70% (M = 0.47, SD = 0.038), while the non-LLMs group showed 47.45% (M = 0.48, SD = 0.057). This difference was not statistically significant (p = .734, Cohen’s d = 0.05).

Since the two space proportions are complementary and sum to one, only the problem space proportion is reported to avoid redundancy. These findings indicate that, despite increased switching behaviour, the overall distribution of collaborative focus between problem and solution spaces remained comparable across groups.

4.2. Cognitive activity patterns in co-design with and without LLMs

4.2.1. Overall differences in cognitive activities Based on the nine collaborative cognitive activity categories defined in this study, we compared overall activity distributions between LLMs and non-LLMs groups. Due to non-normal distributions in several indicators, Mann-Whitney U tests were used (cf. Table 3).

Significant differences (p < .05) were observed in seven categories. The LLMs group exhibited higher frequencies than the non-LLMs group in IR (M = 41.50 compared to 27.00, p < .001), VA (M = 17.50 compared to 13.90, p = .019), and CR (M = 22.50

Cognitive Activity Non-LLMs Mean LLMs Mean Non-LLMs Median LLMs Median p value IR 27.00 41.50 25.00 40.50 <.001 *** SI 23.10 15.90 22.50 17.00 <.001 *** VA 13.90 17.50 13.00 16.00 .019 * MI 23.20 16.90 23.50 17.00 .005 ** PS 37.30 37.10 36.50 37.00 .912 ED 33.40 27.60 34.00 26.50 .043 * FR 24.40 17.40 24.00 16.50 <.001 *** CG 20.90 20.50 21.00 20.50 .912 CR 17.70 22.50 16.50 21.00 .005 **

Note: *p < .05, **p < .01, ***p < .001.

compared to 17.70, p = .005). These results indicate that LLM support was associated with higher frequencies of information-seeking, visual attention, and creative outputlevel reasoning within teams.

Meanwhile, the LLMs group demonstrated lower frequencies than the non-LLMs group in SI (M = 15.90 compared to 23.10, p < .001), MI (M = 16.90 compared to 23.20, p = .005), ED (M = 27.60 compared to 33.40, p = .043), and FR (M = 17.40 compared to 24.40, p < .001). These findings suggest a lower frequency of several higher-order cognitive processes under LLM support, including semantic interpretation, mental imagery, evaluative decision-making, and functional reasoning.

No significant differences were observed between the two groups in PS and CG (both p = .912). Overall, LLMs intervention significantly reshaped the distribution of cognitive activity categories in the co-design process.

4.2.2. Space-specific shifts in cognitive activity patterns To further examine how LLMs influence collaborative cognitive activities within distinct spaces, we analysed the seven cognitive activity categories that previously showed significant group differences. Frequencies were compared separately in the problem and solution spaces (cf. Figure 5).

Within the problem space, the LLMs group engaged more frequently in IR (p < .001) and VA (p = .018). Conversely, the non-LLMs group exhibited higher frequencies in SI (p < .001), MI (p = .031), and FR (p = .047). No significant differences were observed between the groups for ED and CR.

Within the solution space, the LLMs group exhibited a higher frequency of FR (p = .002). In contrast, the non-LLMs group had higher frequencies in MI (p = .027), ED (p = .021), and CR (p = .027). No significant differences were found between the groups for IR, SI, and VA.

4.3. Effects of LLMs on multi-level creativity

4.3.1. Differences in self-perceived creativity To evaluate the impact of LLMs on novice designers’ self-perceptions of creativity, the SSCS was administered. A Mann-Whitney U test indicated that the LLMs group scored significantly higher than the non-LLMs group in overall SSCS scores (Mean Rank = 25.20 vs. 15.80, U = 106.000, p = .011).

Figure 5. Comparative frequencies of coded collaborative cognitive activity categories across the problem and solution spaces.

Subsequent analysis using an independent samples t-test showed a significant differ­ ence on the CPI subscale (p = .006, Cohen’s d = 0.69), favouring the LLMs group. Although the LLMs group also scored higher on the CSE subscale, the difference was not statistically significant (p = .062, Cohen’s d = 0.75). These findings suggest that LLM integration substantially enhances novice designers’ self-perceived creative potential, particularly in terms of identity-related dimensions of creativity (cf. Figure 6).

4.3.2. Differences in perceived creativity support at the team level To assess the perceived creativity support offered by LLMs at the team level, the study employed the CSI, which includes six subdimensions. An independent-samples t-test showed no significant group difference in overall CSI scores, although the LLMs group had a higher mean (p = .115).

To further investigate specific aspects of team-level creativity support, a multivariate analysis of variance was conducted on the six CSI subdimensions. Results showed a significant overall group difference (p = .023). The LLMs group scored significantly higher in three subdimensions: Enjoyment (p = .018), Exploration (p = .018), and Result Worth Effort (p = .011). No significant differences were found in Expressiveness, Collaboration, or Immersion (p > .05). See Table 4 for details.

Figure 6. Differences in self-perceived creativity by groups. Note: *p < .05, **p < .01. Error bars represent standard deviations (SD), and bars indicate mean values.

Table 4. Comparison of CSI subdimension scores between LLM and non-LLM groups.

CSI Subdimension LLM group (Mean) Non-LLM group (Mean) F value p value Collaboration 7.78 7.68 .752 .391 Enjoyment 8.15 6.75 6.065 .018* Exploration 7.83 6.58 6.135 .018* Expressiveness 7.73 6.95 2.760 .105 Immersion 7.48 7.40 .014 .907 Result Worth Effort 8.03 6.68 7.149 .011*

Note: *p < .05.

4.3.3. Creativity differences in design outcomes To evaluate the creativity of the design outcomes, three expert judges independently rated each team’s output on novelty and usefulness. The mean of the novelty and usefulness scores was used as an overall creativity score (cf. Figure 7).

An independent samples t-test showed that the LLMs group scored significantly higher in overall creativity than the non-LLMs group (p = .013). This difference was driven by higher novelty scores (p = .049), while usefulness did not differ significantly (p = .145).

To further contextualise the quantitative creativity ratings, a set of representative design outcomes was selected for visual illustration. Four design proposals were selected from each of the control and experimental groups to reflect a range of creativity out­ comes observed in the data. The selected examples illustrate different combinations of novelty and usefulness scores, including designs rated highest or lowest on each dimension.

Figure 7. Comparison of expert ratings on novelty and usefulness between the control group (T1-10) and the experimental group (T11-20).

Figure 8 presents these eight representative examples together with their corre­ sponding expert-rated novelty and usefulness scores. The purpose of this visual comparison is to illustrate how different creativity ratings are manifested in the design outcomes, rather than to provide an exhaustive overview of all designs. Fullresolution versions of the selected designs are provided in the Appendix (Figures A1–A8).

5. Discussion

Taken together, the results reveal a coherent process-level pattern in how LLMs reshape team collaboration. Specifically, LLMs alter the co-evolutionary rhythm between the problem and solution spaces and redistribute collaborative cognitive activities. These structural and cogni­ tive shifts help explain the asymmetric effects on creativity: higher perceived creativity and outcome novelty, but limited improvement in usefulness and team-level co-creativity. The following sections discuss these results as interconnected components of a unified explanatory chain, rather than as separate findings.

Figure 8. Representative design outcomes over control group and experimental group. Note: Eight representative design proposals are shown (four from each group), each annotated with average expert-rated novelty and usefulness scores (n = 3).

5.1. Reshaping co-evolution: the structural impact of LLMs

Following the proposed explanatory framework, we first examine how LLMs reshape the structural dynamics of the co-design process. This study finds that LLM integration signifi­ cantly reshapes transition dynamics between the problem and solution spaces during codesign. Compared to the non-LLM group, the LLM group demonstrated a higher frequency of space transitions, reflecting a faster-paced co-evolution. LLMs thus acted as ‘cognitive cata­ lysts’ that accelerated iterative cycles between problem framing and solution development (Guo et al. 2024).

However, the overall distribution between problem and solution spaces remained compar­ able across groups, an aspect that has been seldom highlighted in previous studies. This suggests that the focus of collaboration among novice designers remained primarily shaped by participants’ own cognitive engagement, rather than being restructured by LLMs. LLMs thus function more as external assistive tools (Sabbah and Li 2025), as they accelerate the pace of collaboration without redirecting the primary focus of collaborative engagement. This inter­ pretation is consistent with (Z. Chen and Chan 2024), which underscores that the effectiveness of LLMs hinges on users’ application strategies and individual characteristics. While LLMs offer valuable support for feedback and task execution, they do not supplant designers’ core expertise or decision-making authority.

Although LLMs accelerated space transitions, the LLM-supported teams also exhibited a lower average number of segments per space unit. In this study, this indicator reflects reduced within-space verbal elaboration, which has been interpreted as a proxy for the depth of collaborative cognitive engagement. This pattern may stem from two factors: (1) novice designers, with limited cognitive experience, may passively adopt LLMs’ suggestions without fully refining the design problem (Zhai, Wibowo, and Li 2024); and (2) the instant responsiveness of LLMs may promote a shallow mode of interaction, discouraging deeper

At the same time, the methodological interpretation of this finding requires caution. In LLM-supported collaboration, fewer segments per space unit may reflect not only reduced within-space verbal elaboration, but also a redistribution of elaborative work to the human-LLM interaction. Because LLMs can generate suggestions and reformulations near-instantaneously, exploration and refinement may occur through LLM-mediated interaction rather than extended human-to-human discussion. Accordingly, segmentlevel reductions may capture a shift in the locus of elaboration, rather than a simple reduction in cognitive depth.

In summary, while LLMs enhance the pace of co-evolution, they may compromise cognitive depth and processing accuracy. This highlights a critical challenge: how to leverage the efficiency gains offered by LLMs while maintaining rich, engaged collabora­ tion and safeguarding designers’ cognitive autonomy. Future research should investigate longer-term effects, including potential risks of design fixation, reduced independent thinking, or constrained innovation scope.

5.2. Redistributing cognition: shifts in collaborative cognitive activity

The structural shifts identified in Section 5.1 lead to a corresponding redistribution of collaborative cognitive activities during co-design. The results suggest that LLMs reshaped the cognitive structure of collaboration by shifting the emphasis towards faster, more surface-level processing. Rather than uniformly enhancing all aspects of cognitive activity, LLMs predominantly amplified externally oriented activities, such as informa­ tion retrieval, visual attention, and rapid idea expression, particularly within the problem space. This pattern is directly reflected in the higher frequencies of IR and VA observed in the LLM-supported teams, especially within the problem space (cf. Figure 5). This pattern suggests that LLMs can facilitate early task engagement among novice teams by promoting information flow, enhancing visual focus, and supporting the articulation of initial ideas. Such findings echo results from individual design studies that underscore LLMs’ strengths in supporting conceptual exploration (Ma et al. 2023).

However, LLMs provide limited support for complex cognitive activities that require deep understanding, reasoning, and decision-making, particularly in the solution space. While LLMs can facilitate perceptual processing and language output, they appear insufficient for cognitive processes that depend on deeper thinking and conceptual integration (Z. Zhang, Sun, and An 2025). As a result, LLMs may hinder novice designer teams from engaging in the depth of reasoning and collaborative construction necessary for developing robust design solutions.

Our results further suggest that LLMs’ cognitive contributions were concentrated in the problem space. This conclusion follows from the asymmetric distribution of signifi­ cant effects across the two design spaces. Externally oriented activities increased mainly in the problem space under LLM support, whereas integrative and evaluative activities in the solution space showed no corresponding increase and were sometimes reduced. However, LLM support for logical reasoning and integrative expression in the solution space appears limited. This disparity may stem from the current strengths of LLMs in

In conclusion, this study identifies a rarely reported insight: the impact of LLMs on collaborative cognitive activities exhibits a pronounced structural asymmetry. Their facilita­ tive effects are concentrated in external information processing and rapid expression, parti­ cularly within the problem space, while their limiting influence is more evident in activities requiring complex interpretation, construction, and reasoning, especially in the solution space.

5.3. LLMs and creativity: impacts on perception and outcome quality

Building on the structural and cognitive findings reported above, the structural acceleration and cognitive redistribution observed above help explain the differentiated effects of LLMs on creativity. From a process-oriented perspective, these effects can be understood in terms of how LLMs reshape the balance between exploratory and evaluative activities during teambased co-design (Dorst and Cross 2001). This study shows that LLMs influence creativity across three levels: individual perception, perceived team support, and the quality of design outcomes. While LLMs significantly enhanced novice designers’ self-perceived creativity, particularly by strengthening their sense of creative identity, they showed limited influence on team-level creativity perception. In terms of design outcomes, improvements were observed mainly in novelty rather than practical usefulness.

However, the observed increase in self-perceived creativity appears to stem primarily from direct interactions with LLMs, rather than from their systemic integration into the team’s collaboration. While LLMs facilitated individual ideation and boosted initial engagement by offering immediate cognitive support, their role remained isolated from the team’s broader collaborative processes. This limitation was reflected in the CSI results, where no significant differences were observed in dimensions such as Collaboration, Expressiveness, or Immersion. These findings underscore that LLMs currently function more as personal cognitive assistants than as co-creative agents within teams.

The higher novelty scores observed in the LLMs group can be understood in relation to the structural and cognitive shifts identified in Sections 5.1 and 5.2. Specifically, the accelerated transitions between problem and solution spaces, together with increased engagement in information retrieval and visual attention, suggest a mechanism for broader exploration of the design space Hay et al. (2017). This pattern is consistent with prior research showing that rapid exploration and access to diverse information support divergent thinking and the generation of original ideas (Lee and Ostwald 2022). These effects are particularly evident in early-stage design activities.

At a cognitive level, this pattern reflects an asymmetry between the processes that support novelty and those required for usefulness. Novelty in design is commonly associated with expansive search, associative thinking, and the recombination of heterogeneous information.

In contrast, the limited improvement in usefulness can be understood as a consequence of constraints in later-stage cognitive processes. Prior research suggests that usefulness in design outcomes depends on sustained cognitive elaboration, func­ tional reasoning, and systematic evaluation, which are essential for integrating ideas and assessing their feasibility (Sarkar and Chakrabarti 2011). Consistent with the cognitive activity patterns reported above, the LLM-supported teams exhibited reduced depth of engagement in these complex, integrative activities, particularly in evaluative decisionmaking and functional reasoning. The fast-paced and shallow interaction rhythm pro­ moted by LLM use discouraged critical filtering, structural refinement, and objective feasibility assessment, which are necessary for developing practical value. As a result, improvements in usefulness were not observed.

We believe this asymmetry should not be interpreted as an inherent limitation of LLMs themselves. Rather, it may reflect a mismatch between the cognitive affordances of current LLM-supported interaction and the demands of usefulness-oriented design work. While novelty can emerge from accelerated exploration and externally stimulated idea generation, usefulness often relies on slower, internally coordinated, and socially negotiated processes involving sustained evaluation and functional integration. These processes are less easily externalised to an AI system. Consequently, without deliberate scaffolding for evaluative reasoning and integrative decision-making, LLM use may be more likely to enhance novelty than to support the development of usefulness.

Taken together, these findings suggest that LLMs acted as cognitive catalysts by facilitating early-stage exploration and idea generation (Gibson 2001), thereby enhancing perceived creativity and outcome novelty. At the same time, their limited support for deeper evaluative and integrative processes constrained the development of usefulness and sustained team-level co-creativity.

In design practice, these findings have important implications for designers and managers. LLMs can be effectively leveraged to accelerate early-stage ideation and stimulate creative exploration. However, teams must actively maintain critical engage­ ment and shared evaluative practices to avoid over-reliance on tool-generated content. Targeted training for novice designers in effective human-LLM collaboration may be particularly important, with an emphasis on developing skills to synthesise, evaluate, and refine LLM-generated ideas to ensure both creative originality and practical value.

Finally, while this study is situated within design research, related investigations into LLM-supported team collaboration are also emerging in adjacent domains such as soft­ ware design and development. Although a systematic cross-domain comparison lies beyond the scope of the present work, the conceptual parallels in collaborative dynamics and methodological approaches suggest opportunities for future dialogue across research communities. Engaging with these parallel streams may further enrich understanding of how LLMs reshape team-based creative work in complex problem-solving contexts.

This study focused on short-term co-design sessions and captured the immediate effects of LLM integration on team structure, cognitive activity, and creative output among novice designers. However, it did not capture longer-term dynamics that may emerge with sustained engagement with LLMs. Potential risks such as design fixation, cognitive inertia, or growing dependency on LLMs in co-design contexts remain underexplored. Future research should investigate how LLMs influence co-design processes over extended periods and in more complex design settings.

A second limitation concerns the participant sample. The study involved 40 university students with design backgrounds, offering some relevance to novice-level practice. Nevertheless, the limited sample size, the relative homogeneity of cultural and national backgrounds, and the absence of professional designers may constrain the applicability of the findings. Future studies should examine more diverse populations across varied educational and cultural contexts.

Additionally, this study employed a general-purpose LLM (ChatGPT-4) without finetuning. This decision reflected real-world usage patterns, where novice designers often prefer readily accessible models over task-specific alternatives (Lin et al. 2025). While this decision aligned with how novice designers typically use LLMs in practice, the use of a non-optimised, general-purpose system may have constrained the model’s capacity to support the cognitive demands of complex design challenges.

6. Conclusions

This study demonstrates that LLMs reshape co-design by accelerating transitions between the problem and solution spaces and altering the distribution of collaborative cognitive activities. While LLM-supported teams progressed more rapidly, they engaged in less sustained within-space verbal elaboration. This indicates a shift in how cognitive effort is organised during collaboration. At the cognitive level, LLMs primarily supported externally oriented activities, whereas higher-order integrative processes received more limited support, particularly in the solution space. In terms of creativity, LLMs supported novelty generation and enhanced self-perceived creativity. These effects were particularly evident in designers’ enjoyment, exploratory motivation, and expectations regarding outcomes. Nonetheless, their impact on the usefulness of outcomes and team-level creative support was limited. These findings suggest that designers should collaborate strategically with LLMs, maintaining critical thinking and innovative initiative through­ out the design process to ensure both collaborative efficiency and creative quality.

The study offers three key contributions. First, it validates the co-evolution model adapted to Team-LLM co-design, providing a structured framework to analyse how LLMs reshape team transitions and progression. This provides critical insights into the dynamics of early-stage innovation within hybrid human-AI teams. Second, it proposes a domain-specific coding framework for collaborative cognitive activities. This frame­ work reveals differentiated intervention patterns of LLMs across the problem and solu­ tion spaces and establishes a theoretical foundation for analysing the cognitive processes of collaborative design teams. Third, it integrates self-assessment and expert evaluation to examine how LLMs influence creativity at individual, team, and outcome levels. This

In summary, this research provides empirical evidence on how LLMs reshape team collaboration structure, cognitive activities, and creativity in co-design. It advances understanding of team-LLM collaboration mechanisms and offers practical insights for adapting LLMs to specific design contexts.

Acknowledgements

The authors sincerely thank the anonymous reviewers and the editor for their constructive feedback and insightful suggestions, which significantly improved the quality of this paper. The authors also gratefully acknowledge the participants who contributed their time and expertise to the experiments.

Author contributions

CRediT: Deyin Zhang: Conceptualisation, Methodology, Formal Analysis, Writing & Editing. Jianan Shen: Data Collection, Formal Analysis, Visualisation. Shijian Luo: Conceptualisation, Supervision. Xiyuan Zhang: Data Collection, Visualisation. Wei Liu: Conceptualisation, Writing – Review & Editing.

Disclosure statement

No potential conflict of interest was reported by the author(s).

AI usage disclosure

In accordance with the Taylor & Francis AI Policy, we disclose that OpenAI’s ChatGPT-4o was used exclusively for the purpose of language refinement. All outputs generated by the tool were critically evaluated and edited under the close supervision and full responsibility of the first author.

Data availability statement

The data supporting the findings of this study are available from the corresponding author upon reasonable request. Due to privacy or ethical restrictions, full transcripts and participant-level records are not publicly shared.

Ethical statement

All participants provided informed consent prior to participation. The study was conducted in accordance with institutional ethical guidelines for research involving human subjects. No per­ sonally identifiable information was collected, and all data were anonymised prior to analysis.

References

Ahmed, S., K. Wallace, and L. Blessing. 2003. “Understanding the Differences Between How

Novice and Experienced Designers Approach Design Tasks.” Research in Engineering Design 14 (1): 1–11. https://doi.org/10.1007/s00163-002-0023-z  .

Brainstorming for Triggering Creative Thoughts.” Thinking Skills and Creativity 56:101755. https://doi.org/10.1016/j.tsc.2025.101755  . Chen, L., H. Zuo, Z. Cai, Y. Yin, Y. Zhang, L. Sun, P. Childs, and B. Wang. 2024. “Toward

Controllable Generative Design: A Conceptual Design Generation Approach Leveraging the Function–Behavior–Structure Ontology and Large Language Models.” Journal of Mechanical Design 146 (121401). https://doi.org/10.1115/1.4065562  . Chen, X., Z. Ma, X. Jiang, Y. Jian, X. Yao, and P. Wu. 2024. “Lumos: AI-Driven Prompt

Optimisation Tool for Assisting Conceptual Design.” Journal of Engineering Design 35 (12): 1597–1623. https://doi.org/10.1080/09544828.2024.2396195  . Chen, Z., and J. Chan. 2024. “Large Language Model in Creative Work: The Role of Collaboration

Modality and User Expertise.” Management Science 70 (12): 9101–9117. https://doi.org/10. 1287/mnsc.2023.03014  . Cherry, E., and C. Latulipe. 2014. “Quantifying the Creativity Support of Digital Tools Through

the Creativity Support Index.” ACM Transactions on Computer-Human Interaction 21 (4): 1–25. https://doi.org/10.1145/2617588  . Chiarello, F., S. Barandoni, M. M. Škec, and G. Fantoni. 2024. “Generative Large Language Models

in Engineering Design: Opportunities and Challenges.” Proceedings of the Design Society 4:1959–1968. https://doi.org/10.1017/pds.2024.198  . Christensen, B. T., and L. J. Ball. 2016. “Dimensions of Creative Evaluation: Distinct Design and

Reasoning Strategies for Aesthetic, Functional and Originality Judgments.” Design Studies 45:116–136. https://doi.org/10.1016/j.destud.2015.12.005  . Chulvi, V., E. Mulet, A. Chakrabarti, B. López-Mesa, and C. González-Cruz. 2012. “Comparison of

the Degree of Creativity in the Design Outcomes Using Different Design Methods.” Journal of Engineering Design 23 (4): 241–269. https://doi.org/10.1080/09544828.2011.624501  . Crilly, N., and R. Moroşanu Firth. 2019. “Creativity and Fixation in the Real World: Three Case

Studies of Invention, Design and Innovation.” Design Studies 64:169–212. https://doi.org/10. 1016/j.destud.2019.07.003  . Dorst, K. 2019. “Co-Evolution and Emergence in Design.” Design Studies 65:60–77. https://doi.

org/10.1016/j.destud.2019.10.005  . Dorst, K., and N. Cross. 2001. “Creativity in the Design Process: Co-Evolution of Problem–

Solution.” Design Studies 22 (5): 425–437. https://doi.org/10.1016/S0142-694X(01)00009-6  . Doshi, A. R., and O. P. Hauser. 2024. “Generative AI Enhances Individual Creativity but Reduces

the Collective Diversity of Novel Content.” Science Advances 10 (28): eadn5290. https://doi.org/ 10.1126/sciadv.adn5290  . Dreyfus, H. L., and S. E. Dreyfus. 2005. “Peripheral Vision: Expertise in Real World Contexts.”

Organization Studies 26 (5): 779–792. https://doi.org/10.1177/0170840605053102  . Duan, R., N. Karthik, J. Shi, R. Jain, M. C. Yang, and K. Ramani. 2024. ConceptVis: Generating and

Exploring Design Concepts for Early-Stage Ideation Using Large Language Model. ASME 2024 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference, Washington, DC, USA, November 13. https://doi.org/10.1115/ DETC2024-146409  . Gaete Cruz, M., A. Ersoy, D. Czischke, and E. van Bueren. 2023. “Towards a Framework for Urban

Landscape Co-Design: Linking the Participation Ladder and the Design Cycle.” Codesign 19 (3): 233–252. https://doi.org/10.1080/15710882.2022.2123928  . Ge, S., Y. Sun, Y. Cui, and D. Wei. 2025. “An Innovative Solution to Design Problems: Applying

the Chain-of-Thought Technique to Integrate LLM-Based Agents with Concept Generation Methods.” IEEE Access 13:10499–10512. https://doi.org/10.1109/ACCESS.2024.3494054  . Gero, J. S., U. Kannengiesser, and N. Crilly. 2022. “Abstracting and Formalising the Design

Co-Evolution Model.” Design Science 8:e14. https://doi.org/10.1017/dsj.2022.10  . Gibson, C. B. 2001. “From Knowledge Accumulation to Accommodation: Cycles of Collective

Cognition in Work Groups.” Journal of Organizational Behavior 22 (2): 121–134. https://doi. org/10.1002/job.84  .

and Executive Involvement in Generating Novel Uses for Familiar Objects.” British Journal of Psychology 98 (4): 611–625. https://doi.org/10.1111/j.2044-8295.2007.tb00467.x  . Göpfert, J., J. M. Weinand, P. Kuckertz, and D. Stolten. 2024. “Opportunities for Large Language

Models and Discourse in Engineering Design.” Energy and AI 17:100383. https://doi.org/10. 1016/j.egyai.2024.100383  . Guo, J., Y. Yin, L. Sun, and L. Chen. 2024. “Empirical Study of Problem-Solution Co-Evolution in

Human-GAI Collaborative Conceptual Design. DRS2024. June 16. https://dl.designresearchso ciety.org/drs-conference-papers/drs2024/researchpapers/306/ . Hay, L., A. H. B. Duffy, M. Grealy, M. Tahsiri, C. McTeague, and T. Vuletic. 2020. “A Novel

Systematic Approach for Analysing Exploratory Design Ideation.” Journal of Engineering Design 31 (3): 127–149. https://doi.org/10.1080/09544828.2019.1662381  . Hay, L., A. H. B. Duffy, C. McTeague, L. M. Pidgeon, T. Vuletic, and M. Grealy. 2017. “Towards

a Shared Ontology: A Generic Classification of Cognitive Processes in Conceptual Design.” Design Science 3:e7. https://doi.org/10.1017/dsj.2017.6  . Jagtap, S. 2019. “Design Creativity: Refined Method for Novelty Assessment.” International

Journal of Design Creativity & Innovation 7 (1–2): 99–115. https://doi.org/10.1080/21650349. 2018.1463176  . Keshwani, S., T. A. Lenau, S. Ahmed-Kristensen, and A. Chakrabarti. 2017. “Comparing Novelty

of Designs from Biological-Inspiration with Those from Brainstorming.” Journal of Engineering Design 28 (10–12): 654–680. https://doi.org/10.1080/09544828.2017.1393504  . Kim, J., and H. Ryu. 2014. “A Design Thinking Rationality Framework: Framing and Solving

Design Problems in Early Concept Generation.” Human–Computer Interaction 29 (5–6): 516–553. https://doi.org/10.1080/07370024.2014.896706  . Kim, Y. S., S. T. Jin, and S. W. Lee. 2011. “Relations Between Design Activities and Personal

Creativity Modes.” Journal of Engineering Design 22 (4): 235–257. https://doi.org/10.1080/ 09544820903272867  . Le Dantec, C. A. 2010. “Situating Design as Social Creation and Cultural Cognition.” Codesign

6 (4): 207–224. https://doi.org/10.1080/15710882.2010.527009  . Lee, J. H., and M. J. Ostwald. 2022. “The Relationship Between Divergent Thinking and Ideation in

the Conceptual Design Process.” Design Studies 79:101089. https://doi.org/10.1016/j.destud. 2022.101089  . Lee, J. H., M. J. Ostwald, and N. Gu. 2020. “Collaborative Design: Team Cognition and

Communication.” In Design Thinking: Creativity, Collaboration and Culture, edited by J. H. Lee, M. J. Ostwald, and N. Gu, 113–145. Springer International Publishing. https://doi. org/10.1007/978-3-030-56558-9_5  . Lin, X., H. Huang, K. Huang, X. Shu, and J. Vines. 2025. “Seeking Inspiration through

Human-LLM Interaction.” In Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems, edited by N. Yamashita, V. Evers, and K. Yatani, 1–17. New York, NY: Association for Computing Machinery. https://doi.org/10.1145/3706598.3713259  . Ma, K., D. Grandi, C. McComb, and K. Goucher-Lambert. 2023. “Conceptual Design Generation

Using Large Language Models.” In Volume 6: 35th International Conference on Design Theory and Methodology (DTM). New York, NY, USA: American Society of Mechanical Engineers. https://doi.org/10.1115/DETC2023-116838  . Maher, M. L., and J. Poon. 1996. “Modeling Design Exploration as Co-Evolution.” Computer-

Aided Civil and Infrastructure Engineering 11 (3): 195–209. https://doi.org/10.1111/j.1467-8667. 1996.tb00323.x  . Maher, M., and H.-H. Tang. 2003. “Co-Evolution as a Computational and Cognitive Model of

Design.” Research in Engineering Design 14 (1): 47–64. https://doi.org/10.1007/s00163-002- 0016-y  . Oman, S. K., I. Y. Tumer, K. Wood, and C. Seepersad. 2013. “A Comparison of Creativity and

Innovation Metrics and Sample Validation through In-Class Design Projects.” Research in Engineering Design 24 (1): 65–92. https://doi.org/10.1007/s00163-012-0138-9  .

Design Impacts Designers’ Workflows.” In Proceedings of the 2024 ACM Designing Interactive Systems Conference, edited by A. Vallgårda, L. Jönsson, and J. Fritsch, 743–756. New York, NY: Association for Computing Machinery. https://doi.org/10.1145/3643834.3661613  . Ranjan, B. S. C., L. Siddharth, and A. Chakrabarti. 2018. “A Systematic Approach to Assessing

Novelty, Requirement Satisfaction, and Creativity.” AI EDAM 32 (4): 390–414. https://doi.org/ 10.1017/S0890060418000148  . Runco, M. A., and G. J. Jaeger. 2012. “The Standard Definition of Creativity.” Creativity Research

Journal 24 (1): 92–96. https://doi.org/10.1080/10400419.2012.650092  . Sabbah, J., and F. Li. 2025. “When Humans and Large Language Models Collaborate,

Problem-Finding Illuminates.” Innovation: Organization and Management. Scopus: 1–34. https://doi.org/10.1080/14479338.2025.2504428  . Sanders, E. B.-N., and P. J. Stappers. 2008. “Co-Creation and the New Landscapes of Design.”

Codesign 4 (1): 5–18. https://doi.org/10.1080/15710880701875068  . Santiago, C. S. Jr., S. I. Embang, R. B. Acanto, K. W. P. Ambojia, M. D. B. Aperocho, B. B. Balilo,

E. L. Cahapin, et al. 2023. “Utilization of Writing Assistance Tools in Research in Selected Higher Learning Institutions in the Philippines: A Text Mining Analysis.” International Journal of Learning, Teaching and Educational Research 22 (11): 259–284. Article 11. https://doi.org/10. 26803/ijlter.22.11.14  . Sarkar, P., and A. Chakrabarti. 2011. “Assessing Design Creativity.” Design Studies 32 (4): 348–383.

https://doi.org/10.1016/j.destud.2011.01.002  . Shah, J. J., S. M. Smith, and N. Vargas-Hernandez. 2003. “Metrics for Measuring Ideation

Effectiveness.” Design Studies 24 (2): 111–134. https://doi.org/10.1016/S0142-694X(02)00034- 0  . Silvia, P. J., B. Wigert, R. Reiter-Palmon, and J. C. Kaufman. 2012. “Assessing Creativity with

Self-Report Scales: A Review and Empirical Evaluation.” Psychology of Aesthetics, Creativity, and the Arts 6 (1): 19–34. https://doi.org/10.1037/a0024071  . Stolaki, A., M. Satratzemi, and S. Xinogalos. 2023. “Examining the Effects of Creativity,

Collaboration, Creative Diversity and Autonomy on Team Creative Performance.” Thinking Skills and Creativity 50:101415. https://doi.org/10.1016/j.tsc.2023.101415  . Taura, T., E. Yamamoto, M. Y. N. Fasiha, M. Goka, F. Mukai, Y. Nagai, and H. Nakashima. 2012.

“Constructive Simulation of Creative Concept Generation Process in Design: A Research Method for Difficult-to-Observe Design-Thinking Processes.” Journal of Engineering Design 23 (4): 297–321. https://doi.org/10.1080/09544828.2011.637191  . Wadinambiarachchi, S., R. M. Kelly, S. Pareek, Q. Zhou, and E. Velloso. 2024. “The Effects of

Generative AI on Design Fixation and Divergent Thinking.” In Proceedings of the 2024 CHI Conference on Human Factors in Computing Systems, edited by F. F. Mueller, P. Kyburz, and J. R. Williamson, 1–18. New York, NY: Association for Computing Machinery. https://doi.org/10. 1145/3613904.3642919  . Wiltschnig, S., B. T. Christensen, and L. J. Ball. 2013. “Collaborative Problem–Solution Co-

Evolution in Creative Design.” Design Studies 34 (5): 515–542. https://doi.org/10.1016/j.des tud.2013.01.002  . Zamfirescu-Pereira, J. D., E. Jun, M. Terry, Q. Yang, and B. Hartmann. 2025. “Beyond Code

Generation: LLM-Supported Exploration of the Program Design Space.” In Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems, edited by N. Yamashita, V. Evers, and K. Yatani, 1–17. New York, NY: Association for Computing Machinery. https://doi. org/10.1145/3706598.3714154  . Zhai, C., S. Wibowo, and L. D. Li. 2024. “The Effects of Over-Reliance on AI Dialogue Systems on

Students’ Cognitive Abilities: A Systematic Review.” Smart Learning Environments 11 (1): 28. https://doi.org/10.1186/s40561-024-00316-7  . Zhang, J., and I. Arawjo. 2025. “ChainBuddy: An AI-Assisted Agent System for Generating LLM

Pipelines.” In Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems, edited by N. Yamashita, V. Evers, and K. Yatani, 1–21. New York, NY: Association for Computing Machinery. https://doi.org/10.1145/3706598.3714085  .

Team-LLM Collaboration in AI-Infused Classroom Debate.” In Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems, edited by N. Yamashita, V. Evers, and K. Yatani, 1–19. New York, NY: Association for Computing Machinery. https://doi.org/10.1145/ 3706598.3713853  . Zhou, Z., J. Li, Z. Zhang, J. Yu, and H. Duh. 2025. “Examining How the Large Language Models

Impact the Conceptual Design with Human Designers: A Comparative Case Study.” International Journal of Human–Computer Interaction 41 (10): 5864–5880. https://doi.org/10. 1080/10447318.2024.2370635  . Zielińska, A., I. Lebuda, and M. Karwowski. 2022. “Scaling the Creative Self: An Item Response

Theory Analysis of the Short Scale of Creative Self.” Creativity Research Journal 34 (4): 431–444. https://doi.org/10.1080/10400419.2022.2123139.

Figure A1. Representative design outcome (team 9).

Figure A2. Representative design outcome (team 6).

Figure A3. Representative design outcome (team 5).

Figure A4. Representative design outcome (team 4).

Figure A5. Representative design outcome (team 13).

Figure A6. Representative design outcome (team 16).

Figure A7. Representative design outcome (team 19).

Figure A8. Representative design outcome (team 17).