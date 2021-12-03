# my_portf
.navbar {
    background-color: brown;
    height: 50px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    opacity: 0.5;
  }
  .navlink {
    color: hsl(0, 0%, 100%);
    font-size: 1.2em;
    letter-spacing: 0.2em;
    margin: 0 0.5;
    border: 0.1em solid brown;
    padding: 0.2em;
    transition: ease-out 1s all;
  }
  .left {
    position: fixed;
    left: 0px;
    width: 300px;
    border: 3px solid #73AD21;
    padding: 10px;
  }
  .nav-link:hover {
    background-color: beige;
    color: black;
  }
  
  .social {
    list-style: none;
    display: flex;
    flex-direction: row;
    justify-content: center;
  }
  .gallery {
    margin: 5px;
    border: 1px solid #ccc;
    float: left;
    width: 180px;
  }
  
  div.gallery:hover {
    border: 1px solid #777;
  }
  
  div.gallery img {
    width: 100%;
    height: auto;
  }
  
  div.desc {
    padding: 15px;
    text-align: center;
  }  
