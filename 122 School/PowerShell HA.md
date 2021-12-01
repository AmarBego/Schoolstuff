# Aufgabe Teams #

- Als erstens modul Active Directory starten:
 Import-Module ActiveDirectory

- Neue konto erstellen in active directory
Vorgang:
 New-ADUser Amar.Begovic

- Neue gruppe in Active Directory erstelle:
 NEW-ADGroup –name "IL A21” –groupscope Global
 
- Neue OU in Active Directory erstellen:
 NEW-ADOrganizationalUnit "Bene”

- Properties vom OU wechseln:
 Set-ADOrganizationalUnit -city "Luzern" -PropertiesDepartment "Verkauf"

- Suche nach alles
 Get-ADUser -Filter * -SearchBase "OU=Bene"