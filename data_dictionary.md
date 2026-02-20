# Data Dictionary

Only variables used in analysis are documented. Additional fields in raw tables were excluded during preprocessing.

---

## Screening Table (IOBP2DiabScreening.txt)

**PtID**
Unique patient identifier used for table merging.

**DiagAge**
Age at diagnosis of Type 1 Diabetes.

**Sex**
Participant biological sex.

**CGMUseDevice**
Continuous glucose monitoring device used prior to study enrollment.

---

## Local HbA1c Table (IOBP2DiabLocalHbA1c.txt)

**PtID**
Unique patient identifier.

**HbA1cTestRes** 
Baseline HbA1c value collected prior to treatment initiation.

---

## Sample Results Table (STASampleResults.txt)

**PtID**
Unique patient identifier.

**ResultName** 
Laboratory test identifier. Used to filter HbA1c measurements (GLYHB).

**Visit** 
Study visit timing associated with laboratory collection.

**Value** 
Laboratory result value. Used to derive final Week 13 HbA1c.

---

## Treatment Table (IOBP2DiabTreatment.txt)

**PtID**
Unique patient identifier.

**PumpType** 
Insulin delivery system used during the trial. Recoded into iLet vs Other treatment groups for analysis.