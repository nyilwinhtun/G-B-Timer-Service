Game & Billiards Timer — Test Version v2

ဒီ folder ကို GitHub မှာ production branch / live project ကို မထိခိုက်စေဘဲ branch အသစ် သို့မဟုတ် repository အသစ်မှာ စမ်းသပ်ပါ။

ပါဝင်သော ပြင်ဆင်ချက်များ
- PS4, PS5 နှင့် Computer station အတွက် သီးခြား hourly rate
- ဘိလိယက်ခုံသေး/ခုံကြီးအတွက် သီးခြား hourly rate
- PS4, Computer, Pool အတွက် သီးခြား icon များ
- Timer ကို အဝိုင်းပုံမဟုတ်ဘဲ စတုဂံ panel အတွင်း ဖော်ပြထားသည်
- Settings မှ PS4/Computer/Pool အရေအတွက် ထည့်/လျှော့နိုင်သည်
- POS ပစ္စည်းကို ရောင်းရန်စာရင်းမှ ဖယ်ရှားနိုင်သည်; ယခင် order/history object များကို မဖျက်ပါ
- Station အသုံးပြုနေစဉ် သို့မဟုတ် ငွေမရှင်းရသေးလျှင် ဖယ်ရှားခွင့်မပြုပါ
- ဒီ test copy သည် Firestore live shop document ကို မဖတ်/မရေးပါ။ localStorage သီးသန့်သုံးသည်။

သတိပြုရန်
- ဒီ version ကို runtime device testing အပြည့်မလုပ်ရသေးပါ။ ဈေးနှုန်းတွက်ချက်မှု၊ timer၊ checkout, printer, offline reload, mobile screen တို့ကို စမ်းသပ်ပါ။
- Firebase Authentication က login အတွက်သာ ကျန်ရှိနေသေးသည်။ Firestore read/write ကို TEST_BUILD_ISOLATED=true က ပိတ်ထားသည်။
- Bluetooth printer သည် iOS browser တွင် Web Bluetooth မရနိုင်သောကြောင့် iPhone မှာ အလုပ်လုပ်မည်ဟု အာမမခံနိုင်ပါ။
- GitHub Pages တွင် index.html, manifest.json, sw.js, icons folder ကို တူညီသော folder structure ဖြင့်တင်ပါ။ မူလ live file ကို မအစားထိုးပါနှင့်။
