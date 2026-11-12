# Meu Kit de IA 🤖

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio 🚀

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

### Os Passos 👣

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

### O Que Tem no Kit 📂

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

### Os Frameworks das Aulas 🧠

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega 🏆

### Minha Tarefa Real 🎯

Escolhi automatizar a triagem e análise de logs de monitoramento de eventos de segurança e revisar scripts de automação em Python. Escolhi essa tarefa porque ela é repetitiva na minha rotina operacional e exige alta precisão, sendo ideal para aplicar IA com rigor técnico e supervisão humana.

### Meus Atalhos ⌨️

Adaptei dois atalhos principais do kit: a instrução fixa define o papel técnico e o formato de saída, enquanto o conteúdo que muda a cada uso é o relatório de log bruto ou o trecho de código a ser auditado.

```text
Atue como um Analista de Segurança Eletrônica Sênior. Receba o relatório bruto de eventos e alarmes abaixo, filtre os falsos positivos recorrentes, agrupe as ocorrências por nível de severidade e gere um sumário executivo em tópicos destacando anomalias críticas que exigem verificação imediata.
```

```text
Atue como um Engenheiro de Software Sênior especializado em automação e segurança. Analise o script Python fornecido, identifique gargalos de desempenho, falhas no tratamento de exceções ou riscos de exposição de dados, dividindo as sugestões em Correções Críticas Obrigatórias e Melhorias Opcionais.
```

### Minha Delegação 📝

```text
OBJETIVO: Estruturar um script em Python para automatizar a leitura, limpeza e categorização semanal de logs de eventos de monitoramento, gerando um resumo consolidado para conferência operacional.
CONTEXTO: Trabalho na operação de central de monitoramento e preciso otimizar a triagem de eventos repetitivos, mantendo 100% de rastreabilidade sobre ocorrências reais.
RECURSOS: Estrutura de colunas padrão de exportação de eventos e ambiente Python local.
LIMITES: Não utilizar dados reais de clientes, endereços, senhas ou chaves de acesso. Utilizar apenas dados fictícios para testes. Não executar alterações em produção sem aprovação.
SUCESSO: Apresentar primeiro o plano detalhado de execução. Após minha validação, gerar o código comentado e pronto para testes.
```

### O Plano da IA 🗺️

<img width="1080" height="1028" alt="Image 1" src="https://github.com/user-attachments/assets/cd230fde-bf85-4813-bf13-0df50886d193" />

> Ajustei o escopo inicial para garantir que o script realizasse a validação de formato de arquivo antes de processar os dados, inserindo um checkpoint extra de tratamento de exceções.

### O Resultado ✅

<img width="1080" height="984" alt="Image 2" src="https://github.com/user-attachments/assets/539910a4-64d9-4c52-9d23-eba7ca9caeb0" />

> Conferi o código linha por linha, validei que nenhuma credencial ou dado real estava presente e testei a lógica em ambiente isolado antes de integrá-la às minhas rotinas de validação.

### Como Foi para Você 💡

> Estruturar o kit e delegar com critérios claros mudou completamente a forma como encaro tarefas repetitivas. Em vez de aceitar a primeira resposta da IA, usar o plano prévio e manter o comando humano garantiu total segurança e eficiência na automação.

### Long live and prosper! 🖖
