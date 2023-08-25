Een collider is een vorm die wordt gebruikt om te detecteren wanneer een GameObject botst of een ander GameObject kruist. Het is veel gemakkelijker voor een computer om te controleren op botsingen met een simpele vorm dan op de complexe vorm van een GameObject.

Een Box Collider heeft een eenvoudige kubusvorm die kan worden aangepast en gepositioneerd om te voorkomen dat GameObjects dezelfde ruimte innemen.

Om een Box Collider toe te voegen, ga je naar **Add Component** in het Inspector-venster voor je GameObject en selecteer je **Box Collider**.

![Het vervolgkeuzemenu Add Component met 'box' getypt in de zoekbalk en 'Box Collider' gemarkeerd.](images/component-box.png)

Verander de waarden in de 'Center' en 'Size' eigenschappen totdat je tevreden bent dat ze boven de grond staan en het hele GameObject bedekken.

![De component Box Collider met waarden Center y = 0.5, Size x = 0.7, y = 1 en z = 0.7.](images/cone-properties.png)

![Het Roadworks Cone-model in de Scene-weergave met de groene lijnen van de Box Collider in een kubusvorm die passen rond de kegel.](images/colider-cone.png)

**Tip:** Box Colliders moeten worden toegevoegd aan alle GameObjects waarvan je wilt voorkomen dat ze dezelfde ruimte innemen.
