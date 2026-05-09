# ကျွဲဂိမ်းapp - Web-to-App Project

### 🇲🇲 မြန်မာစာညွှန်ကြားချက်
၁။ ဤ ZIP ကို ဖြည်ပြီး GitHub သို့ တင်ပါ။
၂။ GitHub Actions က သင့်အတွက် APK ကို Cloud ပေါ်တွင် အလိုအလျောက် ထုတ်ပေးပါလိမ့်မည်။
၃။ **Play Store (AAB) အတွက် Keystore လိုသလား?** 
   - စမ်းသပ်ဖို့ APK အတွက်ဆိုရင် Keystore မလိုပါ။
   - Play Store တင်ဖို့ AAB အတွက်ဆိုရင်တော့ ကိုယ်ပိုင် Keystore (.jks) မဖြစ်မနေ လိုအပ်ပါသည်။

### 🚀 Manual Build
1. Run `npm install`
2. Run `npx cap sync android`
3. Run `npx cap open android` (Requires Android Studio)

### 🔑 How to create Keystore?
Use Android Studio: Build > Generate Signed Bundle > Create New Keystore.

### 🖼️ How to set App Icon (Logo) in Android Studio
1. Open project in Android Studio.
2. Look at the left panel (Project/Android view).
3. **Right-click** the **'app'** folder (the one at the very top).
4. Select **New** > **Image Asset**.
5. Under **'Path'**, click the folder icon and select your logo file.
6. Use the **'Resize'** slider to fit the icon inside the safe area.
7. Click **Next** > **Finish**.

Note: This generates all required sizes for Play Store compatibility.