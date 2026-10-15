
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Vietnamese Women's Day ❤️</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    min-height: 100vh;
    font-family: "Segoe UI", Arial, sans-serif;
    background: linear-gradient(135deg, #fff0f5, #ffe0eb, #fff5f7);
    color: #813750;
}

.floating-hearts {
    position: fixed;
    inset: 0;
    overflow: hidden;
    pointer-events: none;
    z-index: 0;
}

.floating-hearts span {
    position: absolute;
    bottom: -50px;
    color: #f47ca5;
    opacity: 0;
    animation: floatUp linear infinite;
}

@keyframes floatUp {
    0% {
        transform: translateY(0) rotate(0deg);
        opacity: 0;
    }
    15% {
        opacity: 0.65;
    }
    85% {
        opacity: 0.5;
    }
    100% {
        transform: translateY(-115vh) rotate(35deg);
        opacity: 0;
    }
}

.main {
    position: relative;
    z-index: 1;
    min-height: 100vh;
    max-width: 1300px;
    margin: auto;
    padding: 45px;
    display: grid;
    grid-template-columns: 1.05fr 0.95fr;
    align-items: center;
    gap: 35px;
}

/* Khung lời chúc */
.message-card {
    padding: 36px;
    background: rgba(255, 255, 255, 0.76);
    border: 1px solid rgba(255, 170, 195, 0.6);
    border-radius: 28px;
    box-shadow: 0 15px 45px rgba(205, 91, 132, 0.13);
    animation: appear 1.2s ease both;
}

@keyframes appear {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.eyebrow {
    color: #e45487;
    font-weight: bold;
    letter-spacing: 2px;
    font-size: 13px;
    text-transform: uppercase;
}

h1 {
    margin: 14px 0 22px;
    color: #d93670;
    font-family: Georgia, "Times New Roman", serif;
    font-size: clamp(30px, 3.3vw, 43px);
    line-height: 1.3;
}

.message {
    font-size: 17px;
    line-height: 1.9;
    color: #76364e;
}

.message strong {
    color: #d52e68;
}

.ending {
    margin-top: 22px;
    text-align: center;
    font-family: Georgia, serif;
    font-size: 25px;
    font-weight: bold;
    color: #d52e68;
}

.kisses {
    text-align: center;
    font-size: 27px;
    margin-top: 14px;
}

/* Trái tim ghép từ hai nửa ảnh */
.heart-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    animation: heartAppear 1.5s ease both;
}

@keyframes heartAppear {
    from {
        opacity: 0;
        transform: scale(0.8);
    }
    to {
        opacity: 1;
        transform: scale(1);
    }
}

.heart-photo {
    width: 100%;
    max-width: 490px;
    overflow: visible;
    filter: drop-shadow(0 15px 18px rgba(203, 58, 107, 0.23));
    animation: heartbeat 2s ease-in-out infinite;
}

@keyframes heartbeat {
    0%, 100% { transform: scale(1); }
    12% { transform: scale(1.035); }
    24% { transform: scale(1); }
    36% { transform: scale(1.02); }
}

.name-labels {
    width: 85%;
    max-width: 420px;
    display: flex;
    justify-content: space-around;
    margin-top: 8px;
    color: #cf3c72;
    font-size: 17px;
    font-weight: bold;
}

.heart-caption {
    margin-top: 19px;
    font-family: Georgia, serif;
    color: #d64b7b;
    font-size: 19px;
    font-style: italic;
    text-align: center;
}

/* Điều chỉnh cho điện thoại */
@media (max-width: 800px) {
    .main {
        grid-template-columns: 1fr;
        padding: 22px 15px 35px;
        gap: 35px;
    }

    .message-card {
        padding: 25px 22px;
    }

    h1 {
        font-size: 32px;
    }

    .message {
        font-size: 16px;
    }

    .heart-photo {
        max-width: 390px;
    }
}
</style>
</head>

<body>

<!-- Những trái tim nhỏ bay xung quanh -->
<div class="floating-hearts" id="floatingHearts"></div>

<main class="main">

    <!-- BÊN TRÁI: LỜI CHÚC -->
    <section class="message-card">

        <div class="eyebrow">💌 A little letter from your love</div>

        <h1>Happy VietNamese Women's 🌸</h1>

        <div class="message">
            Chúc bé Tình yêu dấu của anh có một ngày phụ nữ Việt Nam
            thật là trọn vẹn, đầy ý nghĩa, thật là nhiều niềm vui. ❤️

            <br><br>

            Dù anh ở xa, không thể ở cạnh em trong ngày tuyệt vời này,
            thật sự là một điều thiệt thòi cho em. Nhưng anh mong rằng
            hai trái tim ta luôn luôn gần nhau và hướng đến nhau,
            luôn luôn hạnh phúc, luôn luôn yêu thương nhau. 💗

            <br><br>

            Vượt qua giai đoạn khó khăn xa cách này, anh chắc chắn rằng
            chúng ta sẽ có một cái kết đẹp, <strong>Happy Ending</strong> nhaa. 🥹

            <br><br>

            <strong>
                Anh yêu bé Tình của anh nhiều lắmm! ❤️
            </strong>
        </div>

        <div class="ending">Happy Ending 💞</div>

        <div class="kisses">😘 💋 💗 🥰 💋 😘</div>
    </section>


    <!-- BÊN PHẢI: TRÁI TIM GỒM HAI NỬA ẢNH -->
    <section class="heart-section">

        <svg class="heart-photo"
             viewBox="0 0 400 360"
             xmlns="http://www.w3.org/2000/svg"
             role="img"
             aria-label="Hai nửa trái tim ghép thành một trái tim">

            <defs>
                <!-- Nửa trái tim bên trái -->
                <clipPath id="leftHalf">
                    <path d="
                        M200 330
                        C160 290 35 220 35 120
                        C35 55 90 20 135 20
                        C165 20 190 42 200 72
                        Z"/>
                </clipPath>

                <!-- Nửa trái tim bên phải -->
                <clipPath id="rightHalf">
                    <path d="
                        M200 330
                        C240 290 365 220 365 120
                        C365 55 310 20 265 20
                        C235 20 210 42 200 72
                        Z"/>
                </clipPath>
            </defs>

            <!-- Màu nền nếu chưa thêm ảnh -->
            <path d="
                M200 330
                C160 290 35 220 35 120
                C35 55 90 20 135 20
                C165 20 190 42 200 72
                C210 42 235 20 265 20
                C310 20 365 55 365 120
                C365 220 240 290 200 330 Z"
                fill="#ff9dbd"/>

            <!-- Ảnh của anh: anh.jpg -->
            <image href="anh.jpg"
                   x="0" y="0"
                   width="200" height="360"
                   preserveAspectRatio="xMidYMid slice"
                   clip-path="url(#leftHalf)"/>

            <!-- Ảnh của bé: em.jpg -->
            <image href="em.jpg"
                   x="200" y="0"
                   width="200" height="360"
                   preserveAspectRatio="xMidYMid slice"
                   clip-path="url(#rightHalf)"/>

            <!-- Viền trái tim -->
            <path d="
                M200 330
                C160 290 35 220 35 120
                C35 55 90 20 135 20
                C165 20 190 42 200 72
                C210 42 235 20 265 20
                C310 20 365 55 365 120
                C365 220 240 290 200 330 Z"
                fill="none"
                stroke="#fff9fb"
                stroke-width="6"
                stroke-linejoin="round"/>

            <!-- Đường ghép hai nửa -->
            <path d="M200 72 L200 330"
                  fill="none"
                  stroke="#fff9fb"
                  stroke-width="3"
                  stroke-dasharray="5 5"/>
        </svg>

        <div class="name-labels">
            <span>❤️ ANH ❤️</span>
            <span>❤️ BÉ ❤️</span>
        </div>

        <div class="heart-caption">
            Hai trái tim, một tình yêu 💕
        </div>

    </section>

</main>

<script>
// Tạo các trái tim nhỏ bay lên liên tục
const heartContainer = document.getElementById("floatingHearts");
const symbols = ["♡", "♥", "💕", "💗", "💖"];

function createFloatingHeart() {
    const heart = document.createElement("span");

    heart.textContent =
        symbols[Math.floor(Math.random() * symbols.length)];

    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (12 + Math.random() * 20) + "px";
    heart.style.animationDuration = (7 + Math.random() * 9) + "s";
    heart.style.animationDelay = (Math.random() * 2) + "s";

    heartContainer.appendChild(heart);

    heart.addEventListener("animationend", () => heart.remove());
}

for (let i = 0; i < 24; i++) {
    createFloatingHeart();
}

setInterval(createFloatingHeart, 550);
</script>

</body>
</html>
