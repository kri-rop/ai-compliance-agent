# Example Agent Output

## Scenario

A company plans to evaluate incoming job applications with an AI system. The system assigns a score from 0 to 100 based on the CV, professional experience and qualifications. Applications scoring below 60 are automatically rejected without prior human review. The system is used in recruitment and directly determines who proceeds to the next stage. All data is processed within the European Union.

**Question:** Can the company use the system in this form, and which requirements arise under the GDPR and the EU AI Act?

## Agent Response

### 1. Initial Assessment

The proposed use affects a particularly sensitive area: fully automated decisions about individuals without prior human review. Automatic rejection in a recruitment process can have a significant effect on applicants and therefore raises serious concerns under the GDPR. In addition, AI systems used to select or evaluate applicants are likely to fall within the high risk category under the EU AI Act.

The use case is not automatically prohibited in every configuration. However, the described setup creates substantial compliance risks and should not be deployed without significant safeguards and a separate legal assessment.

### 2. Relevant Legal Areas

**GDPR**

1. Scoring applicants based on CV data and qualifications constitutes profiling because personal characteristics are evaluated automatically.

2. Rejecting an applicant without human review constitutes a fully automated decision with a significant effect on the individual.

**EU AI Act**

1. AI systems used for recruitment, selection and evaluation in an employment context are likely to be classified as high risk AI systems.

2. The exact obligations depend on the company role, the system configuration and the applicable implementation timeline.

Employment law and works council participation may also be relevant. These areas require a separate assessment.

### 3. Reasoning

Under GDPR Article 22, individuals have the right not to be subject to a decision based solely on automated processing when the decision produces legal effects or similarly significant consequences. An automated rejection in a recruitment process is a typical example of such a decision.

The scoring process itself may be permissible under specific conditions. However, sending an automatic rejection without meaningful human review is only allowed in narrowly defined situations, such as explicit consent, contractual necessity or a specific legal basis.

Even where an exception applies, suitable safeguards are required. Applicants must be able to contest the decision, present their position and request meaningful human review.

A Data Protection Impact Assessment is also likely to be required because the system systematically evaluates personal aspects and supports decisions with significant consequences.

Under the EU AI Act, recruitment systems are likely to trigger high risk requirements. Depending on whether the company develops or operates the system, relevant duties may include:

1. Human oversight

2. Transparency and documentation

3. Risk management and quality controls

4. Traceability of system decisions

The final classification and applicable obligations must be verified for the specific system and intended use.

### 4. Main Risks

**Risk 1: Unlawful fully automated decision making**

Automatic rejection without meaningful human review may conflict with GDPR Article 22 and may lead to complaints, regulatory action and fines.

**Risk 2: Missing or insufficient legal basis**

The company needs a clear and documented legal basis for both profiling and the related decision process. Consent is particularly difficult in recruitment because it may not be considered freely given.

**Risk 3: Discriminatory outcomes**

The scoring model may disadvantage specific groups because of career gaps, educational background, language, age or other indirect indicators. The risk is higher when no qualified person reviews the result.

**Risk 4: Missing high risk safeguards**

If the system is classified as high risk AI, the company must ensure that the relevant EU AI Act obligations are addressed, particularly human oversight and documentation.

**Risk 5: Missing Data Protection Impact Assessment**

Deploying the system without a prior impact assessment may leave a central GDPR requirement unfulfilled.

### 5. Recommended Actions

#### Safer Use

1. Use the AI score as decision support only. A qualified person should review every proposed rejection before it is communicated.

2. Inform applicants clearly that AI is used, explain the purpose of the scoring and describe the available rights.

3. Provide a clear process for contesting decisions and requesting human review.

These measures reduce risk but do not replace a legal assessment.

#### Questions to Resolve Before Deployment

1. Conduct a Data Protection Impact Assessment.

2. Verify the system classification under the EU AI Act.

3. Document the legal basis for profiling and decision support.

4. Review the provider documentation, including accuracy, limitations and potential bias.

5. Involve the works council where applicable.

6. Define deletion and retention periods for applicant data.

#### Practices to Avoid

1. Sending automatic rejections without human review.

2. Deploying the system without a Data Protection Impact Assessment.

3. Treating the score as objectively correct without testing for bias and error.

4. Failing to inform applicants about the use of AI.

5. Assuming that a lower risk design is automatically compliant.

### 6. Information Still Required

A more precise assessment requires clarification on whether the system is developed internally or purchased from an external provider. This affects whether the company acts as a provider, deployer or both under the EU AI Act.

### 7. Notice

This output is a structured preliminary assessment and does not constitute binding legal advice. Because the scenario involves automated recruitment decisions and a likely high risk AI classification, the company should obtain legal and data protection review before deployment.

## Documentation Note

This example was generated during a controlled validation test of the portfolio MVP. It demonstrates the response structure and the interaction between retrieval, conversation memory and the system prompt. It is not intended as a substitute for current legal guidance.
