# Costs and Benefits of the AIBOM Conept Research
by Nathan Enterline
6/25/2024

## Intorduction 

  Artificial Intelligence (AI) encompasses the complex algorithms of Machine Learning (ML) and the advanced neural networks of Deep Learning (DL). Together, AI has the ability to process vast amounts of data and process the data as if it was an intelligent human. This form of technology can be used in many industries and in many applications. The purpose of an Artificial Intelligence Bill of Materials (AIBOM) is to provide full supply chain transparency of all necessary components that make up AI and ML models.
  This paper will review the Software Bill of Materials (SBOM) and it's effectiveness in generating transparency and safety for the procurement process of open sources software. This paper will use the research of the SBOM as an example to highlight the difference and explain the possible effectiveness of the AIBOM.

## Need for the Study

If an organization wishes to introduce AI technology into their organization, they must either create AI in house or use an existing AI model. If an organization wishes to use an existing AI model from a supplier, a method of examining the AI/ML components would be needed to ensure no compromised components are present in the AI model before it is introduced to an organization. The AIBOM will cover the specific components that the SBOM and Hardware Bill of Materials (HBOM) do not cover in an AI/ML model. Transparency in the procurement process of open-sourced software components has proven to be a critical step in protecting organizations from network attacks. According to Crane (2022), the majority, or about 75%, of software components used by organizations are obtained from open-sourced codebases. Because most software used by organizations comes from open sources, attackers may be capable of infecting software with malware from those open sources before it is introduced to an organization. If this affected software was distributed to organizations, then all organizations receiving this affected software would then affect their systems with malware.
One recent example of a software supply chain attack is the hack on SolarWinds. SolarWinds (2016) is a large-scale corporation that provides services and much of the software products used by other organizations such as Amazon, Apple, Google, Walmart, and McDonalds. They also provide software and services for the federal government. SolarWinds has a popular platform known as their “Orion Platform '' and Keith Barker, from CBT Nuggets (2020), explains that attackers were able to inject malware into SolarWinds’s Orion Platform without SolarWinds’s knowledge. And due to the software supply chain process, this malware was able to affect all the customers that obtained the Orion Platform from SolarWinds. Keith Barker from CBT Nuggets (2020) continues to explain that customers of SolarWinds were affected by this malware due to software updates that SolarWinds sent to its customers. When the customers of SolarWinds accepted their software update, they unknowingly infected their system with malicious code. Not long after the discovery of the SolarWinds incident, in May of 2021, President Biden issued executive order number 14028. This action was created to, “identify, deter, protect against, detect, and respond to these actions and actors” (Biden, 2021). This order directed the NIST to develop draft guidelines for organizations to follow to create an SBOM for federal procurement. If standards in regulations were in place for the SBOM before the attack on SolarWinds, then it can be speculated that the SolarWinds software supply chain attack would have been prevented. Since the inception of the SBOM, tools are now readily available for organization so that they may view critical components of open-source software before procurement. The end goal of an AIBOM would be to prevent AI related attacks on open-sourced AI models.

## Background

Numerous studies and research have been conducted on the SBOM and its effectiveness in improving software supply chain transparency. But with the major progress in AI technology in recent years, there has been minimal research done on the AIBOM concept. In fact, the need for the study and creation of an AIBOM was introduced by the U.S. Army. According to Brown and Travers (2024), the U.S.’s Army Program Executive Office for Intelligence, Electronic Warfare and Sensors (PEO IEW&S) announced a request for information (RFI) on how to implement a proposed AIBOM concept. Jr (2024), reports that there was industry outcry in the initial posting of this RFI and the RFI for the original AIBOM concept was modified. According to Brown and Travers (2024), the current concept includes the detailed components that are used to build an AI model along with dealing with the components for detailing the model’s properties, architecture, training data, hyperparameters, and intended use. However, professionals still protest this concept and cite multiple shortcomings. For example, the concept “would not be able to provide a complete security audit of the given AI model because certain aspects of model training and usage cannot be captured statically… Additionally, the AIBOM tool would miss important AI/ML-specific downstream systems” (Brown & Travers, 2024). Additional issues are also cited to exist in implementing an AIBOM. For instance, M. Brown (personal communication, 2023), mentions that an AI/ML weakness database, much like MITRE’s CVE, would need to be available for effective auditing of AI/ML systems. With the debate over the quality of the proposed AIBOM concept, further research would be needed to understand if the current concept would be effective in preventing AI based attacks or if alternative concepts would be necessary.

## Objectives

The objective of this research is to analyze the current professional opinion of the AIBOM and identify any current limitations to construct an AIBOM. By identifying any challenges with developing the AIBOM, future research can be conducted on the possible future implementation of the AIBOM. With an understanding on the challenges of creating and using an AIBOM, this research also aims to shine a light for organizations if the potential benefits of an AIBOM is worth the cost of investment in its creation. To achieve the objectives of this research, this paper will generate questions to answer five main research questions.

- RQ 1: Will the requirment of the AIBOM reduce the risk of cyberthreats related to supply chain managment?
- RQ2 : What would be the essential and non-essential components for an AIBOM?
- RQ 3: What are the current limitations for implementing the AIBOM?
- RQ 4: What would be an alternative to the AIBOM for AI/ML supply chain transparency?
- RQ 5: What would be the expected cost of research and development of effcient and effective AIBOM tooling?

### Research Questions

To answer the five main objectives and researcher questions (RQ) of this paper, the
respondents will use a Likert scale based on: Strongly Disagree (1), Disagree (2), Neutral (3),
Agree (4), and Strongly Agree (5) when responding to questions. The specific questions (SQ)
that will be asked to participants are outlined below.

- RQ 1: Will the requirment of the AIBOM reduce the risk of cyberthreats related to supply chain managment?
  - SQ: An AIBOM will be easy to use and generate with current available tools.
  - SQ: Third-party and open-source AI/ML components can always be trusted.
  - SQ: No vulnerabilites exsit in AI/ML systems.
    
- RQ2 : What would be the essential and non-essential components for an AIBOM?
  - SQ: All hardware components of an AI/ML system will be covered in an HBOM.
  - SQ: All software components of an AI/ML system will be covered in a SBOM.
  - SQ: AI/ML software vulnerabilites will still exist after a software security audit with an SBOM.
  - SQ: AI/ML hardware vulnerabilites will still exist after a hardware security audit with an HBOM
 
- RQ 3: What are the current limitations for implementing the AIBOM?
  - SQ: Enough technology and tools are available for all organizations to
generate an AIBOM.
  - SQ: A large enough AI/ML weakness database exists to audit AI/ML
systems.
  - SQ: An AIBOM will be easy to use and generate with current available
tools.

- RQ 4: What would be an alternative to the AIBOM for AI/ML supply chain transparency?
  - SQ: An SBOM will cover most of all aspects of AI/ML systems.
  - SQ: An AIBOM is the most effective solution to audit procured open-
source AI/ML systems.
  - SQ: There is no solution (AIBOM, SBOM, HBOM) to audit procured
open-source AI/ML systems.
  - SQ: All AI/ML models should be created in house.
  - SQ: All AI/ML system components can be easily created in house for
small scale organizations.
  - SQ: All AI/ML system components can be easily created in house for
medium scale organizations.
  - SQ: All AI/ML system components can be easily created in house for
large scale organizations.

- RQ 5: What would be the expected cost of research and development of effcient and effective AIBOM tooling?
  - SQ: No research cost would be needed for the generation of AIBOM tools.
  - SQ: A large (≥ $1,000,000) would be needed for research of AIBOM
tools.
  - SQ: No research cost would be needed for the creation of an AI/ML based
weakness database.
  - SQ: A large (≥ $1,000,000) would be needed for the creation of an AI/ML
based weakness database.
  - SQ: Creating in house AI/ML components is affordable for small scale
organizations.
  - SQ: Creating in house AI/ML components is affordable for small medium
organizations.
  - SQ: Creating in-house AI/ML components is affordable for large scale
organizations.

## Research Methodology
This research paper will rely on empirical research from a cross-section survey from professionals from the fields of software development, AI/ML development, and cybersecurity. This paper aims to gather quantitative data from at least 40 individuals from at least 10 different industries. This paper also aims to gather at least 20 participants for an interview on the outlook of the AIBOM. The participants gathered will be from across the globe for a diverse perspective on the topic. In order to recruit participants, the researcher will email developers on GitHub, working on SBOM and AI related projects. The researcher will also advertise on social media websites, such as Twitter and LinkedIn for additional recruitment. All participants will take a screening questionnaire to determine their demographic, experience level and fitness to take part in this research.
For the quantitative data, a questionnaire will use a Likert scale based on: Strongly Disagree (1), Disagree (2), Neutral (3), Agree (4), Strongly Agree (5). The interviewed participants will take the same questionnaire but will then be interviewed by researchers and asked to express their thoughts and provide justification for the grading they have given.

## Research Timeline

This project is predicted to take 3 months, or about 13 weeks to complete. The following  section outlines steps associated with this project and the estimated timeline for completion of those tasks

|  Reserch Tasks:  |  Duration:  |
| ---------- | ---------- |
| Draft Survey  |  1 Week  |
| Participant Recruitment (≥20) to interview for Qualitative data |  3 Weeks  |
| Participant Recruitment (≥40) to interview for Quantitative Survey |  3 Weeks  |
| Analyze Qualitative and Quantitative Results |  3 Weeks  |
| Organize and Graph Results  |  3 Weeks  |
| Present Results  |  1 Weeks  |

## Expected Outcomes

It would be expected that the general concept of an AIBOM would be considered necessary for reducing AI/ML based cyber-attacks that may occur from AI/ML open source acquired AI/ML systems. It would also be expected that most respondents will believe that the current state of tools available is not sufficient to easily draft an AIBOM and that a lack of AI/ML based weakness databases exists in order to audit AI/ML systems. Due to the complexity of AI/ML systems, it will also be expected that the majority of participants would not consider the SBOM and HBOM significant enough to audit complete AI/ML systems and that an AIBOM concept would need to exist and that the cost of investment may be beneficial for organizations at large.

## References
Biden, Joseph. Improving the Nation’s Cybersecurity. 12 May 2021. 14028.
Brown, M. (2023). Trail of Bits [Document to PEO IEW&S].
Brown, M., & Travers, A. (2024, February 28). Our response to the US Army’s RFI on
developing AIBOM tools. Trail of Bits Blog. https://blog.trailofbits.com/2024/02/28/our-
response-to-the-us-armys-rfi-on-developing-aibom-tools-2/
CBT Nuggets. (2020). The SolarWinds Hack Explained | Cybersecurity Advice [YouTube
Video]. In YouTube. https://www.youtube.com/watch?v=jD02Q3RStaM
Crane, D. (2022, September 29). Why The US Government Is Mandating Software Bill Of
Materials (SBOM). ActiveState. https://www.activestate.com/blog/why-the-us-
government-is-mandating-software-bill-of-materials-sbom
Jr, S. J. F. (2024, April 23). “AI-BOM” bombs: Army backs off, will demand less detailed data
from AI vendors. Breaking Defense. https://breakingdefense.com/2024/04/ai-bom-bombs-
army-backs-off-will-demand-less-detailed-data-from-ai-vendors/
