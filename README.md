# detector_yolo

Repositório contendo os códigos para desenvolvimento de um modelo detector de objetos na arquitetura YOLO.

É necessário salvar os pesos treinados no Google Drive para download com o comando gdown. Para salvar esses pesos, é só abrir o drive na sessão e utilizar o comando !cp para copiar os arquivos para uma pasta do drive.

Por segurança, os links do drive com os pesos originais foram removidos.

O notebook contém códigos para exportar imagens detectadas, um modelo treinado, e um arquivo csv com as coordenadas das bounding boxes dessas imagens. As bounding boxes estão no formato YOLO. 

O script da YOLO gera os arquivos de texto no formato YOLO com as coordenadas das bounding boxes, mas não inclui as notas de confiança. Uma solução não tão ideal é copiar os valores de nota de confiança de cada imagem detectada em cada arquivo de texto.
