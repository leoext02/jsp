CREATE TABLE cliente (
    id INT NOT NULL AUTO_INCREMENT,
    nome VARCHAR(45) NULL,
    sobrenome VARCHAR(45) NULL,
    login VARCHAR(45) NULL,
    senha VARCHAR(45) NULL,
    endereco VARCHAR(45) NULL,
    contato VARCHAR(45) NULL,
    PRIMARY KEY (id)
);

INSERT INTO cliente(nome,sobrenome,login,senha,endereco,contato)
VALUE ('Leonardo','costa','leokil',md5('teste'),'paranoa','61981650209');
