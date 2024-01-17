<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #f4f4f4;
            padding: 20px;
            position: sticky;
            top: 0;
            z-index: 100;
            /* transition: all 3s ease; */
        }
        nav ul {
            display: flex;
            justify-content: space-around;
            list-style: none;
            padding: 0;
            /* transition: all 3s ease; */
        }
        nav ul li a {
            color: #333;
            text-decoration: none;
            /* transition: all 3s ease; */
        }
        main {
            padding: 20px;
            /* transition: all 3s ease-in; */
        }        
        section {
            margin-bottom: 20px;
        }        
        button {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
        }
        footer {
            background-color: #f4f4f4;
            padding: 20px;
            text-align: center;
            background-color: transparent;
        }
        .media{
            width: 10rem;
            height: 10rem;
            align-items:self-start;
            justify-content:left ;
        }        
        .bn39 svg{
            margin: 3px;
        }
        .media a{
            text-decoration: none;
        }
        .bn39 {
            height: 2.5rem;
            width: 9rem;
            margin: 10px;
            border-radius: 6px;
            box-sizing: border-box;
            color: #ffffff;
            display: block;
            font-size: 1rem;
            font-weight: 600;
            padding: 4px;
            position: relative;
            text-decoration: none;
            z-index: 2;
        }          
        .bn39:hover {
            color: #fff;
        }          
        .bn39 .bn39span {
            align-items: center;
            background: #0e0e10;
            border-radius: 6px;
            display: flex;
            justify-content: center;
            height: 100%;
            transition: background 0.5s ease;
            width: 100%;
        }          
        .bn39:hover .bn39span {
            background: transparent;
        }
        .insta{
            background-image: linear-gradient(135deg, #ff0059, #0804c3);
        }
        .tele{
            background-image: linear-gradient(135deg, #7c01e7, #00a6ff);
        }
        .yt{
            background-image: linear-gradient(135deg, #ff0000, #ff0000);
        }
        
        nav ul li a:focus section{
            margin-top: 25px;
        }
        /* Dark mode styles */
        
        body.dark-mode {
            background-color: #333;
            color: #fff;
        }
        header.dark-mode{
            background-color: transparent;
            color: #fff;
        }
        button.dark-mode {
            background-color: #4CAF50;
            color: #333;
        }
        nav ul li a.dark-mode {
            color: #fff;
        }        
        footer.dark-mode {
            background-color: #8e6a6a;
            color: #ccc;
        }
        .bn39.dark-mode {
            color: #fff;
        }</style>
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#about">About</a></li>
            </ul>
        </nav>
        <button id="darkLight">Dark Mode</button>
    </header>
    <main>
        <section id="home">
            <h1>Welcome to my Personal Website</h1>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus mollitia iure aspernatur? Provident quaerat dolores beatae ab, consequuntur quos doloremque, voluptatum exercitationem architecto amet recusandae minima cumque in sed neque!
        </section>
        <section id="portfolio">
            <h1>Portfolio</h1>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet iure ipsum ea ab quaerat obcaecati sint! Commodi ut iste cumque quasi neque alias exercitationem, quo accusamus vel eum ab voluptas.
            Iste ipsam omnis magni earum assumenda, repellat harum corrupti consequuntur totam pariatur sunt maxime. Nemo rem eum repudiandae officiis? Id, consectetur recusandae fugiat voluptate perspiciatis nisi exercitationem nihil accusantium tempore.
            Laboriosam quasi repellendus aliquam officiis sed quidem alias laudantium eum? Ea eius et soluta ducimus modi quidem. Quibusdam asperiores, esse, at illum illo fuga doloremque, officiis necessitatibus amet sapiente vel.
            Voluptatibus, quaerat odio? Laudantium delectus enim magni maxime ab temporibus explicabo suscipit ut eligendi vel id blanditiis itaque quod tempore dicta ullam quae iusto voluptatibus, perspiciatis consequuntur non. Doloribus, assumenda!
            Aut eaque, modi error eligendi esse, nostrum fuga dolorum dicta rem sequi necessitatibus quam, neque obcaecati eos ab nulla quibusdam illo culpa totam officia nam. Nisi illum quae quod. Eligendi.
        </section>
        <section id="contact">
            <h1>Contact</h1>
            <div class="media">
                <a class="bn39 insta" href=""><span class="bn39span"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
                    <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334"/>
                    </svg>INSTAGRAM</span></a>
                <a class="bn39 tele" href=""><span class="bn39span">TELEGRAM</span></a>
                <a class="bn39 yt" href=""><span class="bn39span">YOU TUBE</span></a>
            </div>
        </section>
        <section id="about">
            <h1>About</h1>
        </section>
    </main>
    <footer>
        <p> &copy; 2024, AVINASH BAGHE. All rights reserved.</p>
    </footer>
</body>
</html>
