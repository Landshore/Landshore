## Hola! Soc en DAMIAN ZIBOWA👋

# Portfolio — SMX Student

## Sobre mi
Soc estudiant de **SMX (Sistemes Microinformàtics i Xarxes)** i m’interessa especialment la part pràctica de la informàtica: Linux, xarxes, servidors i programació.  
Vull continuar la meva formació cap a **DAM** i **DAW** per enfocar-me en desenvolupament i creixement tècnic.

## Què trobaràs en aquest portfoli
Aquest repositori recull alguns dels projectes i activitats que he anat fent durant el curs:
- Projectes de xarxes i servidors
- Pràctiques de Linux
- Tasques de Samba, NFS i Active Directory
- Exercicis de Python i lògica de programació
- Desenvolupament web i documentació de projectes

## Habilitats que estic consolidant
- Linux i administració bàsica
- Xarxes TCP/IP, DHCP, DNS i subnetting
- Gestió d’usuaris, permisos i serveis
- Python bàsic
- Git i GitHub
- Documentació de projectes en Markdown

## Projectes destacats
- [Projecte 5](https://github.com/Landshore/projecte5-Landshore)
- [Projecte 6](https://github.com/Landshore/projecte6-Landshore)
- [Projecte 7](https://github.com/Landshore/projecte-7-Landshore)
- [Foodlogistic Web](https://github.com/Landshore/Foodlogistic-web)

## Exemple de pràctica
Aquí tens un exemple de codi que he anat treballant durant la meva pràctica:

```python
suma = 0
count = 0
ask_user = input("Vols introduir notes? (si/no): ").lower()

while ask_user in ["sí", "si", "s"]:
    try:
        nota = float(input("Entra una nota: "))
        suma += nota
        count += 1
    except ValueError:
        print("Si us plau, entra només números.")
    
    ask_user = input("Vols introduir una altra nota? (si/no): ").lower()

if count > 0:
    print(f"La mitja és {suma / count:.2f}")
else:
    print("No vas introduïr cap nota.")
