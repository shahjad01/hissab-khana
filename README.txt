ROOM KHANA HISAAB - ANDROID APP (APK banane ke steps)

1. Android Studio install karo (developer.android.com/studio), free hai.
2. Is zip ko extract karo, phir Android Studio mein File > Open > RoomKhanaHisaab folder chuno.
3. Pehli baar Gradle sync hone do (internet chahiye, kuch minute lagenge). Agar "Upgrade" ka sujhav aaye to Yes kar do.
4. Menu: Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Build ke baad "locate" par click karo. APK yahan milegi: app/build/outputs/apk/debug/app-debug.apk
6. APK ko WhatsApp se bhejo, phone mein open karke install karo (Unknown sources allow karna padega).

App ka poora code app/src/main/assets/index.html mein hai. Koi badlav karna ho to usi file ko edit karo.

--- BINA ANDROID STUDIO KE (GitHub se APK) ---
1. github.com par free account banao, New repository banao.
2. Is folder ki saari files (".github" folder samet) repository mein upload karo.
3. Repository ke "Actions" tab mein "Build APK" chalne do (3-5 minute).
4. Complete hone par us run par click karo, neeche "Artifacts" mein RoomKhanaHisaab-APK download karo.
5. Zip kholo, andar app-debug.apk hai. Use phone mein install karo.
