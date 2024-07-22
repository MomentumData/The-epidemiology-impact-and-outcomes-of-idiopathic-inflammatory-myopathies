# The epidemiology, impact, and outcomes of idiopathic inflammatory myopathies
Codelists, exposure/outcome definitions and algorithms for "The epidemiology, impact, and outcomes of idiopathic inflammatory myopathies" study by Momentum Data.

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification

### Idiopathic inflammatory myopathy (IIM)
IIM will be identified and defined using [clinical diagnosis code set]([https://github.com/MomentumData/Momentum-Data-Codelists/blob/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/idiopathic_inflammatory_myopathies_ICD10_code_set.csv](https://github.com/MomentumData/Momentum-Data-Codelists/blob/main/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/idiopathic_inflammatory_myopathies_ICD10_code_set.csv)) (_Myositis, unspecified only to be considered if associated to an interstitial lung disease code (J84.1, J84.0, and J99.1)_) made in secondary care using ICD-10 code set developed in recent research by the study team[^1]

For the full list of codes:
- [Adult dermatomyositis](https://github.com/MomentumData/Momentum-Data-Codelists/blob/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/Adult%20Dermatomyositis/adult_dermatomyositis_ICD10.csv)
- [Juvenile dermatomyositis](https://github.com/MomentumData/Momentum-Data-Codelists/blob/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/Juvenile%20Dermatomyositis/juvenile_dermatomyositis_ICD10.csv)
- [Polymyositis](https://github.com/MomentumData/Momentum-Data-Codelists/blob/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/PM%20(Polymyositis)/polymyositis_ICD10.csv)
- [Inclusion Body Myositis](https://github.com/MomentumData/Momentum-Data-Codelists/blob/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/IBM%20(Inclusion%20Body%20Myositis)/inclusion_body_myositis_ICD10.csv)

To increase the specificity of the case definition, people diagnosed with idiopathic inflammatory myopathies wioth concominant diagnoses of [rheumatoid arthritis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/RA%20(Rheumatoid%20Arthritis)), [psoriatic arthritis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/PsA%20(Psoriatic%20Arthritis)), [ankylosing spondylitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/AS%20(Ankylosing%20Spondylitis)), or [systemic lupus erythematous](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/SLE%20(Systemic%20Lupus%20Erythematosus)) will be excluded.

Additional case identification based on underlying subtype will be performed using codes recorded in primary care to inform the final study case definition. Full list of codes can be found below:
- [Dermatomyositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/DM%20(Dermatomyositis))
- [Inclusion body myositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/IBM%20(Inclusion%20Body%20Myositis))
- [Inflammatory myopathy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/Inflammatory%20Myopathy)
- [Juvenile dermatomyositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/Juvenile%20Dermatomyositis)
- [Myositis - unspecified](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/Myositis%20-%20Unspecified)
- [Other dermatomyositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/Other%20Dermatomyositis)
- [Other myositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/Other%20Myositis)
- [Polymyositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/PM%20(Polymyositis))
- [Paraneoplastic dermatomyositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/Paraneoplastic%20Dermatomyositis)
- [Paraneoplastic polymyositis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/Paraneoplastic%20Polymyositis)

### Systemic lupus erythematous (SLE)
- People identified with a diagnosis code for [SLE](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/SLE%20(Systemic%20Lupus%20Erythematosus)) in primary or secondary care.

### Rheumatoid arthritis (RA)
- People identified with a diagnosis code for [RA](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/RA%20(Rheumatoid%20Arthritis)) in primary or secondary care, and no alternative diagnosis for [psoriatic arthritis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/PsA%20(Psoriatic%20Arthritis)) or [ankylosing spondylitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/AS%20(Ankylosing%20Spondylitis)).

### Haematological cancers
People identified with a diagnosis code for [haematological cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Haematological%20Cancer) in primary or secondary care.

### Solid cancers
People identified with a diagnosis code for [solid cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Solid%20Cancer) in primary or secondary care.

### Interstitial lung disease (ILD)
People identified with a diagnosis code for [ILD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Solid%20Cancer) in primary or secondary care.

### IIM associated ILD
People identified with a diagnosis code for [IIM associated ILD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/ILD%20(Interstitial%20Lung%20Disease)/IIM%20Associated%20ILD) in primary or secondary care.

### Pulmonary hypertension
People identified with a diagnosis code for [pulmonary hypertension](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/ILD%20(Interstitial%20Lung%20Disease)/IIM%20Associated%20ILD) in primary or secondary care.

### Dysphagia
People identified with a diagnosis code for [dysphagia](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Dysphagia) in primary or secondary care.

### Myocarditis
People identified with a diagnosis code for [myocarditis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Myocarditis) in primary or secondary care.

### Depression
Any of:
- People identified with a diagnosis code for [recurrent depressive disorder](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/RDD%20(Recurrent%20Depressive%20Disorder)) in primary care.
- People identified with a diagnosis code for [depressive episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Depressive%20Episodes) **AND** any coded depression treatment* after 365 days in primary care.

### Anxiety
People identified with a diagnosis code for [anxiety episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Anxiety%20Episode) **AND** within 6 months any coded anxiety treatment** in primary care.

*List of depression treatments:
- [Selective Seratonin Reuptake Inhibitors (SSRIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/SSRIs%20(Selective%20Serotonin%20Reuptake%20Inhibitors))
- [Tricyclic Antidepressants (TCAs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/TCAs%20(Tricyclic%20Antidepressants))
- [Monoamine Oxidase Inhibitors (MAOIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/MAOIs%20(Monoamine%20Oxidase%20Inhibitors))
- [Counselling](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Counselling)
- [Psychotherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Psychotherapy)
- [Cognitive Behavioural Therapy (CBT)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/CBT%20(Cognitive%20Behaviour%20Therapy))

*List of anxiety treatments:
- [SSRIs](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/SSRIs%20(Selective%20Serotonin%20Reuptake%20Inhibitors))
- [Anxiolytics](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Anxiolytics)
- [Counselling](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Counselling)
- [Psychotherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Psychotherapy)
- [CBT](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/CBT%20(Cognitive%20Behaviour%20Therapy))

### Muscle weakness
People identified with a diagnosis code for [muscle weakness](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Muscle%20Weakness) in primary care.

### Joint pain
People identified with a diagnosis code for [joint pain](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Joint%20Pain) in primary care.

### Fatigue
People identified with a diagnosis code for [fatigue](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Fatigue) in primary care.

### Elevated Alanine Transaminase (ALT)
People identified with a diagnosis code for [elevated ALT](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Measurements/Elevated%20Alanine%20Transaminase%20(ALT)) in primary care.


# References
[^1]: Hannah JR, Gordon PA, Galloway J, et al. Validation of methods to identify people with idiopathic inflammatory myopathies using hospital episode statistics. Rheumatol Adv Pract 2022;6(3):rkac102. doi: 10.1093/rap/rkac102 [published Online First: 20221202]



























