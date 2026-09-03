# SkillSync AI — Capstone Proposal

## 1. Problem Statement and Target User

Many students and young job seekers have difficulty identifying career paths that match their skills, interests, education, and abilities. They often rely on general online searches, advice from friends or teachers, or manually compare their skills with career requirements.

The target users are students, recent graduates, and young job seekers who need guidance when choosing a career direction or identifying skills they need to develop.

SkillSync AI will provide personalized career recommendations, identify potential skill gaps, and suggest a learning path.

## 2. Proposed Approach

The system will collect information about the user's skills, interests, education, personality, and aptitude.

A machine-learning classification model will analyze the user's profile and recommend suitable career categories. The current concept includes 106 career types and 10 personality/aptitude features. 

After a career is selected, the system will compare the user's existing skills with the skills associated with the career. The differences will be presented as skill gaps. A learning path will then organize suggested learning activities around those gaps.

The system will be designed as decision support rather than a system that makes the final career decision for the user.

## 3. Data

The initial career recommendation model will use a structured career dataset containing career labels and personality/aptitude features. The existing SkillSync concept identifies 106 career types and 10 personality/aptitude features.

Additional career-skill information will be required for the skill-gap and learning-path components.

The data can be stored in structured formats such as CSV and later integrated into the application.

### Open Data Question

A major open question is whether the available career and skill data is sufficiently complete and representative of the careers and users the system is intended to support.

## 4. Success Criteria

The project will be considered successful if:

1. The model can produce career recommendations from a user's profile.
2. The recommendations achieve an acceptable evaluation score on a held-out test dataset.
3. The system can identify skills associated with a selected career that are missing from the user's profile.
4. The system can produce a clear learning path based on the identified gaps.
5. Users can understand why a career was recommended and what they can do next.

The system should support decision-making rather than claim to determine the user's perfect career.

## 5. Scope Cut

The first version will not attempt to build every planned SkillSync feature.

Advanced CV improvement, cover-letter generation, interview evaluation, voice/video interview analysis, and a large job-market recommendation system will be left outside the initial scope.

This scope cut is necessary because implementing all of these features would make the project too large for the available development time. The first version will focus on career recommendation, skill-gap identification, and a basic personalized learning path.