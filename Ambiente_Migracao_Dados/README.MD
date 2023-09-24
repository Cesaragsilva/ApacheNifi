# Como rodar?

1 - Faça o pull do repositorio
2 - Acesse a pasta que contem o docker-compose e execute

        docker-compose up -d

3 - Acesse no browser: http://localhost/nifi

4 - Clique com o botão direito e no apache nifi e escolha Upload Template

5 - Faça Upload do arquivo localizado na pasta: Process-Group/DataMigrationRDS.xml

6 - Clique no botão Template e escolha a template que acabou de fazer o upload

7 - Clique com o botão direto no process group criado e escolha Configure

8 - Clique em Controller Services

9 - Configure a password para a coneão dos bancos Antigo e Novo e ative-os

10 - Ative o JsonRecordSetWritter

11 - Execute o start em tabela por tabela (Mais controlado)