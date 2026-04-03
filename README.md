# ALTYN-BULAK
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Меню</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #f5f5f5;
    }

    .menu {
        max-width: 600px;
        margin: 50px auto;
        background: #fff;
        border-radius: 15px;
        box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        overflow: hidden;
    }

    .menu-header {
        background: #222;
        color: #fff;
        padding: 20px;
        text-align: center;
        font-size: 24px;
        letter-spacing: 2px;
    }

    .menu-section {
        padding: 20px;
    }

    .menu-item {
        display: flex;
        justify-content: space-between;
        margin-bottom: 15px;
        border-bottom: 1px solid #eee;
        padding-bottom: 10px;
    }

    .menu-item:last-child {
        border-bottom: none;
    }

    .item-name {
        font-weight: bold;
    }

    .item-desc {
        font-size: 13px;
        color: #777;
    }

    .item-price {
        font-weight: bold;
        color: #222;
    }
</style>
</head>
<body>

<div class="menu">
    <div class="menu-header">MENU</div>

    <div class="menu-section">
        <div class="menu-item">
            <div>
                <div class="item-name">Бургер</div>
                <div class="item-desc">Говядина, сыр, соус</div>
            </div>
            <div class="item-price">2500 ₸</div>
        </div>

        <div class="menu-item">
            <div>
                <div class="item-name">Пицца</div>
                <div class="item-desc">Сыр, томаты, базилик</div>
            </div>
            <div class="item-price">3500 ₸</div>
        </div>

        <div class="menu-item">
            <div>
                <div class="item-name">Кола</div>
                <div class="item-desc">0.5л</div>
            </div>
            <div class="item-price">800 ₸</div>
        </div>
    </div>
</div>

</body>
</html>
