# Flavor Formulator - Business Logic
## Kalkulasi Formulasi Rasa

### 1. Brix (Weighted Solids)
`Total Brix = SUM(Gram_Bahan * %Solids) / Total_Weight`

### 2. pH Estimation (Weak Acid Logic)
`pH = 0.5 * (pKa - log10[Concentration_mol/L])`
*   Asam Sitrat: pKa ~3.13
*   Asam Laktat: pKa ~3.86

### 3. Costing
`Total Cost = SUM(Gram_Bahan * Price_per_Kg / 1000)`