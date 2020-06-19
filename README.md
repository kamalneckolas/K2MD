# K2MD
K2 on Material Design Theme for iTerm2.


لمستخدمي آجهزه ماك، تشتغل كثير على ال terminal وحاب تخليه زي الصوره؟ 
عشان تقدر تكمل التطبيق لازم تكون مثبت HomeBrew و ال git مسبقا، تابع معايا:

١- نزل وثبت برنامج iTerm2 من الرابط https://www.iterm2.com/downloads.html

٢- نزل الخطوط وثبتها بالجهاز 
https://github.com/enricobacis/.dotfiles/blob/master/osx-fonts/Library/Fonts/Knack%20Regular%20Nerd%20Font%20Complete.ttf?raw=true
https://github.com/powerline/fonts/blob/master/RobotoMono/Roboto%20Mono%20for%20Powerline.ttf?raw=true

٣- نزل نظام الالوان التالي بالضغط طويلا او بالزر الايمن ثم حفظ بإسم بعد التنزيل روح على الملف و سوي إعاده تسميه و احذف .txt الاخيره
https://raw.githubusercontent.com/kamalneckolas/K2MD/master/k2MD.itermcolors

٤- افتح برنامج iTerm2 وبعدها افتح الاعدادت و اتبع الخطوات
Preferences → Profiles → Colors → Color presets → Import
اختار الملف من الخطوه رقم ٣.
بعد الاستيراد افتح مره اخرى Color presets و اختر الثيم K2MD

٥- انتقل لتبويب Text ثم اختر Change Font و اختر 
الخط الاساسي Roboto Mono for Powerline
الخط الثاني Knack

٦- ثبت zsh بكتابة الامر التالي في ال terminal تحتاج يكون عندك (HomeBrew) مثبت مسبقا:
brew install zsh zsh-completions
بعد أكتمال التنزيل اكتب الامر التالي
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

٧- اضافة Powerlevel9k Zsh Theme بطباعة الامر التالي تحتاج ال git يكون مثبت مسبقا:
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k

٨- هذي اهم خطوه واللي فيها بنضيف اللمسات النهائية و التعديلات، افتح هذا الرابط وانسخ كل اللي فيه
https://raw.githubusercontent.com/kamalneckolas/K2MD/master/.zshrc

 اكتب الامر التالي في ال iTerm
nano ~/.zshrc
رح يفتح ملف تنزل لنهاية الملف وتلصق اللي نسخته من الرابط السابق.
اضغط على control + x عشان تحفظ التعديلات اللي سويتها بعدها للتأكيد اضغط على Y بعدها Enter.

٩- قفل البرنامج و افتحه مره ثانيه واستمتع


