<html>
    <head>
        <script type="text/javascript">
            window.addEventListener("resize", AutoScale); //Масштабируем страницу при растягивании окна
            AutoScale(); //Масштабируем страницу после загрузки
            function AutoScale()
            {
	            let width = window.innerWidth; //Ширина окна
                //Если Вы хотите проверять по размеру экрана, то Вам нужно свойство window.screen.width

	            if(width > 1280)
	            {
		            ChangeScale("big");
	            }
	            else if(width <= 1280 && width > 720)
	            {
		            ChangeScale("normal");
	            }
	            else if(width < 720)
	            {
		            ChangeScale("small");
	            }
            }
        </script>
        <link rel="stylesheet" href="style.css"/>
        <link rel="stylesheet" type="text/css" href="styles/<?php echo $_SESSION["scale"]; ?>.css" id="scale-link">
        <title>Holiday</title>
    </head>
    <body>
        <div class="wrapper">
            <header>
                <h1>Сезонное предложение</h1>
                <p>С 5 декабря по 5 марта действует предложение: скидка на всю продукцию 40%.</p>
                <p><i>Спешите купить праздник выгодно!</i></p>
                
            </header>
            <nav style="border:3px ridge DeepSkyBlue">
                <a href="#Product"><b>Продукция</b></a>
                <a href="#Product"><b>Как купить?</b></a>
                <a href="#Product"><b>Оптом</b></a>
                <a href="#Product"><b>О компаниии</b></a>
            </nav>
            <main>
                <p class="n1">
                    <a href="#Product"><img class="icon" src="https://pngimg.com/uploads/confetti/confetti_PNG86985.png"><br><b>Хлопушки</b></a>
                </p>
                <p class="n1">
                    <a href="#Product"><b><img class="icon" src="https://w7.pngwing.com/pngs/996/29/png-transparent-firecrackers-firecrackers-firecracker-explosion-firecrackers-thumbnail.png"><br >Петарды</b></a>
                </p>
                <p class="n1" >
                    <a href="#Product"><img class="icon" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRiiBQ-QhmXH-hxKF1AW-Za0uNXepCKhFuf6A&usqp=CAU"><br><b>Фонтаны</b></a>
                </p>
                <p class="n1">    
                    <a href="#Product"><img class="icon" src="https://images.prom.ua/2948519064_w640_h640_minomet-artillery-shells.jpg"><br><b>Фестивальные шары</b></a>
                </p>
            </main>
            <footer>
                <p style="border:3px ridge DeepSkyBlue"> Наши конакты: +380445613429; Киев, ул. Болгарская 131/44.<a target="_blank" href="https://www.facebook.com/profile.php?id=100001967735519"><img title="Мы в FaceBook" alt="Мы в FaceBook" src="http://drive.google.com/uc?export=view&id=1GC4AE-6LZ68cDBx0zkobP6Kl_Pnij8IT"></a>
<a target="_blank" href="https://www.youtube.com/channel/UCcD6GklUtwkpAa05P0ietPA"><img title="Мы в YouTube" alt="Мы в YouTube" src="http://drive.google.com/uc?export=view&id=1pJ4oN5SB5CEf73YOV8HhNP2JhJStf8Xw"></a>
<a target="_blank" href="https://www.instagram.com/veronika.dinosaurs/"><img title="Мы в Instagram" alt="Мы в Instagram" src="http://drive.google.com/uc?export=view&id=13kjx75UbL8IrxerUFdPPZOiP2KsVdXZA"></a></p>
            </footer>
        </div>
    </body>
</html>
