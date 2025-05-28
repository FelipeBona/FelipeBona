# Gerenciador de DXF - Excel Engenharia

Este projeto é uma suíte de ferramentas em Python com interface gráfica (Tkinter) para facilitar o trabalho com arquivos DXF e DWG na área de engenharia estrutural. O sistema foi criado para uso interno da Excel Engenharia, otimizando processos de análise, conversão, tratamento e geração de arquivos CAD e planilhas.

## Funcionalidades

### 1. Analisador de DXF
- Analisa arquivos DXF, listando layers, tipos de entidades e comandos presentes no arquivo.
- Exibe um resumo detalhado em uma janela interativa.

### 2. Escalador de DXF
- Permite escalar arquivos DXF individualmente ou em lote (pasta).
- O usuário define o fator de escala, útil para ajustar desenhos conforme diferentes padrões de projeto.

### 3. Esquema Vertical para DXF
- Gera um esquema vertical de pavimentos a partir de uma tabela (CSV exportado do S4).
- Permite destacar pavimentos específicos ou todos abaixo/acima do selecionado.
- Exporta o resultado em DXF, facilitando a visualização e documentação.

### 4. Excel para DXF
- Converte tabelas do Excel para o formato DXF, criando desenhos de tabelas prontos para uso em CAD.
- Permite configurar alinhamento, largura das células e cor da tabela.

### 5. Tratamento de DXF
- Automatiza operações comuns em arquivos DXF, como explodir blocos, apagar hachuras, converter círculos em arcos, entre outros.
- Permite configurar sequências personalizadas de operações ou usar um padrão recomendado.

### 6. Conversor DXF para DWG
- Converte arquivos DXF para DWG em diferentes versões, utilizando o ODA File Converter.
- Permite definir o estilo de texto para compatibilidade com diferentes softwares CAD.

### 7. Conversor DWG para DXF
- Converte arquivos DWG para DXF, facilitando a interoperabilidade entre diferentes plataformas CAD.

### 8. Conversor DXF para Excel - Cabos de Protensão
- Extrai informações de cabos de protensão (TENDON e ELONG) de arquivos DXF e gera uma planilha Excel.
- Útil para projetos que utilizam o ADAPT ou softwares similares.

---

## Observações

- O sistema utiliza notificações nativas do Windows 11 para informar o usuário sobre o andamento e conclusão dos processos.
- O código foi desenvolvido para uso interno e pode exigir ajustes para uso em outros ambientes.
- Algumas funcionalidades dependem de softwares externos, como o ODA File Converter.

---

## Créditos

Desenvolvido por Excel Engenharia - Todos os direitos reservados.

---

**Este projeto demonstra habilidades em automação de processos CAD, integração com Excel, manipulação de arquivos e desenvolvimento de interfaces gráficas em Python.**
