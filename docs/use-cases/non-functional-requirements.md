# Non-Functional Requirements

## FURPS Categories

### 1. Functionality
**NFR-01:** The system shall support JPG and PNG image formats for photo upload.
**Measurement:** Only files with .jpg, .jpeg, .png extensions are accepted.

### 2. Usability
**NFR-02:** New users shall be able to complete registration and get first recommendation within 5 minutes.
**Measurement:** Time from sign-up to first 3 outfit recommendations ≤ 300 seconds.

### 3. Reliability
**NFR-03:** The AI recommendation service shall have 99% uptime per month.
**Measurement:** Downtime ≤ 7.2 hours per 30-day period.

### 4. Performance
**NFR-04:** Outfit recommendations shall be generated and displayed within 10 seconds.
**Measurement:** Response time from "Get Outfit Ideas" click to display ≤ 10s for 95% of requests.

### 5. Supportability
**NFR-05:** The system shall be deployable to web and mobile browsers without additional plugins.
**Measurement:** Runs on Chrome, Safari, Firefox latest 2 versions on desktop and mobile.