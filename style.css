*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#0b1220;
    color:#fff;
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    overflow:hidden;
}

.bg{
    position:fixed;
    inset:0;
    background:
        radial-gradient(circle at top left,#2563eb55,transparent 35%),
        radial-gradient(circle at bottom right,#06b6d455,transparent 35%),
        #0b1220;
    z-index:-1;
}

.container{
    width:100%;
    display:flex;
    justify-content:center;
    padding:20px;
}

.card{
    width:100%;
    max-width:420px;
    background:rgba(20,28,45,.92);
    backdrop-filter:blur(15px);
    border:1px solid rgba(255,255,255,.08);
    border-radius:20px;
    padding:25px;
    box-shadow:0 0 35px rgba(0,150,255,.25);
    animation:fade .5s;
}

@keyframes fade{
    from{
        opacity:0;
        transform:translateY(20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

h1{
    text-align:center;
    font-size:30px;
    margin-bottom:5px;
}

.sub{
    text-align:center;
    color:#9ca3af;
    margin-bottom:20px;
}

.tab{
    display:flex;
    gap:10px;
    margin-bottom:20px;
}

.tab button{
    flex:1;
    padding:12px;
    border:none;
    border-radius:12px;
    cursor:pointer;
    background:#1e293b;
    color:#fff;
    transition:.3s;
    font-weight:600;
}

.tab button:hover{
    background:#2563eb;
}

.tab .active{
    background:#2563eb;
}

label{
    display:block;
    margin:10px 0 6px;
    font-size:14px;
}

input{
    width:100%;
    padding:13px;
    border:none;
    outline:none;
    border-radius:12px;
    background:#111827;
    color:#fff;
    margin-bottom:10px;
}

input:focus{
    border:1px solid #3b82f6;
}

.check{
    width:100%;
    padding:14px;
    margin-top:15px;
    border:none;
    border-radius:12px;
    cursor:pointer;
    font-size:16px;
    font-weight:bold;
    color:#fff;
    background:linear-gradient(90deg,#2563eb,#06b6d4);
    transition:.3s;
}

.check:hover{
    transform:scale(1.03);
    box-shadow:0 0 20px #2563eb;
}

#loading{
    display:none;
    margin-top:20px;
    text-align:center;
}

.loader{
    width:45px;
    height:45px;
    border:5px solid rgba(255,255,255,.15);
    border-top:5px solid #3b82f6;
    border-radius:50%;
    margin:auto;
    animation:spin 1s linear infinite;
}

@keyframes spin{
    100%{
        transform:rotate(360deg);
    }
}

#loading span{
    display:block;
    margin-top:12px;
    color:#cbd5e1;
}

#result{
    display:none;
    margin-top:25px;
    background:#111827;
    padding:18px;
    border-radius:14px;
    border:1px solid rgba(255,255,255,.08);
}

#result h3{
    text-align:center;
    margin-bottom:10px;
}

.line{
    height:2px;
    background:#2563eb;
    margin-bottom:12px;
}

#result p{
    margin:8px 0;
    color:#e5e7eb;
    word-break:break-word;
}

@media(max-width:500px){

.card{
    padding:18px;
}

h1{
    font-size:24px;
}

.check{
    font-size:15px;
}

}