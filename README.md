<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>O Mapa da Sua Dor — Quiz emocional</title>
  <meta name="description" content="Descubra a raiz emocional do cansaço que você sente e o primeiro passo para se libertar dele. Um espelho emocional com 5 perguntas e resultado imediato." />

  <!-- OG / Twitter -->
  <meta property="og:title" content="O Mapa da Sua Dor — Quiz emocional" />
  <meta property="og:description" content="Descubra a raiz emocional do cansaço que você sente e o primeiro passo para se libertar dele." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=O+Mapa+da+Sua+Dor" />
  <meta name="twitter:card" content="summary_large_image" />

  <style>
    :root{
      --rose:#C9376E;
      --rose-2:#FCE9F0;
      --blue:#4DA6FF;
      --blue-2:#E6F3FF;
      --ink:#0F172A;
      --soft:#667085;
      --line:#E9EEF5;
      --bg:#FFFFFF;
      --success:#10B981;
      --warn:#E11D48;
      --topbar-h: 92px;
    }

    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);
      font-family:ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,Ubuntu,"Helvetica Neue",Arial;
    }
    a{text-decoration:none;color:inherit}
    .wrap{max-width:1100px;margin:0 auto}
    .sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);border:0}

    body > header,
    header.page-header,
    header.site-header,
    .page-header,
    .site-header,
    .project-name,
    .project-tagline,
    .site-title,
    .site-nav,
    .markdown-body > header,
    .markdown-body .page-header,
    .markdown-body .site-header,
    .gh-header,
    .gh-head,
    .Header,
    .header,
    #header,
    #site-header,
    #page-header{
      display:none !important;
      height:0 !important;
      overflow:hidden !important;
      padding:0 !important;
      margin:0 !important;
      border:0 !important;
    }

    .main-content, .container{
      margin-top:0 !important;
      padding-top:0 !important;
    }

    .topbar{
      position:fixed;
      top:0;left:0;right:0;
      height:var(--topbar-h);
      background:var(--rose);
      z-index:99999;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:0 16px;
      box-shadow:0 10px 30px rgba(0,0,0,.12);
    }
    .topbar h1{
      margin:0;
      color:#fff;
      font-weight:900;
      letter-spacing:.08em;
      text-transform:uppercase;
      font-size:clamp(20px,4.2vw,34px);
      text-align:center;
      line-height:1.1;
    }

    .page{
      padding-top: calc(var(--topbar-h) + 22px);
    }

    .hero{padding:22px 20px 12px;background:#fff}
    .hero-card{
      background:#fff;
      border:1px solid var(--line);
      border-radius:22px;
      padding:28px 18px 30px;
      margin:0 auto;
      max-width:980px;
      box-shadow:0 14px 34px rgba(0,0,0,.06);
      text-align:center;
    }
    .lead{
      color:var(--soft);
      font-size:20px;
      max-width:860px;
      margin:10px auto 0;
      line-height:1.55;
    }
    .divider{
      height:10px;
      margin:20px auto 20px;
      max-width:320px;
      border-radius:999px;
      background:linear-gradient(90deg,var(--rose),var(--blue));
    }

    .cta{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;margin:16px 0 0}
    .btn{
      display:inline-block;
      padding:14px 20px;
      border-radius:14px;
      font-weight:900;
      box-shadow:0 8px 18px rgba(0,0,0,.08);
      border:0;
      cursor:pointer;
      user-select:none;
    }
    .btn:focus{outline:3px solid rgba(77,166,255,.25);outline-offset:3px}
    .primary{background:var(--rose);color:#fff}
    .ghost{background:#fff;border:2px solid var(--blue);color:var(--blue)}
    .primary:hover{filter:brightness(1.05)}
    .ghost:hover{background:var(--blue);color:#fff}
    .hint{margin-top:10px;font-size:14px;color:var(--soft);text-align:center;font-weight:700}

    section{padding:54px 20px;border-bottom:1px solid var(--line)}
    .section-title{
      font-size:clamp(28px,4.2vw,44px);
      font-weight:900;margin:0 0 18px;
      background:linear-gradient(90deg,var(--rose),var(--blue));
      -webkit-background-clip:text;background-clip:text;color:transparent;
      text-align:center;
    }
    .grid{display:grid;gap:24px}
    .two{grid-template-columns:1fr}
    @media(min-width:860px){.two{grid-template-columns:1fr 1fr}}

    .card{
      background:#fff;border:1px solid var(--line);border-radius:18px;
      padding:24px;box-shadow:0 10px 28px rgba(31,35,48,.05)
    }
    .pink{background:var(--rose-2)}
    .blue{background:var(--blue-2)}
    .pill{
      display:inline-block;
      background:var(--blue-2);color:var(--blue);
      padding:6px 12px;border-radius:999px;font-weight:900;font-size:12px;
      letter-spacing:.05em;text-transform:uppercase;
      margin-bottom:10px;border:1px solid #dbeafe;
    }
    .grad-left{
      font-size:clamp(22px,3.4vw,32px);
      line-height:1.15;margin:0 0 12px;font-weight:900;
      background:linear-gradient(90deg,var(--rose) 0%, var(--blue) 100%);
      -webkit-background-clip:text;background-clip:text;color:transparent;
      text-align:left;
    }
    p{margin:8px 0 0;font-size:18px;color:var(--soft);line-height:1.65}

    .quiz{max-width:980px;margin:0 auto;display:grid;gap:14px}
    .q{
      border:1px solid var(--line);
      border-radius:16px;
      overflow:hidden;
      background:#fff;
      box-shadow:0 8px 22px rgba(0,0,0,.05);
    }
    .q-head{
      padding:14px 16px 12px;
      display:flex;justify-content:space-between;gap:10px;align-items:flex-start;
      background:linear-gradient(90deg, rgba(201,55,110,.08), rgba(77,166,255,.08));
      border-bottom:1px solid var(--line);
    }
    .q-title{margin:0;font-weight:900;font-size:16px;color:var(--ink)}
    .q-chip{
      flex:0 0 auto;
      font-size:12px;font-weight:900;
      padding:6px 10px;border-radius:999px;
      border:1px solid var(--line);
      background:#fff;
      color:var(--soft);
      white-space:nowrap;
    }
    .options{padding:12px 12px 16px;display:grid;gap:10px}
    .opt{
      display:flex;gap:10px;align-items:flex-start;
      padding:12px 12px;border-radius:14px;
      border:1px solid var(--line);
      background:#fff;
      cursor:pointer;
      transition: background .18s ease, border-color .18s ease;
    }
    .opt:hover{background:rgba(77,166,255,.06);border-color:#cfe7ff}
    .opt input{margin-top:3px}
    .opt b{display:inline-block;min-width:22px;color:var(--ink)}
    .opt span{color:var(--soft);line-height:1.5}

    .actions{
      display:flex;gap:12px;flex-wrap:wrap;align-items:center;justify-content:space-between;
      margin-top:12px;
    }
    .progress{color:var(--soft);font-size:14px;font-weight:800}

    #result{display:none}
    .result-box{
      max-width:980px;margin:18px auto 0;
      border-radius:18px;border:1px solid var(--line);
      overflow:hidden;background:#fff;
      box-shadow:0 10px 28px rgba(31,35,48,.05);
    }
    .result-top{
      padding:16px 18px;
      background:linear-gradient(90deg,var(--rose),var(--blue));
      color:#fff;
    }
    .result-top small{opacity:.92;font-weight:900;letter-spacing:.02em}
    .result-top h3{margin:6px 0 0;font-size:22px;font-weight:900}
    .result-body{padding:18px}
    .result-body p{margin:0;color:var(--soft);line-height:1.7}
    .first-step{
      margin-top:12px;
      padding:12px 12px;border-radius:14px;
      background:rgba(16,185,129,.10);
      border:1px solid rgba(16,185,129,.28);
      color:var(--ink);
      font-weight:900;
    }

    .footer-cta{
      background:var(--blue-2);
      border:1px solid #dbeafe;
      border-radius:16px;
      padding:26px;
      display:flex;gap:16px;flex-wrap:wrap;
      align-items:center;justify-content:space-between;
      max-width:980px;margin:0 auto;
    }
    footer{padding:26px 0;background:var(--rose);color:#fff;font-size:14px;text-align:center}

    .whats-float{
      position:fixed; right:20px; bottom:18px; z-index:99999;
      width:60px; height:60px; border-radius:50%;
      background:#25D366; box-shadow:0 12px 28px rgba(0,0,0,.18);
      display:flex; align-items:center; justify-content:center;
      border:1px solid rgba(255,255,255,.35);
    }
    .whats-float svg{width:30px; height:30px; fill:#fff}

    @media (max-width:640px){
      :root{ --topbar-h: 84px; }
      section{padding:46px 16px}
      .hero{padding:18px 16px 8px}
      .hero-card{padding:22px 14px 24px}
    }
  </style>
</head>

<body>
  <div class="topbar">
    <h1>O MAPA DA SUA DOR</h1>
  </div>

  <div class="page">

    <div class="hero">
      <div class="wrap">
        <div class="hero-card">
          <p class="lead">
            <strong>Descubra a raiz emocional do cansaço que você sente</strong><br>
            e o primeiro passo para se libertar dele.
          </p>

          <p class="lead" style="max-width:900px">
            <strong>Este não é um teste comum.</strong><br>
            É um espelho emocional para revelar onde você está se perdendo de si.
          </p>

          <div class="divider"></div>

          <div class="cta">
            <a href="#quiz" class="btn primary">Começar agora</a>
            <a href="#instrucao" class="btn ghost">Ver instrução</a>
          </div>

          <p class="hint"><span id="answeredCount">0</span>/5 respondidas</p>
        </div>
      </div>
    </div>

    <section id="instrucao">
      <div class="wrap">
        <h2 class="section-title">🧭 Instrução</h2>

        <div class="grid two" style="max-width:980px;margin:0 auto">
          <div class="card pink">
            <div class="pill">Leia com calma</div>
            <h3 class="grad-left">Antes de marcar</h3>
            <p>
              Leia cada pergunta com calma.<br>
              Marque a alternativa que mais se repete na sua vida <strong>hoje</strong>,
              não a que você gostaria que fosse verdade.
            </p>
          </div>

          <div class="card blue">
            <div class="pill">Como usar</div>
            <h3 class="grad-left">Resultado</h3>
            <p>
              No final, você vai ver qual letra apareceu mais vezes (A–E) e a sua
              <strong>dor dominante</strong>, com um <strong>primeiro passo</strong>.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section id="quiz">
      <div class="wrap">
        <h2 class="section-title">🧩 Quiz — 5 perguntas de diagnóstico</h2>

        <form id="quizForm" class="quiz" autocomplete="off">
          <!-- Q1 -->
          <div class="q">
            <div class="q-head">
              <p class="q-title">1️⃣ Quando você pensa na sua rotina, o que mais aparece?</p>
              <span class="q-chip">Pergunta 1/5</span>
            </div>
            <div class="options" role="radiogroup" aria-label="Pergunta 1">
              <label class="opt"><input type="radio" name="q1" value="A"><div><b>A)</b> <span>Sensação de estar sempre “devendo algo”</span></div></label>
              <label class="opt"><input type="radio" name="q1" value="B"><div><b>B)</b> <span>Cansaço mesmo quando descanso</span></div></label>
              <label class="opt"><input type="radio" name="q1" value="C"><div><b>C)</b> <span>Irritação por fazer mais do que os outros</span></div></label>
              <label class="opt"><input type="radio" name="q1" value="D"><div><b>D)</b> <span>Vazio, mesmo tendo conquistas</span></div></label>
              <label class="opt"><input type="radio" name="q1" value="E"><div><b>E)</b> <span>Medo constante de errar ou decepcionar</span></div></label>
            </div>
          </div>

          <!-- Q2 -->
          <div class="q">
            <div class="q-head">
              <p class="q-title">2️⃣ Em momentos de conflito, você costuma:</p>
              <span class="q-chip">Pergunta 2/5</span>
            </div>
            <div class="options" role="radiogroup" aria-label="Pergunta 2">
              <label class="opt"><input type="radio" name="q2" value="A"><div><b>A)</b> <span>Engolir o que sente para evitar problemas</span></div></label>
              <label class="opt"><input type="radio" name="q2" value="B"><div><b>B)</b> <span>Assumir tudo e resolver sozinho(a)</span></div></label>
              <label class="opt"><input type="radio" name="q2" value="C"><div><b>C)</b> <span>Explodir depois de acumular demais</span></div></label>
              <label class="opt"><input type="radio" name="q2" value="D"><div><b>D)</b> <span>Se afastar emocionalmente</span></div></label>
              <label class="opt"><input type="radio" name="q2" value="E"><div><b>E)</b> <span>Travar, não sabendo o que decidir</span></div></label>
            </div>
          </div>

          <!-- Q3 -->
          <div class="q">
            <div class="q-head">
              <p class="q-title">3️⃣ Qual frase mais combina com você hoje?</p>
              <span class="q-chip">Pergunta 3/5</span>
            </div>
            <div class="options" role="radiogroup" aria-label="Pergunta 3">
              <label class="opt"><input type="radio" name="q3" value="A"><div><b>A)</b> <span>“Se eu não fizer, ninguém faz”</span></div></label>
              <label class="opt"><input type="radio" name="q3" value="B"><div><b>B)</b> <span>“Estou cansado(a), mas não posso parar”</span></div></label>
              <label class="opt"><input type="radio" name="q3" value="C"><div><b>C)</b> <span>“Eu me cobro muito”</span></div></label>
              <label class="opt"><input type="radio" name="q3" value="D"><div><b>D)</b> <span>“Parece que falta algo, mas não sei o quê”</span></div></label>
              <label class="opt"><input type="radio" name="q3" value="E"><div><b>E)</b> <span>“Tenho medo de perder o controle”</span></div></label>
            </div>
          </div>

          <!-- Q4 -->
          <div class="q">
            <div class="q-head">
              <p class="q-title">4️⃣ Quando pensa em cuidar de você, o que surge?</p>
              <span class="q-chip">Pergunta 4/5</span>
            </div>
            <div class="options" role="radiogroup" aria-label="Pergunta 4">
              <label class="opt"><input type="radio" name="q4" value="A"><div><b>A)</b> <span>Culpa</span></div></label>
              <label class="opt"><input type="radio" name="q4" value="B"><div><b>B)</b> <span>Falta de tempo</span></div></label>
              <label class="opt"><input type="radio" name="q4" value="C"><div><b>C)</b> <span>Sensação de egoísmo</span></div></label>
              <label class="opt"><input type="radio" name="q4" value="D"><div><b>D)</b> <span>Confusão sobre o que quer</span></div></label>
              <label class="opt"><input type="radio" name="q4" value="E"><div><b>E)</b> <span>Medo de mexer em coisas antigas</span></div></label>
            </div>
          </div>

          <!-- Q5 -->
          <div class="q">
            <div class="q-head">
              <p class="q-title">5️⃣ O que mais drena sua energia hoje?</p>
              <span class="q-chip">Pergunta 5/5</span>
            </div>
            <div class="options" role="radiogroup" aria-label="Pergunta 5">
              <label class="opt"><input type="radio" name="q5" value="A"><div><b>A)</b> <span>Relações</span></div></label>
              <label class="opt"><input type="radio" name="q5" value="B"><div><b>B)</b> <span>Trabalho / dinheiro</span></div></label>
              <label class="opt"><input type="radio" name="q5" value="C"><div><b>C)</b> <span>Família</span></div></label>
              <label class="opt"><input type="radio" name="q5" value="D"><div><b>D)</b> <span>Expectativas dos outros</span></div></label>
              <label class="opt"><input type="radio" name="q5" value="E"><div><b>E)</b> <span>Pensamentos repetitivos</span></div></label>
            </div>
          </div>

          <div class="actions">
            <button type="button" class="btn primary" id="btnResult">Ver meu resultado</button>
            <button type="button" class="btn ghost" id="btnReset">Reiniciar</button>
            <div class="progress" id="helperText">Responda as 5 perguntas para ver o resultado.</div>
          </div>
        </form>

        <div id="result" aria-live="polite">
          <div class="result-box">
            <div class="result-top">
              <small>🔍 Resultado — identifique sua dor dominante</small>
              <h3 id="resultTitle">Sua dor dominante</h3>
            </div>
            <div class="result-body">
              <p id="resultText"></p>
              <div class="first-step" id="resultStep"></div>

              <div class="cta" style="margin-top:16px">
                <!-- ✅ ALTERAÇÃO 1: TEXTO DO BOTÃO -->
                <a class="btn primary" id="whatsBtn" target="_blank" rel="noopener">
                  Clique aqui para saber como dar esse primeiro passo.
                </a>
                <a class="btn ghost" href="#quiz">Refazer o quiz</a>
              </div>

              <p class="hint" style="margin-top:12px">
                <strong>O cansaço não é fraqueza.</strong> Ele é um pedido de reorganização interna.<br>
                Quando a raiz é vista, o corpo para de gritar.
              </p>
            </div>
          </div>
        </div>

      </div>
    </section>

    <section id="cta" style="padding:32px 20px;border-bottom:0">
      <div class="wrap">
        <div class="footer-cta">
          <div>
            <h3 style="margin:6px 0 0;font-size:22px;color:var(--ink)">
              Quer ir mais fundo e entender a origem real dessa dor na sua história?
            </h3>
            <p style="margin-top:8px">
              Me chama no WhatsApp para uma <strong>Sessão Diagnóstico Gratuita</strong>.<br>
              Vamos olhar isso com clareza, respeito e profundidade.
            </p>
          </div>
          <a id="ctaWhats" class="btn primary" target="_blank" rel="noopener">Chamar no WhatsApp</a>
        </div>
      </div>
    </section>

    <footer>
      © O Mapa da Sua Dor. Todos os direitos reservados.
    </footer>

  </div>

  <a class="whats-float" id="whatsFloat" target="_blank" rel="noopener" aria-label="Falar no WhatsApp">
    <span class="sr-only">Falar no WhatsApp</span>
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/>
    </svg>
  </a>

  <script>
    const WHATS_NUMBER = "5549998110445";

    const RESULTS = {
      A: {
        title: "🔹 MAIORIA A — DOR DA CULPA",
        text: "Você aprendeu a carregar pesos que não são seus. Seu cansaço vem de assumir responsabilidades emocionais demais.",
        step: "👉 Primeiro passo: devolver o que não te pertence."
      },
      B: {
        title: "🔹 MAIORIA B — DOR DA SOBRECARGA",
        text: "Você vive no modo sobrevivência. Não falta força — falta sustentação emocional.",
        step: "👉 Primeiro passo: sair do papel de quem sustenta tudo sozinho(a)."
      },
      C: {
        title: "🔹 MAIORIA C — DOR DA RAIVA CONTIDA",
        text: "Você faz mais do que pode e menos do que merece. A raiva não expressa vira exaustão.",
        step: "👉 Primeiro passo: reconhecer seus limites sem se culpar."
      },
      D: {
        title: "🔹 MAIORIA D — DOR DO VAZIO",
        text: "Você conquistou coisas, mas se desconectou de si. O cansaço aqui é existencial, não físico.",
        step: "👉 Primeiro passo: resgatar sentido e pertencimento."
      },
      E: {
        title: "🔹 MAIORIA E — DOR DO CONTROLE E DO MEDO",
        text: "Você tenta prever tudo para não sofrer. Isso consome energia vital.",
        step: "👉 Primeiro passo: aprender a confiar e soltar o excesso de controle."
      }
    };

    const $ = (s, el=document) => el.querySelector(s);
    const $$ = (s, el=document) => Array.from(el.querySelectorAll(s));

    const form = $("#quizForm");
    const answeredCountEl = $("#answeredCount");
    const helperText = $("#helperText");

    const resultWrap = $("#result");
    const resultTitle = $("#resultTitle");
    const resultText = $("#resultText");
    const resultStep = $("#resultStep");

    const btnResult = $("#btnResult");
    const btnReset = $("#btnReset");

    const ctaWhats = $("#ctaWhats");
    const whatsFloat = $("#whatsFloat");
    const whatsBtn = $("#whatsBtn");

    // ✅ ALTERAÇÃO 2: manter CTA/float com mensagem padrão,
    // e deixar o whatsBtn (resultado) com mensagem especial: resultado + "quero saber como dar o primeiro passo".
    function setWhatsLinks(extraText=""){
      const base = `https://wa.me/${WHATS_NUMBER}`;
      const msgDefault = "Oi! Fiz o quiz O Mapa da Sua Dor e quero uma Sessão Diagnóstico Gratuita.";
      const msg = encodeURIComponent(extraText ? `${msgDefault}\n\nMeu resultado: ${extraText}` : msgDefault);

      // Mantém como estava nos outros botões
      ctaWhats.href = `${base}?text=${msg}`;
      whatsFloat.href = `${base}?text=${msg}`;

      // Somente o botão do resultado envia: resultado + "quero saber como dar o primeiro passo"
      const msgFirstStep = encodeURIComponent(
        extraText
          ? `Meu resultado: ${extraText}\nQuero saber como dar o primeiro passo.`
          : `Quero saber como dar o primeiro passo.`
      );
      whatsBtn.href = `${base}?text=${msgFirstStep}`;
    }
    setWhatsLinks("");

    function countAnswered(){
      let count = 0;
      for(let i=1;i<=5;i++){
        if(form.querySelector(`input[name="q${i}"]:checked`)) count++;
      }
      answeredCountEl.textContent = String(count);
      helperText.textContent = (count === 5)
        ? "Tudo pronto! Clique em “Ver meu resultado”."
        : `Faltam ${5-count} pergunta(s) para completar.`;
      return count;
    }

    form.addEventListener("change", () => {
      countAnswered();
      $$(".options").forEach(group => {
        $$(".opt", group).forEach(opt => opt.style.borderColor = "var(--line)");
        const checked = group.querySelector("input:checked");
        if(checked){
          const label = checked.closest(".opt");
          label.style.borderColor = "#cfe7ff";
        }
      });
    });

    function getWinnerLetter(answers){
      const counts = {A:0,B:0,C:0,D:0,E:0};
      answers.forEach(l => counts[l]++);
      const max = Math.max(...Object.values(counts));
      const tied = Object.keys(counts).filter(k => counts[k] === max);
      if(tied.length === 1) return tied[0];
      for(const l of answers){
        if(tied.includes(l)) return l;
      }
      return tied[0];
    }

    function getAnswers(){
      const answers = [];
      for(let i=1;i<=5;i++){
        const sel = form.querySelector(`input[name="q${i}"]:checked`);
        if(!sel) return null;
        answers.push(sel.value);
      }
      return answers;
    }

    function showResult(){
      const answered = countAnswered();
      if(answered < 5){
        resultWrap.style.display = "none";
        helperText.style.color = "var(--warn)";
        setTimeout(()=> helperText.style.color = "var(--soft)", 1200);
        for(let i=1;i<=5;i++){
          if(!form.querySelector(`input[name="q${i}"]:checked`)){
            const first = form.querySelector(`input[name="q${i}"]`);
            first && first.focus();
            break;
          }
        }
        return;
      }

      const answers = getAnswers();
      const winner = getWinnerLetter(answers);
      const res = RESULTS[winner];

      resultTitle.textContent = res.title;
      resultText.textContent = res.text;
      resultStep.textContent = res.step;

      // Atualiza links (CTA/Float com padrão; botão do resultado com mensagem especial)
      setWhatsLinks(res.title);

      resultWrap.style.display = "block";
      resultWrap.scrollIntoView({behavior:"smooth", block:"start"});
    }

    function resetAll(){
      form.reset();
      resultWrap.style.display = "none";
      helperText.textContent = "Responda as 5 perguntas para ver o resultado.";
      helperText.style.color = "var(--soft)";
      answeredCountEl.textContent = "0";
      setWhatsLinks("");
      $$(".opt").forEach(opt => opt.style.borderColor = "var(--line)");
      $("#quiz").scrollIntoView({behavior:"smooth", block:"start"});
    }

    btnResult.addEventListener("click", showResult);
    btnReset.addEventListener("click", resetAll);

    countAnswered();
  </script>
</body>
</html>
