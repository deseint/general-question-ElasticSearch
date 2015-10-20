# general-question-ElasticSearch
In which directory must I put my JSON file in order to be parsed by ElasticSearch ?


Hello,


I would like to parse a JSON file with ElasticSearch.
In which directory must I put this file ?

Because when I execute this command:
POST  /eurogiciel/test/ --data-binary @test.json
or
POST  /eurogiciel/test/ -d @test.json



In my SENSE dashboard,I've got this error message :
{"error": "MapperParsingException[failed to parse]; nested:
ElasticsearchParseException[Failed to derive xcontent]; ",
   "status": 400}

NB: my test.json file contains :
{"title": "billy","amount": 5.7}

Thanks a lot for your advices.
Best regards
Sabine DESEINT
