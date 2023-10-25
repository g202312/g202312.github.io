<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Group 12</title>
    <style>

        .teammates {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }

        .teammate {
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 10px;
            margin: 10px;
            padding: 20px;
            max-width: 300px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }

        .teammate:hover {
            transform: translateY(-5px);
        }

        a {
            text-decoration: none;
            color: #007bff;
            font-weight: 600;
        }

        a:hover {
            text-decoration: underline;
        }
        .supervisor {
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 10px;
            margin: 0 auto; /* Center horizontally */
            padding: 20px;
            max-width: 350px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
            display: flex;
            flex-direction: column;
            align-items: center; /* Center vertically */
        }
    
        .supervisor:hover {
            transform: translateY(-5px);
        }    
    </style>
</head>
<body>
    <header>
        <h1>Group 12</h1>
    </header>

    <div><p>The forthcoming section provides an in-depth overview of the team composition and the computational infrastructure that underpins our project.Our team is comprised of five individuals, each possessing distinct competencies and specializations. Ziyang Wang’s expertise lies in algorithm design and implementation, with a research focus on deep learning and quantum computing. Bin Jia contributes his proficiency in project management and commercialization, with a particular interest in Unreal Engine development and knowledge-transfer. Jianxu Shangguan is also adept at algorithm design and implementation, with a specialization in computer vision. Eajun’s forte is web development and requirement engineering, while Haoxiang Shi is responsible for data collection and cleaning.Regarding infrastructure, we utilize a remote computation station furnished with two A800 computation cards. These cards are constructed on the 7 nm process and are based on the GA100 graphics processor with 80G VRAM. This setup is capable of training a Language Model with 30 billion parameters.
    </p></div>
    
    <!-- Supervisor section -->
    <div class="supervisor">
        <h2>Jian Feng ren</h2>
        <p>Role: Supervisor</p>
        <p>Email: JianFeng.Ren@nottingham.edu.cn</a>
    </div>
    
    <!-- Teammates section -->
    <div class="teammates">
        <div class="teammate">
            <h2>Zi Yang Wang</h2>
            <p>Role: Leader</p>
            <p>Email: scyzw14@nottingham.edu.cn</p>
        </div>
        <div class="teammate">
            <h2>Bin Jia</h2>
            <p>Role: Project Manager</p>
            <p>Email: hmybj2@nottingham.edu.cn</a>
        </div>
        <div class="teammate">
            <h2>Jianxu Shangguan</h2>
            <p>Role: Project Manager</p>
            <p>Email: scyjs5@nottingham.edu.cn</a>
        </div>
        <div class="teammate">
            <h2>Eajun Ooi Yik Jun</h2>
            <p>Role: Interface design</p>
            <p>Email: hfyeo1@nottingham.edu.cn</a>
        </div>
        <div class="teammate">
            <h2>Shi Yun Xiang</h2>
            <p>Role: Member</p>
            <p>Email: scyys10@nottingham.edu.cn</a>
        </div>
    </div>
</body>
</html>
