
# Event Modelling


## Create Objective Slice
- C: CreateObjective
    - name
    - description
- E: ObjectiveCreated

## View Objective
- V: Show Objective by Id

## Add KeyResult to Objective
- C: AddKeyResult
    - objectiveId
    - name
    - description
    - scale
        - TBD
        - type: numeric, percentage, binary
        - data {}
- E: KeyResultAdded

## Map Dependencies
- C: 





## List all objectives
- V: List all objectives