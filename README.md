<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday, Komal! ❤️</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');

        body {
            font-family: 'Pacifico', cursive;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #fce4ec, #e8f5e9);
            margin: 0;
            overflow: hidden;
            text-align: center;
        }

        .container {
            position: relative;
            background: rgba(255, 255, 255, 0.8);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px);
            animation: fadeIn 2s ease-in-out;
            max-width: 90%;
            transition: all 0.5s ease-in-out;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .slide {
            display: none;
            flex-direction: column;
            align-items: center;
            opacity: 0;
            transition: opacity 1s ease-in-out;
            min-height: 400px;
            justify-content: center;
        }

        .slide.active {
            display: flex;
            opacity: 1;
        }

        .message {
            font-size: 1.5em;
            color: #4a148c;
            margin-top: 20px;
            padding: 0 20px;
        }
        
        .initial-message {
            font-size: 2em;
            color: #d81b60;
            margin-bottom: 20px;
        }
        
        .image-container {
            width: 250px;
            height: 250px;
            border-radius: 15px;
            overflow: hidden;
            margin-bottom: 20px;
            border: 5px solid #fff;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            animation: imageFadeIn 1s ease-in-out;
        }

        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .next-button {
            background: linear-gradient(45deg, #ff4081, #e040fb);
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 50px;
            font-size: 1.2em;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            margin-top: 20px;
        }

        .next-button:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
        }
        
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: scale(0.9);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }
        @keyframes imageFadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>

    <audio id="bg-music" src="komal_song.mp3" autoplay loop></audio>

    <div class="container">
        <div id="slide-0" class="slide active">
            <h1 class="initial-message">Loading something special...</h1>
            <p class="message">Just for you, Komal ❤️</p>
        </div>
        
        <div id="slide-1" class="slide">
            <h1 class="initial-message">For My Cutiepie 😍</h1>
            <p class="message">Your smile is more addictive than chai! I just want to sit here and watch you all day. Happy Birthday, Meri Jaan! 💖</p>
        </div>

        <div id="slide-2" class="slide">
            <div class="image-container">
                <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAYEBQYFBAYGBQYHBwYIChAKCgkJChQODwwQFxQYGBcUFhYaHSUfGhsjHBYWICwgIyYnKSopGR8tMC0oMCUoKSj/2wBDAQcHBwoIChMKChMoGhYaKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCj/wAARCAH6A9cDASIAAhEBAxEB/8QAHAAAAgIDAQEAAAAAAAAAAAAAAwQFBgECBwAI/8QAUxAAAQQBAwIDBAcFBQYEBQIEBwAAAQIDBAUGEQcSITFBURMVImFxgZEyQrEjJHKCtfAUI0OSwdHh8TRTYnLCNFSDstLiGFSCsxYmZHOj/8QAGwEAAgMBAQEAAAAAAAAAAAAAAQIAAwQFBgcI/8QAMBEBAAICAQMDAwMDAwUBAAAAAAECAxEEITESBSJBUYEUMgYUM3EjQlGhscHR8PH/2gAMAwAAhEDEQA/APx1rX4W9WtbWtA83Wta1rWga1rWta1rQNa1rWta0DX//2Q==" alt="Komal's Photo 1">
            </div>
            <p class="message">Tum chai jaisi mohobbat toh karo, mai Biscuit jaisa doob naa jau toh kehna..😊💖</p>
        </div>

        <div id="slide-3" class="slide">
            <div class="image-container">
                <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAYEBQYFBAYGBQYHBwYIChAKCgkJChQODwwQFxQYGBcUFhYaHSUfGhsjHBYWICwgIyYnKSopGR8tMC0oMCUoKSj/2wBDAQcHBwoIChMKChMoGhYaKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCj/wAARCAH6A9cDASIAAhEBAxEB/8QAHAAAAgIDAQEAAAAAAAAAAAAAAwQFBgECBwAI/8QAUxAAAQQBAwIDBAcFBQYEBQIEBwAAAQIDBAUGEQcSITFBURMVImFxgZEyQrEjJHKCtfAUI0OSwdHh8TRTYnLCNFSDstLiGFSCsxYmZHOj/8QAGwEAAgMBAQEAAAAAAAAAAAAAAQIAAwQFBgcI/8QAMBEBAAICAQMDAwMDAwUBAAAAAAECAxEEITESBSJBUYEUMgYUM3EjQlGhscHR8PH/2gAMAwAAhEDEQA/APx1rX4W9WtbWtA83Wta1rWga1rWta1rQNa1rWta0DX//2Q==" alt="Komal's Photo 2">
            </div>
            <p class="message">Are you jinn? Because jinn ne mera dil lutiya ooho!!😋</p>
        </div>

        <div id="slide-4" class="slide">
            <div class="image-container">
                <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAYEBQYFBAYGBQYHBwYIChAKCgkJChQODwwQFxQYGBcUFhYaHSUfGhsjHBYWICwgIyYnKSopGR8tMC0oMCUoKSj/2wBDAQcHBwoIChMKChMoGhYaKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCj/wAARCAH6A9cDASIAAhEBAxEB/8QAHAAAAgIDAQEAAAAAAAAAAAAAAwQFBgECBwAI/8QAUxAAAQQBAwIDBAcFBQYEBQIEBwAAAQIDBAUGEQcSITFBURMVImFxgZEyQrEjJHKCtfAUI0OSwdHh8TRTYnLCNFSDstLiGFSCsxYmZHOj/8QAGwEAAgMBAQEAAAAAAAAAAAAAAQIAAwQFBgcI/8QAMBEBAAICAQMDAwMDAwUBAAAAAAECAxEEITESBSJBUYEUMgYUM3EjQlGhscHR8PH/2gAMAwAAhEDEQA/APx1rX4W9WtbWtA83Wta1rWga1rWta1rQNa1rWta0DX//2Q==" alt="Komal's Photo 3">
            </div>
            <p class="message">Itna jaadu Harry Potter ki 7 kitaabon mein nahi, jitna apki 2 aankhon mein hai.✨💖</p>
        </div>
        
        <div id="slide-5" class="slide">
            <div class="image-container">
                <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAYEBQYFBAYGBQYHBwYIChAKCgkJChQODwwQFxQYGBcUFhYaHSUfGhsjHBYWICwgIyYnKSopGR8tMC0oMCUoKSj/2wBDAQcHBwoIChMKChMoGhYaKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCj/wAARCAH6A9cDASIAAhEBAxEB/8QAHAAAAgIDAQEAAAAAAAAAAAAAAwQFBgECBwAI/8QAUxAAAQQBAwIDBAcFBQYEBQIEBwAAAQIDBAUGEQcSITFBURMVImFxgZEyQrEjJHKCtfAUI0OSwdHh8TRTYnLCNFSDstLiGFSCsxYmZHOj/8QAGwEAAgMBAQEAAAAAAAAAAAAAAQIAAwQFBgcI/8QAMBEBAAICAQMDAwMDAwUBAAAAAAECAxEEITESBSJBUYEUMgYUM3EjQlGhscHR8PH/2gAMAwAAhEDEQA/APx1rX4W9WtbWtA83Wta1rWga1rWta1rQNa1rWta0DX//2Q==" alt="Komal's Photo 4">
            </div>
            <p class="message">Don't ask me kya haal hai, Ofcourse aapka hi khayal hai. 🥰🤧</p>
        </div>

        <div id="slide-6" class="slide">
            <div class="image-container">
                <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAYEBQYFBAYGBQYHBwYIChAKCgkJChQODwwQFxQYGBcUFhYaHSUfGhsjHBYWICwgIyYnKSopGR8tMC0oMCUoKSj/2wBDAQcHBwoIChMKChMoGhYaKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCj/wAARCAH6A9cDASIAAhEBAxEB/8QAHAAAAgIDAQEAAAAAAAAAAAAAAwQFBgECBwAI/8QAUxAAAQQBAwIDBAcFBQYEBQIEBwAAAQIDBAUGEQcSITFBURMVImFxgZEyQrEjJHKCtfAUI0OSwdHh8TRTYnLCNFSDstLiGFSCsxYmZHOj/8QAGwEAAgMBAQEAAAAAAAAAAAAAAQIAAwQFBgcI/8QAMBEBAAICAQMDAwMDAwUBAAAAAAECAxEEITESBSJBUYEUMgYUM3EjQlGhscHR8PH/2gAMAwAAhEDEQA/APx1rX4W9WtbWtA83Wta1rWga1rWta1rQNa1rWta0DX//2Q==" alt="Komal's Photo 5">
            </div>
            <p class="message">Milk ko kehte hai doodh, Aur Curd ko kehte hai dahi, Kahi aapke dil me hum to nahi..!🥺</p>
        </div>
        
        <div id="slide-7" class="slide">
            <h1 class="initial-message">Happy Birthday, Komal! 🎂❤️</h1>
            <p class="message" style="font-size: 1.8em; color: #d81b60;">
                You are my whole world. Every day with you is a gift. This is just a small way to tell you: I love you more than words can say. May your year be as beautiful as your smile!
            </p>
        </div>
        
        <button class="next-button" onclick="nextSlide()">Next →</button>
    </div>

    <script>
        let currentSlide = 0;
        const totalSlides = 8; // Total slides: 0 through 7
        const slides = document.querySelectorAll('.slide');
        const nextButton = document.querySelector('.next-button');

        function nextSlide() {
            const music = document.getElementById('bg-music');
            if (music.paused) {
                // Try to play the music on the first click
                music.play().catch(error => {
                    console.log("Autoplay was prevented. User needs to interact with the page first.");
                });
            }

            slides[currentSlide].classList.remove('active');
            currentSlide = (currentSlide + 1) % totalSlides;
            slides[currentSlide].classList.add('active');
        }
    </script>
</body>
</html>
