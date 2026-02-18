# mailcheck.tools

**Kostenlose E-Mail-Security-Analyse fuer europaeische Domain-Inhaber.**

Free email security analysis for European domain owners.

---

### Was ist mailcheck.tools?

mailcheck.tools prueft die E-Mail-Sicherheit deiner Domain — transparent,
kostenlos, ohne Tracking. SPF, DKIM, DMARC, DANE, MTA-STS, TLS und mehr.

- Kein Account noetig fuer den Schnellcheck
- Keine Werbung, keine versteckten Kosten
- Offene Testregeln — pruefe selbst wie wir bewerten
- Fokus auf europaeische Standards und Regulierungen (BSI, NIS-2)

### What is mailcheck.tools?

mailcheck.tools checks the email security posture of your domain —
transparent, free, no tracking. SPF, DKIM, DMARC, DANE, MTA-STS, TLS
and more.

- No account required for a quick check
- No ads, no hidden costs
- Open test rules — verify how we score
- Focus on European standards and regulations (BSI, NIS-2)

---

### Status

mailcheck.tools befindet sich in aktiver Entwicklung.
Die Repositories werden veroeffentlicht, sobald die erste Version live geht.

mailcheck.tools is under active development.
Repositories will be published when the first version goes live.

---

### Architektur / Architecture

| Component | Description |
|-----------|-------------|
| **scan-engine** | Go API + analysis library — DNS, SMTP, TLS checks |
| **mailcheck-web** | Public frontend at mailcheck.tools |
| **test-catalog** | Open test definitions, scoring rules, compliance profiles (YAML) |

---

### Prinzipien / Principles

| DE | EN |
|----|-----|
| Kostenlos und werbefrei fuer alle | Free and ad-free for everyone |
| Transparente Testregeln (Open Source) | Transparent test rules (open source) |
| Datensparsam — kein Tracking, kein Account-Zwang | Data-minimal — no tracking, no forced accounts |
| Europaeisch — gehostet in der EU, EU-Regulierungen im Fokus | European — hosted in the EU, EU regulations in focus |
| Unabhaengig — kein Venture Capital, kein Konzern | Independent — no venture capital, no corporation |

---

> Primary repository: [Codeberg](https://codeberg.org/mailcheck-tools)
> GitHub is a read-only mirror.

**mailcheck.tools** is part of MSCP (Mail Security Compliance Platform).

License: [EUPL-1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12) (Code) | [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/) (Test Rules) | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) (Docs)

---
*Last updated: 2026-02-18*
