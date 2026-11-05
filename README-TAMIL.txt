SRI SELVI GROCERY POS - ANDROID APK PROJECT

முக்கியம்:
இந்த ZIP நேரடியாக APK அல்ல. GitHub-ல் project files upload செய்த பிறகு GitHub Actions மூலம் APK build செய்யப்படும்.

GitHub upload:
1. Repository-ல் Add file > Upload files செல்லவும்.
2. ZIP-ஐ extract செய்த பிறகு உள்ள project files/folders அனைத்தையும் upload செய்ய வேண்டும்.
3. .github folder-ஐயும் upload செய்ய வேண்டும்.
4. Commit changes அழுத்தவும்.
5. Repository-ல் Actions tab திறந்து Build Android APK workflow முடியும் வரை காத்திருக்கவும்.
6. பச்சை check வந்ததும் workflow run-ஐ திறந்து Artifacts பகுதியில் APK download செய்யவும்.

குறிப்பு:
- HTML app-இன் localStorage தரவு இந்த Android app-இல் அந்த app-க்குள் சேமிக்கப்படும்.
- CDN-ல் உள்ள Tailwind/QR/font அம்சங்களுக்கு இணையம் தேவைப்படலாம்.
- Printer compatibility-ஐ பயன்படுத்தும் printer மற்றும் Android print service மூலம் சோதிக்க வேண்டும்.
- இது debug APK; பொதுவான Play Store release signing செய்யப்படவில்லை.
