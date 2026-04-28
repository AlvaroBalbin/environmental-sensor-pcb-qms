# QMS - 4-Layer Environmental Sensor PCB

Quality Management System for the independent 4-layer environmental sensor PCB project (Arduino Nano ESP32 carrier board).

**Student ID:** ab4647 vlgg20 lh2640

**Project:** EE22005 Engineering Practice and Design - Synthesis Portfolio  
**Date:** March 2026

## QMS Folder Structure

```
QMS/
  01_Feasibility/
      QMS-FS-001_DD-Matrix_v1.0.docx
  02_Design/
      (KiCad schematic and layout files managed separately)
  03_Testing/
      Protocols/
          QMS-TP-VR-001_TestProtocol_VoltageRegulation_v1.0.docx
          QMS-TP-SI-001_TestProtocol_SignalIntegrity_v1.0.docx
      Results/
          QMS-TR-VR-001_TestResults_VoltageRegulation_v1.0.docx
          QMS-TR-SI-001_TestResults_SignalIntegrity_v1.0.docx
  04_Management/
      QMS-NP-001_NamingProcedure_v1.0.docx
      QMS-FL-001_FileList_v1.0.xlsx
```

## File Naming Convention

All files follow the format:

```
QMS-[TYPE]-[ID]_[Description]_v[Major].[Minor].docx
```

| Code | Type | Description |
|------|------|-------------|
| FS   | Feasibility Study | D&D matrices, choice matrices |
| TP   | Test Protocol | Test procedures and pass criteria |
| TR   | Test Results | Recorded test outcomes |
| NP   | Naming Procedure | File naming convention document |
| FL   | File List | Master list of all QMS documents |

## Version Control

- Major version change (v1.0 to v2.0): structural changes, added/removed tests, significant revision
- Minor version change (v1.0 to v1.1): corrections, formatting, clarifications
- All changes tracked via Git commit history

## Continuous Improvement

The QMS is maintained through version-controlled document updates. Each document includes a revision history table. The Git commit log provides an additional layer of change traceability across the full project.
