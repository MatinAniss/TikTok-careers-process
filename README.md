# TikTok Careers Process

This is an unofficial documentation of the enum and states a TikTok careers application can represent.
https://careers.tiktok.com/position/application

## States

The order of the states have no particular importance, it is only ordered in colour. Written examination may be done before the resume evaluation.

### Resume Screening

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #5c3a00; background-color: #faf1d1; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Resume screening</div>
  </foreignObject>
</svg>

### Resume Evaluation

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #5c3a00; background-color: #faf1d1; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Resume evaluation</div>
  </foreignObject>
</svg>

### Written Examination

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #0C296E; background-color: #E1EAFF; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Written test</div>
  </foreignObject>
</svg>

### Evaluation Passed

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #0C296E; background-color: #E1EAFF; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Resume Passed</div>
  </foreignObject>
</svg>

### Interview

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #0C296E; background-color: #E1EAFF; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Interviewing</div>
  </foreignObject>
</svg>

### Interview Pass

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #124B0C; background-color: #D9F5D6; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Interview completed</div>
  </foreignObject>
</svg>

### Pending Entry

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #124B0C; background-color: #D9F5D6; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Pending onboard</div>
  </foreignObject>
</svg>

### Have Joined

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #124B0C; background-color: #D9F5D6; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Onboarded</div>
  </foreignObject>
</svg>

### Transfer

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #1F2329; background-color: #F5F6F7; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Referred to another job</div>
  </foreignObject>
</svg>

### Termination

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; color: #1F2329; background-color: #F5F6F7; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Ended</div>
  </foreignObject>
</svg>

### Unknown

<svg width="200" height="25">
  <foreignObject width="100%" height="100%">
    <div style="width: max-content; text-align: center; border-radius: 2px; padding: 1px 8px; vertical-align: middle;">Unknown</div>
  </foreignObject>
</svg>

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
