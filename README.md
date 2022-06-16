Tese do Doutorado Profissional CESAR School 
=================
<p align="center"><img src="images/banner-pesquisa-cesar-school.png"  width="400" height="255" align="middle"/></p>

Este modelo, adaptado a partir do template da [ICMC/USP](https://www.overleaf.com/latex/templates/modelo-de-teses-e-dissertacoes-icmc-slash-usp/cvqdvbnxjqts), visa atender as exigências dos Programas de Pós-Graduação da CESAR School. O presente template encontra-se aderente ao que preconiza a Associação Brasileira de Normas Técnicas (ABNT), todavia com algumas adaptações em relação aos estilos dos capítulos, capa e folhas de rostos.

O requisito básico para utilização da classe **_icmc_** é criar um documento desta classe com o comando
`\documentclass[@parameters]{icmc}` e ter, no diretório de trabalho, o arquivo *icmc.cls* presente. Entretanto, recomenda-se fortemente manter a estrutura de diretório inicial fornecida por este modelo. 

Para que o documento esteja em conformidade com as normas exigidas pelo programa de Pós-Graduação, o **projeto deve ser compilado utilizando *pdfLaTeX*** e versão **2016 (Overleaf v1) (Legacy)***. Para isso acesse o Menu do overleaf e parametrize o documento conforme imagem abaixo:
<p align="center"><img src="images/erro-compilação.png"  width="500" height="562" align="middle"/></p>

Os parâmetros possíveis utilizados pelo `\documentclass` são:
- **[qualificacao]** Exclusivamente para monografias de qualificação em geral;
- **[mestrado / doutorado]** Identifica o curso ao qual o aluno pertence, sendo utilizado apenas uma das duas opcões disponíveis. O valor padrão é **doutorado**;
- **[pre-defesa / pos-defesa]** Identifica a situação do documento (exceto para qualificação), sedo necessário apenas uma das duas opções. O valor padrão é **pos-defesa**;
- **[impressao]** Gera exclusivamente uma versão para impressão do documento;
- **[french, spanish, english, brazil]** Adiciona o idioma para correta hifenização correta no documento. Os idiomas bases para o modelo (português e inglês) não precisam ser declarados.
