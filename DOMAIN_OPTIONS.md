# Opzioni economiche per il dominio

Verificato il 14 aprile 2026.

## Raccomandazione

Per un sito accademico personale, i nomi migliori sono:

- `fabioangei.it`
- `fabioangei.com`
- `fabioangei.eu`

Se `fabioangei.it` e' disponibile, sceglierei quello: e' professionale, leggibile in Italia, e facile da ricordare. Se vuoi una presenza piu internazionale, sceglierei `.com`.

## Registrar economici

| Registrar | Quando conviene | Note |
| --- | --- | --- |
| Aruba | `.it` economico, interfaccia italiana, DNS semplice | Il piano solo dominio parte da prezzo promozionale il primo anno e rinnova da 11,99 EUR + IVA/anno. Non aggiungere hosting se non ti serve email o altro. |
| Cloudflare Registrar | Rinnovi trasparenti, DNS ottimo, pochi extra | Cloudflare dichiara prezzi at-cost, senza rinnovi gonfiati, e include DNS, SSL, DNSSEC e redazione WHOIS. Ottimo per `.com`; controlla al checkout se supporta il `.it` specifico. |
| Porkbun | `.com` molto economico, pannello semplice, forwarding incluso | `.com` e' indicato a 11,08 USD per registrazione, rinnovo e trasferimento. Non sembra offrire il `.it` puro; mostra `.it.com`, che non e' la stessa cosa. |
| OVHcloud | Registrar europeo, molte estensioni | Buona alternativa per `.it`, `.eu` e `.com`; confronta sempre il prezzo di rinnovo prima dell'acquisto. |

## Cosa farei io

1. Cercherei `fabioangei.it` su Aruba e OVHcloud.
2. Se disponibile, comprerei solo il dominio.
3. Terrei GitHub Pages come hosting gratuito.
4. Aggiungerei questi record DNS:

```text
Type   Name  Value
A      @     185.199.108.153
A      @     185.199.109.153
A      @     185.199.110.153
A      @     185.199.111.153
CNAME  www   flacnunica.github.io
```

5. Aggiungerei il dominio in `Settings` > `Pages` del repository GitHub.
6. Abiliterei HTTPS in GitHub dopo la propagazione DNS.

## Fonti

- GitHub Pages, dominio personalizzato: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
- GitHub Pages, panoramica domini: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages
- Aruba domini: https://hosting.aruba.it/domini/registrazione-dominio.aspx
- Cloudflare Registrar: https://www.cloudflare.com/products/registrar/
- Porkbun prezzi domini: https://porkbun.com/products/domains
- OVHcloud domini: https://www.ovhcloud.com/it/domains/
