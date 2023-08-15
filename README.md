https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task_definition_parameters.html#container_definitions

essential - others stop if container marked as essential, atleast 1 has to essential
hostname - example http://client
hostname is not required for nginx container in this case as no other service is reaching out to it

links - unidirectional
