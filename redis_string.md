##nodejs set with EX PX NX XX
If with Redis 2.6.12 installed, use follow method

`$client->set('hello', 'world', 'NX', 'EX', 300, function(err, reply) {...});`

`$client->set(['hello', 'world', 'NX', 'EX', 300], function(err, reply) {...});`
