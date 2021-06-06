# css-display-style
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>css display properties</title>
    <style>
        +{

        }
        header{
            /* margin: auto; */
            border: 2px solid red;
            background-color:#f5b3f4;
            /* width: 15%; */
        }
        img{
            width: 34px;
            display: block;
            margin: auto
        }
        h3{
            font-size:medium;
            font-weight: bold;
            text-align: center;
            /* animation: name duration timing-function delay iteration-count direction fill-mode; */
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            margin: 0px;
        }
        .box{
            border: 4px solid mediumaquamarine;
            background-color: thistle;
            margin: 10px;
            /* box-sizing: content-box; */
            border-radius: 14px;
            display:inline-block;
            width: 400px;
            box-sizing: border-box;

        }
        .container{
            margin: auto;
        }
    </style>
</head>
<body>
    <header class="top">
        <img src="image.png" alt="akhil">
        <h3>welcome to akhil page</h3>
    </header>
    <div class="container">
        <div class="box">
            <!-- <p class="heading">Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit, animi? Ut molestias suscipit nihil exercitationem nemo, obcaecati vero ipsa quo odit. Laboriosam, alias minima.</p> -->
                <p class="heading">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corrupti, ipsum dolor. Adipisci totam et provident animi iste voluptas, deleniti natus hic quos voluptatem ipsum. Quos error magni corrupti at laboriosam est totam impedit laborum minus alias dolores vitae cum officia, repellendus sit? Repellat repudiandae quis quaerat officia, quam unde deleniti!</p>

        </div>
        <div class="box">
            <!-- <p class="heading">Lorem  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquam rerum quisquam sed illum error autem animi dignissimos incidunt, delectus aut eaque nisi earum accusamus veniam expedita officia exercitationem placeat necessitatibus id! Vitae, nemo atque? sum dolor sit amet consectetur adipisicing elit. Reprehenderit, animi? Ut molestias suscipit nihil exercitationem nemo, obcaecati vero ipsa quo odit. Laboriosam, alias minima.</p> -->
            <p class="heading">Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus illo eaque, autem quis, sapiente asperiores quisquam, numquam ipsa adipisci corrupti quam voluptatum sed sint voluptates magni est aspernatur fuga expedita incidunt fugit? Similique quis ullam cupiditate alias nihil eos totam dignissimos et dicta officia, maiores quasi eius quae, amet porro!</p>

        </div>
        <div class="box">
            <!-- <p class="heading">Lorem  Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste enim doloribus consequuntur ullam magni corrupti quas nam, beatae deleniti tempore qui dolore consequatur sunt quos dignissimos esse, corporis aut aliquid? ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit, animi? Ut molestias suscipit nihil exercitationem nemo, obcaecati vero ipsa quo odit. Laboriosam, alias minima.</p>    -->
            <p class="heading">Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem aspernatur excepturi harum, praesentium voluptates impedit est quam delectus cupiditate inventore iure et tenetur? Accusantium atque, fugit debitis est adipisci vel sit quas fugiat expedita architecto officia quis quod modi delectus ea repellat dicta sint obcaecati vitae perferendis vero optio exercitationem./p>
        </div>
    </div>
</body>
</html>
