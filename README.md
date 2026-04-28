<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>釜山親友團 7天6夜精緻之旅</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.0/font/bootstrap-icons.css">
    <style>
        :root { --primary-color: #003580; --accent-color: #00b1ff; }
        body { background-color: #f8f9fa; font-family: "Microsoft JhengHei", sans-serif; }
        .hero-section { background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1590615365451-4089989736dc?auto=format&fit=crop&q=80&w=1200'); background-size: cover; color: white; padding: 60px 0; text-align: center; }
        .day-card { border-radius: 15px; border-left: 5px solid var(--primary-color); margin-bottom: 20px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); }
        .vbp-badge { background-color: #ff4757; color: white; padding: 2px 8px; border-radius: 5px; font-size: 0.8rem; }
        .nav-link.active { background-color: var(--primary-color) !important; color: white !important; }
        .currency-box { background: white; border-radius: 15px; padding: 20px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); margin-bottom: 30px; }
        .btn-naver { background-color: #03C75A; color: white; border: none; }
        .btn-naver:hover { background-color: #02a34a; color: white; }
    </style>
</head>
<body>

<div class="hero-section">
    <h1>釜山親友團 7天6夜精緻行程</h1>
    <p>2026 / 08 / 19 – 08 / 25</p>
</div>

<div class="container mt-4">
    <div class="row">
        <div class="col-md-6 mb-3">
            <div class="card h-100 shadow-sm">
                <div class="card-header bg-dark text-white"><i class="bi bi-airplane"></i> 航班資訊</div>
                <div class="card-body">
                    <p class="mb-1"><strong>去程：</strong> 08/19 (三) BX796 14:15 高雄 → 17:55 釜山</p>
                    <p class="mb-0"><strong>回程：</strong> 08/25 (二) BX795 11:25 釜山 → 13:20 高雄</p>
                </div>
            </div>
        </div>
        
        <div class="col-md-6 mb-3">
            <div class="card h-100 shadow-sm">
                <div class="card-header bg-primary text-white"><i class="bi bi-buildings"></i> 住宿地點</div>
                <div class="card-body">
                    <h6 class="fw-bold">豪德酒店海雲台 Signature (Hound Hotel)</h6>
                    <p class="small mb-2">부산광역시 해운대구 해운대로594번길 15</p>
                    <a href="https://map.naver.com/p/search/HOUND%20HOTEL%20SIGNATURE" target="_blank" class="btn btn-naver btn-sm">
                        <i class="bi bi-geo-alt"></i> Naver Map 導航
                    </a>
                </div>
            </div>
        </div>
    </div>

    <div class="currency-box">
        <h5 class="mb-3"><i class="bi bi-cash-coin"></i> 預算試算 (台幣 TWD ↔ 韓元 KRW)</h5>
        <div class="row g-3">
            <div class="col-6">
                <label class="form-label">台幣 TWD</label>
                <input type="number" id="twdInput" class="form-control" placeholder="輸入台幣" oninput="convertCurrency('twd')">
            </div>
            <div class="col-6">
                <label class="form-label">韓元 KRW (約略)</label>
                <input type="number" id="krwInput" class="form-control" placeholder="輸入韓元" oninput="convertCurrency('krw')">
            </div>
        </div>
        <div class="mt-2 text-muted small">* 匯率基準：1 TWD ≈ 42 KRW (僅供參考)</div>
    </div>

    <ul class="nav nav-pills mb-4 justify-content-center" id="dayTab" role="tablist">
        <li class="nav-item"><button class="nav-link active mx-1" data-bs-toggle="pill" data-bs-target="#day1">D1</button></li>
        <li class="nav-item"><button class="nav-link mx-1" data-bs-toggle="pill" data-bs-target="#day2">D2</button></li>
        <li class="nav-item"><button class="nav-link mx-1" data-bs-toggle="pill" data-bs-target="#day3">D3</button></li>
        <li class="nav-item"><button class="nav-link mx-1" data-bs-toggle="pill" data-bs-target="#day4">D4</button></li>
        <li class="nav-item"><button class="nav-link mx-1" data-bs-toggle="pill" data-bs-target="#day5">D5</button></li>
        <li class="nav-item"><button class="nav-link mx-1" data-bs-toggle="pill" data-bs-target="#day6">D6</button></li>
        <li class="nav-item"><button class="nav-link mx-1" data-bs-toggle="pill" data-bs-target="#day7">D7</button></li>
    </ul>

    <div class="tab-content" id="dayTabContent">
        
        <div class="tab-pane fade show active" id="day1">
            <div class="card day-card">
                <div class="card-body">
                    <h5 class="fw-bold text-primary">Day 1: 啟程與海雲台首晚</h5>
                    <ul class="list-group list-group-flush">
                        <li class="list-group-item"><strong>18:00</strong> 入境釜山，包車前往飯店</li>
                        <li class="list-group-item">
                            <strong>21:00</strong> 🥩 味贊王鹽烤肉
                            <a href="https://map.naver.com/p/search/맛찬들왕소금구이%20해운대점" target="_blank" class="ms-2 badge btn-naver text-decoration-none">NAVER</a>
                        </li>
                        <li class="list-group-item"><strong>22:30</strong> 海雲台夜景散步 & Ai 超市</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="tab-pane fade" id="day2">
            <div class="card day-card">
                <div class="card-body">
                    <h5 class="fw-bold text-primary">Day 2: 購物與遊艇首航 <span class="vbp-badge">48H VBP 啟動</span></h5>
                    <ul class="list-group list-group-flush">
                        <li class="list-group-item"><strong>11:00</strong> 新世界百貨 Centum City</li>
                        <li class="list-group-item"><strong>15:00</strong> 海理團路咖啡街</li>
                        <li class="list-group-item"><strong>19:30</strong> ⛵ 鑽石遊艇 (Pass 換票)</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="tab-pane fade" id="day3">
            <div class="card day-card">
                <div class="card-body">
                    <h5 class="fw-bold text-primary">Day 3: 海景寺廟與機張螃蟹</h5>
                    <ul class="list-group list-group-flush">
                        <li class="list-group-item"><strong>09:30</strong> 海東龍宮寺</li>
                        <li class="list-group-item"><strong>11:00</strong> Skyline Luge 滑車</li>
                        <li class="list-group-item"><strong>13:00</strong> 🦀 機張市場螃蟹大餐</li>
                        <li class="list-group-item"><strong>18:30</strong> SPA LAND 汗蒸幕</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="tab-pane fade text-center py-5" id="day4">
            <h5 class="text-muted small mb-3">Day 4 - Day 7 詳細資訊請參閱書面行程表</h5>
            <p>包含：松島纜車、慶州包車一日遊、西面/南浦洞購物</p>
        </div>

    </div>

    <div class="mt-5 p-4 bg-light rounded text-center">
        <h6>快速導航工具</h6>
        <div class="d-flex justify-content-center gap-2">
            <a href="https://map.naver.com/" target="_blank" class="btn btn-naver"><i class="bi bi-map"></i> NAVER Map</a>
            <a href="https://www.visitbusanpass.com/" target="_blank" class="btn btn-warning"><i class="bi bi-card-checklist"></i> VBP 官網</a>
        </div>
    </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
<script>
    function convertCurrency(type) {
        const rate = 42.5; // 設定 1 TWD = 42.5 KRW
        const twd = document.getElementById('twdInput');
        const krw = document.getElementById('krwInput');
        
        if (type === 'twd') {
            krw.value = Math.round(twd.value * rate);
        } else {
            twd.value = Math.round(krw.value / rate);
        }
    }
</script>

</body>
</html>
