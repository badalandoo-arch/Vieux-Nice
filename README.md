# Vieux-Nice<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guide du Voyageur - Rue Benoît Bunico, Vieux Nice</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        med: {
                            50: '#fdf8f6',
                            100: '#f2e8e5',
                            500: '#d97706',
                            600: '#b45309',
                            700: '#92400e',
                            800: '#78350f',
                            900: '#451a03',
                        },
                        azure: {
                            50: '#f0f9ff',
                            500: '#0ea5e9',
                            600: '#0284c7',
                            700: '#0369a1',
                            900: '#0c4a6e',
                        }
                    }
                }
            }
        }
    </script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .glass {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased selection:bg-azure-500 selection:text-white">

    <!-- BARRE DE LANGUES -->
    <header class="bg-slate-900 text-white py-2 px-4 sticky top-0 z-50 shadow-md">
        <div class="max-w-6xl mx-auto flex flex-wrap justify-between items-center gap-3">
            <div class="flex items-center space-x-2 text-sm font-medium">
                <i class="fa-solid fa-compass text-azure-400"></i>
                <span data-i18n="top_title">Guide Exclusif - Rue Benoît Bunico</span>
            </div>
            <!-- Sélecteur de langues -->
            <div class="flex items-center space-x-1.5 overflow-x-auto py-1">
                <span class="text-xs text-slate-400 mr-1"><i class="fa-solid fa-globe"></i></span>
                <button onclick="setLanguage('fr')" class="px-2.5 py-1 text-xs rounded font-medium bg-azure-600 text-white transition lang-btn" id="btn-fr">FR</button>
                <button onclick="setLanguage('en')" class="px-2.5 py-1 text-xs rounded font-medium bg-slate-800 text-slate-300 hover:bg-slate-700 transition lang-btn" id="btn-en">EN</button>
                <button onclick="setLanguage('it')" class="px-2.5 py-1 text-xs rounded font-medium bg-slate-800 text-slate-300 hover:bg-slate-700 transition lang-btn" id="btn-it">IT</button>
                <button onclick="setLanguage('es')" class="px-2.5 py-1 text-xs rounded font-medium bg-slate-800 text-slate-300 hover:bg-slate-700 transition lang-btn" id="btn-es">ES</button>
                <button onclick="setLanguage('de')" class="px-2.5 py-1 text-xs rounded font-medium bg-slate-800 text-slate-300 hover:bg-slate-700 transition lang-btn" id="btn-de">DE</button>
                <button onclick="setLanguage('ru')" class="px-2.5 py-1 text-xs rounded font-medium bg-slate-800 text-slate-300 hover:bg-slate-700 transition lang-btn" id="btn-ru">RU</button>
                <button onclick="setLanguage('zh')" class="px-2.5 py-1 text-xs rounded font-medium bg-slate-800 text-slate-300 hover:bg-slate-700 transition lang-btn" id="btn-zh">中文</button>
            </div>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section class="relative bg-gradient-to-br from-azure-900 via-sky-800 to-med-900 text-white py-16 px-6 overflow-hidden">
        <div class="absolute inset-0 opacity-20 bg-[radial-gradient(#38bdf8_1px,transparent_1px)] [background-size:16px_16px]"></div>
        <div class="max-w-4xl mx-auto text-center relative z-10">
            <span class="inline-block py-1 px-4 rounded-full bg-white/10 backdrop-blur-md text-azure-200 text-sm font-medium mb-4 border border-white/20" data-i18n="hero_badge">
                <i class="fa-solid fa-location-dot mr-1.5"></i> Départ : 14 rue Benoît Bunico • Vieux Nice
            </span>
            <h1 class="text-4xl md:text-5xl font-extrabold tracking-tight mb-4" data-i18n="hero_title">
                Votre Séjour Inoubliable à Nice
            </h1>
            <p class="text-lg md:text-xl text-slate-200 max-w-2xl mx-auto font-light" data-i18n="hero_subtitle">
                Toutes les activités, plages, marchés et bonnes adresses sont calculés à pied depuis votre logement.
            </p>
        </div>
    </section>

    <!-- CONTENU PRINCIPAL -->
    <main class="max-w-5xl mx-auto px-4 py-10 space-y-14">
        
        <!-- SECTION ACTIVITÉS -->
        <section>
            <h2 class="text-2xl font-bold text-slate-900 mb-6 flex items-center">
                <i class="fa-solid fa-star text-amber-500 mr-3"></i> <span data-i18n="sec_activities">À pied depuis votre logement</span>
            </h2>
            
            <div class="grid md:grid-cols-2 gap-6">
                <!-- Carte 1 : Ruelles du Vieux Nice -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://cdn.pap.fr/image/cms/96/9b/969b91abc601f4e79136b47c2ff8fd44/9-1200x800-s3.jpg" alt="Place Rossetti et cathédrale Sainte-Réparate, Vieux Nice" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-azure-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-azure-600"></i> <span data-i18n="dist_0min">Environ 1 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-amber-50 text-amber-700 rounded-full" data-i18n="tag_gastronomy">Gastronomie & Ruelles</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="card4_title">Cœur du Vieux Nice & Place Rossetti</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="card4_desc">Vous êtes au cœur du quartier historique ! Goûtez la socca traditionnelle, les panisses et les célèbres glaces artisanales de la Place Rossetti juste à côté.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Place+Rossetti,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-azure-700 hover:text-azure-800 bg-azure-50 hover:bg-azure-100 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Carte 2 : Cours Saleya -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://provence-alpes-cotedazur.com/app/uploads/crt-paca/2022/11/thumbs/Cours-saleya-nice-Istock-1200x900.jpg" alt="Cours Saleya à Nice, marché animé sous les auvents et terrasses des cafés" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-azure-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-azure-600"></i> <span data-i18n="dist_2min">Environ 4 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-azure-50 text-azure-700 rounded-full" data-i18n="tag_culture">Culture & Marché</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="card1_title">Le Cours Saleya & son Marché</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="card1_desc">À deux pas en descendant vers la mer : célèbre pour son marché aux fleurs coloré, ses étals de produits provençaux et ses antiquaires le lundi.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Cours+Saleya,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-azure-700 hover:text-azure-800 bg-azure-50 hover:bg-azure-100 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Carte 3 : Promenade des Anglais & Plages | Photo : Office de Tourisme Nice Côte d’Azur -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://cdn.iris-etourism.io/uploads/nice/8b5/76-141-40734028.webp" alt="Vue aérienne panoramique de la Promenade des Anglais, des plages et de la baie de Nice" loading="lazy" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-azure-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-azure-600"></i> <span data-i18n="dist_4min">Environ 6 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-blue-50 text-blue-700 rounded-full" data-i18n="tag_relax">Détente & Mer</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="card3_title">La Promenade des Anglais & Plages</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="card3_desc">Traversez le Cours Saleya pour rejoindre immédiatement le bord de mer, les plages de galets de la Baie des Anges et les mythiques chaises bleues.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Quai+des+%C3%89tats-Unis,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-azure-700 hover:text-azure-800 bg-azure-50 hover:bg-azure-100 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Carte 4 : Colline du Château | Photo : Tour Azur -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://www.tourazur.com/wp-content/uploads/2025/07/Colline-du-Chateau-Nice-4-1024x576.jpg" alt="Vue panoramique depuis la Colline du Château sur le Vieux Nice et la Baie des Anges" loading="lazy" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-azure-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-azure-600"></i> <span data-i18n="dist_5min">Environ 12 à 15 min à pied (montée)</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-emerald-50 text-emerald-700 rounded-full" data-i18n="tag_view">Panoramique</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="card2_title">La Colline du Château & Cascade</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="card2_desc">Vue imprenable sur la Baie des Anges, les toits ocre du Vieux Nice et le port. Accès rapide par les escaliers Lesage ou l'ascenseur gratuit.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Colline+du+Ch%C3%A2teau,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-azure-700 hover:text-azure-800 bg-azure-50 hover:bg-azure-100 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Carte 5 : Place Masséna & Coulée Verte -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://encrypted-tbn1.gstatic.com/licensed-image?q=tbn:ANd9GcStCsFdzR-n5gsP9IoKeVElsAKts1AmAAvx6i92TlAWwtbvtTiksB7YnGy6bpzc8wPdvo6cKnDxLTRDHP4" alt="Fontaine du Soleil, Place Masséna, Nice" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-azure-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-azure-600"></i> <span data-i18n="dist_6min">Environ 9 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-purple-50 text-purple-700 rounded-full" data-i18n="tag_shopping">Shopping & Parc</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="card5_title">Place Masséna & Promenade du Paillon</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="card5_desc">Le grand parc urbain avec son miroir d'eau rafraîchissant, suivi de l'emblématique Place Masséna et des rues commerçantes (avenue Jean Médecin).</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Place+Mass%C3%A9na,+06000+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-azure-700 hover:text-azure-800 bg-azure-50 hover:bg-azure-100 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>


                <!-- Carte 7 : Rue piétonne Masséna -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Rue_massena_nice_01.jpg?width=1200" alt="Vue de la rue Masséna piétonne à Nice, bordée de commerces" loading="lazy" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-azure-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-azure-600"></i> <span data-i18n="dist_pedestrian">Environ 11 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-rose-50 text-rose-700 rounded-full" data-i18n="tag_pedestrian">Shopping & balade</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="card_pedestrian_title">La rue piétonne Masséna</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="card_pedestrian_desc">Flânez dans le cœur commerçant de Nice, entre la place Masséna et la rue du Congrès. La rue Masséna et les rues voisines regorgent de boutiques, cafés et terrasses : idéal pour une promenade shopping à l’ambiance niçoise.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Rue+Massena,+06000+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-azure-700 hover:text-azure-800 bg-azure-50 hover:bg-azure-100 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Carte 8 : Galeries Lafayette -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Galeries_Lafayette_Nice.jpg?width=1200" alt="Façade des Galeries Lafayette Nice Masséna sur la place Masséna" loading="lazy" class="w-full h-full object-cover object-center group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-azure-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-azure-600"></i> <span data-i18n="dist_galeries">Environ 12 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-purple-50 text-purple-700 rounded-full" data-i18n="tag_galeries">Grand magasin • Shopping</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="card_galeries_title">Galeries Lafayette Nice Masséna</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="card_galeries_desc">Retrouvez les grandes marques, la mode, la beauté et les accessoires dans ce grand magasin emblématique, situé au 6 avenue Jean Médecin, près de la place Masséna. Une belle étape pour une séance shopping au centre de Nice.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Galeries+Lafayette+Nice+Massena,+6+Avenue+Jean+Medecin,+06000+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-azure-700 hover:text-azure-800 bg-azure-50 hover:bg-azure-100 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Carte 6 : Port Lympia & Place Garibaldi -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://encrypted-tbn2.gstatic.com/licensed-image?q=tbn:ANd9GcTknQUV_oQCZplY8MTTaA5hxxXunnQ4j6_5ye0HIVib726oAiWAg_6dhO8ERLOr2Vs10DI2DWiMhsd9yvU" alt="Pointus colorés au Port Lympia, Nice" loading="lazy" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-azure-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-azure-600"></i> <span data-i18n="dist_8min">Environ 9 à 12 min selon la destination</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-rose-50 text-rose-700 rounded-full" data-i18n="tag_port">Sorties & Port</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="card6_title">Place Garibaldi & Port Lympia</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="card6_desc">Quartier animé prisé des locaux pour ses terrasses ensoleillées, ses bars à vin, ses antiquaires et ses pointus colorés amarrés au port.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex flex-wrap gap-2.5 justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Place+Garibaldi,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-azure-700 hover:text-azure-800 bg-azure-50 hover:bg-azure-100 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps_garibaldi">Place Garibaldi (Maps)</span>
                        </a>
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Port+Lympia,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-azure-700 hover:text-azure-800 bg-azure-50 hover:bg-azure-100 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps_port">Port Lympia (Maps)</span>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION RESTAURATION & SPÉCIALITÉS NIÇOISES -->
        <section>
            <div class="mb-6">
                <h2 class="text-2xl font-bold text-slate-900 flex items-center">
                    <i class="fa-solid fa-utensils text-med-600 mr-3"></i> <span data-i18n="sec_food">Bonnes Tables & Spécialités Niçoises</span>
                </h2>
                <p class="text-slate-600 text-sm mt-1" data-i18n="sec_food_sub">Nos adresses incontournables autour de votre logement pour goûter l'authentique cuisine nissarte et italienne.</p>
            </div>

            <div class="grid md:grid-cols-2 gap-6">
                <!-- Resto 1 : Chez Félix — Le vrai Pan Bagnat -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-amber-50">
                            <img src="https://assets.nicematin.com/articles/10/65/48/59/OG-10654859-1200-800-5e74a1f_upload-from-url-1-gdx9xybcrhs5-data-art-16518914.jpg?crop=3%3A2%2Csmart&amp;width=1200" alt="Chez Félix à Nice : préparation du pan bagnat et spécialités niçoises" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-med-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-med-600"></i> <span data-i18n="dist_8min_650">Environ 8 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-med-100 text-med-800 rounded-full" data-i18n="tag_streetfood">Pan Bagnat • Spécialités niçoises</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="resto1_title">Chez Félix — Le vrai Pan Bagnat</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="resto1_desc">Une adresse familiale emblématique du boulevard Jean Jaurès, connue pour son généreux pan bagnat niçois préparé à la demande. On y trouve aussi pissaladière, tourte de blettes et petits farcis. Une belle halte gourmande, à emporter pour un déjeuner dans le quartier. </p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Chez+F%C3%A9lix,+16+Boulevard+Jean+Jaur%C3%A8s,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-med-800 hover:text-med-900 bg-med-100/80 hover:bg-med-200/80 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Resto 2 : Chez Acchiardo -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://lostinfood.it/wp-content/uploads/2024/12/Ristorante-acchiardo-nizza.jpg" alt="Cuisine traditionnelle niçoise Chez Acchiardo" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-med-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-med-600"></i> <span data-i18n="dist_1min_90">Environ 5 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-rose-50 text-rose-700 rounded-full" data-i18n="tag_bistro">Bistrot Historique • Rue Droite</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="resto2_title">Chez Acchiardo (Maison fondée en 1927)</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="resto2_desc">À deux rues de l'appartement, cette adresse familiale mythique sert une cuisine niçoise généreuse : daube provençale, raviolis niçois, gnocchis maison et tripes à la niçoise. Pensez à réserver !</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Chez+Acchiardo,+38+Rue+Droite,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-med-800 hover:text-med-900 bg-med-100/80 hover:bg-med-200/80 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Resto 3 : Favola -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://www.la-favola.com/medias_upload/moxie/slider_accueil/FAVOLA_Header_rigatoni.jpg" alt="Restaurant Favola Vieux Nice" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-med-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-med-600"></i> <span data-i18n="dist_1min_70">Environ 4 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-emerald-50 text-emerald-800 rounded-full" data-i18n="tag_favola">Cuisine Italienne & Pâtes Fraîches</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="resto3_title">Favola — Saveurs d'Italie</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="resto3_desc">À deux pas de l'appartement, un cadre chaleureux et élégant pour savourer de délicieuses pâtes fraîches maison, des risottos crémeux et des spécialités aux accents transalpins.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=La+Favola,+13+Cours+Saleya,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-med-800 hover:text-med-900 bg-med-100/80 hover:bg-med-200/80 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Resto 4 : Di Piu -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://api.cloudly.space/resize/crop/1200/627/60/aHR0cHM6Ly9zdGF0aWMuYXBpZGFlLXRvdXJpc21lLmNvbS9maWxlc3RvcmUvb2JqZXRzLXRvdXJpc3RpcXVlcy9pbWFnZXMvMTY4LzgxLzI5OTA1MzIwLmpwZw%3D%3D/image.jpg" alt="Restaurant Di Piu Promenade des Anglais Nice" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-med-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-med-600"></i> <span data-i18n="dist_3min_250">Environ 7 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-sky-50 text-sky-700 rounded-full" data-i18n="tag_dipiu">Pizzas & Terrasse Mer</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="resto4_title">Di Piu — Face à la Mer</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="resto4_desc">Situé juste en bas du Cours Saleya face à la Baie des Anges. Une immense terrasse ensoleillée idéale pour déguster de généreuses pizzas au feu de bois, des salades et des antipasti avec vue sur la Méditerranée.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Di+Piu+Nice,+85+Quai+des+%C3%89tats-Unis,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-med-800 hover:text-med-900 bg-med-100/80 hover:bg-med-200/80 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Resto 5 : Voglia -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://www.lavoglia.com/medias_upload/moxie/photo3.jpg" alt="Restaurant Voglia Nice" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-med-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-med-600"></i> <span data-i18n="dist_4min_300">Environ 5 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-purple-50 text-purple-700 rounded-full" data-i18n="tag_voglia">Ambiance & Trattoria</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="resto5_title">Voglia — Cours Saleya</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="resto5_desc">Une adresse incontournable et animée sur le Cours Saleya. Ambiance chaleureuse, service dynamique et carte savoureuse proposant de superbes assiettes de pâtes, viandes et poissons frais.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=La+Voglia,+2+Rue+Saint-Fran%C3%A7ois+de+Paule,+06300+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-med-800 hover:text-med-900 bg-med-100/80 hover:bg-med-200/80 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Resto 6 : Le Québec -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-200 hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-48 overflow-hidden bg-slate-200">
                            <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Rue_massena_nice_01.jpg?width=1200" alt="Restaurant Le Québec dans la rue piétonne Masséna à Nice" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 right-3 text-xs font-medium text-med-800 bg-white/95 backdrop-blur-sm px-3 py-1 rounded-full shadow-sm">
                                <i class="fa-solid fa-walking mr-1 text-med-600"></i> <span data-i18n="dist_quebec">Environ 11 min à pied</span>
                            </span>
                        </div>
                        <div class="p-6 pb-4">
                            <div class="mb-2.5">
                                <span class="text-xs font-semibold px-3 py-1 bg-amber-50 text-amber-800 rounded-full" data-i18n="tag_quebec">Brasserie & Terrasse • Rue Piétonne</span>
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2" data-i18n="resto6_title">Le Québec — Rue Piétonne</h3>
                            <p class="text-slate-600 text-sm leading-relaxed" data-i18n="resto6_desc">Situé en plein cœur de la rue piétonne Masséna, cette adresse conviviale dispose d'une belle terrasse animée. Idéal pour savourer une cuisine de brasserie généreuse, des grillades, burgers et spécialités méditerranéennes après une séance shopping.</p>
                        </div>
                    </div>
                    <div class="px-6 pb-6 pt-3 border-t border-slate-100 flex justify-end">
                        <a href="https://www.google.com/maps/dir/?api=1&origin=14+Rue+Beno%C3%AEt+Bunico,+06300+Nice&destination=Le+Qu%C3%A9bec,+43+Rue+Mass%C3%A9na,+06000+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-med-800 hover:text-med-900 bg-med-100/80 hover:bg-med-200/80 px-3.5 py-2 rounded-xl transition">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span data-i18n="btn_maps">Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>
            </div>
        </section>

		<!-- SECTION AGENDA & ACTIVITÉS DU MOIS (NICE À GRASSE) -->
<section id="agenda-section" class="space-y-8">
    <div class="flex flex-col md:flex-row md:items-end justify-between gap-4">
        <div>
            <span class="text-xs font-bold uppercase tracking-wider text-azure-600 bg-azure-50 px-3 py-1 rounded-full">
                Côte d'Azur • Littoral & arrière-pays
            </span>
            <h2 class="text-2xl md:text-3xl font-bold text-slate-900 mt-2 flex items-center">
                <i class="fa-solid fa-calendar-days text-azure-600 mr-3"></i>
                <span data-i18n="sec_agenda">Agenda & Activités du Mois</span>
            </h2>
        </div>
        <!-- Sélecteur manuel optionnel pour explorer d'autres mois -->
        <div class="flex items-center gap-2">
            <label for="month-selector" class="text-xs font-medium text-slate-500">Mois affiché :</label>
            <select id="month-selector" onchange="renderMonthlyEvents(parseInt(this.value))" class="bg-white border border-slate-200 text-slate-700 text-sm rounded-xl px-3 py-2 shadow-sm focus:outline-none focus:ring-2 focus:ring-azure-500">
                <option value="0">Janvier</option>
                <option value="1">Février</option>
                <option value="2">Mars</option>
                <option value="3">Avril</option>
                <option value="4">Mai</option>
                <option value="5">Juin</option>
                <option value="6">Juillet</option>
                <option value="7">Août</option>
                <option value="8">Septembre</option>
                <option value="9">Octobre</option>
                <option value="10">Novembre</option>
                <option value="11">Décembre</option>
            </select>
        </div>
        <a href="https://www.explorenicecotedazur.com/evenements/agenda-de-tous-les-evenements/" target="_blank" rel="noopener"
           class="inline-flex items-center gap-2 bg-amber-400 text-slate-900 font-semibold text-sm px-4 py-2 rounded-xl shadow hover:bg-amber-300 transition">
            <i class="fa-solid fa-calendar-days"></i> Voir l’agenda en direct
        </a>
        <a href="https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/" target="_blank" rel="noopener noreferrer"
           class="inline-flex items-center gap-2 bg-emerald-100 text-emerald-900 font-semibold text-sm px-4 py-2 rounded-xl shadow-sm hover:bg-emerald-200 transition">
            <i class="fa-solid fa-trophy"></i> Calendrier sportif officiel
        </a>

    </div>

    <!-- SOUS-SECTION DYNAMIQUE : FESTIVALS & ÉVÉNEMENTS DU MOIS EN COURS -->
    <div class="bg-gradient-to-br from-slate-900 via-azure-900 to-slate-800 rounded-3xl p-6 md:p-8 text-white shadow-lg relative overflow-hidden">
        <div class="relative z-10">
            <div class="flex flex-wrap items-center justify-between gap-2 mb-6">
                <div class="flex items-center gap-3">
                    <span class="flex h-3 w-3 relative">
                        <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-amber-400 opacity-75"></span>
                        <span class="relative inline-flex rounded-full h-3 w-3 bg-amber-500"></span>
                    </span>
                    <h3 class="text-xl md:text-2xl font-bold">
                        À l'affiche en <span id="current-month-name" class="text-amber-400 underline decoration-amber-400/40 underline-offset-4">...</span>
                    </h3>
                </div>
                <span class="text-xs bg-white/10 backdrop-blur-md px-3 py-1 rounded-full text-azure-200 border border-white/10">
                    De Nice à l’arrière-pays
                </span>
            </div>

            <p class="text-xs text-azure-100/90 mb-4">Sélection d’événements sportifs sur la Côte d’Azur. Les dates indiquées comme « à confirmer » ne sont pas encore publiées officiellement ; consultez le calendrier sportif pour les mises à jour.</p>
            <!-- Conteneur rempli automatiquement par JavaScript selon le mois -->
            <div id="monthly-events-grid" class="grid md:grid-cols-3 gap-4">
                <!-- Les cartes du mois en cours s'injectent ici -->
            </div>
        </div>
    </div>

           <!-- SECTION INFOS PRATIQUES -->
        <section class="bg-azure-900 text-white rounded-3xl p-8 shadow-lg">
            <h2 class="text-2xl font-bold mb-4 flex items-center">
                <i class="fa-solid fa-circle-info text-azure-400 mr-3"></i> <span data-i18n="sec_practical">Infos pratiques depuis votre logement</span>
            </h2>
            <div class="grid md:grid-cols-2 gap-6 mt-6">
                <div class="bg-white/10 backdrop-blur p-6 rounded-2xl border border-white/10 flex flex-col justify-between">
                    <div>
                        <div class="text-azure-300 font-bold mb-2 text-lg" data-i18n="trans_title"><i class="fa-solid fa-tram mr-2"></i> Transports (3 à 6 min)</div>
                        <p class="text-sm text-slate-200 leading-relaxed" data-i18n="trans_desc">Tram L1 (Cathédrale - Vieille Ville) à 3 min pour la gare SNCF. Tram L2 (Garibaldi) à 6 min pour un accès direct à l'aéroport.</p>
                        <div class="flex flex-col items-start gap-2 mt-3 text-sm">
                            <a href="https://www.google.com/maps/dir/?api=1&destination=Arr%C3%AAt+Cath%C3%A9drale+-+Vieille+Ville,+Tramway+L1,+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="text-azure-200 hover:text-white underline underline-offset-2"><i class="fa-solid fa-tram mr-1"></i><span data-i18n="map_tram_l1">Tram L1 – arrêt Cathédrale – Vieille Ville : itinéraire Google Maps</span></a>
                            <a href="https://www.google.com/maps/dir/?api=1&destination=Arr%C3%AAt+Garibaldi,+Tramway+L2,+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="text-azure-200 hover:text-white underline underline-offset-2"><i class="fa-solid fa-tram mr-1"></i><span data-i18n="map_tram_l2">Tram L2 – arrêt Garibaldi : itinéraire Google Maps</span></a>
                            <a href="https://www.google.com/maps/dir/?api=1&destination=Gare+de+Nice-Ville,+Avenue+Thiers,+Nice&travelmode=walking" target="_blank" rel="noopener noreferrer" class="text-azure-200 hover:text-white underline underline-offset-2"><i class="fa-solid fa-train mr-1"></i><span data-i18n="map_train_station">Gare ferroviaire – Nice-Ville : itinéraire Google Maps</span></a>
                        </div>
                    </div>
                    <div class="flex flex-wrap gap-2.5 mt-5 pt-4 border-t border-white/10">
                        <a href="https://www.lignesdazur.com/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3.5 py-2 rounded-xl bg-azure-600 hover:bg-azure-500 text-white text-xs font-semibold transition shadow-sm">
                            <i class="fa-solid fa-bus"></i>
                            <span data-i18n="link_tram">Lignes d'Azur (Tram & Bus)</span>
                            <i class="fa-solid fa-arrow-up-right-from-square text-[10px] opacity-80"></i>
                        </a>
                        <a href="https://www.sncf-connect.com/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3.5 py-2 rounded-xl bg-white/15 hover:bg-white/25 text-white text-xs font-semibold transition">
                            <i class="fa-solid fa-train"></i>
                            <span data-i18n="link_train">Trains TER / SNCF</span>
                            <i class="fa-solid fa-arrow-up-right-from-square text-[10px] opacity-80"></i>
                        </a>
                    </div>
                </div>
                <div class="bg-white/10 backdrop-blur p-6 rounded-2xl border border-white/10">
                    <div class="text-azure-300 font-bold mb-2 text-lg" data-i18n="help_title"><i class="fa-solid fa-phone mr-2"></i> Urgences / Aide</div>
                    <p class="text-sm text-slate-200 leading-relaxed" data-i18n="help_desc">En cas de besoin ou de question sur l'appartement, n'hésitez pas à nous contacter directement via la messagerie Booking/Airbnb !</p>
                </div>
            </div>
        </section>

    </main>

    <!-- FOOTER -->
    <footer class="bg-slate-900 text-slate-400 py-8 text-center text-sm border-t border-slate-800 mt-16">
        <p data-i18n="footer_text">Rue Benoît Bunico, Vieux Nice • Créé avec soin pour rendre votre séjour inoubliable ☀️</p>
    </footer>

    <!-- SCRIPT DE TRADUCTION INSTANTANÉE -->
    <script>
        const translations = {
            fr: {
                top_title: "Guide Exclusif - Rue Benoît Bunico",
                hero_badge: "<i class=\"fa-solid fa-location-dot mr-1.5\"></i> Départ : 14 rue Benoît Bunico • Vieux Nice",
                hero_title: "Votre Séjour Inoubliable à Nice",
                hero_subtitle: "Toutes les activités, plages, marchés et bonnes adresses sont calculés à pied depuis votre logement.",
                sec_activities: "À pied depuis votre logement",
                tag_gastronomy: "Gastronomie & Ruelles",
                tag_coup_coeur: "Coup de cœur • Pan Bagnat",
                tag_culture: "Culture & Marché",
                tag_relax: "Détente & Mer",
                tag_view: "Panoramique",
                tag_shopping: "Shopping & Parc",
                tag_port: "Sorties & Port",
                tag_pedestrian: "Shopping & balade",
                dist_pedestrian: "Environ 11 min à pied",
                card_pedestrian_title: "La rue piétonne Masséna",
                card_pedestrian_desc: "Flânez dans le cœur commerçant de Nice, entre la place Masséna et la rue du Congrès. La rue Masséna et les rues voisines regorgent de boutiques, cafés et terrasses : idéal pour une promenade shopping à l’ambiance niçoise.",
                tag_galeries: "Grand magasin • Shopping",
                dist_galeries: "Environ 12 min à pied",
                card_galeries_title: "Galeries Lafayette Nice Masséna",
                card_galeries_desc: "Retrouvez les grandes marques, la mode, la beauté et les accessoires dans ce grand magasin emblématique, situé au 6 avenue Jean Médecin, près de la place Masséna. Une belle étape pour une séance shopping au centre de Nice.",
                dist_0min: "Environ 1 min à pied",
                dist_1min: "1 min à pied (80 m)",
                dist_2min: "Environ 4 min à pied",
                dist_4min: "Environ 6 min à pied",
                dist_5min: "Environ 12 à 15 min à pied (montée)",
                dist_6min: "Environ 9 min à pied",
                dist_8min: "Environ 9 à 12 min selon la destination",
                btn_maps: "Itinéraire Google Maps",
                btn_maps_garibaldi: "Place Garibaldi (Maps)",
                btn_maps_port: "Port Lympia (Maps)",
                card4_title: "Cœur du Vieux Nice & Place Rossetti",
                card4_desc: "Vous êtes au cœur du quartier historique ! Goûtez la socca traditionnelle, les panisses et les célèbres glaces artisanales de la Place Rossetti juste à côté.",
                card_felix_title: "Chez Félix — Le vrai Pan Bagnat",
                card_felix_desc: "À deux pas de l'appartement, ne manquez pas Félix pour déguster un authentique Pan Bagnat niçois généreux et préparé dans les règles de l'art. Idéal à emporter sur la plage !",
                card1_title: "Le Cours Saleya & son Marché",
                card1_desc: "À deux pas en descendant vers la mer : célèbre pour son marché aux fleurs coloré, ses étals de produits provençaux et ses antiquaires le lundi.",
                card3_title: "La Promenade des Anglais & Plages",
                card3_desc: "Traversez le Cours Saleya pour rejoindre immédiatement le bord de mer, les plages de galets de la Baie des Anges et les mythiques chaises bleues.",
                card2_title: "La Colline du Château & Cascade",
                card2_desc: "Vue imprenable sur la Baie des Anges, les toits ocre du Vieux Nice et le port. Accès rapide par les escaliers Lesage ou l'ascenseur gratuit.",
                card5_title: "Place Masséna & Promenade du Paillon",
                card5_desc: "Le grand parc urbain avec son miroir d'eau rafraîchissant, suivi de l'emblématique Place Masséna et des rues commerçantes (avenue Jean Médecin).",
                card6_title: "Place Garibaldi & Port Lympia",
                card6_desc: "Quartier animé prisé des locaux pour ses terrasses ensoleillées, ses bars à vin, ses antiquaires et ses pointus colorés amarrés au port.",
                sec_food: "Bonnes Tables & Spécialités Niçoises",
                sec_food_sub: "Nos adresses incontournables autour de votre logement pour goûter l'authentique cuisine nissarte et italienne.",
                dist_1min_70: "Environ 4 min à pied",
                dist_1min_90: "Environ 5 min à pied",
                dist_2min_150: "Environ 8 min à pied",
                dist_3min_250: "Environ 7 min à pied",
                dist_4min_300: "Environ 5 min à pied",
                dist_8min_650: "Environ 8 min à pied",
                tag_streetfood: "Pan Bagnat • Spécialités niçoises",
                tag_bistro: "Bistrot Historique • Rue Droite",
                tag_favola: "Cuisine Italienne & Pâtes Fraîches",
                tag_dipiu: "Pizzas & Terrasse Mer",
                tag_voglia: "Ambiance & Trattoria",
                resto1_title: "Chez Félix — Le vrai Pan Bagnat",
                resto1_desc: "Une adresse familiale emblématique du boulevard Jean Jaurès, connue pour son généreux pan bagnat niçois préparé à la demande. On y trouve aussi pissaladière, tourte de blettes et petits farcis. Une belle halte gourmande, à emporter pour un déjeuner dans le quartier.",
                resto2_title: "Chez Acchiardo (Maison fondée en 1927)",
                resto2_desc: "À deux rues de l'appartement, cette adresse familiale mythique sert une cuisine niçoise généreuse : daube provençale, raviolis niçois, gnocchis maison et tripes à la niçoise. Pensez à réserver !",
                resto3_title: "Favola — Saveurs d'Italie",
                resto3_desc: "À deux pas de l'appartement, un cadre chaleureux et élégant pour savourer de délicieuses pâtes fraîches maison, des risottos crémeux et des spécialités aux accents transalpins.",
                resto4_title: "Di Piu — Face à la Mer",
                resto4_desc: "Situé juste en bas du Cours Saleya face à la Baie des Anges. Une immense terrasse ensoleillée idéale pour déguster de généreuses pizzas au feu de bois, des salades et des antipasti avec vue sur la Méditerranée.",
                resto5_title: "Voglia — Cours Saleya",
                resto5_desc: "Une adresse incontournable et animée sur le Cours Saleya. Ambiance chaleureuse, service dynamique et carte savoureuse proposant de superbes assiettes de pâtes, viandes et poissons frais.",
                dist_quebec: "Environ 11 min à pied",
                tag_quebec: "Brasserie & Terrasse • Rue Piétonne",
                resto6_title: "Le Québec — Rue Piétonne",
                resto6_desc: "Situé en plein cœur de la rue piétonne Masséna, cette adresse conviviale dispose d'une belle terrasse animée. Idéal pour savourer une cuisine de brasserie généreuse, des grillades, burgers et spécialités méditerranéennes après une séance shopping.",
                sec_events: "Agenda & Activités du Mois (De Menton à Grasse)",
                sec_events_sub: "Profitez de votre séjour pour explorer les incontournables de la Côte d'Azur accessibles facilement depuis le Vieux Nice.",
                ev_train_menton: "TER ~35 min depuis Nice",
                ev_tram_nice: "Sur place & Tram L1/L2",
                ev_train_cannes: "TER ~30 min depuis Nice",
                tag_menton: "La Cité du Citron • Est",
                tag_nice: "Culture & Expositions • Nice",
                tag_cannes: "La Croisette & Îles de Lérins • Ouest",
                ev1_title: "Échappée à Menton & Jardins",
                ev1_desc: "Explorez la vieille ville aux façades colorées, flânez le long du nouveau port et visitez les somptueux jardins botaniques (Serre de la Madone, Val Rahmeh) surplombant la mer.",
                ev2_title: "Musées & Opéra de Nice",
                ev2_desc: "Profitez des expositions temporaires aux musées Matisse et Chagall, ou assistez à une représentation à l'Opéra de Nice situé à quelques minutes à pied de l'appartement.",
                ev3_title: "Cannes & Échappée Insulaire",
                ev3_desc: "Marchez sur les pas des stars le long de la Croisette, visitez le Suquet, puis prenez une navette maritime express vers l'île Sainte-Marguerite et son calme absolu.",
                sec_practical: "Infos pratiques depuis votre logement",
                trans_title: "<i class=\"fa-solid fa-tram mr-2\"></i> Transports (3 à 6 min)",
                trans_desc: "Tram L1 (Cathédrale - Vieille Ville) à 3 min pour la gare SNCF. Tram L2 (Garibaldi) à 6 min pour un accès direct à l'aéroport.",
                link_tram: "Lignes d'Azur (Tram & Bus)",
                link_train: "Trains TER / SNCF",
                map_tram_l1: "Tram L1 – arrêt Cathédrale – Vieille Ville : itinéraire Google Maps",
                map_tram_l2: "Tram L2 – arrêt Garibaldi : itinéraire Google Maps",
                map_train_station: "Gare ferroviaire – Nice-Ville : itinéraire Google Maps",
                help_title: "<i class=\"fa-solid fa-phone mr-2\"></i> Urgences / Aide",
                help_desc: "En cas de besoin ou de question sur l'appartement, n'hésitez pas à nous contacter directement via la messagerie Booking/Airbnb !",
                footer_text: "Rue Benoît Bunico, Vieux Nice • Créé avec soin pour rendre votre séjour inoubliable ☀️"
            },
            en: {
                top_title: "Exclusive Guide - Rue Benoît Bunico",
                hero_badge: "<i class=\"fa-solid fa-location-dot mr-1.5\"></i> Departure: Rue Benoît Bunico • Old Nice",
                hero_title: "Your Unforgettable Stay in Nice",
                hero_subtitle: "All activities, beaches, markets and great local addresses measured on foot from Rue Benoît Bunico.",
                sec_activities: "Walking Distances from Rue Benoît Bunico",
                tag_gastronomy: "Gastronomy & Alleys",
                tag_coup_coeur: "Local Favorite • Pan Bagnat",
                tag_culture: "Culture & Market",
                tag_relax: "Relaxation & Sea",
                tag_view: "Panoramic",
                tag_shopping: "Shopping & Park",
                tag_port: "Nightlife & Port",
                tag_pedestrian: "Shopping & stroll",
                dist_pedestrian: "About 11 min walk",
                card_pedestrian_title: "Rue Masséna pedestrian street",
                card_pedestrian_desc: "Stroll through the heart of Nice’s shopping district, between Place Masséna and Rue du Congrès. Rue Masséna and the nearby streets are lined with shops, cafés and terraces—perfect for a relaxed shopping walk.",
                tag_galeries: "Department store • Shopping",
                dist_galeries: "About 12 min walk",
                card_galeries_title: "Galeries Lafayette Nice Masséna",
                card_galeries_desc: "Discover leading brands, fashion, beauty and accessories in this landmark department store at 6 avenue Jean Médecin, near Place Masséna. A great stop for shopping in central Nice.",
                dist_0min: "About 1 min walk",
                dist_1min: "1 min walk (80 m)",
                dist_2min: "About 4 min walk",
                dist_4min: "About 6 min walk",
                dist_5min: "About 12–15 min walk (uphill)",
                dist_6min: "About 9 min walk",
                dist_8min: "About 9–12 min, depending on destination",
                btn_maps: "Google Maps Directions",
                btn_maps_garibaldi: "Place Garibaldi (Maps)",
                btn_maps_port: "Port Lympia (Maps)",
                card4_title: "Heart of Old Nice & Place Rossetti",
                card4_desc: "You are right in the historic center! Try traditional socca, panisse, and the famous artisanal ice creams at Place Rossetti just steps away.",
                card_felix_title: "Chez Félix — Authentic Pan Bagnat",
                card_felix_desc: "Just steps from the apartment, don't miss Félix to enjoy an authentic, generous traditional Niçois Pan Bagnat sandwich. Perfect to take away to the beach!",
                card1_title: "Cours Saleya & its Market",
                card1_desc: "Just down the street toward the sea: famous for its colorful flower market, Provençal food stalls, and Monday antiques market.",
                card3_title: "Promenade des Anglais & Beaches",
                card3_desc: "Cross Cours Saleya to immediately reach the seafront, the pebble beaches of the Baie des Anges, and the iconic blue chairs.",
                card2_title: "Castle Hill & Waterfall",
                card2_desc: "Breathtaking view over the Baie des Anges, Old Nice rooftops, and the port. Quick access via the Lesage stairs or free elevator.",
                card5_title: "Place Masséna & Promenade du Paillon",
                card5_desc: "The large urban park with its refreshing water mirror, followed by iconic Place Masséna and main shopping streets (Avenue Jean Médecin).",
                card6_title: "Place Garibaldi & Port Lympia",
                card6_desc: "Lively neighborhood loved by locals for its sunny terraces, wine bars, antique shops, and colorful traditional boats moored in the port.",
                sec_food: "Best Restaurants & Niçois Specialties",
                sec_food_sub: "Our must-try spots around Rue Benoît Bunico to taste authentic local and Italian cuisine.",
                dist_1min_70: "About 4 min walk",
                dist_1min_90: "About 5 min walk",
                dist_2min_150: "2 min walk (150 m)",
                dist_3min_250: "About 7 min walk",
                dist_4min_300: "About 5 min walk",
                dist_8min_650: "About 8 min walk",
                tag_streetfood: "Pan Bagnat • Niçois Specialties",
                tag_bistro: "Historic Bistro • Rue Droite",
                tag_favola: "Italian Cuisine & Fresh Pasta",
                tag_dipiu: "Pizzas & Seafront Terrace",
                tag_voglia: "Vibrant Trattoria",
                resto1_title: "Chez Félix — The Authentic Pan Bagnat",
                resto1_desc: "A beloved family-run spot on Boulevard Jean Jaurès, known for its generous Niçois pan bagnat, prepared to order. You can also find pissaladière, Swiss chard pie and stuffed vegetables. A great local stop for a takeaway lunch.",
                resto2_title: "Chez Acchiardo (Est. 1927)",
                resto2_desc: "Two streets away from the apartment, this legendary family-run bistro serves generous Niçois dishes: Provençal beef daube, Niçois ravioli, and homemade gnocchi. Booking recommended!",
                resto3_title: "Favola — Flavors of Italy",
                resto3_desc: "Just steps from the apartment, a warm and elegant setting to enjoy delicious homemade fresh pasta, creamy risottos, and Italian specialties.",
                resto4_title: "Di Piu — Facing the Sea",
                resto4_desc: "Located right at the bottom of Cours Saleya facing the Baie des Anges. A huge sunny terrace ideal for wood-fired pizzas, salads, and antipasti with a view of the Mediterranean.",
                resto5_title: "Voglia — Cours Saleya",
                resto5_desc: "A lively and must-visit spot on Cours Saleya. Warm atmosphere, dynamic service, and a delicious menu featuring great pasta, meat, and fresh fish dishes.",
                dist_quebec: "About 11 min walk",
                tag_quebec: "Brasserie & Terrace • Pedestrian Street",
                resto6_title: "Le Québec — Pedestrian Street",
                resto6_desc: "Located right in the heart of the Rue Masséna pedestrian zone, this welcoming spot features a lively terrace. Ideal for enjoying hearty brasserie dishes, grilled meats, burgers, and Mediterranean specialties after shopping.",
                sec_events: "Agenda & Activities of the Month (From Menton to Cannes)",
                sec_events_sub: "Make the most of your stay by exploring the highlights of the French Riviera, easily accessible from Old Nice.",
                ev_train_menton: "TER ~35 min from Nice",
                ev_tram_nice: "On-site & Tram L1/L2",
                ev_train_cannes: "TER ~30 min from Nice",
                tag_menton: "The Lemon City • East",
                tag_nice: "Culture & Exhibitions • Nice",
                tag_cannes: "La Croisette & Lérins Islands • West",
                ev1_title: "Day Trip to Menton & Gardens",
                ev1_desc: "Explore the colorful old town, stroll along the new port, and visit the stunning botanical gardens (Serre de la Madone, Val Rahmeh) overlooking the sea.",
                ev2_title: "Museums & Nice Opera House",
                ev2_desc: "Enjoy temporary exhibitions at the Matisse and Chagall museums, or attend a performance at the Nice Opera House just a short walk from the apartment.",
                ev3_title: "Cannes & Island Getaway",
                ev3_desc: "Walk in the footsteps of stars along La Croisette, visit Le Suquet, then take an express ferry to Sainte-Marguerite Island for absolute peace and quiet.",
                sec_practical: "Practical Info from Rue Benoît Bunico",
                trans_title: "<i class=\"fa-solid fa-tram mr-2\"></i> Transport (3 to 6 min)",
                trans_desc: "Tram L1 (Cathédrale - Vieille Ville) 3 min away for the train station. Tram L2 (Garibaldi) 6 min away for direct airport access.",
                link_tram: "Lignes d'Azur (Tram & Bus)",
                link_train: "Regional & SNCF Trains",
                map_tram_l1: "Tram L1 – Cathédrale – Vieille Ville stop: Google Maps directions",
                map_tram_l2: "Tram L2 – Garibaldi stop: Google Maps directions",
                map_train_station: "Railway station – Nice-Ville: Google Maps directions",
                help_title: "<i class=\"fa-solid fa-phone mr-2\"></i> Emergency / Help",
                help_desc: "If you need anything or have questions about the apartment, feel free to contact us directly via Booking/Airbnb messages!",
                footer_text: "Rue Benoît Bunico, Old Nice • Created with care to make your stay unforgettable ☀️"
            },
            it: {
                top_title: "Guida Esclusiva - Rue Benoît Bunico",
                hero_badge: "<i class=\"fa-solid fa-location-dot mr-1.5\"></i> Partenza: 14 Rue Benoît Bunico • Vecchia Nizza",
                hero_title: "Il Tuo Soggiorno Indimenticabile a Nizza",
                hero_subtitle: "Tutte le attività, spiagge, mercati e ottimi indirizzi calcolati a piedi da Rue Benoît Bunico.",
                sec_activities: "A piedi da Rue Benoît Bunico",
                tag_gastronomy: "Gastronomia e Vicoli",
                tag_coup_coeur: "Consigliato • Pan Bagnat",
                tag_culture: "Cultura e Mercato",
                tag_relax: "Relax e Mare",
                tag_view: "Panoramica",
                tag_shopping: "Shopping e Parco",
                tag_port: "Locali e Porto",
                tag_pedestrian: "Shopping e passeggiata",
                dist_pedestrian: "Circa 11 min a piedi",
                card_pedestrian_title: "La zona pedonale di rue Masséna",
                card_pedestrian_desc: "Passeggiate nel cuore commerciale di Nizza, tra Place Masséna e rue du Congrès. Rue Masséna e le strade vicine sono ricche di negozi, caffè e terrazze: l’ideale per una passeggiata dedicata allo shopping.",
                tag_galeries: "Grande magazzino • Shopping",
                dist_galeries: "Circa 12 min a piedi",
                card_galeries_title: "Galeries Lafayette Nice Masséna",
                card_galeries_desc: "Scoprite grandi marchi, moda, bellezza e accessori in questo iconico grande magazzino al 6 avenue Jean Médecin, vicino a Place Masséna. Una tappa perfetta per fare shopping nel centro di Nizza.",
                dist_0min: "Circa 1 min a piedi",
                dist_1min: "1 min a piedi (80 m)",
                dist_2min: "Circa 4 min a piedi",
                dist_4min: "Circa 6 min a piedi",
                dist_5min: "Circa 12–15 min a piedi (in salita)",
                dist_6min: "Circa 9 min a piedi",
                dist_8min: "Circa 9–12 min secondo la destinazione",
                btn_maps: "Indicazioni Google Maps",
                btn_maps_garibaldi: "Place Garibaldi (Maps)",
                btn_maps_port: "Porto Lympia (Maps)",
                card4_title: "Cuore della Vecchia Nizza e Place Rossetti",
                card4_desc: "Siete nel cuore del centro storico! Assaggiate la socca tradizionale, le panisse e i famosi gelati artigianali di Place Rossetti proprio accanto.",
                card_felix_title: "Chez Félix — Il vero Pan Bagnat",
                card_felix_desc: "A due passi dall'appartamento, non perdetevi Félix per gustare un autentico Pan Bagnat nizzardo generoso e preparato a regola d'arte. Ideale da portare in spiaggia!",
                card1_title: "Cours Saleya e il suo Mercato",
                card1_desc: "A due passi scendendo verso il mare: famoso per il mercato dei fiori colorato, i prodotti provenzali e gli antiquari il lunedì.",
                card3_title: "Promenade des Anglais e Spiagge",
                card3_desc: "Attraversate Cours Saleya per raggiungere subito il lungomare, le spiagge di ciottoli della Baie des Anges e le mitiche sedie blu.",
                card2_title: "Collina del Castello e Cascata",
                card2_desc: "Vista mozzafiato sulla Baie des Anges, i tetti ocra della Vecchia Nizza e il porto. Accesso rapido dalle scale Lesage o ascensore gratuito.",
                card5_title: "Place Masséna e Promenade du Paillon",
                card5_desc: "Il grande parco urbano con il suo specchio d'acqua rinfrescante, seguito dall'iconica Place Masséna e dalle vie dello shopping.",
                card6_title: "Place Garibaldi e Porto Lympia",
                card6_desc: "Quartiere vivace amato dai nizzardi per le terrazze soleggiate, i wine bar, gli antiquari e le barche colorate ormeggiate al porto.",
                sec_food: "Ristoranti Tipici e Specialità Nizzarde",
                sec_food_sub: "I nostri indirizzi imperdibili intorno a Rue Benoît Bunico per gustare l'autentica cucina locale e italiana.",
                dist_1min_70: "Circa 4 min a piedi",
                dist_1min_90: "Circa 5 min a piedi",
                dist_2min_150: "2 min a piedi (150 m)",
                dist_3min_250: "Circa 7 min a piedi",
                dist_4min_300: "Circa 5 min a piedi",
                dist_8min_650: "Circa 8 min a piedi",
                tag_streetfood: "Pan Bagnat • Specialità nizzarde",
                tag_bistro: "Bistrot Storico • Rue Droite",
                tag_favola: "Cucina Italiana & Pasta Fresca",
                tag_dipiu: "Pizze & Terrazza sul Mare",
                tag_voglia: "Trattoria Vivace",
                resto1_title: "Chez Félix — Il vero Pan Bagnat",
                resto1_desc: "Un indirizzo familiare molto conosciuto su Boulevard Jean Jaurès, celebre per il generoso pan bagnat nizzardo preparato al momento. Si trovano anche pissaladière, torta di bietole e verdure ripiene. Una gustosa tappa per un pranzo da asporto.",
                resto2_title: "Chez Acchiardo (Dal 1927)",
                resto2_desc: "A due passi dall'appartamento, questa storica trattoria familiare serve cucina nizzarda generosa: daube provenzale, ravioli e gnocchi fatti in casa. Prenotazione consigliata!",
                resto3_title: "Favola — Sapori d'Italia",
                resto3_desc: "A due passi dall'appartamento, un ambiente caldo ed elegante per gustare ottima pasta fresca fatta in casa, risotti cremosi e specialità italiane.",
                resto4_title: "Di Piu — Di Fronte al Mare",
                resto4_desc: "Situato proprio in fondo a Cours Saleya di fronte alla Baie des Anges. Una grande terrazza soleggiata ideale per pizze cotte a legna e piatti con vista sul mare.",
                resto5_title: "Voglia — Cours Saleya",
                resto5_desc: "Un indirizzo vivace e imperdibile su Cours Saleya. Atmosfera calorosa, servizio dinamico e menu gustoso con ottimi piatti di pasta, carne e pesce fresco.",
                dist_quebec: "Circa 11 min a piedi",
                tag_quebec: "Brasserie & Terrazza • Zona Pedonale",
                resto6_title: "Le Québec — Via Pedonale",
                resto6_desc: "Situato nel cuore della zona pedonale di rue Masséna, questo locale accogliente dispone di una vivace terrazza. Ideale per gustare una cucina da brasserie generosa, grigliate, burger e specialità mediterranee dopo lo shopping.",
                sec_events: "Agenda ed Eventi del Mese (Da Mentone a Cannes)",
                sec_events_sub: "Approfitta del soggiorno per esplorare le meraviglie della Costa Azzurra, facilmente raggiungibili dalla Vecchia Nizza.",
                ev_train_menton: "TER ~35 min da Nizza",
                ev_tram_nice: "Sul posto & Tram L1/L2",
                ev_train_cannes: "TER ~30 min da Nizza",
                tag_menton: "La Città del Limone • Est",
                tag_nice: "Cultura & Mostre • Nizza",
                tag_cannes: "La Croisette & Isole di Lérins • Ovest",
                ev1_title: "Gita a Mentone e ai Giardini",
                ev1_desc: "Esplora il centro storico dai colori vivaci, passeggia lungo il nuovo porto e visita i meravigliosi giardini botanici (Serre de la Madone, Val Rahmeh) a picco sul mare.",
                ev2_title: "Musei & Opera di Nizza",
                ev2_desc: "Goditi le mostre temporanee ai musei Matisse e Chagall o assisti a uno spettacolo all'Opera di Nizza, situata a pochi minuti a piedi dall'appartamento.",
                ev3_title: "Cannes e Fuga sulle Isole",
                ev3_desc: "Cammina sulle orme delle star lungo La Croisette, visita il Le Suquet e prendi un traghetto espresso per l'isola di Sainte-Marguerite in cerca di totale relax.",
                sec_practical: "Info pratiche da Rue Benoît Bunico",
                trans_title: "<i class=\"fa-solid fa-tram mr-2\"></i> Trasporti (3-6 min)",
                trans_desc: "Tram L1 (Cathédrale - Vieille Ville) a 3 min per la stazione. Tram L2 (Garibaldi) a 6 min con collegamento diretto all'aeroporto.",
                link_tram: "Lignes d'Azur (Tram e Bus)",
                link_train: "Treni TER / SNCF",
                map_tram_l1: "Tram L1 – fermata Cathédrale – Vieille Ville: percorso Google Maps",
                map_tram_l2: "Tram L2 – fermata Garibaldi: percorso Google Maps",
                map_train_station: "Stazione ferroviaria – Nice-Ville: percorso Google Maps",
                help_title: "<i class=\"fa-solid fa-phone mr-2\"></i> Emergenza / Aiuto",
                help_desc: "In caso di necessità o domande sull'appartamento, contattateci direttamente tramite i messaggi di Booking/Airbnb!",
                footer_text: "Rue Benoît Bunico, Vecchia Nizza • Creato con cura per un soggiorno indimenticabile ☀️"
            },
            es: {
                top_title: "Guía Exclusiva - Rue Benoît Bunico",
                hero_badge: "<i class=\"fa-solid fa-location-dot mr-1.5\"></i> Salida: 14 Rue Benoît Bunico • Casco Antiguo",
                hero_title: "Su Estancia Inolvidable en Niza",
                hero_subtitle: "Todas las actividades, playas, mercados y buenas direcciones calculadas a pie desde la calle Benoît Bunico.",
                sec_activities: "A pie desde Rue Benoît Bunico",
                tag_gastronomy: "Gastronomía y Callejuelas",
                tag_coup_coeur: "Favorito • Pan Bagnat",
                tag_culture: "Cultura y Mercado",
                tag_relax: "Relajación y Mar",
                tag_view: "Panorámica",
                tag_shopping: "Compras y Parque",
                tag_port: "Ocio y Puerto",
                tag_pedestrian: "Compras y paseo",
                dist_pedestrian: "Aproximadamente 11 min a pie",
                card_pedestrian_title: "La zona peatonal de rue Masséna",
                card_pedestrian_desc: "Pasee por el corazón comercial de Niza, entre la plaza Masséna y la rue du Congrès. La rue Masséna y las calles cercanas están llenas de tiendas, cafés y terrazas: el lugar ideal para disfrutar de un paseo de compras.",
                tag_galeries: "Grandes almacenes • Compras",
                dist_galeries: "Aproximadamente 12 min a pie",
                card_galeries_title: "Galeries Lafayette Nice Masséna",
                card_galeries_desc: "Descubra grandes marcas, moda, belleza y accesorios en estos emblemáticos grandes almacenes, situados en el 6 avenue Jean Médecin, cerca de la plaza Masséna. Una parada ideal para ir de compras por el centro de Niza.",
                dist_0min: "Aproximadamente 1 min a pie",
                dist_1min: "1 min a pie (80 m)",
                dist_2min: "Aproximadamente 4 min a pie",
                dist_4min: "Aproximadamente 6 min a pie",
                dist_5min: "Aproximadamente 12–15 min a pie (cuesta arriba)",
                dist_6min: "Aproximadamente 9 min a pie",
                dist_8min: "Aproximadamente 9–12 min según el destino",
                btn_maps: "Cómo llegar (Google Maps)",
                btn_maps_garibaldi: "Place Garibaldi (Maps)",
                btn_maps_port: "Puerto Lympia (Maps)",
                card4_title: "Corazón del Casco Antiguo y Place Rossetti",
                card4_desc: "¡Está en pleno centro histórico! Pruebe la socca tradicional, las panisse y los famosos helados artesanales de la Place Rossetti justo al lado.",
                card_felix_title: "Chez Félix — El auténtico Pan Bagnat",
                card_felix_desc: "A dos pasos del apartamento, no se pierda Félix para disfrutar de un auténtico Pan Bagnat nizardo generoso y tradicional. ¡Ideal para llevar a la playa!",
                card1_title: "Cours Saleya y su Mercado",
                card1_desc: "A dos pasos bajando hacia el mar: famoso por su colorido mercado de flores, productos provenzales y antigüedades los lunes.",
                card3_title: "Paseo de los Ingleses y Playas",
                card3_desc: "Cruce Cours Saleya para llegar de inmediato al paseo marítimo, las playas de guijarros y las míticas sillas azules.",
                card2_title: "Colina del Castillo y Cascada",
                card2_desc: "Vista impresionante de la Bahía de los Ángeles, los tejados ocres y el puerto. Acceso rápido por las escaleras Lesage o ascensor gratuito.",
                card5_title: "Place Masséna y Promenade du Paillon",
                card5_desc: "El gran parque urbano con su espejo de agua refrescante, seguido de la emblemática Place Masséna y las calles comerciales.",
                card6_title: "Place Garibaldi y Puerto Lympia",
                card6_desc: "Barrio animado preferido por los locales por sus terrazas soleadas, bares de vinos, anticuarios y barcos coloridos en el puerto.",
                sec_food: "Buenos Restaurantes y Especialidades",
                sec_food_sub: "Nuestras direcciones imprescindibles alrededor de Rue Benoît Bunico para probar la auténtica cocina local e italiana.",
                dist_1min_70: "Aproximadamente 4 min a pie",
                dist_1min_90: "Aproximadamente 5 min a pie",
                dist_2min_150: "2 min a pie (150 m)",
                dist_3min_250: "Aproximadamente 7 min a pie",
                dist_4min_300: "Aproximadamente 5 min a pie",
                dist_8min_650: "Aproximadamente 8 min a pie",
                tag_streetfood: "Pan Bagnat • Especialidades nizas",
                tag_bistro: "Bistró Histórico • Rue Droite",
                tag_favola: "Cocina Italiana y Pasta Fresca",
                tag_dipiu: "Pizzas y Terraza al Mar",
                tag_voglia: "Trattoria Animada",
                resto1_title: "Chez Félix — El auténtico Pan Bagnat",
                resto1_desc: "Un conocido establecimiento familiar del Boulevard Jean Jaurès, famoso por su generoso pan bagnat nizardo preparado al momento. También ofrece pissaladière, tarta de acelgas y verduras rellenas. Una parada deliciosa para llevar y comer por la zona.",
                resto2_title: "Chez Acchiardo (Fundada en 1927)",
                resto2_desc: "A dos calles del apartamento, esta mítica casa familiar sirve cocina nizarda generosa: estofado provenzal, raviolis y ñoquis caseros. ¡Se recomienda reservar!",
                resto3_title: "Favola — Sabores de Italia",
                resto3_desc: "A dos pasos del apartamento, un ambiente cálido y elegante para disfrutar de deliciosa pasta fresca casera, risottos cremosos y especialidades italianas.",
                resto4_title: "Di Piu — Frente al Mar",
                resto4_desc: "Situado justo al final de Cours Saleya frente a la Bahía de los Ángeles. Una enorme terraza soleada ideal para pizzas al horno de leña y pasta con vistas al Mediterráneo.",
                resto5_title: "Voglia — Cours Saleya",
                resto5_desc: "Un lugar animado e imprescindible en Cours Saleya. Ambiente cálido, servicio dinámico y un menú sabroso con estupendos platos de pasta, carnes y pescados frescos.",
                dist_quebec: "Aproximadamente 11 min a pie",
                tag_quebec: "Brasserie y Terraza • Calle Peatonal",
                resto6_title: "Le Québec — Calle Peatonal",
                resto6_desc: "Situado en pleno corazón de la calle peatonal Masséna, este acogedor restaurante cuenta con una animada terraza. Ideal para disfrutar de una generosa cocina de brasserie, carnes a la parrilla, hamburguesas y especialidades mediterráneas tras ir de compras.",
                sec_events: "Agenda y Actividades del Mes (De Menton a Cannes)",
                sec_events_sub: "Aproveche su estancia para explorar los lugares más destacados de la Costa Azul, fácilmente accesibles desde el Casco Antiguo.",
                ev_train_menton: "TER ~35 min desde Niza",
                ev_tram_nice: "Aquí mismo y Tranvía L1/L2",
                ev_train_cannes: "TER ~30 min desde Niza",
                tag_menton: "La Ciudad del Limón • Este",
                tag_nice: "Cultura y Exposiciones • Niza",
                tag_cannes: "La Croisette e Islas de Lérins • Oeste",
                ev1_title: "Excursión a Menton y sus Jardines",
                ev1_desc: "Explore el casco antiguo de fachadas coloridas, pasee por el nuevo puerto y visite los magníficos jardines botánicos con vistas al mar.",
                ev2_title: "Museos y Ópera de Niza",
                ev2_desc: "Disfrute de las exposiciones temporales en los museos Matisse y Chagall, o asista a una función en la Ópera de Niza a poca distancia a pie.",
                ev3_title: "Cannes y Escapada a las Islas",
                ev3_desc: "Siga los pasos de las estrellas en La Croisette, visite Le Suquet y tome un ferry exprés a la isla Sainte-Marguerite para disfrutar de una paz absoluta.",
                sec_practical: "Información práctica desde Rue Benoît Bunico",
                trans_title: "<i class=\"fa-solid fa-tram mr-2\"></i> Transporte (3 a 6 min)",
                trans_desc: "Tranvía L1 (Cathédrale - Vieille Ville) a 3 min para la estación de tren. Tranvía L2 (Garibaldi) a 6 min directo al aeropuerto.",
                link_tram: "Lignes d'Azur (Tranvía y Bus)",
                link_train: "Trenes TER / SNCF",
                map_tram_l1: "Tranvía L1 – parada Cathédrale – Vieille Ville: ruta en Google Maps",
                map_tram_l2: "Tranvía L2 – parada Garibaldi: ruta en Google Maps",
                map_train_station: "Estación de tren – Nice-Ville: ruta en Google Maps",
                help_title: "<i class=\"fa-solid fa-phone mr-2\"></i> Emergencia / Ayuda",
                help_desc: "Si necesita algo o tiene preguntas sobre el apartamento, contáctenos directamente a través de los mensajes de Booking/Airbnb.",
                footer_text: "Rue Benoît Bunico, Casco Antiguo • Creado con esmero para una estancia inolvidable ☀️"
            },
            de: {
                top_title: "Exklusiver Guide - Rue Benoît Bunico",
                hero_badge: "<i class=\"fa-solid fa-location-dot mr-1.5\"></i> Start: 14 Rue Benoît Bunico • Altstadt Nizza",
                hero_title: "Ihr unvergesslicher Aufenthalt in Nizza",
                hero_subtitle: "Alle Aktivitäten, Strände, Märkte und Tipps zu Fuß ab der Rue Benoît Bunico berechnet.",
                sec_activities: "Zu Fuß ab der Rue Benoît Bunico",
                tag_gastronomy: "Gastronomie & Gassen",
                tag_coup_coeur: "Geheimtipp • Pan Bagnat",
                tag_culture: "Kultur & Markt",
                tag_relax: "Entspannung & Meer",
                tag_view: "Panoramablick",
                tag_shopping: "Shopping & Park",
                tag_port: "Ausgehen & Hafen",
                tag_pedestrian: "Shopping & Spaziergang",
                dist_pedestrian: "Etwa 11 Min. zu Fuß",
                card_pedestrian_title: "Die Fußgängerzone Rue Masséna",
                card_pedestrian_desc: "Bummeln Sie durch das Einkaufsviertel von Nizza zwischen Place Masséna und Rue du Congrès. In der Rue Masséna und den umliegenden Straßen finden Sie zahlreiche Geschäfte, Cafés und Terrassen – ideal für einen entspannten Einkaufsbummel.",
                tag_galeries: "Kaufhaus • Shopping",
                dist_galeries: "Etwa 12 Min. zu Fuß",
                card_galeries_title: "Galeries Lafayette Nice Masséna",
                card_galeries_desc: "Entdecken Sie bekannte Marken, Mode, Beauty und Accessoires in diesem renommierten Kaufhaus in der 6 avenue Jean Médecin, nahe der Place Masséna. Ein schöner Einkaufsstopp im Zentrum von Nizza.",
                dist_0min: "Etwa 1 Min. zu Fuß",
                dist_1min: "1 Min. zu Fuß (80 m)",
                dist_2min: "Etwa 4 Min. zu Fuß",
                dist_4min: "Etwa 6 Min. zu Fuß",
                dist_5min: "Etwa 12–15 Min. zu Fuß (bergauf)",
                dist_6min: "Etwa 9 Min. zu Fuß",
                dist_8min: "Etwa 9–12 Min., je nach Ziel",
                btn_maps: "Google Maps Route",
                btn_maps_garibaldi: "Place Garibaldi (Maps)",
                btn_maps_port: "Hafen Lympia (Maps)",
                card4_title: "Herz der Altstadt & Place Rossetti",
                card4_desc: "Sie wohnen mitten im historischen Zentrum! Probieren Sie traditionelle Socca, Panisse und das berühmte hausgemachte Eis am Place Rossetti gleich nebenan.",
                card_felix_title: "Chez Félix — Echter Pan Bagnat",
                card_felix_desc: "Nur wenige Schritte vom Apartment entfernt: Verpassen Sie nicht Félix für ein authentisches, reichhaltiges Nizzaer Pan Bagnat. Perfekt zum Mitnehmen an den Strand!",
                card1_title: "Cours Saleya & Blumenmarkt",
                card1_desc: "Nur wenige Schritte Richtung Meer: berühmt für seinen bunten Blumenmarkt, provenzalische Spezialitäten und den Antiquitätenmarkt am Montag.",
                card3_title: "Promenade des Anglais & Strände",
                card3_desc: "Überqueren Sie den Cours Saleya und Sie stehen direkt an der Strandpromenade, den Kieselstränden und den berühmten blauen Stühlen.",
                card2_title: "Schloßberg & Wasserfall",
                card2_desc: "Atemberaubender Blick über die Baie des Anges, die Dächer der Altstadt und den Hafen. Schneller Zugang über die Lesage-Treppe oder kostenlosen Aufzug.",
                card5_title: "Place Masséna & Promenade du Paillon",
                card5_desc: "Der große Stadtpark mit erfrischendem Wasserspiegel, gefolgt vom berühmten Place Masséna und den Einkaufsstraßen.",
                card6_title: "Place Garibaldi & Hafen Lympia",
                card6_desc: "Lebendiges Viertel, beliebt bei Einheimischen für sonnige Terrassen, Weinbars, Antiquitätenläden und bunte Boote im Hafen.",
                sec_food: "Restaurants & Spezialitäten",
                sec_food_sub: "Unsere kulinarischen Lieblingsadressen rund um die Rue Benoît Bunico für lokale und italienische Küche.",
                dist_1min_70: "Etwa 4 Min. zu Fuß",
                dist_1min_90: "Etwa 5 Min. zu Fuß",
                dist_2min_150: "2 Min. zu Fuß (150 m)",
                dist_3min_250: "Etwa 7 Min. zu Fuß",
                dist_4min_300: "Etwa 5 Min. zu Fuß",
                dist_8min_650: "Etwa 8 Min. zu Fuß",
                tag_streetfood: "Pan Bagnat • Nizzaer Spezialitäten",
                tag_bistro: "Traditionsbistro • Rue Droite",
                tag_favola: "Italienische Küche & Frische Pasta",
                tag_dipiu: "Pizzen & Meerblick-Terrasse",
                tag_voglia: "Belebte Trattoria",
                resto1_title: "Chez Félix — Das echte Pan Bagnat",
                resto1_desc: "Ein beliebter Familienbetrieb am Boulevard Jean Jaurès, bekannt für sein großzügiges, frisch zubereitetes Nizzaer Pan Bagnat. Außerdem gibt es Pissaladière, Mangoldkuchen und gefülltes Gemüse. Ein köstlicher Zwischenstopp für ein Mittagessen zum Mitnehmen.",
                resto2_title: "Chez Acchiardo (Gegründet 1927)",
                resto2_desc: "Nur zwei Straßen entfernt serviert dieses legendäre Familienlokal herzhafte Nizzaer Küche: provenzalische Daube, Ravioli und hausgemachte Gnocchi. Reservierung empfohlen!",
                resto3_title: "Favola — Geschmack Italiens",
                resto3_desc: "Nur wenige Schritte entfernt ein gemütliches und elegantes Ambiente, um köstliche frische Hausgemachte Pasta, cremige Risottos und italienische Spezialitäten zu genießen.",
                resto4_title: "Di Piu — Direkt am Meer",
                resto4_desc: "Direkt am Ende des Cours Saleya mit Blick auf die Baie des Anges. Eine riesige sonnige Terrasse, ideal für Holzofenpizzen und Gerichte mit Blick auf das Mittelmeer.",
                resto5_title: "Voglia — Cours Saleya",
                resto5_desc: "Ein lebendiger und beliebter Treffpunkt am Cours Saleya. Herzliche Atmosphäre, dynamischer Service und eine schmackhafte Karte mit toller Pasta und frischem Fisch.",
                dist_quebec: "Etwa 11 Min. zu Fuß",
                tag_quebec: "Brasserie & Terrasse • Fußgängerzone",
                resto6_title: "Le Québec — Fußgängerzone",
                resto6_desc: "Mitten in der Fußgängerzone Rue Masséna gelegen, bietet dieses einladende Lokal eine lebhafte Terrasse. Ideal für herzhafte Brasserie-Küche, Grillgerichte, Burger und mediterrane Spezialitäten nach dem Einkaufsbummel.",
                sec_events: "Veranstaltungen & Aktivitäten des Monats (Von Menton bis Cannes)",
                sec_events_sub: "Nutzen Sie Ihren Aufenthalt, um die Highlights der Côte d'Azur zu erkunden, die von der Altstadt aus leicht erreichbar sind.",
                ev_train_menton: "TER ~35 Min. ab Nizza",
                ev_tram_nice: "Vor Ort & Tram L1/L2",
                ev_train_cannes: "TER ~30 Min. ab Nizza",
                tag_menton: "Die Zitronenstadt • Ost",
                tag_nice: "Kultur & Ausstellungen • Nizza",
                tag_cannes: "La Croisette & Lérins-Inseln • West",
                ev1_title: "Ausflug nach Menton & Gärten",
                ev1_desc: "Erkunden Sie die bunte Altstadt, schlendern Sie am neuen Hafen entlang und besuchen Sie die wunderschönen botanischen Gärten mit Meerblick.",
                ev2_title: "Museen & Oper von Nizza",
                ev2_desc: "Genießen Sie Sonderausstellungen in den Matisse- und Chagall-Museen oder besuchen Sie eine Aufführung in der Oper von Nizza, nur wenige Gehminuten entfernt.",
                ev3_title: "Cannes & Inselausflug",
                ev3_desc: "Wandel Sie auf den Spuren der Stars an der Croisette, besuchen Sie Le Suquet und nehmen Sie eine Expressfähre zur ruhigen Insel Sainte-Marguerite.",
                sec_practical: "Praktische Infos ab Rue Benoît Bunico",
                trans_title: "<i class=\"fa-solid fa-tram mr-2\"></i> Verkehrsmittel (3 bis 6 Min.)",
                trans_desc: "Tram L1 (Cathédrale - Vieille Ville) in 3 Min. zum Bahnhof. Tram L2 (Garibaldi) in 6 Min. direkt zum Flughafen.",
                link_tram: "Lignes d'Azur (Tram & Bus)",
                link_train: "TER / SNCF Züge",
                map_tram_l1: "Tram L1 – Haltestelle Cathédrale – Vieille Ville: Route in Google Maps",
                map_tram_l2: "Tram L2 – Haltestelle Garibaldi: Route in Google Maps",
                map_train_station: "Bahnhof – Nice-Ville: Route in Google Maps",
                help_title: "<i class=\"fa-solid fa-phone mr-2\"></i> Notfall / Hilfe",
                help_desc: "Bei Fragen zum Apartment kontaktieren Sie uns bitte direkt über die Booking/Airbnb-Nachrichten!",
                footer_text: "Rue Benoît Bunico, Altstadt Nizza • Mit Sorgfalt für Ihren Aufenthalt erstellt ☀️"
            },
            ru: {
                top_title: "Эксклюзивный гид - Rue Benoît Bunico",
                hero_badge: "<i class=\"fa-solid fa-location-dot mr-1.5\"></i> Старт: Rue Benoît Bunico • Старая Ницца",
                hero_title: "Ваш незабываемый отдых в Ницце",
                hero_subtitle: "Все развлечения, пляжи, рынки и лучшие места в пешей доступности от улицы Бенуа Бюнико (Rue Benoît Bunico).",
                sec_activities: "Пешком от Rue Benoît Bunico",
                tag_gastronomy: "Гастрономия и улочки",
                tag_coup_coeur: "Рекомендуем • Пан-банья",
                tag_culture: "Культура и рынок",
                tag_relax: "Отдых и море",
                tag_view: "Панорама",
                tag_shopping: "Шопинг и парк",
                tag_port: "Кафе и порт",
                tag_pedestrian: "Покупки и прогулка",
                dist_pedestrian: "Около 11 мин пешком",
                card_pedestrian_title: "Пешеходная улица Rue Masséna",
                card_pedestrian_desc: "Прогуляйтесь по торговому центру Ниццы между площадью Массена и улицей Конгре. На улице Массена и соседних улочках расположены магазины, кафе и террасы — отличное место для прогулки и покупок.",
                tag_galeries: "Универмаг • Покупки",
                dist_galeries: "Около 12 мин пешком",
                card_galeries_title: "Galeries Lafayette Nice Masséna",
                card_galeries_desc: "Здесь представлены известные бренды, одежда, косметика и аксессуары. Универмаг находится по адресу 6 avenue Jean Médecin, недалеко от площади Массена, и отлично подходит для шопинга в центре Ниццы.",
                dist_0min: "Около 1 мин пешком",
                dist_1min: "1 мин пешком (80 м)",
                dist_2min: "Около 4 мин пешком",
                dist_4min: "Около 6 мин пешком",
                dist_5min: "Около 12–15 мин пешком (в гору)",
                dist_6min: "Около 9 мин пешком",
                dist_8min: "Около 9–12 мин в зависимости от пункта назначения",
                btn_maps: "Маршрут в Google Maps",
                btn_maps_garibaldi: "Площадь Гарибальди (Maps)",
                btn_maps_port: "Порт Лимпия (Maps)",
                card4_title: "Сердце Старой Ниццы и площадь Россетти",
                card4_desc: "Вы находитесь в самом центре исторического квартала! Попробуйте традиционную сокку, панисс и знаменитое мороженое на соседней площади Россетти.",
                card_felix_title: "Chez Félix — Настоящий Пан-банья",
                card_felix_desc: "В двух шагах от апартаментов обязательно загляните к Феликсу (Félix), чтобы попробовать настоящий сытный нисуазский сэндвич Пан-банья. Идеально взять с собой на пляж!",
                card1_title: "Кур Салея и цветочный рынок",
                card1_desc: "В двух шагах по направлению к морю: знаменит красочным цветочным рынком, провансальскими деликатесами и антиквариатом по понедельникам.",
                card3_title: "Английская набережная и пляжи",
                card3_desc: "Перейдите Кур Салея, чтобы сразу выйти к морю, галечным пляжам Бухты Ангелов и знаменитым синим стульям.",
                card2_title: "Замковая гора и водопад",
                card2_desc: "Потрясающий вид на Бухту Ангелов, крыши Старой Ниццы и порт. Быстрый подъем по лестнице Лесаж или на бесплатном лифте.",
                card5_title: "Площадь Массена и парк Пайон",
                card5_desc: "Большой городской парк с освежающим водным зеркалом, за которым следуют знаменитая площадь Массена и торговые улицы.",
                card6_title: "Площадь Гарибальди и порт Лимпия",
                card6_desc: "Оживленный квартал, любимый местными жителями за солнечные террасы, винные бары, антикварные лавки и яркие лодки в порту.",
                sec_food: "Лучшие рестораны и специалитеты",
                sec_food_sub: "Наши любимые заведения рядом с Rue Benoît Bunico, где можно отведать местную и итальянскую кухню.",
                dist_1min_70: "Около 4 мин пешком",
                dist_1min_90: "Около 5 мин пешком",
                dist_2min_150: "2 мин пешком (150 м)",
                dist_3min_250: "Около 7 мин пешком",
                dist_4min_300: "Около 5 мин пешком",
                dist_8min_650: "Около 8 мин пешком",
                tag_streetfood: "Пан-банья • Нисские блюда",
                tag_bistro: "Историческое бистро • Rue Droite",
                tag_favola: "Итальянская кухня и паста",
                tag_dipiu: "Пицца и терраса у моря",
                tag_voglia: "Оживленная траттория",
                resto1_title: "Chez Félix — Настоящий пан-банья",
                resto1_desc: "Популярное семейное заведение на бульваре Жан-Жорес, известное щедрым пан-банья по-нисски, который готовят на заказ. Здесь также подают писсаладьеру, пирог с мангольдом и фаршированные овощи. Отличное место, чтобы взять обед с собой.",
                resto2_title: "Chez Acchiardo (основан в 1927 г.)",
                resto2_desc: "В двух улицах от апартаментов это знаменитое семейное бистро подает блюда нисуазской кухни: говядину доб, равиоли и домашние ньокки. Лучше бронировать заранее!",
                resto3_title: "Favola — Вкус Италии",
                resto3_desc: "В двух шагах от апартаментов, теплая и элегантная атмосфера, где можно насладиться вкуснейшей домашней свежей пастой, ризотто и итальянскими специалитетами.",
                resto4_title: "Di Piu — У самого моря",
                resto4_desc: "Расположен в самом низу Кур Салея напротив Бухты Ангелов. Огромная солнечная терраса, идеальная для пиццы на дровах и блюд с видом на Средиземное море.",
                resto5_title: "Voglia — Кур Салея",
                resto5_desc: "Оживленное и популярное место на Кур Салея. Теплая атмосфера, динамичное обслуживание и отличное меню с пастой, мясом и свежей рыбой.",
                dist_quebec: "Около 11 мин пешком",
                tag_quebec: "Брассери и терраса • Пешеходная улица",
                resto6_title: "Le Québec — Пешеходная улица",
                resto6_desc: "Расположенный в самом сердце пешеходной улицы Массена, этот уютный ресторан располагает оживленной террасой. Идеально подходит для сытных блюд брассери, гриля, бургеров и средиземноморских деликатесов после шопинга.",
                sec_events: "Афиша и события месяца (От Ментона до Канн)",
                sec_events_sub: "Воспользуйтесь поездкой, чтобы открыть для себя знаковые места Лазурного Берега, легко доступные из Старой Ниццы.",
                ev_train_menton: "TER ~35 мин от Ниццы",
                ev_tram_nice: "На месте и трамвай L1/L2",
                ev_train_cannes: "TER ~30 мин от Ниццы",
                tag_menton: "Город лимонов • Восток",
                tag_nice: "Культура и выставки • Ницца",
                tag_cannes: "Круазет и Леринские острова • Запад",
                ev1_title: "Поездка в Ментон и сады",
                ev1_desc: "Исследуйте яркий старый город, прогуляйтесь по новому порту и посетите великолепные ботанические сады с видом на море.",
                ev2_title: "Музеи и Опера Ниццы",
                ev2_desc: "Наслаждайтесь временными выставками в музеях Матисса и Шагала или посетите представление в Опере Ниццы в нескольких минутах ходьбы.",
                ev3_title: "Канны и поездка на острова",
                ev3_desc: "Пройдите по следам звезд вдоль набережной Круазет, посетите квартал Сюке и садитесь на экспресс-катер до тишайшего острова Сент-Маргерит.",
                sec_practical: "Полезная информация от Rue Benoît Bunico",
                trans_title: "<i class=\"fa-solid fa-tram mr-2\"></i> Транспорт (3–6 мин)",
                trans_desc: "Трамвай L1 (Cathédrale - Vieille Ville) в 3 мин до вокзала. Трамвай L2 (Garibaldi) в 6 мин напрямую до аэропорта.",
                link_tram: "Lignes d'Azur (Трамваи и автобусы)",
                link_train: "Поезда TER / SNCF",
                map_tram_l1: "Трамвай L1 – остановка Cathédrale – Vieille Ville: маршрут Google Maps",
                map_tram_l2: "Трамвай L2 – остановка Garibaldi: маршрут Google Maps",
                map_train_station: "Железнодорожный вокзал – Nice-Ville: маршрут Google Maps",
                help_title: "<i class=\"fa-solid fa-phone mr-2\"></i> Помощь / Экстренно",
                help_desc: "Если возникнут вопросы по апартаментам, пишите нам напрямую через сообщения Booking/Airbnb!",
                footer_text: "Rue Benoît Bunico, Старая Ницца • Создано с заботой о вашем отдыхе ☀️"
            },
            zh: {
                top_title: "专属指南 - Rue Benoît Bunico",
                hero_badge: "<i class=\"fa-solid fa-location-dot mr-1.5\"></i> 出发点：Rue Benoît Bunico • 老尼斯核心区",
                hero_title: "您在尼斯的难忘假期",
                hero_subtitle: "从 Benoît Bunico 街出发步行可达的所有景点、海滩、集市与地道好去处。",
                sec_activities: "从 Rue Benoît Bunico 步行距离",
                tag_gastronomy: "美食与老街",
                tag_coup_coeur: "强力推荐 • 尼斯三明治",
                tag_culture: "文化与集市",
                tag_relax: "休闲与大海",
                tag_view: "全景风光",
                tag_shopping: "购物与公园",
                tag_port: "夜生活与港口",
                tag_pedestrian: "购物与漫步",
                dist_pedestrian: "步行约 11 分钟",
                card_pedestrian_title: "马塞纳步行街（Rue Masséna）",
                card_pedestrian_desc: "漫步尼斯购物区中心，从马塞纳广场一直延伸至Congrès街。马塞纳街及周边街道汇集了各类商店、咖啡馆和露台，是悠闲购物散步的好去处。",
                tag_galeries: "百货商店 • 购物",
                dist_galeries: "步行约 12 分钟",
                card_galeries_title: "尼斯马塞纳老佛爷百货",
                card_galeries_desc: "这家标志性百货商店汇集知名品牌、时装、美妆和配饰，地址为Jean Médecin大道6号，靠近马塞纳广场，是在尼斯市中心购物的好去处。",
                dist_0min: "步行约 1 分钟",
                dist_1min: "步行 1 分钟 (80米)",
                dist_2min: "步行约 4 分钟",
                dist_4min: "步行约 6 分钟",
                dist_5min: "步行约 12–15 分钟（上坡）",
                dist_6min: "步行约 9 分钟",
                dist_8min: "步行约 9–12 分钟，视目的地而定",
                btn_maps: "Google 地图导航",
                btn_maps_garibaldi: "加里波第广场 (地图)",
                btn_maps_port: "林皮亚港 (地图)",
                card4_title: "老尼斯中心与罗塞蒂广场 (Place Rossetti)",
                card4_desc: "您正处于历史街区的核心！就在旁边的罗塞蒂广场品尝传统的鹰嘴豆饼 (Socca)、炸面团 (Panisse) 以及著名的手工冰淇淋。",
                card_felix_title: "Chez Félix — 正宗尼斯 Pan Bagnat 三明治",
                card_felix_desc: "距离公寓仅几步之遥，千万不要错过 Félix 家地道十足的尼斯特色三明治 (Pan Bagnat)，用料丰富传统，非常适合打包带去海滩享用！",
                card1_title: "萨雷亚集市 (Cours Saleya)",
                card1_desc: "朝海边走几步即达：以色彩缤纷的花卉市场、普罗旺斯特产摊位以及周一的古董市场而闻名。",
                card3_title: "英国人漫步大道与海滩",
                card3_desc: "穿过萨雷亚集市即可直达海滨、天使湾鹅卵石海滩以及标志性的蓝色座椅。",
                card2_title: "城堡山与瀑布 (Colline du Château)",
                card2_desc: "俯瞰天使湾、老尼斯红褐色屋顶和港口的绝佳视野。可通过 Lesage 阶梯或免费电梯快速登顶。",
                card5_title: "马塞纳广场与帕永绿带公园",
                card5_desc: "拥有清凉水镜广场的大型城市公园，紧邻标志性的马塞纳广场及主要商业购物街。",
                card6_title: "加里波第广场与林皮亚港",
                card6_desc: "深受当地人喜爱的活力街区，拥有阳光露台、葡萄酒吧、古董店以及停泊 en 港口的彩色传统木船。",
                sec_food: "精选餐厅与特色美食",
                sec_food_sub: "Rue Benoît Bunico 周边不容错过的地道尼斯风味与意大利美食小馆。",
                dist_1min_70: "步行约 4 分钟",
                dist_1min_90: "步行约 5 分钟",
                dist_2min_150: "步行 2 分钟 (150米)",
                dist_3min_250: "步行约 7 分钟",
                dist_4min_300: "步行约 5 分钟",
                dist_8min_650: "步行约 8 分钟",
                tag_streetfood: "Pan Bagnat • 尼斯特色美食",
                tag_bistro: "百年家族老店 • Rue Droite",
                tag_favola: "意式风味与鲜制意面",
                tag_dipiu: "披萨与无敌海景露台",
                tag_voglia: "热闹意式小馆",
                resto1_title: "Chez Félix — 正宗尼斯 Pan Bagnat",
                resto1_desc: "这家位于让·饶勒斯大道的家庭小店以现点现做、馅料丰富的尼斯特色三明治 Pan Bagnat 闻名，也供应洋葱鳀鱼挞、甜菜叶馅饼和尼斯酿蔬菜。适合在附近买一份外带午餐。",
                resto2_title: "Chez Acchiardo (始创于1927年)",
                resto2_desc: "距离公寓仅两条街的家族百年老店，供应地道的尼斯家常菜：普罗旺斯炖牛肉、尼斯饺子和手工土豆团子。建议提前预订！",
                resto3_title: "Favola — 意式美味",
                resto3_desc: "距离公寓仅几步之遥，温馨优雅的环境，提供美味的手工鲜制意面、香浓意式饭及特色菜肴。",
                resto4_title: "Di Piu — 面朝大海",
                resto4_desc: "位于萨雷亚集市尽头，紧邻天使湾。超大阳光露台，是在地中海美景下享用木火烤炉披萨、沙拉和开胃菜的绝佳去处。",
                resto5_title: "Voglia — 萨雷亚集市",
                resto5_desc: "萨雷亚集市上一家极具人气与活力的餐厅。气氛热烈，服务热情，菜单丰富，供应极佳的意面、肉类和新鲜海鲜。",
                dist_quebec: "步行约 11 分钟",
                tag_quebec: "法式小酒馆与露台 • 步行街",
                resto6_title: "Le Québec — 马塞纳步行街",
                resto6_desc: "位于马塞纳步行街中心，这家热情友好的餐厅拥有充满活力的露天座位。非常适合在购物漫步后享用丰盛的法式小酒馆美食、烤肉、汉堡和地中海特色菜。",
                sec_events: "当月活动指南 (从芒通到戛纳)",
                sec_events_sub: "充分利用您的假期，去探索蔚蓝海岸的精华风光，从老尼斯出发即可轻松抵达。",
                ev_train_menton: "乘TER动车自尼斯出发约35分钟",
                ev_tram_nice: "就在当地 & 有电车 L1/L2",
                ev_train_cannes: "乘TER动车自尼斯出发约30分钟",
                tag_menton: "柠檬之城 • 东部",
                tag_nice: "文化与展览 • 尼斯",
                tag_cannes: "克鲁瓦塞特大道与莱兰群岛 • 西部",
                ev1_title: "芒通小镇与花园一日游",
                ev1_desc: "探索色彩斑斓的老城区，漫步全新海港，并参观俯瞰大海的壮丽植物园（如：圣母玛利亚温室花园、瓦尔拉梅花园）。",
                ev2_title: "尼斯博物馆与歌剧院",
                ev2_desc: "参观马蒂斯博物馆和夏加尔博物馆的限时特展，或前往距离公寓仅几步之遥的尼斯歌剧院欣赏精彩演出。",
                ev3_title: "戛纳与海岛休闲之旅",
                ev3_desc: "沿着克鲁瓦塞特大道追寻明星 Footprints，游览老城叙凯 (Le Suquet)，然后搭乘快艇前往圣玛格丽特岛享受宁静避世时光。",
                sec_practical: "Rue Benoît Bunico 周边实用信息",
                trans_title: "<i class=\"fa-solid fa-tram mr-2\"></i> 交通出行 (3至6分钟)",
                trans_desc: "步行 3 分钟至电车 L1 线 (Cathédrale - Vieille Ville 站) 可达火车站；步行 6 分钟至 L2 线 (Garibaldi 站) 可直达机场。",
                link_tram: "Lignes d'Azur (电车与公交)",
                link_train: "TER / SNCF 火车",
                map_tram_l1: "L1 号有轨电车 – Cathédrale – Vieille Ville 站：Google 地图路线",
                map_tram_l2: "L2 号有轨电车 – Garibaldi 站：Google 地图路线",
                map_train_station: "铁路车站 – Nice-Ville：Google 地图路线",
                help_title: "<i class=\"fa-solid fa-phone mr-2\"></i> 紧急求助 / 帮助",
                help_desc: "如果您对公寓有任何疑问或需求，请随时通过 Booking/Airbnb 消息直接与我们联系！",
                footer_text: "Rue Benoît Bunico, 老尼斯 • 用心打造您的难忘假期 ☀️"
            }
        };

        function setLanguage(lang) {
            document.querySelectorAll('.lang-btn').forEach(btn => {
                btn.classList.remove('bg-azure-600', 'text-white');
                btn.classList.add('bg-slate-800', 'text-slate-300');
            });
            const activeBtn = document.getElementById('btn-' + lang);
            if(activeBtn) {
                activeBtn.classList.remove('bg-slate-800', 'text-slate-300');
                activeBtn.classList.add('bg-azure-600', 'text-white');
            }

            document.querySelectorAll('[data-i18n]').forEach(el => {
                const key = el.getAttribute('data-i18n');
                if (translations[lang] && translations[lang][key]) {
                    el.innerHTML = translations[lang][key];
                }
            });

            localStorage.setItem('preferred_lang', lang);
        }


        // ===== ACTIVITÉS DU MOIS EN COURS (Nice, Menton, Cannes, Grasse) =====
        const monthlyEvents = {
            0: [
                {city:'Nice', date:'Janvier (dates à confirmer)', title:'Promenade du Paillon & illuminations', desc:'Balade hivernale dans le parc du Paillon et découverte des illuminations du centre-ville.', tag:'Nice • Sur place', icon:'fa-snowflake', map:'https://www.google.com/maps/dir/?api=1&destination=Promenade+du+Paillon+Nice'},
                {city:'Grasse', date:'Janvier (dates à confirmer)', title:'Ateliers parfum d’hiver', desc:'Visites et ateliers de création parfumée dans les maisons historiques de Grasse.', tag:'Grasse • TER', icon:'fa-spray-can-sparkles', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+Parfumerie'},
                {city:'Nice', date:'10 janvier 2027', title:'Prom’Classic – course de 10 km', desc:'Course à pied populaire sur la Promenade des Anglais. Une belle occasion de voir Nice en mouvement au début de l’année.', tag:'Sport • Course à pied', icon:'fa-person-running', map:'https://www.google.com/maps/dir/?api=1&destination=Promenade+des+Anglais+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/'},
                {city:'Nice', date:'16 janvier 2027', title:'OGC Nice – Le Havre AC', desc:'Match de Ligue 1 à l’Allianz Riviera. Vérifier les horaires et éventuels changements avant le déplacement.', tag:'Sport • Football', icon:'fa-futbol', map:'https://www.google.com/maps/dir/?api=1&destination=Allianz+Riviera+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/'},
                {city:'Isola 2000', date:'23 au 25 janvier 2027', title:'Coupe d’Europe de snowboard', desc:'Compétition de snowboard dans la station d’Isola 2000, dans les Alpes-Maritimes.', tag:'Sport • Snowboard', icon:'fa-snowflake', map:'https://www.google.com/maps/dir/?api=1&destination=Isola+2000', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/'},
            ],
            1: [
                {city:'Menton', date:'Mi-février (dates à confirmer)', title:'Fête du Citron', desc:'Défilés, sculptures d’agrumes et animations dans la cité du citron.', tag:'Menton • TER', icon:'fa-lemon', map:'https://www.google.com/maps/dir/?api=1&destination=Menton+centre-ville'},
                {city:'Nice', date:'Février (dates à confirmer)', title:'Carnaval de Nice', desc:'Parades, batailles de fleurs et ambiance festive sur la Promenade des Anglais.', tag:'Nice • Sur place', icon:'fa-mask', map:'https://www.google.com/maps/dir/?api=1&destination=Promenade+des+Anglais+Nice'},
                {city:'Nice', date:'6 février 2027', title:'OGC Nice – Brest', desc:'Match de Ligue 1 à l’Allianz Riviera. Les horaires peuvent évoluer : consulter l’agenda officiel avant la sortie.', tag:'Sport • Football', icon:'fa-futbol', map:'https://www.google.com/maps/dir/?api=1&destination=Allianz+Riviera+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/'},
                {city:'Nice', date:'20 février 2027', title:'OGC Nice – AJ Auxerre', desc:'Rendez-vous football à l’Allianz Riviera, sous réserve de confirmation de l’horaire.', tag:'Sport • Football', icon:'fa-futbol', map:'https://www.google.com/maps/dir/?api=1&destination=Allianz+Riviera+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/'},
                {city:'La Colmiane', date:'27 février 2027', title:'Snow Trail de La Colmiane', desc:'Course nature hivernale en montagne, pour découvrir le trail dans un décor enneigé.', tag:'Sport • Trail', icon:'fa-person-running', map:'https://www.google.com/maps/dir/?api=1&destination=La+Colmiane', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/page/2/'},
            ],
            2: [
                {city:'Nice', date:'Mars (dates à confirmer)', title:'Printemps des musées', desc:'Expositions temporaires au MAMAC, au musée Matisse et au musée Chagall.', tag:'Nice • Culture', icon:'fa-palette', map:'https://www.google.com/maps/dir/?api=1&destination=Musée+Matisse+Nice'},
                {city:'Grasse', date:'Mars (dates à confirmer)', title:'Jardins & parfumeries', desc:'Découverte des jardins parfumés et des maisons Fragonard, Molinard et Galimard.', tag:'Grasse • TER', icon:'fa-leaf', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+Parfumerie'},
                {city:'Isola 2000', date:'12 au 14 mars 2027', title:'Championnat du monde de Snowscoot', desc:'Rendez-vous international consacré au snowscoot dans la station d’Isola 2000.', tag:'Sport • Glisse', icon:'fa-snowflake', map:'https://www.google.com/maps/dir/?api=1&destination=Isola+2000', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/page/2/'},
                {city:'Nice', date:'13 mars 2027', title:'OGC Nice – Toulouse FC', desc:'Match de Ligue 1 à l’Allianz Riviera. Consulter le calendrier officiel pour l’horaire définitif.', tag:'Sport • Football', icon:'fa-futbol', map:'https://www.google.com/maps/dir/?api=1&destination=Allianz+Riviera+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/page/2/'},
            ],
            3: [
                {city:'Cannes', date:'Avril (dates à confirmer)', title:'Îles de Lérins', desc:'Navette maritime vers Sainte-Marguerite et balade sur la Croisette.', tag:'Cannes • TER + bateau', icon:'fa-water', map:'https://www.google.com/maps/dir/?api=1&destination=Îles+de+Lérins+Cannes'},
                {city:'Grasse', date:'Avril (dates à confirmer)', title:'Jasmin & senteurs de printemps', desc:'Promenade dans la vieille ville et initiation à la parfumerie.', tag:'Grasse • TER', icon:'fa-spa', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+vieille+ville'},
                {city:'Nice', date:'3 avril 2027', title:'OGC Nice – Olympique Lyonnais', desc:'Affiche de Ligue 1 à l’Allianz Riviera. Vérifier les horaires avant de s’y rendre.', tag:'Sport • Football', icon:'fa-futbol', map:'https://www.google.com/maps/dir/?api=1&destination=Allianz+Riviera+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/page/2/'},
                {city:'Isola 2000', date:'3 et 4 avril 2027', title:'Duathlon trail – ski alpi', desc:'Épreuve combinant disciplines de montagne à Isola 2000.', tag:'Sport • Multisport', icon:'fa-person-hiking', map:'https://www.google.com/maps/dir/?api=1&destination=Isola+2000', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/page/2/'},
                {city:'Nice', date:'10 avril 2027', title:'OGC Nice – Paris FC', desc:'Match de Ligue 1 à l’Allianz Riviera. Horaire à vérifier sur l’agenda officiel.', tag:'Sport • Football', icon:'fa-futbol', map:'https://www.google.com/maps/dir/?api=1&destination=Allianz+Riviera+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/page/2/'},
                {city:'Nice', date:'24 avril 2027', title:'OGC Nice – Angers SCO', desc:'Match de Ligue 1 à l’Allianz Riviera. Horaire à vérifier sur l’agenda officiel.', tag:'Sport • Football', icon:'fa-futbol', map:'https://www.google.com/maps/dir/?api=1&destination=Allianz+Riviera+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/page/2/'},
            ],
            4: [
                {city:'Cannes', date:'Mi-mai (dates à confirmer)', title:'Festival de Cannes', desc:'Ambiance du festival, tapis rouge et projections sur la Croisette.', tag:'Cannes • TER', icon:'fa-film', map:'https://www.google.com/maps/dir/?api=1&destination=Palais+des+Festivals+Cannes'},
                {city:'Nice', date:'Mi-mai (dates à confirmer)', title:'Nuit des Musées', desc:'Ouvertures exceptionnelles et visites nocturnes des musées niçois.', tag:'Nice • Culture', icon:'fa-moon', map:'https://www.google.com/maps/dir/?api=1&destination=Musée+Chagall+Nice'},
                {city:'Nice', date:'8 mai 2027', title:'OGC Nice – Olympique de Marseille', desc:'Grand rendez-vous de Ligue 1 à l’Allianz Riviera. Consulter l’agenda officiel pour l’horaire définitif.', tag:'Sport • Football', icon:'fa-futbol', map:'https://www.google.com/maps/dir/?api=1&destination=Allianz+Riviera+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/page/2/'},
                {city:'Nice', date:'22 mai 2027', title:'OGC Nice – AS Monaco', desc:'Derby de la Côte d’Azur à l’Allianz Riviera, sous réserve de confirmation de l’horaire.', tag:'Sport • Football', icon:'fa-futbol', map:'https://www.google.com/maps/dir/?api=1&destination=Allianz+Riviera+Nice', info:'https://www.explorenicecotedazur.com/evenements/agenda-des-evenements-sportifs/page/2/'},
            ],
            5: [
                {city:'Nice', date:'21 juin', title:'Fête de la Musique', desc:'Concerts en plein air dans toute la ville au soir du 21 juin.', tag:'Nice • Sur place', icon:'fa-music', map:'https://www.google.com/maps/dir/?api=1&destination=Place+Masséna+Nice'},
                {city:'Grasse', date:'Fin juin (dates à confirmer)', title:'Expofleur', desc:'Grande fête des fleurs et des parfums au cœur de Grasse.', tag:'Grasse • TER', icon:'fa-fan', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+centre-ville'},
                {city:'Nice', date:'Juin 2027 • date à confirmer', title:'IRONMAN France Nice', desc:'Grand triathlon longue distance : natation en mer, parcours vélo dans l’arrière-pays et course à pied sur le littoral. La tenue de l’épreuve à Nice en juin 2027 est annoncée ; la date précise reste à confirmer.', tag:'Sport • Triathlon', icon:'fa-person-swimming', map:'https://www.google.com/maps/dir/?api=1&destination=Promenade+des+Anglais+Nice', info:'https://www.explorenicecotedazur.com/loffice-de-tourisme-nice-cote-dazur-partenaire-des-championnats-du-monde-dironman-70-3/'},
            ],
            6: [
                {city:'Nice', date:'14 juillet', title:'Plages & feux d’artifice', desc:'Soirées estivales sur la Promenade des Anglais et feux d’artifice.', tag:'Nice • Mer', icon:'fa-fire', map:'https://www.google.com/maps/dir/?api=1&destination=Promenade+des+Anglais+Nice'},
                {city:'Grasse', date:'Juillet (dates à confirmer)', title:'Soirées estivales', desc:'Concerts et animations dans la vieille ville de Grasse.', tag:'Grasse • TER', icon:'fa-sun', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+vieille+ville'}
            ],
            7: [
                {city:'Cannes', date:'Août (dates à confirmer)', title:'Soirées estivales', desc:'Cinéma en plein air, concerts et animations sur la Croisette.', tag:'Cannes • TER', icon:'fa-star', map:'https://www.google.com/maps/dir/?api=1&destination=La+Croisette+Cannes'},
                {city:'Grasse', date:'Août (dates à confirmer)', title:'Jasmin en fleurs', desc:'Découverte des champs de jasmin et des traditions parfumées.', tag:'Grasse • TER', icon:'fa-seedling', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+Parfumerie'}
            ],
            8: [
                {city:'Nice', date:'Septembre (dates à confirmer)', title:'Rentrée culturelle', desc:'Nouvelles expositions et saison culturelle dans les musées niçois.', tag:'Nice • Culture', icon:'fa-book', map:'https://www.google.com/maps/dir/?api=1&destination=MAMAC+Nice'},
                {city:'Grasse', date:'Mi-septembre (dates à confirmer)', title:'Journées du Patrimoine', desc:'Visites exceptionnelles des sites historiques et des parfumeries.', tag:'Grasse • TER', icon:'fa-landmark', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+centre-ville'},
                {city:'Roquebillière', date:'4 et 5 septembre 2027', title:'Rallye de la Vésubie', desc:'Rendez-vous automobile dans l’arrière-pays niçois, au cœur de la vallée de la Vésubie.', tag:'Sport • Rallye', icon:'fa-flag-checkered', map:'https://www.google.com/maps/dir/?api=1&destination=Roquebilliere', info:'https://www.explorenicecotedazur.com/en/events/sports-events-calendar/'},
            ],
            9: [
                {city:'Menton', date:'Octobre (dates à confirmer)', title:'Jardins d’automne', desc:'Balade dans les jardins botaniques et les ruelles colorées de Menton.', tag:'Menton • TER', icon:'fa-tree', map:'https://www.google.com/maps/dir/?api=1&destination=Jardin+Serre+de+la+Madone+Menton'},
                {city:'Grasse', date:'Octobre (dates à confirmer)', title:'Mois du parfum', desc:'Ateliers et découvertes autour des parfums et des essences.', tag:'Grasse • TER', icon:'fa-spray-can-sparkles', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+Parfumerie'}
            ],
            10: [
                {city:'Nice', date:'Novembre (dates à confirmer)', title:'Saveurs d’automne', desc:'Marchés et spécialités niçoises de saison dans le Vieux Nice.', tag:'Nice • Gastronomie', icon:'fa-utensils', map:'https://www.google.com/maps/dir/?api=1&destination=Cours+Saleya+Nice'},
                {city:'Grasse', date:'Novembre (dates à confirmer)', title:'Escapade parfumée', desc:'Visite des parfumeries historiques et de la vieille ville.', tag:'Grasse • TER', icon:'fa-spray-can-sparkles', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+Parfumerie'},
                {city:'Nice → Cannes', date:'7 novembre 2027', title:'Marathon des Alpes-Maritimes Nice-Cannes', desc:'Grande course sur route de 42,195 km entre la Promenade des Anglais à Nice et le boulevard de la Croisette à Cannes. Des formats complémentaires sont également proposés.', tag:'Sport • Marathon', icon:'fa-person-running', map:'https://www.google.com/maps/dir/?api=1&origin=Promenade+des+Anglais+Nice&destination=La+Croisette+Cannes&travelmode=transit', info:'https://www.marathon06.com/2027/index.htm'},
            ],
            11: [
                {city:'Nice', date:'Décembre (dates à confirmer)', title:'Marché de Noël', desc:'Illuminations, chalets et animations de fin d’année.', tag:'Nice • Sur place', icon:'fa-gift', map:'https://www.google.com/maps/dir/?api=1&destination=Place+Masséna+Nice'},
                {city:'Grasse', date:'Décembre (dates à confirmer)', title:'Noël à Grasse', desc:'Marché de Noël, illuminations et animations dans la capitale du parfum.', tag:'Grasse • TER', icon:'fa-snowflake', map:'https://www.google.com/maps/dir/?api=1&destination=Grasse+centre-ville'}
            ]
        };

        const monthNamesFr = ['Janvier','Février','Mars','Avril','Mai','Juin','Juillet','Août','Septembre','Octobre','Novembre','Décembre'];

        function renderMonthlyEvents(monthIndex) {
            const grid = document.getElementById('monthly-events-grid');
            const label = document.getElementById('current-month-name');
            if (!grid) return;
            const events = monthlyEvents[monthIndex] || [];
            grid.innerHTML = events.map(ev => `
                <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-5 border border-white/15 hover:bg-white/15 transition flex flex-col">
                    <div class="flex items-center gap-2 mb-3">
                        <span class="w-8 h-8 rounded-full bg-amber-400/20 text-amber-300 flex items-center justify-center">
                            <i class="fa-solid ${ev.icon}"></i>
                        </span>
                        <span class="text-xs font-semibold uppercase tracking-wide text-amber-300">${ev.city}</span>
                    </div>
                    <h4 class="text-lg font-bold text-white mb-1">${ev.title}</h4>
                    <p class="text-xs text-amber-200 mb-2"><i class="fa-regular fa-calendar mr-1"></i>${ev.date}</p>
                    <p class="text-sm text-slate-200 mb-4 flex-1">${ev.desc}</p>
                    <div class="flex flex-wrap items-center justify-between gap-2">
                        <span class="inline-block text-xs font-medium bg-white/10 text-white px-3 py-1 rounded-full">${ev.tag}</span>
                        <div class="flex items-center gap-2">
                            ${ev.info ? `<a href="${ev.info}" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 text-xs font-semibold text-white border border-white/30 px-3 py-1.5 rounded-full hover:bg-white/10 transition"><i class="fa-solid fa-circle-info"></i> Infos</a>` : ''}
                            <a href="${ev.map}" target="_blank" rel="noopener" class="inline-flex items-center gap-1 text-xs font-semibold bg-white text-slate-900 px-3 py-1.5 rounded-full hover:bg-amber-300 transition">
                                <i class="fa-solid fa-diamond-turn-right"></i> Itinéraire
                            </a>
                        </div>
                    </div>
                </div>
            `).join('');
            if (label) label.textContent = monthNamesFr[monthIndex];
        }

        window.addEventListener('DOMContentLoaded', () => {
            const selector = document.getElementById('month-selector');
            const currentMonth = new Date().getMonth();
            if (selector) {
                selector.value = String(currentMonth);
                selector.addEventListener('change', () => renderMonthlyEvents(parseInt(selector.value)));
            }
            renderMonthlyEvents(currentMonth);
        });

        window.addEventListener('DOMContentLoaded', () => {
            const savedLang = localStorage.getItem('preferred_lang');
            if (savedLang && translations[savedLang]) {
                setLanguage(savedLang);
            }
        });
    </script>
</body>
</html>
