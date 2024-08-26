

<div class="profile">

    <img src="/images/avatar-jessica.jpeg" alt="img" class="img">

    <div class="profile-details">
        <h1>Jessica Randall</h1>
        <p class="location">London, United Kingdom</p>
    </div>

    <p style={"opacity: 0.7"}>"Front-end developer and avid reader."</p>

    <div class="links">
        <div class="link">Github</div>
        <div class="link">Frontend Mentor</div>
        <div class="link">LinkedIn</div>
        <div class="link">Twitter</div>
        <div class="link">Instagram</div>
    </div>

</div>

<style>

    .profile{
        width: 80%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 40px 0px;
        
    }

    .img{
        width: 100px;
        height: 100px;
        border-radius: 50%;
    }

    .profile-details{
        text-align: center;
        margin: 10px 0px;
    }

    .profile-details h1{
        margin-bottom: -5px;
        font-size: 20px;
        font-weight: 700;
    }
    .profile-details p{
        color: hsl(75, 94%, 57%);
        font-weight: 600;
    }

    p{
        font-size: 14px;
        font-weight: 400;  
    }

    .links{
        width: 100%;
        margin-top: 20px;
        display: flex;
        flex-direction: column;
        text-align: center;
    }

    .link{
        width: 100%;
        background-color: hsl(0, 0%, 20%);
        margin-top: 15px;
        color: hsl(0, 0%, 100%);
        padding: 15px 0px;
        border-radius: 10px;
        font-weight: 600;
        font-size: 14px;
    }

    .link:hover{
        cursor: pointer;
        background: hsl(75, 94%, 57%);
        color: hsl(0, 0%, 8%);
        transition: all 0.3s;
    }


    
   
</style>