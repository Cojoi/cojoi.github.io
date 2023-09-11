# cojoi.github.io
frontend stage one track
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta content="viewport">
        <title>Stage one frontend track</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <main>
            <section>
                <div class="slack-profile">
                    <h1 data-testid="slackDisplayImage">Johjo</h1>
                    <img src="c:\Users\USER\Downloads\IMG-0235.JPG" alt="johjo">
                </div>

            <div class="information">
                <p data-testid="currentDayOfTheWeek">Days of the week: Sunday</p>
                <p data-testid="currentUTCTime">UTC time: <span id="utcTime"></span></p>
                <p data-testid="myTrack">Track: Frontend</p>
                <a href="https://github.com/Cojoi/stage-one-frontend-track.git"  data-testid=“githubURL”>Github Repository</a>
            </div>
            </section>
        </main>
    </body>
</html>


body {
    font: sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
    color: #333;
    height: 100vh;
    background-repeat: no-repeat;
}

main{
    background-color: #f8f8f8;
    color: #333;
}


section{
    padding: 20px;
    flex: 1 1 300px;
    border: 1px solid black;
    background-color: #f8f8f8;
    color: #333;
    margin: 20px;
}

.slack-profile {
    text-align: left;
    margin: 20px;
}

.slack-profile h1{
    font-size: 32px;
}

.slack-profile {
    text-align: center;
    margin: 20px;
}


.information {
    text-align: left;
    margin: 20px;
}

.information p{
    font-size: 20px;
}
