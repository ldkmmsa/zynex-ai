# Zynex AI

Zynex AI is een draagbare Windows-chatapp voor gesprekken met een AI-model dat op je eigen computer draait. De app gebruikt Ollama; chats worden lokaal verwerkt en zijn geen cloudchat.

## Download en gebruik

Zodra een release beschikbaar is, kun je daar **Zynex AI.exe** downloaden via [Releases](https://github.com/ldkmmsa/zynex-ai/releases). Er is geen installer nodig: start het bestand nadat je het hebt gedownload.

Installeer eerst [Ollama voor Windows](https://ollama.com/download/windows) en download daarna zelf een lokaal model, bijvoorbeeld:

```powershell
ollama pull qwen2.5:7b
```

Start Ollama en open vervolgens Zynex AI. Ollama en het AI-model worden niet met de app meegeleverd. Internet is nodig om Ollama en modellen te downloaden; chatten met een reeds geinstalleerd lokaal model blijft lokaal.

## Windows-beveiliging

Deze download is niet digitaal ondertekend. Windows of beheerbeleid op je computer kan daarom een waarschuwing tonen of het starten blokkeren. Ga alleen verder als je de herkomst vertrouwt; organisatiebeleid kan alleen door je beheerder worden aangepast.