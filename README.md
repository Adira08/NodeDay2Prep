# NodeDay2Prep

<hr />

<h1>Question1:What are the different types of HTTP requests?</h1>
    <p>HTTP Stand for "Hyper Text Transfer Protocol" which specifies a collection of request methods to specify what action is to be performed on a particular resource.</p>
    <ul>HTTP Request methods are as mentioned below:
        <li>GET: GET request is used to read/retrieve data from a web server. GET returns an HTTP status code of 200 (OK) if the data is successfully retrieved from the server.</li>
        <li>POST:POST request is used to send data (file, form data, etc.) to the server. On successful creation, it returns an HTTP status code of 201.</li>
        <li>PUT: A PUT request is used to modify the data on the server.</li>
        <li>PATCH: PATCH is similar to PUT request, but the only difference is, it modifies a part of the data. It will only replace the content that you want to update.</li>
        <li>DELETE: A DELETE request is used to delete the data on the server at a specified location.</li>
    </ul><br>
    <h1">Question2:Explain the concept of middleware in Node.js.</h1>
    <ul>
        <li>Middleware are like general function which takes three parameters as request,response and next.</li>
        <li>These middleware are used to execute some function before the resposne is send back to the client.</li>
        <li>Middleware mostly get used for authentication if the API request is called from the client with proper user credentials or not.</li>
        <li>next() function is very important,after the end of each middleware we should execute the next() function so that the program execution can move w=either to next middleware or to main route.</li>
    </ul><br>
    <h1>Question3:Explain CORS?</h1>
    <ul>
        <li>CORS Stands for "cross-rigin resource sharing".</li>
        <li>CORS is a mechanism by what data or any other resource of a site could be shared to a third party website when there is need.</li>
    </ul><br>
    <h1>Question4:What is Express?how it helps you to create a backend application?</h1>
    <p>Express is a small framework that sits on the top of nodejs wehb server functionality to simplicity its APIs and add helpful features.</p>
    <p>It makes it easier to oragnize your application functionality with middleware and routing.</p>
    <br>
    <h1>Question5:Explain min 5 status codes gets used in Backend development?</h1>
    <p>An HTTP status code is a message a website's server sends to the browser to indicate whether or not that request can be fulfilled.</p>
    <p>
        HTTP status codes are:-
        <ul>
            <li>200:This is the standard "OK" status code for a successful request.</li>
            <li>400:This indicates the "BAD REQUEST" response status code means the server cannot or will not process the request due to something i.e preceived to be client error.</li>
            <li>401:This status code request occurs when authentication is required but has failed or not been provided.</li>
            <li>402:This status code request occurs for payment.The initial aim for creating this code was using it for digital payment system.</li>
            <li>403:The client does not have access rights to the content i.e it is unauthorised so the server is refusing to give the requested resource.</li>
            <li>404:A status code 404 occurs when the request is valid, but the resource cannot be found on the server.</li>
            <li>500:The status code 500 happens when the server cannot fulfill a request due to an unexpected issue.</li>
            <li>503:The status code 503 occurs when the server is not ready to handle the request and due to this give error of 503 as service unavialable.</li>
        </ul>
    </p><br>
    <h1>Question6:What is the Difference between HTTP and HTTPS?</h1>
    <ul>
        <b>HTTPS</b>
        <li>HTTP stands for "Hyper Text Transfer Protocol".</li>
        <li>In HTTP,URL begins with "http://".</li>
        <li>HTTP is considered to be insecured.</li>
        <li>HTTP speed is faster than HTTPS.</li>
        <li>HTTP uses port number 80 for communication.</li>
    </ul>
    <ul>
        <b>HTTPS</b>
        <li>HTTPS stands for "Hyper Text Transfer Protocol secure".</li>
        <li>In HTTPS,URL begins with "https://".</li>
        <li>HTTPS is secure.</li>
        <li>HTTPS speed is slower than HTTP.</li>
        <li>HTTPS uses port number 443 for communication.</li>
    </ul><br>
    <h1>Question7:What are JWT tokens?</h1>
    <ul>
        <li>To achieve authentication in the APIs, we use JWT tokens.</li>
        <li>They stand for JSON Web Tokens.</li>
        <li>When any user logs-in by giving its username and password, then we will receive the username and password in the request body of the API.</li>
        <li>Then using username and password we will create one token and assign it to the user.</li>
        <li>Then whenever this user will be calling any API, then this token will be passed from front-end application, then from backend application we will verify this token is valid or not.</li>
        <li>This is how we can achieve authentication in the APIs using JWT tokens.</li>
    </ul> 
