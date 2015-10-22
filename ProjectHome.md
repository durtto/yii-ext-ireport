This extension was based on PHPJasperXML. Is in Beta

Requirements

iReport 3.7.4
TCPDF
Usage

Yii::import('application.ext.extensions.ireport.**');**

$AReport = new IReport('sample2.jrxml');

$AReport->parameters = array("parameter1"=>1);

$AReport->execute();

by Questor Sistemas