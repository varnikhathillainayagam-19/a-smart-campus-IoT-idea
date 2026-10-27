# Smart-Campus Air Quality IoT - Final Submission Pack
Use case: classroom air quality (CO2, PM2.5, temperature, humidity). Audience: college administration and student innovation teams.
**All data is simulated. No real devices, people or campus networks were used or tested.**

| Required item | File |
|---|---|
| Research report | 01_Research_Report.docx |
| IoT design and security checklist | 02_IoT_Design_and_Security_Checklist.docx |
| Problem statement and architecture | 03_Problem_Statement_and_Architecture.docx |
| Simulation code (+ data, charts) | 04_simulation/simulate_air_quality.py, out/ |
| Diagram and risk table | 05_Diagram_and_Risk_Table.docx, 05_diagram_and_risk/ (PNG, CSV, generator) |
| Quiz and answer key | 06_Quiz_and_Answer_Key.docx |
| Presentation (6 slides) | 07_Pitch_Deck.pptx |
| Automation script | 08_automation_script/daily_summary.py (+ sample outputs) |
| Prompt library | 09_Prompt_Library.docx |
| Verification report | 10_Verification_Report.docx |
| Before/after analysis | 11_Before_After_Analysis.docx |
| Final demo | 12_final_demo/run_demo.py, DEMO_GUIDE.md |

Run: `pip install -r requirements.txt` then `python 12_final_demo/run_demo.py`.

## Before you submit (things only you can do)
1. Run the "To run" prompts in at least 3 more free tools (e.g. Perplexity, NotebookLM, Gemini, ChatGPT, Gamma) so you meet the 4-tool and 2-research-tool requirement; paste outputs into the log in 09_Prompt_Library.docx and complete the probe table in 10_Verification_Report.docx.
2. Resolve every NOT VERIFIED item in the Verification Report (CO2 threshold, sensor datasheets, DPDP Act, CO2-per-person figure).
3. Open the primary sources (OWASP, NIST IR 8259 Rev. 1, OASIS MQTT) and add access dates to the citations.
4. Optional: mirror one sensor in Wokwi and add a screenshot.
