# Arbitration Seat and Venue in the Supreme Court of India, 2021 to 2026

# # Team
1.	Akshitha — DIVISION D (Cases #1, #5, #9, #13, #17, #21, #25, #29)
2.	Ram Sharan — DIVISION D (Cases #2, #6, #10, #14, #18, #22, #26, #30)
3.	Kritika — DIVISION D (Cases #3, #7, #11, #15, #19, #23, #27)
4.	Prateek — DIVISION D (Cases #4, #8, #12, #16, #20, #24, #28)
# # Topic
This project examines how the Supreme Court of India demarcates the juridical "seat" of arbitration (lex arbitri and exclusive supervisory court jurisdiction under Sections 2(1)(e), 2(2), 9, 11(6), 14(2), 20, 29A (4), 34, and 42) from the geographical "venue" of hearings under Section 20(3) of the Arbitration and Conciliation Act, 1996. Following BGS SGS Soma JV v. NHPC Ltd., (2020) 4 SCC 234, commercial litigants repeatedly tested whether shifting hearing locations, executing contracts across states, or naming foreign venues alters supervisory court competence. This topic interests our team because a single drafting ambiguity between "seat" and "venue" routinely triggers multi-year jurisdictional litigation across High Courts before reaching the Supreme Court.
# # How We Found the Judgments
We retrieved and verified all judgments exclusively through official Supreme Court repositories—the Digital Supreme Court Reports (e-SCR) (https://digiscr.sci.gov.in/) and the Official Supreme Court Portal (https://www.sci.gov.in/ and https://api.sci.gov.in/), excluding third-party aggregators like Indian Kanoon. We ran Boolean searches combining "Section 20", "juridical seat", "venue", "Section 42", "Section 29A (4)", and "BGS SGS Soma" for decisions delivered between September 2021 and October 2026. Out of roughly 85 initial results, we filtered out routine transfer petitions and non-speaking orders to select 30 reportable judgments substantively adjudicating seat-versus-venue conflicts, supervisory court competence, referral boundaries, or foreign-seat exclusions.
# # What the Data Shows

<img width="460" height="267" alt="image" src="https://github.com/user-attachments/assets/114a8b4c-0df7-4a70-ab80-22e9900ecde3" />

The first chart shows the annual distribution of our 30 Supreme Court decisions from 2021 to 2026, averaging 5.00 judgments per year (median 4.50, minimum 3, maximum 8, standard deviation 2.10). Litigation peaked in 2022 with 8 decisions (26.7%) and in 2024 with 7 decisions (23.3%), alongside 3 decisions in 2021, 5 in 2023, 3 in 2025, and 4 in 2026. What surprised us most was that despite BGS SGS Soma (2020) establishing a bright-line rule, seat-versus-venue appeals did not decline by 2026; instead, fresh disputes arose over whether convenient sittings in Delhi, Cuttack, or Bogota displaced contractual seats in Panchkula (BBR India, 2022), Srinagar (J&K ERA, 2026), Sundargarh (Mahanadi Coalfields, 2026), or Gujarat (Disortho S.A.S., 2025).

<img width="457" height="344" alt="image" src="https://github.com/user-attachments/assets/e2e1f445-e9c0-4140-8fba-519e6acb3217" />

The second chart breaks down dispositions across the 30 judgments: 20 appeals or petitions were Allowed (66.7%), 8 were Dismissed (26.7%), and 2 were Constitution Bench References Answered (6.7%) in Cox and Kings Ltd. v. SAP India Pvt. Ltd. (2023 INSC 1051) and Central Organisation for Railway Electrification v. M/s ECI SPIC SMO MCML (JV) (2024 INSC 857). Bench strength averaged 2.53 Judges (median 2.00, standard deviation 0.82), spanning 18 two-Judge Division Benches (60.0%), 10 three-Judge Full Benches (33.3%), and 2 five-Judge Constitution Benches (6.7%). It did not surprise us that two-thirds of the cases were allowed, as the Supreme Court consistently intervened whenever High Courts confused a convenient Section 20(3) venue with the juridical seat or conducted mini-trials at the Section 11(6) stage (SBI General Insurance v. Krish Spinning, 2024).

<img width="496" height="308" alt="image" src="https://github.com/user-attachments/assets/98b8f431-b710-4c46-97a2-bcfe2ef562d2" /> 

The third chart categorizes winning litigants across the 30 rulings: domestic private parties won 17 cases (56.7%), State governments, PSUs, and public authorities won 8 cases (26.7%), foreign private corporations won 3 cases (10.0%), and pro-arbitration references accounted for 2 cases (6.7%), yielding a 73.3% private and pro-arbitration win rate (22 of 30 cases). What surprised us was that even though State entities and PSUs lost constitutional challenges to unilateral appointment clauses in Glock Asia-Pacific (2023) and CORE (2024), PSUs still prevailed whenever contractors treated non-binding departmental circulars as arbitration agreements (Mahanadi Coalfields v. IVRCL, 2022) or claimed convenient sittings shifted a PSU's seat (Mahanadi Coalfields v. GSCO, 2026).

# # Limits

A reader should not conclude from these 30 judgments that High Courts routinely misapply Section 20 in ordinary disputes, because our dataset reflects apex-court selection bias and captures only contested appeals reaching the Supreme Court under Article 136 or Section 11(6). Moreover, procedural outcomes ("Allowed" or "Dismissed") do not indicate which party ultimately won monetary damages before the arbitral tribunal, nor can 30 cases predict outcomes in unappealed District Commercial Court proceedings under Sections 9, 29A, and 34.

# # AI-Use Disclosure

We used Claude to assist with Python statistical scripts, generating our matplotlib charts (chart1-per-year.png, chart2-outcomes.png, chart3-who-won.png), building the interactive HTML5 dashboard (index.html), and tightening one-line summaries. Every neutral citation (INSC), decision date, coram, statutory provision, and holding formatted with AI assistance was manually verified by the assigned team member against the official signed PDF judgment on api.sci.gov.in and sci.gov.in before entry into data.csv and data.xlsx.

