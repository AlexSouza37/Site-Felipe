# Site-Felipe

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Neurodiversidade — Informação acessível</title>
  <style>
    :root{
      --bg:#ffffff;
      --text:#0b1a2b;
      --accent:#0b7b8f;
      --muted:#4a4a4a;
      --max-width:900px;
      --base-font:18px; /* default base */
      --line:1.6;
    }
    /* Basic reset */
    *{box-sizing:border-box}
    html{font-size:16px}
    body{
      margin:0;
      font-family: 'Lexend', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
      background:var(--bg);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:var(--line);
    }

    /* Container */
    .wrap{max-width:var(--max-width);margin:24px auto;padding:20px}

    header{display:flex;gap:16px;align-items:center;justify-content:space-between}
    h1{font-size:clamp(1.6rem, 2.4vw, 2.2rem);margin:0}
    p.lead{font-size:clamp(1rem,1.4vw,1.1rem);color:var(--muted)}

    /* Controls for personalization */
    .controls{display:flex;gap:8px;flex-wrap:wrap}
    .control{display:flex;gap:6px;align-items:center}
    button,select{font-size:1rem;padding:8px 10px;border-radius:8px;border:1px solid #d0d7dc;background:transparent}

    /* Accessible content blocks */
    main{margin-top:18px}
    section.card{background:rgba(11,123,143,0.04);padding:16px;border-radius:12px;margin-bottom:12px}
    h2{font-size:1.25rem;margin:0 0 8px}
    ul{padding-left:1.1rem}
    li{margin:8px 0}

    /* Quiz styling */
    .quiz{margin-top:20px;padding:16px;border-radius:12px;background:#f7f9fb}
    .quiz h3{margin-top:0}
    .q{margin-bottom:14px;padding:10px;border-radius:8px}
    .options{display:flex;flex-direction:column;gap:8px}
    label.option{display:flex;align-items:center;gap:10px;padding:8px;border-radius:8px;border:1px solid #e3e7ea;cursor:pointer}
    input[type="radio"]{accent-color:var(--accent);width:18px;height:18px}
    .result{margin-top:12px;font-weight:600}

    /* Focus outlines & big hit targets */
    :focus{outline:3px solid #ffd54f;outline-offset:3px}
    button,select,label.option{min-height:44px}

    /* Contrast theme */
    .high-contrast{--bg:#000000;--text:#ffffff;--accent:#ffd54f}

    /* Dyslexia friendly: heavier letterforms and larger spacing */
    .dyslexia{font-family: 'OpenDyslexic', 'Lexend', system-ui, Arial, sans-serif;letter-spacing:0.02em}

    /* Reduced motion */
    @media (prefers-reduced-motion:reduce){*{transition:none!important}}

    /* Responsive */
    @media(min-width:720px){header{gap:24px}}

    /* Small helper */
    .muted{color:var(--muted);font-size:0.95rem}

    footer{margin-top:28px;padding-top:12px;border-top:1px dashed #dfe7eb;color:var(--muted);font-size:0.95rem}
  </style>
</head>
<body>
  <a class="skip" href="#maincontent" style="position:absolute;left:-999px;top:auto;">Ir para o conteúdo</a>
  <div class="wrap" id="page">
    <header>
      <div>
        <h1>Neurodiversidade — Informação clara e adaptada</h1>
        <p class="lead">Site criado e adaptado para pesseas eurodivergentes.</p>
      </div>
      <div class="controls" aria-hidden="false" role="group" aria-label="Controles de acessibilidade">
        <div class="control">
          <label for="fontSize">Tamanho da letra</label>
          <select id="fontSize" aria-label="Ajustar tamanho da letra">
            <option value="16">Padrão</option>
            <option value="18" selected>Maior</option>
            <option value="20">Grande</option>
            <option value="22">Muito grande</option>
          </select>
        </div>
        <div class="control">
          <label for="lineHeight">Espaçamento</label>
          <select id="lineHeight" aria-label="Ajustar espaçamento entre linhas">
            <option value="1.4">Padrão</option>
            <option value="1.6" selected>Maior</option>
            <option value="1.9">Muito maior</option>
          </select>
        </div>
        <div class="control">
          <button id="toggleContrast" aria-pressed="false">Alto contraste</button>
        </div>
        <div class="control">
          <button id="toggleDys" aria-pressed="false">Fonte disléxica</button>
        </div>
      </div>
    </header>

    <main id="maincontent">
      <section class="card" aria-labelledby="o-que-e">
        <h2 id="o-que-e">O que é neurodiversidade?</h2>
        <p>Neurodiversidade é a ideia de que diferenças neurológicas — como autismo, TDAH, dislexia, discalculia e outras — fazem parte da variação natural do cérebro humano. Não são doenças a serem "corrigidas", mas formas diferentes de pensar, aprender e perceber o mundo.</p>
      </section>

      <section class="card" aria-labelledby="caracteristicas">
        <h2 id="caracteristicas">Características comuns</h2>
        <ul>
          <li>Variação na forma de atenção e foco (ex.: TDAH).</li>
          <li>Diferenças sensoriais — hipersensibilidade ou hipossensibilidade a luz, som, toque.</li>
          <li>Padrões repetitivos e interesses intensos (comum no autismo).</li>
          <li>Dificuldades com leitura ou escrita (dislexia) ou com números (discalculia).</li>
          <li>Forças específicas, como criatividade, memória de detalhes e pensamento visual.</li>
        </ul>
      </section>

      <section class="card" aria-labelledby="boas-praticas">
        <h2 id="boas-praticas">Como apoiar — boas práticas</h2>
        <p>Pequenas mudanças no ambiente escolar, no trabalho ou em casa fazem grande diferença:</p>
        <ul>
          <li>Oferecer instruções claras e em passos curtos.</li>
          <li>Permitir pausas sensoriais e ambientes com menos estímulos.</li>
          <li>Usar texto com espaçamento maior e fontes legíveis.</li>
          <li>Fornecer alternativas (áudio, vídeo, imagens) ao texto escrito.</li>
          <li>Aceitar diferentes maneiras de completar tarefas e demonstrar conhecimento.</li>
        </ul>
      </section>

      <section class="card" aria-labelledby="linguagem">
        <h2 id="linguagem">Linguagem e respeito</h2>
        <p>Use linguagem que respeite a pessoa. Pergunte como ela prefere ser chamada (por exemplo, "pessoa autista" ou "autista"). Evite termos ofensivos e não trate a neurodivergência como algo a ser "corrigido".</p>
      </section>

      <section class="quiz" aria-labelledby="quiz-title">
        <h3 id="quiz-title">Quiz — revise o que leu</h3>
        <form id="quizForm">

          <div class="q" role="group" aria-labelledby="q1">
            <div id="q1"><strong>1.</strong> O que significa "neurodiversidade"?</div>
            <div class="options">
              <label class="option"><input type="radio" name="q1" value="a"> Uma doença mental.</label>
              <label class="option"><input type="radio" name="q1" value="b"> Variação natural do cérebro humano.</label>
              <label class="option"><input type="radio" name="q1" value="c"> Um tipo de educação especial.</label>
              <label class="option"><input type="radio" name="q1" value="d"> Um transtorno contagioso.</label>
            </div>
          </div>

          <div class="q" role="group" aria-labelledby="q2">
            <div id="q2"><strong>2.</strong> Qual destas é uma característica que pode aparecer na neurodivergência?</div>
            <div class="options">
              <label class="option"><input type="radio" name="q2" value="a"> Hipersensibilidade sensorial.</label>
              <label class="option"><input type="radio" name="q2" value="b"> Imunidade a doenças.</label>
              <label class="option"><input type="radio" name="q2" value="c"> Supervelocidade física.</label>
              <label class="option"><input type="radio" name="q2" value="d"> Incapacidade de aprender.</label>
            </div>
          </div>

          <div class="q" role="group" aria-labelledby="q3">
            <div id="q3"><strong>3.</strong> O que é uma boa prática para apoiar pessoas neurodivergentes?</div>
            <div class="options">
              <label class="option"><input type="radio" name="q3" value="a"> Oferecer instruções claras e em passos curtos.</label>
              <label class="option"><input type="radio" name="q3" value="b"> Forçar horários rígidos sem explicação.</label>
              <label class="option"><input type="radio" name="q3" value="c"> Ignorar preferências sensoriais.</label>
              <label class="option"><input type="radio" name="q3" value="d"> Usar linguagem ofensiva para "corrigir" comportamento.</label>
            </div>
          </div>

          <div class="q" role="group" aria-labelledby="q4">
            <div id="q4"><strong>4.</strong> Qual afirmação sobre linguagem é correta?</div>
            <div class="options">
              <label class="option"><input type="radio" name="q4" value="a"> Sempre use termos médicos apenas.
              </label>
              <label class="option"><input type="radio" name="q4" value="b"> Pergunte a pessoa como ela prefere ser chamada.</label>
              <label class="option"><input type="radio" name="q4" value="c"> Evite perguntar e supor preferências.</label>
              <label class="option"><input type="radio" name="q4" value="d"> Use apelidos sem consentimento.</label>
            </div>
          </div>

          <div class="q" role="group" aria-labelledby="q5">
            <div id="q5"><strong>5.</strong> Quais alternativas ao texto podem ajudar na compreensão?</div>
            <div class="options">
              <label class="option"><input type="radio" name="q5" value="a"> Áudio e imagens.</label>
              <label class="option"><input type="radio" name="q5" value="b"> Apenas textos longos sem imagens.</label>
              <label class="option"><input type="radio" name="q5" value="c"> Somente diagramas técnicos sem explicação.</label>
              <label class="option"><input type="radio" name="q5" value="d"> Textos em letra de mão ilegível.</label>
            </div>
          </div>

          <div style="display:flex;gap:8px;align-items:center;margin-top:8px;">
            <button type="button" id="checkBtn">Enviar respostas</button>
            <button type="button" id="resetBtn">Limpar</button>
            <div id="score" class="result" aria-live="polite"></div>
          </div>

        </form>
      </section>

      <footer>
        <div>Este site é um material informativo e educativo. Para suporte individualizado, procure profissionais qualificados.</div>
      </footer>
    </main>
  </div>

  <script>
    // Accessibility controls
    const page = document.getElementById('page');
    const fontSizeSel = document.getElementById('fontSize');
    const lineSel = document.getElementById('lineHeight');
    const toggleContrast = document.getElementById('toggleContrast');
    const toggleDys = document.getElementById('toggleDys');

    function applySettings(){
      const fs = fontSizeSel.value;
      document.documentElement.style.setProperty('--base-font', fs + 'px');
      document.documentElement.style.fontSize = (fs/16) + 'rem';
      document.documentElement.style.setProperty('--line', lineSel.value);
    }
    fontSizeSel.addEventListener('change',applySettings);
    lineSel.addEventListener('change',applySettings);
    applySettings();

    toggleContrast.addEventListener('click', ()=>{
      const pressed = toggleContrast.getAttribute('aria-pressed') === 'true';
      toggleContrast.setAttribute('aria-pressed', String(!pressed));
      page.classList.toggle('high-contrast', !pressed);
    });

    toggleDys.addEventListener('click', ()=>{
      const pressed = toggleDys.getAttribute('aria-pressed') === 'true';
      toggleDys.setAttribute('aria-pressed', String(!pressed));
      page.classList.toggle('dyslexia', !pressed);
      // Note: to fully use OpenDyslexic you must have the font installed or include it.
    });

    // Quiz logic
    const answers = {q1:'b', q2:'a', q3:'a', q4:'b', q5:'a'};
    const checkBtn = document.getElementById('checkBtn');
    const resetBtn = document.getElementById('resetBtn');
    const scoreEl = document.getElementById('score');

    function grade(){
      const form = document.getElementById('quizForm');
      let correct = 0;
      let total = 0;
      for(const k in answers){
        total++;
        const val = (form.elements[k] && form.elements[k].value) || '';
        if(val === answers[k]) correct++;
      }
      scoreEl.textContent = `Você acertou ${correct} de ${total} perguntas.`;
      // Provide brief feedback for each question
      // For screen readers, add descriptions
      scoreEl.setAttribute('role','status');
    }
    checkBtn.addEventListener('click', grade);
    resetBtn.addEventListener('click', ()=>{
      document.getElementById('quizForm').reset();
      scoreEl.textContent = '';
    });

    // Keyboard-friendly: allow Enter to submit when on a radio
    document.getElementById('quizForm').addEventListener('keydown', (e)=>{
      if(e.key === 'Enter'){
        e.preventDefault();
        grade();
      }
    });
  </script>
</body>
</html>
