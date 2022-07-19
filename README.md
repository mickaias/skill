nav a {
    color: #101010;
    text-decoration: none;
    font-family: 'Poppins', sans-serif;
    padding-right: 20px;
    position: relative;
    
}

nav a::after {
    content: " ";
    width: 0%;
    height: 2px;
    background-color: #101010;
    position: absolute;
    bottom: 0;
    left: 0;
    transition: 0.4s ease-in-out;
}

nav a:hover::after {
    width: 85%;
}

/*--hover--*/
