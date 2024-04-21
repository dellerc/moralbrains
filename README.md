# moralbrains
for MB
graph TB
  subgraph Hypothesis 1.1: Insula Activation
    subgraph NT[Neurotypical Group]
      NT_ESS[Essentialist Labels] --> NT_NON[Non-Essentialist Labels]
    end
    subgraph ASD[ASD Group]
      ASD_ESS[Essentialist Labels] --> ASD_NON[Non-Essentialist Labels]
    end
    NT_ESS --> NT_NON
    ASD_ESS --> ASD_NON
    NT_ESS --> |Higher Activation| ASD_ESS
    NT_NON --> |Similar Activation| ASD_NON
  end

  subgraph Hypothesis 1.2: Insula Activation vs. Empathic Abilities
    subgraph NT_CORR[Neurotypical Group]
      NT_INSULA[Insula Activation] --> |Strong Positive Correlation| NT_EMPATHY[Empathic Abilities]
    end
    subgraph ASD_CORR[ASD Group]
      ASD_INSULA[Insula Activation] --> |Weak Positive Correlation| ASD_EMPATHY[Empathic Abilities]
    end
    NT_INSULA --> NT_EMPATHY
    ASD_INSULA --> ASD_EMPATHY
    NT_CORR --> |Stronger Correlation| ASD_CORR
  end
