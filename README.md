# dashboard
Repositório Entrevista programador

Os arquivos aqui disponibiizados requerem lumen para seu funcionamento.
Para isso estou deixando o acesso externo habilitado para testes até que se encerre o processo seletivo.

Script da table..

CREATE TABLE `dados` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `data` date NOT NULL,
  `hora` int(2) NOT NULL,
  `dia` int(2) NOT NULL,
  `mes` int(2) NOT NULL,
  `uf` char(2) DEFAULT NULL,
  `estado` varchar(50) DEFAULT NULL,
  `alo` int(11) DEFAULT NULL,
  `cpc` int(11) DEFAULT NULL,
  `cpca` int(11) DEFAULT NULL,
  `pp` int(11) DEFAULT NULL,
  `cliente_nao_esta` int(11) DEFAULT NULL,
  `cliente_nao_validou` int(11) DEFAULT NULL,
  `desconhece` int(11) DEFAULT NULL,
  `desconhece_divida` int(11) DEFAULT NULL,
  `falecido` int(11) DEFAULT NULL,
  `fone_mudo` int(11) DEFAULT NULL,
  `lig_perdida` int(11) DEFAULT NULL,
  `preventivo` int(11) DEFAULT NULL,
  `recado` int(11) DEFAULT NULL,
  `alega` int(11) DEFAULT NULL,
  `retorno_agendado` int(11) DEFAULT NULL,
  `dados_invalidos` int(11) DEFAULT NULL,
  `sem_interesse` int(11) DEFAULT NULL,
  `nao_tabulada` int(11) DEFAULT NULL,
  `retorno_indireto` int(11) DEFAULT NULL,
  `fraude` int(11) DEFAULT NULL,
  `ocupado` int(11) DEFAULT NULL,
  `recept` int(11) DEFAULT NULL,
  `processo_juridico` int(11) DEFAULT NULL,
  `contestacao` int(11) DEFAULT NULL,
  `valor` decimal(10,2) DEFAULT NULL,
  `tipo` varchar(50) DEFAULT NULL,
  `produto` varchar(50) DEFAULT NULL,
  PRIMARY KEY (`id`)
)

Alguns dados contidos no excel estavam nulos e os mesmos foram ignorados.


