# CrowdStrike Security Alert Report Template

## Executive Summary

**Alert ID:** [ALERT_ID]  
**Status:** [Severity Level]  
**Detection Type:** [Detection Category]  
**Date:** [Investigation Date]  
**Risk Level:** [Risk Assessment]

---

## Device Information

| Property | Details |
|----------|---------|
| **Hostname** | [HOSTNAME] |
| **Device ID** | [DEVICE_ID] |
| **User** | [USERNAME] |
| **Platform** | [OS_VERSION] |
| **Product Type** | [DEVICE_TYPE] |
| **Local IP** | [LOCAL_IP] |
| **External IP** | [EXTERNAL_IP] |

---

## Threat Assessment

### Severity Metrics
- **Current Severity:** [SEVERITY] ([SEVERITY_SCORE]/100)
- **Maximum Severity:** [MAX_SEVERITY]
- **Confidence Level:** [CONFIDENCE_LEVEL]
- **Classification:** [CLASSIFICATION]

### Detection Details
**Alert Link:** [View in CrowdStrike Falcon]([FALCON_LINK])

**Detection Reason:** [DETECTION_REASON]

---

## File Analysis

### Basic Information
| Property | Value |
|----------|-------|
| **Filename** | [FILENAME] |
| **Location** | [FILE_PATH] |
| **SHA256** | [SHA256_HASH] |
| **Command Line** | [COMMAND_LINE] |

### VirusTotal Analysis
| Property | Value |
|----------|-------|
| **Detection Score** | [VT_SCORE]/100 |
| **VT Link** | [View on VirusTotal]([VT_LINK]) |
| **File Creation Date** | [CREATION_DATE] |
| **First Submission** | [FIRST_SUBMISSION] |
| **Last Submission** | [LAST_SUBMISSION] |
| **File Tags** | [FILE_TAGS] |

### Analysis Summary
- [SIGNATURE_STATUS] **Digitally Signed:** [SIGNATURE_INFO]
- [VT_STATUS] **VT Score:** [VT_ANALYSIS]
- [DETECTION_STATUS] **Detection Confidence:** [CONFIDENCE_INFO]
- [SOFTWARE_INFO] **Associated Software:** [SOFTWARE_NAME]
- [LOCATION_INFO] **File Location:** [LOCATION_CONTEXT]

---

## Risk Assessment

### Likelihood: **[LIKELIHOOD_LEVEL]**
[LIKELIHOOD_REASONING]

### Impact: **[IMPACT_LEVEL]**
[IMPACT_REASONING]

### Overall Risk: **[OVERALL_RISK]**

---

## Recommended Actions

### Immediate Actions
1. ✅ **Review with User:** [USER_VERIFICATION_STEPS]

2. 🔍 **Additional Investigation:**
   - [INVESTIGATION_STEP_1]
   - [INVESTIGATION_STEP_2]
   - [INVESTIGATION_STEP_3]

### Follow-up Actions
- [ ] **If Legitimate:** 
  - [LEGITIMATE_ACTION_1]
  - [LEGITIMATE_ACTION_2]
  - [LEGITIMATE_ACTION_3]

- [ ] **If Malicious:**
  - [MALICIOUS_ACTION_1]
  - [MALICIOUS_ACTION_2]
  - [MALICIOUS_ACTION_3]

### Monitoring
- [MONITORING_ITEM_1]
- [MONITORING_ITEM_2]
- [MONITORING_ITEM_3]

---

## Additional Context

### About [SOFTWARE_NAME]
[SOFTWARE_BACKGROUND_INFO]

### Detection Context
[DETECTION_CONTEXT_INFO]

---

## Investigation Notes

**Next Steps:**
1. [NEXT_STEP_1]
2. [NEXT_STEP_2]
3. [NEXT_STEP_3]

**Status:** [CURRENT_STATUS]

---

*Report Generated for Alert ID: [ALERT_ID]*  
*Classification: [CLASSIFICATION_LEVEL]*

---

## Usage Instructions

This template should be used for all CrowdStrike security alerts. Replace all placeholders in [BRACKETS] with actual values from the alert.

### Field Descriptions

**Alert ID:** Unique identifier from CrowdStrike  
**Severity Level:** Low/Medium/High/Critical  
**Detection Category:** Type of threat (Malware, PUP, Adware, etc.)  
**Risk Assessment:** Use emojis: ✅ (Low), ⚠️ (Medium), ⛔ (High), 🔴 (Critical)  

**Severity Score:** Numerical value 0-100  
**Confidence Level:** Detection confidence score  

**VT Score:** VirusTotal detection ratio (X/100)  
**Status Indicators:**
- ✅ = Positive/Good indicator
- ⚠️ = Caution/Warning
- ❌ = Negative/Bad indicator
- ℹ️ = Informational

**Risk Levels:** LOW, MEDIUM, HIGH, CRITICAL

### Color Coding Guide
Use emojis to quickly identify risk levels in reports for visual scanning.
