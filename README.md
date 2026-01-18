<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Правила покупки голды</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            color: #333;
            line-height: 1.6;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }

        header {
            background: linear-gradient(135deg, #2c3e50, #4a6491);
            color: white;
            padding: 30px 20px;
            text-align: center;
        }

        h1 {
            font-size: 2.2em;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.1em;
            opacity: 0.9;
        }

        .content {
            padding: 30px;
        }

        .warning {
            background: #fff3cd;
            border-left: 5px solid #ffc107;
            padding: 20px;
            margin-bottom: 25px;
            border-radius: 5px;
        }

        h2 {
            color: #2c3e50;
            margin: 25px 0 15px 0;
            padding-bottom: 10px;
            border-bottom: 2px solid #eee;
        }

        h2:first-child {
            margin-top: 0;
        }

        .rules-list {
            list-style: none;
            counter-reset: rule-counter;
        }

        .rules-list li {
            counter-increment: rule-counter;
            margin-bottom: 20px;
            padding-left: 30px;
            position: relative;
        }

        .rules-list li:before {
            content: counter(rule-counter);
            background: linear-gradient(135deg, #2c3e50, #4a6491);
            color: white;
            width: 24px;
            height: 24px;
            border-radius: 50%;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-size: 0.8em;
            font-weight: bold;
            position: absolute;
            left: 0;
            top: 2px;
        }

        .important-note {
            background: #d4edda;
            border-left: 5px solid #28a745;
            padding: 20px;
            margin-top: 25px;
            border-radius: 5px;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #f8f9fa;
            color: #6c757d;
            font-size: 0.9em;
        }

        @media (max-width: 600px) {
            .container {
                border-radius: 10px;
            }
            
            h1 {
                font-size: 1.8em;
            }
            
            .content {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Правила покупки игровой валюты</h1>
            <div class="subtitle">Внимательно ознакомьтесь перед совершением заказа</div>
        </header>
            
            <h2>1. Общие положения</h2>
            <ul class="rules-list">
                <li>Настоящие правила регулируют отношения между Продавцом и Покупателем при приобретении игровой валюты.</li>
                <li>Совершая покупку, Вы подтверждаете, что ознакомились с данными правилами и полностью согласны со всеми их пунктами.</li>
                <li>Все услуги оказываются в виртуальной форме, и материальный товар не передается.</li>
            </ul>
            
            <h2>2. Порядок оформления заказа</h2>
            <ul class="rules-list">
                <li>Для совершения покупки Вы должны предоставить точные реквизиты для передачи валюты (никнейм, сервер, название игры и т.д.).</li>
                <li>Вы несете полную ответственность за достоверность предоставленных данных. Я не несу ответственности за доставку голды на неправильно указанные реквизиты.</li>
                <li>После подтверждения заказа и его оплаты отмена заказа невозможна.</li>
            </ul>
            
            <h2>3. Оплата</h2>
            <ul class="rules-list">
                <li>Цены указаны на момент заказа. Я оставляю за собой право изменять цены.</li>
                <li>Оплата производится строго в соответствии с выбранным методом (например, банковская карта, электронные деньги и т.д.).</li>
                <li>Момент оплаты считается по времени поступления средств на мой счет.</li>
            </ul>
            
            <h2>4. Процесс и сроки доставки</h2>
            <ul class="rules-list">
                <li>Срок доставки голды указывается для каждого заказа индивидуально и является ориентировочным.</li>
                <li>Я не несу ответственности за задержки, связанные с работой игровых серверов, техническими неполадками у провайдера или действиями администрации игры.</li>
                <li>После завершения передачи голды я предоставляю доказательства выполнения заказа (скриншот, видео). Этим подтверждается полное исполнение моих обязательств.</li>
            </ul>
            
            <h2>5. Гарантии и ответственность сторон</h2>
            <ul class="rules-list">
                <li>Я гарантирую, что передаваемая валюта получена легальными, с точки зрения правил игры, методами (фарм, перепродажа на аукционе и т.д.). Однако, окончательное решение о легальности любых операций остается за администрацией игры.</li>
                <li>Вы понимаете и соглашаетесь, что покупка игровой валюты у третьих лиц может противоречить Пользовательскому соглашению (EULA) вашей игры.</li>
                <li>Я не несу ответственности за любые санкции (бан, блокировка, обнуление рейтинга и т.д.), applied к Вашему игровому аккаунту со стороны администрации игры. Весь риск подобных действий Вы принимаете на себя.</li>
                <li>Возврат средств осуществляется только в случае, если я по своей вине не выполнил условия заказа.</li>
            </ul>
            
            <h2>6. Политика конфиденциальности</h2>
            <ul class="rules-list">
                <li>Я обязуюсь не передавать ваши личные данные (никнейм, прочие реквизиты) третьим лицам.</li>
                <li>Данные, необходимые для платежа (email, номер телефона), используются исключительно для выполнения текущего заказа.</li>
            </ul>
            
            <h2>7. Разрешение споров</h2>
            <ul class="rules-list">
                <li>Все спорные ситуации решаются путем переговоров.</li>
                <li>Претензии по заказу принимаются в течение 24 часов с момента его выполнения, при предоставлении Вами доказательств невыполнения условий.</li>
                <li>При невозможности договориться, спор может быть передан на рассмотрение в суд по месту моей регистрации (если применимо).</li>
            </ul>
            
            <div class="important-note">
                СОВЕРШАЯ ПОКУПКУ, ВЫ ПОДТВЕРЖДАЕТЕ, ЧТО ОЗНАКОМЛЕНЫ С ПРАВИЛАМИ И ПРИНИМАЕТЕ ВСЮ ОТВЕТСТВЕННОСТЬ ЗА ВОЗМОЖНЫЕ ПОСЛЕДСТВИЯ, СВЯЗАННЫЕ С НАРУШЕНИЕМ ПОЛЬЗОВАТЕЛЬСКОГО СОГЛАШЕНИЯ ВАШЕЙ ИГРЫ.
            </div>
        </div>
        
        <footer>
            <p>© 2026 Правила покупки игровой валюты. Все права защищены.</p>
        </footer>
    </div>
</body>
</html>
