---
published: true
---
Nu blev jag rätt sugen på att undersöka alternativen här ikväll, så jag gjorde ett exempel med min egna domän "tilly.pro"
Hemsidan går att besöka här: https://tilly.pro/
Källkoden här: https://github.com/tilly-pro/homepage
* Det här är alltså en github organisation, detta kan man sätta upp så att fler personer har administrativa rättigheter.
* Så fort kod pushas till detta repo så triggas ett bygge för den statiska hemsidan. 
* Jag låter cloudflare (kostnadsfritt) hantera domänen, cachning, ddos skydd, https etc. 
* Jag vidarbefodrar epost med hjälp av  improvmx (Google for Nonprofit skulle nog vara snäppet smidigare)

För att lägga till CMS aspekten till det hela så finns det lite alternativ. prose.io var ett jag hittade, det är rätt smalt så kräver lite mer av användaren. Netlify CMS verkar ha mer WYSIWYG editors så det kan nog vara smidigare, och som jag förstår det så kan man koppla det till google för identifiering så eventuellt rätt smidigt ur den apsekten också.

Allt det här skulle ju kräva att man bygger om det som tidigare varit ett wordpress tema till valfritt statisk ramverk (i mitt exempel använder jag jekyll men det går bra med många andra också)
