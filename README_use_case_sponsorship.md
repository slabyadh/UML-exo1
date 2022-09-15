# use_case_sponsorship

### Description :
Donner la possibilité au client de parrainer un filleul
Offrir une récompense au filleul et parrain dans le cas d'un parrainnage réussi, cad une création de compte du filleul

### Pré condition:
Le client doit avoir un compte, transmettre le lien à son filleul.
Le filleul doit créé un compte pour bénéficier du parrainnage

### Post condition:
Une fois le compte créé par le filleul en suivant le lien envoyé par le client, la récomprense de parrainnage est ainsi offerte aux deux

### Scénario Nominal:
1. client: demande le lien de parrainnage au système
2. système: génère un lien de parrainnage et le transmet au client
3. filleul: demande la création de son sompte via le lien de parrainnage
4. système: créé le compte du filleul et envoi la récompense au client et au filleul

### Scénario Alternatif:
1. système: propose un lien de parrainnage au client
2. client: accepte le lien de parrainage
3. filleul: demande la création de son sompte via le lien de parrainnage
4. système: créé le compte du filleul et envoi la récompense au client et au filleul

### Scénario Erreur:
1. client: demande le lien de parrainnage au système
2. système: génère un lien de parrainnage et le transmet au client
3. filleul: demande la création de son sompte en passant par le lien de parrainnage
4. système: créé le compte du filleul et n'envoi pas la récompense au client et au filleul