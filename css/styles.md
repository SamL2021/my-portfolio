/_ Original CSS _/

:root {
--clr-light: #451e3e;
--clr-dark: #251e3e;
--clr-accent: #851e3e;
--ff-primary: "Gravitas One", cursive;
--ff-secondary: "Poppins", sans-serif;

    /* #051e3e #651e3e */

}
/_ About _/

.columns {
margin: 30px;
}
.column-one {
margin-top: 0;
text-align: justify;
}

.column-two {
margin-top: 0;
text-align: justify;
}

/_ Tech Skills _/

#tech {
display: flex;
align-items: center;
justify-content: center;
background-color: var(--clr-dark);
background-image: url("img/skills.jpg");
background-size: cover;
min-height: 300px;
max-height: 400px;
margin: 20px;
padding: 20px;
border-radius: 12px;
}

#tech span {
font-family: var(--ff-primary);
font-weight: lighter;
}

/_ Projects _/

.projects-flexbox {
display: flex;
align-items: center;
justify-content: center;
margin: auto;
}

#projects h1 {
text-align: center;
font-size: 3em;
font-family: var(--ff-primary);
padding-bottom: 30px;
padding-top: 20px;
}

.projects-img {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 10px;
padding-bottom: 10px;
}

#projects img {
border: 2px white solid;
max-width: 300px;
margin: 0px;
}

/_ Contact _/

#contact {
padding-top: 10px;
text-align: center;
}

#contact a {
color: white;
text-decoration: none;
font-size: 2em;
}

.icons {
padding-top: 10px;
padding-bottom: 10px;
display: flex;
align-items: center;
}

/_ Footer _/
footer {
border-top: 2px white solid;
padding: 20px;
text-align: center;
}

/_ Media Queries _/

@media (min-width: 768px) {
header {
min-height: 600px;
}

    header h1 {
        font-size: 4em;
    }

    .columns {
        flex: 50%;
        padding: 20px;
    }

    #about {
        display: flex;
    }

}
