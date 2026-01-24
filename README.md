
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>O Mapa da Sua Dor</title>

<style>
:root{
  --rose:#C9376E;
  --blue:#4DA6FF;
  --ink:#0F172A;
  --soft:#667085;
  --line:#E9EEF5;
}
*{box-sizing:border-box}
html,body{margin:0;padding:0;font-family:system-ui;background:#fff;color:var(--ink)}

header,.page-header,.site-header,.project-name,.project-tagline,
#header,#page-header{display:none!important}

/* Barra fixa */
.topbar{
  position:fixed;top:0;left:0;right:0;height:90px;
  background:var(--rose);z-index:9999;
  display:flex;align-items:center;justify-content:center;
}
.topbar h1{
  color:#fff;font-weight:900;letter-spacing:.08em;
  text-transform:uppercase;font-size:28px;margin:0;
}

.page{padding-top:110px}
.wrap{max-width:980px;margin:0 auto;padding:0 16px}

/* Hero */
.hero-card{
  border:1px solid var(--line);
  border-radius:22px;
  padding:32px;
  text-align:center;
  box-shadow:0 12px 30px rgba(0,0,0,.06)
}
.lead{color:var(--soft);font-size:20px;line-height:1.55}
.divider{
  height:8px;width:280px;margin:20px auto;
  background:linear-gradient(90deg,var(--rose),var(--blue));
  border-radius:999px
}

/* Botões */
.btn{
  padding:14px 22px;border-radius:14px;
  font-weight:900;border:none;cursor:pointer
}
.primary{background:var(--rose);color:#fff}
.ghost{background:#fff;border:2px solid var(--blue);color:var(--blue)}
.cta{display:flex;gap:12px;justify-content:center;flex-wrap:wrap}

/* Quiz */
section{padding:48px 0;border-bottom:1px solid var(--line)}
.section-title{
  text-align:center;font-size:36px;font-weight:900;
  background:linear-gradient(90deg,var(--rose),var(--blue));
  -webkit-background-clip:text;color:transparent
}
.q{
  border:1px solid var(--line);
  border-radius:16px;
  margin-bottom:14px;
  overflow:hidden
}
.q-head{
  padding:14px;
  background:rgba(201,55,110,.08);
  font-weight:900
}
.options{padding:14px}
.opt{
  display:flex;gap:10px;margin-bottom:10px;
  padding:10px;border:1px solid var(--line);
  border-radius:12px;cursor:pointer
}
.opt:hover{background:#f4f8ff}
.actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:16px}

/* Resultado */
#result{display:none}
.result-box{
  border:1px solid var(--line);
  border-radius:18px;
  margin-top:20px;
  overflow:hidden
}
.result-top{
  background:linear-gradient(90deg,var(--rose),var(--blue));
  color:#fff;padding:16px
}
.result-body{padding:18px}
.first-step{
  margin-top:14px;
  padding:12px;
  border-radius:12px;
  background:#e8f7f1;
  font-weight:900
}

/* WhatsApp flutuante */
.whats{
  position:fixed;right:18px;bottom:18px;
  width:60px;height:60px;border-radius:50%;
  background:#25D366;display:flex;
  align-items:center;justify-content:center;
  z-index:9999
}
.whats svg{width:30px;height:30px;fill:#fff}
</style>
</head>

<body>

<div class="topbar">
  <h1>O MAPA DA SUA DOR</h1>
</div>

<div class="page">

<div class="wrap">
  <div class="hero-card">
    <p class="lead"><strong>Descubra a raiz emocional do cansaço que você sente</strong><br>
    e o primeiro passo para se libertar dele.</p>

    <p class="lead"><strong>Este não é um teste comum.</strong><br>
    É um espelho emocional para revelar onde você está se perdendo de si.</p>

    <div class="divider"></div>

    <div class="cta">
      <a href="#quiz" class="btn primary">Começar agora</a>
    </div>
  </div>
</div>

<section id="quiz">
<div class="wrap">
<h2 class="section-title">Quiz</h2>

<form id="quizForm">

<!-- PERGUNTAS -->
<div class="q"><div class="q-head">1️⃣ Quando você pensa na sua rotina, o que mais aparece?</div>
<div class="options">
<label class="opt"><input type="radio" name="q1" value="A"> A) Sensação de estar sempre devendo algo</label>
<label class="opt"><input type="radio" name="q1" value="B"> B) Cansaço mesmo quando descanso</label>
<label class="opt"><input type="radio" name="q1" value="C"> C) Irritação por fazer mais do que os outros</label>
<label class="opt"><input type="radio" name="q1" value="D"> D) Vazio mesmo com conquistas</label>
<label class="opt"><input type="radio" name="q1" value="E"> E) Medo de errar ou decepcionar</label>
</div></div>

<div class="q"><div class="q-head">2️⃣ Em conflitos, você costuma:</div>
<div class="options">
<label class="opt"><input type="radio" name="q2" value="A"> A) Engolir o que sente</label>
<label class="opt"><input type="radio" name="q2" value="B"> B) Assumir tudo</label>
<label class="opt"><input type="radio" name="q2" value="C"> C) Explodir depois</label>
<label class="opt"><input type="radio" name="q2" value="D"> D) Se afastar</label>
<label class="opt"><input type="radio" name="q2" value="E"> E) Travar</label>
</div></div>

<div class="q"><div class="q-head">3️⃣ Qual frase combina com você?</div>
<div class="options">
<label class="opt"><input type="radio" name="q3" value="A"> A) Se eu não fizer, ninguém faz</label>
<label class="opt"><input type="radio" name="q3" value="B"> B) Estou cansado(a), mas não paro</label>
<label class="opt"><input type="radio" name="q3" value="C"> C) Eu me cobro muito</label>
<label class="opt"><input type="radio" name="q3" value="D"> D) Falta algo</label>
<label class="opt"><input type="radio" name="q3" value="E"> E) Medo de perder o controle</label>
</div></div>

<div class="q"><div class="q-head">4️⃣ Cuidar de você gera:</div>
<div class="options">
<label class="opt"><input type="radio" name="q4" value="A"> A) Culpa</label>
<label class="opt"><input type="radio" name="q4" value="B"> B) Falta de tempo</label>
<label class="opt"><input type="radio" name="q4" value="C"> C) Egoísmo</label>
<label class="opt"><input type="radio" name="q4" value="D"> D) Confusão</label>
<label class="opt"><input type="radio" name="q4" value="E"> E) Medo</label>
</div></div>

<div class="q"><div class="q-head">5️⃣ O que mais drena sua energia?</div>
<div class="options">
<label class="opt"><input type="radio" name="q5" value="A"> A) Relações</label>
<label class="opt"><input type="radio" name="q5" value="B"> B) Trabalho/dinheiro</label>
<label class="opt"><input type="radio" name="q5" value="C"> C) Família</label>
<label class="opt"><input type="radio" name="q5" value="D"> D) Expectativas</label>
<label class="opt"><input type="radio" name="q5" value="E"> E) Pensamentos</label>
</div></div>

<div class="actions">
<button type="button" class="btn primary" id="btnResult">Ver meu resultado</button>
</div>

</form>

<div id="result">
  <div class="result-box">
    <div class="result-top"><h3 id="resultTitle"></h3></div>
    <div class="result-body">
      <p id="resultText"></p>
      <div class="first-step" id="resultStep"></div>
    </div>
  </div>
</div>

</div>
</section>

</div>

<a class="whats" id="whatsFloat" target="_blank">
<svg viewBox="0 0 24 24"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Z"/></svg>
</a>

<script>
const WHATS_NUMBER="5549998110445";

const RESULTS={
A:{title:"DOR DA CULPA",text:"Você carrega pesos que não são seus.",step:"Primeiro passo: devolver o que não te pertence."},
B:{title:"DOR DA SOBRECARGA",text:"Você vive no modo sobrevivência.",step:"Primeiro passo: parar de sustentar tudo sozinho(a)."},
C:{title:"DOR DA RAIVA CONTIDA",text:"A raiva não expressa vira exaustão.",step:"Primeiro passo: reconhecer seus limites."},
D:{title:"DOR DO VAZIO",text:"O cansaço é existencial.",step:"Primeiro passo: resgatar sentido."},
E:{title:"DOR DO CONTROLE E DO MEDO",text:"Controlar tudo consome energia.",step:"Primeiro passo: aprender a confiar."}
};

btnResult.onclick=function(){
const answers=["q1","q2","q3","q4","q5"].map(q=>document.querySelector(`input[name="${q}"]:checked`)?.value);
if(answers.includes(undefined))return;

const count={A:0,B:0,C:0,D:0,E:0};
answers.forEach(a=>count[a]++);
const win=Object.keys(count).reduce((a,b)=>count[a]>count[b]?a:b);
const r=RESULTS[win];

resultTitle.innerText=r.title;
resultText.innerText=r.text;
resultStep.innerText=r.step;
result.style.display="block";

const msg=`Resultado do quiz O Mapa da Sua Dor:%0A${r.title}%0A${r.step}`;
window.open(`https://wa.me/${WHATS_NUMBER}?text=${msg}`,"_blank");
};

whatsFloat.href=`https://wa.me/${WHATS_NUMBER}?text=Oi! Fiz o quiz O Mapa da Sua Dor e quero uma Sessão Diagnóstico Gratuita.`;
</script>

</body>
</html>
