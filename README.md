FUTURE_CS_03 — API Security Risk Analysis Report


Read-only security analysis of a public REST API to identify common API security risks and vulnerabilities.
Tools Used

-Postman — API request testing and response inspection
-Browser DevTools — HTTP header and network analysis
-ReqRes API Documentation — Official API reference
-Microsoft Word — Documentation and reporting

API Tested
-Target: ReqRes Public Test API (https://reqres.in)
-Type: Public REST API for testing and learning
-Scope: Read-only requests only (GET, safe POST)

Analysis Approach
Tested API endpoints using Postman to identify security weaknesses including authentication issues, data exposure, rate limiting, authorization flaws, and input validation. Risk classified as High/Medium/Low based on potential business impact.
Risks Identified

-No authentication required (High Risk)
-Excessive data exposure (High Risk)
-Missing rate limiting (Medium Risk)
-Broken Object Level Authorization - BOLA (Medium Risk)
-Weak authentication tokens (Medium Risk)
-No input validation (Low Risk)

Assessment by Valery Vezenegho | CIN: FIT/MAR26/CS7097 | April 2026
