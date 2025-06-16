<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>AACeylon</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Updated favicon with fallback -->
    <link rel="icon" href="https://verifyidp.aaceylon.com/images/AAC Logo.jpg" type="image/jpeg">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">

    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@700&family=Poppins:wght@400&display=swap"
        rel="stylesheet">

    <style>
        .body-dark {
            background-color: #0f1112;
            color: #ffffff;
            font-family: 'Poppins', sans-serif;
        }

        .body-light {
            background-color: #ffffff;
            color: #000000;
            font-family: 'Poppins', sans-serif;
        }

        header {
            background-color: #1c1e20;
            border-bottom: 3px solid #f4c103;
        }

        .header-title {
            font-family: 'Merriweather', serif;
        }

        .logo {
            max-height: 65px;
            object-fit: contain;
        }

        /* Fallback logo style if images don't load */
        .logo-fallback {
            width: 100px;
            height: 65px;
            background-color: #f8f9fa;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #495057;
            font-weight: bold;
            border: 1px solid #dee2e6;
        }

        .card {
            background-color: #1e1f20;
            border: 1px solid #2c2f33;
            border-radius: 12px;
        }

        .card-header {
            background-color: #f4c103;
            color: #000;
        }

        .card-body {
            font-size: 16px;
            color: #ffffff;
        }

        .fw-semibold {
            color: #f4c103;
        }

        footer {
            background-color: #000;
            color: #f4c103;
        }

        footer a {
            color: #f4c103;
        }

        footer a:hover {
            text-decoration: underline;
        }

        h3 {
            margin-top: 30px;
        }

        table th,
        table td {
            vertical-align: middle !important;
        }

        .custom-alert-blocked {
            background-color: #431a24;
            border-radius: 10px;
            max-width: 500px;
            margin: 20px auto;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
        }

        .custom-alert-blocked .icon i {
            color: #8c7be4;
        }

        .custom-alert-blocked .text-light-emphasis {
            color: #ffffff;
            font-size: 16px;
        }

        .custom-alert-blocked .text-muted {
            color: #f2f2f2;
            font-size: 14px;
        }

        .hover-bg-red:hover {
            background-color: #dc3545 !important;
            color: white !important;
        }

        .hover-bg-blue:hover {
            background-color: #0069d9 !important;
            color: white !important;
        }
    </style>
</head>

<body class="body-dark d-flex flex-column min-vh-100">

    <!-- Light Topbar with Logout -->
    <div class="bg-dark py-1">
        <div class="container-fluid px-3 d-flex justify-content-between align-items-center">
        </div>
    </div>

    <!-- Main Dark Header -->
    <header>
        <div class="container py-2">
            <div class="d-flex align-items-center justify-content-between">
                <!-- AAC Logo with fallback -->
                <div class="logo-container">
                    <img src="https://verifyidp.aaceylon.com/images/AAC Logo.jpg" 
                         alt="AAC logo" 
                         class="logo"
                         onerror="this.onerror=null; this.style.display='none'; document.getElementById('aac-fallback').style.display='block';">
                    <div id="aac-fallback" class="logo-fallback" style="display: none;">AAC Logo</div>
                </div>

                <div class="text-center d-none d-md-block">
                    <h5 class="m-0 fw-bold header-title text-white">Republic of Sri Lanka (CEYLON)</h5>
                    <p class="m-0 text-light">International Motor Traffic</p>
                    <p class="m-0 text-light">International Driving Permit</p>
                    <p class="m-0 text-secondary" style="font-size: 12px;">Convention On Road Traffic of 19 September
                        1949</p>
                </div>

                <div class="text-center d-block d-md-none">
                    <h6 class="m-0 fw-bold text-white" style="font-size:small;">Automobile Association of Ceylon</h6>
                    <p style="font-size: 10px" class="m-0 text-light">International Motor Traffic</p>
                    <p style="font-size: 10px" class="m-0 text-light">International Driving Permit</p>
                    <p class="m-0 text-secondary" style="font-size: 9px;">Convention On Road Traffic of <br>19 September
                        1949</p>
                </div>

                <!-- FIA Logo with fallback -->
                <div class="logo-container">
                    <img src="https://verifyidp.aaceylon.com/images/FIA Logo.jpg" 
                         alt="FIA logo" 
                         class="logo"
                         onerror="this.onerror=null; this.style.display='none'; document.getElementById('fia-fallback').style.display='block';">
                    <div id="fia-fallback" class="logo-fallback" style="display: none;">FIA Logo</div>
                </div>
            </div>
        </div>
    </header>

    <main class="container my-5">
        <div class="card shadow mx-auto" style="max-width: 900px;">
            <div class="card-header text-center">
                <h4 class="fw-bold mb-0">Permit Holder Information</h4>
            </div>

            <div class="card-body">
                <div class="row mb-3">
                    <div class="col-md-5 fw-semibold">Surname</div>
                    <div class="col-md-7">HEELLA PATHIRANAGE</div>
                </div>
                <div class="row mb-3">
                    <div class="col-md-5 fw-semibold">Other Names</div>
                    <div class="col-md-7">DEEPTHI MANGALA</div>
                </div>
                <div class="row mb-3">
                    <div class="col-md-5 fw-semibold">Date of Birth</div>
                    <div class="col-md-7">1992-10-29</div>
                </div>
                <div class="row mb-3">
                    <div class="col-md-5 fw-semibold">Sri Lankan Driving License Number</div>
                    <div class="col-md-7">B1982184</div>
                </div>
                <div class="row mb-3">
                    <div class="col-md-5 fw-semibold">International Driving Permit Number</div>
                    <div class="col-md-7">451203</div>
                </div>
                <div class="row mb-3">
                    <div class="col-md-5 fw-semibold">Issued Date</div>
                    <div class="col-md-7">2025-05-26</div>
                </div>
                <div class="row mb-3">
                    <div class="col-md-5 fw-semibold">Expiry Date</div>
                    <div class="col-md-7">2026-05-26</div>
                </div>
                <div class="row">
                    <div class="col-md-5 fw-semibold">Vehicles for which the permit is valid</div>
                    <div class="col-md-7">A, B</div>
                </div>
            </div>
        </div>
    </main>

    <footer class="py-4 mt-auto" style="background-color: #000;">
        <div class="container">
            <div class="row text-center text-md-start">
                <!-- Left Column -->
                <div class="col-md-6 mb-3 mb-md-0">
                    <h6 class="fw-bold">Issued At</h6>
                    <p class="mb-1">The Automobile Association of Ceylon</p>
                    <p class="mb-0">
                        40, Sir Mohamed Macan Marker Mawatha, Colombo 03,<br> Sri Lanka.
                    </p>
                </div>

                <!-- Middle Column: Contact -->
                <div class="col-md-3 mb-3 mb-md-0">
                    <h6 class="fw-bold">Contact</h6>
                    <ul class="list-unstyled mb-0">
                        <li><i class="bi bi-telephone-fill me-2"></i>+94 2446 074 / +94 2421 528-9</li>
                        <li><i class="bi bi-printer-fill me-2"></i>+94 2446074</li>
                    </ul>
                </div>

                <!-- Right Column: Links -->
                <div class="col-md-3">
                    <h6 class="fw-bold">Connect</h6>
                    <ul class="list-unstyled mb-0">
                        <li>
                            <i class="bi bi-globe me-2"></i>
                            <a href="https://www.aaceylon.lk" target="_blank"
                                class="text-warning text-decoration-none">www.aaceylon.lk</a>
                        </li>
                        <li>
                            <i class="bi bi-envelope-fill me-2"></i>
                            <a href="mailto:aacmotor@sltnet.lk"
                                class="text-warning text-decoration-none">aacmotor@sltnet.lk</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</body>

</html>
