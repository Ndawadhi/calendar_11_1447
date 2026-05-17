<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>التقويم التوثيقي لشهر ذو الحجة ١٤٤٧ هـ</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Premium Fonts for Clear and Readable Arabic Typography -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Readex+Pro:wght@300;400;500;600;700&family=IBM+Plex+Sans+Arabic:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Font Awesome Icons (Minimalist Icons representation) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        // Priority: Readex Pro (Premium Apple-like modern geometric font), then IBM Plex Sans Arabic for high legibility
                        sans: ['"Readex Pro"', '"IBM Plex Sans Arabic"', 'sans-serif'],
                        english: ['"Readex Pro"', 'sans-serif'],
                    },
                    colors: {
                        gold: {
                            500: '#B79851', // Primary Gold
                            600: '#A48745', // Interactive Gold Hover
                        },
                        accent: {
                            green: '#627536', // Secondary Limited Green
                        },
                        warm: {
                            bg: '#F7F3ED',       // Page Background
                            card: '#FAF8F4',     // Card Background
                            header: '#F5F2E9',   // Header Background
                            border: '#E2D8C8',   // Borders
                            textPrimary: '#1F1F1F', // Primary Text
                            textSecondary: '#3E3A33', // Secondary Text
                            textMuted: '#6F6A5F',     // Muted Text
                        }
                    },
                    boxShadow: {
                        'soft-sm': '0 2px 8px -1px rgba(31, 31, 31, 0.04)',
                        'soft-md': '0 10px 30px -4px rgba(31, 31, 31, 0.06)',
                        'soft-lg': '0 20px 40px -8px rgba(31, 31, 31, 0.08)',
                    }
                }
            }
        }
    </script>
    
    <style>
        body {
            font-family: 'Readex Pro', 'IBM Plex Sans Arabic', sans-serif;
            background-color: #F7F3ED;
            color: #1F1F1F;
            -webkit-font-smoothing: antialiased;
        }

        /* Apple-inspired scrollbar */
        .custom-scrollbar::-webkit-scrollbar {
            width: 5px;
            height: 5px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: transparent;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #E2D8C8;
            border-radius: 999px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb:hover {
            background: #B79851;
        }

        /* Apple-inspired glass effect card (where needed) */
        .glass-card {
            background: rgba(250, 248, 244, 0.85);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(226, 216, 200, 0.6);
        }

        /* Print Mode Optimization (High Contrast Clean Typography) */
        @media print {
            body {
                background: #ffffff !important;
                color: #000000 !important;
            }
            .no-print {
                display: none !important;
            }
            .print-grid {
                grid-template-columns: repeat(7, minmax(0, 1fr)) !important;
                gap: 8px !important;
            }
            .print-card {
                border: 1px solid #E2D8C8 !important;
                box-shadow: none !important;
                background-color: #ffffff !important;
                color: #000000 !important;
                height: auto !important;
                min-height: 120px !important;
                page-break-inside: avoid;
            }
            .print-note {
                display: block !important;
                font-size: 10px !important;
                border-top: 1px solid #E2D8C8;
                margin-top: 6px;
                padding-top: 4px;
                color: #1F1F1F !important;
            }
        }
    </style>
</head>
<body class="min-h-screen flex flex-col selection:bg-gold-500/10 selection:text-gold-600">

    <header class="bg-warm-header border-b border-warm-border/60 sticky top-0 z-40 backdrop-blur-md bg-opacity-95 transition-all duration-300 no-print">
        <div class="max-w-7xl mx-auto px-6 py-5 sm:px-8 flex flex-col sm:flex-row sm:items-center sm:justify-between gap-4">
            <div>
                <div class="flex items-center gap-2 mb-1.5">
                    <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-[11px] font-medium bg-gold-500/10 text-gold-600 border border-gold-500/20">
                        رصد وتوثيق الأيام الفضيلة
                    </span>
                    <span class="text-warm-textMuted text-xs font-mono">•</span>
                    <span class="text-warm-textMuted text-xs">١٤٤٧ هـ</span>
                </div>
                <h1 class="text-2xl sm:text-3xl font-bold text-warm-textPrimary tracking-tight">
                    تقويم شهر ذو الحجة
                </h1>
                <p class="text-warm-textSecondary text-xs sm:text-sm mt-1 max-w-xl font-light">
                    غرة ذو الحجة تبدأ يوم الاثنين (الموافق ١٨ مايو ٢٠٢٦ م). منبر توثيقي هادئ ومستقر لمتابعة إنجازاتك اليومية.
                </p>
            </div>
            
            <!-- Sleek Countdown Widget -->
            <div class="flex items-center gap-3.5 bg-warm-card border border-warm-border px-4.5 py-3 rounded-[20px] shadow-soft-sm self-start sm:self-auto">
                <div class="w-9 h-9 rounded-full bg-gold-500/10 flex items-center justify-center text-gold-500 text-sm">
                    <i class="fa-regular fa-clock"></i>
                </div>
                <div>
                    <span class="text-[10px] text-warm-textMuted block font-medium leading-none mb-1">العد التنازلي ليوم النحر</span>
                    <span class="text-sm font-bold text-warm-textPrimary font-mono" id="countdown-display">جاري الاحتساب...</span>
                </div>
            </div>
        </div>
    </header>

    <main class="flex-grow max-w-7xl w-full mx-auto px-6 sm:px-8 py-10">
        
        <!-- Controls & Metrics Grid -->
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 mb-12 no-print">
            
            <!-- Clean Control Panel Card -->
            <div class="bg-warm-card border border-warm-border rounded-[24px] p-6 shadow-soft-sm flex flex-col justify-between transition-all duration-200 hover:shadow-soft-md">
                <div>
                    <h3 class="font-bold text-sm text-warm-textPrimary mb-4 flex items-center gap-2.5">
                        <i class="fa-solid fa-sliders text-gold-500 text-xs"></i>
                        <span>إعدادات العرض والحفظ</span>
                    </h3>
                    
                    <div class="space-y-4">
                        <!-- Toggle Gregorian UI element (Apple style switch) -->
                        <div class="flex items-center justify-between p-3.5 bg-[#FAF8F4] border border-warm-border/60 rounded-xl">
                            <div>
                                <label for="toggle-gregorian" class="font-semibold text-xs text-warm-textPrimary block cursor-pointer">إظهار التاريخ الميلادي</label>
                                <span class="text-[10px] text-warm-textMuted block mt-0.5">مايو - يونيو ٢٠٢٦ م</span>
                            </div>
                            <button id="toggle-gregorian" onclick="toggleGregorian()" class="relative inline-flex h-5 w-10 shrink-0 cursor-pointer rounded-full border-2 border-transparent transition-colors duration-200 ease-in-out focus:outline-none bg-gold-500">
                                <span id="toggle-switch-dot" class="pointer-events-none inline-block h-4 w-4 transform rounded-full bg-white shadow-soft-sm ring-0 transition duration-200 ease-in-out translate-x-5"></span>
                            </button>
                        </div>

                        <!-- Private Local Storage Notice & Actions -->
                        <div class="p-4 bg-[#F5F2E9]/40 rounded-xl border border-warm-border/40 space-y-3.5">
                            <div class="flex items-center gap-2 text-[11px] font-semibold text-warm-textSecondary">
                                <i class="fa-solid fa-shield-halved text-gold-500 text-xs"></i>
                                <span>خصوصيتك مصونة بالكامل</span>
                            </div>
                            <p class="text-[10px] text-warm-textMuted leading-relaxed">
                                تُحفظ المذكرات تلقائياً ومباشرةً في متصفحك الحالي دون إرسالها لأي جهة أو خادم خارجي. يمكنك تصديرها كملف احتياطي لاستعادتها بأي وقت.
                            </p>
                            <div class="grid grid-cols-2 gap-2">
                                <button onclick="exportBackupData()" class="py-2 px-2.5 bg-gold-500 hover:bg-gold-600 text-white rounded-lg text-[10px] font-medium transition-all duration-150 flex items-center justify-center gap-1.5 shadow-soft-sm">
                                    <i class="fa-solid fa-download text-[9px]"></i> تصدير البيانات
                                </button>
                                <button onclick="triggerImport()" class="py-2 px-2.5 bg-warm-header hover:bg-warm-border/40 text-warm-textSecondary rounded-lg text-[10px] font-medium border border-warm-border transition-all duration-150 flex items-center justify-center gap-1.5">
                                    <i class="fa-solid fa-upload text-[9px]"></i> استيراد ملف
                                </button>
                            </div>
                            <!-- Hidden input for JSON file upload -->
                            <input type="file" id="import-file-input" accept=".json" class="hidden" onchange="importBackupData(event)">
                        </div>

                        <!-- Advanced Sync Accordion -->
                        <details class="group border border-warm-border/60 rounded-xl overflow-hidden transition-all duration-200">
                            <summary class="flex items-center justify-between p-3 bg-warm-card cursor-pointer list-none select-none">
                                <span class="text-xs font-semibold text-warm-textSecondary flex items-center gap-2">
                                    <i class="fa-solid fa-arrows-spin text-gold-500 text-[10px]"></i>
                                    <span>مزامنة سحابية متقدمة</span>
                                </span>
                                <span class="text-[10px] text-warm-textMuted group-open:rotate-180 transition-transform duration-200">
                                    <i class="fa-solid fa-chevron-down"></i>
                                </span>
                            </summary>
                            <div class="p-3.5 bg-white border-t border-warm-border/50 space-y-3">
                                <div class="flex items-center justify-between text-[10px] font-semibold text-warm-textMuted mb-1">
                                    <span>ربط مع Google Sheets الشخصي</span>
                                    <span id="sync-status" class="text-[9px] px-2 py-0.5 rounded-full bg-warm-border/30 text-warm-textMuted font-medium">غير متصل</span>
                                </div>
                                <input type="password" id="sheet-url-input" placeholder="رابط Web App الخاص بالـ Apps Script..." class="w-full text-xs p-2.5 rounded-lg border border-warm-border focus:outline-none focus:ring-1 focus:ring-gold-500 bg-warm-card text-warm-textPrimary" onchange="updateSheetURL()">
                                <div class="flex gap-2">
                                    <button onclick="syncFromGoogleSheets()" class="flex-1 py-1.5 px-3 bg-gold-500 hover:bg-gold-600 text-white rounded-lg text-xs font-medium transition-all flex items-center justify-center gap-1.5">
                                        <i class="fa-solid fa-rotate text-[10px]"></i> مزامنة الآن
                                    </button>
                                    <button onclick="removeSheetConnection()" class="py-1.5 px-3 bg-warm-header hover:bg-warm-border/40 text-warm-textSecondary rounded-lg text-xs font-medium border border-warm-border transition-all">
                                        إلغاء الربط
                                    </button>
                                </div>
                            </div>
                        </details>
                    </div>
                </div>
                
                <div class="flex gap-2.5 mt-6 pt-4 border-t border-warm-border/50">
                    <button onclick="window.print()" class="flex-1 py-2.5 px-4 rounded-xl bg-warm-header hover:bg-warm-border/40 text-warm-textSecondary text-xs font-medium border border-warm-border transition-all duration-150 flex items-center justify-center gap-2">
                        <i class="fa-solid fa-print"></i> طباعة كتقرير ورقي
                    </button>
                    <button onclick="confirmClearAllNotes()" class="py-2.5 px-4 rounded-xl hover:bg-red-50 text-red-700 text-xs font-medium transition-all duration-150 flex items-center justify-center gap-2">
                        <i class="fa-solid fa-eraser"></i> تهيئة البيانات
                    </button>
                </div>
            </div>

            <div class="bg-warm-card border border-warm-border rounded-[24px] p-6 shadow-soft-sm flex flex-col justify-between transition-all duration-200 hover:shadow-soft-md">
                <div>
                    <h3 class="font-bold text-sm text-warm-textPrimary mb-1.5 flex items-center gap-2.5">
                        <i class="fa-solid fa-chart-line text-gold-500 text-xs"></i>
                        <span>التحليل الكمي للملاحظات</span>
                    </h3>
                    <p class="text-[10px] text-warm-textMuted mb-5">مؤشرات حية لمتابعة نسبة تغطيتك اليومية لشهر ذو الحجة.</p>
                    
                    <div class="grid grid-cols-2 gap-4">
                        <div class="bg-[#FAF8F4] border border-warm-border/60 p-4 rounded-2xl">
                            <span class="text-[10px] text-warm-textMuted block">أيام تم رصدها</span>
                            <span class="text-2xl font-bold text-gold-500 font-mono" id="stat-noted-days">٠</span>
                            <span class="text-[9px] text-warm-textMuted block mt-1">من أصل ٣٠ يوماً</span>
                        </div>
                        <div class="bg-[#FAF8F4] border border-warm-border/60 p-4 rounded-2xl">
                            <span class="text-[10px] text-warm-textMuted block">إجمالي الإدخالات</span>
                            <span class="text-2xl font-bold text-warm-textPrimary font-mono" id="stat-total-notes">٠</span>
                            <span class="text-[9px] text-warm-textMuted block mt-1">مدخلات رصد مخزنة</span>
                        </div>
                    </div>
                </div>
                
                <div class="mt-6">
                    <div class="flex justify-between text-[11px] text-warm-textSecondary mb-2 font-medium">
                        <span>النسبة العامة للاكتمال</span>
                        <span id="coverage-percentage" class="font-mono">٠%</span>
                    </div>
                    <div class="w-full bg-[#FAF8F4] border border-warm-border/40 rounded-full h-1.5 overflow-hidden">
                        <div id="coverage-bar" class="bg-gold-500 h-1.5 rounded-full transition-all duration-300" style="width: 0%"></div>
                    </div>
                </div>
            </div>

            <div class="bg-warm-card border border-warm-border rounded-[24px] p-6 shadow-soft-sm transition-all duration-200 hover:shadow-soft-md">
                <h3 class="font-bold text-sm text-warm-textPrimary mb-3 flex items-center gap-2.5">
                    <i class="fa-solid fa-star-and-crescent text-gold-500 text-xs"></i>
                    <span>المحطات والأيام العظيمة</span>
                </h3>
                <p class="text-[10px] text-warm-textMuted mb-3">اضغط على أي محطة للانتقال المباشر إليها بالجدول:</p>
                
                <ul class="space-y-1 text-xs text-warm-textSecondary">
                    <li onclick="scrollToDay(1)" class="flex items-center justify-between p-2.5 rounded-xl hover:bg-gold-500/5 transition duration-150 cursor-pointer">
                        <span class="flex items-center gap-2 font-medium">
                            <span class="w-1.5 h-1.5 rounded-full bg-gold-500"></span>
                            العشر الأوائل الفضيلة
                        </span>
                        <span class="text-warm-textMuted font-mono text-[10px]">٠١ - ٠٩ ذو الحجة</span>
                    </li>
                    <li onclick="scrollToDay(8)" class="flex items-center justify-between p-2.5 rounded-xl hover:bg-gold-500/5 transition duration-150 cursor-pointer">
                        <span class="flex items-center gap-2 font-medium">
                            <span class="w-1.5 h-1.5 rounded-full bg-accent-green"></span>
                            يوم التروية
                        </span>
                        <span class="text-warm-textMuted font-mono text-[10px]">٠٨ ذو الحجة</span>
                    </li>
                    <li onclick="scrollToDay(9)" class="flex items-center justify-between p-2.5 rounded-xl bg-gold-500/5 hover:bg-gold-500/10 transition duration-150 cursor-pointer border border-gold-500/10">
                        <span class="flex items-center gap-2 font-bold text-gold-600">
                            <span class="w-1.5 h-1.5 rounded-full bg-gold-500 animate-pulse"></span>
                            يوم عرفة المبارك
                        </span>
                        <span class="text-gold-600 font-bold font-mono text-[10px]">٠٩ ذو الحجة</span>
                    </li>
                    <li onclick="scrollToDay(10)" class="flex items-center justify-between p-2.5 rounded-xl hover:bg-gold-500/5 transition duration-150 cursor-pointer">
                        <span class="flex items-center gap-2 font-medium text-warm-textPrimary">
                            <span class="w-1.5 h-1.5 rounded-full bg-warm-textPrimary"></span>
                            عيد الأضحى السعيد
                        </span>
                        <span class="text-warm-textMuted font-mono text-[10px]">١٠ ذو الحجة</span>
                    </li>
                </ul>
            </div>
        </div>

        <div class="bg-warm-card border border-warm-border rounded-[28px] p-6 sm:p-10 shadow-soft-md relative">
            
            <!-- Calendar Header Elements -->
            <div class="flex flex-col sm:flex-row items-center justify-between border-b border-warm-border pb-6 mb-8 gap-4">
                <div class="text-center sm:text-right">
                    <div class="text-warm-textPrimary font-bold text-lg flex items-center justify-center sm:justify-start gap-2">
                        <i class="fa-regular fa-calendar-days text-gold-500 text-sm"></i>
                        <span>جدول الرصد لشهر ذو الحجة ١٤٤٧ هـ</span>
                    </div>
                    <div class="text-warm-textMuted text-[11px] mt-1 font-light">طبيعة التوثيق: علمية، هادئة ورصينة في استعراض الأيام</div>
                </div>
                
                <!-- Custom Minimalist Legend -->
                <div class="flex flex-wrap items-center justify-center gap-4 text-[10px] text-warm-textMuted font-medium">
                    <span class="flex items-center gap-1.5"><span class="w-2.5 h-2.5 rounded-full bg-gold-500"></span> الهجري</span>
                    <span class="flex items-center gap-1.5 gregorian-label-indicator"><span class="w-2.5 h-2.5 rounded-full bg-warm-textMuted"></span> الميلادي</span>
                    <span class="flex items-center gap-1.5"><span class="w-2.5 h-2.5 rounded bg-gold-500/10 border border-gold-500/20"></span> محطات خاصة</span>
                </div>
            </div>

            <!-- Calendar Days of the Week Header Grid -->
            <div class="grid grid-cols-7 gap-1.5 sm:gap-4 mb-4 text-center font-bold text-[11px] sm:text-xs text-warm-textSecondary select-none">
                <div class="py-2.5 bg-warm-header/50 border border-warm-border/40 rounded-xl">السبت</div>
                <div class="py-2.5 bg-warm-header/50 border border-warm-border/40 rounded-xl">الأحد</div>
                <div class="py-2.5 bg-warm-header/50 border border-warm-border/40 rounded-xl">الاثنين</div>
                <div class="py-2.5 bg-warm-header/50 border border-warm-border/40 rounded-xl">الثلاثاء</div>
                <div class="py-2.5 bg-warm-header/50 border border-warm-border/40 rounded-xl">الأربعاء</div>
                <div class="py-2.5 bg-warm-header/50 border border-warm-border/40 rounded-xl">الخميس</div>
                <div class="py-2.5 bg-warm-header/50 border border-warm-border/40 rounded-xl">الجمعة</div>
            </div>

            <!-- Dynamically populated Grid -->
            <div id="calendar-days-grid" class="grid grid-cols-7 gap-1.5 sm:gap-4 print-grid">
                <!-- Javascript will inject clean, highly refined days here -->
            </div>
        </div>
    </main>

    <div id="note-modal" class="fixed inset-0 bg-warm-textPrimary/40 backdrop-blur-sm flex items-center justify-center p-4 z-50 hidden no-print transition-all duration-200 opacity-0">
        <div class="bg-warm-card rounded-[24px] max-w-lg w-full shadow-soft-lg overflow-hidden transform scale-95 transition-all duration-200 border border-warm-border" id="modal-container">
            <!-- Modal Header -->
            <div class="bg-warm-header px-6 py-5 relative border-b border-warm-border/60">
                <button onclick="closeModal()" class="absolute left-6 top-5 text-warm-textMuted hover:text-warm-textPrimary transition duration-150 text-base">
                    <i class="fa-solid fa-xmark"></i>
                </button>
                <div class="flex items-center gap-3">
                    <div class="w-9 h-9 rounded-full bg-gold-500/10 flex items-center justify-center text-gold-500">
                        <i class="fa-regular fa-pen-to-square"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-sm text-warm-textPrimary" id="modal-title">ملاحظات اليوم</h4>
                        <p class="text-[10px] text-warm-textMuted font-mono mt-0.5" id="modal-subtitle">الموافق المقابل</p>
                    </div>
                </div>
            </div>
            
            <!-- Modal Body content -->
            <div class="p-6 space-y-4">
                <!-- Tag Filters/Selectors (Minimal Design) -->
                <div>
                    <label class="block text-[10px] font-bold text-warm-textMuted tracking-wider mb-2 uppercase">تصنيف المذكرة</label>
                    <div class="grid grid-cols-4 gap-2">
                        <button type="button" onclick="selectTag('worship')" id="tag-worship" class="py-2 px-1 rounded-xl text-[11px] font-medium border flex items-center justify-center gap-1.5 transition-all duration-150">
                            <span class="text-xs">🕋</span>
                            <span>عبادة</span>
                        </button>
                        <button type="button" onclick="selectTag('work')" id="tag-work" class="py-2 px-1 rounded-xl text-[11px] font-medium border flex items-center justify-center gap-1.5 transition-all duration-150">
                            <span class="text-xs">💼</span>
                            <span>مهام</span>
                        </button>
                        <button type="button" onclick="selectTag('family')" id="tag-family" class="py-2 px-1 rounded-xl text-[11px] font-medium border flex items-center justify-center gap-1.5 transition-all duration-150">
                            <span class="text-xs">👥</span>
                            <span>عائلي</span>
                        </button>
                        <button type="button" onclick="selectTag('general')" id="tag-general" class="py-2 px-1 rounded-xl text-[11px] font-medium border flex items-center justify-center gap-1.5 transition-all duration-150">
                            <span class="text-xs">📝</span>
                            <span>عام</span>
                        </button>
                    </div>
                </div>

                <!-- Textarea -->
                <div>
                    <label for="note-text-area" class="block text-[10px] font-bold text-warm-textMuted tracking-wider mb-2 uppercase">نص الملاحظة أو التذكير اليومي</label>
                    <textarea id="note-text-area" rows="4" placeholder="اكتب مذكراتك بسلام وأمان، سيتم تخزينها بالمتصفح..." class="w-full rounded-xl border border-warm-border focus:border-gold-500 focus:ring-1 focus:ring-gold-500/50 text-xs p-3 transition outline-none bg-white text-warm-textPrimary"></textarea>
                </div>
                
                <!-- Quick Recommendations -->
                <div class="bg-warm-header/40 p-3 rounded-xl border border-warm-border/40">
                    <div class="text-[10px] font-bold text-warm-textSecondary mb-2 flex items-center gap-1.5">
                        <i class="fa-regular fa-lightbulb text-gold-500 text-[11px]"></i>
                        <span>اقتراحات ملهمة لتوثيق هذا اليوم:</span>
                    </div>
                    <div class="flex flex-wrap gap-1.5" id="modal-quick-suggestions">
                        <!-- Loaded dynamically based on the active day -->
                    </div>
                </div>
            </div>

            <!-- Modal Footer -->
            <div class="bg-warm-header px-6 py-4 flex items-center justify-between border-t border-warm-border/50">
                <button type="button" onclick="deleteNote()" class="py-2 px-3 rounded-lg hover:bg-red-50 text-red-600 text-xs font-medium transition flex items-center gap-1.5">
                    <i class="fa-regular fa-trash-can"></i>
                    <span>حذف</span>
                </button>
                <div class="flex items-center gap-2">
                    <button type="button" onclick="closeModal()" class="py-2 px-4 rounded-lg hover:bg-warm-border/40 text-warm-textSecondary text-xs font-medium transition">إلغاء</button>
                    <button type="button" onclick="saveNote()" class="py-2 px-5 rounded-lg bg-gold-500 hover:bg-gold-600 text-white text-xs font-medium shadow-soft-sm transition">حفظ التوثيق</button>
                </div>
            </div>
        </div>
    </div>

    <div id="custom-alert-dialog" class="fixed inset-0 bg-warm-textPrimary/40 flex items-center justify-center p-4 z-50 hidden no-print transition-all duration-200">
        <div class="bg-warm-card rounded-[24px] max-w-sm w-full p-6 text-center shadow-soft-lg border border-warm-border">
            <div class="w-11 h-11 rounded-full bg-gold-500/10 text-gold-500 flex items-center justify-center mx-auto text-sm mb-3.5">
                <i class="fa-solid fa-circle-exclamation"></i>
            </div>
            <h4 class="font-bold text-sm text-warm-textPrimary" id="alert-title-text">تنبيه</h4>
            <p class="text-xs text-warm-textSecondary mt-2 leading-relaxed" id="alert-message-text">محتوى التنبيه</p>
            <div class="flex gap-2.5 mt-6">
                <button onclick="closeAlert()" id="alert-cancel-button" class="flex-1 py-2 px-4 rounded-xl bg-warm-header hover:bg-warm-border/40 text-warm-textSecondary text-xs font-semibold transition">إلغاء</button>
                <button id="alert-confirm-button" class="flex-1 py-2 px-4 rounded-xl bg-red-600 hover:bg-red-700 text-white text-xs font-semibold transition">تأكيد</button>
            </div>
        </div>
    </div>

    <!-- Minimalist Footer -->
    <footer class="bg-warm-header border-t border-warm-border/40 text-warm-textMuted py-8 mt-16 no-print">
        <div class="max-w-7xl mx-auto px-6 text-center text-xs space-y-1">
            <p class="font-medium text-warm-textSecondary">التقويم التوثيقي لشهر ذو الحجة ١٤٤٧ هـ</p>
            <p class="font-light">رؤية تصميمية علمية وهادئة • جميع البيانات آمنة تماماً ومحفوظة محلياً.</p>
        </div>
    </footer>

    <script>
        // Core state values
        let displayGregorianState = true;
        let selectedDayIndex = null;
        let selectedTagState = 'general';
        let notesDataStorage = {}; // key: day-{num}, val: {text, tag}
        let googleSheetUrl = '';

        // Religious suggestions database
        const recommendationList = {
            general: ["الاستغفار والذكر اليومي", "متابعة المهام بإنتاجية", "توثيق اليوم بسلام"],
            tenDays: ["التكبير المطلق", "صيام هذا اليوم المبارك", "صدقة مباركة مستورة"],
            arafah: ["صيام عرفة وتكفير السنتين", "الإلحاح بالدعاء", "الذكر المأثور"],
            eid: ["صلة الرحم والتهنئة", "أداء الأضحية بسلام", "الاحتفال الهادئ مع العائلة"],
            tashreeq: ["التكبير المقيد عقب الصلوات", "أذكار الصباح والمساء"]
        };

        // Static parameters for Dhu al-Hijjah 1447 (Starting Monday, May 18, 2026)
        const totalMonthDays = 30;
        const offsetFirstDay = 2; // Monday (0=Sat, 1=Sun, 2=Mon, 3=Tue, 4=Wed, 5=Thu, 6=Fri)

        const arabicNumerals = ["٠", "١", "٢", "٣", "٤", "٥", "٦", "٧", "٨", "٩"];
        const convertToArabicNumber = (num) => String(num).split('').map(d => arabicNumerals[parseInt(d)]).join('');

        // Generate full structured static array of the days
        const generatedDaysArray = [];
        for (let hDayNum = 1; hDayNum <= totalMonthDays; hDayNum++) {
            // Gregorian conversion logic
            let gDay = 18 + hDayNum - 1;
            let gMonthName = "مايو";
            let gYear = 2026;

            if (gDay > 31) {
                gDay = gDay - 31;
                gMonthName = "يونيو";
            }

            let categoryTag = "";
            let specialCardClass = "";
            let tagBadgeClass = "";
            let keySuggestionGroup = "general";

            if (hDayNum >= 1 && hDayNum <= 9) {
                keySuggestionGroup = "tenDays";
                if (hDayNum === 1) {
                    categoryTag = "غرة العشر الأوائل";
                    tagBadgeClass = "bg-gold-500/10 text-gold-600 border border-gold-500/20";
                } else if (hDayNum === 8) {
                    categoryTag = "يوم التروية";
                    tagBadgeClass = "bg-accent-green/10 text-accent-green border border-accent-green/20";
                } else if (hDayNum === 9) {
                    categoryTag = "يوم عرفة العظيم";
                    tagBadgeClass = "bg-gold-500 text-white border border-transparent";
                    specialCardClass = "bg-gradient-to-br from-warm-card to-gold-500/5 border-gold-500/50 shadow-soft-md ring-1 ring-gold-500/20";
                    keySuggestionGroup = "arafah";
                } else {
                    categoryTag = "العشر المباركة";
                    tagBadgeClass = "bg-gold-500/5 text-gold-600 border border-gold-500/10";
                }
            } else if (hDayNum === 10) {
                categoryTag = "عيد الأضحى المبارك";
                tagBadgeClass = "bg-warm-textPrimary text-white border border-transparent";
                specialCardClass = "bg-gradient-to-br from-warm-card to-warm-header border-warm-border shadow-soft-md";
                keySuggestionGroup = "eid";
            } else if (hDayNum >= 11 && hDayNum <= 13) {
                keySuggestionGroup = "tashreeq";
                if (hDayNum === 11) categoryTag = "يوم التشريق الأول";
                else if (hDayNum === 12) categoryTag = "يوم التشريق الثاني";
                else if (hDayNum === 13) categoryTag = "يوم التشريق الثالث";
                tagBadgeClass = "bg-warm-textSecondary/5 text-warm-textSecondary border border-warm-border";
            }

            generatedDaysArray.push({
                hijriDayNumber: hDayNum,
                hijriDayArabic: convertToArabicNumber(hDayNum),
                gregorianDateString: `${convertToArabicNumber(gDay)} ${gMonthName}`,
                specialCategoryLabel: categoryTag,
                specialCardClassStyle: specialCardClass,
                tagBadgeClassStyle: tagBadgeClass,
                suggestionCategory: keySuggestionGroup
            });
        }

        // Window load initial actions
        window.onload = function() {
            loadLocalNotes();
            loadLocalSettings();
            renderActiveCalendar();
            calculateCountdownToEid();
            updateLiveStats();

            if (googleSheetUrl) {
                syncFromGoogleSheets();
            }
        };

        // Load functions
        function loadLocalNotes() {
            const savedData = localStorage.getItem('dhulhijjah_1447_clean_notes');
            if (savedData) {
                try {
                    notesDataStorage = JSON.parse(savedData);
                } catch(e) {
                    console.error("Local Storage Parsing Error", e);
                    notesDataStorage = {};
                }
            }
        }

        function loadLocalSettings() {
            const visibilityPref = localStorage.getItem('dhulhijjah_greg_visible_pref');
            if (visibilityPref !== null) {
                displayGregorianState = visibilityPref === 'true';
            }
            updateGregorianButtonUI();

            const savedSheet = localStorage.getItem('dhulhijjah_sheet_connection_url');
            if (savedSheet) {
                googleSheetUrl = savedSheet;
                document.getElementById('sheet-url-input').value = googleSheetUrl;
                updateSyncStatusUI('متصل ومزامن', 'bg-gold-500/10 text-gold-600 border border-gold-500/20');
            }
        }

        function saveNotesData() {
            localStorage.setItem('dhulhijjah_1447_clean_notes', JSON.stringify(notesDataStorage));
            updateLiveStats();
        }

        // Toggle Gregorian views
        function toggleGregorian() {
            displayGregorianState = !displayGregorianState;
            localStorage.setItem('dhulhijjah_greg_visible_pref', displayGregorianState);
            updateGregorianButtonUI();

            const elements = document.querySelectorAll('.gregorian-date-label');
            elements.forEach(el => {
                if (displayGregorianState) {
                    el.classList.remove('hidden');
                } else {
                    el.classList.add('hidden');
                }
            });
        }

        function updateGregorianButtonUI() {
            const btn = document.getElementById('toggle-gregorian');
            const dot = document.getElementById('toggle-switch-dot');
            if (displayGregorianState) {
                btn.classList.add('bg-gold-500');
                btn.classList.remove('bg-warm-border');
                dot.classList.add('translate-x-5');
                dot.classList.remove('translate-x-0');
            } else {
                btn.classList.add('bg-warm-border');
                btn.classList.remove('bg-gold-500');
                dot.classList.add('translate-x-0');
                dot.classList.remove('translate-x-5');
            }
        }

        function renderActiveCalendar() {
            const container = document.getElementById('calendar-days-grid');
            container.innerHTML = '';

            // Inject offsets for the start day of the week (Monday start index 2)
            for (let index = 0; index < offsetFirstDay; index++) {
                const offsetCell = document.createElement('div');
                offsetCell.className = "bg-warm-header/20 border border-warm-border/30 rounded-2xl min-h-[100px] sm:min-h-[150px] opacity-40 flex items-center justify-center no-print select-none";
                offsetCell.innerHTML = `<span class="text-[10px] text-warm-textMuted">ذو القعدة</span>`;
                container.appendChild(offsetCell);
            }

            // Inject month days
            generatedDaysArray.forEach(day => {
                const cell = document.createElement('div');
                cell.id = `day-cell-id-${day.hijriDayNumber}`;
                
                let baseCellClasses = `bg-warm-card border rounded-[22px] p-3 sm:p-5 min-h-[110px] sm:min-h-[150px] flex flex-col justify-between transition-all duration-150 hover:shadow-soft-sm cursor-pointer group relative overflow-hidden print-card ${day.specialCardClassStyle || 'border-warm-border/60 hover:border-gold-500/80'}`;
                
                cell.className = baseCellClasses;
                cell.onclick = () => openNoteModal(day.hijriDayNumber);

                const existingNoteData = notesDataStorage[`day-${day.hijriDayNumber}`];
                const hasNote = existingNoteData && existingNoteData.text.trim() !== "";

                let badgeMarkup = "📝";
                if (hasNote && existingNoteData.tag) {
                    if (existingNoteData.tag === 'worship') badgeMarkup = "🕋";
                    else if (existingNoteData.tag === 'work') badgeMarkup = "💼";
                    else if (existingNoteData.tag === 'family') badgeMarkup = "👥";
                }

                cell.innerHTML = `
                    <div class="flex items-start justify-between">
                        <!-- Hijri Number -->
                        <span class="text-xl sm:text-2xl font-bold text-warm-textPrimary group-hover:text-gold-500 transition duration-150 font-sans">${day.hijriDayArabic}</span>
                        
                        <!-- Mini visual tag wrapper -->
                        <div class="flex items-center gap-1">
                            ${hasNote ? `<span class="text-xs sm:text-sm" title="ملاحظة مدونة">${badgeMarkup}</span>` : ''}
                            ${day.specialCategoryLabel ? `<span class="sm:hidden block w-1.5 h-1.5 rounded-full bg-gold-500"></span>` : ''}
                        </div>
                    </div>

                    <!-- Category tag text (Large screens only) -->
                    ${day.specialCategoryLabel ? `
                        <div class="hidden sm:block my-2 text-[9px] font-medium px-2 py-0.5 rounded-full text-center whitespace-normal truncate ${day.tagBadgeClassStyle}">
                            ${day.specialCategoryLabel}
                        </div>
                    ` : ''}

                    <!-- Bottom elements -->
                    <div class="flex items-end justify-between mt-2 pt-2 border-t border-warm-border/20">
                        <!-- Gregorian element -->
                        <span class="gregorian-date-label text-[10px] text-warm-textMuted font-medium font-english ${displayGregorianState ? '' : 'hidden'}">
                            ${day.gregorianDateString}
                        </span>

                        <!-- Note preview -->
                        <div class="hidden md:block max-w-[110px] truncate text-[10px] text-warm-textMuted group-hover:text-warm-textPrimary transition duration-150 font-light">
                            ${hasNote ? existingNoteData.text : 'أضف رصداً...'}
                        </div>
                    </div>

                    <!-- Print-specific layout representation -->
                    <div class="hidden print-note">
                        ${hasNote ? `<strong>توثيق اليوم (${badgeMarkup}):</strong> ${existingNoteData.text}` : ''}
                    </div>
                `;

                container.appendChild(cell);
            });
        }

        // Scroll animation function
        function scrollToDay(dayNum) {
            const el = document.getElementById(`day-cell-id-${dayNum}`);
            if (el) {
                el.scrollIntoView({ behavior: 'smooth', block: 'center' });
                el.classList.add('ring-2', 'ring-gold-500/60');
                setTimeout(() => {
                    el.classList.remove('ring-2', 'ring-gold-500/60');
                }, 2000);
            }
        }

        // Modal triggers
        function openNoteModal(dayNum) {
            selectedDayIndex = dayNum;
            const dayData = generatedDaysArray[dayNum - 1];

            document.getElementById('modal-title').innerText = `رصد يوم ${dayData.hijriDayArabic} ذو الحجة`;
            document.getElementById('modal-subtitle').innerText = `التاريخ المتوقع: ${dayData.gregorianDateString} ٢٠٢٦ م`;

            const currentNote = notesDataStorage[`day-${dayNum}`];
            if (currentNote) {
                document.getElementById('note-text-area').value = currentNote.text;
                selectTag(currentNote.tag || 'general');
            } else {
                document.getElementById('note-text-area').value = '';
                selectTag('general');
            }

            // Clear & populate suggestions
            const suggestionsWrapper = document.getElementById('modal-quick-suggestions');
            suggestionsWrapper.innerHTML = '';

            const list = recommendationList[dayData.suggestionCategory] || recommendationList['general'];
            list.forEach(rec => {
                const btn = document.createElement('button');
                btn.type = 'button';
                btn.className = "text-[10px] px-2.5 py-1 rounded-lg bg-warm-header text-warm-textSecondary hover:bg-gold-500 hover:text-white border border-warm-border transition duration-150";
                btn.innerText = `+ ${rec}`;
                btn.onclick = () => insertSuggestionText(rec);
                suggestionsWrapper.appendChild(btn);
            });

            // Display modal
            const modal = document.getElementById('note-modal');
            const container = document.getElementById('modal-container');
            modal.classList.remove('hidden');
            setTimeout(() => {
                modal.classList.add('opacity-100');
                modal.classList.remove('opacity-0');
                container.classList.add('scale-100');
                container.classList.remove('scale-95');
            }, 10);
        }

        function closeModal() {
            const modal = document.getElementById('note-modal');
            const container = document.getElementById('modal-container');
            modal.classList.add('opacity-0');
            modal.classList.remove('opacity-100');
            container.classList.add('scale-95');
            container.classList.remove('scale-100');
            setTimeout(() => {
                modal.classList.add('hidden');
            }, 200);
        }

        function selectTag(tagName) {
            selectedTagState = tagName;
            const allTags = ['worship', 'work', 'family', 'general'];

            allTags.forEach(t => {
                const el = document.getElementById(`tag-${t}`);
                if (t === tagName) {
                    el.className = "py-2 px-1 rounded-xl text-[11px] font-semibold bg-gold-500 text-white border border-transparent shadow-soft-sm transition-all duration-150";
                } else {
                    el.className = "py-2 px-1 rounded-xl text-[11px] font-medium bg-white text-warm-textSecondary border border-warm-border hover:bg-warm-header transition-all duration-150";
                }
            });
        }

        function insertSuggestionText(textVal) {
            const textarea = document.getElementById('note-text-area');
            const baseText = textarea.value.trim();
            if (baseText === '') {
                textarea.value = textVal;
            } else {
                textarea.value = baseText + "، " + textVal;
            }
            textarea.focus();
        }

        // Saving and Deleting elements
        function saveNote() {
            const textContent = document.getElementById('note-text-area').value.trim();
            if (textContent !== '') {
                notesDataStorage[`day-${selectedDayIndex}`] = {
                    text: textContent,
                    tag: selectedTagState
                };
            } else {
                delete notesDataStorage[`day-${selectedDayIndex}`];
            }

            saveNotesData();
            renderActiveCalendar();
            closeModal();

            if (googleSheetUrl) {
                pushNoteToGoogleSheets(selectedDayIndex, textContent, selectedTagState);
            }
        }

        function deleteNote() {
            document.getElementById('note-text-area').value = '';
            delete notesDataStorage[`day-${selectedDayIndex}`];
            saveNotesData();
            renderActiveCalendar();
            closeModal();

            if (googleSheetUrl) {
                pushNoteToGoogleSheets(selectedDayIndex, '', 'general');
            }
        }

        // Data backup & import structures
        function exportBackupData() {
            if (Object.keys(notesDataStorage).length === 0) {
                displayAlertBox("لا توجد مذكرات", "لا توجد ملاحظات أو مذكرات رصد لتصديرها حالياً.", true);
                return;
            }
            const dataStr = "data:text/json;charset=utf-8," + encodeURIComponent(JSON.stringify(notesDataStorage));
            const downloadAnchor = document.createElement('a');
            downloadAnchor.setAttribute("href", dataStr);
            downloadAnchor.setAttribute("download", "مذكرات_ذو_الحجة_1447.json");
            document.body.appendChild(downloadAnchor);
            downloadAnchor.click();
            downloadAnchor.remove();
        }

        function triggerImport() {
            document.getElementById('import-file-input').click();
        }

        function importBackupData(event) {
            const file = event.target.files[0];
            if (!file) return;

            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    const parsed = JSON.parse(e.target.result);
                    if (parsed && typeof parsed === 'object') {
                        notesDataStorage = { ...notesDataStorage, ...parsed };
                        saveNotesData();
                        renderActiveCalendar();
                        displayAlertBox("تم الاستيراد بنجاح", "تمت استعادة وتحديث مذكراتك بنجاح بالتقويم.", true);
                    } else {
                        displayAlertBox("خطأ في بنية الملف", "الملف المرفوع غير صالح للاستعادة.", true);
                    }
                } catch(err) {
                    displayAlertBox("عطل بالملف", "فشل قراءة ملف الاستيراد. الرجاء التحقق من الملف.", true);
                }
            };
            reader.readAsText(file);
            event.target.value = '';
        }

        function updateSheetURL() {
            const inputVal = document.getElementById('sheet-url-input').value.trim();
            if (inputVal) {
                googleSheetUrl = inputVal;
                localStorage.setItem('dhulhijjah_sheet_connection_url', googleSheetUrl);
                updateSyncStatusUI('جاري الربط...', 'bg-gold-500/10 text-gold-600 animate-pulse');
                syncFromGoogleSheets();
            }
        }

        function removeSheetConnection() {
            googleSheetUrl = '';
            localStorage.removeItem('dhulhijjah_sheet_connection_url');
            document.getElementById('sheet-url-input').value = '';
            updateSyncStatusUI('غير متصل', 'bg-warm-border/30 text-warm-textMuted');
        }

        function updateSyncStatusUI(statusText, classStyles) {
            const badge = document.getElementById('sync-status');
            badge.className = `text-[9px] px-2.5 py-0.5 rounded-full font-semibold ${classStyles}`;
            badge.innerText = statusText;
        }

        async function syncFromGoogleSheets() {
            if (!googleSheetUrl) return;
            updateSyncStatusUI('مزامنة...', 'bg-gold-500/10 text-gold-600 animate-pulse');

            try {
                const response = await fetch(googleSheetUrl);
                if (response.ok) {
                    const data = await response.json();
                    notesDataStorage = { ...notesDataStorage, ...data };
                    saveNotesData();
                    renderActiveCalendar();
                    updateSyncStatusUI('متصل ومزامن', 'bg-accent-green/10 text-accent-green border border-accent-green/20');
                } else {
                    updateSyncStatusUI('عطل بالاتصال', 'bg-red-500/10 text-red-600');
                }
            } catch(e) {
                console.error("Sheet Connection Sync Error", e);
                updateSyncStatusUI('فشل الاتصال', 'bg-red-500/10 text-red-600');
            }
        }

        async function pushNoteToGoogleSheets(dayNum, noteText, noteTag) {
            if (!googleSheetUrl) return;
            updateSyncStatusUI('جاري الرفع...', 'bg-gold-500/10 text-gold-600 animate-pulse');

            try {
                await fetch(googleSheetUrl, {
                    method: 'POST',
                    mode: 'no-cors',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify({
                        day_number: dayNum,
                        note_text: noteText,
                        tag: noteTag
                    })
                });
                updateSyncStatusUI('تم التحديث', 'bg-accent-green/10 text-accent-green');
            } catch(e) {
                console.error("Sheets push error", e);
                updateSyncStatusUI('فشل الرفع', 'bg-red-500/10 text-red-600');
            }
        }

        function updateLiveStats() {
            const keysWithNotes = Object.keys(notesDataStorage).filter(key => notesDataStorage[key].text.trim() !== "");
            const notesCount = keysWithNotes.length;

            document.getElementById('stat-noted-days').innerText = convertToArabicNumber(notesCount);
            document.getElementById('stat-total-notes').innerText = convertToArabicNumber(notesCount);

            const activePercentage = Math.round((notesCount / totalMonthDays) * 100);
            document.getElementById('coverage-percentage').innerText = `${convertToArabicNumber(activePercentage)}%`;
            document.getElementById('coverage-bar').style.width = `${activePercentage}%`;
        }

        function calculateCountdownToEid() {
            const currentDateStr = '2026-05-17'; // Today
            const targetEidDateStr = '2026-05-27'; // 10 Dhu al-Hijjah
            
            const current = new Date(currentDateStr);
            const target = new Date(targetEidDateStr);

            const differenceInTime = target.getTime() - current.getTime();
            const differenceInDays = Math.ceil(differenceInTime / (1000 * 3600 * 24));

            if (differenceInDays > 0) {
                document.getElementById('countdown-display').innerText = `باقي ${convertToArabicNumber(differenceInDays)} أيام على عيد الأضحى`;
            } else if (differenceInDays === 0) {
                document.getElementById('countdown-display').innerText = `اليوم عيد الأضحى المبارك 🎉`;
            } else {
                document.getElementById('countdown-display').innerText = `تقبل الله طاعاتكم وغفر لنا ولكم`;
            }
        }

        // Alert dialog box rendering
        function displayAlertBox(title, msg, isSuccessInfo = false) {
            const dialog = document.getElementById('custom-alert-dialog');
            document.getElementById('alert-title-text').innerText = title;
            document.getElementById('alert-message-text').innerText = msg;

            const confirmBtn = document.getElementById('alert-confirm-button');
            const cancelBtn = document.getElementById('alert-cancel-button');

            if (isSuccessInfo) {
                cancelBtn.classList.add('hidden');
                confirmBtn.innerText = "فهمت";
                confirmBtn.className = "flex-1 py-2 px-4 rounded-xl bg-gold-500 hover:bg-gold-600 text-white text-xs font-semibold transition text-center";
                confirmBtn.onclick = closeAlert;
            } else {
                cancelBtn.classList.remove('hidden');
                confirmBtn.innerText = "نعم، متأكد";
                confirmBtn.className = "flex-1 py-2 px-4 rounded-xl bg-red-600 hover:bg-red-700 text-white text-xs font-semibold transition text-center";
            }

            dialog.classList.remove('hidden');
        }

        function closeAlert() {
            document.getElementById('custom-alert-dialog').classList.add('hidden');
        }

        function confirmClearAllNotes() {
            displayAlertBox("تفريغ كامل البيانات", "هل أنت متأكد تماماً من رغبتك بتفريغ كافة مذكراتك؟ لن تتمكن من استرجاعها إلا في حال كنت تمتلك نسخة احتياطية مصدّرة سابقاً.");
            
            const confirmBtn = document.getElementById('alert-confirm-button');
            confirmBtn.onclick = function() {
                notesDataStorage = {};
                saveNotesData();
                renderActiveCalendar();
                closeAlert();

                if (googleSheetUrl) {
                    for (let dayIdx = 1; dayIdx <= totalMonthDays; dayIdx++) {
                        pushNoteToGoogleSheets(dayIdx, '', 'general');
                    }
                }
            }
        }
    </script>
</body>
</html>
