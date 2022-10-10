# Criar site completo com 4 páginas.
<!-- ✅ -->
## ⬜️ Home
## ⬜️ Sobre
## ⬜️ Horário de atendimento
## ⬜️ Contato
#

## Página Principal
### ⬜️ Imagem no Header. 
### ⬜️ Em Content(centro da pg) uma breve descrição sobre a clínica.
### ⬜️ Menu e Footer padrões em todas as páginas.
#

## Sobre a clínica
### ⬜️ Imagem diferente no Header.
### ⬜️ Em Content um texto falando sobre a clínica.
### ⬜️ Menu e Footer padrões em todas as páginas.
#

## Horário de Atendimento
### ⬜️ Imagem diferente no Header.
### ⬜️ Em Content um pequeno texto falando sobre os serviços, e uma tabela de preços, onde cada linha é um serviço, com o preço de cada um de acordo com os dias da semana.
### ⬜️ Menu e Footer padrões em todas as páginas.

### HTML da tabela de horários:
<table border="1" style="width:auto;font-size:8px;">
	<thead>
		<tr>
			<th>Serviços</th>
			<th>Segunda a Sexta</th>
			<th>Sábados</th>
			<th>Feriados</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Clínica geral</td>
			<td>08h - 19h</td>
			<td>08h - 14h</td>
			<td>08h - 14h</td>
		</tr>
		<tr>
			<td>Psicologia</td>
			<td>08h - 19h</td>
			<td>08h - 14h</td>
			<td>08h - 14h</td>
		</tr>
		<tr>
			<td>Pediatria</td>
			<td>08h - 19h</td>
			<td>08h - 18h</td>
			<td>-</td>
		</tr>
		<tr>
			<td>Oftalmologia</td>
			<td>08h - 19h</td>
			<td>08h - 18h</td>
			<td>-</td>
		</tr>
	</tbody>
</table>

#

### HTML da tabela de preços com horários:
##### Como os dados de horário estão relacionados com os preços, decidi agrupar.
<table border="1" style="width:auto;font-size:8px;">
	<thead>
		<tr>
			<th>Serviços</th>
			<th>Segunda a Sexta</th>
            <th>Valor</th>
			<th>Sábados</th>
            <th>Valor</th>
			<th>Feriados</th>
            <th>Valor</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Clínica geral</td>
			<td>08h - 19h</td>
            <td>R$ 100</td>
			<td>08h - 14h</td>
            <td>R$ 120</td>
			<td>08h - 14h</td>
            <td>R$ 150</td>
		</tr>
		<tr>
			<td>Psicologia</td>
			<td>08h - 19h</td>
            <td>R$ 150</td>
			<td>08h - 14h</td>
            <td>R$ 170</td>
			<td>08h - 14h</td>
            <td>R$ 180</td>
		</tr>
		<tr>
			<td>Pediatria</td>
			<td>08h - 19h</td>
            <td>R$ 80</td>
			<td>08h - 18h</td>
            <td>R$ 90</td>
			<td>-</td>
            <td>-</td>
		</tr>
		<tr>
			<td>Oftalmologia</td>
			<td>08h - 19h</td>
            <td>R$ 100</td>
			<td>08h - 18h</td>
            <td>R$ 170</td>
			<td>-</td>
            <td>-</td>
		</tr>
	</tbody>
</table>

#
## Contato
### ⬜️ Imagem diferente no Header.
### Em Content deve ter: 
#### ⬜️ Os telefones de contato (celular e whatsapp)
#### ⬜️ Endereço completo da clínica
#### ⬜️ Um Iframe com o Google Maps apontando o endereço da clínica
#### ⬜️ Um formulário de contato com:
> Nome (type="text"), E-mail (type="email"), Assunto (type="text"), Mensagem (textarea).
#### ⬜️ Botões de enviar e limpar formulário.
#### ⬜️ Menu e Footer padrões em todas as páginas.
#
