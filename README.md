
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bamboenyi - Electronic Press Kit (EPK)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&family=Playfair+Display:ital,wght@0,600;0,700;1,400&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
        }
        h1, h2, h3, .serif-font {
            font-family: 'Playfair Display', serif;
        }
    </style>
</head>
<body class="bg-stone-950 text-stone-100 antialiased selection:bg-amber-600 selection:text-white">

    <header class="sticky top-0 z-50 bg-stone-950/90 backdrop-blur border-b border-stone-800 px-4 py-3">
        <div class="max-w-4xl mx-auto flex justify-between items-center">
            <div class="flex items-center gap-2">
                <img src="BAMBOENYI LOGO.png" alt="Bamboenyi Logo" class="w-7 h-7 rounded-full object-cover border border-amber-500/50" onerror="this.src='https://placehold.co/40x40/1c1917/d97706?text=B'">
                <span class="text-xs uppercase tracking-widest text-amber-500 font-semibold">Bamboenyi EPK</span>
            </div>
            <div class="flex items-center gap-2">
                <span class="text-xs text-stone-400">Language:</span>
                <select id="langSelect" onchange="changeLanguage(this.value)" class="bg-stone-900 border border-stone-700 text-stone-200 text-xs rounded px-2 py-1 focus:outline-none focus:border-amber-500">
                    <option value="id" selected>Bahasa Indonesia</option>
                    <option value="en">English</option>
                    <option value="ja">日本語 (Japanese)</option>
                    <option value="zh">中文 (Chinese)</option>
                </select>
            </div>
        </div>
    </header>

    <main class="max-w-4xl mx-auto my-8 bg-stone-900 border border-stone-800 shadow-2xl overflow-hidden rounded-xl">
        
        <section class="relative bg-gradient-to-b from-stone-900 via-stone-900/90 to-stone-950 px-8 py-16 text-center border-b border-stone-800">
            <div class="absolute inset-0 opacity-20 bg-[radial-gradient(#d97706_1px,transparent_1px)] [background-size:16px_16px]"></div>
            <div class="relative z-10 flex flex-col items-center">
                <div class="w-24 h-24 mb-4 rounded-full border-2 border-amber-500/70 overflow-hidden shadow-xl bg-stone-950 flex items-center justify-center p-1">
                    <img src="BAMBOENYI LOGO.png" alt="Bamboenyi Official Logo" class="w-full h-full object-cover rounded-full" onerror="this.src='https://placehold.co/100x100/1c1917/d97706?text=BAMBOENYI'">
                </div>
                <span class="inline-block uppercase tracking-[0.3em] text-xs font-semibold text-amber-500 mb-3 bg-amber-950/40 px-3 py-1 rounded-full border border-amber-800/55" data-i18n="badge">
                    Official Electronic Press Kit
                </span>
                <h1 class="text-5xl md:text-6xl font-bold tracking-tight text-white mb-4">
                    BAMBOENYI
                </h1>
                <p id="tagline" class="text-lg md:text-xl text-amber-200/80 italic font-light max-w-2xl mx-auto mb-6">
                    "Contemporary Bamboo Orchestra & World Music Ensemble"
                </p>
                <div class="flex justify-center items-center gap-4 text-xs text-stone-400 uppercase tracking-widest">
                    <span>Bandung, Indonesia</span>
                    <span>•</span>
                    <span data-i18n="global_ready">Global Stage & Diplomatic Reception Ready</span>
                </div>
            </div>
        </section>

        <section class="px-8 py-12 border-b border-stone-800/60">
            <h2 class="text-2xl font-bold text-amber-500 mb-4 flex items-center gap-3">
                <span class="w-8 h-[2px] bg-amber-500"></span> <span data-i18n="about_title">About Bamboenyi</span>
            </h2>
            <div id="about_text_container" class="space-y-4 text-stone-300 leading-relaxed text-base font-light">
                <p data-i18n="p1">
                    Melalui surat elektronik ini, izinkan kami memperkenalkan <strong>Bamboenyi</strong>, sebuah sanggar seni dan kelompok musik asal Bandung, Indonesia, yang berfokus pada inovasi musik angklung tradisional yang dipadukan dengan sentuhan modern.
                </p>
                <p data-i18n="p2">
                    Bamboenyi hadir untuk membawa warna baru dalam diplomasi budaya melalui pendekatan World Music. Dalam setiap pementasannya, kami memadukan kehangatan suara angklung multilaras dengan aransemen sequencer elektronik modern serta karya-karya orisinal yang segar. Selain itu, kami juga membawa misi edukasi melalui pengenalan metode aransemen dan aplikasi digital penulisan notasi angklung yang kami kembangkan sendiri.
                </p>
                <p data-i18n="p3">
                    Meskipun berbasis di Indonesia, para personel inti Bamboenyi memiliki rekam jejak dan pengalaman pementasan internasional di berbagai belahan dunia (termasuk pengalaman sukses di Jepang serta negara-negara di Asia, Timur Tengah, dan Afrika). Sebelumnya, kiprah artistik kami juga pernah didukung dan dikurasi melalui program pendanaan kebudayaan nasional (Dana Indonesiaraya).
                </p>
            </div>
        </section>

        <section class="px-8 py-12 bg-stone-900/50 border-b border-stone-800/60">
            <h2 class="text-2xl font-bold text-amber-500 mb-4 flex items-center gap-3">
                <span class="w-8 h-[2px] bg-amber-500"></span> <span data-i18n="programs_title">Program Penawaran & Kolaborasi Global</span>
            </h2>
            <p class="text-stone-300 text-sm mb-6 leading-relaxed" data-i18n="programs_desc">
                Sehubungan dengan agenda pengembangan jejaring budaya ke kancah global, kami bermaksud menawarkan program pementasan khusus—terutama untuk memeriahkan <strong>acara resepsi diplomatik</strong>, perayaan hari nasional, malam kebudayaan (cultural night), pameran pariwisata, maupun kegiatan pertukaran pelajar di universitas setempat.
            </p>
            <div class="grid md:grid-cols-2 gap-6 pt-2">
                <div class="border-l-2 border-amber-500 pl-4 bg-stone-950/40 p-4 rounded-r-lg">
                    <h3 class="font-semibold text-white mb-1 text-sm" data-i18n="pr1_title">Resepsi Diplomatik & VIP</h3>
                    <p class="text-stone-400 text-xs leading-relaxed" data-i18n="pr1_desc">
                        Pementasan elegan untuk tamu kenegaraan, korps diplomatik, dan acara gala resmi.
                    </p>
                </div>
                <div class="border-l-2 border-amber-500 pl-4 bg-stone-950/40 p-4 rounded-r-lg">
                    <h3 class="font-semibold text-white mb-1 text-sm" data-i18n="pr2_title">Festival Budaya & Konser</h3>
                    <p class="text-stone-400 text-xs leading-relaxed" data-i18n="pr2_desc">
                        Panggung dunia memadukan kehangatan akustik bambu dan ketukan sequencer modern.
                    </p>
                </div>
                <div class="border-l-2 border-amber-500 pl-4 bg-stone-950/40 p-4 rounded-r-lg">
                    <h3 class="font-semibold text-white mb-1 text-sm" data-i18n="pr3_title">Lokakarya & Edukasi</h3>
                    <p class="text-stone-400 text-xs leading-relaxed" data-i18n="pr3_desc">
                        Pelatihan angklung dengan metode interaktif yang mudah dan menarik, pengenalan aplikasi digital, serta metode aransemen kreatif.
                    </p>
                </div>
                <div class="border-l-2 border-amber-500 pl-4 bg-stone-950/40 p-4 rounded-r-lg">
                    <h3 class="font-semibold text-white mb-1 text-sm" data-i18n="pr4_title">Kolaborasi Tari Tradisional</h3>
                    <p class="text-stone-400 text-xs leading-relaxed" data-i18n="pr4_desc">
                        Didukung oleh talent penari tradisional profesional yang gerakannya diiringi langsung oleh aransemen musik angklung modern.
                    </p>
                </div>
            </div>
        </section>

        <!-- INSTAGRAM PREVIEW SECTION -->
        <section class="px-8 py-12 border-b border-stone-800/60 bg-stone-950/30">
            <div class="flex justify-between items-center mb-6">
                <div>
                    <h2 class="text-2xl font-bold text-amber-500 flex items-center gap-3">
                        <span class="w-8 h-[2px] bg-amber-500"></span> <span data-i18n="ig_title">Instagram Feed Preview</span>
                    </h2>
                    <p class="text-xs text-stone-400 mt-1" data-i18n="ig_subtitle">Ikuti aktivitas terbaru kami di Instagram @bamboenyi</p>
                </div>
                <a href="https://instagram.com/bamboenyi" target="_blank" class="px-4 py-2 bg-gradient-to-r from-purple-600 to-pink-600 text-white font-semibold text-xs tracking-wider uppercase rounded-lg hover:opacity-90 transition flex items-center gap-2">
                    <span>Follow @bamboenyi</span>
                </a>
            </div>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <a href="https://instagram.com/bamboenyi" target="_blank" class="group relative bg-stone-900 border border-stone-800 rounded-lg overflow-hidden aspect-square block">
                    <img src="https://placehold.co/300x300/1c1917/d97706?text=Bamboenyi+Live" alt="Instagram Post 1" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="this.src='https://placehold.co/300x300/1c1917/d97706?text=Bamboenyi'">
                    <div class="absolute inset-0 bg-black/60 opacity-0 group-hover:opacity-100 transition duration-300 flex items-center justify-center p-4 text-center">
                        <p class="text-xs text-white font-medium">❤️ Interactive Angklung Session</p>
                    </div>
                </a>
                <a href="https://instagram.com/bamboenyi" target="_blank" class="group relative bg-stone-900 border border-stone-800 rounded-lg overflow-hidden aspect-square block">
                    <img src="https://placehold.co/300x300/1c1917/d97706?text=Traditional+Dance" alt="Instagram Post 2" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="this.src='https://placehold.co/300x300/1c1917/d97706?text=Bamboenyi'">
                    <div class="absolute inset-0 bg-black/60 opacity-0 group-hover:opacity-100 transition duration-300 flex items-center justify-center p-4 text-center">
                        <p class="text-xs text-white font-medium">✨ Traditional Dance & Modern Angklung</p>
                    </div>
                </a>
                <a href="https://instagram.com/bamboenyi" target="_blank" class="group relative bg-stone-900 border border-stone-800 rounded-lg overflow-hidden aspect-square block">
                    <img src="https://placehold.co/300x300/1c1917/d97706?text=Japan+Tour" alt="Instagram Post 3" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="this.src='https://placehold.co/300x300/1c1917/d97706?text=Bamboenyi'">
                    <div class="absolute inset-0 bg-black/60 opacity-0 group-hover:opacity-100 transition duration-300 flex items-center justify-center p-4 text-center">
                        <p class="text-xs text-white font-medium">🌏 Global Stage & Diplomatic Events</p>
                    </div>
                </a>
                <a href="https://instagram.com/bamboenyi" target="_blank" class="group relative bg-stone-900 border border-stone-800 rounded-lg overflow-hidden aspect-square block">
                    <img src="https://placehold.co/300x300/1c1917/d97706?text=Rehearsal+Studio" alt="Instagram Post 4" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="this.src='https://placehold.co/300x300/1c1917/d97706?text=Bamboenyi'">
                    <div class="absolute inset-0 bg-black/60 opacity-0 group-hover:opacity-100 transition duration-300 flex items-center justify-center p-4 text-center">
                        <p class="text-xs text-white font-medium">🎵 Original Composition & Sequencer</p>
                    </div>
                </a>
            </div>
        </section>

        <footer class="px-8 py-12 bg-stone-950 text-center">
            <h2 class="text-2xl font-bold text-amber-500 mb-4" data-i18n="footer_title">Tautan Portofolio & Kontak</h2>
            <p class="text-stone-400 text-sm mb-6 max-w-lg mx-auto" data-i18n="footer_desc">
                Sebagai bahan pertimbangan Bapak/Ibu, silakan jelajahi tautan video penampilan dan portofolio lengkap kami di bawah ini:
            </p>
            
            <div class="flex flex-wrap justify-center gap-4 mb-8">
                <a href="https://www.youtube.com/@bamboenyientertainment45" target="_blank" class="px-6 py-2.5 bg-red-700 hover:bg-red-600 text-white font-semibold text-xs tracking-wider uppercase rounded transition flex items-center gap-2">
                    <span>📺 YouTube Showreel</span>
                </a>
                <a href="https://instagram.com/bamboenyi" target="_blank" class="px-6 py-2.5 bg-gradient-to-r from-purple-600 to-pink-600 hover:opacity-90 text-white font-semibold text-xs tracking-wider uppercase rounded transition flex items-center gap-2">
                    <span>📸 Instagram @bamboenyi</span>
                </a>
            </div>

            <div class="border-t border-stone-800/80 pt-6 text-xs text-stone-400 space-y-2">
                <p><strong class="text-stone-200" data-i18n="director">Direktur / Pimpinan:</strong> Yoga Andika</p>
                <p><strong class="text-stone-200">Email:</strong> <a href="mailto:bamboenyi@gmail.com" class="text-amber-400 hover:underline">bamboenyi@gmail.com</a> | <strong class="text-stone-200" data-i18n="whatsapp">WhatsApp:</strong> <a href="https://wa.me/6281112347397" target="_blank" class="text-amber-400 hover:underline">+62 811-1234-7397</a></p>
                <p class="text-stone-400 pt-2">© 2026 Bamboenyi. All Rights Reserved.</p>
            </div>
        </footer>

    </main>

    <script>
        const translations = {
            id: {
                badge: "Official Electronic Press Kit",
                tagline: "\"Orkestra Bambu Kontemporer & Ensemble Musik Dunia\"",
                global_ready: "Siap Panggung Global & Resepsi Diplomatik",
                about_title: "Tentang Bamboenyi",
                p1: "Melalui surat elektronik ini, izinkan kami memperkenalkan <strong>Bamboenyi</strong>, sebuah sanggar seni dan kelompok musik asal Bandung, Indonesia, yang berfokus pada inovasi musik angklung tradisional yang dipadukan dengan sentuhan modern.",
                p2: "Bamboenyi hadir untuk membawa warna baru dalam diplomasi budaya melalui pendekatan World Music. Dalam setiap pementasannya, kami memadukan kehangatan suara angklung multilaras dengan aransemen sequencer elektronik modern serta karya-karya orisinal yang segar. Selain itu, kami juga membawa misi edukasi melalui pengenalan metode aransemen dan aplikasi digital penulisan notasi angklung yang kami kembangkan sendiri.",
                p3: "Meskipun berbasis di Indonesia, para personel inti Bamboenyi memiliki rekam jejak dan pengalaman pementasan internasional di berbagai belahan dunia (termasuk pengalaman sukses di Jepang serta negara-negara di Asia, Timur Tengah, dan Afrika). Sebelumnya, kiprah artistik kami juga pernah didukung dan dikurasi melalui program pendanaan kebudayaan nasional (Dana Indonesiaraya).",
                programs_title: "Program Penawaran & Kolaborasi Global",
                programs_desc: "Sehubungan dengan agenda pengembangan jejaring budaya ke kancah global, kami bermaksud menawarkan program pementasan khusus—terutama untuk memeriahkan <strong>acara resepsi diplomatik</strong>, perayaan hari nasional, malam kebudayaan (cultural night), pameran pariwisata, maupun kegiatan pertukaran pelajar di universitas setempat.",
                pr1_title: "Resepsi Diplomatik & VIP",
                pr1_desc: "Pementasan elegan untuk tamu kenegaraan, korps diplomatik, dan acara gala resmi.",
                pr2_title: "Festival Budaya & Konser",
                pr2_desc: "Panggung dunia memadukan kehangatan akustik bambu dan ketukan sequencer modern.",
                pr3_title: "Lokakarya & Edukasi",
                pr3_desc: "Pelatihan angklung dengan metode interaktif yang mudah dan menarik, pengenalan aplikasi digital, serta metode aransemen kreatif.",
                pr4_title: "Kolaborasi Tari Tradisional",
                pr4_desc: "Didukung oleh talent penari tradisional profesional yang gerakannya diiringi langsung oleh aransemen musik angklung modern.",
                ig_title: "Instagram Feed Preview",
                ig_subtitle: "Ikuti aktivitas terbaru kami di Instagram @bamboenyi",
                footer_title: "Tautan Portofolio & Kontak",
                footer_desc: "Sebagai bahan pertimbangan Bapak/Ibu, silakan jelajahi tautan video penampilan dan portofolio lengkap kami di bawah ini:",
                director: "Direktur / Pimpinan:",
                whatsapp: "WhatsApp:"
            },
            en: {
                badge: "Official Electronic Press Kit",
                tagline: "\"Contemporary Bamboo Orchestra & World Music Ensemble\"",
                global_ready: "Global Stage & Diplomatic Reception Ready",
                about_title: "About Bamboenyi",
                p1: "Through this email, allow us to introduce <strong>Bamboenyi</strong>, an art collective and music ensemble from Bandung, Indonesia, focusing on the innovation of traditional angklung music blended with a modern touch.",
                p2: "Bamboenyi brings a fresh perspective to cultural diplomacy through a World Music approach. In every performance, we combine the warm resonance of multi-tuned angklung with modern electronic sequencer arrangements and fresh original compositions. Furthermore, we carry an educational mission by introducing proprietary arrangement methods and digital angklung notation apps developed in-house.",
                p3: "Based in Indonesia, Bamboenyi's core personnel carry a strong track record of international performance experience across the globe (including successful runs in Japan, as well as countries across Asia, the Middle East, and Africa). Previously, our artistic endeavors have also been supported and curated through the national cultural funding program (Dana Indonesiaraya).",
                programs_title: "Performance & Global Collaboration Programs",
                programs_desc: "In connection with our global cultural networking agenda, we would like to offer special performance programs—particularly designed to enliven <strong>diplomatic receptions</strong>, national day celebrations, cultural nights, tourism exhibitions, and student exchange activities at local universities.",
                pr1_title: "Diplomatic Receptions & VIPs",
                pr1_desc: "Elegant showcases tailored for state guests, diplomatic corps, and official gala events.",
                pr2_title: "Cultural Festivals & Concerts",
                pr2_desc: "World stages blending acoustic bamboo warmth with modern sequencer beats.",
                pr3_title: "Workshops & Education",
                pr3_desc: "Angklung training featuring easy and engaging interactive methods, digital app introductions, and creative arrangement techniques.",
                pr4_title: "Traditional Dance Collaboration",
                pr4_desc: "Supported by professional traditional dancers whose choreography is harmonized live with modern angklung music arrangements.",
                ig_title: "Instagram Feed Preview",
                ig_subtitle: "Follow our latest updates on Instagram @bamboenyi",
                footer_title: "Portfolio Links & Contact",
                footer_desc: "For your kind consideration, please explore our performance video links and full portfolio below:",
                director: "Director / Leader:",
                whatsapp: "WhatsApp:"
            },
            ja: {
                badge: "公式電子プレスキット (EPK)",
                tagline: "「コンテンポラリー・バンブー・オーケストラ & ワールド・ミュージック・アンサンブル」",
                global_ready: "世界基準のステージ & 外交レセプション対応",
                about_title: "バンボエニについて",
                p1: "本メールを通지まして、インドネシア・バンドゥンを拠点とする芸術集団・音楽アンサンブル<strong>Bamboenyi（バンボエニ）</strong>をご紹介いたします。私たちは伝統的なアンクルン音楽の革新と現代的なアレンジの融合に注力しています。",
                p2: "バンボエニは、ワールドミュージックのアプローチを通じて文化外交に新たな彩りをもたらします。毎回の演奏では、マルチチューン竹楽器の温かい響きと、現代のエレクトロニック・シーケンサーによるアレンジ、そして新鮮なオリジナル曲を融合させています。さらに、独自に開発したデジタルアンクルン記譜アプリや編曲手法の紹介を通じた教育的ミッションも担っています。",
                p3: "インドネシアを拠点としながらも、コアメンバーは日本をはじめ、アジア、中東、アフリカなど世界各地での豊富な国際演奏実績を持っています。これまでの芸術活動は、国家の文化資金提供プログラム（Dana Indonesiaraya）の支援とキュレーションも受けてまいりました。",
                programs_title: "プログラムのご案内 & グローバルコラボレーション",
                programs_desc: "グローバルな文化ネットワーキングの推進にあたり、<strong>外交レセプション</strong>、ナショナルデーの祝賀会、文化夜会（カルチュラルナイト）、観光展、現地の大学での交流イベントなどを彩る特別演奏プログラムをご提案いたします。",
                pr1_title: "外交レセプション & VIP",
                pr1_desc: "国賓や外交団、公式ガラディナーに向けた洗練されたショーケース。",
                pr2_title: "文化フェスティバル & コンサート",
                pr2_desc: "竹のアコースティックな温もりと現代のシーケンサービートが融合したワールドステージ。",
                pr3_title: "ワークショップ & 教育",
                pr3_desc: "簡単で魅力的なインタラクティブ手法を用いたアンクルン指導、デジタルアプリの紹介、創造的な編曲法。",
                pr4_title: "伝統舞踊コラボレーション",
                pr4_desc: "現代的なアンクルン音楽に合わせて優雅に舞う、プロの伝統舞踊タレントとの共演。",
                ig_title: "Instagram フィードプレビュー",
                ig_subtitle: "Instagram @bamboenyi で最新情報をフォローしてください",
                footer_title: "ポートフォリオリンク & お問い合わせ",
                footer_desc: "ご検討の参考として、以下のパフォーマンス動画およびポートフォリオをご覧ください。",
                director: "ディレクター / リーダー:",
                whatsapp: "WhatsApp:"
            },
            zh: {
                badge: "官方电子新闻资料袋 (EPK)",
                tagline: "\"当代竹乐团与世界音乐重奏组\"",
                global_ready: "随时准备迎接全球舞台与外交招待会",
                about_title: "关于 Bamboenyi",
                p1: "谨通过本邮件向您介绍<strong>Bamboenyi</strong>，这是一个来自印度尼西亚万隆的艺术团体与音乐组合，专注于将传统昂克隆音乐与现代元素相结合的创新。",
                p2: "Bamboenyi 致力于通过世界音乐的视角为文化外交带来全新色彩。在每一次演出中，我们将多调昂克隆的温暖共鸣与现代电子音序器编排以及清新的原创作品相融合。此外，我们还通过介绍自主研发的昂克隆数字记谱应用和编曲方法来践行教育使命。",
                p3: "尽管立足于印尼，Bamboenyi 的核心成员拥有丰富的全球巡演经验（包括在日本以及亚洲、中东和非洲多国的成功演出经历）。此前，我们的艺术成果曾获得国家文化资助项目（Dana Indonesiaraya）的支持与策划。",
                programs_title: "演出项目与全球合作",
                programs_desc: "为拓展全球文化交流网络，我们诚挚推出特别演出项目——尤其适合为<strong>外交招待会</strong>、国庆庆典、文化之夜（Cultural Night）、旅游博览会以及当地大学的师生交流活动增添光彩。",
                pr1_title: "外交招待会与贵宾接待",
                pr1_desc: "专为国家元首、外交使节及官方晚宴打造的精致演出。",
                pr2_title: "文化艺术节与音乐会",
                pr2_desc: "将竹乐原声底蕴与现代音序器节奏完美交织的世界级舞台。",
                pr3_title: "工作坊与音乐教育",
                pr3_desc: "采用简单生动、趣味盎然的互动方式进行昂克隆教学，介绍数码记谱应用与创意编曲。",
                pr4_title: "传统舞蹈跨界合作",
                pr4_desc: "搭配专业传统舞蹈演员，其优美舞姿由现代昂克隆音乐进行现场伴奏。",
                ig_title: "Instagram 动态预览",
                ig_subtitle: "在 Instagram 上关注我们的最新动态 @bamboenyi",
                footer_title: "作品集链接与联系方式",
                footer_desc: "供您审阅参考，请通过下方链接查看我们的演出视频与完整作品集：",
                director: "总监 / 负责人：",
                whatsapp: "WhatsApp："
            }
        };

        function changeLanguage(lang) {
            const t = translations[lang];
            if (!t) return;
            
            document.querySelectorAll('[data-i18n]').forEach(el => {
                const key = el.getAttribute('data-i18n');
                if (t[key]) {
                    el.innerHTML = t[key];
                }
            });

            if (lang === 'ja' || lang === 'zh') {
                document.getElementById('tagline').innerText = t.tagline;
            } else if (lang === 'en') {
                document.getElementById('tagline').innerText = '"Contemporary Bamboo Orchestra & World Music Ensemble"';
            } else {
                document.getElementById('tagline').innerText = '"Orkestra Bambu Kontemporer & Ensemble Musik Dunia"';
            }
        }
    </script>
</body>
</html>
