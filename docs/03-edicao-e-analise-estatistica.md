<div style="display: flex; justify-content: flex-end; align-items: center; gap: 8px; margin: 10px 0;">
 <span style="font-size: 14px; color: #555; font-weight: bold;">Tamanho do texto:</span>
 <button onclick="diminuirFonte()" title="Diminuir texto" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A-</button>
 <button onclick="resetarFonte()" title="Tamanho normal" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A</button>
 <button onclick="aumentarFonte()" title="Aumentar texto" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A+</button>
 
 <button onclick="window.print()" style="background-color: #0056b3; color: white; padding: 6px 16px; border: none; border-radius: 5px; font-size: 14px; cursor: pointer; box-shadow: 0 2px 4px rgba(0,0,0,0.2); margin-left: 10px;">
 🖨️ Imprimir ou baixar esta página
 </button>
</div>

# EDIÇÃO DE ITENS E ANÁLISE ESTATÍSTICA

**Passo 11:** Caso deseje alterar a pesquisa, clique em **“Editar item”** (ícone de lápis) ou **“Excluir Itens”** (ícone de lixeira vermelha) na coluna “Ações”.

![Opções de edição e exclusão de itens](Imagens/PPLite-9.png)

**Passo 12:** Após clicar em **“Editar item”**, abrirá a tela de edição. No topo da página, o sistema exibe as informações oficiais do catálogo do sistema Compras.gov.br (CATMAT para materiais ou CATSER para serviços) a respeito do item selecionado:

* **Descrição do Item:** Mostra o código e a descrição padronizada (*Ex.: 500075 - Caneta Esferográfica Material: Madeira*).
* **Quantidade e Unidade de Fornecimento:** Indica a quantidade estipulada para a contratação e como o item é fornecido (*Ex.: Caixa 50 Unidade*).

![Informações oficiais do item no catálogo](Imagens/PPLite-11.png)

**Passo 13:** Faça as alterações necessárias e clique em **“Aplicar”**. O sistema confirma a atualização das unidades de fornecimento ou quantidades, alertando que as cotações para aquele item serão atualizadas.

![Tela de aplicação das alterações](Imagens/Screenshot_25.jpg)

**Passo 14:** Confirme a alteração do item.

![Confirmação da alteração do item](Imagens/Screenshot_24.jpg)

Pronto, a cotação para aquele item foi atualizada. Para atualizar os demais itens, basta seguir novamente as instruções dos Passos 11 e 12.

---

## Indicadores e Gestão de Amostras

O Pesquisa de Preços Lite exibe os seguintes indicadores em tempo real:

![Painel de indicadores e estatísticas](Imagens/Screenshot_22.jpg)

* **Métodos de Cálculo:** Permite visualizar e alternar o critério de obtenção do preço estimado entre **Menor Preço**, **Média** ou **Mediana**. O método selecionado influenciará diretamente no valor de referência calculado pelo sistema.
* **Painel de Controle Estatístico:** Localizado à direita, apresenta o Coeficiente de Variação, o Desvio Padrão e o Maior Preço encontrado na amostra, servindo de parâmetro para analisar a homogeneidade e a segurança dos dados.

O Pesquisa de Preços Lite também mostra a relação de contratações públicas que foram selecionadas para compor os preços. Além disso, é possível detalhar as informações a respeito das compras na seção **“Lista de cotações realizadas para o item”**. Ao expandir o registro, o usuário tem acesso completo às informações da compra, incluindo o número do processo, a modalidade de contratação (*Ex.: Dispensa*), os dados do fornecedor, marca do produto e o critério de julgamento.

!!! warning "Atenção"
    **Gerenciamento das Cotações:**
    É possível gerenciar as contratações que compõem a pesquisa de preços na tabela exibida:
    
    * Na coluna **Compor**, é possível ativar ou desativar aquela cotação específica. Quando a opção estiver desativada, o valor é excluído dos cálculos estatísticos.
    * Na coluna **Ações**, o ícone de lixeira exclui permanentemente o registro da lista do item.

<br>
<div style="text-align: right; margin: 10px 0;">
 <button onclick="window.print()" style="background-color: #0056b3; color: white; padding: 10px 20px; border: none; border-radius: 5px; font-size: 16px; cursor: pointer; box-shadow: 0 2px 4px rgba(0,0,0,0.2);">
 🖨️ Imprimir ou baixar esta página
 </button>
</div>
