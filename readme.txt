:root {
    background-color: rgba(0, 0, 21, 1);
    
}

.header{
    

}
.heeder-large-screen{
    display: flex !important;
    justify-content: space-evenly !important;
    color:orange;
    font-size: 18px !important;


}
#navDemo{
    background-color: #000015;
    
}
#navDemo a{
    font-size: 13px !important;
    color:orange;
}

.hero{
    height: 650px;
    background-image: url("https://live.staticflickr.com/4002/4400791589_233f6ab870_b.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position:center;
    background-color: #000015; 

    
}
.hero-description{
    height: 650px;
    background-color: rgba(0, 0, 21, .7);
    display: flex;
}
.hero-text{
    width:70% !important;
    margin: auto !important;
    display: flex;
    flex-wrap: wrap;
    
}


.hero-text p{
    color:white;
    width: 50%;
}
.hero-title{
     font-weight: 800;
    text-transform: uppercase;
    font-size: 80px;
    color:orange;
    
    text-align: center;

}
.social{
    width:100%;
}
.icons{
    font-size: 20px;
    letter-spacing: 5px;

}
main{
    width:80% !important;
    margin: auto !important;
}
.title{
    color:white;
    font-weight: 600;
    font-size: 40px;;
    margin:50px 0px;
    text-align: center;
    text-transform: uppercase;
    
}


.skills-logo img{
    width:100%;
    height: 100%;
    object-fit: contain;
}
h3{
    color:white;
    text-align: center;
}

.skills{
    display: flex;
    
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-evenly;
}
.skills-list{
    margin: 30px;;
    padding: 20px;
    height: 200px;
    width:250px;
    display: flex;
    flex-direction: column;
    align-items: center;
    border:1px solid gray;
    background: rgba(255, 75, 255, 0.1);
    box-shadow: 0 8px 40px 0 rgba(45, 57, 231, 0.37);
    backdrop-filter: blur( 4px );
    -webkit-backdrop-filter: blur( 4px );
    border-radius: 10px;
    border: 1px solid rgba( 255, 255, 255, 0.18 );
}
.skills-list:hover{
    transform: scale(1.05);
}
.store{
    margin-top: 50px;
}
.skills-store{
    margin-top: 20px !important;
display: flex;
justify-content: space-evenly;
flex-wrap: wrap;
}
.skills-image{
    width:300px;
    height: 180px;
    
}
.skills-image img{
    width:100%;
    height: 100%;
    object-fit: cover;
}
.skills-store-list{
    width:300px;
    height: 300px;
     margin: 20px;
    overflow: hidden;
    border-top: none;
    
      -webkit-box-shadow: 0 8px 40px 0 rgba(45, 57, 231, 0.37);
              box-shadow: 0 8px 40px 0 rgba(45, 57, 231, 0.37);
    backdrop-filter: blur( 4px );
    -webkit-backdrop-filter: blur( 4px );
    border-bottom: 1px solid blueviolet;
    color:white;
     
}
.hobbies-text-description{
     
padding-left:20px;
display: flex;
flex-direction: column;
     
} 
h4{
    color:white;
    font-weight: 700;
}
.hobbies-hero{
    display: flex;
    flex-wrap: wrap;
    background: rgba(255, 75, 255, 0.1);
    justify-content: space-evenly;
    align-items: center;
    padding:50px;
    margin-top: 50px;
    border:1px solid black;
    border-radius: 10px;
    
}
.hobbies-text{
    width:50%;
    color: orange;

}
.hobbies-title{
    font-size: 40px;
    text-transform: uppercase;

    font-weight: 600;
    

}
.hobbies-image{
    width:400px;
    height: 500px;
}
.hobbies-image img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.hobbies-text p{
    color: white;
}
.contact information{
    
    
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
}
.contact information-list{
    margin-top: 15px !important;
    color: white;
}
h5{
    color:white;
}
span{
    padding-right: 10px;
}
.contact information-list p{
}
.email-contact{
    width:80%;
    color: gray;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
}






html {
  scroll-behavior: smooth;
}

* {
  margin: 0;
  padding: 0;
}








@media screen and (max-width: 1500px) {
    .hero{
        height: 550px !important;;
        background-image: url("https://live.staticflickr.com/4002/4400791589_233f6ab870_b.jpg");
    }
    .hero-description{
        height: 550px
    }
    .hero-title{
        font-size:50px;
    }
}

@media screen and (max-width: 1024px) {
    main{
        width:100% !important;
        margin: auto !important;
    }    
    
}

@media screen and (max-width: 768px) {
    .heeder-large-screen{
        display:block !important;
    }
    header a{
        font-size: 14px;
    }
    .hero{
        height: 400px !important;
        background-image: url("https://live.staticflickr.com/4002/4400791589_233f6ab870_b.jpg");
    }
    .hero-description{
        height: 400px;
        background-color: rgba(0, 0, 21, .7);
        
    
    }
    .hero-title{
        font-size: 35px;;
        
    }
    .hero-text p{
        width: 80%;;
        font-size: 13px;
    }
    .title{
        text-align: center;
        font-size: 30px;
    }
    .hobbies-text{
        width:80%;
        color: blueviolet;

    }
    .hobbies-text p{
        font-size: 13px;
    }
    .hobbies-title{
        font-size: 30px;
        text-transform: uppercase;
        font-weight: 600;
    

    }
    .hobbies-hero{
        width: 80% ;
        margin: auto;
    }
    .hobbies-image{
        width:250px;
        height: 400px;
    }
    .hobbies-image img{
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
    .contact information-list{
        width: 300px;
    }
    .contact information{
        justify-content: space-around;
    }
    .contact information-list p{
        font-size: 14px ;

    }
    h5{
        font-size: 17px;
    }
    
}

@media screen and (max-width: 480px) {
    .heeder-large-screen{
        display:block !important;
    }
    .hero{
        height: 450px !important;
        background-image: url("https://live.staticflickr.com/4002/4400791589_233f6ab870_b.jpg");
    }
    .hero-description{
        height: 450px;
        background-color: rgba(0, 0, 21, .7);
    
    }
    .hero-title{
        font-size: 30px;;
        padding-top: 70px;
    }
    .hero-text p{
        width: 100%;;
        font-size: 13px;
    }
    .title{
        text-align: center;
        font-size: 25px;
    }
    .hobbies-text{
        width:100%;
        color: blueviolet;

    }
    .hobbies-text p{
        font-size: 13px;
    }
    .hobbies-title{
        font-size: 30px;
        text-transform: uppercase;
        font-weight: 600;
    

    }
    .hobbies-hero{
        width: 90% ;
        margin: auto;
    }
    .hobbies-image{
        width:250px;
        height: 400px;
    }
    .hobbies-image img{
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
    .contact information-list{
        width: 300px;
        padding:25px;
        border:1px solid rgba(255, 255, 255, 0.5);
        border-radius: 10px;
    }
    .contact information-list p{
        font-size: 12px ;

    }
    h5{
        font-size: 15px;
    }
    .badge{

    }
    p{
        font-size: 12px;
    }
    
}
