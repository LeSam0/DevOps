# Resultat du scan du premier dockerfile

### Commande utiliser :

```bin
docker scout cves test1:latest
```

### Resultat :

```bin
Analyzing image test1:latest
    v SBOM of image already cached, 225 packages indexed
    v No vulnerable package detected
```

# Resultat du scan du second dockerfile

### Commande utiliser :

```bin
docker scout cves test2:latest
```

### Resultat :

```bin
Analyzing image test2:latest
    v SBOM of image already cached, 221 packages indexed
    v No vulnerable package detected
```
