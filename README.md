<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Біографія Олі</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #1f1c2c, #928dab);
            color: rgb(255, 255, 255);
        }

        .card {
            max-width: 700px;
            margin: 80px auto;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 0 20px rgba(0,0,0,0.6);
            text-align: center;
        }

        h1 {
            margin-bottom: 5px;
        }

        .info {
            margin: 10px 0;
            font-size: 16px;
        }

        .section {
            margin-top: 25px;
            text-align: left;
        }

        .section h2 {
            border-bottom: 2px solid #a78bfa;
            padding-bottom: 5px;
        }

        ul {
            padding-left: 20px;
        }

        .highlight {
            color: #a78bfa;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="card">

    <h1>Гордієнко Оля</h1>

    <div class="info"> Вік: <span class="highlight">19 років</span></div>
    <div class="info"> Спеціальність: <span class="highlight">Комп'ютерний інженер</span></div>

    <div class="section">
        <h2>Про мене</h2>
        <p>
            Я студентка, яка навчається у Новобузькому коледжі на комп'ютерного інженера.
            Люблю займатись саморозвитком, але також маю творчу сторону —
            займаюся театром і навіть працюю там.
        </p>
    </div>

    <div class="section">
        <h2>Мої інтереси</h2>
        <ul>
            <li> Театр і акторська гра</li>
            <li> Програмування</li>
            <li> Творчість та саморозвиток</li>
        </ul>
    </div>

    <div class="section">
        <h2>Мета</h2>
        <p>
            Хочу стати професіоналом у сфері творчості,
            розвиватися та досягати нових висот.
        </p>
    </div>

</div>

<!-- 🔥 Firebase SDK -->
<script src="https://www.gstatic.com/firebasejs/10.12.0/firebase-app-compat.js"></script>
<script src="https://www.gstatic.com/firebasejs/10.12.0/firebase-analytics-compat.js"></script>

<script>
const firebaseConfig = {
  apiKey: "AIzaSyBldxGXI-fVCL74BN-IcNz-FjRKpEf__Ls",
  authDomain: "olia-site.firebaseapp.com",
  projectId: "olia-site",
  storageBucket: "olia-site.firebasestorage.app",
  messagingSenderId: "929616368595",
  appId: "1:929616368595:web:7885809d8e5fbfb6a41526",
  measurementId: "G-HD5NKRQ33J"
};

// Ініціалізація Firebase
firebase.initializeApp(firebaseConfig);

// Аналітика
firebase.analytics();
</script>

</body>
</html>
