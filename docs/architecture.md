# AuthentID - eMRTD Chip Identity Verification - architecture

Read the eMRTD chip itself, take the portrait the issuing authority stored there, and match it against a live capture. Verification then rests on data signed by the issuer rather than on the printed surface, which is the part a forger controls.

## Components

### Chip reading

eMRTD data group extraction

### Document validation

Certificate and integrity checking

### Face matching

Stored portrait against live capture

### Test suite

Verification coverage over document handling

## Stack

| Layer | Technology |
| --- | --- |
| Language | Python |
| Standards | ICAO eMRTD data groups |
| Biometrics | Face matching pipeline |
| Security | Certificate validation |

Designed and implemented by Muhammad Tanveer - Full-Stack AI Automation Engineer.