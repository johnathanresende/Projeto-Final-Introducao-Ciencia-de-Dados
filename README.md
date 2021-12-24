<h1> Projeto Final Disciplina Introdução à Ciência de Dados/UnB </h1>

<p align="justify"> Esse projeto foi desenvolvido para a disciplina de <b>Introdução à Ciência de Dados</b> da Universidade de Brasília (UnB), no curso de Biblioteconomia, no ano de 2019. O objetivo era <b>coletar informações sobre os acervos digitais de bibliotecas estaduais brasileiras</b>, e assim averiguar quais Estados disponibilizavam documentos digitais e em quais formatos estes estavam disponíveis. Para atingir esse escopo, foram empregadas ferramentas como o <b>Excel</b>, <b>OpenRefine</b> e bibliotecas de extração e análise de dados da linguagem <b>Python</b>. </p>

<h2> Acerca da obtenção dos dados </h2>

<p align = "justify"> Para obter os dados, fez-se uma pesquisa dos sites de todas a bibliotecas estaduais brasileiras e de seus respectivos acervos digitais. Notou-se que a maioria das bibliotecas possuem algum tipo de site — seja blogs, páginas de Facebook ou domínios privados. No entanto, apenas uma <b>minoria dessas bibliotecas disponibilizava documentos digitais online</b>. </p> 

<p align = "justify">A seguinte tabela reúne as informações relativas aos sites, existência de acervos digitais em cada estado e os modos de extrair esses documentos:</p>


<div id="Pasta1_13894" align=center x:publishsource="Excel">

<table border=0 cellpadding=0 cellspacing=0 width=1302 style='border-collapse:
 collapse;table-layout:fixed;width:977pt' data-pm-slice="1 1 []"
 data-en-clipboard=true>
 <col width=228 style='mso-width-source:userset;mso-width-alt:8338;width:171pt'>
 <col width=300 style='mso-width-source:userset;mso-width-alt:10971;width:225pt'>
 <col width=243 style='mso-width-source:userset;mso-width-alt:8886;width:182pt'>
 <col width=246 style='mso-width-source:userset;mso-width-alt:8996;width:185pt'>
 <col width=285 style='mso-width-source:userset;mso-width-alt:10422;width:214pt'>
 <tr height=141 style='height:105.75pt'>
  <td height=141 class=xl6513894 width=228 style='height:105.75pt;width:171pt;
  padding-bottom:10px;padding-top:10px' data-colwidth=145>ESTADO</td>
  <td class=xl6513894 width=300 style='border-left:none;width:225pt;padding-bottom:
  10px;padding-top:10px' data-colwidth=277>BIBLIOTECA</td>
  <td class=xl6513894 width=243 style='border-left:none;width:182pt;padding-bottom:
  10px;padding-top:10px' data-colwidth=81>BIBLIO DIGITAL</td>
  <td class=xl6513894 width=246 style='border-left:none;width:185pt;padding-bottom:
  10px;padding-top:10px' data-colwidth=441>LINK</td>
  <td class=xl6513894 width=285 style='border-left:none;width:214pt;padding-bottom:
  10px;padding-top:10px' data-colwidth=291>POSSIBILIDADE DE EXTRAÇÃO E ANÁLISE</td>
 </tr>
 <tr height=121 style='height:90.75pt'>
  <td height=121 class=xl6413894 width=228 style='height:90.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Acre
  (AC)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Estadual de Rio Branco</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://bpeac.blogspot.com/" rev="en_rl_none">http://bpeac.blogspot.com/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=201 style='height:150.75pt'>
  <td height=201 class=xl6413894 width=228 style='height:150.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Alagoas
  (AL)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Estadual Graciliano Ramos</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://siabiclientes.com/bp-gracilianoramos/Telas/w_busca_rapida.php"
  rev="en_rl_none">http://siabiclientes.com/bp-gracilianoramos/Telas/w_busca_rapida.php</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=281 style='height:210.75pt'>
  <td height=281 class=xl6413894 width=228 style='height:210.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Amapá
  (AP)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Profª Elcy Lacerda</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="https://pt-br.facebook.com/pages/Biblioteca-P%C3%BAblica-Elcy-Lacerda/373556786023524"
  rev="en_rl_none">https://pt-br.facebook.com/pages/Biblioteca-P%C3%BAblica-Elcy-Lacerda/373556786023524</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=121 style='height:90.75pt'>
  <td height=121 class=xl6413894 width=228 style='height:90.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Amazonas
  (AM)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública do Amazonas</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>SIM</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="https://issuu.com/bibliovirtualsec" rev="en_rl_none">https://issuu.com/bibliovirtualsec</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Títulos
  em formato PDF.</td>
 </tr>
 <tr height=161 style='height:120.75pt'>
  <td height=161 class=xl6413894 width=228 style='height:120.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Bahia
  (BA)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Central do Estado da Bahia</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>SIM</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.bvconsueloponde.ba.gov.br/" rev="en_rl_none">http://www.bvconsueloponde.ba.gov.br/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Títulos
  em formato PDF e Estatísticas de visualizações</td>
 </tr>
 <tr height=261 style='height:195.75pt'>
  <td height=261 class=xl6413894 width=228 style='height:195.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Ceará
  (CE)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Governador Menezes Pimentel</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="https://pt.wikipedia.org/wiki/Biblioteca_P%C3%BAblica_Governador_Menezes_Pimentel"
  rev="en_rl_none">https://pt.wikipedia.org/wiki/Biblioteca_P%C3%BAblica_Governador_Menezes_Pimentel</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=141 style='height:105.75pt'>
  <td height=141 class=xl6413894 width=228 style='height:105.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Distrito
  Federal (DF)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Nacional de Brasília</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.bnb.df.gov.br/sophia/index.html" rev="en_rl_none">http://www.bnb.df.gov.br/sophia/index.html</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=121 style='height:90.75pt'>
  <td height=121 class=xl6413894 width=228 style='height:90.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Espírito
  Santo (ES)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública do Espírito Santo</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://bibtranscolbpes.es.gov.br/" rev="en_rl_none">http://bibtranscolbpes.es.gov.br/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=181 style='height:135.75pt'>
  <td height=181 class=xl6413894 width=228 style='height:135.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Goiás
  (GO)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Estadual Pio Vargas</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="https://pt.wikipedia.org/wiki/Biblioteca_Estadual_Pio_Vargas"
  rev="en_rl_none">https://pt.wikipedia.org/wiki/Biblioteca_Estadual_Pio_Vargas</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=181 style='height:135.75pt'>
  <td height=181 class=xl6413894 width=228 style='height:135.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Maranhão
  (MA)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Benedito Leite</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>SIM</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.cultura.ma.gov.br/portal/bpbl/acervodigital/"
  rev="en_rl_none">http://www.cultura.ma.gov.br/portal/bpbl/acervodigital/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Lista de
  documentos em PDF.</td>
 </tr>
 <tr height=181 style='height:135.75pt'>
  <td height=181 class=xl6413894 width=228 style='height:135.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Mato
  Grosso (MT)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Estadual Estevão de Mendonça</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.bibliotecapublica.mt.gov.br/" rev="en_rl_none">http://www.bibliotecapublica.mt.gov.br/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=221 style='height:165.75pt'>
  <td height=221 class=xl6413894 width=228 style='height:165.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Mato
  Grosso do Sul (MS)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Estadual Dr. Isaias Paim</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.fundacaodecultura.ms.gov.br/biblioteca-publica-isaias-paim/"
  rev="en_rl_none">http://www.fundacaodecultura.ms.gov.br/biblioteca-publica-isaias-paim/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=181 style='height:135.75pt'>
  <td height=181 class=xl6413894 width=228 style='height:135.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Minas
  Gerais (MG)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Estadual de Minas Gerais</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.bibliotecapublica.mg.gov.br/index.php/pt-br/"
  rev="en_rl_none">http://www.bibliotecapublica.mg.gov.br/index.php/pt-br/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=321 style='height:240.75pt'>
  <td height=321 class=xl6413894 width=228 style='height:240.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Pará
  (PA)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Arthur Vianna</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>SIM</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.fcp.pa.gov.br/consulta-do-acervo/acervo-bibliografico/consulta-do-acervo-da-biblioteca"
  rev="en_rl_none">http://www.fcp.pa.gov.br/consulta-do-acervo/acervo-bibliografico/consulta-do-acervo-da-biblioteca</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Obras
  digitalizadas</td>
 </tr>
 <tr height=161 style='height:120.75pt'>
  <td height=161 class=xl6413894 width=228 style='height:120.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Paraíba
  (PB)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Estadual Augusto dos Anjos</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://bibliotecas.cultura.gov.br/espaco/194/" rev="en_rl_none">http://bibliotecas.cultura.gov.br/espaco/194/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=101 style='height:75.75pt'>
  <td height=101 class=xl6413894 width=228 style='height:75.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Paraná
  (PR)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública do Paraná</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.bpp.pr.gov.br/" rev="en_rl_none">http://www.bpp.pr.gov.br/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=119 style='mso-height-source:userset;height:89.25pt'>
  <td rowspan=2 height=140 class=xl6713894 width=228 style='border-bottom:1.0pt solid #CCCCCC;
  height:105.0pt;border-top:none;width:171pt;padding-bottom:10px;padding-top:
  10px' data-colwidth=145>Pernambuco (PE)</td>
  <td rowspan=2 class=xl6713894 width=300 style='border-bottom:1.0pt solid #CCCCCC;
  border-top:none;width:225pt;padding-bottom:10px;padding-top:10px'
  data-colwidth=277>Biblioteca Pública do Estado de Pernambuco</td>
  <td rowspan=2 class=xl6713894 width=243 style='border-bottom:1.0pt solid #CCCCCC;
  border-top:none;width:182pt;padding-bottom:10px;padding-top:10px'
  data-colwidth=81>NÃO</td>
  <td rowspan=2 class=xl6913894 width=246 style='border-bottom:1.0pt solid #CCCCCC;
  border-top:none;width:185pt;padding-bottom:10px;padding-top:10px'
  data-colwidth=441><a href="http://www.biblioteca.pe.gov.br/" rev="en_rl_none">http://www.biblioteca.pe.gov.br/</a></td>
  <td rowspan=2 class=xl6713894 width=285 style='border-bottom:1.0pt solid #CCCCCC;
  border-top:none;width:214pt;padding-bottom:10px;padding-top:10px'
  data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=21 style='height:15.75pt'>
 </tr>
 <tr height=241 style='height:180.75pt'>
  <td height=241 class=xl6413894 width=228 style='height:180.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Piauí
  (PI)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Estadual Desembargador Cromwell de Carvalho</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="https://pt.wikipedia.org/wiki/Biblioteca_Estadual_do_Piau%C3%AD"
  rev="en_rl_none">https://pt.wikipedia.org/wiki/Biblioteca_Estadual_do_Piau%C3%AD</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=101 style='height:75.75pt'>
  <td height=101 class=xl6413894 width=228 style='height:75.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Rio
  de Janeiro (RJ)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Parque Estadual</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.bibliotecasparque.rj.gov.br/" rev="en_rl_none">www.bibliotecasparque.rj.gov.br</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=121 style='height:90.75pt'>
  <td height=121 class=xl6413894 width=228 style='height:90.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Rio
  Grande do Norte (RN)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Câmara Cascudo</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="https://bpcamaracascudo.webnode.com.br/" rev="en_rl_none">https://bpcamaracascudo.webnode.com.br/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=161 style='height:120.75pt'>
  <td height=161 class=xl6413894 width=228 style='height:120.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Rio
  Grande do Sul (RS)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública do Estado do Rio Grande do Sul</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.bibliotecapublica.rs.gov.br/" rev="en_rl_none">http://www.bibliotecapublica.rs.gov.br/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=321 style='height:240.75pt'>
  <td height=321 class=xl6413894 width=228 style='height:240.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Rondônia
  (RO)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Estadual Dr. José Pontes Pinto</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://www.rondonia.ro.gov.br/funcer/institucional/biblioteca-publica-estadual-doutor-jose-pontes-pinto/"
  rev="en_rl_none">http://www.rondonia.ro.gov.br/funcer/institucional/biblioteca-publica-estadual-doutor-jose-pontes-pinto/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=161 style='height:120.75pt'>
  <td height=161 class=xl6413894 width=228 style='height:120.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Roraima
  (RR)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública do Estado de Roraima</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6413894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441>-</td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=141 style='height:105.75pt'>
  <td height=141 class=xl6413894 width=228 style='height:105.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Santa
  Catarina (SC)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública de Santa Catarina</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>SIM</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://hemeroteca.ciasc.sc.gov.br/" rev="en_rl_none">http://hemeroteca.ciasc.sc.gov.br/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Hemeroteca
  virtual</td>
 </tr>
 <tr height=281 style='height:210.75pt'>
  <td height=281 class=xl6413894 width=228 style='height:210.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>São
  Paulo (SP)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  de São Paulo</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>SIM</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="https://bsp.org.br/" rev="en_rl_none">https://bsp.org.br/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Lista de
  livros digitais disponíveis para download em PDF, tabelas com metadados dos
  livros.</td>
 </tr>
 <tr height=161 style='height:120.75pt'>
  <td height=161 class=xl6413894 width=228 style='height:120.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Sergipe
  (SE)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Epifânio Dória</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6613894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441><a
  href="http://mapa.cultura.aracaju.se.gov.br/espaco/14146/" rev="en_rl_none">http://mapa.cultura.aracaju.se.gov.br/espaco/14146/</a></td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <tr height=121 style='height:90.75pt'>
  <td height=121 class=xl6413894 width=228 style='height:90.75pt;border-top:
  none;width:171pt;padding-bottom:10px;padding-top:10px' data-colwidth=145>Tocantins
  (TO)</td>
  <td class=xl6413894 width=300 style='border-top:none;border-left:none;
  width:225pt;padding-bottom:10px;padding-top:10px' data-colwidth=277>Biblioteca
  Pública Estadual Darcy Cardeal</td>
  <td class=xl6413894 width=243 style='border-top:none;border-left:none;
  width:182pt;padding-bottom:10px;padding-top:10px' data-colwidth=81>NÃO</td>
  <td class=xl6413894 width=246 style='border-top:none;border-left:none;
  width:185pt;padding-bottom:10px;padding-top:10px' data-colwidth=441>-</td>
  <td class=xl6413894 width=285 style='border-top:none;border-left:none;
  width:214pt;padding-bottom:10px;padding-top:10px' data-colwidth=291>Nenhuma</td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=228 style='width:171pt'></td>
  <td width=300 style='width:225pt'></td>
  <td width=243 style='width:182pt'></td>
  <td width=246 style='width:185pt'></td>
  <td width=285 style='width:214pt'></td>
 </tr>
 <![endif]>
</table>

</div>

<h3>Captura, Armazenamento e Tratamento dos Dados</h3>

<h4> Amazonas </h4>

<p align= "justify">O acervo da Biblioteca Virtual do Amazonas estava disposto da seguinte maneira:</p>

![image](https://user-images.githubusercontent.com/57017227/147302658-61300630-06e2-482d-a782-5806a410c768.png)

<p align= "justify">Para obter o nome de todas as obras, foi feita uma seleção manual de todos os documentos disponíveis na página. </p>

![image](https://user-images.githubusercontent.com/57017227/147302741-ed987c21-d012-4497-8bc7-92e076dc8b6d.png)

<p align= "justify">Ao colar os títulos em uma planilha do Excel, os dados ainda demandavam alguns processos de limpeza. De início, os dados vieram assim para o excel: </p>

![image](https://user-images.githubusercontent.com/57017227/147302836-bb2a4554-d086-4a37-823f-55b18cef32db.png)

<p align = "justify">Para eliminar tais sujeiras, o procedimento foi: 1) Localizar as palavras "Cover", "by" e "Published"; 2) Excluir as células selecionadas.</p>

![image](https://user-images.githubusercontent.com/57017227/147302961-430d1277-c465-49b4-a3b2-6db47a985fc4.png)

<p align = "justify">Após eliminar os dados indesejados, sobrou uma lista que continha somente o título da obra. O nome do autor, porém, requisitava um acesso arquivo por arquivo e, portanto, foi desconsiderado</p>

![image](https://user-images.githubusercontent.com/57017227/147303082-f5af26fa-5d03-4367-81bc-cb3e00a05ccf.png)

<p align = "justify">Após eliminar os dados indesejados, sobrou uma lista que continha somente o título da obra. O nome do autor, porém, requisitava um acesso arquivo por arquivo e, portanto, foi desconsiderado</p>

![image](https://user-images.githubusercontent.com/57017227/147303148-2d918185-ed8d-4bde-9a1f-bc610c72b204.png)

<h4>Bahia</h4>

