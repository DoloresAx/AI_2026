### သင်တန်းသားများလေ့ကျင့်ရန်

- [[ YouTube Recommendation Data  ]](https://www.kaggle.com/code/madaratheog/youtube-recommendation): User interaction တွေ၊ Video category တွေနဲ့ Watch time တွေ ပါဝင်ပါတယ်။ "Recommended video ကို User က နှိပ်မလား (Click-through rate)" ဆိုတာကို Random Forest နဲ့ Predict လုပ်ကြည့်လို့ ရပါတယ်။

- [[ MovieLens Dataset ]](https://www.kaggle.com/datasets/ayushimishra2809/movielens-dataset): ဒါကတော့ Recommendation system လောကမှာ Standard ပါပဲ။ User တွေရဲ့ Rating တွေပေါ်မူတည်ပြီး နောက်ထပ် ဘယ်ကားကို ကြည့်မလဲဆိုတာကို Classify လုပ်နိုင်ပါတယ်။

- [[ Bank Marketing Dataset (UCI) ]](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset): ဖောက်သည်တစ်ယောက်က ဘဏ်ရဲ့ ဝန်ဆောင်မှု (Term Deposit) ကို ဝယ်မလား၊ မဝယ်ဘူးလားဆိုတာကို Predict လုပ်ရတာပါ။ Feature တွေ အစုံပါလို့ Ensemble methods တွေရဲ့ စွမ်းဆောင်ရည်ကို ကောင်းကောင်းသိနိုင်ပါတယ်။

- [[ E-commerce Customer Churn ]](https://www.kaggle.com/datasets/samuelsemaya/e-commerce-customer-churn): Shopping site တစ်ခုကနေ ဝယ်ယူသူက ထွက်သွားတော့မလား (Churn) ဒါမှမဟုတ် ဆက်သုံးမလားဆိုတာကို ခန့်မှန်းတဲ့ Project မျိုးပါ။

- [[ Loan Approval Prediction ]](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset): ချေးငွေလျှောက်ထားသူရဲ့ အချက်အလက်တွေ (Income, Credit History, Education) ကို ကြည့်ပြီး ချေးငွေ ခွင့်ပြုသင့်မသင့် ဆုံးဖြတ်တဲ့ Dataset ပါ။

- [[ Breast Cancer Wisconsin (Diagnostic) ]](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data): ဆဲလ်တွေရဲ့ အတိုင်းအတာတွေပေါ် မူတည်ပြီး ရောဂါရှိမရှိ ခန့်မှန်းတာပါ။ Random Forest က Feature Importance (ဘယ်အချက်က အရေးကြီးဆုံးလဲ) ကို ထုတ်ပေးနိုင်တာကြောင့် ဆေးဘက်ဆိုင်ရာမှာ အရမ်းသုံးပါတယ်။

- [[  🌲 Forest Cover Type Prediction   ]](https://www.kaggle.com/c/forest-cover-type-prediction): ဘာကြောင့် စမ်းသင့်တာလဲ: * Multiclass Classification: ရှေ့က Project တွေလို Yes/No (Binary) တင်မဟုတ်ဘဲ သစ်တောအမျိုးအစား ၇ မျိုးအထိ ခွဲခြားရမှာပါ။
Feature Diversity: မြေပြင်အနိမ့်အမြင့် (Elevation)၊ နေရောင်ခြည်ကျရောက်မှု (Hillshade) နဲ့ မြေဆီလွှာအမျိုးအစား (Soil Type) စတဲ့ Numeric ရော Categorical data တွေပါ ရောနေပါတယ်။
Decision Boundaries: သစ်ပင်အမျိုးအစားတွေက တစ်ခုနဲ့တစ်ခု "အချက်အလက်ချင်း ထပ်နေတတ်တာ" ကြောင့် Linear models တွေထက် Decision Tree-based models တွေက ပိုပြီး တိတိကျကျ ခွဲခြားနိုင်တာကို တွေ့ရပါလိမ့်မယ်။


### Decision Tree vs Random Forest
ဘယ်လို စမ်းသပ်မလဲ?ဒီ Dataset တွေကို သုံးပြီး အောက်ပါအတိုင်း နှိုင်းယှဉ်လေ့ကျင့်ကြည့်ပါ
- Step 1 Decision Tree တစ်ခုတည်းနဲ့ အရင် Run ကြည့်ပါ။ ရလဒ်နဲ့ Tree ရဲ့ ပုံစံကို လေ့လာပါ။
- Step 2 Random Forest (Ensemble) ကို သုံးပြီး Accuracy တက်မတက် ကြည့်ပါ။
- Step 3 Feature Importance ကို ထုတ်ကြည့်ပါ။ (ဥပမာ- YouTube မှာဆိုရင် User က Video ကို နှိပ်ဖို့အတွက် Category က ပိုအရေးကြီးသလား၊ Watch time က ပိုအရေးကြီးသလား စသဖြင့်)