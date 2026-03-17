# Ai-Object-Scanner

README – AI Object Scanner App

1. rész: Áttekintés & Funkciók

Ez az alkalmazás egy mesterséges intelligenciára épülő mobil app, amely képfelismerés segítségével azonosítja a lefotózott tárgyakat, és eldönti, hogy azok már korábban szerepeltek-e a rendszerben.

A cél egy játékos, gyűjtögetős élmény létrehozása, ahol a felhasználók minél több új tárgyat fedeznek fel és fotóznak be.

Főbb funkciók:
	•	 Tárgyak fotózása valós időben
	•	AI-alapú képfelismerés
	•	 Duplikált tárgyak felismerése
	•	 Pontozási rendszer (új tárgy = több pont)
	•	 Statisztikák és gyűjtemény megjelenítése
	•	 Adatok mentése és szinkronizálása

Pontozás logika:
	•	 Új tárgy felismerése → magas pontszám
	•	 Már létező tárgy → alacsony vagy 0 pont
	•	 Ritka / nehezen felismerhető tárgy → extra pont

Az alkalmazás gamifikációval motiválja a felhasználókat, hogy minél kreatívabb és változatosabb tárgyakat fotózzanak.


2. rész: Használat & Telepítés

Használat:
	1.	Nyisd meg az alkalmazást
	2.	Koppints a kamera ikonra
	3.	Fotózz le egy tárgyat
	4.	Az AI elemzi a képet és visszajelzést ad:
	•	Új tárgy → pontot kapsz
	•	Már ismert tárgy → nincs vagy kevesebb pont
	5.	Kövesd a pontjaidat és a gyűjteményedet az alkalmazásban


## 
Telepítés

```bash
git clone https://github.com/your-repo/ai-object-scanner.git
cd ai-object-scanner
npm install
npm start
