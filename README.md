# kafka

https://www.cnblogs.com/zhouj850/p/15630101.html


server properties
authorizer.class.name=kafka.security.auth.SimpleAclAuthorizer
super.users=User:admin
port=9092
allow.everyone.if.no.acl.found=false
advertised.port=9092
security.inter.broker.protocol=SASL_PLAINTEXT
sasl.mechanism.inter.broker.protocol=PLAIN
sasl.enabled.mechanisms=PLAIN


consumer properties
bootstrap.servers=localhost:9092
group.id=test-consumer-groupa
security.protocol=SASL_PLAINTEXT
sasl.mechanism=PLAIN




