<h1>Baseball Teams API</h1>

    <h2>What does this API do?</h2>
    <p>Add a city name as a query parameter to a URL and get back information about that city's baseball team in the form of a JSON object.</p>

    <h2>How to Use this API:</h2>
    <p>1. To use this API from anywhere, go to https://baseball-nipq.onrender.com.</p>
    <ul>
        <li>
            <p>Since the hosting is free, it will spin down with inactivity, which can delay requests by 50 seconds or more. Thanks for your patience.</p>
        </li>
    </ul>

    <p>2. Add api/ and a query parameter (a city name) to the URL to get info back about that baseball team.  Press enter to refresh your browser.</p>
    <ul>
        <li>
            <p>Ex. https://baseball-nipq.onrender.com/api/oakland or https://baseball-nipq.onrender.com/api/baltimore.</p>
        </li>
        <li>
            <p>Your query parameter can have a space in it. Ex. https://baseball-nipq.onrender.com/api/kansas city</p>
        </li>
        <li>
            <p>If your query parameter is not the name of a city with a MLB team, you will get back a JSON object that says the info is unknown.</p>
        </li>
    </ul>
    <p>3.  You will see info about that city's baseball team in the browser in the form of a JSON object.</p>

    <h2>For Developers:</h2>
    <p>If you prefer to host this server and api locally on your computer (instead of accessing the version hosted on render.com) and have node.js installed, you can:</p>
    <ul>
        <li><p>Type 'node server.js' in your command line to start the local server.</p></li> 
        <li><p>Go to localhost:8000 in your web browser to read this documentation </p></li>
        <li><p>Follow the instructions for query parameter use above using the local host. Ex. localhost:8000/api/kansas city </p></li>
    </ul>