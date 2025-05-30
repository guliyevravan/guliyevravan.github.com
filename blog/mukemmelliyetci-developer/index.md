# Mükəmməlliyətçi developer

![Sekil](https://media.licdn.com/dms/image/v2/D4E12AQF6gyaNOM2cjw/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1726051243181?e=1753920000&v=beta&t=bOKUlBcZ11HuMn3Rstc92tnPcUOq4KAZjxN-d7-Lu-A){:class="max-w-[200px]"}

Bugün sizə yaxşı bir şey kimi görünən, lakin həm vaxtınızı, həm enerjinizi alan bu xüsusiyyətdən danışmaq istəyirəm.

Yazdığım məqalə 3-cü şəxslərdən aldığınız sifarişlərə və kollektiv işlədiyiniz layihələrə aid deyil. Mən nümunələrimdə layihənizin vebsayt olduğunu güman edərək ondan **_"Sayt"_** deyərək danışacam. 

## Mükəmməlliyətçinin sonsuz döngüsü

Axşam parkda gəzinti edirsən və ağlına mükəmməl (ən azından sənin üçün) bir ideya gəlir. Onsuz da əlində hansısa sifariş də yoxdur. Mütləq başlamaq lazımdır. Tez bir zamanda bu ideyanı həyata keçirməlisən. Axırki öz saytınla gəlir əldə etmə fürsəti qazana biləcəyini düşünürsən.

Bütün hazırlıqlarını görürsən, **_project_client_** və **_project_server_** qovluqları da hazırdır. Hətta github repository belə yaradıbsan. Nə gözəl. Kim bilərdi ki, 2 il əvvəl yaratdığın digər yarımçıq repository'lər orda gözü yaşlı səni izləyir.

Saytı hazırlamağa başlayırsan. Əvvəlcə **qeydiyyat** bölməsi hazır olmalıdır. Bütün inputları hazırladın. Göndərə klikləndiyində lazımi təhlükəsizlik tədbirlərini gördün, məlumatları DB'ə əlavə etdin. Çox sevinclisən. Axırki qeydiyyat hissəsi bitdi. Giriş hissəsinə keçə bilərsən və içindəki səs birdən sənə səslənir. Niyə ziyarətçi adını boş qoyursa bunu server'ə göndərməmişdən əvvəl front'da yoxlamıram? Düz edirsən. Axı milyonlarla insan saytını ziyarət etmək üçün sırada gözləyir. Resursları indidən düzgün idarə etməlisən. Elə deyilmi?

Axırki qeydiyyat hissəsi bitdi. Heç kim ad hissəsini boş qoya bilməyəcək. Boş qoysa sorğu server'ə göndərilməyəcək. Nə gözəl. Əhsən sənə dostum! Sən artıq serverə 10000$ yerinə 9000$ ödəyəcəksən. Giriş hissəsinə keçə bilərsən. 1 dəqiqə. Axı **captcha** yoxdur. Birdən kimsə bot yazıb 10000 dəfə qeydiyyatdan keçsə nolacaq? Captcha hissəsini də yaratmalısan. Afərin! Sən əjdahasan. Başa düşdün ki, bütün "XAKER"lər Kali Linux yüklü komputerləriylə sənin saytının bitməsini gözləyirlər.

Yenə bəxtin gətirdi. Qeydiyyatdan keçərkən istifadə etdiyin field'lər giriş hissəsində də mövcuddur. Nə xoşbəxt insansan sən. Email və Şifrə field'lərini **_qeydiyyat_** hissəsindən giriş hissəsinə kopyalayıb atdın. Özün də bilmirdin ki, **_giriş_** hissəsi bu qədər rahat olacaq. Dayan. Axı sən developersən. Nə vaxtsa SOLID deyə bir şey görmüşdün. İndi yadında deyil hansı hərfinə aiddir, amma sən özünü təkrarladın. Bəlkə bütün field'ləri component halına salasan? Eybi yoxdur, 1 saatla heç nə olmaz. 

Artıq o qədər yorulubsan ki, zehni və fiziki olaraq taqətin qalmayıb. Neçə gündür dəli kimi kod yazırsan, amma hələ gözəçarpan irəliləyiş yoxdur. Eybi yoxdur, əsas odur ki, ortaya çıxardacağın məhsul mükəmməl olacaq.

Yeni bir gün, səhər yuxudan elə enerjili oyanıbsan ki, Formula1 pilotları ilə yarışacaq sürətdə komputerini yandırırsan. İstifadəçilər saytında məqalə paylaşacaq. Hər şey əladır. Məqalənin başlıq hissəsi olacaq, internetdən tapdığın heç vaxt tam ürəyinə yatmayacaq **Rich Textbox**'u da saytına inteqrasiya etdin. Artıq sənin istifadəçilərin yazıları **qalın** da yaza biləcək, hətta şəkil də yükləyə biləcəklər. Sən mükəmməlsən. Şükür, bu hissə də bitdi. Dayan! Bəs digər istifadəçilər rəy bildirsə necə? Əla olardı e 🥹. Məncə rəy bölməsi də hazırla. Təcili rəy üçün də DB-də rəy cədvəl yarat. Bəs rəy məqaləyə bağlı olmalıdır axı. O qədər **_relational database_** filan boşunamı öyrəndin bu qədər şeyi. Məqalənin ID'si ilə rəyin ID'si arasında DB səviyyəsində də əlaqə yarat. Nə gözəl. Vaxt çoxdur. Rahat ol.

Rəylər də hazırdır. Artıq Fəqan rəylərdə Gülnarın məqaləsinə söz soxa bilər. Məqaləyə smile filan da atmaq olsun. Mark, sən kimsən axı? Mənim saytımın qabağında baş əyəcəksən. 1 dəqiqə. Fəqan Gülnara söz soxdu bəs Gülnar ona necə cavab verəcək? Hansısa rəyə cavab vermək funksionallığı da əlavə et. Rəylərin bir-biri ilə əlaqəsini DB səviyyəsində qur. DB strukturun dəyişməlidir. Mövcud kodunda da rəylərdə bir aləm dəyişikliklər etməlisən. 

Komputeri keçirt. Sabah gedib Starbucks'da gic-gic stickerli Macbook'unu qabağına qoyub Latteni içə-içə kodunu yazarsan. Hələ 5 qəpiklik xeyrin yoxdur, amma eybi yox. Gələcəyə yatırım edirsən. Bu layihə **"partdadacaq"**. 

## Nə baş verdi?

Onsuz da yazdıqlarımdam az-çox nə deməyə çalışdığımı anladınız. O layihə heç vaxt bitməyəcək. Siz də bilirsiniz. Lazımsız şeylərə o qədər vaxt sərf etdiniz ki, artıq nə əvvəlki enerjiniz qalıb, nə də layihənin mükəmməl olduğunu düşünürsünüz.

Özünüzə o qədər böyük hədəflər qoydunuz ki, yenə uğursuzluq hissini yaşadınız. Özünüzü daim aşağıladınız. Daha mükəmməl funksionallıq və ya daha mükəmməl kod ağlınıza gələndə əvvəlki əziyyətiniz gözünüzdən düşdü. Halbuki necə əziyyət çəkmişdiniz o kodu yazmaq üçün. Artıq yazdığınız kodlardan əvvəlki kimi zövq ala bilmirsiniz. Köhnə vaxtlarınızı düşünün. Necə xoşbəxt idiniz. Qeydiyyat hissəsində istifadəçinin adını DB-ə yazanda axır ki alınmışdı. Qeydiyyatdan keçən istifadəçinin şifrəsini belə olduğu kimi DB-yə yazdırırdınız, amma xoşbəxtiydiniz. Kod yazmaq sizin üçün zövqlüydü. O qədər xırdalıqları düşündünüz ki, sonu olmayan bir quyuya atılmış kimi hissedirsiniz. Hər dəfəsində yarımçıq qoymaq hissi isə özgüvəninizi yerlə bir etdi. 

Öz saytınızı hazırlayarkən mükəmməlliyətçilik sizin düşündüyünüz qədər yaxşı xüsusiyyət deyil, çünki hələ sizə gəlir gətirib gətirməyəcəyi bəlli olmayan bir iş üzərində günlərlə vaxtınızı sərf edirsiniz. Freelancer iş götürərkən layihəni mükəmməl hazırlamağın müqabilində ona uyğun da məvacib təyin edə bilirsiniz. Əvvəlcədən bütün bu mükəmməlliyətçi baxışınızı nəzərə alaraq müştəriyə layihənin bitmə tarixini bildirmək elə də çətin olmur. Öz işinizi gördükdə isə bir müddət sonra tükənmişlik sindromu ilə üz-üzə gəlirsiniz. 

## Nələrə diqqət etməliyəm?

**Saytınızı istifadə edən şəxslər developer deyil.**

Saytınızı istifadə edən şəxslərin developer olmadığını heç vaxt unutmayın. Hamı sizin kimi düşünmür. Bəzən günlərlə vaxtınızı sərf edib hazırladığınız hansısa funksionallıq bir başqası üçün çox adi, 1 saat vaxtınızı almayan funksionallıq isə mükəmməl sayılacaq. Çünki sizin necə kod yazdığınız, hansı dildə yazdığınız, hansı paradigmadan istifadə etdiyiniz, təmiz kod yazdığınız və s., insanlara maraqlı deyil. Onlar üçün maraqlı olan yalnız 1 sual var: "Bu sayt mənim problemimi həll edir, ya yox?"

Onlar üçün vacib olan digər məsələ isə dizayndır. Yaxşı dizayn edilmiş sayt, istifadəçilərin saytda qalma müddətini artıra bilər. İstifadəçilərin görmədiyi şeylərə fokuslanmaq yerinə ilkin mərhələdə normal bir dizayn ilə onları saytda tutmağa və məhsulunuzu almağa sövq edin.

**İlkin hədəflər qoyun.** 
  
Layihəyə başlamamışdan əvvəl ilkin hədəflər qoyun. **Kifayət qədər yaxşı** yazılmış sayt ilkin mərhələdə işinizi görəcək. Daha yaxşısını etməyə çalışmayın. Həmişə daha yaxşısı olacaq. Özünüzü bezdirməyin. İnsanlar sizin saytınıza daxil olduqda indikindən qat-qat enerjili olacağınıza əmin ola bilərsiniz. 

**Sadə olun.**

Sayta hər cür funksionallığı əlavə etməyə məcbur deyilsiniz. Saytınızın əsas məqsədini unutmayın. Əlavə funksionallıqları saytınızın populyarlığı artdıqca yaranan ehtiyaclara görə əlavə edə bilərsiniz. Hansıki əlavə etdiyiniz bu funksionallıqların bəlkə də 60-70% hissəsi ümumiyyətlə istifadə olunmayacaq. Tək olduğunuzu unutmayın. Bu işdə yanınızda heç kim yoxdur və siz robot deyilsiniz. İstədiyiniz funksionallıqları zamanla əlavə edə bilərsiniz. 

Məsələn PDF fayllarını birləşdirən bir saytınız var. Əgər istifadəçi saytınızda bu funksiyanı yerinə yetirə bilirsə ilkin mərhələdə bu sizin işinizi görəcək. PDF fayllarını yükləyəndə _"onun adını da saytdan dəyişdirib sonra yükləyə bilsin"_ bu funksiyanı da əlavə edim deməyin.

**Özünüzü təbrik edin.**

Mükəmməlliyətçi olduğunuz üçün hər zaman gördüyünüz işi gözünüzdə kiçildəcəksiniz. Özünüzə kənardan baxın. İllər əvvəl bildiklərinizlə indi bildiklərinizi müqayisə edin. Əvvəlki saytlarınıza baxın və necə özünüzü inkişaf etdirdiyinizdən xəbərdar olun. 

## Xülasə.

**Sonra daha çətin olmayacaq?**

Təbi ki, kodunuza aylar sonra yenidən baxarkən keçirdiyiniz hisləri çox yaxşı başa düşürəm. Bütün işləri indi etmək, 3 ay sonra etməkdən daha az vaxt tələb edəcək, amma indi tükənərək  işi yarıda buraxmaqdansa tez müddətdə saytı insanların istifadəsinə vermək məncə daha məqsədəuyğundur.

**Resurslara fikir verməyək?**

Resurslara fikir verin. Kodunuzu yazarkən ən optimal versiyalardan istifadə edin, amma ən mükəmməli bacarmağa çalışmayın. Sonradan da kodunuzda optimizasiyalar edə bilərsiniz. 

Sonda qeyd etmək istəyirəm ki, məqalə sırf mükəmməlliyətçilik üzərinə yazılıb. Nəyin doğru, nəyin yanlış olduğu qərarını siz verəcəksiniz.

Çatdırmağa çalışdığım tək bir fikir var: _Bacardığınızın **ən yaxşısısını** yox, **yaxşısını** edin._