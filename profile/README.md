# LINKSCRAP

> Open-source tool for LinkedIn reconnaissance and OSINT.

## Tools

### [LinkedIn2Email](https://github.com/LINKSCRAP/LinkedIn2Email)
Modernized fork of [initstring/linkedin2username](https://github.com/initstring/linkedin2username).  
Extracts employees from a LinkedIn company page and generates likely email/username patterns.

**Key improvements over the original:**
- **Playwright** instead of Selenium — faster, more reliable automation
- **httpcloak** instead of requests — TLS fingerprint spoofing to mimic real browser handshakes
- **Auto-login** via `.env` with headless → visible browser fallback for 2FA/captcha

```bash
pip install -r requirements.txt && playwright install chromium
python3 main.py -c TARGET_COMPANY -n company.com
```
<p align="center"> <img src="https://github.com/LINKSCRAP/.github/blob/main/profile/arq.png"/> </p>

---

*Use responsibly. Only for legitimate purposes, in compliance with applicable law and LinkedIn's ToS.*

