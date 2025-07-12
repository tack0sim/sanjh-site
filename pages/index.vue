<script setup lang="ts"></script>

<template>
  <div>
    <!-- <GallerySlider /> -->
    <!-- Hero Section -->
    <section class="prose max-w-[1440px] mx-auto mb-4">
      <h2 class="text-center">Our Bestsellers</h2>
      <HeroMain />
    </section>

    <!-- Directors Note Section -->
    <section class="prose max-w-[1440px] mx-auto mb-8">
      <h2 class="max-w-[1440px] text-center">Directors Note</h2>

      <div
        class="flex max-sm:flex-col max-sm:justify-center justify-evenly items-start gap-x-6 mx-8"
      >
        <DirectorsCard
          src="amjad.jpeg"
          title="Amjad Saleem Minhas"
          body-urdu="سانجھ پبلیکیشنز  2005 وچ بنیا۔اوس ویلے ملک وچ مذہبی انتہا پسندی اپنے عروج تے سی۔سارے ملک وچ کوئی حصہ تشدد دی لہر توں بچیا ہویا نہیں سی۔ایس لئی ساڈے خیال موجب سانوں ملک وچ موجود ون سونتا نوں سلاہن لئی اپنی اپنی ماں بولی ول دھیان دینا ہووے گا۔پنجابی زبان دی ترقی تے اوہدے قدرتی بہاو وچ سب توں وڈی رکاوٹ خود ریاست دا نظریاتی کٹڑ پن سی جینہے پنجاب وچ ساڈے ایس مڈھلے بولی حق نوں منن توں انکار کیتا ہویا سی۔سانجھ پبلیکیشنز نے ایس حوالے نال دو پدھری کم کیتا۔اک اپنی ماں بولی وچ سوہنا لٹریچر چھاپیا تے دوجا پنجابی ستھاں نال مل کے منظم طریقے نال پنجابی سوال نوں سیاسی ایجنڈے اتے لیاندا۔اج 20 سالاں توں بعد اسیں سمجھدے ہاں کہ اپنے ٹچیاں اتے ہن اک وڈے کھلار نال اگے ودھ رہے ہاں۔پنجاب دی ہر نکڑ اتے ایہہ سوال پوری طاقت نال چکیا جا رہیا اے۔
          چیتا رہوے کہ اسیں اپنے ملک وچ بولی جان والی ہر زبان تے رہتل دا برابری دی پدھر اتے احترام کردے ہاں تے ہن تک اسیں پنجابی توں وکھ سندھی سرائیکی پشتو بلوچی اردو تے انگریزی وچ کتاباں چھاپ چکے ہاں۔
  روشن خیالی تے سائنسی خیالات نوں آزادی دے نال ورتن تے پھیلان دے حق وچ ہاں۔ہر طرح دی شدت پسندی نوں ملک و قوم تے اوہدی ترقی دی راہ وچ رکاوٹ سمجھدے ہاں۔
  سانجھ پبلی کیشنز اک چھوٹا جیہا اشاعتی ادارہ ہے لیکن اسیں اپنے ویژن دے وڈے ہوون اتے یقین رکھدے ہاں۔ساڈی کوشش تے خواہش اے کہ ساڈا ملک  سیاسی سماجی معاشی پدھر اتے دن دگنی تے رات چوگنی ترقی کرے۔"
          class="sm:w-[50vw]"
        />

        <DirectorsCard
          src="farkhanda-1.jpeg"
          title="Farkhanda Amjad"
          body-urdu="ساڈے ادارے سانجھ پبلیکیشنز نوں قائم ہوۓ ایس ورھے 20 سال پورے ہو جاسن ۔جولایٔی  2005 توں جون 2025 دا اے سفر اسی ماں بولی دے ودھا لیٔ شروع کیتا سی ۔جیہدے وچ ہر علاقے اور خطے دی زبان اچ کتاباں چھاپیاں مثلاً انگریزی، اردو، پنجابی، سندھی، سرایٔیکی، بلوچی، پشتو وغیرہ ایہناں وچ تاریخ ،ناول،افسانے، کہانیاں، سفرنامے، شاعری، تنقید، میگزین، ہڈورتی، پنجابی قاعدہ تے ڈرامے شامل نیں۔
          سانجھ دے پلیٹ فارم تے صرف پبلیکیشن دا ہی کم نہیں ہوندا بلکہ ایتھے وڈے ،چھوٹے،نوجوان، کڑیاں، منڈے مختلف موضوعات تے اپنی گل بات وی سانجھی کردے نیں۔ اسیں اپنے ادارے، پنجاب لوک سنگت دی چھتر چھاویں سانجھ ساہت میلے وی سجاۓ۔ کتاب میلے تے مختلف یونیورسٹیاں اور اداریاں وچ کتاباں دی مکھ وکھالی پروگرام وی کیتے.
          سانجھ ادارے دیاں چھپیاں کتاباں تے مناسب رعایت دتی جاندی اے۔ اپنے  ادارے دے 20 سال پورے ہون دی خوشی وچ جولائی 2025 دا پورا مہینہ ٪ 70 تک رعایت دتی جاوے گی۔ ہر پڑھیار نوں اس آفر توں فائدہ حاصل کرنا چاہی دا اے۔"
          class="sm:w-[50vw]"
        />
      </div>
    </section>

    <!-- References Section -->
    <section class="prose max-w-[1440px] mx-auto mb-4">
      <h2 class="text-center">References</h2>

      <div
        class="not-prose grid grid-cols-[repeat(auto-fit,minmax(250px,1fr))] mx-6 gap-4 gap-y-6"
      >
        <ReferencesCard
          author="Khurram Mughal (Lahore)"
          blurb="Under the visionary leadership of Mr. Amjad Saleem Minhas, the convener of Sanjh, and the unwavering commitment of Mrs. Amjad, its Managing Director, Sanjh has flourished into a home for serious literature, especially in Punjabi and Urdu. 
          Both are known for their humility and deep respect for writers, readers, and the literary community — and it is this human connection that sets Sanjh apart."
          body="Sanjh Publications, Punjab's pride and a true guardian of Punjabi language and culture, has completed 20 exceptional years of literary service — a milestone that deserves heartfelt celebration. 
          
          Under the visionary leadership of Mr. Amjad Saleem Minhas, the convener of Sanjh, and the unwavering commitment of Mrs. Amjad, its Managing Director, Sanjh has flourished into a home for serious literature, especially in Punjabi and Urdu. Both are known for their humility and deep respect for writers, readers, and the literary community — and it is this human connection that sets Sanjh apart.
          
          Mr. Amjad Saleem Minhas is more than a publisher — he is a compassionate soul, a literary visionary, and a cultural custodian whose efforts have given countless writers a voice and readers a mirror to their roots.

          For two decades, Sanjh Publications has worked tirelessly to revive, preserve, and promote Punjabi language, literature, and cultural heritage — something few institutions have done with such sincerity and continuity. Their catalog is a rich blend of contemporary voices and timeless classics, all rooted in the soil of Punjab.

          Sanjh is more than a publishing house — it is a cultural movement, a safe haven for linguistic pride, and a bridge between generations. The humility and warmth of its founders reflect in every page they publish.

          In these 20 years, Sanjh has not only published books — it has built bridges between hearts, languages, and generations.

          Here's to Sanjh Publications — may the next 20 years shine even brighter!"
        />

        <ReferencesCard
          author="Sufi Nauman Yawer (Lahore)"
          blurb-urdu="کتابوں کی دکانوں کا تذکرہ ہو تو ذہن میں اکثر وہی روایتی منظر ابھرتا ہے. شیلفوں پر سجی کتابیں، بے رونق چہروں والے دکاندار، اور ایک سودا سا، جیسے الفاظ کو ترازو میں تولا جا رہا ہو۔ اگر آپ لاہور کی ٹیمپل روڈ سے صفاں والے چوک سے گزر کر مزنگ اڈے کی طرف مڑیں، تو بائیں ہاتھ ایک گلی میں ’سانجھ‘ نام کی ایسی کتابوں کی دکان واقع ہے جو دکان سے کہیں زیادہ ایک تہذیبی بیٹھک ہے، ایک علمی تھڑّا ہے، ایک ایسی جگہ جہاں کتابیں محض اشیائے تجارت نہیں بلکہ روح کی غذا بن کر آپ کا استقبال کرتی ہیں"
          body-urdu="
کتابوں کی دکانوں کا تذکرہ ہو تو ذہن میں اکثر وہی روایتی منظر ابھرتا ہے. شیلفوں پر سجی کتابیں، بے رونق چہروں والے دکاندار، اور ایک سودا سا، جیسے الفاظ کو ترازو میں تولا جا رہا ہو۔ اگر آپ لاہور کی ٹیمپل روڈ سے صفاں والے چوک سے گزر کر مزنگ اڈے کی طرف مڑیں، تو بائیں ہاتھ ایک گلی میں ’سانجھ‘ نام کی ایسی کتابوں کی دکان واقع ہے جو دکان سے کہیں زیادہ ایک تہذیبی بیٹھک ہے، ایک علمی تھڑّا ہے، ایک ایسی جگہ جہاں کتابیں محض اشیائے تجارت نہیں بلکہ روح کی غذا بن کر آپ کا استقبال کرتی ہیں۔

یہ ایک چھوٹی سی دکان ہے۔ باہر سے دیکھنے پر شاید معمولی لگے، مگر جیسے ہی آپ اندر قدم رکھتے ہیں، کتابوں کی خوشبو اور حرف کی حرارت آپ کو لپیٹ میں لے لیتی ہے۔ سامنے کمپیوٹر کے پیچھے ایک دھان پان سا شخص دکھائی دیتا ہے۔ بکھرے بال، چہرے پر چشمہ، اور آنکھوں میں ایک ایسی چمک جس میں کئی کہانیاں سمٹی ہوئی ہیں۔ یہی ہیں امجد سلیم منہاس ’سانجھ‘ کے روح رواں، دکان کے مالک، اور درحقیقت علم کے خادم۔

آپ کو دکان میں داخل ہوتا دیکھ کر وہ کچھ یوں مخاطب ہوتے ہیں، گویا برسوں کا یار ملا ہو:
’’گپ شپ کے آغاز میں پوچھ لیں گے چا تے پیو گے ناں؟‘‘

اور پھر کسی ملازم کو آواز دیتے ہیں کہ چائے بنا لاؤ یا پاس والی دکان سے لے آؤ۔ چائے کا دور چلتا ہے اور ساتھ ہی باتوں کا سلسلہ بھی۔ آپ کتاب لینے آئے ہوں یا محض جھانکنے، امجد صاحب پہلے آپ کی طبیعت کو پرکھیں گے، آپ کی دلچسپیوں کو سمجھیں گے، اور پھر اپنی الماریوں کے خزانے کھول دیں گے۔ ان کے ہاں ادیبوں دانشوروں صحافیوں اور سیاست میدان سے وابستہ افراد بھی بیٹھے ملیں گے۔ امجد صاحب کتاب کا تعارف کچھ یوں کراتے ہیں۔
’’ایہہ ویکھو، ایہہ نویں آئی اے، فلاں صاحب دی اے۔۔۔ تُسیں پڑھو گے تے مزہ آ جائے گا۔‘‘

سانجھ پر اردو اور پنجابی کی درجنوں کتابیں ایسی ملتی ہیں جو کہیں اور نایاب ہو چکی ہیں۔ یہاں تک کہ بعض ادبی جرائد تو ایسے ہیں جو اب صرف یہیں دستیاب ہیں۔ کتاب کی عدم دستیابی کا اعتراف کرتے ہی اس کے حصول پر گفتگو شروع کر دیتے ہیں۔  وہاں موجود کچھ امجد سلیم منہاس کی اپنی شائع کردہ مطبوعات بھی ہوتی ہیں، جن پر تیس سے چالیس فیصد تک رعایت دی جاتی ہے اور یہ رعایت محض قیمت کی نہیں بلکہ خلوص کی ہے، اُس علمی رشتے کی ہے جو وہ ہر گاہک سے جوڑتے ہیں۔

کوئی اگر پوچھے کہ کیا سانجھ کوئی فلاحی ادارہ ہے؟ تو جواب صاف ہے: نہیں، یہ ایک کاروبار ہے۔ مگر ایک ایسا کاروبار جو محبت سے چلتا ہے، ایک ایسی تجارت جس کا سرمایہ کتابیں نہیں، قاری کا اعتبار ہے۔ امجد صاحب کتاب بیچنے سے پہلے قاری کو جیتنے کا فن جانتے ہیں۔

کتاب دوستوں کیلئے مشورہ ہے:
اگر لاہور میں ہو اور کتاب خریدنی ہو، تو سیدھا سانجھ چلے جانا۔ کتاب خریدو یا نہ خریدو، مگر امجد سلیم منہاس سے کتابوں کی بات ضرور کرنا۔
وہ تمہیں کتابوں کے پیچھے چھپے زمانے دکھائیں گے، وہ سطر در سطر تمہیں ایسے مصنفین سے ملوائیں گے جن کے لفظ دھڑکتے ہیں۔
اور اگر کبھی پیسوں کی کمی ہو، تو خریدا ہوا بل مجھے بھیج دینا، میں ادا کر دوں گا۔ مگر ایک کتاب دوست کی حوصلہ افزائی ضرور کرنا۔
سانجھ ایک دکان نہیں، ایک تجربہ ہے۔ یہ ان گنی چنی جگہوں میں سے ہے جہاں لفظ آج بھی زندہ ہیں، اور جہاں قاری اب بھی پرتپاک انداز میں استقبال ہوتا ہے۔"
        />

        <ReferencesCard
          author="Talha Minhas (Bielefeld)"
          blurb="Sanjh is an absolute gem - an oasis for book lovers of Pakistan, thirsty for knowledge. I am very grateful for Sanjh that has enlightened and enriched the lives of so many. I wish to see Sanjh growing into an even bigger platform for generations to come."
        />
      </div>
    </section>
  </div>
</template>
