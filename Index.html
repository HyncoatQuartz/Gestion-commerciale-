```html
<!DOCTYPE html>
<html lang="fr" class="h-full bg-slate-50">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hsabati - Logiciel de Facturation et Gestion d'Entreprise</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0fdf4',
                            100: '#dcfce7',
                            500: '#22c55e',
                            600: '#16a34a',
                            700: '#15803d',
                            800: '#166534',
                            900: '#14532d',
                        },
                        navy: {
                            800: '#1e293b',
                            900: '#0f172a'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts & FontAwesome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body { font-family: 'Inter', sans-serif; }
        ::-webkit-scrollbar { width: 6px; height: 6px; }
        ::-webkit-scrollbar-track { background: #f1f5f9; }
        ::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #94a3b8; }
        
        @media print {
            .no-print { display: none !important; }
            .print-only { display: block !important; }
            body { background: white; font-size: 12pt; }
            #printable-invoice { border: none !important; box-shadow: none !important; width: 100% !important; margin: 0 !important; padding: 0 !important; }
        }
    </style>
</head>
<body class="h-full text-slate-800 flex flex-col md:flex-row overflow-hidden antialiased">

    <!-- SIDEBAR -->
    <aside class="w-full md:w-64 bg-slate-900 text-slate-300 flex-shrink-0 flex flex-col no-print z-20">
        <!-- Logo & Brand -->
        <div class="p-4 border-b border-slate-800 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-600 to-emerald-400 flex items-center justify-center text-white font-bold text-xl shadow-lg shadow-brand-900/50">
                    H
                </div>
                <div>
                    <h1 class="font-bold text-white tracking-wide text-lg leading-tight">Hsabati <span class="text-xs px-1.5 py-0.5 bg-brand-500/20 text-brand-400 rounded border border-brand-500/30">PRO</span></h1>
                    <p class="text-xs text-slate-400">Gestion & Facturation</p>
                </div>
            </div>
            <button id="mobile-menu-btn" class="md:hidden text-slate-400 hover:text-white">
                <i class="fas fa-bars text-xl"></i>
            </button>
        </div>

        <!-- Navigation -->
        <nav id="sidebar-nav" class="flex-1 px-3 py-4 space-y-1 overflow-y-auto hidden md:block">
            <div class="text-xs font-semibold text-slate-500 uppercase tracking-wider px-3 mb-2">Principal</div>
            
            <a href="#" onclick="switchTab('dashboard')" id="nav-dashboard" class="nav-item flex items-center px-3 py-2.5 text-sm font-medium rounded-lg text-white bg-brand-600 shadow-md transition-all">
                <i class="fas fa-chart-pie w-6 text-center text-lg mr-2"></i>
                Tableau de bord
            </a>

            <a href="#" onclick="switchTab('invoices')" id="nav-invoices" class="nav-item flex items-center px-3 py-2.5 text-sm font-medium rounded-lg text-slate-400 hover:bg-slate-800 hover:text-white transition-all">
                <i class="fas fa-file-invoice-dollar w-6 text-center text-lg mr-2"></i>
                Factures & Devis
            </a>

            <a href="#" onclick="switchTab('stock')" id="nav-stock" class="nav-item flex items-center px-3 py-2.5 text-sm font-medium rounded-lg text-slate-400 hover:bg-slate-800 hover:text-white transition-all">
                <i class="fas fa-boxes-stacked w-6 text-center text-lg mr-2"></i>
                Stock & Produits
            </a>

            <a href="#" onclick="switchTab('contacts')" id="nav-contacts" class="nav-item flex items-center px-3 py-2.5 text-sm font-medium rounded-lg text-slate-400 hover:bg-slate-800 hover:text-white transition-all">
                <i class="fas fa-users-gears w-6 text-center text-lg mr-2"></i>
                Clients & Créances
            </a>

            <a href="#" onclick="switchTab('expenses')" id="nav-expenses" class="nav-item flex items-center px-3 py-2.5 text-sm font-medium rounded-lg text-slate-400 hover:bg-slate-800 hover:text-white transition-all">
                <i class="fas fa-receipt w-6 text-center text-lg mr-2"></i>
                Dépenses & Charges
            </a>

            <div class="text-xs font-semibold text-slate-500 uppercase tracking-wider px-3 mt-6 mb-2">Outils & OCR</div>

            <a href="#" onclick="switchTab('reports')" id="nav-reports" class="nav-item flex items-center px-3 py-2.5 text-sm font-medium rounded-lg text-slate-400 hover:bg-slate-800 hover:text-white transition-all">
                <i class="fas fa-chart-line w-6 text-center text-lg mr-2"></i>
                Déclaration TVA (20%)
            </a>

            <a href="#" onclick="openOcrModal()" class="nav-item flex items-center px-3 py-2.5 text-sm font-medium rounded-lg text-amber-400 hover:bg-amber-400/10 transition-all border border-amber-400/20 my-2">
                <i class="fas fa-wand-magic-sparkles w-6 text-center text-lg mr-2"></i>
                Scanner OCR Facture
            </a>
        </nav>

        <!-- Company Footer -->
        <div class="p-3 bg-slate-950/60 border-t border-slate-800 m-2 rounded-xl text-xs space-y-1">
            <div class="font-semibold text-slate-200 flex items-center justify-between">
                <span class="truncate">HYNCOAT QUARTZ SARL</span>
                <i class="fas fa-building text-brand-500"></i>
            </div>
            <div class="text-slate-400">ICE: <span>002849182000045</span></div>
            <div class="text-slate-500 text-[10px]">TVA: 20% (Conforme Maroc)</div>
        </div>
    </aside>

    <!-- MAIN CONTENT AREA -->
    <main class="flex-1 flex flex-col h-full overflow-hidden bg-slate-100">

        <!-- HEADER -->
        <header class="bg-white border-b border-slate-200 px-6 py-3 flex items-center justify-between no-print z-10 shadow-sm">
            <div class="flex items-center gap-4">
                <div class="relative hidden sm:block">
                    <i class="fas fa-search absolute left-3 top-1/2 -translate-y-1/2 text-slate-400 text-sm"></i>
                    <input type="text" placeholder="Rechercher facture, client, article..." class="pl-9 pr-4 py-1.5 text-sm bg-slate-100 border border-slate-200 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-500 w-64 md:w-80">
                </div>
            </div>

            <div class="flex items-center gap-3">
                <button onclick="openInvoiceModal('FACTURE')" class="bg-brand-600 hover:bg-brand-700 text-white px-3.5 py-1.5 rounded-lg text-sm font-semibold flex items-center gap-2 shadow-sm transition">
                    <i class="fas fa-plus"></i>
                    <span>Nouvelle Facture</span>
                </button>

                <div class="flex items-center gap-1.5 px-2.5 py-1 bg-slate-100 border border-slate-200 rounded-lg text-xs font-medium text-slate-600">
                    <span class="w-2 h-2 rounded-full bg-emerald-500"></span>
                    <span>MA - MAD (DH)</span>
                </div>
            </div>
        </header>

        <!-- VIEWPORT CONTENT -->
        <div class="flex-1 overflow-y-auto p-4 md:p-6 no-print" id="content-area">

            <!-- TAB 1: DASHBOARD -->
            <section id="tab-dashboard" class="space-y-6">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4">
                    <div>
                        <h2 class="text-2xl font-bold text-slate-800">Tableau de Bord</h2>
                        <p class="text-sm text-slate-500">Vue globale des performances financières et opérationnelles.</p>
                    </div>
                    <button onclick="resetDataToDemo()" class="text-xs bg-slate-200 hover:bg-slate-300 text-slate-700 px-3 py-1.5 rounded-lg transition flex items-center gap-1 self-start sm:self-auto">
                        <i class="fas fa-rotate"></i> Recharger Données Démo
                    </button>
                </div>

                <!-- KPI Cards -->
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-5 gap-4">
                    <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm relative overflow-hidden">
                        <p class="text-[11px] font-semibold text-slate-400 uppercase">Chiffre d'Affaires (TTC)</p>
                        <h3 class="text-xl font-extrabold text-slate-900 mt-1" id="kpi-ca-ttc">0,00 DH</h3>
                        <p class="text-[11px] text-emerald-600 font-medium mt-1">HT: <span id="kpi-ca-ht">0,00 DH</span></p>
                        <div class="absolute bottom-0 left-0 right-0 h-1 bg-emerald-500"></div>
                    </div>

                    <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm relative overflow-hidden">
                        <p class="text-[11px] font-semibold text-slate-400 uppercase">Total Dépenses</p>
                        <h3 class="text-xl font-extrabold text-red-600 mt-1" id="kpi-expenses-total">0,00 DH</h3>
                        <p class="text-[11px] text-slate-500 font-medium mt-1">Charges d'exploitation</p>
                        <div class="absolute bottom-0 left-0 right-0 h-1 bg-red-500"></div>
                    </div>

                    <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm relative overflow-hidden">
                        <p class="text-[11px] font-semibold text-slate-400 uppercase">Factures En Attente</p>
                        <h3 class="text-xl font-extrabold text-amber-600 mt-1" id="kpi-pending-count">0</h3>
                        <p class="text-[11px] text-amber-600 font-medium mt-1">Solde: <span id="kpi-pending-total">0,00 DH</span></p>
                        <div class="absolute bottom-0 left-0 right-0 h-1 bg-amber-500"></div>
                    </div>

                    <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm relative overflow-hidden">
                        <p class="text-[11px] font-semibold text-slate-400 uppercase">TVA Collectée (20%)</p>
                        <h3 class="text-xl font-extrabold text-blue-600 mt-1" id="kpi-tva-total">0,00 DH</h3>
                        <p class="text-[11px] text-slate-500 font-medium mt-1">A déclarer au FISC</p>
                        <div class="absolute bottom-0 left-0 right-0 h-1 bg-blue-500"></div>
                    </div>

                    <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm relative overflow-hidden">
                        <p class="text-[11px] font-semibold text-slate-400 uppercase">Total Devis Émis</p>
                        <h3 class="text-xl font-extrabold text-indigo-600 mt-1" id="kpi-devis-count">0</h3>
                        <p class="text-[11px] text-indigo-600 font-medium mt-1">Potentiel: <span id="kpi-devis-total">0,00 DH</span></p>
                        <div class="absolute bottom-0 left-0 right-0 h-1 bg-indigo-500"></div>
                    </div>
                </div>

                <!-- Charts & Stock Alerts -->
                <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
                    <div class="lg:col-span-2 bg-white p-5 rounded-2xl border border-slate-200 shadow-sm">
                        <div class="flex justify-between items-center mb-4">
                            <h3 class="font-bold text-slate-800 flex items-center gap-2">
                                <i class="fas fa-chart-area text-brand-600"></i> Suivi Financier & Évolution des Ventes
                            </h3>
                            <span class="text-xs bg-slate-100 text-slate-600 px-2 py-1 rounded">Exercice En Cours</span>
                        </div>
                        <div class="h-64">
                            <canvas id="salesChart"></canvas>
                        </div>
                    </div>

                    <div class="bg-white p-5 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-slate-800 mb-3 flex items-center gap-2">
                                <i class="fas fa-triangle-exclamation text-amber-500"></i> Alertes Stock Critique
                            </h3>
                            <div class="space-y-3" id="dashboard-stock-alerts">
                                <!-- Dynamic Low Stock -->
                            </div>
                        </div>
                        <button onclick="switchTab('stock')" class="mt-4 text-xs font-semibold text-brand-600 hover:text-brand-700 text-center block">
                            Accéder à la gestion du stock <i class="fas fa-arrow-right ml-1"></i>
                        </button>
                    </div>
                </div>

                <!-- Recent Transactions -->
                <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
                    <div class="p-4 border-b border-slate-100 flex items-center justify-between">
                        <h3 class="font-bold text-slate-800 flex items-center gap-2">
                            <i class="fas fa-receipt text-slate-500"></i> Dernières Transactions & Factures
                        </h3>
                        <button onclick="switchTab('invoices')" class="text-xs font-semibold text-brand-600 hover:underline">Voir tout</button>
                    </div>
                    <div class="overflow-x-auto">
                        <table class="w-full text-left text-sm">
                            <thead class="bg-slate-50 text-slate-500 text-xs uppercase font-semibold border-b border-slate-200">
                                <tr>
                                    <th class="p-3.5 px-4">N° Doc</th>
                                    <th class="p-3.5 px-4">Client</th>
                                    <th class="p-3.5 px-4">Date</th>
                                    <th class="p-3.5 px-4 text-right">Montant TTC</th>
                                    <th class="p-3.5 px-4 text-center">Statut</th>
                                    <th class="p-3.5 px-4 text-center">Action</th>
                                </tr>
                            </thead>
                            <tbody id="dashboard-recent-invoices" class="divide-y divide-slate-100">
                                <!-- Dynamic Rows -->
                            </tbody>
                        </table>
                    </div>
                </div>
            </section>

            <!-- TAB 2: INVOICES & QUOTES -->
            <section id="tab-invoices" class="space-y-6 hidden">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4">
                    <div>
                        <h2 class="text-2xl font-bold text-slate-800">Factures & Devis</h2>
                        <p class="text-sm text-slate-500">Établissez et gérez vos documents commerciaux conforme à la réglementation.</p>
                    </div>
                    <div class="flex items-center gap-2">
                        <button onclick="openInvoiceModal('DEVIS')" class="bg-indigo-50 hover:bg-indigo-100 text-indigo-700 border border-indigo-200 px-4 py-2 rounded-xl text-sm font-semibold flex items-center gap-2 transition">
                            <i class="fas fa-plus-circle"></i> Nouveau Devis
                        </button>
                        <button onclick="openInvoiceModal('FACTURE')" class="bg-brand-600 hover:bg-brand-700 text-white px-4 py-2 rounded-xl text-sm font-semibold flex items-center gap-2 shadow-sm transition">
                            <i class="fas fa-file-invoice"></i> Créer Facture
                        </button>
                    </div>
                </div>

                <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm flex flex-wrap items-center justify-between gap-3">
                    <div class="flex items-center gap-2 flex-1 min-w-[240px]">
                        <div class="relative w-full">
                            <i class="fas fa-search absolute left-3 top-1/2 -translate-y-1/2 text-slate-400 text-sm"></i>
                            <input type="text" id="invoice-search" onkeyup="filterInvoicesTable()" placeholder="Rechercher par N°, Client, ICE..." class="pl-9 pr-4 py-2 text-sm bg-slate-50 border border-slate-200 rounded-lg w-full focus:outline-none focus:ring-2 focus:ring-brand-500">
                        </div>
                    </div>
                    <div class="flex items-center gap-2">
                        <select id="invoice-filter-type" onchange="filterInvoicesTable()" class="bg-slate-50 border border-slate-200 text-slate-700 text-sm rounded-lg p-2">
                            <option value="ALL">Tous les types</option>
                            <option value="FACTURE">Factures</option>
                            <option value="DEVIS">Devis</option>
                        </select>
                        <select id="invoice-filter-status" onchange="filterInvoicesTable()" class="bg-slate-50 border border-slate-200 text-slate-700 text-sm rounded-lg p-2">
                            <option value="ALL">Tous les statuts</option>
                            <option value="PAYEE">Payée</option>
                            <option value="EN_ATTENTE">En Attente</option>
                        </select>
                    </div>
                </div>

                <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
                    <div class="overflow-x-auto">
                        <table class="w-full text-left text-sm">
                            <thead class="bg-slate-50 text-slate-500 text-xs uppercase font-semibold border-b border-slate-200">
                                <tr>
                                    <th class="p-4">Type & N°</th>
                                    <th class="p-4">Client / Raison Sociale</th>
                                    <th class="p-4">Date</th>
                                    <th class="p-4 text-right">Total HT</th>
                                    <th class="p-4 text-right">TVA (20%)</th>
                                    <th class="p-4 text-right">Total TTC</th>
                                    <th class="p-4 text-center">Statut</th>
                                    <th class="p-4 text-center">Actions</th>
                                </tr>
                            </thead>
                            <tbody id="invoices-table-body" class="divide-y divide-slate-100">
                                <!-- Dynamic Rows -->
                            </tbody>
                        </table>
                    </div>
                </div>
            </section>

            <!-- TAB 3: STOCK & PRODUCTS -->
            <section id="tab-stock" class="space-y-6 hidden">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4">
                    <div>
                        <h2 class="text-2xl font-
```
