# <p align="center">My Profile</p>

<p align="center">🌟 RevoU FSSE Student - Section Seoul 🌟</p>

---

Hi, I'm **Jeong** from Team 2 🙋‍♂️

![mylink](https://i1.sndcdn.com/avatars-000638932203-7921ri-t500x500.jpg)

## 🤷‍♂️ About Me

I'm currently exploring exciting opportunities in my career journey as a **Software Engineer**. I'm passionate about coding and web development, and I'm thrilled to be a part of the RevoU community to further hone my skills.

- 📍 **Location:** Indonesia
- 🐈‍⬛ **GitHub:** [kevinjeonghun](https://github.com/kevinjeonghun)
- 💼 **LinkedIn:** [kevinjeonghun](https://www.linkedin.com/in/kevinjeonghun/)

---

## 📝 Project Milestone 1 - Create a company profile page using HTML & CSS, Responsive, Deploy with Custom Domain

**Final Deployment**

Check out my self created website below by clicking this [link](https://topupzone.my.id)

**My HTML Structure**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <div class="wrapper">
            <div class="logo"><a href=''>Please Fill In</a></div>
            <div class="menu">
                <ul>
                    <li><a href="#Please Fill In">Please Fill In</a></li>
                    <li><a href="#Please Fill In">Please Fill In</a></li>
                    <li><a href="#Please Fill In">Please Fill In/a></li>
                    <li><a href="#Please Fill In">Please Fill In</a></li>
                    <li><a href="#Please Fill In">Please Fill In</a></li>
                    <li><a href="" class="tbl-biru">Please Fill In</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="wrapper">
<!-- Section 1 -->
        <section id="produk">
            <img src="Please Fill In" alt="Please Fill In"/>
            <div class="kolom">
                <p class="deskripsi">Please Fill In</p>
                <h2>Please Fill In</h2>
                <p>Please Fill In</p>
                <p><a href="" class="tbl-biru">Please Fill In</a></p>
            </div>
        </section>

<!-- Card Section -->
        <section id="timkami">
            <div class="tengah">
                <div class="kolom">
                    <p class="deskripsi">Perkenalkan Tim Software Engineers Kami</p>
                    <h2>Team 2</h2>
                </div>

                <div class="tim-kami">
                    <div class="kartu-tim">
                        <img src="Please Fill In" alt="Please Fill In"/>
                        <p>Jeong</p>
                    </div>
                </div>
            </div>
        </section>
    </div>
</body>
</html>
```

**My CSS Structure**

To make everything responsive:

```
@media screen and (max-width: 991.98px) {
    .wrapper {
        width: 90%;
    }

    .logo a {
        display: block;
        width: 100%;
        text-align: center;
    }

    nav .menu {
        width: 100%;
        margin: 0;
    }

    nav .menu ul {
        text-align: center;
        margin: auto;
        line-height: 60px;
    }

    nav .menu ul li {
        display: inline-block;
        float: none;
    }

    section {
        display: block;
    }

    section img {
        display: block;
        width: 100%;
        height: auto;
    }

    .kartu-tim {
        width: 50%;
    }

    .social-logo {
        display: block;
        text-align: center;
        width: 50%;
    }
}
```

**Vercel Sign up process & connect Vercel to your Github project & Auto Deployment on Github with Vercel**

1.  Create or login your Vercel account [here](https://vercel.com/signup)
2.  Choose your Plan Type & enter your name
3.  Continue with GitHub (Recommended)
4.  Choose your Git Repository and click Import
5.  Wait until deployment completed
6.  Done. Please note that configuring your GitHub repository as **public** will result in automatic deployment updates whenever changes occur.

![alt text](https://github.com/revou-fsse-3/Module-2-Jeong/blob/main/Assets/collage-1.jpg?raw=true)

**How to connect your custom domain and DNS**

1. Create or login your Niagahoster account [here](https://www.niagahoster.co.id/cpanel-login)
2. Click on "Domain" tab and enter the domain name you want
3. Once you have chosen, click on "_Beli domain_" button
4. Proceed to the payment method page and make the payment
5. Click on "_Kelola_" button to change your domain settings
6. Open your vercel domain settings
7. We need to configure the DNS record in Niagahoster so that it matches with Vercel (Follow step 8 & 9)
8. In _Kelola DNS Record_ form, fill in _Tipe_ to "CNAME", _Nama_ and Target as similar to Vercel domain settings. Leave TTL default to "14400". If you done, click on "_Tambah Record_" button
9. Scroll down & find _Tipe_ "A", then click on "Edit" button. Edit _Mengarah ke_ address as similar to Vercel domain settings. Then change the TTL to "60". If you done, click on "_Perbarui_" button
10. Wait for the domain to process, it may take around 3-5 minutes
11. Done, you can now open your project with your custom domain

![alt text](https://github.com/revou-fsse-3/Module-2-Jeong/blob/main/Assets/collage-2.jpg?raw=true)

![alt text](https://github.com/revou-fsse-3/Module-2-Jeong/blob/main/Assets/collage-3.jpg?raw=true)

---

<p align="right">last created on November 17, 2023</p>
<p align="right"><i>&copy; 2023. KevinJeongHun. All Rights Reserved.</i></p>
