
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phạm Ngọc Anh Quốc </title>
    <style>
        body {
            background-image:url("https://toanthaydinh.com/wp-content/uploads/2020/04/anh-bia-anime-cap-doi-8.png");  
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #Image {
            margin-top: -100px;
            display:block;
            position: absolute;
            cursor: pointer;
            width:800px;
            height:500%;
            margin-left: -390px;
        }
        #image1{
            margin-top: -100px;
            display:block;
            position: absolute;
            cursor: pointer;
            width:800px;
            height:500%; 
            margin-left: -390px;
        }
        .image-container {
            position: relative;
            display: inline-block;
            font-size: 100px;
        }
        .text{ 
            position: absolute;
            top: 900%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: red;
            font-size: 100px;
            font-weight: bold;
            text-align: center;
        }-s
        img:active {
            transform: scale(0.95);
        }
    </style>
</head>
<body>
    <div class="image-container">
    <!-- <img id="Image" src="https://scontent.fhan3-3.fna.fbcdn.net/v/t1.15752-9/461123461_3749509568648205_9217075488434266898_n.jpg?stp=dst-jpg_s2048x2048&_nc_cat=101&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeF9V5DcNMQM5_ksUqQ5UNv3Oe0V44TFSs457RXjhMVKzvL04QqBPOBwPNYYlZN3flKDjt46EPuMgxH52Th1PrxB&_nc_ohc=NL_bYBXZ2a4Q7kNvgF5fRqc&_nc_ht=scontent.fhan3-3.fna&oh=03_Q7cD1QGs3ahIxH31oDCRZy6OnW4M3hL3EJfClDyAMZzrNo6rTw&oe=6719624C"> -->
    <!-- <img id="image1" src="https://scontent.fhan4-5.fna.fbcdn.net/v/t1.15752-9/461049651_792045732896168_6528922519707795861_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeH5jjGUpaikwmB2ckDIvHr6tRf4VCgJKX-1F_hUKAkpf7nvD8iGzIJDF12UAqO7wI4nFQTA3ijfRVqgTKdLpxe7&_nc_ohc=d_ya_FLCVtIQ7kNvgGv8qKv&_nc_ht=scontent.fhan4-5.fna&oh=03_Q7cD1QFxgLt39IE_SWPbP1ylCSv_W9xfj5VkBKe2uPfR9vX2zg&oe=67198B64"> -->
    <img id="Image"  src="https://scontent.fsgn8-4.fna.fbcdn.net/v/t1.15752-9/459555829_334106726396044_5332927443886719651_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeE-2ov1FupLTGmrRowl2Z1o5jiwAQSM6HXmOLABBIzodeZff15pHO1mKWETjmfvCehChPXE_jDPRX-t9ltX-Gyn&_nc_ohc=yXcc0K27vGYQ7kNvgGubCV9&_nc_ht=scontent.fsgn8-4.fna&_nc_gid=AfHLsCVrLPA7F7atwCg1ra3&oh=03_Q7cD1QEFxU7wCcSLY1HavBUmNg9ohKP1Zqlg4oVFzYhiwG8iog&oe=671A3094" >
    <img id="image1"   src="https://scontent.fsgn8-3.fna.fbcdn.net/v/t1.15752-9/459568071_1745087909365765_5148609453394280955_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeGhrS0FPWDWsKMvfclSkNFqLeNbf3RK6dQt41t_dErp1BWGD1fdfNpqQiITY2cJt-Gqawq2z-B0yiWNpXMxzC4A&_nc_ohc=Cg2UEQjAFRMQ7kNvgG-kR9W&_nc_ht=scontent.fsgn8-3.fna&_nc_gid=AMX_i2h33iKdg3WwrCtbg0s&oh=03_Q7cD1QFuTv2DHCi79bNf1BuAVamWrSQTk7ZpkJ2bgGoOpO9IFQ&oe=671A4BDF" >
    <audio id="clickSound" src="Untitled video - Made with Clipchamp (1).mp4" preload="auto"></audio>
    <div class="text"><span id="dem">0</span></div>
    <button onclick="increment()"></button>
    </div>
<script>  
    const image=document.getElementById("image1","Image");
    const clickSound = document.getElementById("clickSound");   
    image.addEventListener("mousedown", function() {
            clickSound.currentTime = 0;
            clickSound.play(); 
        });
    const clickcountDisplay=document.getElementById("dem");
    let count= 0;
        image.addEventListener("mousedown",function increment (){
            count++;
            clickcountDisplay.textContent=count;
        });
</script>
<script>
        document.getElementById("Image").addEventListener("mouseup", function() {
            var img = document.getElementById("image1");
        if (img.style.display === "none") { 
            img.style.display = "block";
        } else {
            img.style.display = "none";
        }});
        
document.getElementById("image1").addEventListener("mouseup", function() {
            var img = document.getElementById("image1");
        if (img.style.display === "none") { 
            img.style.display = "block";
        } else {
            img.style.display = "none";
        }});
       
 document.getElementById("image1").addEventListener("mousedown", function() {
            var img = document.getElementById("image1");
        if (img.style.display === "block") { 
            img.style.display = "none";
        } else {
            img.style.display = "block";
        }});
</script>
</body>
</html>
