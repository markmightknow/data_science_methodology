# Data Science Lifecycle (DSLC) Methodology

This document outlines a Data Science Lifecycle (DSLC) methodology for use in any data science team's project work.

# DSLC Phase 1: Business Understanding

## DSLC1.1: Learn background context and establish business problem
### Principles
  * Assemble and communicate enough information to help determine whether the project should commence, relative to other priorities.
  * Learnings along the way can provide broader value.
  * Ambiguous terminology or interpretations that might impact on the translation to a data problem need to be identified.
  * It is essential to get a level of agreement on all matters pertaining to overall scope.
  * Assumptions and Dependencies play a foundational role in how analytics work unfolds.
### Expectations
  * Devise examples and ask questions until the business expectation is clear.
  * Ask and understand how any results are intended to be used.
  * Emphasise both knowledge and value are possible outcomes.
  * Try to home in on suitable modelling targets.
  * Details the rest of the team might need to know are recorded.
  * Enumerate the risks; this should include everything that can be identified up-front, discussed and assessed.
### Tasks
  1. Find out what the business request is.
  2. Clarify any up-front ambiguity in what is being requested as much as possible.
  3. Ideate/empathise/take cognizance.
  4. Provide enough relevant information on how data science projects are different from other approaches.
  5. For ideas that seem worth pursuing but are different to what the business has asked for, identify the discrepancy and seek agreement or make an agreeable plan to explore the possibility subsequently, or instead, or in parallel, and/or reevaluate at a decision point.
  6. Also consider whether a non-data science solution can be suggested at this stage.
  7. Review prior work, existing approaches and anything that has been implemented in the organisation already that is a potential component of candidate solutions.
  8. Identify all of the stakeholders and what their individual needs and roles are.
  9. Establish terminology and SME.
  10. Consider the role of IT given the potential different outcomes of the project and the implications for any targets, timeframes, and other scope.
  11. Initiate RAID Log + AD Register.
### Deliverable
  1. Triage advice
  2. Initial Project notes
#### Components
  1. Notes recorded from each of the tasks
  2. Inventory of Resources
#### Components
  1. List of the candidate data sources and any up-front understanding of what will be involved in the acquisition and data understanding.
  2. Compilation of other relevant materials
  3. RAAIDD
#### Components
  1. Risks, Actions, Issues, Decisions, Assumptions, Dependencies
### Definition of Done
  * Resolve any initial dependencies the supplying process has on the data science team.
  * Important background details communicated and available to team members.
  * Next steps enabled.
  * RAID Log and AD Register exist and available to reviewers and updaters.
### Other Questions
  * Why did this request come to the data science team?
  * What is the bigger picture that the project fits into?
  * Have contingencies been identified?
### Comments
  * May also need a light-weight mode.

## DSLC1.2: Assess business objectives and success criteria (pre-kickoff cost/benefit analysis)
### Principles
  * There are many ways a data science project can offer value and knowledge but it must be clear what success looks like and what the outlook is for achieving it -- including any uncertainty.
### Expectations
  * Determine the goals, objectives, and business success criteria well enough for a meaningful high-level estimate.
### Tasks
  1. List the inputs of the agreed success criteria.
  2. Prepare and pre-process data.
  3. Calculate Value, Assess feasibility.
### Deliverable
  1. Results of feasibility assessment
#### Components
  1. Any results that are essential inputs to initial solution design or decision to proceed.
  2. Plausible but high-level cost/benefit estimates.
### Definition of Done
  * The decision to proceed based on feasibility has been addressed.
### Other Questions
### Comments

## DSLC1.3: Translation of Business Problem to Data Problem
### Principles
  * At various stages of a data science project, the tasks at hand needs to explicitly reflect the data rather than separate concerns. Hence the business problem and goals must be accurately translated to and from facts about datasets.
### Expectations
  * Formalise the modelling in terms of data sets rather than business problems without losing alignment to the targets.
  * Assess and discuss the types of tools and techniques that are likely to be employed to build a solution.
  * Determine what is the most immediate activity that provides knowledge or value to stakeholders and uplifts the current state. (Arrange to do it and get feedback).
### Tasks
  1. Translation of Business success criteria to Data success criteria (subject to hypotheses etc.).
  2. Draft the high-level modelling plan.
  3. Update the inventory of resources.
  4. Establish what model is currently the most stable baseline in terms of assumptions and dependencies. What would be used in the absence of anything better?
### Deliverable
  1. Draft Modelling Plan
#### Components
    1. Proposed modelling outputs
    2. Proposed modelling goals
    3. Initial assessment of tools and techniques and high-level inputs to model requirements
### Definition of Done
  * Decision to proceed based on modelling capabilities has been addressed.
### Other Questions
  * Some reference methodologies put an ask "what else is important?" step here.
### Comments

## DSLC1.4: Agree Charter and Milestone Estimates
### Principles
  * It is important to make sure the stakeholders understand the nature of the project, and to address the possible outcomes relative to the stated goals, hence it makes sense to formalise it with a charter.
### Expectations
  * Use the available information to fill out a project charter.
  * Define the baseline performance. What heuristic or existing process are we trying to beat?
  * Provide visibility of a set of milestones that align everyone's expectations but with an overarching expectation that the exploratory nature of data science work can lead to the plan changing by necessity.
  * Address the calendar of stand-ups, planning, review, etc. sessions.
  * Summarise the purpose of the project in a motivational way.
  * Ask the people who are involved for estimates of how long their activities might take or when their dependencies might eventuate.
### Tasks
  1. Determine all the charter components and put them in the required format.
### Deliverable
  1. Charter Document
#### Components
    1. The problem statement
    2. The research goal
    3. The context
    4. How the analysis will be performed
    5. Measure of success
    6. Well-defined deliverables
    7. A plan with a timetable
    8. Justification that the project has chance to meet the measures of success
    9. The expected required resources
    10. Reach formal agreement on the deliverables to the extent that the business knows up-front what the expected effort, costs, and possible outcomes are.
    11. Proof-of-concept milestones highlighted
### Definition of Done
  * Charter created, discussed, and agreed.
### Other Questions
  * Is the overall cost & benefit analysis estimated and communicated accurately enough to go ahead with the data science work?
### Comments

## DSLC1.5: Project kick-off
### Principles
  * If the project is proceeding this should be reflected in the delivery tracking system.
### Expectations
  * The agreed work is broken down according to the currently agreed plan and organised with the relevant tracking artefacts.
### Tasks
  1. Manage Backlog.
### Deliverable
  1. Project Plan
#### Components
    1. Up-to-date backlog
### Definition of Done
  * The agreement to proceed can be enacted via the team's delivery approach.
### Other Questions
### Comments

# DSLC Phase 2: Data Understanding

## DSLC2.1: Data Acquisition
### Principles
  * Acquiring data from appropriate sources is an essential dependency of all data science projects.
### Expectations
  * Seek out the source data that best enables the goals of the project.
  * Navigate sensitivities around data access.
  * Communicate the findings from the data acquisition activities with a view to reusable datasets.
### Tasks
  1. Identify data sources (internal / external / public domain) and up-front data requirements.
  2. Approve purchases, buy and ingest.
  3. Request access to data.
  4. Collect initial data.
  5. Describe acquired data.
  6. Request up-front data engineering.
### Deliverable
  1. Rationale for the chosen source data
#### Components
  1. Details added to the project notes
  2. Source data for modelling 
#### Components
  1. Confirmed data sources and data dictionaries
  2. Data engineering outputs
### Definition of Done
  * Suitable data has been found and is accessible.
### Other Questions
  * Is the proposed data the source of truth?
  * What are the limitations (software/hardware/platform/operational) on accessing the source data?
### Comments

## DSLC2.2: Exploratory Data Analysis
### Principles
  * When you reduce datasets to statistics there is the potential for characteristics of the data to go unnoticed.
  * Exploratory Data Analysis allows us to figure out which subsets of data to use for further modelling.
  * Exploratory Data Analysis informs on how to prepare the data.
  * When you run datasets through modelling that is partly automated by software, there is the potential for characteristics of the data to go unnoticed or fail silently or produce unexpected results.
  * When the team is looking at a feature group for the first time, EDA might take longer to do properly. When the team is looking at a feature group for the nth time there should be clearly communicated prior work to leverage for greater efficiency.
### Expectations
  * When you are working on an exploratory data analysis task you aim to produce a structured set of summary statistics and useful visualisations. 
  * Form an understanding of the problem in terms of the detailed data context.
  * Aim for the team to retain the knowledge of what we learn about the data.
### Tasks
  1. Conduct Exploratory Data Analysis.
  2. Use summary statistics, clustering, simple modelling techniques, etc as needed to get an understanding of the data.
  3. Use graphical techniques to gain an understanding of your data and the interactions between variables.
  4. Determine the hypotheses to explore.
  5. Check the data being used to find out a model is well-aligned with the data for any scenarios the model is designed to be used on. (e.g. check no leakage of future state information into training data for a predictive model).
### Deliverable
  1. Explicitly obtained and shared profiling results and key observations.
#### Components
    1. Datatypes
    2. Univariate distributions
    3. Outliers and anomalies
    4. Correlations
    5. Noteworthy observations
    6. The factors influencing the modelling
  2. Inputs to a list of repeatable data validations
### Definition of Done
  * The results of the analysis inform on subsequent activities.
### Other Questions
  * Does the data have the required detail?
  * Can all the identified data reliably be accessed / acquired from the sources?
  * What are the (anticipated or actual) limitations (software/hardware/platform/operational) on accessing the source data?
### Comments
  * Further Reading: https://datascienceguide.github.io/exploratory-data-analysis

## DSLC2.3: Data Quality
### Principles
  * It is not logical to test hypotheses, draw conclusions, or plan processes based on invalid data.
### Expectations
  * The data quality is checked for suitable plausibility and consistency and can be validated on an ongoing basis if there are repeatable steps intended in the project.
### Tasks
  1. Identify any other datasets the data needs to reconcile to.
  2. Identify potential data quality issues that might impact on the project.
  3. Assess historical data stability to identify potential concept drift or structural breaks in the data generating process.
### Deliverable
  1. Data Quality Analysis
#### Components
    1. Rules, checks, controls, remediation approaches, code.
### Definition of Done
  * Modelling data can be validated for plausibility and consistency as frequently as needed.
### Other Questions
### Comments

## DSLC2.4: Design the Modelling
### Principles
  * The learnings from the data understanding phase will inform on what can and can’t be modelled and it is important to consolidate that in the form of a plan.
### Expectations
  * Different options for the modelling are considered against the goals of the project and the details of the design align with the team practices.
### Tasks
  1. Finalise high-level design and draft detailed design.
### Deliverable
  1. Detailed modelling plan
#### Components
    1. A detailed view of the planned components to the modelling, how the modelling will be assessed, the planned outputs, and how the outputs will be presented and used.
### Definition of Done
  * The modelling plan is updated and the inputs to the decision to continue based on what it is possible to model are available.
### Other Questions
  * Is the proposed data the best fit for delivering the solution?
### Comments

## DSLC2.5: Decision to proceed with modelling
### Principles
  * Information that comes to light during the data understanding phase may have an impact on the possible outcomes of the project and this should be discussed and considered.
### Expectations
  * Relevant information from the data understanding phase is translated into any decision points or other matters to be discussed with stakeholders.
### Tasks
  1. Establish the potential next steps ahead of detailed modelling.
### Deliverable
  1. Phase 2 Go/No-Go Checkpoint decision.
#### Components
    1. Summary of data viability
    2. Identified technical risks
    3. Revised timeline estimate
### Definition of Done
  * Decision whether to proceed has been made.
### Other Questions
  * Are the goals of the project in line with the advice of relevant data SMEs?
### Comments

# DSLC Phase 3: Modelling

## DSLC3.1: Feature Engineering
### Principles
  * The path to new insights and value from our business data will involve arranging datasets from different sources into previously unexplored configurations.
  * In most cases there is a point in the data flow where the joining and filtering of different sources has finished, and the remaining transformations make use of project-specific assumptions or imputations, derived values, aggregations, encoding for specific algorithms, etc.
### Expectations
  * With the learnings from the Data Understanding phase in-hand, join and transform the different source datasets into a suitable format for the ensuing steps.
  * Aim to be able to draw a clean line where the dataset can stand in its own right for modelling.
### Tasks
  1. Handle different file formats.
  2. Select, clean data, etc.
  3. Combine different source data sets.
  4. Apply modelling assumptions as needed.
  5. Derive, translate, and encode features.
  6. Set up dataset in a form ready for the modelling algorithms.
### Deliverable
  1. Prepared model inputs dataset
#### Components
    1. Documented inclusion/exclusion rules
    2. Readable remediation code
    3. Engineered dataset
    4. A plan that caters for any expected variability in subsequently generated versions of the datasets
  2. Pipeline for ongoing inputs to modelling
### Definition of Done
  * Feature data ready for modelling.
### Other Questions
### Comments

## DSLC3.2: Model Creation
### Principles
  * Modelling with data is the central activity in data science projects.
### Expectations
  * Correctly apply theory.
### Tasks
  1. Select Modeling Techniques.
  2. Feature Selection.
  3. Request Tools.
  4. Create model.
  5. Build model code.
  6. Set parameters.
  7. Train model.
  8. Test functionality.

### Deliverable
  1. Updated modelling plan
#### Components
    1. Explain Modelling Technique
    2. Document Modelling Assumptions
  2. Trained model
#### Components
    1. Trained model artifacts etc.
### Definition of Done
  * Model is ready to use in experiments.
### Other Questions
### Comments

## DSLC3.3: Experimental use of the Model
### Principles
  * A series of experiments may be required to test the modelling hypotheses.
### Expectations
  * Balance the need to experiment with the impact on live processes.
  * Accurately record the results of the experiments and make them available.
### Tasks
  1. Generate Test Design (iterative experiments or A/B testing on live data etc.).
  2. Detailed plan for conducting the experiments.
  3. Any implementation work to run the model in the experimental context.
  4. Run experiments.
### Deliverable
  1. Results of Experiments
#### Components
    1. Test Design
    2. Parameter Settings
    3. Completed experiment Runs
    4. Record of experiment runs and results
### Definition of Done
  * Enough evidence to proceed with evaluation.
### Other Questions
### Comments
  * Design for treatment feedback loops. If the model's output will influence future data collection, account for how to measure success without biasing future training sets.

## DSLC3.4: Evaluation of model
### Principles
  * Results of modelling should be assessed against project goals.
  * The path from modelling output back to business value may require custom translation work.
### Expectations
  * Bridge the gap between behaviour of the model and the original project goals.
  * Assess modelling and identify suitable next steps.
### Tasks
  1. Translate model assessment into success criteria and calculate the translated metrics.
  2. Assess parameters, redesign, retraining options and need for iteration.
  3. Finalise detailed design.
  4. Evaluation of model against benchmarks or standard measures.
  5. Evaluation of model based on translated business success measures.
  6. Production suitability determination.
  7. Business Validation.
  8. Technical Validation.
  9. Identify model enhancements based on validation results.
  10. Deployment readiness validation.
  11. List of Possible Actions.
  12. Determine Next Steps.
  13. Perform fairness and bias checks across critical cohorts.
### Deliverable
  1. Model Description
#### Components
    1. Modelling Report
    2. Solution architecture
  2. Evaluation results
  3. Checkpoint decision
#### Components
    1. Approved Models
### Definition of Done
  * Status of the model communicated.
  * Up-to-date project documentation and code repository.
### Other Questions
### Comments

## DSLC3.5: Insights
### Principles
  * The reason for the modelling is to uncover information and value for the customer.
  * When presenting insights, meaningful patterns and findings should be easy to see and make sense of with relatively little preparation on the part of the decision maker.
  * Insights should be presented in a way that allows stakeholders to avoid misinterpretation.
  * The methods used to arrive at the findings should be clear, compelling, and reproducible.
### Expectations
  * Results of the modelling are examined and interpreted for the benefit of the stakeholders.
  * Insights are presented in meaningful way.
### Tasks
  1. Assess model results and model-based insights analysis.
  2. Prepare insights for presentation.
  3. Deliver business insights.
### Deliverable
  1. Modelling Insights
### Definition of Done
  * Insights shared.
### Other Questions
### Comments

# DSLC Phase 4: Deployment

## DSLC4.1: Operationalisation
### Principles
  * Creation of a successful model is not the end of the project and many steps must be taken to get value out of the outputs.
### Expectations
  * Organise ongoing use of the model.
### Tasks
  1. Plan Deployment.
  2. Change an existing process to integrate modelling results or use of a model.
  3. Address any governance aspects.
  4. Establish handoff points.
  5. Build Test Infrastructure.
  6. Monitoring and training plan.
  7. Operationalised Data Engineering.
  8. Operational Data Validation.
  9. Job scheduling, failure modes.
  10. Operational implementation.
  11. A/B testing.
  12. UAT.
  13. Operationalise the model.
### Deliverable
  1. Detailed Plan of deployment components and outputs
  2. Operational Implementation
### Definition of Done
  * Model artifacts are successfully integrated into the target environment, automated pipelines are running without error, and business users can access the outputs.
### Other Questions
### Comments

## DSLC4.2: Monitoring
### Principles
  * Models need to be managed on an ongoing basis when in operation.
### Expectations
  * Address how to efficiently monitor and maintain the model.
### Tasks
  1. Monitoring of statistical aspects of an operational model.
  2. Monitoring of system aspects of an operational model.
  3. Provision, access, or use of model outputs.
  4. Monitor usage, performance, and value.
### Deliverable
  1. Monitoring Arrangements
#### Components
    1. Dashboards
    2. Triage and Fix arrangements
    3. Other BAU arrangements
### Definition of Done
  * Automated alerts for data drift, concept drift, and system failures are active and routing to the designated support team.
### Other Questions
### Comments

## DSLC4.3: Post-Deployment Status Update
### Principles
  * A project is not complete just because code is in production; knowledge transfer and documentation are vital for long-term maintainability.
### Expectations
  * Provide a clear summary of what was built, the ongoing value, how it operates, and any technical debt accepted during deployment.
### Tasks
  1. Produce Final Report.
  2. Conduct Final Presentation.
### Deliverable
  1. Final Presentation
#### Components
    1. Final modelling report with deployment details and solution architecture document
### Definition of Done
  * Final report is distributed to all stakeholders and archived in the team's knowledge base.
### Other Questions
### Comments

## DSLC4.4: Customer Acceptance
### Principles
  * The value of a data science solution is ultimately determined by the end-user's willingness to adopt it.
### Expectations
  * Secure formal acknowledgement that the solution meets the agreed-upon success criteria from the Charter (DSLC1.4).
### Tasks
  1. Arrange an exit report for the project from the customer.
  2. Establish customer acceptance.
### Deliverable
  1. Project validation, sign-off, and feedback
### Definition of Done
  * Formal customer sign-off is recorded.
### Other Questions
### Comments

## DSLC4.5: Measure Uplift
### Principles
  * True ROI is measured after the model has interacted with the real world for a sustained period.
### Expectations
  * Quantify the actual business impact against the original baseline and conduct a team retrospective.
### Tasks
  1. Reflect and identify improvements.
  2. Translate project work and ongoing value into team success measures.
### Deliverable
  1. Experience Documentation, Identified Improvements
  2. Measured Uplift
### Definition of Done
  * ROI analysis is completed and lessons learned are integrated into the team's ongoing practices.
### Other Questions
### Comments