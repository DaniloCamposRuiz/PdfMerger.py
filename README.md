Ferramenta de Mesclagem de PDFs
Este é um script Python que mescla vários arquivos PDF em um único arquivo PDF final.

Pré-requisitos
Certifique-se de ter a biblioteca PyPDF2 instalada para usar a funcionalidade de mesclagem de PDFs.

Você pode instalar o pacote usando o seguinte comando:
pip install PyPDF2

Como usar:
Crie uma pasta chamada "arquivos" no mesmo diretório onde este script está localizado.
Coloque os arquivos PDF que deseja mesclar na pasta "arquivos".
Execute o script merge_pdfs.py.
O script percorrerá todos os arquivos na pasta "arquivos", identificará os arquivos com a extensão .pdf e os mesclará em um único arquivo PDF final chamado "PDF Final.pdf".
Certifique-se de ajustar o nome do arquivo de saída conforme suas necessidades.

Observações
Os arquivos PDF na pasta "arquivos" serão mesclados na ordem alfabética.
O script utiliza a biblioteca PyPDF2 para realizar a mesclagem. Certifique-se de que todos os arquivos PDF na pasta estejam em um formato compatível com essa biblioteca.
Lembre-se de que este é um script básico e pode não cobrir todos os cenários possíveis ao trabalhar com arquivos PDF. Adaptações adicionais podem ser necessárias para atender a casos específicos.

Nota: Este README é uma descrição geral do funcionamento do script. Certifique-se de personalizá-lo de acordo com suas necessidades e incluir qualquer informação adicional relevante.
