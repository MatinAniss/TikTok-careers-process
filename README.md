# TikTok Careers Process

This is an unofficial documentation of the enum and states a TikTok careers application can represent.
https://careers.tiktok.com/position/application

## States

The order of the states have no particular importance, it is only ordered in colour. Written examination may be done before the resume evaluation.

### Resume Screening

<div style="width: max-content; color: #5c3a00; background-color: #faf1d1; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Resume screening</div>

### Resume Evaluation

<div style="width: max-content; color: #5c3a00; background-color: #faf1d1; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Resume evaluation</div>

### Written Examination

<div style="width: max-content; color: #0C296E; background-color: #E1EAFF; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Written test</div>

### Evaluation Passed

<div style="width: max-content; color: #0C296E; background-color: #E1EAFF; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Resume Passed</div>

### Interview

<div style="width: max-content; color: #0C296E; background-color: #E1EAFF; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Interviewing</div>

### Interview Pass

<div style="width: max-content; color: #124B0C; background-color: #D9F5D6; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Interview completed</div>

### Pending Entry

<div style="width: max-content; color: #124B0C; background-color: #D9F5D6; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Pending onboard</div>

### Have Joined

<div style="width: max-content; color: #124B0C; background-color: #D9F5D6; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Onboarded</div>

### Transfer

<div style="width: max-content; color: #1F2329; background-color: #F5F6F7; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Referred to another job</div>

### Termination

<div style="width: max-content; color: #1F2329; background-color: #F5F6F7; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Ended</div>

### Unknown

<div style="width: max-content; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle; margin-top: -2px;">Unknown</div>

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
