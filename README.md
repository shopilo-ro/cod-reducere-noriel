# Cod reducere Noriel — fetch automat de pe shopilo.ro

Modul Python pentru fetch automat de **coduri de reducere Noriel** de pe [shopilo.ro](https://shopilo.ro/magazin/noriel.ro). Returneaza **cupoane Noriel** active in format JSON, gata de integrat intr-un bot Telegram, extensie de browser sau orice alt tool.

**Pagina live:** [shopilo-ro.github.io/cod-reducere-noriel](https://shopilo-ro.github.io/cod-reducere-noriel/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Instalare

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-ro/cod-reducere-noriel
cd cod-reducere-noriel
python fetch.py
```

## Output exemplu

```json
[
  {
    "store": "Noriel",
    "code": "SHOPILO10",
    "discount": "10%",
    "description": "10% reducere la jucarii si cadouri pentru copii",
    "expires": "2026-10-02",
    "source": "https://shopilo.ro/magazin/noriel.ro"
  }
]
```

## Cupoane Noriel disponibile

| Reducere | Descriere | Sursa |
|----------|-----------|-------|
| 10% | 10% reducere la jucarii si cadouri pentru copii | [shopilo.ro](https://shopilo.ro/magazin/noriel.ro) |

Codurile active: **[shopilo.ro/magazin/noriel.ro](https://shopilo.ro/magazin/noriel.ro)**

## Intrebari frecvente

### Cum folosesc un cod de reducere Noriel?
Copiaza codul din tabelul de mai sus sau de pe [shopilo.ro](https://shopilo.ro/magazin/noriel.ro), adauga produsele in cos pe Noriel, si introdu codul la checkout in campul dedicat.

### Cat timp sunt valabile cupoanele Noriel?
Fiecare cupon are data de expirare afisata in coloana "Expira". Scriptul fetch.py returneaza doar cupoanele active la momentul rularii.

### Unde gasesc cele mai noi voucher-uri Noriel?
Pagina [shopilo.ro/magazin/noriel.ro](https://shopilo.ro/magazin/noriel.ro) este actualizata zilnic cu cele mai noi cod reducere Noriel, voucher Noriel si cupon promotional Noriel.

### Codul nu functioneaza. Ce fac?
Verifica data de expirare si conditiile (valoare minima cos, produse eligibile). Unele coduri sunt valabile doar in aplicatia mobila sau pentru prima comanda.

## Despre Noriel

Noriel este unul dintre magazinele online populare. Gasesti pe [shopilo.ro](https://shopilo.ro/magazin/noriel.ro) cele mai bune cod reducere Noriel, cupoane Noriel verificate si voucher Noriel active, actualizate zilnic.

## Instalare npm

```bash
npm install cod-reducere-noriel
```

```javascript
const { fetchCoupons } = require('cod-reducere-noriel');
fetchCoupons().then(data => console.log(data));
```

## Licenta

MIT — date sursa de pe [shopilo.ro](https://shopilo.ro)
