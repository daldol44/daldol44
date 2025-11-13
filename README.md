<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>최상위권 고교 입시 전략 (학부모 설명회용)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700;900&family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: #f0f4f8; /* Slightly lighter blue-gray background */
            color: #333;
        }
        .slide {
            width: 100%;
            min-height: 85vh; 
            background-color: white;
            /* Updated background: A subtle linear gradient */
            background-image: linear-gradient(135deg, #ffffff 0%, #f5f7fa 100%);
            padding: 3rem; 
            margin: 2rem auto;
            border-radius: 16px; /* Slightly more rounded corners */
            /* Updated shadow: Softer, more modern shadow */
            box-shadow: 0 10px 30px rgba(0, 40, 80, 0.08);
            display: flex;
            flex-direction: column;
            overflow: hidden;
            box-sizing: border-box; 
        }

        .slide-header {
            padding-bottom: 1rem;
            border-bottom: 3px solid #0a2d5e; 
            margin-bottom: 2rem;
        }

        .slide-header h2 {
            font-family: 'Montserrat', sans-serif;
            font-size: 2rem; 
            font-weight: 700;
            color: #0a2d5e; 
        }

        .chart-container {
            position: relative;
            width: 100%;
            height: 100%;
            max-height: 400px;
        }

        .roadmap-list li {
            padding-bottom: 0.75rem; 
        }
        .roadmap-list li:last-child {
            padding-bottom: 0;
        }

        /* Styles for new SVG icons */
        .icon-lg-svg {
            width: 80px;
            height: 80px;
            margin: 0 auto 1rem;
            filter: drop-shadow(0 4px 6px rgba(0,0,0,0.1));
            stroke-width: 1.5; /* Thinner stroke for elegance */
        }
        .icon-sm-svg {
            width: 40px;
            height: 40px;
            margin: 0 auto 0.5rem;
            stroke-width: 2;
        }


        /* Enhanced Color Palette */
        .color-primary { color: #0a2d5e; } /* Deep Blue - for titles/main elements */
        .color-secondary { color: #e67e22; } /* Orange - for contrast/highlights */
        .color-tertiary { color: #27ae60; } /* Green - for emphasis */
        .color-quaternary { color: #8e44ad; } /* Purple - for another emphasis */

        .bg-primary { background-color: #0a2d5e; }
        .bg-light-blue { background-color: #e8f0f8; } 
        .border-primary { border-color: #0a2d5e; }
        .border-secondary { border-color: #e67e22; }
        .border-tertiary { border-color: #27ae60; }


        @media print {
            @page {
                size: A4 portrait;
                margin: 0.5in;
            }
            body {
                background-color: white;
                margin: 0;
                padding: 0;
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }
            .slide {
                width: 100%;
                min-height: 95vh; 
                margin: 0;
                border: none;
                box-shadow: none;
                page-break-after: always; 
                padding: 0.25in;
                background-image: none; 
                border-radius: 0;
            }
            .slide:last-child {
                page-break-after: auto;
            }
            .no-print {
                display: none;
            }
            .chart-container {
                max-height: 350px;
            }
            table {
                font-size: 0.8rem;
            }
            th, td {
                padding: 0.5rem !important;
            }
            .icon-lg-svg { height: 4rem; width: 4rem; margin-bottom: 0.5rem;}
            .icon-sm-svg { height: 2.5rem; width: 2.5rem; margin-bottom: 0.25rem;}
        }
    </style>
</head>
<body>

    <!-- Removed the print header --><section class="slide flex-col justify-center items-center text-center">
        <h1 class="text-6xl font-extrabold color-primary mb-8 tracking-tight">최상위권 고교 입시 전략</h1>
        <p class="text-3xl font-medium text-gray-700 mb-12">영재고, 경기북과고, 상산고 심층 비교 분석</p>
        
        <div class="flex justify-center items-center space-x-16 mt-16">
            <!-- 영재고 아이콘 (뇌 + 회로) --><div class="flex flex-col items-center w-32">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" class="icon-lg-svg color-primary">
                    <path d="M12 2a4 4 0 0 0-4 4v2H7a2 2 0 0 0-2 2v3a2 2 0 0 0 2 2h1v2a4 4 0 0 0 8 0v-2h1a2 2 0 0 0 2-2v-3a2 2 0 0 0-2-2h-1V6a4 4 0 0 0-4-4Z"/><path d="M12 13v10"/><path d="M9 18H8a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1h1"/><path d="m14 15h1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-1"/><path d="M4.5 10.5h-2"/><path d="M21.5 10.5h-2"/><path d="M12 8v-2"/>
                </svg>
                <span class="text-lg font-semibold color-primary">영재학교</span>
            </div>
            <!-- 과학고 아이콘 (플라스크) - Updated Icon --><div class="flex flex-col items-center w-32">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" class="icon-lg-svg color-secondary">
                    <path d="M8.5 22a.5.5 0 0 1-.5-.5v-5.06c0-.33.1-.65.3-.9L14.42 8H18a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h3.58L15.7 15.6a.9.9 0 0 1 .3.9V21.5a.5.5 0 0 1-.5.5Z"/><path d="M8 3v1"/>
                </svg>
                <span class="text-lg font-semibold color-secondary">과학고</span>
            </div>
            <!-- 상산고 아이콘 (학사모) --><div class="flex flex-col items-center w-32">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" class="icon-lg-svg color-tertiary">
                    <path d="M21.42 10.922a1 1 0 0 0-.019-1.838L12.83 5.18a2 2 0 0 0-1.66 0L2.6 9.084a1 1 0 0 0 0 1.838l8.57 3.908a2 2 0 0 0 1.66 0z"/><path d="M22 10v6"/><path d="M6 12v5c0 3 2.5 5 6 5s6-2 6-5v-5"/>
                </svg>
                <span class="text-lg font-semibold color-tertiary">상산고</span>
            </div>
        </div>
        <p class="text-xl text-gray-600 mt-16">구리시 학부모님을 위한 입시 설명회 발표 자료</p>
    </section>

    
    <section class="slide" id="slide-2">
        <div class="slide-header">
            <h2>1. 중1부터 철저한 준비: 학교별 핵심 비교</h2>
        </div>
        <div class="overflow-auto flex-1">
            <table class="w-full text-left text-sm h-full rounded-lg overflow-hidden border border-gray-200">
                <thead class="bg-light-blue color-primary">
                    <tr class="text-center">
                        <th class="p-3 font-bold text-base">구분</th>
                        <th class="p-3 font-bold text-base">
                            <!-- 영재고 (소형) --><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" class="icon-sm-svg color-primary">
                                <path d="M12 2a4 4 0 0 0-4 4v2H7a2 2 0 0 0-2 2v3a2 2 0 0 0 2 2h1v2a4 4 0 0 0 8 0v-2h1a2 2 0 0 0 2-2v-3a2 2 0 0 0-2-2h-1V6a4 4 0 0 0-4-4Z"/><path d="M12 13v10"/><path d="M9 18H8a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1h1"/><path d="m14 15h1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-1"/><path d="M4.5 10.5h-2"/><path d="M21.5 10.5h-2"/><path d="M12 8v-2"/>
                            </svg>
                            영재학교 (전국 8개)
                        </th>
                        <th class="p-3 font-bold text-base">
                            <!-- 과학고 (소형) - Updated Icon --><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" class="icon-sm-svg color-secondary">
                                <path d="M8.5 22a.5.5 0 0 1-.5-.5v-5.06c0-.33.1-.65.3-.9L14.42 8H18a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h3.58L15.7 15.6a.9.9 0 0 1 .3.9V21.5a.5.5 0 0 1-.5.5Z"/><path d="M8 3v1"/>
                            </svg>
                            과학고 (경기북과고)
                        </th>
                        <th class="p-3 font-bold text-base">
                            <!-- 상산고 (소형) --><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" class="icon-sm-svg color-tertiary">
                                <path d="M21.42 10.922a1 1 0 0 0-.019-1.838L12.83 5.18a2 2 0 0 0-1.66 0L2.6 9.084a1 1 0 0 0 0 1.838l8.57 3.908a2 2 0 0 0 1.66 0z"/><path d="M22 10v6"/><path d="M6 12v5c0 3 2.5 5 6 5s6-2 6-5v-5"/>
                            </svg>
                            상산고 (전국 자사고)
                        </th>
                    </tr>
                </thead>
                <tbody class="divide-y divide-gray-200 bg-white">
                    <tr class="align-top hover:bg-gray-50 transition-colors">
                        <td class="p-3 font-medium">특징</td>
                        <td class="p-3">R&E 중심, 대학 수준 교육, AP/UP</td>
                        <td class="p-3">심화 과학/수학, 실험/탐구 중심</td>
                        <td class="p-3">'수학의 정석' 저자, 정시/수시 균형, 의대 실적</td>
                    </tr>
                    <tr class="align-top hover:bg-gray-50 transition-colors">
                        <td class="p-3 font-medium">장점</td>
                        <td class="p-3">최고의 학생들, 자유로운 연구, 의대 지원 가능(불이익 감수)</td>
                        <td class="p-3">우수 이공계 진학(KAIST 등), 심화학습</td>
                        <td class="p-3">의/치/한/약/수 실적, 전국구 인재, 높은 정시 경쟁력</td>
                    </tr>
                    <tr class="align-top hover:bg-gray-50 transition-colors">
                        <td class="p-3 font-medium">단점</td>
                        <td class="p-3">극심한 경쟁, 학업 스트레스, 높은 학비</td>
                        <td class="p-3">의/약대 지원 시 극심한 불이익, 이공계열 진학 강제</td>
                        <td class="p-3">높은 학비, 기숙사 필수, 치열한 내신 경쟁</td>
                    </tr>
                    <tr class="align-top hover:bg-gray-50 transition-colors">
                        <td class="p-3 font-medium">주소지 (구리시)</td>
                        <td class="p-3"><span class="font-bold text-green-700">유리 (영향 없음)</span><br>전국 단위 선발.</td>
                        <td class="p-3"><span class="font-bold text-red-700">불리 (지원 고정)</span><br>경기북과고만 지원 가능.</td>
                        <td class="p-3"><span class="font-bold text-green-700">유리 (영향 없음)</span><br>전국 단위 선발.</td>
                    </tr>
                    <tr class="align-top hover:bg-gray-50 transition-colors">
                        <td class="p-3 font-medium">선발 시기</td>
                        <td class="p-3">4월~8월 (전기)</td>
                        <td class="p-3">8월~11월 (후기)</td>
                        <td class="p-3">12월 (후기)</td>
                    </tr>
                    <tr class="align-top hover:bg-gray-50 transition-colors">
                        <td class="p-3 font-medium">중복 지원</td>
                        <td class="p-3">1개교만 지원 가능 (과고와 중복 가능)</td>
                        <td class="p-3">영재고 불합격 시 지원 가능</td>
                        <td class="p-3">영재고/과고 불합격 시 지원 가능</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>

    
    <section class="slide" id="slide-3">
        <div class="slide-header">
            <h2>2. 필요 역량 및 선행 수준 (5점 만점)</h2>
        </div>
        <div class="flex-1 grid grid-cols-2 gap-8 items-center">
            <div class="chart-container" style="max-height: 450px;">
                <canvas id="prepRadarChart"></canvas>
            </div>
            <div class="text-gray-700 text-base space-y-4">
                <h3 class="font-bold text-xl color-primary mb-4">핵심 역량 분석</h3>
                <ul class="list-disc list-inside space-y-3 pl-4">
                    <li><strong class="color-primary">영재고:</strong> 수학/과학 심화 역량(KMO 등)과 <span class="font-bold text-red-600">독창적인 사고력</span>이 필수.</li>
                    <li><strong class="color-secondary">경기북과고:</strong> <span class="font-bold text-orange-600">탐구력, 실험 역량, 자기주도 학습 능력</span>을 높이 평가.</li>
                    <li><strong class="color-tertiary">상산고:</strong> 수학 선행과 더불어 <span class="font-bold text-green-600">전과목 최상위 내신 성적(All A)</span>과 인문학적 소양도 중요.</li>
                </ul>
            </div>
        </div>
    </section>

    
    <section class="slide" id="slide-4">
        <div class="slide-header">
            <h2>3. 생기부 및 평가 핵심 요소</h2>
        </div>
        <div class="flex-1 grid grid-cols-3 gap-6 items-start">
            
            <div class="text-center flex flex-col h-full bg-white rounded-lg p-4 shadow-lg border border-gray-100">
                <h3 class="text-xl font-bold color-primary mb-3">영재학교</h3>
                <div class="chart-container flex-grow" style="height: 200px; max-height: 220px;">
                    <canvas id="evalDonutChart1"></canvas>
                </div>
                <ul class="mt-4 text-sm text-left list-disc list-inside px-2 text-gray-700">
                    <li><strong>핵심:</strong> 2/3단계 지필/캠프 성적</li>
                    <li><strong>세특:</strong> 수학/과학 분야 독창적 연구, 심화탐구 역량</li>
                    <li><strong>기타:</strong> 영재원/KMO 실적 (참고용)</li>
                </ul>
            </div>
            
            <div class="text-center flex flex-col h-full bg-white rounded-lg p-4 shadow-lg border border-gray-100">
                <h3 class="text-xl font-bold color-secondary mb-3">경기북과고</h3>
                <div class="chart-container flex-grow" style="height: 200px; max-height: 220px;">
                    <canvas id="evalDonutChart2"></canvas>
                </div>
                <ul class="mt-4 text-sm text-left list-disc list-inside px-2 text-gray-700">
                    <li><strong>핵심:</strong> 생기부 기반의 심층 면접</li>
                    <li><strong>세특:</strong> 특정 과학 분야 꾸준한 관심, 주도적 실험 과정</li>
                    <li><strong>기타:</strong> 수학/과학 내신 A등급 (성취도)</li>
                </ul>
            </div>
            
            <div class="text-center flex flex-col h-full bg-white rounded-lg p-4 shadow-lg border border-gray-100">
                <h3 class="text-xl font-bold color-tertiary mb-3">상산고</h3>
                <div class="chart-container flex-grow" style="height: 200px; max-height: 220px;">
                    <canvas id="evalDonutChart3"></canvas>
                </div>
                <ul class="mt-4 text-sm text-left list-disc list-inside px-2 text-gray-700">
                    <li><strong>핵심:</strong> 전과목 내신 성적 (A)</li>
                    <li><strong>세특:</strong> 폭넓고 깊이 있는 독서, 인성/리더십</li>
                    <li><strong>기타:</strong> '상산 인재상' 부합 (면접 중요)</li>
                </ul>
            </div>
        </div>
    </section>

    
    <section class="slide" id="slide-5">
        <div class="slide-header">
            <h2>4. 최신 입시 경향 및 경쟁률 (2025 추정)</h2>
        </div>
        <div class="flex-1 grid grid-cols-2 gap-8 items-center">
            <div class="chart-container" style="max-height: 400px;">
                <canvas id="competitionBarChart"></canvas>
            </div>
            <div class="text-gray-700 text-base space-y-4">
                <h3 class="font-bold text-xl color-primary mb-4">최신 입시 트렌드</h3>
                <ul class="list-disc list-inside space-y-3 pl-4">
                    <li><strong>의대 정원 확대:</strong> 최상위권 학생들의 '의대' 선호도가 더욱 높아졌습니다.</li>
                    <li><strong class="color-primary">영재고/상산고:</strong> 의대 진학의 문이 비교적 열려있어 인기가 동반 상승 중입니다.</li>
                    <li><strong class="color-secondary">경기북과고:</strong> 의대 지원 시 불이익이 커서, <span class="font-bold text-red-600">순수 이공계열 진학 의지</span>가 확고한 학생들이 주로 지원하는 경향이 뚜렷합니다.</li>
                    <li><strong>수능 중심 전형 확대:</strong> 정시 준비의 중요성이 커지고 있습니다.</li>
                </ul>
            </div>
        </div>
    </section>

    
    <section class="slide" id="slide-6">
        <div class="slide-header">
            <h2>5. 구리시 입시 결과 분석 (추정치)</h2>
        </div>
        <div class="flex-1 grid grid-cols-2 gap-8 items-center">
            <div class="chart-container" style="max-height: 300px;">
                <canvas id="guriPathChart"></canvas>
            </div>
            <div class="text-gray-700 text-base space-y-4">
                <h3 class="font-bold text-xl color-primary mb-4">구리시 최상위권 지원 패턴</h3>
                <ul class="list-disc list-inside space-y-3 pl-4">
                    <li><strong>데이터 출처:</strong> 공식 자료가 아닌, 구리/남양주 학원가 데이터를 종합한 <span class="font-bold">추정치</span>입니다.</li>
                    <li><strong class="color-secondary">경기북과고:</strong> '경기도'라는 광역권 이점과 지리적 근접성으로 인해 구리시 최상위권 학생들이 가장 많이 목표하는 학교입니다.</li>
                    <li><strong class="color-primary">영재고/상산고:</strong> 전국 단위 선발이므로, 구리시 지역적 유불리 없이 <span class="font-bold">오직 실력으로 경쟁</span>합니다. 꾸준히 합격생을 배출하고 있습니다.</li>
                </ul>
            </div>
        </div>
    </section>

    
    <section class="slide" id="slide-7">
        <div class="slide-header">
            <h2>6. 지원 및 불합격 시 고교 결정 로드맵</h2>
        </div>
        <div class="flex-1 grid grid-cols-3 gap-6 items-start">
            
            <div class="bg-white rounded-lg p-5 border-t-4 border-primary shadow-xl">
                <h3 class="text-xl font-bold text-center color-primary mb-4">PLAN A (영재고 우선)</h3>
                <ul class="space-y-4 roadmap-list text-gray-800">
                    <li class="font-semibold text-lg">4~8월: 영재고 지원</li>
                    <li class="text-center text-red-600 font-bold">↓ (불합격 시)</li>
                    <li class="font-semibold text-lg">8~11월: 과고(경기북과고) 지원</li>
                    <li class="text-center text-red-600 font-bold">↓ (불합격 시)</li>
                    <li class="font-semibold text-lg">12월: 상산고/타 자사고/일반고 지원</li>
                </ul>
            </div>

            <div class="bg-white rounded-lg p-5 border-t-4 border-secondary shadow-xl">
                <h3 class="text-xl font-bold text-center color-secondary mb-4">PLAN B (과고 우선)</h3>
                <ul class="space-y-4 roadmap-list text-gray-800">
                    <li class="font-semibold text-lg">8~11월: 과고(경기북과고) 지원</li>
                    <li class="text-center text-red-600 font-bold">↓ (불합격 시)</li>
                    <li class="font-semibold text-lg">12월: 상산고/타 자사고/일반고 지원</li>
                    <li class="text-center text-red-600 font-bold">↓ (불합격 시)</li>
                    <li class="font-semibold text-lg">1월: 1지망 일반고 배정</li>
                </ul>
            </div>

            <div class="bg-white rounded-lg p-5 border-t-4 border-tertiary shadow-xl">
                <h3 class="text-xl font-bold text-center color-tertiary mb-4">PLAN C (상산고 우선)</h3>
                <ul class="space-y-4 roadmap-list text-gray-800">
                    <li class="font-semibold text-lg">12월: 상산고 지원</li>
                    <li class="text-center text-red-600 font-bold">↓ (불합격 시)</li>
                    <li class="font-semibold text-lg">1월: 1지망 일반고 배정</li>
                    <li class="text-sm text-gray-600 mt-4">* 특목/자사고 불합격 시 일반고 배정 불이익은 없습니다.</li>
                </ul>
            </div>

        </div>
    </section>
    
    
    <section class="slide" id="slide-8">
        <div class="slide-header">
            <h2>7. 학부모님께 드리는 최종 조언</h2>
        </div>
        <div class="flex-1 text-gray-700 text-lg space-y-6">
            <ul class="list-decimal list-inside space-y-6 pl-4">
                <li>
                    <strong class="text-2xl color-primary">자녀의 '진정한 강점'을 찾아주세요.</strong>
                    <p class="text-base pl-6 mt-2">무조건적인 최상위권 학교 지원보다는, 자녀가 수학/과학에서 타고난 재능을 보이는지, 꾸준히 탐구하는 것을 좋아하는지, 아니면 전반적으로 성실하고 꼼꼼한지 등 '아이의 성향과 강점'을 먼저 파악하는 것이 중요합니다.</p>
                </li>
                <li>
                    <strong class="text-2xl color-secondary">'Plan B'는 언제나 중요합니다.</strong>
                    <p class="text-base pl-6 mt-2">영재고/과고는 매우 높은 경쟁률을 보입니다. 합격하지 못했을 때를 대비하여 자녀가 진학할 수 있는 '차선책' 고등학교에 대한 충분한 정보를 미리 알아두시고, 불안해하지 않도록 격려하는 것이 필요합니다.</p>
                </li>
                <li>
                    <strong class="text-2xl color-tertiary">꾸준함과 자기주도학습이 핵심입니다.</strong>
                    <p class="text-base pl-6 mt-2">어떤 학교에 진학하든, 스스로 공부 계획을 세우고 실천하는 '자기주도학습 능력'은 가장 강력한 무기입니다. 학년이 올라갈수록 이 능력의 중요성은 더욱 커지므로, 어릴 때부터 길러줄 수 있도록 옆에서 지지해 주세요.</p>
                </li>
                <li>
                    <strong class="text-2xl text-red-700">긍정적인 태도와 믿음이 최고의 응원입니다.</strong>
                    <p class="text-base pl-6 mt-2">입시 과정은 학생뿐만 아니라 학부모님께도 힘든 시간일 수 있습니다. 자녀에게 압박감을 주기보다는 '할 수 있다'는 믿음과 긍정적인 응원으로 힘을 실어주는 것이 무엇보다 중요합니다.</p>
                </li>
            </ul>
        </div>
    </section>


    <script>
        window.onload = function () {
            
            const palette = {
                deepBlue: '#0a2d5e',    // Primary (영재고)
                orange: '#e67e22',      // Secondary (경기북과고)
                green: '#27ae60',       // Tertiary (상산고)
                purple: '#8e44ad',      // Quaternary
                lightBlue: '#5dade2',   // Used for sub-elements
                darkGray: '#333333',
                lightGray: '#aaaaaa',
                offWhite: '#eef0f8',
                red: '#e74c3c',
                yellow: '#f1c40f'
            };

            const tooltipTitleCallback = (tooltipItems) => {
                const item = tooltipItems[0];
                let label = item.chart.data.labels[item.dataIndex];
                if (Array.isArray(label)) {
                    return label.join(' ');
                } else {
                    return label;
                }
            };
            
            const commonTooltipOptions = {
                plugins: {
                    tooltip: {
                        callbacks: { title: tooltipTitleCallback },
                        backgroundColor: '#FFFFFF',
                        titleColor: palette.deepBlue,
                        bodyColor: palette.darkGray,
                        borderColor: '#DDDDDD',
                        borderWidth: 1,
                        padding: 10,
                        displayColors: true,
                        boxPadding: 4,
                        bodyFont: { size: 12 },
                        titleFont: { size: 14, weight: 'bold' }
                    },
                    legend: {
                        labels: {
                            color: palette.darkGray,
                            font: { size: 12 }
                        }
                    }
                }
            };

            var ctxRadar = document.getElementById('prepRadarChart');
            if(ctxRadar) {
                new Chart(ctxRadar.getContext('2d'), {
                    type: 'radar',
                    data: {
                        labels: ['수학(심화)', '물리', '화학', '생명/지구', '정보(코딩)', '국어/영어'],
                        datasets: [
                            { label: '영재고', data: [5, 5, 4, 3, 4, 2], backgroundColor: 'rgba(10, 45, 94, 0.2)', borderColor: palette.deepBlue, borderWidth: 2, pointBackgroundColor: palette.deepBlue},
                            { label: '경기북과고', data: [4, 4, 3, 3, 2, 3], backgroundColor: 'rgba(230, 126, 34, 0.2)', borderColor: palette.orange, borderWidth: 2, pointBackgroundColor: palette.orange},
                            { label: '상산고', data: [4, 3, 2, 2, 1, 5], backgroundColor: 'rgba(39, 174, 96, 0.2)', borderColor: palette.green, borderWidth: 2, pointBackgroundColor: palette.green}
                        ]
                    },
                    options: { 
                        responsive: true, 
                        maintainAspectRatio: false, 
                        ...commonTooltipOptions, 
                        scales: { 
                            r: { 
                                angleLines: { color: 'rgba(0, 0, 0, 0.1)' }, 
                                grid: { color: 'rgba(0, 0, 0, 0.15)' }, 
                                pointLabels: { color: palette.darkGray, font: { size: 13, weight: 'bold' } }, 
                                ticks: { backdropColor: 'transparent', color: palette.lightGray, beginAtZero: true, max: 5, stepSize: 1, font: { size: 10 } } 
                            } 
                        },
                        plugins: {
                            ...commonTooltipOptions.plugins,
                            legend: {
                                labels: {
                                    color: palette.darkGray,
                                    font: { size: 13, weight: 'bold' }
                                }
                            }
                        }
                    }
                });
            }

            var ctxDonut1 = document.getElementById('evalDonutChart1');
            if(ctxDonut1) {
                new Chart(ctxDonut1.getContext('2d'), {
                    type: 'doughnut',
                    data: { labels: ['2/3단계 시험', '생기부(수과학)', '면접/캠프'], datasets: [{ data: [50, 30, 20], backgroundColor: [palette.deepBlue, palette.lightBlue, palette.lightGray] }] },
                    options: { 
                        responsive: true, 
                        maintainAspectRatio: false, 
                        ...commonTooltipOptions, 
                        plugins: { 
                            ...commonTooltipOptions.plugins, 
                            legend: { 
                                position: 'bottom', align: 'start', 
                                labels: { font: {size: 10}, boxWidth: 10, padding: 8, color: palette.darkGray } 
                            } 
                        } 
                    }
                });
            }

            var ctxDonut2 = document.getElementById('evalDonutChart2');
            if(ctxDonut2) {
                new Chart(ctxDonut2.getContext('2d'), {
                    type: 'doughnut',
                    data: { labels: ['생기부(탐구)', '방문/소집 면접', '내신(수과학)'], datasets: [{ data: [40, 35, 25], backgroundColor: [palette.orange, '#F39C12' /* Lighter Orange */, palette.lightGray] }] },
                    options: { 
                        responsive: true, 
                        maintainAspectRatio: false, 
                        ...commonTooltipOptions, 
                        plugins: { 
                            ...commonTooltipOptions.plugins, 
                            legend: { 
                                position: 'bottom', align: 'start', 
                                labels: { font: {size: 10}, boxWidth: 10, padding: 8, color: palette.darkGray } 
                            } 
                        } 
                    }
                });
            }

            var ctxDonut3 = document.getElementById('evalDonutChart3');
            if(ctxDonut3) {
                new Chart(ctxDonut3.getContext('2d'), {
                    type: 'doughnut',
                    data: { labels: ['내신(전과목)', '생기부(독서/인성)', '면접'], datasets: [{ data: [50, 30, 20], backgroundColor: [palette.green, '#2ECC71' /* Lighter Green */, palette.lightGray] }] },
                    options: { 
                        responsive: true, 
                        maintainAspectRatio: false, 
                        ...commonTooltipOptions, 
                        plugins: { 
                            ...commonTooltipOptions.plugins, 
                            legend: { 
                                position: 'bottom', align: 'start', 
                                labels: { font: {size: 10}, boxWidth: 10, padding: 8, color: palette.darkGray } 
                            } 
                        } 
                    }
                });
            }

            var ctxBar = document.getElementById('competitionBarChart');
            if(ctxBar) {
                new Chart(ctxBar.getContext('2d'), {
                    type: 'bar',
                    data: {
                        labels: ['영재학교 (평균)', '경기북과고', '상산고 (전국)'],
                        datasets: [{ label: '2025학년도 추정 경쟁률 (대 1)', data: [13.5, 7.8, 3.2], backgroundColor: [palette.deepBlue, palette.orange, palette.green], borderWidth: 1, borderRadius: 6 }]
                    },
                    options: { 
                        responsive: true, 
                        maintainAspectRatio: false, 
                        ...commonTooltipOptions, 
                        scales: { 
                            y: { 
                                beginAtZero: true, 
                                grid: { color: 'rgba(0, 0, 0, 0.1)' }, 
                                ticks: { color: palette.lightGray, font: { size: 12 } } 
                            }, 
                            x: { 
                                grid: { display: false }, 
                                ticks: { color: palette.darkGray, font: { size: 14, weight: 'bold' } } 
                            } 
                        },
                        plugins: {
                            ...commonTooltipOptions.plugins,
                            legend: { display: false }
                        }
                    }
                });
            }

            var ctxBarGuri = document.getElementById('guriPathChart');
            if(ctxBarGuri) {
                new Chart(ctxBarGuri.getContext('2d'), {
                    type: 'bar',
                    data: {
                        labels: ['경기북과고', '영재고', '상산/외대/하나'],
                        datasets: [{ label: '구리시 최상위권 지원 비율 (추정)', data: [60, 25, 15], backgroundColor: [palette.orange, palette.deepBlue, palette.green], borderRadius: 6 }]
                    },
                    options: { 
                        indexAxis: 'y', 
                        responsive: true, 
                        maintainAspectRatio: false, 
                        ...commonTooltipOptions, 
                        plugins: { 
                            ...commonTooltipOptions.plugins, 
                            legend: { display: false } 
                        }, 
                        scales: { 
                            x: { 
                                beginAtZero: true, 
                                ticks: { callback: function(value) { return value + '%' }, color: palette.lightGray, font: { size: 12 } },
                                grid: { color: 'rgba(0, 0, 0, 0.1)' }
                            },
                            y: {
                                ticks: { color: palette.darkGray, font: { size: 14, weight: 'bold' } },
                                grid: { display: false }
                            }
                        } 
                    }
                });
            }
        };
    </script>
</body>
</html>

