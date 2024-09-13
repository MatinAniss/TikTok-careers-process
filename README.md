# TikTok Careers Process

This is an unofficial documentation of the enum and states a TikTok careers application can represent.
https://careers.tiktok.com/position/application

## States

The order of the states have no particular importance, it is only ordered in colour. Written examination may be done before the resume evaluation.

### Resume Screening

<img src="badges/resumeScreening.svg" style="width: 100%;" alt="Resume Screening Badge">

### Resume Evaluation

<img src="badges/resumeEvaluation.svg" style="width: 100%;" alt="Resume Evaluation Badge">

### Written Examination

<img src="badges/writtenExamination.svg" style="width: 100%;" alt="Written Examination Badge">

### Evaluation Passed

<img src="badges/evaluationPassed.svg" style="width: 100%;" alt="Evaluation Passed Badge">

### Interview

<img src="badges/interview.svg" style="width: 100%;" alt="Interview Badge">

### Interview Pass

<img src="badges/interviewPass.svg" style="width: 100%;" alt="Interview Pass Badge">

### Pending Entry

<img src="badges/pendingEntry.svg" style="width: 100%;" alt="Pending Entry Badge">

### Have Joined

<img src="badges/haveJoined.svg" style="width: 100%;" alt="Have Joined Badge">

### Transfer

<img src="badges/transfer.svg" style="width: 100%;" alt="Transfer Badge">

### Termination

<img src="badges/termination.svg" style="width: 100%;" alt="Termination Badge">

### Unknown

<img src="badges/unknown.svg" style="width: 100%;" alt="Unknown Badge">

## Enum

| State                   | Enum               | Code |
| ----------------------- | ------------------ | ---- |
| Unknown                 | Unknown            | 0    |
| Ended                   | Termination        | 1    |
| Resume screening        | ResumeScreening    | 2    |
| Resume evaluation       | ResumeEvaluation   | 3    |
| Evaluation passed       | EvaluationPassed   | 4    |
| Written test            | WrittenExamination | 5    |
| Interviewing            | Interview          | 6    |
| Interview completed     | InterviewPass      | 7    |
| Pending onboard         | PendingEntry       | 8    |
| Onboarded               | HaveJoined         | 9    |
| Referred to another job | Transfer           | 10   |
