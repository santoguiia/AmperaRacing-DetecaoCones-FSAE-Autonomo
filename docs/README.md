# Documentação para Download do Dataset de Identificação de Cones

Esta documentação fornece instruções detalhadas sobre como baixar o dataset utilizado nas redes neurais treinadas para identificação de cones. O dataset está disponível no Google Drive e pode ser acessado através do link fornecido.

## Pré-requisitos

Certifique-se de ter os seguintes itens instalados em seu ambiente:

- Um navegador da web para acessar o Google Drive.
- Espaço suficiente em disco para armazenar o dataset.

## Passos para Baixar o Dataset

1. **Acesse o Link do Google Drive:**
   - [Dataset de Identificação de Cones](https://drive.google.com/file/d/1eCevaY3ZScfCFb2HFV7YeOHel0WjJi9g/view?usp=sharing)
   - [Redes Neurais já treinadas](https://drive.google.com/drive/folders/1KwxyqjjileZHjT5nfLRKbbiU4tfxDKuV?usp=sharing)

2. **Visualize o Conteúdo do Drive:**
   - Ao acessar o link, você será direcionado para o Google Drive onde o dataset está armazenado. Visualize o conteúdo do drive para garantir que está acessando o dataset correto.

3. **Fazer Download do Dataset:**
   - Selecione os arquivos ou o diretório correspondente ao dataset de identificação de cones.
   - Clique com o botão direito do mouse e escolha a opção "Fazer download".
   - O Google Drive comprimirá os arquivos em um arquivo zip e começará a baixar automaticamente.

4. **Extração dos Arquivos:**
   - Após o download ser concluído, localize o arquivo zip em seu sistema.
   - Extraia os arquivos para a pasta desejada em seu ambiente local.

## Estrutura do Dataset

O dataset está estruturado da seguinte forma:

```
|-- dataset_identificacao_cones
    |-- test
        |-- images
            |-- ...
        |-- labels
            |-- ...
    |-- train
        |-- images
            |-- ...
        |-- labels
            |-- ...
    |-- valid
        |-- images
            |-- ...
        |-- labels
            |-- ...
    |-- data.yaml
    |-- README.roboflow.txt
```

- A pasta `images` contém as imagens do dataset.
- A pasta `labels` contém os arquivos txt com a lozalização de cada cones na imagem.
- O arquivo `data.yaml` fornece informações de classificação dos cones.
- O arquivo `README.md` fornece informações adicionais sobre o dataset, como a fonte dos dados e quaisquer instruções especiais.

## Considerações Finais

Após seguir esses passos, você terá o dataset de identificação de cones disponível localmente em seu sistema. Certifique-se de ler o arquivo `README.md` para obter informações adicionais sobre o dataset.

Se precisar de suporte adicional ou tiver dúvidas, sinta-se à vontade para abrir uma issue neste repositório do GitHub.

Obrigado por usar nosso dataset!