# e-beyanname

SAP S/4HANA ABAP package for Turkish electronic tax declarations (e-Beyanname).  
Repository: `34267094342-e-beyanname` | Package: `ZETR_TAX`

---

## Package Contents

This repository is managed via SAP gCTS and contains **1,037** ABAP repository objects across 26 object types.

| # | Type | Count | Description |
|---|------|------:|-------------|
| 1 | DDLS | 100 | CDS Data Definition Language sources (CDS views) |
| 2 | SICF | 74 | SAP Internet Communication Framework services |
| 3 | DTEL | 73 | Data elements |
| 4 | SUSH | 69 | Authorization object assignments |
| 5 | BDEF | 63 | Behavior definitions (RAP business objects) |
| 6 | SIA6 | 45 | OData service arrangements |
| 7 | SIA7 | 44 | OData service arrangements (V4) |
| 8 | TABL | 43 | Database tables / structures |
| 9 | CLAS | 42 | ABAP classes (including RAP behavior implementations) |
|10 | UIAD | 41 | UI adaptations |
|11 | WAPA | 37 | BSP / Fiori web applications |
|12 | SMIM | 37 | MIME objects |
|13 | DDLX | 36 | CDS view extensions / metadata extensions |
|14 | SRVB | 35 | OData service bindings |
|15 | SCO2 | 35 | SAP Cloud Objects |
|16 | SRVD | 34 | OData service definitions |
|17 | OA2S | 34 | OAuth 2.0 configuration scopes |
|18 | IWVB | 34 | OData vocabulary-based annotations |
|19 | IWSV | 34 | OData service versions |
|20 | IWSG | 34 | OData service groups |
|21 | IWOM | 34 | OData model sources |
|22 | IWMO | 34 | OData model definitions |
|23 | DOMA | 20 | Domains |
|24 | SIA1 | 3 | OData communication arrangements |
|25 | G4BA | 1 | Fiori app descriptor |
|26 | DEVC | 1 | Development package (`ZETR_TAX`) |

---

## Functional Areas

### KDV1 — VAT Return (Katma Değer Vergisi Beyannamesi 1)
Objects: `ZTAX_*_VAT1_*`  
Covers company codes, condition types, delivery services, withholding process types, withholding rates, XML tags, refraction definitions, and declaration/TEV reports.

### KDV2 — VAT Withholding Return (Katma Değer Vergisi Beyannamesi 2)
Objects: `ZTAX_*_VAT2_*`  
Covers calculation rules, company codes, KES reports, payment types, processing fields/types, refraction definitions, and declaration reports.

### BRF — Brief / Summary Declarations
Objects: `ZTAX_*_BRF_*`  
Covers company codes, document lists, document types, payment records, refraction definitions, seller definitions, trade registry, and work place data.

### GIB — Revenue Administration (Gelir İdaresi Başkanlığı)
Objects: `ZTAX_*_GIB_*`  
Integration objects for submitting declarations to the Turkish Revenue Administration.

### Common / Shared
Shared objects for period information, company info, file paths, tax conditions, and versioning.

---

## Repository Configuration

```json
{
  "name": "34267094342-e-beyanname",
  "repositoryLayout": {
    "format": "json",
    "formatVersion": "6",
    "metaInformation": ".gctsmetadata/"
  }
}
```

**SAP System:** SAP S/4HANA Cloud  
**gCTS Endpoint:** `https://api.github.com`  
**Namespace:** `/0CUST/`  
**Delivery Unit:** `ZPARTNER`
