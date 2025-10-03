# CrowdStrike Security Alert Report

## Executive Summary

**Alert ID:** bcf6f8a1ca6d4ecb88d67531991f6a23  
**Status:** Low Severity Detection  
**Detection Type:** Adware/PUP (Potentially Unwanted Program)  
**Date:** Current Investigation  
**Risk Level:** ⚠️ Low (Requires Investigation)

---

## Device Information

| Property | Details |
|----------|---------|
| **Hostname** | AMEXGBT-J7N7O9G |
| **Device ID** | 03826e7568354ebf8560915d405bf985 |
| **User** | rselim1 |
| **Platform** | Windows 11 |
| **Product Type** | Workstation |
| **Local IP** | 10.241.20.249 |
| **External IP** | 89.202.27.118 |

---

## Threat Assessment

### Severity Metrics
- **Current Severity:** Low (30/100)
- **Maximum Severity:** 30
- **Confidence Level:** 30
- **Classification:** Adware/PUP - Low Confidence Detection

### Detection Details
**Alert Link:** [View in CrowdStrike Falcon](https://falcon.crowdstrike.com/activity-v2/detections/bcf6f8a1ca6d4ecb88d67531991f6a23:ind:03826e7568354ebf8560915d405bf985:197146141349-5760-48255760?_cid=g03000vskyuepepnhhjjzr6b4kpohpzu)

**Detection Reason:** This file meets the Adware/PUP Anti-malware ML algorithm's low-confidence threshold.

---

## File Analysis

### Basic Information
| Property | Value |
|----------|-------|
| **Filename** | ZoomInfoContactContributor (1).exe |
| **Location** | C:\Users\rselim1\Downloads\ |
| **SHA256** | 2724caa0ff4d6fe3b40743105b2d5a2e4781b9eccfc637c07a6f21fe09d3f669 |
| **Command Line** | "C:\Users\rselim1\Downloads\ZoomInfoContactContributor (1).exe" |

### VirusTotal Analysis
| Property | Value |
|----------|-------|
| **Detection Score** | 3/100 (Very Low) |
| **VT Link** | [View on VirusTotal](https://www.virustotal.com/gui/file/2724caa0ff4d6fe3b40743105b2d5a2e4781b9eccfc637c07a6f21fe09d3f669/detection) |
| **File Creation Date** | Sat, 5 Dec 2009 22:50:52 |
| **First Submission** | Tue, 12 Nov 2024 18:22:22 |
| **Last Submission** | Wed, 6 Aug 2025 18:29:52 |
| **File Tags** | overlay, signed, checks-user-input, peexe |

### Analysis Summary
- ✅ **Digitally Signed:** File appears to be signed (legitimate software indicator)
- ✅ **Low VT Score:** Only 3 out of 100 vendors flagged this file
- ⚠️ **Low Confidence Detection:** CrowdStrike ML algorithm detected at low confidence threshold
- ℹ️ **ZoomInfo Software:** Appears to be related to ZoomInfo Contact Contributor application
- ℹ️ **User Downloads Folder:** File located in user's Downloads directory

---

## Risk Assessment

### Likelihood: **LOW**
- Very low VirusTotal detection rate (3/100)
- File is digitally signed
- Associated with legitimate software (ZoomInfo)
- Low confidence ML detection

### Impact: **LOW**
- Classified as Adware/PUP (not malware)
- Workstation environment
- Single user affected

### Overall Risk: **LOW**

---

## Recommended Actions

### Immediate Actions
1. ✅ **Review with User:** Contact rselim1 to verify:
   - Did they intentionally download ZoomInfo Contact Contributor?
   - Is this application needed for business purposes?
   - Were they expecting this installation?

2. 🔍 **Additional Investigation:**
   - Check if ZoomInfo Contact Contributor is approved software
   - Verify the application's legitimacy with ZoomInfo official sources
   - Review user's other recent downloads and activities

### Follow-up Actions
- [ ] **If Legitimate:** 
  - Document as approved software
  - Consider adding to allowlist if organization uses ZoomInfo
  - Mark alert as false positive
  - Close ticket

- [ ] **If Unwanted:**
  - Quarantine or remove the file
  - Run full endpoint scan
  - Educate user on download policies
  - Document incident

### Monitoring
- Monitor device for any unusual behavior
- Watch for additional alerts from this device
- Track for any network anomalies from 10.241.20.249

---

## Additional Context

### About ZoomInfo Contact Contributor
ZoomInfo Contact Contributor is a legitimate browser extension/application from ZoomInfo Technologies LLC, a business intelligence company. However:
- Sometimes flagged as PUP due to data collection practices
- May be installed without full user awareness
- Should be verified against company software policies

### Detection Context
- This is an ML-based detection at **low confidence**
- The file has been in circulation since 2009
- Recent submissions to VirusTotal suggest ongoing use
- Minimal vendor consensus on malicious nature

---

## Investigation Notes

**Next Steps:**
1. Verify user intent and business need
2. Confirm against company software policy
3. Make disposition decision based on findings

**Status:** Awaiting User Verification

---

*Report Generated for Alert ID: bcf6f8a1ca6d4ecb88d67531991f6a23*  
*Classification: Security Investigation - Low Priority*
