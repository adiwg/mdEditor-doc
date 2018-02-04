# Translate

---

The **Translate **function allows you to translate and export a record into another metadata format. Translation works to the following formats: ISO 19115-2, ISO 19110, HTML, or sbJSON \(ScienceBase JSON\). **Translate** is only visible when you’re viewing a metadata record.

![](/assets/translate_screenshot.png)

### How mdJSON Works With the mdTranslator

mdTranslator is an open-source, Ruby software application for translating between metadata standards. mdTranslator inputs mdJSON \(or any other reader formats: sbJSON; FGDC; or CSDGM\). The translator reformats the file into any of the selected writer formats: ISO 19115-2; ISO 19110; HTML; mdJSON; FGDC; CSDGM; ISO 19115-1; or sbJSON.  It then outputs the selected file format. mdTranslator is available as a Ruby gem or Command-Line-Interface.

![](/assets/translator_diagram.png)

