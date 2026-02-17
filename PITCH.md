# TNZXMiner - Il Mining Diventa Privato

## Pitch Generale

**TNZXMiner** non è solo un miner. È un ecosistema completo che trasforma il tuo computer in un nodo sovrano della rete Monero, con wallet integrato, comunicazioni cifrate e identità decentralizzata.

### Il Problema

I miner tradizionali:
- Espongono il tuo indirizzo wallet alla pool (tracciabile)
- Non hanno wallet integrato (devi usare software separato)
- Nessuna comunicazione sicura con altri miner
- Dipendenza totale da servizi centralizzati

### La Soluzione TNZX

Un'unica applicazione che ti dà:
- **Mining** → Guadagni Monero
- **Wallet** → Gestisci i tuoi fondi
- **Messenger** → Comunichi in modo sicuro
- **Identità** → Possiedi il tuo nome digitale

**Zero dipendenze esterne. Zero tracciamento. Zero compromessi.**

---

## Funzionalità e Vantaggi

### 1. MINING INTELLIGENTE

| Funzione | Vantaggio |
|----------|-----------|
| **Profili Energetici** | Mining silenzioso mentre lavori, potenza piena quando sei via |
| **Auto-Detection CPU** | Configurazione automatica ottimale per la tua CPU |
| **Pool Integrata** | Connessione diretta a TNZXPool senza configurazione |
| **Dashboard Real-time** | Vedi hashrate, shares, guadagni in tempo reale |

**Beneficio chiave:** Inizi a minare in 30 secondi. Scarica, avvia, guadagna.

---

### 2. WALLET MULTI-COLORE (5 Portafogli)

Un sistema unico che separa i tuoi fondi per funzione:

| Colore | Uso | Perché Serve |
|--------|-----|--------------|
| 🔵 **BLU** | Identità | La tua firma digitale, mai esposta |
| 🔴 **ROSSO** | Spese | Per pagamenti, separato dal resto |
| 🟢 **VERDE** | Ricevi | Dai questo indirizzo a chi ti paga |
| 🟡 **GIALLO** | Mining | Rewards dalla pool, tracciabile solo da te |
| 🟣 **VIOLA** | Stealth | Indirizzi usa-e-getta per massima privacy |

**Beneficio chiave:** Nessuno può collegare i tuoi pagamenti tra loro. Ogni transazione è isolata.

---

### 3. MESSENGER CIFRATO END-TO-END

| Funzione | Vantaggio |
|----------|-----------|
| **Crittografia E2E** | Nemmeno il server può leggere i messaggi |
| **X25519 + AES-256** | Standard militare, non "cifratura fai da te" |
| **Nessun Account** | La tua chiave pubblica È la tua identità |
| **Zero Metadati** | Non salviamo chi parla con chi |

**Beneficio chiave:** Comunichi con altri miner senza email, telefono o registrazione. Solo la tua chiave.

---

### 4. DNS DECENTRALIZZATO (.tnzx)

Invece di ricordare `46xyz...abc` (64 caratteri), usi `tuonome.tnzx`.

| Funzione | Vantaggio |
|----------|-----------|
| **Domini Personali** | `mario.tnzx` invece di stringhe esadecimali |
| **Verifica Crittografica** | Nessuno può impersonarti |
| **Nessun ICANN** | Non dipendi da autorità centrali |
| **Pagamento in XMR** | Registri con quello che mini |

**Beneficio chiave:** Identità digitale che possiedi TU, non Google/Facebook/governo.

---

### 5. RETE P2P (Nuovo)

| Funzione | Vantaggio |
|----------|-----------|
| **Routing Onion** | I tuoi dati passano per nodi intermedi |
| **Anti-Correlazione** | Impossibile collegare richieste alla tua identità |
| **Exit Node Pool** | La pool funge da uscita, tu resti anonimo |

**Beneficio chiave:** Navighi la rete TNZX senza rivelare il tuo IP reale.

---

## Confronto con Alternative

| Caratteristica | XMRig Standard | NiceHash | **TNZXMiner** |
|----------------|----------------|----------|---------------|
| Mining Monero | ✅ | ❌ (paga in BTC) | ✅ |
| Wallet Integrato | ❌ | ❌ | ✅ |
| Messenger Cifrato | ❌ | ❌ | ✅ |
| Identità Decentralizzata | ❌ | ❌ | ✅ |
| Open Source | ✅ | ❌ | ✅ |
| Zero Tracciamento | ❌ | ❌ | ✅ |
| Fee Pool | ~1% | 2-5% | 0.5% |

---

## Privacy by Design

TNZXMiner è costruito con la privacy come **fondamento**, non come feature aggiuntiva:

### Cosa NON Facciamo
- ❌ Non tracciamo il tuo IP
- ❌ Non logghiamo i tuoi messaggi
- ❌ Non colleghiamo i tuoi wallet
- ❌ Non vendiamo i tuoi dati
- ❌ Non abbiamo backdoor per "autorità"

### Cosa Facciamo
- ✅ Crittografia end-to-end ovunque
- ✅ Chiavi generate localmente
- ✅ Codice verificabile (open source)
- ✅ Zero-knowledge dove possibile

---

## Per Chi È TNZXMiner?

### Perfetto Per:
- **Miner Privacy-Focused** → Vuoi minare senza essere tracciato
- **Holder Monero** → Vuoi gestire XMR senza exchange
- **Crypto-Anarchici** → Vuoi comunicare senza Big Tech
- **Developer** → Vuoi costruire su un'infrastruttura libera

### Non Adatto A:
- Chi vuole "guadagno facile" senza capire
- Chi preferisce custodial wallet (exchange)
- Chi non apprezza la privacy

---

## Numeri

| Metrica | Valore |
|---------|--------|
| Fee Pool | **0.5%** (tra le più basse) |
| Crittografia | **AES-256-GCM** (standard bancario) |
| Key Exchange | **X25519** (Signal/WhatsApp usano questo) |
| Codice Rust | **48KB** di logica wallet sicura |
| Tempo Setup | **< 1 minuto** |

---

## Come Iniziare

1. **Scarica** → [TNZXMiner v16.1.0 Beta](https://github.com/tnzxpool/tnzxminer-releases/releases)
2. **Avvia** → Click su "More info" → "Run anyway" se Windows blocca
3. **Crea Wallet** → Segui il wizard, salva le 25 parole
4. **Mina** → Click su "Start Mining"

**In 60 secondi stai già guadagnando Monero.**

---

## Roadmap Beta

| Fase | Stato | Cosa Testare |
|------|-------|--------------|
| Mining | ✅ Funzionante | Hashrate, shares, stabilità |
| Wallet | ✅ Funzionante | Creazione, import, indirizzi |
| Messenger | 🔄 Testing | Invio messaggi, contatti |
| DNS | 🔄 Testing | Registrazione domini |
| P2P | 🆕 Nuovo | Connessione relay |

---

## Contatti

- **Issues:** https://github.com/tnzxpool/tnzxminer-releases/issues
- **Email:** tnzx@proton.me

---

*"La privacy non è qualcosa che puoi chiedere.
È qualcosa che devi pretendere."*

— Il Team TNZX
