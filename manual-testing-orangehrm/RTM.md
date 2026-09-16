# 🗺️ Requirements Traceability Matrix (RTM)

| Requirement ID | Business Requirement Description | Associated Test Case ID(s) | Test Execution Status |
| :--- | :--- | :--- | :--- |
| **REQ-UM-01** | System shall allow Admins to create new system users with assigned roles[cite: 1]. | TC_UM_001, TC_UM_010 | **PASS** |
| **REQ-UM-02** | Usernames must be unique and between 5 and 40 characters in length[cite: 1]. | TC_UM_002, TC_UM_003, TC_UM_004 | **PASS** |
| **REQ-UM-03** | System must sanitize input fields to protect against script injections[cite: 1]. | TC_UM_005, TC_UM_006 | **PASS** |
| **REQ-UM-04** | Disabled user accounts must be blocked from authenticating[cite: 1]. | TC_UM_008 | **PASS** |
| **REQ-UM-05** | Inactive user sessions must terminate mid-action upon expiration[cite: 1]. | TC_UM_009 | **PASS** |
| **REQ-LA-01** | Admins shall allocate leave entitlements between 0.01 and 365 days[cite: 1]. | TC_LA_001, TC_LA_002, TC_LA_003, TC_LA_004 | **PASS** |
| **REQ-LA-02** | System shall prevent submission of overlapping leave dates for an employee[cite: 1]. | TC_LA_006 | **PASS** |
| **REQ-LA-03** | State transitions (Pending $\rightarrow$ Approved/Cancelled) must update employee balance[cite: 1]. | TC_LA_007, TC_LA_008 | **PASS** |
| **REQ-LA-04** | Restricted administrative portals must enforce role-based URL protection[cite: 1]. | TC_LA_010 | **PASS** |
