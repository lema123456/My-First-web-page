<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>
  
    <style>
        body {

        }

        h1, h2, p {
            text-align: center;
            color: black;
            margin-bottom: 10px;
        }

        h1 {
            font-size: 36px;
            color: #black;
        }

        h2 {
            font-size: 28px;
            color: black;
        }

         Flexbox for main content 
        .main-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 20px;
        }

        .left-content, .right-content {
            flex: 1;
            padding: 20px;
        }

        .right-content {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 10px;
            
        }

     {
            border-radius: 10px;
            background-color: white;
            padding: 10px;
            box-shadow: 0 4px 8px rgba;
            transition: transform 0.3s ease;
        }

        .round:hover {
            transform: translateY(-10px);
        }

        .oval {
            border-radius: 40px;
            background-color: rgba(black);
            padding: 20px;
            box-shadow: 0 4px 12px rgba;
        }

        .rectangle {
            background-color: rgba(black);
            padding: 20px;
            box-shadow: 0 4px 16px ;


        }

        img {
            display: block;
            margin: 20px auto;
            border-radius: 8px;
            box-shadow: ;
            transition: transform 0.3s ease-in-out;
        }

        img:hover {
            transform: scale;
        }

        video, audio {
            display: block;
            margin: 20px auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba;
        }

        .content-card {
            background: rgba;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba;
            margin: 20px auto;
            max-width: 800px;
            transition: transform 0.3s ease-in-out;
        }

        .content-card:hover {
            transform: translateY(-10px);
        }

        a {
            text-decoration: none;
            color: #2980b9;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        a:hover {
            color: black;
        }

        .button {
            display: inline-block;
            padding: 12px 25px;
            background-color:black;
            color: white;
            font-size: 16px;
            font-weight: bold;
            border-radius: 5px;
            text-align: center;
            text-decoration: none;
            transition: background-color black;
        }

        .button:hover {
            background-color: black;
        }

        keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        .fade-in {
            animation: fadeIn 1.5s ease-in-out;
        }

    </style>
</head>
<body>


    <h1 class="fade-in">My little world of writing   &#127757;</h1>


<div class="content-card fade-in rectangle">
<p>Welcome to my personal world of writing, where words flow like rivers and ideas take flight like birds in the sky. It's a place where I share my thoughts, my dreams, and my experiences through the beauty of language. Join me in discovering new worlds, one sentence at a time.</p>
    </div>

    <div class="main-content">
        <div class="left-content">
            <div class="content-card fade-in rectangle">
                <p>Life isn't easy at the age of nineteen or twenty one, you will lose friends, face financial problems, have goals but can't accomplish them, you will fall, fail, face a bitter reality, mistakes will be made. Even you will lose yourself. You will see your parents getting old, scoring low marks in your exams, and then everyone hates you and you can't do anything about it. I'm at this stage but I always keep telling myself that: Well, life has problems, struggles and difficulties, but patience, positive thinking and learning from mistakes can make you stronger, this time will pass, take courage and believe in yourself.</p>
            </div>

            <img src="Hawa.jpg" width="350” height=“300” alt="Hawa.jpg">
            
            <h2 class="fade-in">The Smell of Peace</h2>

            <div class="content-card fade-in rectangle">
                <p>An immigrant knows very well about life and how it feels to be in another country.
                Exactly as you say it has a lot of facilities, but how about me? How about my losses, did you ever ask yourself how a person could fight with all 100 things at a time? With all that some people say you did nothing and you were in another country for a long. But I say, do you think it’s going to be easy to spend that much time without all the things you wanted to have in your own country, you know what we just came to spend time not to live. As an immigrant, I would say when I see the sky I feel like I’m in my own country. It feels comfortable with the smell, wind, and even all the trees, but how about earth? Have you ever woken up from a deep dream that you enjoyed? This is exactly my life.</p>
            </div>

          

            <div class="content-card fade-in rectangle">
                <p>Reading books fills me with a sense of wonder, as if I’m glimpsing into different minds. It brings me joy, a deep sense of fulfillment, and the feeling that I hold a powerful key—one that can unlock doors to new possibilities.</p>
            </div>

            <img src="lemaa.jpg" width="300" height=“300” alt="lemaa.jpg">

            <h2 class="fade-in">Unknown world</h2>

            <div class="content-card fade-in round">
                <p> In searching for secrets, you will be able to find more secrets. 
                در جستجوی اسرار، می توانید اسرار بیشتری را بیابی.</p>
            </div>

            <div class="content-card fade-in rectangle">
                <p>My biggest fear in life has always been changing people's behavior! Sometimes I ask myself why? That is, what makes people not be with you after a while like they were in the first days. This issue has been an unsolvable puzzle for me. If I make friends, I will stay with someone until my death. If I love someone, I will love them with every bit of my being, but these people...
                How easy it is to go to heart
                What is easy to replace?
                And how convenient. It's easy, it's easy...
                Do they understand from the heart what it feels like?
                Do you understand how quickly the human soul is wounded?
                If people saw themselves through our eyes, you would understand how much we value them.
                Maybe hearts don't fail like this
                Maybe a more colorful life would be more attractive and happier
                lasting friendship
                The lover reaches the beloved
                And life is beautiful!</p>
            </div>
        </div>
           
                <div class="content-card fade-in rectangle">
          <p> I really cherish the simple things in life, for they bring me unlimited joy and calmness,like the peaceful feeling I get when riding my bike, where every pedal takes me closer to a moment of pure happiness.</p>
</div>

        <div class="right-content">
            <video width=“200” controls>
                <source src="lema.mp4" type="video/mp4">
                
            </video>

            <h1 class="fade-in">My Audio</h1>
            <p class="fade-in">In this audio clip, you will hear the gentle strumming of a guitar accompanied by soft sounds, creating a soothing and tranquil atmosphere.</p>

            <audio controls>
                <source src="AudioSample.mp3" type="audio/mpeg">
                <source src="path/to/your/audio.ogg" type="audio/ogg">
                Your browser does not support the audio tag.
            </audio>

            <h2 class="fade-in">Check Out My Favorite Video</h2>
            <p class="fade-in">Visit my favorite video: <a href="https://www.youtube.com/watch?v=cW8VLC9nnTo" target="_blank" class="button">Watch Now</a></p>
        </div>
    </div>

</body>
</html>
