# FACTURES-LIGNES-DASHBOARD
This Project analyzes and visualizes invoice line data for a french based company using Powe BI. it covers revenue trends, contract performance, customer segmentation and discount impact.

## OBJECTIVES
- Analyze  invoice line a data to uncover trends and performance indicators
- Identify top contibuting and contract types
- Provide Strtegic recommendation basedrevenue insighta.
## SKILLS DEMONSTRATED
During the analysis processs, a diverse set of skills was demonstrated, including descriptive analysis aof the dataset, visualization summary and data trasformation

## TOOLS USED
Power BI|
Power Query|
Dax |

## Dataset Summary
The dataset contains invoice line information with the following important fields:
- FLIG_idf_facture: Invoice ID
- FLIG_code_produit: Product code
- FLIG_mnt_total: Total amount per line
- FLIG_remise: Discount applied
- FLIG_taux_tva: VAT amount
- FLIG_punet: Net unit price
- FLIG_type_contrat: Type of contract
- FLIG_idf_societe: Company ID (client)
- FLIG_periode_debut: Start date of the invoicing period
- FLIG_periode_fin: End date of the invoicing period
- FLIG_explicitation: Contract explanation or description
  
## DATA CLEANING & TRANSFORMATION
To ensure data reliability and data integrity of the dataset the following step wre taken
1.Column Profile
2.Duplicate Check
3.Handling missing valuea
4.Data Sorting
5.**Merged Tables**: Combined supplementary company and product metadata into the main table.

## Analysis  and Visualization
This section present the key findings derived from the interactive dashboard.
### Dashboard Preview
<img width="576" alt="Screenshot 2025-04-22 172733" src="https://github.com/user-attachments/assets/97263c6b-d7bb-470f-b845-8d59b2aaa2cc" />

1.Total FLIG_MNT_TOTAL by explication : Contract logiciel (softwarwe contracts) generated the highest revenue(7M) i.e there are the biggest driver of business while the lowest revenue is generated from  Ventes hors contract (sales  outside contract) 
<img width="571" alt="Screenshot 2025-04-22 174051" src="https://github.com/user-attachments/assets/d0530d94-81f5-4896-892e-396d2e638b11" />

2.Total FLIG_MNT_TOTAL by FLIG_type_contrat:  FLIG_type_contrat 3 dominated with the highest revenue of 7M while  FLIG_type_contrat 78 generated the lowest revenue
<img width="539" alt="Screenshot 2025-04-22 180620" src="https://github.com/user-attachments/assets/d0bdad83-8a6a-44e2-aed0-5b7385b824d5" />

3.Total FLIG_MNT_TOTAL by FLIG_PERIODE_DEBUT Month: There's a high rervenue peak in Jannuary in the start date of the invoice period
<img width="551" alt="Screenshot 2025-04-22 183600" src="https://github.com/user-attachments/assets/2ff19f82-ec81-49fa-9eac-26d7336949cc" />

4.Total FLIG_MNT_TOTAL by FLIG_PERIODE_FIN Month: There's a high rervenue peak in December in the End date of the invoice period
<img width="538" alt="Screenshot 2025-04-22 184751" src="https://github.com/user-attachments/assets/bfb6610a-9458-4ebb-95d9-16683d7bcd27" />

5.Total FLIG_MNT_TOTAL by Top 10  FLIG_code_product:Top Clients contibuting to the revenue ASSLOGWPCLIENT(1,88m), MAJBAS (1.24M), INTEGRALEPR (858K) ,HILINTEGRALE (593k), PROTECT (488k),  CTMSREVEUR (488K),  ASSLOGSERV (415K), PAX-48MOIS (372K), ASSLOGSCAN (359K), ASSLOGSTOCK(324K)
<img width="571" alt="Screenshot 2025-04-22 192406" src="https://github.com/user-attachments/assets/1b4dc1b0-79d2-4225-ad47-e310f492c06c" />

## RECOMENDATION
1.Since Contract logiciel (softwarwe contracts) generate the huighest revenue Stakeholder should focus marketing and retenttion effort on Contract logiciel. Stakeholder should explore upsell opportunities within the product line.

2.Priotize Clients like (ASSLOGWPCLIENT, MAJBAS) with loyalty, alos analyze what make them top performace and try to replicate that to the other clients
