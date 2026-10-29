Applying the Gollin effect to design VR for stargazing, and exploring the correlates between participants’ VR self‑efficacy, interest, frustration, flow experience and learning outcomes

Kai‑Hsin Tai1 · Jon‑Chao Hong2

Received: 29 September 2023 / Accepted: 7 June 2024 / Published online: 11 July 2024 © The Author(s), under exclusive licence to Springer Science+Business Media, LLC, part of Springer Nature 2024

Abstract Stellar observation, encompassing the study of star formation, stellar properties, and the governing physical laws, presents a readily accessible topic for many learners; however, many stargazing beginners may find it challenging. By applying the supplemental Gollin effect within animated display and the haptic effect of game-like play with a remote controller joystick, we designed an immersive Virtual Reality (IVR) game named Stargazing-Fun for participants to locate stars with different levels of brightness and to draw lines between stars to form constellations. To understand the learning effect of this IVR design, visitors to an Astronomical Museum were invited to take part in an experiment, during which the learning effectiveness of IVR-Stargazing-Fun was examined by conducting preand post-tests and administering a questionnaire related to IVR self-efficacy, learning interest, IVR frustration, and flow experience. A total of 213 useful data were subjected to structural equation modeling. The results of this study indicated that IVR self-efficacy was positively related to learning interest, but negatively related to IVR frustration; flow experience could be positively predicted by learning interest, but negatively predicted by IVR frustration; and flow experience could positively predict learning outcome. Besides, comparing the pretest and posttest, the results showed learning progress in IVR practice. Results imply that the Gollin effect can be applied to VR designs for beginner of stargazing.

Keywords  Gollin effect · Haptic effect · Human–computer interface · Virtual reality

Highlights • To prove the Gollin effect in stargazing learning via immersive virtual reality (IVR). • The Gollin effect can enhance learners’ stargazing outcome. • Increasing IVR self-efficacy can increase learning interest, while decreasing IVR frustration. • Increasing flow experience can increase learning interest, while decreasing IVR frustration. • Flow experience can positively predict players’ learning outcomes.

Extended author information available on the last page of the article

1  Introduction

Despite the widespread inclusion of astronomy stargazing in curricula prior to the twentieth century, how to use new technology to enhance students’ learning of stargazing is a relatively new endeavor (Chiang et al., 2021). Examples of this shift to new technology use include the STAR project, which was carried out in the United States, and the CLEA (Contemporary Laboratory Experiences in Astronomy) project, which was conducted in France. Both of these projects are examples of this shift (Cevik & Kurnaz, 2017). Observations and experiments are essential for the emergence and advancement of science, and execution for comprehending astronomy (Trumper, 2000). In school astronomical courses, learning aids, paper-based planispheres, or computer simulations are most popular to assist with learning (Cui & Li, 2018). However, they do not easily reflect the three-dimensional sense of the starry sky, and can cause observational obstacles (Liono et al., 2021).

A brief overview of existing digital curriculum designs for stargazing education is provided as follows. A recent study utilized a mobile planetarium using the DynaLearn software, called Stargazing Live, to support learners in building up their stargazing conceptual models and concept trees (Bredeweg et al., 2023). Their digital curriculum was shown to help learners gain conceptual understanding of star formation, star properties and associated laws. Chen and Lin (2016) developed a context-aware astronomy learning system based on the concept of ubiquitous learning. Their system used real-time and season-specific learning content, which integrated personal experience and conceptual knowledge. In Chen and Lin’s study, those designs efficiently guided learners to find specific stars by showing the image and information of the stars. Additionally, due to its use of augmented reality, the Mobile Digital Armillary Sphere (MDAS) could help users feel they were really observing the stars outdoors (Zhang et al., 2014). Users used their mobile devices as a digital compass, and after setting the time and date, following the guide, the specific stars would appear. The app would then display the pictures as a cognitive scaffold to support users’ effective learning. To sum up, the current mobile application, augmented reality, and virtual reality market provides different kinds of applications such as star walking and sky guides that enable users to find the stars and arrange certain shapes by observing and comparing pictures. However, the available applications primarily cater to visual and auditory learners, potentially neglecting those with a kinesthetic learning style (Huang & Wang, 2023). Empirical studies on stargazing using learning methods suitable for such learners are limited.

To overcome this problem, previous studies have considered using augmented reality (AR) to develop students’ astronomical knowledge, and have found that it provides better learning aids to help develop learners’ stargazing skills (e.g., Chiang et al., 2021; Liono et al., 2021). It is not difficult to conclude that adding haptics can enhance the experience of stargazing because immersive virtual reality (IVR) can introduce haptic feedback to enhance the sense of reality for users by more closely reproducing the kind of real-world conditions that the IVR

experience provides (Gibbs et al., 2022). However, a virtual observation device needs to make sense of changing sensations that are naturally and coherently generated by the same image or percept (Nanay, 2018). Thus, for the present study we designed IVR for stargazing learning.

The Gollin effect (1960) is associated with episodic memory which has strong image connections to medial temporal lobe memory structures (Pearson et  al., 2011). When using Gollin figures, players must extract distinctive features and mentally “fill in” the missing visual information to guess what the object might be (Gollin, 1960); we therefore wanted to understand how the image sources contribute to visuo-haptic multisensory action. Thus, the present study aimed to determine whether the availability of the virtual haptic positional cue with drawing to link stars and recognize constellations would facilitate stargazing performance (i.e., after virtual practice, players can form the lines for constellations by imagining when they look at the sky without any instruments). Additionally, the functional integration of the mirror neuron system under the visual perception of actions is for the application of action observation in the virtual environment (Cattaneo & Rizzolatti, 2009). IVR can provide a virtual learning environment combined with authentic situations so that complex spatial relationships and abstract images can be visualized (Fan & Luo, 2022); thus, embedding the Gollin effect into IVR for stargazing seemed likely to provide an opportunity for beginners. We therefore designed a virtual environment named Stargazing-Fun to assist stargazing learning, and explored how players reacted to this environment by exploring their cognitive and affective processes while playing the game.

According to the cognitive-affective theory of multimedia learning (CATML; Moreno, 2006), Matthews et  al. (2020) suggested that negative IVR experiences can lead to adverse emotional reactions and hinder comprehension of the simulated game content. Moreover, self-efficacy refers to an individual’s feeling of being competent and confident in their capacity to finish tasks and activate positive emotion in learning (Demirelli & Karaçay, 2024); for example, self-efficacy could affect players’ IVR learning interest and influence their learning performance (Tai et al., 2022). This raises an interesting research question: What are the relations between learners’ self-efficacy, learning interest, frustration, flow experience and learning progress when playing Stargazing-Fun. The present study aimed to provide advanced understanding of IVR research on the use of virtual environments for learning in stellar contexts over the cognitive and affective processes. The ultimate goal of our study was to provide valuable insights for future stargazing education through the processes of IVR so that students could learn about the constellations in a more effective manner.

2  Theoretical background

2.1  VR self‑efficacy

According to Bandura (1986), self-efficacy is an individual’s belief that one can accomplish an objective or task. The degree to which individuals believe they

can successfully utilize technologies is known as technology self-efficacy. Many technology self-efficacy measures have been influenced by or have directly adapted Compeau and Higgins’s (1995) measure of computer self-efficacy, and the technology self-efficacy construct has been conceptualized and measured in a variety of different ways, including internet self-efficacy (Jokisch et  al., 2020; Tsai & Tsai, 2003), and IVR self-efficacy (Tai et  al., 2022). Empirical studies have pointed out that IVR can be of greater benefit to learners’ efficacy beliefs than video (Meyer et  al., 2019) or textbook presentations (Makransky et al., 2019). According to drive theory, individual self-efficacy is a predisposition which can encourage individuals to adapt to new environments (Hong et al., 2023). In Ptak et  al.’s (2022) study, the haptic constellation 3D VR was presented with a flexible orientation, and users had to rotate or redraw lines while they were exploring. In the intervals between stimuli, they indicated whether the figure was identical to or different from the immediately preceding one by pressing one of two buttons on the IVR controller. Thus, self-efficacy in using immersive VR for stargazing has also been associated with improved observation ability (Fan & Luo, 2022). Therefore, IVR self-efficacy was explored in this study, specifically when using the IVR stargazing system.

2.2  Frustration with IVR

VR gaming relies heavily on gaming experience, and cybersickness symptoms such as disorientation and frustration are probably brought on by being unaware of one’s surroundings rather than by the VR content itself (Kwon, 2019). Lemmens and von Münchhausen (2023) found that if the game was too hard, this caused frustration. When immersed in VR, users must recognize and manipulate 3D components and use their spatial–temporal abilities to observe and control the steps required to overcome the challenges posed by the design of the user interface (Sun et al., 2019). When individuals are immersed in using VR, their mental stress load can be high enough to disengage because of frustration or being overwhelmed (Matthews et al., 2020). That is, if they have trouble perceiving the correct depth or maintaining constant fixation on an object, they may be so frustrated that they are unable to enjoy the interaction with the VR content (Iskander et al., 2019).

However, immersing oneself in VR demands mental, physical, and temporal effort that may cause frustration during users’ pseudo-haptic experience (Kim & Xiong, 2022). In Gupta et al.’s (2020) study, actuators were used to provide finger-specific haptic feedback when entering text, which resulted in overwhelming frustration and effort, even when feedback was provided. Therefore, an IVR pre-training session was conducted, in which the participants were introduced to using Stargazing-Fun; it was expected that they would have lower levels of frustration from the task as a result of the training. Accordingly, the present study aimed to understand the degree of players’ frustration after pre-training on the use of immersive VR for practicing stargazing.

2.3  Learning interest

The potential for technological interaction known as technology-enhanced learning can be broken down into its cognitive and functional components (Salen et al., 2004). Cognitive interactivity refers to the psychological interaction with learning content. The learner’s interaction with the environment is referred to as functional interactivity. Most of it takes the form of direct manipulation of the environment’s components (Collins et al., 2021). VR systems can pique students’ interest in interaction by utilizing enough teaching materials, media, and equipment to pique students’ functional interest (Parong & Mayer, 2018). Taken together, VR allows learners to adopt cognitive and functional approaches through interactive scenarios, thereby increasing their learning interest (Tai et al., 2022). In other words, VR-based learning environments are very beneficial for enhancing learning interest (Schutte, 2020). There are several reasons why IVR is more enjoyable than traditional games, and understanding how immersive VR devices affect the gaming experience is important (Reer et al., 2022). However, few studies have examined learning interest in IVR stargazing, the subject of this study; thus, the present study explored the role of learning interest while players were playing Stargazing-Fun.

2.4  Flow experience

People in various work or learning settings experience flow, which is defined as an optimal experience (Csikszentmihalyi, 1990). Each player’s skill level was taken into consideration when setting the difficulty; if the game was too difficult, there was less flow, but if it was too easy, there was also less flow because they were bored (Lemmens & von Münchhausen, 2023). The primary function of IVR is to enhance telepresence and provide users with an immersive experience. Research on IVR recognizes the opportunity for immersive VR to create flow (Anderson & Laverie, 2022). For instance, users who have a VR travel experience may have higher flow when performing challenging tasks (An et al., 2021). Csikszentmihalyi (2000) stated that flow is dependent upon the individual’s perception of how difficult the task is; however, few studies have focused on identifying the mechanism of IVR that generates such user IVR flow experiences in the context of stargazing. Thus, participants’ flow experience when immersed in playing Stargazing-Fun was explored.

2.5  Learning progress

In terms of learning, a recently published meta-analysis found that VR is superior to non-immersive methods (Wu et al., 2020). Moreover, an interaction effect between media and methods on learning has been consistently demonstrated, and the implementation of different instructional methods has benefitted VR the most; this has been shown with the cognitive process principle (Meyer et al., 2019), and enactment (Makransky et al., 2021). Moreover, one important aspect of VR that aims to improve a student’s palpatory and, consequently, physical examination abilities is haptic feedback (Sampath et al., 2022). Additionally, Makransky and Petersen’s

2.6  Research model and hypotheses

2.7  Hypotheses

Learning

interest

H3 H1

IVR self-

efficacy

H2 H4

IVR Frustration

Fig. 1   Research model

(2019) desktop VR study results indicated that affective and cognitive pathways both lead to learning outcomes when measured with pre-to-post-test scores. For example, by being immersed in VR for nursing-simulated learning, the combination of modalities explained 51% of knowledge achievement in the preto posttest (Dubovi, 2022). In this study, learning was measured as preto posttest changes in the number of correct responses on a declarative knowledge test.

The cognitive aspect described as “spatial presence” or simply “being there” is a core aspect of presence (Gibbs et al., 2022). Moreover, learning assisted by extended reality (XR) technologies can facilitate students’ learning, affective processes, and learning outcomes (Chen et  al., 2022). In this IVR design, the Gollin effect was to activate players’ cognitive and affective processes to help them make sense of constellations with coherent percepts that can enhance their learning effectiveness. According to CATML (Moreno, 2006), a research model was conceptualized to explore the driving factor of IVR self-efficacy that affects participants’ learning interest and frustration when immersed in VR, as reflected in their flow experience and learning progress. The research model is presented as follows (Fig. 1).

Lowell and Tagare (2023) found that self-efficacy is extended to the participants’ cognitive and affective processes while immersed in VR. For example, Huang et al. (2023) applied VR simulation in teacher training and found that the pre-service teachers had a significant increment of self-efficacy and triggered interest, but also higher extraneous cognitive load. Breitkreuz et al.’s (2021) study felt that interacting

H5

IVR Flow experience

Learning

progress

IVR was fun and challenging, but the technical issues frustrated them, and they did not enjoy learning how to function within the virtual environment. That is, when using the IVR device with 3D headset and remote controllers in both hands, some of the users in Menin et al.’s (2022) study may be frustrated while operating VR as they did the same action in the real world, but they may also be interested in the IVR design which could generate the flow experience.

According to flow theory, participants’ flow experience could be predicted by positive emotion and some factors of technology acceptance (Wang, 2023). When students were engaged in digital learning situations, they may feel various academic emotions (e.g., interest or frustration in the present study), which may affect their engagement and flow experience (Fidan & Koçak Usluel, 2024). Besides, interest could generate a significant effect on learning, engagement, and flow experience (Flowerday & Shell, 2015), while VR usability, immersion, and interface learnability would significantly influence users’ flow experience while immersed in VR (Fang & Huang, 2021). Moreover, flow experience could be an efficient predictor of learning progress (e.g., Tang et al., 2023; Wang et al., 2023). Underpinning the cognitive and affective process, the IVR of this study based on the theoretical foundations of the Gollin effect and haptic feedback to design for examining the correlates between self-efficacy in IVR utilization, learning interest in stargazing, IVR frustration which may be associated with IVR flow experiences while playing Stargazing- Fun, and the progression of stargazing learning. Thus, a research model was conceptualized as follow.

In line with research model, this study explored how players process cognitively and affectively with the function of the design of Stargazing-Fun. Based on the research model above concerning the variables, which indicate a correlational effect of VR, it was predicted that IVR self-efficacy, interactive interest, and frustration when immersed in VR would have a significant effect on flow experience in Stargazing Fun and their learning progress after playing Stargazing Fun. Consequently, a total of five hypotheses were linked and proposed: IVR self-efficacy will have a positive effect on learning interest (Hypothesis 1), IVR self-efficacy will have a negative effect on frustration (Hypothesis 2); learning interest will have a positive effect on flow experience (Hypothesis 3), frustration will have a negative effect on flow experience (Hypothesis 4), and flow experience will have a positive effect on learning progress (Hypothesis 5). Hypotheses 1 through 5 are displayed in Table 1.

Table 1   Research hypotheses

H1: IVR self-efficacy is positively related to learning interest H2: IVR self-efficacy is negatively related to frustration H3: Learning interest is positively related to flow experience H4: IVR Frustration is negative related to flow experience H5: IVR Flow experience is positively related to learning progress

3  Method

3.1  Stargazing‑fun

The perceptual representation of an object is associated with its meaning on a mental associative level, and the object is identified. When compared to using each sense separately, the integration of visual and haptic inputs improves movement performance (Camponogara & Volcic, 2021). Deshpande et al.’s (2008) report on haptic shape and texture provides the details of image acquisition and analysis. Accordingly, in the present study, we first designed different virtual stars as objects for players to locate at each different level of stars in the suitable position of that constellation. Thus, we designed eight levels of star sizes for players to locate the position and place each star corresponding to different constellations.

The human brain needs to continuously accumulate sensory information over time to begin haptic object perception (Yang et al., 2021). Since VR devices now include haptic feedback as a built-in feature, it is critical to comprehend how the two modes interact to enhance the learning experience (Gibbs et al., 2022). For example, Yang et al. (2021) suggested that haptic 3D object perception is processed across the cortical hierarchy, with other higher-level regions across time in a way that depends upon the object’s features. Additionally, a grip controller typically displays movements toward haptic-sensing objects more slowly than movements toward visually detected objects (Camponogara & Volcic, 2019). Accordingly, we designed constellations for players practicing stargazing by drawing the lines between stars to show the figure of those constellations (see Fig. 3) to form the Gollin effect.

3.2  How to play

3.2.1  Allocating stars

The size of each star represents a different level of magnitude. There are eight levels of stars of different size and brightness in the game. Players have to select and locate the stars correctly by operating the controller with their hands (see Fig. 2). If the

Fig. 2   Select and locate the stars

player places a star in the wrong position, the dot will turn red and an error sound will be produced as feedback.

3.2.2  Drawing lines between stars

The players were instructed to use the controllers to draw lines between stars based on the zodiac sign. Correct lines would remain on the screen, while incorrect lines would be removed. If the player failed, dotted lines would appear on the screen as hints (see Fig. 3). After the player drew all lines correctly, an image of the constellation would be presented.

3.3  Research settings

The experiment was set up at Taipei Astronomical Museum where visitors could play with the VR devices. As the metaverse has been popularized since Oct. 2021, we believed that visitors to Taipei Astronomical Museum might be curious about playing Stargazing-Fun. We set up five constellations in the VR devices and placed the VR equipment in the first-floor lobby of the museum for visitors to take part in this experiment. The schedule of the experiment was from 10:00 to 17:00 for 14 days. Every player could spend 20 min to complete the five constellations.

To ensure participants’ correct VR operation, we set up 5 min pre-training for players to familiarize themselves with the mobility of VR. That is, during the beginning interaction of playing VR, assistants helped anyone who was frustrated, for example, saying: “Go left, more left…No other direction… Left, no right…Or what side is it?” The assistant may instruct players, “Go right, it is just above you, there, there are some levels of stars …. You need to take steps forward and not backward.” Players may respond, “I thought I was reaching to those stars, but it seems that I missed looking at the top of the sky.”

Fig. 3   Feedback of drawing correct and incorrect lines between the stars of Cassiopeia

3.4  Procedure

First, visitors to the Astronomical Museum in Taipei who were interested in playing Stargazing-Fun registered and took a pretest on their knowledge of the five constellations. Second, they received pre-training to familiarize them with VR mobility. Third, they played Stargazing-Fun until they had completely linked the five constellations. Finally, they took the posttest on the five constellations and completed the questionnaire items. As this study falls into the category of “educational evaluation” in our institution, participants gave their consent before taking part in this experiment. They were also given the information that they had the option of withdrawing from the study if they wished to.

3.5  Participants

The participants in the present study were visitors to the Astronomical Museum in Taipei. Data were collected over a period of 2 weeks, with 254 questionnaires returned. After deleting incomplete questionnaires, 213 were left for further statistical analysis. In terms of gender, there were 98 males (46%) and 115 females (54%). As for age, we only collected data from visitors between the ages of 21 and 60, of whom 139 (65%) were between 21 and 40, and 74 (35%) were between 41 and 60. Regarding educational level, 36 participants (17%) were studying for a bachelor’s degree, 117 (55%) had a bachelor’s degree, and 60 (28%) had a master’s degree or above.

3.6  Questionnaire

3.6.1  IVR self‑efficacy

Tai et  al. (2022) adapted computer self-efficacy (Compeau & Higgins, 1995) to design a VR self-efficacy scale for students engaged in VR car-detailing. Referring to their scale, we designed six items for measuring participants’ self-efficacy when immersed in VR to play Stargazing-Fun. Example items are: “I can manipulate the VR by myself,” “I can easily operate the VR,” and “I can easily find out how to play the astronomy VR game.”

3.6.2  Frustration

The frustration measurement of this study referred to the scale developed by Lemmens and von Münchhausen (2023) which asked participants to reflect on the game when answering the following items: “Interacting with VR is difficult to operate and frustrates me,” “I lose my sense of balance when using the VR,” and “I feel tired when using the VR.”

3.6.3  Learning interest

An interest scale was designed by Hong et al. (2019) to measure learning interest, based on which Tai et al. (2022) developed the VR Learning Interest scale Accordingly, we designed seven items to measure participants’ learning interest while immersed in VR, which included statements such as: “Being immersed in VR to learn astronomy is enjoyable” and “I think it is fun to learn about constellations in VR.”

3.6.4  Flow experience

Tai et al. (2022) modified the questionnaire designed by Pearce et al. (2004) which measured internet users’ flow experience. Referring to Authors’ scale, seven items were designed for this study; example items are: “When experiencing the VR, I can ignore the passage of time,” “When experiencing the VR, I will not be distracted by the environment,” and “When experiencing the VR, I do not notice what is happening around me.”

3.7  Questionnaire development

The questionnaire items were adapted from previous researchers, and content validity was obtained by domain experts with their item verification. Moreover, face validity was obtained by inviting seven students to examine the meaning of each item. Finally, the items were assessed on a 5-point Likert scale ranging from 1 (Disagree strongly) to 5 (Agree strongly). Then, confirmatory factor analysis (CFA) was applied to analyze the item suitability, and SPPS was applied to test the construct reliability. Based on the first-order CFA, items were deleted as follows: IVR self-efficacy was reduced from six to five items, learning interest from seven to six, frustration from seven to six, and flow experience from eight to six. The remaining items were then subjected to reliability and validity tests.

3.7.1  Reliability and validity analysis

Questionnaire item analysis involves internal and external validity analysis. The results of a test administration can identify which items can be retained and which need to be discarded (Nunnally & Bernstein, 1994). Internal validity was ascertained by assessing the value of the factor loadings, and those items in each construct with a factor loading value of less than 0.5 were removed (Hair et al., 2019). Table 2 shows that all factor loading of items in each construct were over 0.7. Then, retained items in each construct were subjected to reliability and validity analysis.

To understand whether a questionnaire construct is reliable and stable, reliability tests are needed to understand the consistency of the items within the questionnaire constructs. Emerson (2019) proposed that Cronbach’s α values and composite reliability (CR) should be higher than 0.70 to be considered highly

Table 2   Reliability and validity analysis

Construct Items M SD Cronbach’s α CR FL AVE

IVR self-efficacy 5 3.89 0.70 0.78 0.80 0.75 0.75

Frustration 6 1.94 0.71 0.93 0.95 0.87 0.80

Learning interest 6 4.05 0.80 0.86 0.90 0.80 0.64

Flow experience 6 4.38 0.84 0.94 0.92 0.82 0.71

Table 3   Constituent discriminative validity

Construct IVR self-efficacy Frustration Learning interest Flow experience

IVR self-efficacy 0.87

Frustration 0.32 0.89

Learning interest 0.26 0.64 0.80

Flow experience 0.37 0.40 0.41 0.84

reliable. Table 2 shows that all Cronbach’s α values were over 0.78, and the CR values were over 0.80, indicating that all constructs had good reliability.

In the study, convergent validity and construct discriminant validity were examined by average variance extracted (AVE) and factor loadings (FL) which should be higher than 0.5. Table 1 indicates that AVE ranged from 0.64 to 0.80 and FL ranged from 0.75 to 0.87, which means that each component of the questionnaire scale in this study had convergent validity (Emerson, 2019).

Construct discriminant validity is mainly used to verify whether there is a difference in the correlation between two structures. The absolute value of Pearson correlation between constructs should be lower than the square root of AVE (Emerson, 2019). Table 3 indicates that the research instrument of this study has construct discriminative validity.

4  Results

4.1  Learning progress

To understand the Gollin effect on stargazing, participants’ learning progress was calculated by comparing pre-to-post-test. The participants took a pretest before they played Stargazing-Fun, and then took a posttest after they finished playing. The correct rate was found to be 3.70 with a standard deviation of 1.61 for the pretest and 5.02 with a standard deviation of 1.61 for the posttest. To test the learning progress, we performed the t test and found that the participants had made great improvement (t = −11.27***, p < 0.001) (see Table 4).

Table 4   Learning progress descriptive statistics analysis table

Correct rate % M SD Mode Median t-value

Pretest 3.70 1.61 3 4 −11.27***

Posttest 5.02 1.61 5 5

*** p < 0.001

4.2  The structural model fit analysis

Referring to Hair et al. (2019), the fit indexes for the Absolute Fit Measures include the Chi-square, Root Mean Square Error of Approximation (RMSEA), Goodness of Fit Index (GFI), and Adjusted Goodness of Fit Index (AGFI). The data of this study showed that the overall Absolute Fit Measures in this research were χ2 = 593, and the degree of freedom was df = 185, which indicated that χ2/df = 0.01. A ratio of less than 3 is indicative of a good fit (Hair et al., 2016). For RMSEA, a commonly reported cut-off value is 0.08 and the lower the RMSEA value, the better it is. For GFI, a value above 0.8 is a good fit. For AGFI, a value above 0.8 is acceptable. In this study, the value of RMSEA was 0.08, GFI was 0.81, and AGFI was 0.80, indicating that they all exceeded the recommended threshold values (Hair et al., 2019).

The fit indexes for Incremental Fit Measures include the Normed Fit Index (NFI), Non-Normed Fit Index (NNFI), Incremental Fit Index (IFI), Comparative Fit Index (CFI), and Relative Fit Index (RFI). The Incremental Fit Measures in this research were NFI = 0.80, TLI = 0.82, IFI = 0.85, CFI = 0.85 and RFI = 0.80. Those values greater than 0.80 are considered a good fit (Hair et al., 2019). Overall, according to Hair et al. (2019), the model fit indexes above show that the model of this research was acceptable.

4.3  Path analysis

After testing model fit, AMOS 20.0 was applied to test the significance of the hypotheses in the research model. Figure 4 indicates that IVR self-efficacy was positively related to learning interest (β = 0.71***, t = 3.79, and negatively related to frustration (β = -0.84***, t = 4.08). Learning interest was positively related to flow experience (β = 0.38***, t = 4.14). Frustration was significantly negatively related to flow experience (β = -0.25**, t = 3.12). Flow experience was positively related to learning progress (β = 0.20*, t = 1.90).

Figure 4 shows that the explanatory power ­R2 of IVR self-efficacy on learning interest was 0.22 and the overall effect statistic f2 was 0.28, which was greater than 0.02 and so had a moderate effect; the explanatory power ­R2 of IVR selfefficacy on frustration was 0.27 and the effect size f2 was 0.37, which was greater than 0.35 and so had a large effect; the explanatory power of learning interest and frustration on flow experience ­R2 was 0.19. The collation effect size f2 was 0.23, which was greater than 0.02 and so had a moderate effect; the explanatory power

Learning

interest

.38*** (t = 4.14) .71 *** (t = 3.79)

Ŕ2= .28

Gameplay self-efficacy

-.84*** (t = 4.08)

Frustration

R2= .27

Ŕ2= .37

Fig. 4   Verification of the research model

5  Discussion

5.1  IVR self‑efficacy related to learning interest

.20* (t = 1.90) R2= .22

Flow experience

Learning

progress

R2= .19

R2= .11

Ŕ2= .23

Ŕ2= .03

-.25** (t = 3.12)

of flow experience on learning progress ­R2 was 0.11, and f2 was 0.03 with a moderate effect size.

In this study, we embedded haptic feedback by providing sound when errors were made or dotted lines to provide cognitive scaffolding for players to notice their mistakes. In line with these schemes, feedback can diminish users’ trial and error rating, and there is no doubt that users can meaningfully learn via VR (Schölkopf et  al., 2021). However, to examine the cognitive and affective processes of immersing VR to practice stargazing with the Gollin effect, five hypotheses were verified as follows.

According to Dewey (1913), when the enjoyment of a learning activity and the informational content are not connected, learners are likely to quickly lose interest and so disengage from the activity. Previous studies have found IVR self-efficacy to be associated with a significant increase in virtual environment. For example, in Pande et al.’s (2021) study, undergraduates’ performance and perceived enjoyment increased because of using an environment biology VR system, but their self-efficacy did not improve significantly. According to Fredrickson (2001), emotions such

as joy and interest have complimentary effects. Additionally, emotions are portrayed in the literature at various continuous or discrete levels (Schlosberg, 1954). Drawing on Dewey’s definition and levels of emotion, Hong et al. (2014) divided the levels of interest into: like, enjoyment and engagement. According to Authors’ differentiation of interest, enjoyment could be the second level of interest. Therefore, how interest in being immersed in VR to learn about constellations was affected by IVR self-efficacy was explored in this study; the results showed that H1 was positively verified. This result is similar to that of Tai et al. (2022) (Hong et al., 2022) empirical study which invited participants to play car maintenance VR training games, as self-efficacy was shown to be positively related to learning interest.

5.2  IVR self‑efficacy related to frustration

Based on Bandura’s conceptualization of self-efficacy (1997), virtual reality selfefficacy can be defined as the belief that one can successfully complete a VR task that requires visuospatial ability (Tai et al., 2022; Hong et al., 2022). There is, however, scarce evidence that IVR self-efficacy affects spatial mobility performance (Kuznetcova et  al., 2023). Additionally, when immersed in VR, students need to practice certain skills by familiarizing themselves with the interface, which may make them feel frustrated (Reeves et al., 2021). However, self-efficacy can promote proper execution of the skills and may result in less frustration in virtual environments; that is, if individuals have greater self-efficacy to perform VR operational procedures, they should experience less frustration (Saville & Foster, 2021). In this study, playing Stargazing-Fun required spatial mobility; therefore, to understand how players’ frustration could be predicted by their self-efficacy, H2 was proposed, but it was negatively supported, indicating that the higher level of IVR self-efficacy players had, the lower level of frustration they would have.

5.3  Learning interest related to flow experience

According to flow theory, the most crucial factor in achieving optimal experience is achieving a balance between difficulty and skill (Csikszentmihalyi, 1990). Kiili et al. (2021) examined the extent to which flow experience and situational interest are indicators of game-based learning engagement, and found that learning interest is mostly related to the immersive aspect of flow. However, flow and learning interest measures were embedded directly into the learning environment. For example, the immersion of VR learning environments could enhance learners’ task interest and generate flow (Lindner et al., 2017). A greater understanding of what makes VR games interesting and of how being immersed in using VR devices changes the interaction experience offers the opportunity to improve interest and the user flow experience (Reer et al., 2022). Previous empirical studies had similar results, with learning interest positively related to flow experience during a Chinese remote association game (Hong et al., 2021) and during VR car-detailing (Tai et al., 2022). In examining the relationship between learning interest and IVR flow experience while

playing Stargazing, the prediction of learning interest to flow experience (H3) was positively verified in this study.

5.4  Frustration related to flow experience

Frustration is poorly induced negative emotion, as knowledge or competence cannot guide the development of targeted interventions (Scheinost et al., 2021). Games involve players in a competition against a time limitation or other players (Gomila & Calvo, 2008). In this kind of game-based learning environment, if the game task is not too difficult or too easy, players will experience flow. On the other hand, if a game is too difficult and uses too many mental resources, it will create frustration (Kiili et al., 2021). Williams’s (2018) empirical study explored whether the two different types of controllers would affect users’ conceptual models and mental models, and the result supported that operation frustration may have a significant negative relation to flow expectation. This supports H4 in the present study. It was indicated that if participants perceived high levels of frustration when playing IVR Stargazing-Fun, they would experience less flow state.

5.5  IVR flow related to learning progress

When a challenge’s difficulty continuously adapts to a player’s evolving skills, flow occurs. This gives the player a sense of mastery and influences the learning outcome (Rutrecht et al., 2021). Positive emotions can act as a mediator between the multimedia lesson and learning outcomes because they interact with one another (Meyer et  al., 2019). Digital learning methods such as game-based learning that support interaction and competition may improve flow experience and may appeal more to students (García-Viola et al., 2019). They may therefore retain knowledge for longer (Gutierrez-Puertas et al., 2021). Another empirical study by Tai et al. (2022) also found that when VR was used for car-detailing training, the higher level of flow experience participants had, the better their learning outcomes in terms of procedural accuracy and performance quality. Supporting their study, H5 was positively verified, indicating that when participants played VR Stargazing-Fun, if they had high levels of flow experience, their learning progress would be enhanced based on a comparison of their pre-to-post-test scores.

6  Conclusion

With the application of the Gollin effect, players can extract distinctive features and mentally “fill in” the missing visual information to guess what the object might be. The present study assumed that the availability of the virtual haptic positional cue with drawing to link stars and recognize constellations would facilitate stargazing in terms of constellation recognition performance with VR simulation. The statistical results revealed that IVR self-efficacy is positively related to learning interest, but negatively related to IVR frustration. Learning interest is positively related to IVR

flow experience, but IVR frustration is negatively related to IVR flow experience. Lastly, IVR flow experience is positively related to learning progress. The results of this study showed that VR can provide a virtual learning environment combined with complex spatial relationships and abstract images, and found that the haptic effect in virtual reality on stargazing seems to bring an opportunity for beginners to learn about constellations. Additionally, the research hypotheses were positively verified, except for the linkages of frustration.

6.1  Implications

The results of this study provide evidence that to shape concrete images from abstract images, the Gollin effect can be applied to stimulate learners’ imagination. Thus, the Gollin effect can be applied to the recognition of other mental figures, if the image is not so clear to beginners. For example, it could be applied to pathology checking for medical students.

It is very common for new VR users to experience frustration when interacting with VR; thus, pre-training for new VR users is necessary to let them become familiar with the VR functions and mobility. In this study, the average score of frustration when immersed in using VR was 1.94 (SD = 0.71), which indicates that pre-training on immersive VR for visitors who might never have used VR before was effective. Moreover, the results of this study found that the lower level of frustration one has, the higher level of flow one would have. It can therefore be concluded that pre-training for new VR users is an essential approach when implementing VR for learning.

6.2  Limitations and future study

Stargazing-Fun encourages learners to use episodic memory to acquire declarative knowledge through procedural knowledge about stargazing based on the Gollin and haptic effects. However, there are other cognitive approaches that may be used to design educational games, such as Embodied Conversational Agents (Elvir et al., 2017), or different retrieval design (Small & Cochrane, 2020). Future studies may merge different cognitive approaches to design IVR and compare the different learning effects.

In terms of the human–computer interaction, Johnston et al. (2018) highlighted two types of interactivities in virtual surroundings: functional and cognitive interactivity. This study took IVR self-efficacy as one dimension to explore the correlates when playing Stargazing-Fun. Hong et al., (2022) divided self-efficacy into Internet self-efficacy and content learning self-efficacy. Future studies may separate self-efficacy into VR functional self-efficacy and VR content learning self-efficacy, and take them as two driving factors to activate cognition or emotion when engaged in different types of VR learning.

This study was conducted at Taipei Astronomical Museum, where visitors might be more interested in stargazing than other people. The results of this study can therefore only apply to this group. Future studies may compare Astronomical

Museum visitors to non-visitors to explore the difference in their learning interest or flow experience, and the Gollin effect on Stargazing-Fun. Besides, different learning styles may also be considered to explore the difference in learners’ learning interest and flow experience (e.g., visual, audio, reading, kinesthetic, VARK learning style; Nguyen et al., 2024). Future studies may compare the learning effects of IVR Stargazing-Fun on learners with different learning styles.

Acknowledgements  This work was financially supported by the “Institute for Research Excellence in Learning Sciences” of National Taiwan Normal University (NTNU) from The Featured Areas Research Center Program within the framework of the Higher Education Sprout Project by the Ministry of Education (MOE) in Taiwan.

Funding  This work was financially supported by the “Institute for Research Excellence in Learning Sciences” of National Taiwan Normal University (NTNU) from The Featured Areas Research Center Program within the framework of the Higher Education Sprout Project by the Ministry of Education (MOE) in Taiwan.

Data availability  The relevant data sets collected during this research can only be accessed for educational research purposes, and the participants are not permitted to share the data according to the consent form.

Declarations

Competing interests  The authors declare that they have no competing interests" in this section.

References

An, S., Choi, Y., & Lee, C. K. (2021). Virtual travel experience and destination marketing: Effects of

sense and information quality on flow and visit intention. Journal of Destination Marketing & Management, 19, 100492. https://​doi.​org/​10.​1016/j.​jdmm.​2020.​100492 Anderson, K. C., & Laverie, D. A. (2022). In the consumers’ eye: A mixed-method approach to under-

standing how VR-Content influences unbranded product quality perceptions. Journal of Retailing and Consumer Services, 67, 102977. https://​doi.​org/​10.​1016/j.​jretc​onser.​2022.​102977 Bandura, A. (1986). The explanatory and predictive scope of self-efficacy theory. Journal of Social and

Clinical Psychology, 4(3), 359–373. https://​doi.​org/​10.​1521/​jscp.​1986.4.​3.​359 Bandura, A. (1997). Self-efficacy: The exercise of control. Freeman. Bredeweg, B., Kragten, M., Holt, J., Vaendel, D., Hanse, J., & Bloemen, S. (2023). Stargazing live!

Inspiring with real data in a mobile planetarium and learning through conceptual modelling. In International Conference on Intelligent Tutoring Systems (pp. 257–269). Springer. Breitkreuz, K. R., Kardong-Edgren, S., Gilbert, G. E., Anderson, P., DeBlieck, C., Maske, M., Hallock,

C., Lanzara, S., Parrish, K., Rossler, K., Turkelson, C., & Ellertson, A. (2021). Nursing faculty perceptions of a virtual reality catheter insertion game: A multisite international study. Clinical Simulation in Nursing, 53, 49–58. https://​doi.​org/​10.​1016/j.​ecns.​2020.​10.​003 Camponogara, I., & Volcic, R. (2019). Grasping movements toward seen and handheld objects. Scientific

Reports, 9(1), 3665. https://​doi.​org/​10.​1038/​s41598-​018-​38277-w Camponogara, I., & Volcic, R. (2021). Integration of haptics and vision in human multisensory grasping.

Cortex, 135, 173–185. https://​doi.​org/​10.​1016/j.​cortex.​2020.​11.​012 Cattaneo, L., & Rizzolatti, G. (2009). The mirror neuron system. Archives of Neurology, 66(5), 557–560.

https://​doi.​org/​10.​1001/​archn​eurol.​2009.​41 Cevik, E. E., & Kurnaz, M. A. (2017). Investigation of preservice science teachers’ comprehension of the

Star, Sun, Comet and Constellation concepts. Journal of Education and Practice, 8(6), 48–58.

Chen, C. C., & Lin, P. H. (2016). Development and evaluation of a context-aware ubiquitous learning

environment for astronomy education. Interactive Learning Environments, 24(3), 644–661. https://​ doi.​org/​10.​1080/​10494​820.​2014.​915417 Chen, X., Xie, H., & Li, Q. (2022). Vision, status, and topics of X Reality in education. Computers &

Education: X Reality, 1, 100001. https://​doi.​org/​10.​1016/j.​cexr.​2022.​100001 Chiang, C. L., Chen, C. Y., Lin, Y. L., & Lai, C. H. (2021). Effect of augmented reality on astronomy

learning: An example of informal constellation courses. International Journal on Digital Learning Technology, 13(2), 27–55. Collins, J., Regenbrecht, H., & Langlotz, T. (2021). Expertise and Experience in VR-supported learning:

Achieving a deep non-verbal comprehension of four-dimensional space. International Journal of Human-Computer Studies, 152, 102649. https://​doi.​org/​10.​1016/j.​ijhcs.​2021.​102649 Compeau, D. R., & Higgins, C. A. (1995). Computer self-efficacy: Development of a measure and initial

test. MIS Quarterly, 19(2), 189–211. https://​doi.​org/​10.​2307/​249688 Csikszentmihalyi, M. (1990). Flow: The psychology of optimal experience. Harper Collins. Csikszentmihalyi, M. (2000). Happiness, flow, and economic equality. American Psychologist, 55(10),

1163–1164. https://​doi.​org/​10.​1037/​0003-​066X.​55.​10.​1163 Cui, C., & Li, S. (2018). IAU WG, data-driven astronomy education and public outreach, current status

and working plans. arXiv e-prints arXiv:​1801.​05098 Demirelli, E. G., & Karaçay, P. (2024). Factors associated with nursing students’ online learning self-

efficacy: A descriptive cross-sectional study. Nurse Education Today, 132, 106029. https://​doi.​org/​ 10.​1016/j.​nedt.​2023.​106029 Deshpande, G., Hu, X., Stilla, R., & Sathian, K. (2008). Effective connectivity during haptic perception:

A study using Granger causality analysis of functional magnetic resonance imaging data. NeuroImage, 40, 1807–1814. https://​doi.​org/​10.​1016/j.​neuro​image.​2008.​01.​044 Dewey, J. (1913). Interest and effort in education. Riverside. Dubovi, I. (2022). Cognitive and emotional engagement while learning with VR: The perspective of mul-

timodal methodology. Computers & Education, 183, 104495. https://​doi.​org/​10.​1016/j.​compe​du.​ 2022.​104495 Elvir, M., Gonzalez, A. J., Walls, C., & Wilder, B. (2017). Remembering a conversation–a conversational

memory architecture for embodied conversational agents. Journal of Intelligent Systems, 26(1), 1–21. https://​doi.​org/​10.​1515/​jisys-​2015-​0094 Emerson, R. W. (2019). Cronbach’s alpha explained. Journal of Visual Impairment & Blindness (Online),

113(3), 327–327. https://​doi.​org/​10.​1177/​01454​82X19​858866 Fan, H., & Luo, Z. (2022). Functional integration of mirror neuron system and sensorimotor cortex under

virtual self-actions visual perception. Behavioural Brain Research, 423, 113784. https://​doi.​org/​10.​ 1016/j.​bbr.​2022.​113784 Fang, Y. M., & Huang, Y. J. (2021). Comparison of the usability and flow experience of an exercise pro-

motion virtual reality programme for different age groups. Behaviour & Information Technology, 40(12), 1250–1264. https://​doi.​org/​10.​1080/​01449​29X.​2021.​19386​80 Fidan, A., & Koçak Usluel, Y. (2024). Emotions, metacognition and online learning readiness are power-

ful predictors of online student engagement: A moderated mediation analysis. Education and Information Technologies, 29, 459–481. https://​doi.​org/​10.​1007/​s10639-​023-​12259-6 Flowerday, T., & Shell, D. F. (2015). Disentangling the effects of interest and choice on learning, engage-

ment, and attitude. Learning and Individual Differences, 40, 134–140. https://​doi.​org/​10.​1016/j.​lindif.​2015.​05.​003 Fredrickson, B. L. (2001). The role of positive emotions in positive psychology: The broaden-and-build

theory of positive emotions. American Psychologist, 56(3), 218–226. https://​doi.​org/​10.​1037/​0003-​ 066X.​56.3.​218 García-Viola, A., Garrido-Molina, J. M., Marquez-Hernandez, V. V., Granados-Gamez, G., Aguilera-

Manrique, G., & Gutierrez-Puertas, L. (2019). The influence of gamification on decision making in nursing students. Journal of Nursing Education, 58(12), 718–722. https://​doi.​org/​10.​3928/​01484​ 834-​20191​120-​07 Gibbs, J. K., Gillies, M., & Pan, X. (2022). A comparison of the effects of haptic and visual feedback

on presence in virtual reality. International Journal of Human - Computer Studies, 157, 102717. https://​doi.​org/​10.​1016/j.​ijhcs.​2021.​102717 Gollin, E. S. (1960). Developmental studies of visual recognition of incomplete objects. Perceptual and

Motor Skills, 11, 289–298.

Gomila, T., & Calvo, P. (2008). Directions for an embodied cognitive science: Toward an integrated

approach. In P. Calvo & T. Gomila (Eds.), Handbook of cognitive science: An embodied approach. Elsevier. Gupta, A., Samad, M., Kin, K., Kristensson, P. O., & Benko, H. (2020). Investigating remote tactile feed-

back for mid-air text-entry in virtual reality. In: 2020 IEEE International Symposium on Mixed and Augmented Reality (ISMAR) (pp. 350–360). IEEE. https://​doi.​org/​10.​1109/​ISMAR​50242.​2020.​ 00062. Gutierrez-Puertas, L., García-Viola, A., Marquez-Hernandez, V., Garrido-Molina, J., Granados-Gamez,

G., & Aguilera-Manrique, G. (2021). Guess it (SVUAL): An app designed to help nursing students acquire and retain knowledge about basic and advanced life support techniques. Nurse Education in Practice, 50, 102961. https://​doi.​org/​10.​1016/j.​nepr.​2020.​102961 Hair, J. F., Risher, J. J., Sarstedt, M., & Ringle, C. M. (2019). When to use and how to report the results

of PLS-SEM. European Business Review, 13(1), 2–24. https://​doi.​org/​10.​1108/​EBR-​11-​2018-​0203 Hair, J. F., Sarstedt, M., Matthews, L. M., & Ringle, C. M. (2016). Identifying and treating unobserved

heterogeneity with FIMIX-PLS: part I – method. European Business Review, 28(1), 63–76. Hong, J. C., Chang, C. H., Tsai, C. R., & Tai, K. H. (2019). How situational interest affects individual

interest in a STEAM competition. International Journal of Science Education, 41(12), 1667–1681. https://​doi.​org/​10.​1080/​09500​693.​2019.​16249​92 Hong, J. C., Hwang, M. Y., Hsu, H. T., & Tai, K. H. (2023). Gestalt perception: A game designed to

explore players’ gameplay self-efficacy and anxiety reflected in their learning effects. Journal of Research on Technology in Education, 55(3), 441–458.  https://​doi.​org/​10.​1080/​15391​523.​2021.​ 19678​19 Hong, J. C., Hwang, M. Y., Liu, M. C., Ho, H. Y., & Chen, Y. L. (2014). Using a “prediction-observation-

explanation” inquiry model to enhance student interest and intention to continue science learning predicted by their internet cognitive failure. Computers & Education, 72, 110–120. https://​doi.​org/​ 10.​1016/j.​compe​du.​2013.​10.​004 Hong, J. C., Hwang, M. Y., Tai, K. H., & Lin, P. H. (2021). The effects of intrinsic cognitive load and

gameplay interest on flow experience reflecting performance progress in a Chinese remote association game. Computer Assisted Language Learning, 34(3), 358–378. https://​doi.​org/​10.​1080/​09588​ 221.​2019.​16140​68 Hong, J. C., Liu, X., Cao, W., Tai, K. H., & Zhao, L. (2022). Effects of self-efficacy and online learning

mind states on learning ineffectiveness during the COVID-19 lockdown. Educational Technology & Society, 25(1), 142–154. Huang, T. H., & Wang, L. Z. (2023). Artificial intelligence learning approach through total physical

response embodiment teaching on French vocabulary learning retention. Computer Assisted Language Learning, 36(8), 1608–1632. https://​doi.​org/​10.​1080/​09588​221.​2021.​20089​80 Huang, Y., Richter, E., Kleickmann, T., & Richter, D. (2023). Comparing video and virtual reality as

tools for fostering interest and self-efficacy in classroom management: Results of a pre-registered experiment. British Journal of Educational Technology, 54(2), 467–488. https://​doi.​org/​10.​1111/​ bjet.​13254 Iskander, J., Hossny, M., & Nahavandi, S. (2019). Using biomechanics to investigate the effect of VR

on eye vergence system. Applied Ergonomics, 81, 102883. https://​doi.​org/​10.​1016/j.​apergo.​2019.​ 102883 Johnston, E., Olivas, G., Steele, P., Smith, C., & Bailey, L. (2018). Exploring pedagogical foundations

of existing virtual reality educational applications: A content analysis study. Journal of Educational Technology Systems, 46(4), 414–439. https://​doi.​org/​10.​1177/​00472​39517​745560 Jokisch, M. R., Schmidt, L. I., Doh, M., Marquard, M., & Wahl, H.-W. (2020). The role of internet

self-efficacy, innovativeness and technology avoidance in breadth of internet use: Comparing older technology experts and non-experts. Computers in Human Behavior, 111, 106408. https://​ doi.​org/​10.​1016/j.​chb.​2020.​106408 Kiili, K. J. M., Lindstedt, A., Koskinen, A., Halme, H., Ninaus, M., & McMullen, J. (2021). Flow

experience and situational interest in game-based learning: Cousins or identical twins. International Journal of Serious Games, 8(3), 93–114. https://​doi.​org/​10.​17083/​ijsg.​v8i3.​462 Kim, W., & Xiong, S. (2022). Pseudo-haptics and self-haptics for freehand mid-air text entry in VR.

Applied Ergonomics, 104, 103819. https://​doi.​org/​10.​1016/j.​apergo.​2022.​103819 Kuznetcova, I., Glassman, M., Tilak, S., Wen, Z., Evans, M., Pelfrey, L., & Lin, T. J. (2023). Using a

mobile Virtual Reality and computer game to improve visuospatial self-efficacy in middle school students. Computers & Education, 192, 104660. https://​doi.​org/​10.​1016/j.​compe​du.​2022.​104660

Kwon, C. (2019). Verification of the possibility and effectiveness of experiential learning using

HMD-based immersive VR technologies. Virtual Reality, 23, 101–118. https://​doi.​org/​10.​1007/​ s10055-​018-​0364-1 Lemmens, J. S., & von Münchhausen, C. F. (2023). Let the beat flow: How game difficulty in vir-

tual reality affects flow. Acta Psychologica, 232, 103812. https://​doi.​org/​10.​1016/j.​actpsy.​2022.​ 103812 Lindner, P., Miloff, A., Hamilton, W., Reuterskiold, L., Andersson, G., Powers, M. B., & Carlbring,

P. (2017). Creating state of the art, next-generation virtual reality exposure therapies for anxiety disorders using consumer hardware platforms: Design considerations and future directions. Cognitive Behavioral Therapy, 46(5), 404–420. https://​doi.​org/​10.​1080/​16506​073.​2017.​12808​43 Liono, R. A., Amanda, N., Pratiwi, A., & Gunawan, A. A. S. (2021). A systematic literature review:

Learning with visual by the help of augmented reality helps students learn better. Procedia Computer Science, 179, 144–152. https://​doi.​org/​10.​1016/j.​procs.​2020.​12.​019 Lowell, V. L., & Tagare, D. (2023). Authentic learning and fidelity in virtual reality learning experi-

ences for self-efficacy and transfer. Computers & Education: X Reality, 2, 100017. https://​doi.​ org/​10.​1016/j.​cexr.​2023.​100017 Makransky, G., & Petersen, G. B. (2019). Investigating the process of learning with desktop virtual

reality: A structural equation modeling approach. Computers & Education, 134, 15–30. https://​ doi.​org/​10.​1016/j.​compe​du.​2019.​02.​002 Makransky, G., Borre-Gude, S., & Mayer, R. E. (2019). Motivational and cognitive benefits of train-

ing in immersive virtual reality based on multiple assessments. Journal of Computer Assisted Learning, 35(6), 691–707. https://​doi.​org/​10.​1111/​jcal.​12375 Makransky, G., Andreasen, N. K., Baceviciute, S., & Mayer, R. E. (2021). Immersive virtual reality

increases liking but not learning with a science simulation and generative learning strategies promote learning in immersive virtual reality. Journal of Educational Psychology, 110, 785–797. https://​doi.​org/​10.​1037/​edu00​00473 Matthews, T. J., Tian, F., & Dolby, T. (2020). Interaction design for paediatric emergency VR train-

ing. Virtual Reality & Intelligent Hardware, 2(4), 330–344. https://​doi.​org/​10.​1016/j.​vrih.​2020.​ 07.​006 Menin, A., Torchelsen, R., & Nedel, L. (2022). The effects of VR in training simulators: Exploring

perception and knowledge gain. Computers & Graphics, 102, 402–412. https://​doi.​org/​10.​1016/j.​ cag.​2021.​09.​015 Meyer, O. A., Omdahl, M. K., & Makransky, G. (2019). Investigating the effect of pre-training when

learning through immersive virtual reality and video: A media and methods experiment. Computers & Education, 140, 1–17. https://​doi.​org/​10.​1016/j.​compe​du.​2019.​103603 Moreno, R. (2006). Does the modality principle hold for different media? A test of the method-affects-

learning hypothesis. Journal of Computer Assisted Learning, 22(3), 149–158. https://​doi.​org/​10.​ 1111/j.​1365-​2729.​2006.​00170.x Nanay, B. (2018). Multimodal mental imagery. Cortex, 105, 125–134. https://​doi.​org/​10.​1016/j.​cortex.​

2017.​07.​006 Nguyen, H. H., Do Trung, K., Duc, L. N., Hoang, L. D., Ba, P. T., & Nguyen, V. A. (2024). A model to

create a personalized online course based on the student’s learning styles. Education and Information Technologies, 29, 571–593. https://​doi.​org/​10.​1007/​s10639-​023-​12287-2 Nunnally, J. C., & Bernstein, I. H. (1994). Psychometric theory (3rd ed., p. 736). McGraw-Hill. Pande, P., Thit, A., Sørensen, A. E., Mojsoska, B., Moeller, M. E., & Jepsen, P. M. (2021). Long-term

effectiveness of immersive VR simulations in undergraduate science learning: lessons from a media-comparison study. Research in Learning Technology, 29, 1063519. https://​doi.​org/​10.​25304/​ rlt.​v29.​2482 Parong, J., & Mayer, R. E. (2018). Learning science in immersive virtual reality. Journal of Educational

Psychology, 110(6), 785–797. https://​doi.​org/​10.​1037/​edu00​00241 Pearce, J. M., Ainley, M., & Howard, S. (2004). The ebb and flow of online learning. Computers in

Human Behavior, 21(5), 745–771. https://​doi.​org/​10.​1016/j.​chb.​2004.​02.​019 Pearson, J. M., Heilbronner, S. R., Barack, D. L., Hayden, B. Y., & Platt, M. L. (2011). Posterior cingu-

late cortex adapting behavior to a changing world. Trends in Cognitive Sciences, 15(4), 143–151. https://​doi.​org/​10.​1016/j.​tics.​2011.​02.​002 Ptak, R., Turri, F., & Doganci, N. (2022). Object recognition and visual agnosia. Encyclopedia of Behav-

ioral Science ­(2nd edn, pp. 587–596). Academic Press.

Reer, F., Wehden, L. O., Janzik, R., Tang, W. Y., & Quandt, T. (2022). Virtual reality technology and

game enjoyment: The contributions of natural mapping and need satisfaction. Computers in Human Behavior, 132, 107242. https://​doi.​org/​10.​1016/j.​chb.​2022.​107242 Reeves, S. M., Crippen, K. J., & McCray, E. D. (2021). The varied experience of undergraduate students

learning chemistry in virtual reality laboratories. Computers & Education, 175, 104320. https://​doi.​ org/​10.​1016/j.​compe​du.​2021.​104320 Rutrecht, H., Wittmann, M., Khoshnoud, S., & Igarzabal, F. A. (2021). Time speeds up during flow

states: A study in virtual reality with the video game thumper. Timing & Time Perception, 9(4), 353–376. https://​doi.​org/​10.​1163/​22134​468-​bja10​033 Salen, K., Tekinbaş, K. S., & Zimmerman, E. (2004). Rules of play: Game design fundamentals. MIT

press. Sampath, K. K., Arumugam, A., Yaghi, E., Chidambaranathan, K., & Andersen, P. (2022). The role of

virtual reality (VR) with haptic feedback in enhancing physical examination skills of health care students - A systematic review protocol. International Journal of Osteopathic Medicine, 46, 51–54. Saville, J. D., & Foster, L. L. (2021). Does technology self-efficacy influence the effect of training pres-

entation mode on training self-efficacy? Computers in Human Behavior Reports, 4, 100124. https://​ doi.​org/​10.​1016/j.​chbr.​2021.​100124 Scheinost, D., Dadashkarimi, J., Finn, E. S., et al. (2021). Functional connectivity during frustration: A

preliminary study of predictive modeling of irritability in youth. Neuropsychopharmacology, 46, 1300–1306. https://​doi.​org/​10.​1038/​s41386-​020-​00954-8 Schlosberg, H. (1954). Three dimensions of emotion. Psychological Review, 61(2), 81–88. Schölkopf, L., Lorenz, M., & Tümler, J. (2021). Haptic feedback is more important than VR experi-

ence for the user experience assessment of in-car human machine interface. Procedia CIRP, 100, 601–606. https://​doi.​org/​10.​1016/j.​procir.​2021.​05.​130 Schutte, N. S. (2020). The impact of virtual reality on curiosity and other positive characteristics. Inter-

national Journal of Human-Computer Interaction, 36(7), 661–668. https://​doi.​org/​10.​1080/​10447​ 318.​2019.​16765​20 Small, J. A., & Cochrane, D. (2020). Spaced retrieval and episodic memory training in Alzheimer’s dis-

ease. Clinical Interventions in Aging, 519–536. https://​doi.​org/​10.​2147/​CIA.​S2421​13 Sun, C., Hu, W., & Xu, D. (2019). Navigation modes, operation methods, observation scales and back-

ground options in UI design for high learning performance in VR-based architectural applications. Journal of Computational Design and Engineering, 6, 189–196. https://​doi.​org/​10.​1016/j.​jcde.​2018.​ 05.​006 Tai, K. H., Hong, J. C., Tsai, C. R., Lin, C. J., & Hwang, M. Y. (2022). Virtual reality for car-detailing

skill development: Learning outcomes of procedural accuracy and performance quality predicted by VR self-efficacy, VR using anxiety, VR learning interest and flow experience. Computers & Education, 182, 104458. https://​doi.​org/​10.​1016/j.​compe​du.​2022.​104458 Tang, Q., Zhang, T., & Jiang, L. (2023). Influence of blended instruction on students’ learning effective-

ness: The role of Flow. Education and Information Technologies, 28(2), 1891–1909. https://​doi.​org/​ 10.​1007/​s10639-​022-​11224-z Trumper, R. (2000). University students’ conceptions of basic astronomy concepts. Physics Education,

35(1), 9–15. https://​doi.​org/​10.​1088/​0031-​9120/​35/1/​301 Tsai, C. C., & Tsai, M. J. (2003). Information searching strategies in web-based science learning: The

role of Internet self-efficacy. Innovations in Education and Teaching International, 40(1), 43–50. https://​doi.​org/​10.​1080/​13558​00032​00003​8822 Wang, J. (2023). Predictors of flow experience and knowledge acquisition in a STEM game. International

Journal of Serious Games, 10(3), 67–82. https://​doi.​org/​10.​17083/​ijsg.​v10i3.​619 Wang, W. T., Lin, Y. L., & Lu, H. E. (2023). Exploring the effect of improved learning performance: A

mobile augmented reality learning system. Education and Information Technologies, 28(6), 7509– 7541. https://​doi.​org/​10.​1007/​s10639-​022-​11487-6 Williams, R. B. (2018). Conceptual models and mental models in operation: Frustration, performance

and flow with two different video game controllers. Entertainment Computing, 28, 2–10. https://​doi.​ org/​10.​1016/j.​entcom.​2018.​07.​004 Wu, B., Yu, X., & Gu, X. (2020). Effectiveness of immersive virtual reality using head-mounted dis-

plays on learning performance: A meta-analysis. British Journal of Educational Technology, 51(6), 1991–2005. https://​doi.​org/​10.​1111/​bjet.​13023 Yang, J., Molfese, P. J., Yu, Y., Handwerker, D. A., Chen, G., Taylor, P. A., Ejima, Y., Wu, J., & Ban-

dettini, P. A. (2021). Different activation signatures in the primary sensorimotor and higher-level

regions for haptic three-dimensional curved surface exploration. NeuroImage, 231, 117754. https://​ doi.​org/​10.​1016/j.​neuro​image.​2021.​117754 Zhang, J., Sung, Y. T., Hou, H. T., & Chang, K. E. (2014). The development and evaluation of an aug-

mented reality-based armillary sphere for astronomical observation instruction. Computers & Education, 73, 178–188. https://​doi.​org/​10.​1016/j.​compe​du.​2014.​01.​003

Publisher’s Note  Springer Nature remains neutral with regard to jurisdictional claims in published maps and institutional affiliations.

Springer Nature or its licensor (e.g. a society or other partner) holds exclusive rights to this article under a publishing agreement with the author(s) or other rightsholder(s); author self-archiving of the accepted manuscript version of this article is solely governed by the terms of such publishing agreement and applicable law.

Authors and Affiliations

Kai‑Hsin Tai1 · Jon‑Chao Hong2

*	 Jon‑Chao Hong tcdahong@gmail.com

Kai‑Hsin Tai khtai@scu.edu.tw

1 Global Program in Interdisciplinary Studies, Soochow University, No. 70, Linhsi Road, Taipei City, Taiwan 111002

2 Institute for Research Excellence in Learning Sciences, National Taiwan Normal University, No. 162, Heping East Road Section 1, P. O. Box 7‑513, Taipei, Taiwan 106308