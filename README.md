# The epidemiology, impact, and outcomes of idiopathic inflammatory myopathies
Codelists, exposure/outcome definitions and algorithms for "The epidemiology, impact, and outcomes of idiopathic inflammatory myopathies" study by Momentum Data.

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification

### Idiopathic inflammatory myopathy (IIM)
IIM will be identified and defined using [clinical diagnosis code set](https://github.com/MomentumData/Momentum-Data-Codelists/blob/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/IIM%20(Idiopathic%20Inflammatory%20Myopathies)/idiopathic_inflammatory_myopathies_ICD10_code_set.csv) (_Myositis, unspecified only to be considered if associated to an interstitial lung disease code (J84.1, J84.0, and J99.1)_) made in secondary care using ICD-10 code set developed in recent research by the study team[^1]

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
People identified with a diagnosis code for [haematological cancer]() in primary or secondary care.

### Solid cancers
People identified with a diagnosis code for [solid cancer]() in primary or secondary care.

### Interstitial lung disease (ILD)
People identified with a diagnosis code for [ILD]() in primary or secondary care.

### IIM associated ILD
People identified with a diagnosis code for [ILD]() in primary or secondary care.

### Pulmonary hypertension
People identified with a diagnosis code for [ILD]() in primary or secondary care.

### Dysphagia
People identified with a diagnosis code for [ILD]() in primary or secondary care.

### Myocarditis
People identified with a diagnosis code for [ILD]() in primary or secondary care.

### Depression

### Anxiety

### Idiopathic inflammatory myopathy symptoms














# References
[^1]: Hannah JR, Gordon PA, Galloway J, et al. Validation of methods to identify people with idiopathic inflammatory myopathies using hospital episode statistics. Rheumatol Adv Pract 2022;6(3):rkac102. doi: 10.1093/rap/rkac102 [published Online First: 20221202]



























