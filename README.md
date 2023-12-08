<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Інформація про нашу групу</title>
    <link rel="stylesheet" href="decor.css"> <!-- Link your external CSS file -->

    <!-- Load Chart.js library from CDN -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>

    <header>
        <div class="header-content">
            <h1>ФЕП-12</h1>
            <p class="header-subtitle">Академічна група</p>
        </div>
    </header>


    <section id="photoSection">
        <h2>Наша Фотогалерея</h2>
        <div class="photo">
            <img src="photo_2023-12-07_20-28-37.jpg">
        </div>
        <div class="photo">
            <img src="photo_2023-12-07_20-28-39.jpg">
        </div>
        
        
    </section>

    <section id="textInfoSection">
            <h2>Трішки про нас</h2>
            <p>
            Ми є групою ФЕП-12, яка навчається в Львівському національному університеті імені Івана Франка. 
            Старостою нашої групи є Назаришина Софія. У нашій команді є люди з майже усіх регіонів країни. Ми позиціонуємо себе як дружню та креативну команду, 
            що готова до навчання та розвитку.
            </p>
        </section>
    <section id="groupMembers">
            <h2>Учасники групи</h2>

            <div class="member">
                <div class="member-photo">
                    <img src="photo_2023-11-26_13-06-58.jpg" alt="Member 1 Photo">
                </div>
                <div>
                    <h3>Юрій Кирчей</h3>
                    <p></p>
                </div>
            </div>

            <div class="member">
                <div class="member-photo">
                    <img src="photo_2023-12-07_23-45-47.jpg">
                </div>
                
                <div>
                    <h3>Назаришина Софія</h3>
                    <p>Староста групи, частина студентського самоврядування. </p>
                </div>
            </div>
            <div class="member">
                <div class="member-photo">
                     <img src="360_F_549983970_bRCkYfk0P6PP5fKbMhZMIb07mCJ6esXL.jpg" alt="Member 1 Photo">
                </div>
               
                <div>
                    <h3>Келба Денис</h3>
                    <p></p>
                </div>
            </div>
            <div class="member">
                <div class="member-photo">
                    <img src="photo_2023-12-07_23-46-45.jpg">
                </div>
                
                <div>
                    <h3>Марчак ЮрійК</h3>
                    <p></p>
                </div>
            </div>
            <div class="member">
                <div class="member-photo">
                     <img src="photo_2023-12-07_23-53-05.jpg" alt="Member 1 Photo">
                </div>
               
                <div>
                    <h3>Тарадайка Дарія</h3>
                    <p></p>
                </div>
            </div>
            <div class="member">
                <div class="member-photo">
                    <img src="photo_2023-12-07_23-57-00.jpg" alt="Member 1 Photo">
                </div>
                
                <div>
                    <h3>Демчук Андрій</h3>
                    <p></p>
                </div>
            </div>
            <div class="member">
                <div class="member-photo">
                     <img src="photo_2023-12-07_23-49-02.jpg" alt="Member 1 Photo">
                </div>
               
                <div>
                    <h3>Тисяк Анастасія</h3>
                    <p></p>
                </div>
            </div>
            <div class="member">
                <div class="member-photo">
                     <img src="photo_2023-12-07_23-50-04.jpg" alt="Member 1 Photo">
                </div>
               
                <div>
                    <h3>Шабленко Аліна</h3>
                    <p></p>
                </div>
            </div>
            <div class="member">
                <div class="member-photo">
                    <img src="360_F_549983970_bRCkYfk0P6PP5fKbMhZMIb07mCJ6esXL.jpg" alt="Member 1 Photo">
                </div>
                
                <div>
                    <h3>Козак Валерій</h3>
                    <p></p>
                </div>
            </div>

            <div class="member">
                <div class="member-photo">
                    <img src="360_F_549983970_bRCkYfk0P6PP5fKbMhZMIb07mCJ6esXL.jpg" alt="Member 1 Photo">
                </div>
                
                <div>
                    <h3>Монець Валерій</h3>
                    <p></p>
                </div>
            </div>
            <div class="member">
                <div class="member-photo">
                    <img src="photo_2023-12-07_23-51-09.jpg" alt="Member 1 Photo">
                </div>
                
                <div>
                    <h3>Демко Вероніка</h3>
                    <p></p>
                </div>
            </div>

        </section>
    <section id="cityChartSection">
        <h2>Звідки ми?</h2>
        <div id="cityChartContainer">
            <canvas id="cityChart"></canvas>
        </div>
    </section>

    

    

    <footer>
        <p class="footer-contact">Контакти: 9999999999</p>
    </footer>

    <!-- Chart.js script -->
    <script>
        var ctx = document.getElementById('cityChart').getContext('2d');
        var cityData = {
            labels: ['Львів', 'Rivne',  'Shepetivka', 'Stryi', 'Sokal'],
            datasets: [{
                label: 'Кількість Людей',
                data: [2, 3, 1, 1, 1],
                backgroundColor: [
                    'rgba(255, 99, 132, 0.2)',
                    'rgba(54, 162, 235, 0.2)',
                    'rgba(75, 192, 192, 0.2)',
                    'rgba(153, 102, 255, 0.2)',
                    'rgba(255, 159, 64, 0.2)'
                ],
                borderColor: [
                    'rgba(255, 99, 132, 1)',
                    'rgba(54, 162, 235, 1)',

                    'rgba(75, 192, 192, 1)',
                    'rgba(153, 102, 255, 1)',
                    'rgba(255, 159, 64, 1)'
                ],
                borderWidth: 1
            }]
        };
        var myChart = new Chart(ctx, {
            type: 'bar',
            data: cityData,
            options: {
                scales: {
                    y: {
                        beginAtZero: true
                    }
                }
            }
        });
    </script>

</body>
</html>
