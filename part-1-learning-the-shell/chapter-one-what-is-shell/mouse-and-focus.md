# mouse၊ focus အကြောင်းလေး

shell က keyboard တစ်ခုတည်းနဲ့ပဲ အလုပ်လုပ်တယ်ဆိုပေမယ့် terminal emulator \( terminal \) တွေမှာ mouse ကို သုံးလို့ရပါတယ်။ copy, paste မြန်မြန်ဆန်ဆန်လုပ်နိုင်ဖို့အတွက် X Window System \( GUI အလုပ်လုပ်အောင် လုပ်ပေးတဲ့ engine \) ကနေပြီး support လုပ်ထားပါတယ်။ \( ကိုယ်ကူးချင်တဲ့ \) စာကြောင်းကို highlight \( select \) လုပ်လိုက်တာနဲ့ အဲ့ စာကြောင်းကို X system မှာ ပါတဲ့ buffer ထဲကို ကူးထည့်ထားပေးတယ်။ နောက်ပိုင်း middle click ကို နှိပ်လိုက်ရင် တခါတည်း paste လုပ်ပြီးသားဖြစ်သွားပါမယ်။ စမ်းကြည့်ကြည့်ပါ။ \( TLDR; အရင် highlight လုပ်၊ paste ချင်တဲ့နေရာမှာ middle click နှိပ် \)

{% hint style="warning" %}
terminal မှာ `ctrl-c`, `ctrl-v` နဲ့ copy, paste လုပ်ဖို့ မကြိုးစားပါနဲ့။ အလုပ်လုပ်မှာမဟုတ်ပါဘူး။ ဒီ control code တွေက Microsoft Windows မထွက်ခင်ကတည်းက တခြားအဓိပ္ပါယ်တွေနဲ့ သတ်မှတ်ပြီးသားပါ။
{% endhint %}

စာဖတ်သူရဲ့ desktop environment \( အများအားဖြင့် KDE or GNOME \) မှာ Windows လိုအလုပ်လုပ်ဖို့ဆိုရင် focus policy ကို `click-to-focus` ထားထားရပါတယ်။ ပြောချင်တာက window တစ်ခုကို focus ရဖို့ဆိုရင် \(​ foreground \) ရောက်ဖို့ဆိုရင် click လုပ်ရပါတယ်။ ဒီအချက်က ရှေး X system ရဲ့အလုပ်လုပ်ပုံနဲ့ ဆန့်ကျင်နေပါတယ်။ သူ့မှာဆိုရင် `focus-follows-mouse` - window ဟာ mouse တင်လိုက်ရုံနဲ့ focus ရပါတယ်။ ဒါပေမယ့် click မလုပ်မချင်း foreground ရောက်လာမှာတော့မဟုတ်ပါဘူး။ ဒါပေမယ့် အဲ့ window ဟာ input လက်ခံနိုင်ပါတယ်။ focus policy ကို `focus-follows-mouse` ထားထားတာဟာ ခဏကလို copy paste လုပ်တာတွေကို အများကြီး မြန်ဆန်စေပါတယ်။ စာဖတ်သူအနေနဲ့ အဲ့တာကို စမ်းကြည့်လို့ရပါတယ်။ \( Unity DE တို့မှာတော့ အလုပ်မလုပ်ဘူးပေါ့ \)။ စာဖတ်သူအဲ့တာကို စမ်းကြည့်ပြီးရင် ကြိုက်သွားမှာပါ။ ကိုယ့် window manager setting ထဲမှာ အဲ့ဒီ focus policy ကို ပြင်လို့ရမှာပါ။

