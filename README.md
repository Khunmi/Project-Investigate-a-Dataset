
# Project- Investigate a Dataset
## by Bukunmi Adebanjo


## Dataset

This dataset collects information from 100k medical appointments in Brazil and is focused on the
question of whether or not patients show up for their appointment. A number of characteristics
about the patient are included in each row.‘ScheduledDay’ tells us on what day the patient setup their appointment.‘Neighborhood’ indicates the location of the hospital.‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família:

        Variable                Data_ Type
    1. PatientId                   float64
    2. Appointment                 IDint64
    3. Gender                       object
    4. ScheduledDay                 object
    5. AppointmentDay               object
    6. Age                           int64
    7. Neighbourhood                object
    8. Scholarship                   int64
    9. Hipertension                  int64
    10. Diabetes                     int64
    11. Alcoholism                   int64
    12. Handcap                      int64
    13. SMS_received                 int64
    14. No-show                     object

The dataset was provided by Udacity

## Questions for Analysis
    1. What age ranges are more likely to honor appointments as well as the ages that most likely wouldn't?
    2. Does SMS prompts play an important role in appoinment showup rates?
    3. What percentage of males and females are enrolled in welfare programs?

## Summary of Findings

Investigation shows through question one that according to the data provided, people who are middleaged(35 to 41) tend to honor appointments more. Although slightly younger observations were highlighted in the male category. Question two investigated the influence of SMS prompts on attendance of appiontment. Analysis shows that SMS prompts do not neccessarily affect the percentage of people that honored their appointments. Lastly, wellfare enrollment distribution amongst gender was investigated and analysis revealed that a lot lesser percentage of men are enrolled in wellfare programmes as opposed to women. However, there is a generally low enrolment rate for accross the dataset.


