# Sheet n°0: Develop in compliance with the GDPR

#### Whether you work alone, are part of a team developing a project, manage a development team, or are a service provider carrying out developments for third parties, it is essential to ensure that user data and all personal data processing are suffisiently protected throughout the lifecycle of the project.

The following steps will help you in the developing privacy-friendly applications or websites:

1. **Be aware of the GDPR core principles**. If you work in a team, we recommend that you identify a person responsible for monitoring compliance. If your company has a Data Protection Officer (DPO), then that person is a key asset in [understanding and meeting the GDPR obligations](https://www.cnil.fr/sites/default/files/atoms/files/guidelines_on_dpos_5_april_2017.pdf). The appointment of a DPO may also be mandatory in some cases, for example if your programs or applications process so-called "sensitive" data (see [examples](#Sheet_n°1:_Identify_personal_data)) on a large scale or conduct regular and systematic monitoring on a large scale.

2. **Map and categorize the data and processing in your system**. Accurately mapping the data processing performed by your program or application will help you ensuring that they comply with legal requirements. Keeping a [record of processing activities](https://www.cnil.fr/en/record-processing-activities) (an example of which can be found on the [CNIL website](https://www.cnil.fr/sites/default/files/atoms/files/record-processing-activities.ods)), allows you to have an overall view of these data, and to identify and prioritize the associated risks. Indeed, personal data may be present in unexpected places such as in server logs, cache files, Excel files, etc., and may be stored in a number of different places. Such record-keeping is mandatory in most cases.

3. **Prioritize the required actions**. On the basis of the data processing registry, identify the required actions to comply with the obligations of the GDPR in advance of the development and prioritize the attention points with regard to the risks for the data subjects by the processing. These points of attention concern in particular [the necessity and types of data collected and processed](#Sheet_n°7:_Minimize_the_data_collection) by your software, [the legal basis](#Sheet_n°15:_Take_into_account_the_legal_basis_in_the_technical_implementation) on which your data processing operations are based, [the information mentions](#Sheet_n°12:_Inform users) of your software or application, [the contractual clauses](#Sheet_n°5_:_Make_an_informed_choice_of_its_architecture) binding you to your contractors, the terms and conditions for [exercising rights](#Sheet_n°13:_Prepare_for_the_exercise_of_people_rights), the measures implemented to [secure your processing](#Sheet_n°6:_Secure_your_websites,_applications_and_servers).

4. **Manage the risks**. When you identify that a processing of personal data is likely to create high risks for data subjects, make sure that you manage those risks appropriately in the context. A [Privacy Impact Assessment (PIA) ](https://www.cnil.fr/en/privacy-impact-assessment-pia) can help you manage those risks. The CNIL has developed a [method](https://www.cnil.fr/sites/default/files/atoms/files/cnil-pia-1-en-methodology.pdf), [model documents](https://www.cnil.fr/sites/default/files/atoms/files/cnil-pia-2-en-templates.pdf) and a [tool](https://www.cnil.fr/en/open-source-pia-software-helps-carry-out-data-protection-impact-assesment) that will help you to identify those risks, as well as a [catalogue of good practices](https://www.cnil.fr/sites/default/files/atoms/files/cnil-pia-3-en-knowledgebases.pdf) that will assist you in implementing measures to address the identified risks. Furthermore, a privacy impact assessment is mandatory for all processing operations that are likely to create high risks to the rights and freedoms of data subjects. The CNIL proposes, on its [website](https://www.cnil.fr/sites/default/files/atoms/files/liste-traitements-aipd-requise.pdf), a list of  types of processing operations for which a DPA is required or not.

5. **put in place internal processes** to ensure compliance during all development stages, ensure that internal procedures guarantee that data protection is taken into account in all aspects of your project and into all events that may occur (e.g. security breach, requests for rectification or access fulfillment, modification of data collected, change of provider, data breach, etc.). The requirements of the [governance label](https://www.cnil.fr/sites/default/files/typo/document/CNIL_Privacy_Seal-Governance-EN.pdf) (even if this one no longer granted by the CNIL since the entry into force of the GDPR) can constitute a useful basis of inspiration to help you set up the necessary organization.

6. **Document developments compliance** to prove your compliance with the GDPR at all times: the actions performed and the documents produced at each stage of development must be mastered. This implies in particular a regular review and update of the documentation of your developments so that it is constantly consistent with the features deployed on your program.

The CNIL website provides numerous practical files which will assist you in setting up law-abiding treatments according to your sector of activity.