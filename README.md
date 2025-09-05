# Landing-
Inscrição curso técnico
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Curso Técnico - Inscrição</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      margin: 0;
      padding: 0;
      color: #fff;
    }
    .container {
      max-width: 480px;
      margin: 60px auto;
      background: #fff;
      border-radius: 12px;
      padding: 30px;
      color: #333;
      box-shadow: 0 0 25px rgba(0,0,0,0.2);
    }
    h1 {
      text-align: center;
      margin-bottom: 12px;
    }
    p {
      text-align: center;
      margin-bottom: 20px;
      color: #555;
    }
    input, select, button {
      width: 100%;
      padding: 14px;
      margin: 10px 0;
      font-size: 16px;
      border-radius: 8px;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }
    button {
      background-color: #2c5364;
      border: none;
      color: white;
      font-weight: 700;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #203a43;
    }
    .footer {
      text-align: center;
      margin-top: 30px;
      font-size: 14px;
      color: #ddd;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Inscreva-se no Curso Técnico</h1>
    <p>Preencha seus dados para garantir sua vaga.</p>

    <form action="https://formsubmit.co/luizam287%40gmail.com" method="POST">
      <input type="text" name="nome" placeholder="Seu nome completo" required />
      <input type="email" name="email" placeholder="Seu e-mail" required />
      <input type="tel" name="telefone" placeholder="Seu WhatsApp ou telefone" required />

      <select name="curso" required>
        <option value="">Escolha seu curso técnico</option>
        <option value="administracao">Administração</option>
        <option value="analises_clinicas">Análises Clínicas</option>
        <option value="recursos_humanos">Recursos Humanos</option>
        <option value="radiologia">Radiologia</option>
        <option value="contabilidade">Contabilidade</option>
        <option value="enfermagem">Enfermagem</option>
        <option value="logistica">Logística</option>
        <option value="seguranca_do_trabalho">Segurança do Trabalho</option>
        <option value="transacoes_imobiliarias">Transações Imobiliárias</option>
      </select>

      <!-- Configurações do FormSubmit -->
      <input type="hidden" name="_subject" value="Nova Inscrição no Curso Técnico" />
      <input type="hidden" name="_captcha" value="false" />
      <input type="hidden" name="_template" value="box" />
      <!-- Atualize para sua página de obrigado ou remova essa linha para usar padrão -->
      <input type="hidden" name="_next" value="https://seusite.com/obrigado.html" />

      <button type="submit">Quero Saber Mais</button>
    </form>
  </div>

  <div class="footer">
    © 2025 Instituto Técnico Nacional. Todos os direitos reservados.
  </div>
</body>
</html>
